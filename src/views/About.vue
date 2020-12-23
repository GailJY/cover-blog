<template>
  <div class="about">
    <HelloWorld msg="叶嘉宇" name="Gail" info="Web/前端学习" :class="{cover_collapsed:isActive}"/>
    <Contain></Contain>
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue';
import Contain from '@/components/Contain.vue';
export default{
  name: "about",
  components: {
    HelloWorld,
    Contain
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

