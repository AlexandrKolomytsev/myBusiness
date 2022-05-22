<template>
  <div>
    <nav>
      <div class="nav-wrapper flex items-center">
        <div>
          <a href="" class="account bg-red text-white rounded-full">Личный кабинет</a>
          <a href="" class="font-bold">Каталог услуг</a>
        </div>
        <div class="flex gap-60 items-center">
          <img src="~/assets/img/rocket.svg" alt="Логотип" width="39">
          <a class="helper text-red" href="">Онлайн помощник</a>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HeaderComponent'
}
</script>

<style lang="scss" scoped>
.nav-wrapper{
  margin: 35rem auto 0;
  justify-content: space-between;
  & .account{
    padding: 7rem 30rem;
    margin-right: 31rem;
  }
  & .helper{
    font-weight: 700;
    font-size: 16px;
  }
}
</style>
