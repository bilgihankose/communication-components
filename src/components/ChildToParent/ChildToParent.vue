<template>
  <div class="container">
    <h3 class="pt-5">Child To Parent</h3>
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
