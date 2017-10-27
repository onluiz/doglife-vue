<template>
  <v-layout>
      <v-card>
        <v-card-media src="/static/dog-icon-35930.png" height="200px">
        </v-card-media>
        <v-card-title primary-title>
          <div>
            <h3 class="headline mb-0">{{dog.nickname}}</h3>
            <div>{{dog.name}}</div>
          </div>
        </v-card-title>
        <v-card-actions>
          <v-btn flat color="orange">Share</v-btn>
          <v-btn flat color="orange">Explore</v-btn>
        </v-card-actions>
      </v-card>
  </v-layout>
</template>

<script>
export default {
  props: {
    dog: {
      type: Object,
      required: true
    }
  }
}
</script>