<script>
import AboutSection from './AboutSection.vue';
export default {
    name: 'AppMain',
    components: {
        AboutSection
    }
}

</script>

<template>
    <main>
        <AboutSection />
    </main>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

main {
    background-color: #34353a;
}
</style>
