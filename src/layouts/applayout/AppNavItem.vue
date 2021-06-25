<template>
    <li class="mx-4 font-medium">
        <router-link :to="to">
            <slot></slot>
        </router-link>
    </li>
</template>

<script>
export default {
    props: {
        to: {
            type: String,
            required: true
        }
    }
}
</script>

<style>
.router-link-active{
    color: white;
}
</style>