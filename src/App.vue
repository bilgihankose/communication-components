<template>
  <div class="container">
    <ParentToChild></ParentToChild>
    <ChildToParent></ChildToParent>
  </div>
</template>

<script>
import ParentToChild from "@/components/ParentToChild/ParentToChild";
import ChildToParent from "@/components/ChildToParent/ChildToParent";
export default {
  name: "App",
  components: {
    ParentToChild,
    ChildToParent,
  },
};
</script>