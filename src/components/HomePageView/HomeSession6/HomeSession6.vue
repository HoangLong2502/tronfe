@<template>
    <div class="session-6__container container relative bg-white-1">
        <div class="session-6__title mb5">
            <div class="h2">
                Từ fanpage của Tròn
            </div>
        </div>

        <div class="session-6__slide z2">
            <Flickity
                ref="flickity" 
                :options="flickityOptions">

                <!-- 1 -->
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession6/Slide1.png" alt="">
                    <div class="f jcb aic mb05">
                        <div>
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                        </div>
                        <div class="pt075 pb075 pl1 pr1 border-radius-m border-primary">
                            <div class="p6 primary">Nhắn tin</div>
                        </div>
                    </div>
                    <div class="p6 gray align-l">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                    </div>
                </div>

                <!-- 2 -->
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession6/Slide2.png" alt="">
                    <div class="f jcb aic mb05">
                        <div>
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                        </div>
                        <div class="pt075 pb075 pl1 pr1 border-radius-m border-primary">
                            <div class="p6 primary">Nhắn tin</div>
                        </div>
                    </div>
                    <div class="p6 gray align-l">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                    </div>
                </div>

                <!-- 3 -->
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession6/Slide3.png" alt="">
                    <div class="f jcb aic mb05">
                        <div>
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                        </div>
                        <div class="pt075 pb075 pl1 pr1 border-radius-m border-primary">
                            <div class="p6 primary">Nhắn tin</div>
                        </div>
                    </div>
                    <div class="p6 gray align-l">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                    </div>
                </div>

                <!-- 4 -->
                <div class="carousel-cell">
                    <img class="carousel-cell-image mb15" src="../../../assets/imgSession3/1.png" alt="">
                    <div class="f jcb aic mb05">
                        <div>
                            <div class="mb1 align-l">
                                <div class="p6 gray">15 tháng 5, 2022</div>
                            </div>
                            <div class="align-l">
                                <div class="p2">Tên tin tức D</div>
                            </div>
                        </div>
                        <div class="pt075 pb075 pl1 pr1 border-radius-m border-primary">
                            <div class="p6 primary">Nhắn tin</div>
                        </div>
                    </div>
                    <div class="p6 gray align-l">
                        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Eu...
                    </div>
                </div>
            </Flickity>
        </div>

        <div class="session-6__logo z1 absolute logo-tron-small"></div>
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

<style scoped lang="scss">
    @import "HomeSession6.scss";
</style>