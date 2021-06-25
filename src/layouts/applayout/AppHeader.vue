<template>
    <header class="bg-gray-900 border-b border-gray-700">
        <div class="container m-auto h-16 flex items-center justify-between">
            
            <h1 class="text-3xl font-bold text-white"><span class="text-green-400">Vue</span> Movie App</h1>

            <nav class="text-gray-400">
                <ul class="flex">
                    <AppNavItem to="/">Home</AppNavItem>
                    <AppNavItem to="/movies">Movies</AppNavItem>
                    <AppNavItem to="/tv-shows">Tv Shows</AppNavItem>
                    <AppNavItem to="/about">About</AppNavItem>
                </ul>
            </nav>

        </div>
    </header>
</template>

<script>
import AppNavItem from "./AppNavItem.vue"
export default {
    name: "AppHeader",
    components: { AppNavItem }
}
</script>