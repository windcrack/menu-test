<template>
  <footer>
    <ul class="footer-items">
      <li class="footer-item">
        <img src="../assets/ficon1.svg" alt="" class="footer-icon" />
        <span class="footer-text">Главная</span>
      </li>
      <li class="footer-item">
        <img src="../assets/ficon2.svg" alt="" class="footer-icon" />
        <span class="footer-text">Каталог</span>
      </li>
      <li class="footer-item">
        <img src="../assets/ficon3.svg" alt="" class="footer-icon" />
        <span class="footer-text">Landscape</span>
      </li>
      <li class="footer-item">
        <img src="../assets/ficon4.svg" alt="" class="footer-icon" />
        <span class="footer-text">Стройка</span>
      </li>
      <li class="footer-item">
        <img src="../assets/ficon5.svg" alt="" class="footer-icon" />
        <span class="footer-text active">Меню</span>
      </li>
    </ul>
  </footer>
</template>

<style lang="sass">
footer
    background: rgba(154, 152, 154, 0.94)
    backdrop-filter: blur(20px)
    border-radius: 16px
    padding: 16px 12px
.footer
    &-items
        display: flex
        list-style: none
        justify-content: space-between
    &-item
        display: flex
        flex-direction: column
        align-items: center
        cursor: pointer

    &-icon
        margin-bottom: 6px

    &-text
        font-weight: 750
        font-size: 10px
        line-height: 100%
</style>