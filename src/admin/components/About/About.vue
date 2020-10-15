<template lang="pug">
  section.about
    .container
      .about__wrapper
        .about__headline
          h1.about__title Блок «Обо мне»
          .button
            .button__icon
              .icon
            span.button__text Добавить группу
        ul.about__list
          li.about__item.card
            .form.about-form
              form.about-form__header.form
                input(
                  placeholder='Название новой группы'
                ).about-form__input.about-form__input--group
                .about-form__icons
                  button.button__icon.button__icon--tick
                  button.button__icon.button__icon--close

              .about-form__main
                .about-form__table
                  table.table-skills
                    tr.table-skills__row
                      td.table-skills__skill skill
                      td.table-skills__value 10
                      td.table-skills__percent %
                      td.table-skills__icons
                        .about-form__icons
                          button.button__icon.button__icon--edit
                          button.button__icon.button__icon--delete
              .about-form__footer

</template>
<script>

</script>
<style lang="postcss" src="../../global.pcss"></style>
<style scoped lang="postcss" src="./About.pcss"></style>


