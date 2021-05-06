<template lang="html">
    <div class="">
        <main v-if="$route.params.slug">
            <h1 v-text="'Blog ' +$route.params.slug"></h1>

        </main>
        <main v-else>
            <h1>List Blog</h1>
        </main>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="css" scoped>
</style>
