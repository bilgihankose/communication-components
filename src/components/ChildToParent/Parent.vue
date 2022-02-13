<template>
  <div>
    <p>Verilerim {{ todos }}</p>
    <p>Verilerim {{ string }}</p>
    <p>Verilerim {{ object }}</p>
    <ChildOne></ChildOne>
    <ChildTwo :yolla="todos" :kelime="string" :gonder="object"></ChildTwo>
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
      todos: [1, 2, 3, 4],
      object: {"greeting" : "hello from adele"},
      string: "Hi",
    };
  },
};
</script>
