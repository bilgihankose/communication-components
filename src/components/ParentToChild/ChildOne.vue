<template>
  <div>
    <h6>Child One</h6>
    <p>{{ propsOne }}</p>
  </div>
</template>

<script>
export default {
  name: "ChildOne",
  props: ["propsOne"],
};
</script>
