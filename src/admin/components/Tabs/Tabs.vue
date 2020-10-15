<template lang="pug">
  nav.tabs
    .container
      ul.tabs__list
        - var tabs = ['Обо мне', 'Работы', 'Отзывы'];
        each item in tabs
          li.tabs__item
            a.tab #{item}
</template>
<script>

</script>
<style lang="postcss" src="../../global.pcss"></style>
<style scoped lang="postcss" src="./Tabs.pcss"></style>
