<template>
  <div class="container">
    <h3 class="pt-5">Parent To child</h3>
    <Parent></Parent>
  </div>
</template>

<script>
import Parent from "@/components/ParentToChild/Parent";

export default {
  name: "ParentToChild",
  components: {
    Parent,
  },
};
</script>
