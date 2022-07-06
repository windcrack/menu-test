<template>
  <ul class="menu-items">
    <li class="menu-item">
      <img src="../assets/icon1.svg" class="icon" />
      <a href="" class="menu-item__link">Как это работает</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon2.svg" class="icon" />
      <a href="" class="menu-item__link">ИЖС Стандарт</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon3.svg" class="icon" />
      <a href="" class="menu-item__link">Договоры</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon4.svg" class="icon" />
      <a href="" class="menu-item__link">Росреестр</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon5.svg" class="icon" />
      <a href="" class="menu-item__link">Помощь</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon6.svg" class="icon" />
      <a href="" class="menu-item__link">Промокоды</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon7.svg" class="icon" />
      <a href="" class="menu-item__link">Партнёрам</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
    <li class="menu-item">
      <img src="../assets/icon8.svg" class="icon" />
      <a href="" class="menu-item__link">Избранное</a>
      <img src="../assets/shevron.svg" class="menu-item__shevron" />
    </li>
  </ul>
</template>

<style lang="sass">
.menu-items
    list-style: none
    display: flex
    flex-direction: column
    margin-bottom: 48px
.menu-item
    display: flex
    align-items: center
    padding: 22px 0
    border-bottom: 1px solid #E0E0E0
    cursor: pointer

    &__link
        margin-left: 12px
        font-weight: 750
        font-size: 16px
        line-height: 120%
        color: #2D2D2D

    &__shevron
        margin-left: auto
</style>