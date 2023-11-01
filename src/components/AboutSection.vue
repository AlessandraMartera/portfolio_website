<script>
export default {
    name: 'AboutSection',
}

</script>

<template>
    <section>
        <div>
            <h3 class="highlighter">
                About Me
            </h3>
            <h2>
                Il mio percoso professionale fino ad oggi
            </h2>
            <p>

            </p>
        </div>

        <div id="container">


            <div id="training">
                <h1 class="highlighter b_title">
                    Formazione
                </h1>

                <!-- Boolean -->
                <div>
                    <h3>
                        Boolean Carrers
                    </h3>
                    <h5>
                        Master | Full Stack Web Developer
                        marzo 2023 - settembre 2023
                    </h5>
                    <p>
                        Corso di 700 ore, formazione pratica e teorica di tecnologie e metodo per lo sviluppo web full-stack
                    </p>
                </div>

                <!-- università -->
                <div>
                    <h3>
                        Università degli studi Aldo Moro
                    </h3>
                    <h5>
                        Laurea | Programmazione e comunicazione digitale
                        settembre 2018 - percorso interrotto
                    </h5>
                    <p>Alcuni corsi svolti e conseguiti:
                    <ul>
                        <li> - Programmazione ( Linguaggio C )</li>
                        <li> - Laboratorio di informatica ( Linguaggio C )</li>
                        <li> - inglese</li>
                    </ul>
                    </p>
                </div>

                <!-- Liceo -->
                <div>
                    <h3>
                        Liceo Scientifico Galileo Ferraris
                    </h3>
                    <h5>
                        Diploma | Scienze applicate
                        settembre 2013 - lugio 2018
                    </h5>
                    <p>
                        Consolidata formmazione logica con diagrammi di flusso
                    </p>
                </div>

            </div>

            <!-- WorK -->
            <div id="work">
                <h1 class="highlighter b_title">
                    Lavoro
                </h1>

                <!-- Boolean -->
                <div>
                    <h3>
                        Boolean Carrers
                    </h3>
                    <h5>
                        Master | Full Stack Web Developer
                        marzo 2023 - settembre 2023
                    </h5>
                    <p>
                        Corso di 700 ore, formazione pratica e teorica di tecnologie e metodo per lo sviluppo web full-stack
                    </p>
                </div>

                <!-- università -->
                <div>
                    <h3>
                        Università degli studi Aldo Moro
                    </h3>
                    <h5>
                        Laurea | Programmazione e comunicazione digitale
                        settembre 2018 - percorso interrotto
                    </h5>
                    <p>Alcuni corsi svolti e conseguiti:
                    <ul>
                        <li> - Programmazione ( Linguaggio C )</li>
                        <li> - Laboratorio di informatica ( Linguaggio C )</li>
                        <li> - inglese</li>
                    </ul>
                    </p>
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

    .b_title {
        font-size: 48px;
    }

    #container {
        display: flex;

        gap: 100px;


        #training {
            text-align: left;
        }

        #work {
            text-align: right;
        }
    }
}
</style>
