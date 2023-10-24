<script >
// import file
import AppHeader from './components/AppHeader.vue'
import AppFooter from './components/AppFooter.vue'

// export file
export default {
  components: {
    AppHeader,
    AppFooter,
  },
}

</script>

<template>
  <AppHeader />

  <AppFooter />
</template>


<style lang="scss">
@use "./styles/general.scss" as *;
</style>
