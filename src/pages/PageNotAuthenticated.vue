<template>
  <div class="container">
    <ErrorView :title="'Ooooops, you are not authenticated pls login'"
               :status="'401'"
               :navigateToPage="'PageLogin'"
               :navigateToText="'Navigate to login page'" />
  </div>
</template>

<script>
  import ErrorView from '@/components/ErrorView'
  export default {
    components: {
      ErrorView
    }
  }
</script>

<style scoped>
</style>