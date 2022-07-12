@<template>
    <div class="session-5__container f jcb aic z2 container h100vh bg-primary-1">
        <div class="session-5__left">
            <img src="../../../assets/imgSession5/img_Left.png" alt="">
        </div>
        <div class="session-5__right f fdc ais">
            <div class="session-5__right-title mb05">
                <div class="h2 primary">
                    Tin tức - Khuyến mãi 
                </div>
            </div>
            <div class="session-5__right-text mb15">
                <div class="p6">
                    With each new day, there's a new Le Legna With each new day, there's a new Le Legna
                </div>
            </div>
            <div class="session-5__right-slide w100">
                <div class="right-slide__action f aic mb2">
                    <div class="p2 primary">
                        Xem thêm tin tức
                    </div>
                    <div class="icon--arrown-right ml05"></div>
                </div>
                <div class="right-slide__lits">
                    <Flickity
                        ref="flickity" 
                        :options="flickityOptions">

                        <!-- 1 -->
                        <div class="carousel-cell">
                            <img class="carousel-cell-image mb1" src="../../../assets/imgSession3/1.png" alt="">
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="mb05 align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                            <div class="p6 gray align-l">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                            </div>
                        </div>

                        <!-- 2 -->
                        <div class="carousel-cell">
                            <img class="carousel-cell-image mb1" src="../../../assets/imgSession5/Slide1.png" alt="">
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="mb05 align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                            <div class="p6 gray align-l">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                            </div>
                        </div>

                        <!-- 3 -->
                        <div class="carousel-cell">
                            <img class="carousel-cell-image mb1" src="../../../assets/imgSession5/Slide2.png" alt="">
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="mb05 align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                            <div class="p6 gray align-l">
                                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                            </div>
                        </div>
                    </Flickity>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import Flickity from '../../../../node_modules/vue-flickity/src/flickity.vue';

export default {
    components : {
        Flickity
    },

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
}
</script>

<style lang="scss" scoped>
    @import 'HomeSession5.scss';
</style>

