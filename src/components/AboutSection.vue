<script>
export default {
    name: 'AboutSection',
}

</script>

<template>
    <section id="About_me">
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
                    <h3 class="highlighter">
                        Boolean Carrers
                    </h3>
                    <h5>
                        Master | Full Stack Web Developer <br>
                        marzo 2023 - settembre 2023
                    </h5>
                    <p>
                        Corso di 700 ore, formazione pratica e teorica di tecnologie e metodo per lo sviluppo web full-stack
                    </p>
                </div>

                <!-- università -->
                <div>
                    <h3 class="highlighter">
                        Università degli studi Aldo Moro
                    </h3>
                    <h5>
                        Laurea | Programmazione e comunicazione digitale <br>
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
                    <h3 class="highlighter">
                        Liceo Scientifico Galileo Ferraris
                    </h3>
                    <h5>
                        Diploma | Scienze applicate <br>
                        settembre 2013 - lugio 2018
                    </h5>
                    <p>
                        Consolidata formmazione logica con diagrammi di flusso, piccoli accenni di C++
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
                    <h3 class="highlighter">

                        Jr. Full Stack Web Developer Trainee
                    </h3>
                    <h5>
                        Boolean, Milano, Lombardia, Italia <br>
                        Full time, da remoto <br>
                        mar 2023 - set 2023 ( 7 mesi )
                    </h5>
                    <p>
                        Corso di 700 ore, formazione pratica e teorica di tecnologie e metodo per lo sviluppo web full-stack
                    </p>
                </div>

                <!-- università -->
                <div>
                    <h3 class="highlighter">
                        Chef de rang
                    </h3>
                    <h5>
                        Posta ZIRM HOTEL****, Corvara in Badia, Trentino-Alto Adige, Italia <br>
                        Full-time, in sede <br>
                        giugno 2021 - ottobre 2022 ( 1 anno e 6 mesi )
                    </h5>
                    <p> Cameriera di sala di hotel****
                        Propensione per il lavoro in squadra, cura per i dettagli e l'attenzione verso il cliente.

                        Avanzamento professionale da commis di sala a chef de rang.
                        Gestione del magazzino, ordino merci, rapporti con i fornitori.
                        Coordinamento del personale, in mancanza della figura della responsabile.
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
        justify-content: space-between;
        gap: 100px;


        #training {
            width: 40%;
            text-align: left;
        }

        #work {
            width: 40%;
            text-align: right;
        }

        #training>div,
        #work>div {
            padding: 16px;
            margin-top: 8px;
            border-bottom: 1px $primary solid;
        }

        #training h5,
        #work h5 {
            margin-top: 8px;
            margin-bottom: 5px;
        }
    }
}
</style>
