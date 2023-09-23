<template>
    <section id="buy">
        <div class="container py-5">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-5 justify-content-between justify-content-md-center">


                <div class="col1" v-for="action in actions">
                    <a href="#">
                        <img :src="action.img" alt=""><span>{{ action.text }}</span>
                    </a>
                </div>

                <!-- <div class="col1">
                    <a href="#">
                        <img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span>
                    </a>
                </div>

                <div class="col1">
                    <a href="#">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span>
                    </a>
                </div>

                <div class="col1">
                    <a href="#">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span>
                    </a>
                </div>

                <div class="col1">
                    <a href="#">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span>
                    </a>
                </div> -->

            </div>

        </div>

    </section>
    <!-- /#buy -->
</template>

<script>
export default {
    name: 'AppBuy',
    data() {
        return {
            actions: [
                {
                    img: 'src/assets/img/buy-comics-digital-comics.png',
                    text: 'DIGITAL COMICS'

                },
                {
                    img: 'src/assets/img/buy-comics-merchandise.png',
                    text: 'DC MERCHANDISE'

                },
                {
                    img: 'src/assets/img/buy-comics-subscriptions.png',
                    text: 'SUBSCRIPTION'

                },
                {
                    img: 'src/assets/img/buy-comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR'

                },
                {
                    img: 'src/assets/img/buy-dc-power-visa.svg',
                    text: 'DC POWER VISA'

                },
            ]
        }
    }
}
</script>
