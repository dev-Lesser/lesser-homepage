<template>
  <v-app>
    <Header/>
    <side-bar/>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import SideBar from '@/components/SideBar'
import Header from '@/components/Header'
export default {
  name: 'App',

  components: {
    SideBar,
    Header
  },

  data: () => ({
    //
  }),
};
</script>
