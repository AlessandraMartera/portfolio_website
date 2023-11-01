<script>
export default {
    name: 'AboutSection',
}

</script>

<template>
    <section>
        <div>
            <h5 class="highlighter">
                About Me
            </h5>
            <h2>
                titolo generico
            </h2>
            <p>
                Fin da piccola sono sempre stata incuriosita dalla tecnologia, dalle cose più banali, da come funziona una
                lampadina a come fanno i computer a comunicare tra loro. <br>

                Quando ho iniziato la scuola superiore, ho iniziato a studiare informatica e programmazione, da lì ho capito
                che per fare grandi progetti, si inizia sempre da piccole cose. <br>

                Finita la scuola ho iniziato un percorso universitario in programmazione e comunicazione digitale. Dopo
                alcuni esami teorici ho pensato che non fosse adatto a me, nonostante mi incuriosisse e appassionasse molto.
                <br>

                Ho lasciato alle spalle l'università ed iniziato a lavorare in ambiti più pratici. Questa esperienza mi ha
                permesso di migliorare le mie skills interpersonali. Ho scoperto la tech accademy di Boolean, che fin dal
                corso di preparazione all' ammissione, mi ha fatto riscoprire la bellezza di cercare e scoprire come
                risolvere problemi e realizzare progetti divertenti e interessanti. <br>
            </p>
        </div>

        <div>
            <h1 class="highlighter b_title">
                Perscorso Formativo
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
}</style>
