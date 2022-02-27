<template>
  <p v-if="num < 300">{{ num }}ms, much skill!</p>
  <p v-if="num > 300 && num < 500">{{ num }}ms, practice more!</p>
  <p v-if="num > 700">{{ num }}ms, don't hurt yourself!</p>
</template>

<script>
export default {
    props: [ 'num' ],

}
</script>

<style>

</style>