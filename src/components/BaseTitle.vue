<template>
    <h1>La mia prima app con Vue CLI!</h1>
</template>

<script>
export default {
  name: 'BaseTitle',
  props: {
    msg: String
  }
}
</script>

<style scoped lang="scss">
    h1 {
        color: rgb(255, 0, 0);
        font-size: 60px;
    }
</style>