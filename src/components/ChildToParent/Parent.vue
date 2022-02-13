<template>
  <div>
    <ChildOne></ChildOne>
    <ChildTwo></ChildTwo>
  </div>
</template>

<script>
import ChildOne from "@/components/ChildToParent/ChildOne";
import ChildTwo from "@/components/ParentToChild/ChildTwo";
export default {
  name: "Parent",
  components: {
    ChildOne,
    ChildTwo,
  },
};
</script>
