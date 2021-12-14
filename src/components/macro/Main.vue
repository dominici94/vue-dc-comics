<template>
  <main>
      <Jumbotron/>
      <Comics/>
  </main>
</template>

<script>
import Comics from '../sections/Comics.vue'; 
import Jumbotron from '../sections/Jumbotron.vue'

export default {
    name: 'Main',
    components: {
        Jumbotron,
        Comics
    }
}
</script>

<style lang="scss" scoped>
    @import '../../assets/style/partials/variables.scss';

    main{
        background-color: $secondaryColor;
        color: white;
    }
</style>