<template>
  <div>
    <LikeHeader></LikeHeader>
    <h1>{{ number }}</h1>
    <LikeNumber :number="number"></LikeNumber>
    <LikeNumber :number="number"></LikeNumber>
  </div>
</template>

<script>
import LikeHeader from "./components/LikeHeader.vue";

export default {
  data() {
    return {
      number: 10,
    };
  },
  components: {
    LikeHeader,
  },
};
</script>

<style scoped>
div {
  border: 1px solid red;
}
</style>
