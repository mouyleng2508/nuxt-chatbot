<template>
    <div class="bg-[#0A0A0A]  h-screen">
        <LayoutNavbar />
        <slot />
    </div>
</template>

<script>
import LayoutNavbar from '../components/LayoutNavbar.vue';

export default {
    setup() {
        return {};
    },
    components: { LayoutNavbar }
}
</script>

<style lang="scss" scoped></style>