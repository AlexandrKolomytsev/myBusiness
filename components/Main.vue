<template>
  <div>
    <div class="nav-wrapper">
      <img class="background-image -z-1 absolute top-0 left-0" src="~assets/img/svg-sprite/background-main.svg" alt="Фон" width="16">
      <img class="logo my-16" src="~assets/img/logo.svg" alt="Логотип" width="209">
      <h1 class="main-text">
        Мой бизнес - цифровая платформа для тех, кто хочет открыть и развивать свой бизнес
      </h1>
      <div class="background-border-block absolute">
        <img src="~assets/img/border.svg" alt="Граница" width="1920">
        <p class="main-description">Для начала работы ответьте на вопрос,<br>
          есть ли у вас уже существующий бизнес? </p>
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
  width: 576px;
  height: 152px;
  font-style: normal;
  font-weight: 700;
  font-size: 35px;
  line-height: 111.4%;
  color: #2B2B2B;
}
.main-description{
  font-style: normal;
  font-weight: 700;
  font-size: 30rem;
  line-height: 35rem;
  position: absolute;
  top: 85rem;
  left: 50%;
  transform: translate(-50%, 0);
}
.logo{
  margin: 63rem 0;
}
</style>
