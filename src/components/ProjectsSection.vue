<script>
export default {
    name: 'ProjectsSection',
}

</script>

<template>
    <section>
        <div>
            <h3 class="highlighter">
                My projects
            </h3>

            <!-- qui porbabilmente andrà un carosello -->
            <div id="projects">

                <div class="square">ciao</div>
                <div class="square"></div>
                <div class="square"></div>
                <div class="square"></div>
                <div class="square"></div>
                <div class="square"></div>
            </div>

        </div>





    </section>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

section {
    text-align: center;
    background-color: $background_dark;

    #projects {
        display: flex;
        flex-wrap: wrap;
        gap: 20px;
    }
}

//DEBUG
.square {
    width: calc((100%/3) - 20px);
    aspect-ratio: 1/1;
    border: rgb(95, 165, 42) 3px dotted;

}
</style>
