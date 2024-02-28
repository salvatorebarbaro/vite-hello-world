<script>
import AppTitle from "./components/AppTitle.vue"
import AppHero from "./components/AppHero.vue"

export default
{
  components:{
    AppTitle,
    AppHero,

  }

}

</script>

<template>
  <AppTitle></AppTitle>
  
  <div id="container_jumbo">
    <AppHero></AppHero>
  </div>
</template>

<style>
#container_jumbo
{
  display: flex;
  justify-content: center;
}


</style>
