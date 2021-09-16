<template>
  <header>
      <h1>{{ valor }}</h1>
  </header>
</template>

<script>
export default {
  props: ["valor"]
}
</script>

<style scoped>
header{
    background-color: palevioletred;
    color: slateblue;
    height: 50px;
    width: 100%;
    display: flex;
}
</style>