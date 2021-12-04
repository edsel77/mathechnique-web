<template>
    <section class="section section-lg">
        <div class="container">
            <div class="row row-grid justify-content-center">
                <div class="col-lg-8 text-center">
                    <h2 class="display-3">Do you love this awesome
                        <span class="text-success">MATHechnique learning app?</span>
                    </h2>
                    <p class="lead">Cause if you do, it can be yours for FREE. Hit the button below to navigate to download page where you can find the android application. Start a new learning and develop your skill!</p>
                    <div class="btn-wrapper">
                        <a :href="$downloadLink" target="_blank" class="btn btn-primary mb-3 mb-sm-0">Download Now!</a>
                    </div>
                    <div class="text-center">
                        <h4 class="display-4 mb-5 mt-5">Available topics on this app</h4>
                        <div class="row justify-content-center">
                            <div class="col-lg-2 col-4">
                                <img src="mathechnique/integers.png" class="img-fluid">
                            </div>
                            <div class="col-lg-2 col-4">
                                <img src="mathechnique/calculus.png" class="img-fluid">
                            </div>
                            <div class="col-lg-2 col-4">
                                <img src="mathechnique/probability.png" class="img-fluid">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {};
</script>
<style>
</style>
