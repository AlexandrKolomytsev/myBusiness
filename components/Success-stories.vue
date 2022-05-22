<template>
  <div>
    <div class="success-stories">
      <h2 class="success-stories__title">
        Истории успеха
      </h2>
      <div class="success-stories-blocks">
        <div class="success-stories-block">
          <img class="success-stories__img-one" src="~assets/img/success1.svg" alt="Пекарня" width="200">
          <div class="success-stories-block-inform">
            <p class="success-stories__name">
              Пекарня “Русские традиции”
            </p>
            <div class="success-stories__red-block">
              <img src="~assets/img/redBlock.svg" alt="Блок" width="40">
              <p class="success-stories__red-text">
                Как говорит сам Владимир: «мне хотелось, чтобы все узнали, что<br> такое русская кухня», «обьяснить, что она жива».
              </p>
            </div>
            <p class="success-stories__text">
              Чтобы мини-пекарня стала рентабельным бизнесом, необходимы строгие расчеты, учет рисков и перспектив, анализ рынка, налаживание сбыта.
            </p>
            <a href="" class="success-stories__button">
              <div class="success-stories__href">
                <p class="success-stories__href-name">Читать историю</p>
                <img class="success-stories__href-arrow" src="~assets/img/arrow.svg" alt="Стрелка" width="10">
              </div>
            </a>
          </div>
        </div>
        <div class="success-stories-block">
          <img class="success-stories__img-one" src="~assets/img/success2.svg" alt="Автомастерская" width="200">
          <div class="success-stories-block-inform">
            <p class="success-stories__name">
              Автомастерская
            </p>
            <div class="success-stories__red-block">
              <img src="~assets/img/redBlock.svg" alt="Блок" width="40">
              <p class="success-stories__red-text">
                Первые дни независимости. Когда не нужно рано вставать, когда не нужно отпрашиваться, что бы успеть съездить в магазин, когда удобно.
              </p>
            </div>
            <p class="success-stories__text">
              Встреча в городе Н с моими будущими партнерами была плодотворной. Я не смог заснуть до пяти утра – не потому что не спалось, но потому что мысли о будущих перспективах просто взрывали мой мозг.
            </p>
            <a href="" class="success-stories__button">
              <div class="success-stories__href">
                <p class="success-stories__href-name">Читать историю</p>
                <img class="success-stories__href-arrow" src="~assets/img/arrow.svg" alt="Стрелка" width="10">
              </div>
            </a>
          </div>
        </div>
        <div class="success-stories-block">
          <img class="success-stories__img-one" src="~assets/img/success3.svg" alt="Салон красоты" width="200">
          <div class="success-stories-block-inform">
            <p class="success-stories__name">
              Салон красоты “Эмират”
            </p>
            <div class="success-stories__red-block">
              <img src="~assets/img/redBlock.svg" alt="Блок" width="40">
              <p class="success-stories__red-text">
                Когда же появилась возможность открыть свой бизнес, я рассматривала различные варианты, изучала всевозможные направления.
              </p>
            </div>
            <a href="" class="success-stories__button success-stories__button-end">
              <div class="success-stories__href">
                <p class="success-stories__href-name">Читать историю</p>
                <img class="success-stories__href-arrow" src="~assets/img/arrow.svg" alt="Стрелка" width="10">
              </div>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SuccessStories'
}
</script>

<style lang="scss" scoped>
.success-stories{
  width: 980rem;
  margin: 0 auto 472rem;
  & .success-stories__title{
    margin: 0 auto 40rem;
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
  & .success-stories-blocks{
    & .success-stories-block{
      display: flex;
      justify-content: space-between;
      align-items: center;
      &:nth-child(2n){
        flex-direction: row-reverse
      }
      & .success-stories__name{
        font-weight: 700;
        font-size: 24rem;
        line-height: 23rem;
        color: #2B2B2B;
        margin-bottom: 22rem;
      }
      & .success-stories__red-block{
        display: flex;
        gap: 20rem;
        margin-bottom: 15rem;
        & .success-stories__red-text{
          font-weight: 700;
          font-size: 16rem;
          line-height: 20rem;
          color: #FE5F5F;
          width: 518rem;
        }
      }
      & .success-stories__text{
        font-weight: 400;
        font-size: 16rem;
        line-height: 18rem;
        color: #000000;
        width: 567rem;
        margin-bottom: 17rem;
      }
      & .success-stories__button{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 177rem;
        height: 39rem;
        background: #3864A7;
        border-radius: 50rem;
        & .success-stories__href{
          display: flex;
          gap: 13rem;
          justify-content: center;
          align-items: center;
          margin: auto 0;
          & .success-stories__href-name{
            font-weight: 400;
            font-size: 14rem;
            line-height: 17rem;
            color: #FFFFFF;
          }
          & .success-stories__href-arrow{
            width: 16rem;
          }
        }
      }
      & .success-stories__button-end{
        margin-top: 88rem;
      }
    }
  }
}
.success-stories__img-one{
  width: 326rem;
}
</style>
