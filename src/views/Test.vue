<template>
  <div class="test">
    <MyTest />
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
