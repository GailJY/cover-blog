<template>
  <div class="about">
    <HelloWorld msg="叶嘉宇" name="Gail" info="Web/前端学习" :class="{cover_collapsed:isActive}"/>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';

export default{
  name: "about",
  components: {
    HelloWorld
  },
  data() {
    return{
      isActive:true

    }
  }
};
</script>
<style lang="scss">
.cover_collapsed{
    width:22%;
    max-width:320px;
}
</style>

