<template>
  <div class="child">
    <p>Child Two</p>
    <p>{{ propsTwo }}</p>
  </div>
</template>

<script>
export default {
  name: "ChildTwo",
  props: ["propsTwo"],
};
</script>
