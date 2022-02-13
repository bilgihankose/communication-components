<template>
  <div class="child">
    <p>Child One</p>
    <p>{{ propsOne }}</p>
  </div>
</template>

<script>
export default {
  name: "ChildOne",
  props: ["propsOne"],
};
</script>