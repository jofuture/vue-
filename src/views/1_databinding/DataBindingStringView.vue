<template>
  <div>
    <h1>Hello {{ userName }}</h1>
    <p>{{ message }}</p>
  </div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'Mirae Jo',
      message: 'Welcome 미래'
    }
  }
}
</script>
<style scoped>
.text-red {
  color: red;
}
</style>
