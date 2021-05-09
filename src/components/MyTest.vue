<template>
  <div class="test">
    <h1>{{ tester }}</h1>
    <h3>{{ msg }}</h3>
    <p>Tess lives in {{ tessCity }}</p>
    <p>Alan lives in {{ alanCity }}</p>
  </div>
</template>

<script>
export default {
  name: "MyTest",
  props: {
    msg: String,
  },
  data() {
    return {
      tessCity: "Buffalo",
      alanCity: "New York",
    };
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
