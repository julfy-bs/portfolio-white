<template lang="pug">
  .wrapper.admin-wrapper
    Header
    Tabs
    About
</template>
<script>
import Header from "./components/Header/Header";
import Tabs from "./components/Tabs/Tabs";
import About from "./components/About/About";
export default {
  components: {About, Tabs, Header}
}
</script>
<style lang="postcss" src="./global.pcss"></style>
