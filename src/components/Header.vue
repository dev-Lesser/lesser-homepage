<template>
    <v-app-bar
      app
      color="blue-grey darken-3"
      dark
    >
    <v-app-bar-nav-icon @click="$store.state.showNav = !$store.state.showNav"></v-app-bar-nav-icon>
     
    </v-app-bar>
</template>
<script>
export default {
    data() {
        return {
            
        }
        
    },
    mounted(){
        console.log(this.$store.state.showNav)
    },
    methods:{
    
    },
    computed:{
        showNav(){
            return this.$store.state.showNav;
        }
    }
}
</script>