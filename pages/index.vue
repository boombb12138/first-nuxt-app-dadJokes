<template>
  <h2>Welcome to the best app</h2>
</template>

<script>
export default {
  layout: "defalut",
  head() {
    return {
      title: "Welcome to Dad jokes",
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Best place for dad jokes",
        },
      ],
    };
  },
};
</script>
<style scoped>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: grey;
}
</style>
