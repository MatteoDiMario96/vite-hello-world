<script>
import AppTitle from './components/AppTitle.vue';
export default {
  components:{
    AppTitle,
  },
  data() {
    return {
      message: 'ciao'
    }
  },
  methods:{

  },
  created(){

  }
}
</script>

<template>
  {{ message }}
  <AppTitle/>
</template>

<style scoped>

</style>
