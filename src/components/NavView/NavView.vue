@<template>
    <div class="nav__container relative pt075 pb075 shadow bg-white-1 z100">
        <div class="nav__body w100 f jcc aic">
            <router-link
                :to=" { name: 'page' , params : { path : item.path } } "
                class="f aic cursor"
                v-for="(item, index) in NavItemLeft"
                :key="index">
                    <div 
                        class="p2 primary"
                        v-if="$route.params.path === item.path">
                        {{ item.title }}
                    </div>
                    <div 
                        class="p2"
                        v-else>
                            {{ item.title }}
                    </div>

                    <div 
                        v-if="item.dropDown"
                        class="icon--arrown ml05"></div>
            </router-link>
            <div class="icon--tron"></div>
            <div
                class="cursor"
                v-for="(item, key) in NavItemRight"
                :key="key">
                    <div 
                        class="p2 primary"
                        v-if="$route.params.path === item.path">
                        {{ item.title }}
                    </div>
                    <div 
                        class="p2"
                        v-else>
                            {{ item.title }}
                    </div>
            </div>
        </div>

        <div class="nav__action absolute f aic">
            <div class="p2 pt075 pb075 pl2 pr2 border border-radius primary">Đăng nhập</div>
            <div class="p2 ml05 pt075 pb075 pl2 pr2 border-radius bg-primary white">Đăng ký</div>
        </div>
    </div>
</template>

<script>
export default {
    data () {
        return {
            NavItemLeft : [
                {
                    title: "Trang chủ",
                    dropDown: false,
                    path: 'homePage'
                },
                {
                    title: "Về Tròn",
                    dropDown: false,
                    path: 'aboutTron'
                },
                {
                    title: "Dịch vụ",
                    dropDown: true,
                    path: 'service'
                },
                {
                    title: "Sản phẩm",
                    dropDown: true,
                    path: 'product'
                }
            ],
            NavItemRight : [
                {
                    title: "Gói dịch vụ doanh nghiệp",
                    dropDown: false,
                    path: 'business-service '
                },
                {
                    title: "Tin Tức",
                    dropDown: false,
                    path: 'news'
                },
                {
                    title: "Liên hệ",
                    dropDown: false,
                    path: 'contact'
                },
            ]
        }
    }
}
</script>

<style scoped lang='scss'>
    @import 'NavView.scss';
</style>