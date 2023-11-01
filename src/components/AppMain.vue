<script>
import AboutSection from './AboutSection.vue';
import ProjectsSection from './ProjectsSection.vue';

export default {
    name: 'AppMain',
    components: {
        AboutSection,
        ProjectsSection
    }
}

</script>

<template>
    <main>
        <AboutSection />
        <ProjectsSection />
    </main>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

main {
    background-color: #34353a;
}
</style>
