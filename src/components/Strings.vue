<template>
    <div>
        <li v-bind:key="string.id" v-for="string in strings"></li>
    </div>
</template>

<script>
export default {
    name: "Strings",
    props: ["strings"]
}
</script>

<style scoped>

</style>