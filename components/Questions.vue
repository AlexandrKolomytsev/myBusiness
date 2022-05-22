<template>
  <div>
    <div class="questions-block">
      <img class="questions-block__img" src="~assets/img/border.svg" alt="border" width="1920">
      <div class="questions-block__wrapper">
        <h3 class="questions-block__title">
          Есть вопросы?
        </h3>
        <p class="questions-block__text">
          Задайте интересующие вас вопросы<br>
          онлайн помощнику
        </p>
        <a href="" class="questions-block__button">
          <img class="questions-block__button-img" src="~assets/img/rocket-two.svg" alt="Ракета" width="20">
          <p class="questions-block__button-text">
            Онлайн помощник
          </p>
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'QuestionsComponent'
}
</script>

<style lang="scss" scoped>
.questions-block{
  position: relative;
  & .questions-block__img{
    position: absolute;
    bottom: -8rem;
    width: 100%;
    height: 300rem;
    transform: rotate(180deg);
    z-index: -1;
  }
  & .questions-block__wrapper{
    width: 263rem;
    position: absolute;
    left: 50%;
    transform: translate(-50%, 0);
    bottom: 68rem;
    & .questions-block__title{
      font-weight: 700;
      font-size: 35rem;
      line-height: 52rem;
      text-align: center;
      color: #000000;
    }
    & .questions-block__text{
      font-weight: 400;
      font-size: 16rem;
      line-height: 24rem;
      text-align: center;
      color: #000000;
      margin-bottom: 29rem;
    }
    & .questions-block__button{
      display: flex;
      background: #FE5F5F;
      border-radius: 50rem;
      padding: 10rem 53rem;
      align-items: center;
      gap: 10rem;
      & .questions-block__button-img{
        width: 13rem;
      }
      & .questions-block__button-text{
        font-weight: 700;
        font-size: 16rem;
        line-height: 20rem;
        color: #FFFFFF;
        white-space: nowrap;
      }
    }
  }
}
</style>
