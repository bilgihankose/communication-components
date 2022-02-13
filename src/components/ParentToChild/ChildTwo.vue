<template>
  <div>
    <h6>Child Two</h6>
    <p>{{ propsTwo }}</p>
  </div>
</template>

<script>
export default {
  name: "ChildTwo",
  props: ["propsTwo"],
};
</script>
