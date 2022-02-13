<template>
  <div class="container">
    <h1>Parent To child</h1>
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
