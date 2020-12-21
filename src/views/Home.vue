<template>
  <div class="home">
    <HelloWorld msg="叶嘉宇" name="Gail" info="Web/前端学习"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
