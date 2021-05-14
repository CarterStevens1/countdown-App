<template>
  <div>
    <h3>Hello World</h3>
    <Counter
      :year="2022"
      :month="4"
      :date="14"
      :hour="0"
      :minute="0"
      :second="0"
      :millisecond="0"
    />
  </div>
</template>

<script>
import Counter from "./Counter.vue";
export default {
  components: {
    Counter,
  },
};
</script>

<style scoped></style>
