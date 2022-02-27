<template>
  <div class="relative h-full min-h-screen">
    <!--<TheNavBar />-->
       <div class="pt-10 px-10 flex justify-center">
        <img :width="400" :height="400" src="./assets/logo.png" />
    </div>
    <div class="p-10">
      <router-view />
    </div>

    <div class="pt-10"></div>
    <!--<TheCat />-->
    <!--<TheFooter />-->
  </div>
</template>

<script>
import TheNavBar from '@/components/TheNavBar';
//import TheFooter from '@/components/gem-farm/TheFooter';
//import TheCat from '@/components/gem-farm/TheCat';
export default {
  components: { TheNavBar },
};
</script>

<style>
* {
  font-family: 'Roboto,Oxygen,Ubuntu,Cantarell,"Open Sans","Helvetica Neue",sans-serif;', monospace;
}
input[type='radio']:checked + span {
  @apply text-black;
}
body {
  background-color: #181818;
  color: white;
}
</style>
