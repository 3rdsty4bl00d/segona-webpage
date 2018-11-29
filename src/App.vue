<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col-md-12 pull-right">
            <app-header></app-header>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12">
          <app-home></app-home>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12">
          <app-about></app-about>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12">
          <app-facts></app-facts>
        </div>
      </div>
      <div class="row">
        <div class="col-md-12">
          <app-services></app-services>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Home from './components/Home.vue';
import About from './components/About.vue';
import Facts from './components/Facts.vue';
import Services from './components/Services.vue';

export default {
  components: {
    appAbout: About,
    appHome: Home,
    appHeader: Header,
    appFacts: Facts,
    appServices: Services
  }
}
</script>

<style>
.container {
  height: 100%;
  width: 100%;
}
</style>
