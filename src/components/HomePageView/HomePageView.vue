@<template>
    <div class="home-page__container">
        <div class="home-page__session">
            <div class="home-page__session-1">
                <HomeSession1></HomeSession1>
            </div>
            <div class="home-page__session-2">
                <HomeSession2 />
            </div>
            <div class="home-page__session-3">
                <HomeSession3 />
            </div>
            <div class="home-page__session-4">
                <HomeSession4 />
            </div>
            <div class="home-page__session-5">
                <HomeSession5 />
            </div>
            <div class="home-page__session-6">
                <HomeSession6 />
            </div>
            <div class="home-page__session-7">
                <HomeSession7 />
            </div>
        </div>
    </div>
</template>

<script>
import HomeSession1 from "@/components/HomePageView/HomeSession1/HomeSession1.vue"
import HomeSession2 from "@/components/HomePageView/HomeSession2/HomeSession2.vue"
import HomeSession3 from "@/components/HomePageView/HomeSession3/HomeSession3.vue"
import HomeSession4 from "@/components/HomePageView/HomeSession4/HomeSession4.vue"
import HomeSession5 from "@/components/HomePageView/HomeSession5/HomeSession5.vue"
import HomeSession6 from "@/components/HomePageView/HomeSession6/HomeSession6.vue"
import HomeSession7 from "@/components/HomePageView/HomeSession7/HomeSession7.vue"
export default {
    components : {
        HomeSession1,
        HomeSession2,
        HomeSession3,
        HomeSession4,
        HomeSession5,
        HomeSession6,
        HomeSession7,
    }
}
</script>

<style scoped lang="scss">
    @import "HomePage.scss";
</style>