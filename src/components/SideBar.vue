<template>
    <v-navigation-drawer 
    v-model="$store.state.showNav"
    app 
    color="blue-grey darken-3" 
    dark>
        <v-card-title dark>
            homepage
        </v-card-title>
    </v-navigation-drawer>
</template>
<script>
export default {
    data() {
        return {
        }

    },
    computed:{
        controlDrawer(){
            return this.$store.state.showNav;
        }
    }

}
</script>