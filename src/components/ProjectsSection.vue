<script>
export default {
    name: 'ProjectsSection',
}

</script>

<template>
    <section id="Projects">
        <div>
            <h3 class="highlighter">
                My projects
            </h3>

            <!-- qui porbabilmente andrà un carosello -->
            <div id="projects">

                <div class="square">
                    <img src="dropbox.png" alt="">
                    <div>
                        dropbox
                    </div>
                </div>
                <div class="square">
                    <img src="zalando.png" alt="">
                    <div>
                        zalando
                    </div>
                </div>
                <div class="square">
                    <img src="whatsapp.png" alt="">
                    <div>
                        whatsapp
                    </div>
                </div>
                <div class="square">
                    <img src="zoom.png" alt="">
                    <div>
                        zoom
                    </div>
                </div>
                <div class="square">
                    <img src="spotify.png" alt="">
                    <div>
                        spotify
                    </div>
                </div>
                <div class="square">
                    <img src="dropbox.png" alt="">
                    <div>
                        dropbox
                    </div>
                </div>
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

        .square {
            width: calc((100%/3) - 20px);
            aspect-ratio: 1/1;

            img {
                width: 100%;
            }
        }
    }
}

//DEBUG
.quare {
    border: rgb(95, 165, 42) 3px dotted;
}
</style>
