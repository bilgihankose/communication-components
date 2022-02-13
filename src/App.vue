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

<style>
* {
  box-sizing: border-box;
}
body {
  background-color: lightyellow;
  margin: 10px;
  padding: 10px;
}

.container {
  margin-top: 10px;
}
.parent {
  background-color: #f0f0f0;
}
.child {
  margin: 10px;
  border: 1px solid black;
  background-color: lightblue;
}
</style>
