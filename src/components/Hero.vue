<template>
    <div class="hero">
        <!-- desktop -->
        <div class="d-none d-md-block">
            <div class="row">
                <div class="col-md-6">
                    <div class="d-flex h-100">
                        <div class="justify-content-center align-self-center">
                            <h2><strong>Delicious Food Menu, </strong> <br>in Your Gadget</h2>
                            <p>Pilih dan pesan makanan favorit anda</p>
                            <router-link class="btn btn-lg btn-success" to="/food"><b-icon-arrow-right></b-icon-arrow-right> Pesan</router-link>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <img src="../assets/images/hero.svg" alt="" width="100%">
                </div>
            </div>
        </div>

        <!-- mobile -->
        <div class="d-sm-block d-md-none">
            <div class="row">
                <div class="col-md-6 mb-3">
                    <img src="../assets/images/hero.svg" alt="" width="100%">
                </div>
                <div class="col-md-6">
                    <div class="d-flex h-100">
                        <div class="justify-content-center align-self-center">
                            <h2><strong>Delicious Food Menu, </strong> <br>in Your Gadget</h2>
                            <p>Pilih dan pesan makanan favorit anda</p>
                            <button class="btn btn-lg btn-success"><b-icon-arrow-right></b-icon-arrow-right> Pesan</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeroComponent'
}
</script>

<style>

</style>