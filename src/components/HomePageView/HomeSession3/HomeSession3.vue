@<template>
    <div class="session-3__container f fdc pl150 relative pt5 pb5 bg-primary-1">
        <div class="session-3__header f jcb aic mb05 pr5">
            <div class="h2 primary">
                Dịch vụ tại Tròn
            </div>
            <div class="p4 primary">
                XEM TẤT CẢ
            </div>
        </div>
        <div class="session-3__title mb2">
            <div class="h7">Tròn Spa giúp mọi khách hàng có nhu cầu làm đẹp, thư giãn và chăm sóc sức khỏe 1 cách toàn diện. Tròn Spa giúp mọi khách <br> hàng có nhu cầu làm đẹp, thư giãn và chăm sóc sức khỏe 1 cách toàn diện.</div>
        </div>
        <div class="session-3__list">
            <Flickity
                ref="flickity" 
                :options="flickityOptions">
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession3/1.png" alt="">
                    <div class="mb05" style="text-align: start">
                        <div class="h5">Massage & chăm sóc body</div>
                    </div>
                    <div class="p3" style="text-align: start">Massage thư giãn, trị liệu chuyên sâu và liệu pháp thanh tẩy cơ thể </div>
                </div>
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession3/2.png" alt="">
                    <div class="mb05" style="text-align: start">
                        <div class="h5">Massage & chăm sóc body</div>
                    </div>
                    <div class="p3" style="text-align: start">Massage thư giãn, trị liệu chuyên sâu và liệu pháp thanh tẩy cơ thể </div>
                </div>
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession3/3.png" alt="">
                    <div class="mb05" style="text-align: start">
                        <div class="h5">Massage & chăm sóc body</div>
                    </div>
                    <div class="p3" style="text-align: start">Massage thư giãn, trị liệu chuyên sâu và liệu pháp thanh tẩy cơ thể </div>
                </div>
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession3/4.png" alt="">
                    <div class="mb05" style="text-align: start">
                        <div class="h5">Massage & chăm sóc body</div>
                    </div>
                    <div class="p3" style="text-align: start">Massage thư giãn, trị liệu chuyên sâu và liệu pháp thanh tẩy cơ thể </div>
                </div>
            </Flickity>
        </div>
    </div>
</template>

<script>
import Flickity from '../../../../node_modules/vue-flickity/src/flickity.vue';
export default {
    data () {
        return {
            flickityOptions: {
                prevNextButtons: true,
                pageDots: false,
                initialIndex: 1,
                lazyLoad: 2
            }
        }
    },
    components : {
        Flickity
    }
}
</script>

<style scoped lang="scss">
    @import "HomeSession3.scss";
</style>