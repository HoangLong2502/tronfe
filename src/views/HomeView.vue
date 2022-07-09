<template>
  <div class="home bg-primary-1 h100vh">
    <NavView class="fixed w100"></NavView>
    <HomePageView v-if="$route.params.path === 'homePage'"/>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

import NavView from '@/components/NavView/NavView.vue'
import HomePageView from "@/components/HomePageView/HomePageView.vue"

@Component({
  components: {
    HelloWorld,
    NavView,
    HomePageView
  },
})
export default class HomeView extends Vue {}
</script>
