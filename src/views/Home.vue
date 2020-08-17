<template>
<div class="flex">
  <h1>{{ new Date() | moment('LTS') }}</h1>
  <textarea name="text"></textarea>
</div>
</template>

<script>
</script>

<style scoped>
h1 {
  font-size: 20px;
  padding: 50px 0 20px 50px;
}
textarea {
  border: #fff;
  margin: 50px;
}
</style>