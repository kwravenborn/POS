<template>
  <div id="app" class="small-container">
    <login-index />
  </div>
</template>

<script>
import LoginIndex from '@/components/LoginIndex'

export default {
  name: 'App',
  components: {
    LoginIndex
  }
}
</script>

<style>

  .small-container {
    max-width: 680px;
  }
</style>
