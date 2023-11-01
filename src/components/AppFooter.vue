<script>
// export file
export default {
    name: 'AppFooter',

}

</script>

<template>
    <footer>
        <div>
            profili social:
            <ul>
                <!-- instagram link -->
                <li>
                    <a href="https://www.instagram.com/alee_mrt/">
                        <i class="fa-brands fa-instagram"></i>
                    </a>
                </li>

                <!-- linkedin link -->
                <li>
                    <a href="https://www.linkedin.com/in/alessandra-martera-3330b6162/">
                        <i class="fa-brands fa-linkedin-in"></i>
                    </a>
                </li>
            </ul>
        </div>

        <small>© Alessandra Martera. Tutti i diritti riservati.</small>
    </footer>
</template>


<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

footer {
    padding: 20px;
    height: 150px;
    background-color: $background_dark;

    ul {
        display: flex;
        gap: 10px;
    }
}
</style>
