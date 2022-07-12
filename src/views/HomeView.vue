<template>
  <div class="home bg-primary-1 h100vh">
    <NavView class="fixed w100"></NavView>
    <HomePageView v-if="$route.params.path === 'homePage'"/>
    <ContactView v-else-if="$route.params.path === 'contact'"></ContactView>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

import NavView from '@/components/NavView/NavView.vue'
import HomePageView from "@/components/HomePageView/HomePageView.vue"
import ContactView from "@/components/ContactView/ContactView.vue"

@Component({
  components: {
    HelloWorld,
    NavView,
    HomePageView,
    ContactView
  },
})
export default class HomeView extends Vue {}
</script>
