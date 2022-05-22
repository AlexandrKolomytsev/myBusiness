<template>
  <div>
    <div class="nav-wrapper">
      <img class="background-image -z-1 absolute top-0 left-0" src="~assets/img/background-main.svg" alt="Фон" width="1920">
      <img class="logo my-16" src="~assets/img/logo.svg" alt="Логотип" width="209">
      <h1 class="main-text">
        Мой бизнес - цифровая платформа для тех, кто хочет открыть и развивать свой бизнес
      </h1>
      <div class="background-border-block absolute">
        <img src="~assets/img/border.svg" alt="Граница" width="1920">
        <div class="main-block">
          <p class="main-block__description">
            Для начала работы ответьте на вопрос,<br>
            есть ли у вас уже существующий бизнес?
          </p>
          <div class="main-block__buttons">
            <a href="" class="main-block__button-red">
              Да, у меня уже есть бизнес
            </a>
            <a href="" class="main-block__button-blue">
              Нет, но планирую открыть
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainComponent'
}
</script>
<style lang="scss" scoped>
.background-image{
  height: 846rem;
  width: 1920rem;
}
.background-border-block{
  top: 699rem;
  left: 0;
}
.main-text{
  width: 576rem;
  height: 152rem;
  font-style: normal;
  font-weight: 700;
  font-size: 35rem;
  line-height: 111.4%;
  color: #2B2B2B;
}
.main-block{
  width: fit-content;
  position: absolute;
  top: 30rem;
  left: 50%;
  transform: translate(-50%, 0);
  & .main-block__description{
    font-style: normal;
    font-weight: 700;
    font-size: 30rem;
    line-height: 35rem;
    margin-bottom: 40rem;
    text-align: center;
  }
  & .main-block__buttons{
    display: flex;
    gap: 26rem;
    & .main-block__button-red{
      font-weight: 400;
      font-size: 22rem;
      line-height: 27rem;
      color: #FFFFFF;
      background: #FE5F5F;
      border-radius: 50rem;
      padding: 13rem 53rem 13rem 46rem;
    }
    & .main-block__button-blue{
      font-weight: 400;
      font-size: 22rem;
      line-height: 27rem;
      color: #FFFFFF;
      background: #3865A7;
      border-radius: 50rem;
      padding: 13rem 75rem 13rem 58rem;
    }
  }
}
.logo{
  width: 208rem;
  margin: 63rem 0;
}
</style>
