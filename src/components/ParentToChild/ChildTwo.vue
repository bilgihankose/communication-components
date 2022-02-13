<template>
  <div>
    <h6>Child Two</h6>
    <p>{{ messageTwo }}</p>
  </div>
</template>

<script>
export default {
  name: "ChildTwo",
  props: ["messageTwo"],
};
</script>