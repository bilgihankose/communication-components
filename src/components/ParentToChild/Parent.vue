<template>
  <div class="container">
    <h6>You can send data to child.</h6>
    <p>Message One is:</p>
    <input type="text" v-model="messageOne" />
    <p>Message Two is:</p>
    <input type="text" v-model="messageTwo" />
    <ChildOne :messageOne="messageOne"></ChildOne>
    <ChildTwo :messageTwo="messageTwo"></ChildTwo>
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
