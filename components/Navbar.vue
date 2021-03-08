<template>
    <nav class="fixed top-0 left-0 flex w-full gap-4 p-4 bg-gray-200 shadow-md">
        <NuxtLink to="/">Home</NuxtLink>
        <NuxtLink to="/helloworld">Hello</NuxtLink>
    </nav>
</template>

<script>
    export default {
        name: 'Navbar',
    }
</script>

<style lang="postcss" scoped>
    a {
        @apply bg-gray-100 border border-gray-300 rounded shadow-xs px-4 py-2 text-green-400;
    }
    .nuxt-link-exact-active {
        @apply bg-gray-300 border-gray-100 shadow-inner text-green-700 font-bold;
    }
</style>
