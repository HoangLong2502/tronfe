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
        </div>
    </div>
</template>

<script>
import HomeSession1 from "@/components/HomePageView/HomeSession1/HomeSession1.vue"
import HomeSession2 from "@/components/HomePageView/HomeSession2/HomeSession2.vue"
import HomeSession3 from "@/components/HomePageView/HomeSession3/HomeSession3.vue"
export default {
    components : {
        HomeSession1,
        HomeSession2,
        HomeSession3
    }
}
</script>

<style scoped lang="scss">
    @import "HomePage.scss";
</style>