<template>
  <div class="wrapper">
    <Header  />
    <div class="wrapper-content">
      <div class="container">
        <router-view />
        <!-- <router-view /> - это компонент, который будет меняться в зависимости от маршрута -->
       
      </div>
    </div>
    <Footer  />
    
  </div>
</template>


<script>
import Header from '@/components/Header.vue';
import Footer from '@/components/Footer.vue';
export default {
  components: {
    Header,
    Footer
  },


}
</script>