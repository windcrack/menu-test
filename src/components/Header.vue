<template>
  <header class="header-body">
    <a href="#" class="header-body__link">Мой ИЖС</a>
    <div class="header-body__left">
      <div class="header-body__round">
        <img src="../assets/Gimg.svg" alt="G" class="header-body__img" />
      </div>
      <p class="header-body__text">статус</p>
    </div>
  </header>
</template>

<style lang="sass">
.header-body
  display: flex
  justify-content: space-between
  padding: 8px 0 9px
  align-items: center
  margin-bottom: 24px

  &__link
    color: #090909
    font-weight: 750
    font-size: 26px
    line-height: 120%

  &__left
    display: flex

  &__round
    background: linear-gradient(90deg, #C5ACFF 0%, #FBC2EB 100%)
    width: 24px
    height: 24px
    border-radius: 24px
    display: flex
    align-items: center
    justify-content: center

  &__text
    margin-left: 8px
    font-weight: 750
    font-size: 14px
    line-height: 120%
    display: flex
    align-items: center
</style>