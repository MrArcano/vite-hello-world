
<script>
export default {
  name: "Hero",
  data() {
    return {
      text: "Hero",
    };
  },
};
</script>

<template>
  <div class="hero">{{ text }}</div>
</template>

<style scoped>
.hero{
  background-color: rgb(21, 207, 61);
  font-size: 8rem;

  height: 200px;
  line-height: 200px;
  text-align: center;
}
</style>