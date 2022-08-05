<script>
export default {
  data() {
    return {
      message: 'Hello World!'
    }
  }
}
</script>

<template>
  <div class="container pt-5">
    <h1>{{ message }}</h1>
    <NuxtLink to="/about" class="btn btn-primary">About Page</NuxtLink>
  </div>
</template>