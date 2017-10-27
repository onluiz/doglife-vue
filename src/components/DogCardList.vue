<template>
  <main>
      <v-content>
        <v-container fluid>
          <dog-card v-for="dog,i in dogs" v-bind:key="i" :dog="dog" />
        </v-container>
      </v-content>
    </main>
</template>

<script>
import DogCard from './DogCard'
export default {
  components: {
    DogCard
  },
  data () {
    return {
      dogs: [{
        id: 1,
        name: 'Link da Silva',
        nickname: 'Link'
      },
      {
        id: 2,
        name: 'Mog da Silva',
        nickname: 'Mog'
      }]
    }
  }
}
</script>
