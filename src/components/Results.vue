<template>
  <p v-if="num < 300">{{ num }}ms, much skill!</p>
  <p v-if="num > 300 && num < 500">{{ num }}ms, practice more!</p>
  <p v-if="num > 700">{{ num }}ms, so slowness!</p>
</template>

<script>
export default {
    props: [ 'num' ],

// could also put logic for rank/score here
// in mounted() using if statements to update
// a new variable, then displaying that in
// another p or span...
// data handled in template expression comes
// in just before mounted(), or after ???

}
</script>

<style>

</style>