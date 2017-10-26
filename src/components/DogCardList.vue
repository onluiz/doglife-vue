<template>
  <main>
      <v-content>
        <v-container fluid>
          <dog-card />
        </v-container>
      </v-content>
    </main>
</template>

<script>
import DogCard from './DogCard'
export default {
  components: {
    DogCard
  }
}
</script>

