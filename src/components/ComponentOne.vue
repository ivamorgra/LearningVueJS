<template>
  <p> This is the first example component. It is relationated with third one.</p>
  <componentThree></componentThree>
</template>

<script>
import componentThree from './ComponentThree.vue'

export default {
    components: {
        componentThree
    }
}
</script>

<style>

</style>