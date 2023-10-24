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

    </footer>
</template>


<style lang="scss" scoped>
@use "./../styles/general.scss" as *;

footer {
    height: 100px;
    background-color: #000;
    color: #fff;
}
</style>
