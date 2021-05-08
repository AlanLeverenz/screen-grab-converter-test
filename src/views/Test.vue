<template>
  <div class="test">
    <Test />
  </div>
</template>

<script>
// @ is an alias to /src
import Test from "@/components/Test.vue";

export default {
  name: "Test",
  components: {
    Test,
  },
};
</script>
