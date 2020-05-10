<template>
<!-- Women Banner Section Begin -->
    <section class="partner-logo">
        <div class="container">
                    <carousel class="logo-carousel" :items="5" :dots="false" :nav="false" :autoplay="true" :loop="true">
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="img/logo-carousel/logo-1.png" alt="" />
                            </div>
                        </div>
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="img/logo-carousel/logo-2.png" alt="" />
                            </div>
                        </div>
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="img/logo-carousel/logo-3.png" alt="" />
                            </div>
                        </div>
                        <div class="logo-item">
                            <div class="tablecell-inner">
                                <img src="img/logo-carousel/logo-4.png" alt="" />
                            </div>
                        </div>
                    </carousel>
        </div>
    </section>
    <!-- Women Banner Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "PatnerShayna",
  components: {
      carousel
  }
}
</script>

<style scoped>
.product-item{
    margin-right: 25px;
}
</style>