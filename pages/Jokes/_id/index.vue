<template>
  <div>
    <nuxt-link to="/jokes"><button>Back to Jokes page</button></nuxt-link>
    <h2>{{ joke }}</h2>
    <hr />
    <small> Joke ID:{{ $route.params.id }} </small>
  </div>
</template>

<script>
import axios from "axios";

export default {
  data() {
    return {
      joke: {},
    };
  },
  async created() {
    const config = {
      headers: {
        Accept: "application/json",
      },
    };
    try {
      const res = await axios.get(
        `https://icanhazdadjoke.com/j/${this.$route.params.id}`,
        config
      );
      this.joke = res.data.joke;
      console.log(res.data);
    } catch (error) {
      console.log(error);
    }
  },
};
</script>
<style scoped></style>
