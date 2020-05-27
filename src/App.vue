<template>
  <div id="app">
    <TopBar />
    <SideMenu />
    <MainContent />
  </div>
</template>

<script>

import SideMenu from './components/SideMenu';
import TopBar from './components/TopBar';
import MainContent from './components/MainContent';

export default {
  name: 'App',
  components: { 
    SideMenu,
    TopBar,
    MainContent
  }
}
</script>

<style>
  body, html, * {
    margin: 0;
    padding: 0;
  }

  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    background-color:#f3f4f6;
    margin:0;
    padding:0;
  }
</style>
