<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: 'La mia prima app con Vite!'
        }
    }
}
</script>

<template>
    <header>
        <h1>{{ title }}</h1>
    </header>
</template>

<style>
header {
    text-align: center;
    margin-top: 50px;
}

h1 {
    color: red;
}
</style>