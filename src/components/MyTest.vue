<template>
  <div class="test">
    <h1>{{ tester }}</h1>
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: "MyTest",
  props: {
    msg: String,
  },
  setup() {
    const tester = "tess & alan";
    return { tester };
  },
};
</script>

<style>
.test {
  text-align: center;
}
</style>
