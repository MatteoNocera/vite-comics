<template>
    <section id="buy">
        <div class="container py-5">
            <div class="row row-cols-1 row-cols-sm-2 row-cols-md-5 justify-content-between justify-content-md-center">

                <div class="col1" v-for="action in actions">
                    <a href="#">
                        <img :src="getImageUrl(action.img)" alt=""><span>{{ action.text }}</span>
                    </a>
                </div>

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
                    img: '../assets/img/buy-comics-digital-comics.png',
                    text: 'DIGITAL COMICS'

                },
                {
                    img: '../assets/img/buy-comics-merchandise.png',
                    text: 'DC MERCHANDISE'

                },
                {
                    img: '../assets/img/buy-comics-subscriptions.png',
                    text: 'SUBSCRIPTION'

                },
                {
                    img: '../assets/img/buy-comics-shop-locator.png',
                    text: 'COMIC SHOP LOCATOR'

                },
                {
                    img: '../assets/img/buy-dc-power-visa.svg',
                    text: 'DC POWER VISA'

                },
            ]
        }
    },
    methods: {
        getImageUrl: function (img) {
            return new URL(img, import.meta.url)
        }
    }
}
</script>
