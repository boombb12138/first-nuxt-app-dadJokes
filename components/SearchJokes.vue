<template>
  <!-- prevent是preventDefault,阻止标签默认行为， -->
  <!-- submit点击默认行为是提交表单，这里并不需要它提交,只需要执行addMemo方法 -->
  <form @submit.prevent="onSubmit">
    <input type="text" v-model="text" placeholder="Search Jokes.." />
    <input type="submit" value="Search Jokes" />
  </form>
</template>

<script>
export default {
  name: "SearchJokes",
  data() {
    return {
      text: "",
    };
  },
  methods: {
    onSubmit() {
      this.$emit("search-text", this.text);
      this.text = "";
    },
  },
};
</script>
<style scoped></style>
