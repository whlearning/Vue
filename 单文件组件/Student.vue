<template>
  <div>
    <h1>学生名称：{{ name }}</h1>
    <h1>学生年龄：{{ age }}</h1>
  </div>
</template>
  
<script>
export default {
  name: "Student",
  data() {
    return {
      name: "尚",
      age: 11,
    };
  },
};
</script>

<style>
</style>
