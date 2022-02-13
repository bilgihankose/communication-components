<template>
  <div class="container">
    <ParentToChild></ParentToChild>
  </div>
</template>

<script>
import ParentToChild from "@/components/ParentToChild/ParentToChild";
export default {
  name: "App",
  components: {
    ParentToChild,
  },
};
</script>