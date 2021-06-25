<template>
    <div id="main">

        <!-- header -->
        <AppHeader />

        <!-- main content-->
        <main class="bg-gray-900 text-white">
            <div class="container m-auto p-4">
                <slot></slot>
            </div>
        </main>


        <!-- footer -->
        <AppFooter/>

    </div>
</template>

<script>
import AppHeader from "@/layouts/applayout/AppHeader.vue"
import AppFooter from "@/layouts/applayout/AppFooter.vue"
export default {
    components: { AppHeader, AppFooter },
}
</script>