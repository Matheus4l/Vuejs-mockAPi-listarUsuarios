<template>
  <v-app >
    <TopMenu></TopMenu>
    <v-content>
      <router-view></router-view>
    </v-content>
   
  </v-app>
</template>

<script>
import TopMenu from '../src/components/navegacao/TopMenu';


export default {
  name: 'App',
  components:{
    TopMenu
  },
 
  data: () => ({
    
  }),
  mathod:{
    
  }
};
</script>
