<template>
  <div>
    <h6>Child One</h6>
    <p>{{ messageOne }}</p>
  </div>
</template>

<script>
export default {
  name: "ChildOne",
  props: ["messageOne"],
};
</script>