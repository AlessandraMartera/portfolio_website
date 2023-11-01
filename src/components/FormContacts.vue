<script>
export default {
    name: 'FormContacts',
}

</script>

<template>
    <section id="Contacts">
        <div>
            <h3 class="highlighter">
                Contact me
            </h3>

            <div id="contact_area">

                <form action="">
                    <label for="email"></label>
                    <input type="email" id="email" nome="email" placeholder="your email">
                    <br>
                    <textarea name="message" id="message" cols="30" rows="10" placeholder="Send me a message"></textarea>
                    <input type="button" id="send" value="SEND">
                </form>
            </div>

        </div>





    </section>
</template>

<style lang="scss" scoped>
@use "./../styles/general.scss" as *;
@use "./../styles/partials/variables.scss" as *;

section {
    text-align: center;

    #contact_area {
        width: 40%;
        margin: 0 auto;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 20px;

        form {
            width: 100%;

            #email,
            #message,
            #send {
                font-size: 16px;
                padding: 5px 8px;
                width: 100%;
                line-height: 40px;
                margin: 5px;
                border-radius: 12px;
            }

            #send {
                width: 100px;
                // padding: 20px;

                cursor: not-allowed;
                padding: 6px;
                border: 2px solid $highlighter;
                color: $highlighter;
                background: none;
            }
        }
    }
}

//DEBUG
.square {
    width: calc((100%/3) - 20px);
    aspect-ratio: 1/1;
    border: rgb(95, 165, 42) 3px dotted;

}
</style>
