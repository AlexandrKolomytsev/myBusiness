<template>
  <div>
    <div class="advantages">
      <h2 class="advantages__title">
        Преимущества
      </h2>
      <div class="advantages__blocks">
        <div class="advantages__block">
          <img src="~assets/img/advantages1.svg" alt="Приемущества1" width="179">
          <p class="advantages__block-number">
            482
          </p>
          <p class="advantages__block-text">
            Организаций поддержки<br>
            по Российской Федерации
          </p>
        </div>
        <div class="advantages__block">
          <img src="~assets/img/advantages2.svg" alt="Приемущества2" width="179">
          <p class="advantages__block-number">
            5240
          </p>
          <p class="advantages__block-text">
            Оказано услуг<br>
            государственной поддержки
          </p>
        </div>
        <div class="advantages__block">
          <img src="~assets/img/advantages3.svg" alt="Приемущества3" width="179">
          <p class="advantages__block-number">
            1360
          </p>
          <p class="advantages__block-text">
            Зарегестрировано<br>
            участников проекта
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AdvantagesComponent'
}
</script>

<style lang="scss" scoped>
  .advantages{
    width: 920rem;
    margin: 700rem auto 0;
    & .advantages__title{
      margin: 0 auto;
      font-style: normal;
      font-weight: 700;
      font-size: 40rem;
      line-height: 24rem;
      text-align: center;
      color: #000000;
      position: relative;
      width: fit-content;
      &:before{
        position: absolute;
        left: -16rem;
        top: 50%;
        transform: translate(0, -50%) rotate(45deg);
        content: '';
        width: 6.6rem;
        height: 6.6rem;
        background: #FE5F5F;
      }
      &:after{
        position: absolute;
        right: -16rem;
        top: 50%;
        transform: translate(0, -50%) rotate(45deg);
        content: '';
        width: 6.6rem;
        height: 6.6rem;
        background: #FE5F5F;
      }
    }
    & .advantages__blocks{
      display: flex;
      justify-content: space-between;
      margin: 72rem 0 240rem;
      & .advantages__block{
        display: flex;
        flex-direction: column;
        align-items: center;
        & .advantages__block-number{
          font-weight: 700;
          font-size: 50rem;
          line-height: 61rem;
          color: #3865A7;
        }
        & .advantages__block-text{
          font-weight: 700;
          font-size: 20rem;
          line-height: 24rem;
          color: #000000;
          text-align: center;
        }
      }
    }
  }
</style>
