<template>
  <v-app>
    <header-main-page />
    <dog-card-list />
    <footer-main-page />
  </v-app>
</template>

<script>
  import HeaderMainPage from './components/mainPage/HeaderMainPage'
  import DogCardList from './components/DogCardList'
  import FooterMainPage from './components/mainPage/FooterMainPage'

  export default {
    components: {
      HeaderMainPage,
      DogCardList,
      FooterMainPage
    }
  }
</script>
