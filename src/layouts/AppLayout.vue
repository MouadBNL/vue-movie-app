<template>
    <div id="main">

        <!-- header -->
        <AppHeader />

        <!-- main content-->
        <main class="bg-gray-900 text-white">
            <div class="container m-auto py-4">
                <slot></slot>
            </div>
        </main>


        <!-- footer -->
        <AppFooter/>

    </div>
</template>

<script>
import AppHeader from "./applayout/AppHeader.vue"
import AppFooter from "./applayout/AppFooter.vue"
export default {
    components: { AppHeader, AppFooter },
}
</script>