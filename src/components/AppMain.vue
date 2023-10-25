<script>
export default {
    name: 'AppMain',

}

</script>

<template>
    <main>
        <section class="get_start_today">
            <div class="center_container">
                <div class="name">
                    <!-- <img src="getstarttoday/artist-quote-icon.png" alt="virgolette"> -->
                    <h1>
                        Ciao! Io sono Alessandra Martera
                    </h1>

                </div>
                <!-- carousel with my title job -->
                <div class="carousel">
                    <div class="text">
                        e sono una junior full Stack Web Developer
                    </div>
                </div>
            </div>

        </section>
    </main>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;

main {
    color: #778899;
    height: 100vh;
    background-color: #3c3c3c;
    padding: 60px 0;

    .center_container {
        width: 80%;
        margin: 0 auto;


    }
}



.center_container {
    display: flex;

    .name {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 30px;
        width: 40%;
        text-align: center;

        img {
            width: 40px;
        }

        h1 {
            font-size: 50px;
        }
    }

    .text {}
}
</style>
