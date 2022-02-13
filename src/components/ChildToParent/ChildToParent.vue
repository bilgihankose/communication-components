<template>
  <div class="container">
    <h1>Child To Parent</h1>
    <Parent></Parent>
  </div>
</template>

<script>
import Parent from "@/components/ChildToParent/Parent";
export default {
  name: "ChildToParent",
  components: {
    Parent,
  },
};
</script>