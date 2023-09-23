<template>
    <section id="links">
        <div class="container">
            <div class="row py-5">
                <div class="col-6">

                    <div class="row">

                        <div class="col-4">

                            <h5>DC COMICS</h5>
                            <ul class="list-unstyled">
                                <li v-for="link in dcComics">
                                    <a href="#">
                                        {{ link.section }}
                                    </a>
                                </li>

                            </ul>

                            <h5>SHOP</h5>
                            <ul class="list-unstyled">

                                <li v-for="shop in shops">
                                    <a href="#">
                                        {{ shop.section }}
                                    </a>
                                </li>

                            </ul>
                        </div>

                        <div class="col-4">

                            <h5>DC</h5>
                            <ul class="list-unstyled">
                                <li v-for="link in dC">
                                    <a href="#">
                                        {{ link.section }}
                                    </a>
                                </li>

                            </ul>

                        </div>

                        <div class="col-4">

                            <h5>SITES</h5>
                            <ul class="list-unstyled">

                                <li v-for="site in sites">
                                    <a href="#">
                                        {{ site.section }}
                                    </a>
                                </li>

                            </ul>

                        </div>

                    </div>

                </div>



                <div class="col-6 position relative">
                    <img id="dc_logo_big" src="../assets/img/dc-logo-bg.png" alt="Logo DC" class="img-fluid">
                </div>

            </div>
        </div>


    </section>
</template>

<script>
export default {
    name: 'AppLinks',
    data() {
        return {
            dcComics: [
                {
                    section: 'Characters'
                },
                {
                    section: 'Comics'
                },
                {
                    section: 'Movies'
                },
                {
                    section: 'Tv'
                },
                {
                    section: 'Games'
                },
                {
                    section: 'Videos'
                },
                {
                    section: 'News'
                }

            ],
            shops: [
                {
                    section: 'Shop DC'
                },
                {
                    section: 'Shop DC Collectibles'
                }
            ],
            dC: [
                {
                    section: 'Term Of Use'
                },
                {
                    section: 'Privacy policy (New)'
                },
                {
                    section: 'Ad Choices'
                },
                {
                    section: 'Advertising'
                },
                {
                    section: 'Jobs'
                },
                {
                    section: 'Subscriptions'
                },
                {
                    section: 'Talent Workshops'
                },
                {
                    section: 'CPSC Certificates'
                },
                {
                    section: 'Ratings'
                },
                {
                    section: 'Shop Help'
                },
                {
                    section: 'Contact Us'
                }

            ],
            sites: [
                {
                    section: 'DC'
                },
                {
                    section: 'MAD Magazine'
                },
                {
                    section: 'DC Kids'
                },
                {
                    section: 'DC Universe'
                },
                {
                    section: 'DC Power Visa'
                }
            ]
        }
    }
}
</script>
