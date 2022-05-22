<template>
  <div>
    <div class="footer">
      <div class="footer__wrapper">
        <div class="footer-left">
          <a href="" class="footer__item">
            Услуги  и поддержка
          </a>
          <a href="" class="footer__item">
            Сервисы для бизнеса
          </a>
          <a href="" class="footer__item">
            Общая информация
          </a>
          <a href="" class="footer__item">
            Защита бизнеса
          </a>
        </div>
        <div class="footer-right">
          <a href="" class="footer__item">
            service@in-line.ru
          </a>
          <a href="" class="footer__item">
            8-800-200-74-30
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'FooterComponent'
}
</script>

<style lang="scss" scoped>
.footer{
  width: 100%;
  height: 86rem;
  background: #2F2F2F;
  display: flex;
  align-items: center;
  & .footer__wrapper{
    width: 1125rem;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
  }
  & .footer-left{
    display: flex;
    gap: 47rem;
  }
  & .footer-right{
    display: flex;
    gap: 34rem;
  }
  & .footer__item{
    font-weight: 700;
    font-size: 16rem;
    line-height: 24rem;

    letter-spacing: 0.01em;
    color: #FFFFFF;
  }
}
</style>
