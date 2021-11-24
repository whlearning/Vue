<template>
  <div>
    <School></School>
    <Student></Student>
  </div>
</template>

<script>
//引入组件
import School from "./School.vue";
import School from "./Studnet.vue";
export default {
  name: "App",     //省略了Vue.extend
  components: {
    School,
    Student,
  },
};
</script>

<style>
</style>