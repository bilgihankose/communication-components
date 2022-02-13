<template>
  <div class="parent">
    <h2>Parent Container</h2>
    <p>{{ emitOne }}</p>
    <p>{{ emitTwo }}</p>
    <ChildOne @childOne="emitOne = $event"></ChildOne>
    <ChildTwo @childTwo="emitTwo = $event"></ChildTwo>
  </div>
</template>

<script>
import ChildOne from "@/components/ChildToParent/ChildOne";
import ChildTwo from "@/components/ChildToParent/ChildTwo";
export default {
  name: "Parent",
  components: {
    ChildOne,
    ChildTwo,
  },
  data() {
    return {
      emitOne: "Child One's Data",
      emitTwo: "Child Two's Data",
    };
  },
};
</script>
