<template>
  <div class="parent">
    <h2>Parent Container</h2>
    <p>You can send data to child.</p>
    <p>Message One is:</p>
    <input type="text" v-model="messageOne" />
    <p>Message Two is:</p>
    <input type="text" v-model="messageTwo" />
    <ChildOne :propsOne="messageOne"></ChildOne>
    <ChildTwo :propsTwo="messageTwo"></ChildTwo>
  </div>
</template>

<script>
import ChildOne from "@/components/ParentToChild/ChildOne";
import ChildTwo from "@/components/ParentToChild/ChildTwo";
export default {
  components: {
    ChildOne,
    ChildTwo,
  },
  name: "ParentToChild",
  data() {
    return {
      messageOne: "",
      messageTwo: "",
    };
  },
};
</script>
