<template lang="pug">
  header.header
    .container.header__container
      .header__wrapper
        .header__left
          .user
            .user__avatar.user__avatar--background
            .user__name Богдан Сутужко
            .admin-alert Панель администрирования
        .header__center
        .header__right
          a.logout(
            href="/"
          ) Выйти
</template>
<script>

</script>
<style lang="postcss" src="../../global.pcss"></style>
<style scoped lang="postcss" src="./Header.pcss"></style>
