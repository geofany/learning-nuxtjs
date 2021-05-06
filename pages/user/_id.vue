<template lang="html">
  <h1>Profile {{$route.params.id}}</h1>
</template>

<script>
export default {
    validate({params}) {
        //must be a number
        return /^\d+$/.test(params.id)
    }
}
</script>

<style lang="css" scoped>
</style>
