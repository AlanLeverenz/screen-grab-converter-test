<template>
  <div class="test">
    <MyTest msg="We're the best testers, period!" />
  </div>
</template>

<script>
// @ is an alias to /src
import MyTest from "@/components/MyTest.vue";

export default {
  name: "Test",
  components: {
    MyTest,
  },
};
</script>
