<template>
  <div>
    <nav>
      <div class="nav-wrapper flex items-center">
        <div>
          <a href="" class="account bg-red text-white rounded-full">Личный кабинет</a>
          <a href="" class="catalog font-bold">Каталог услуг</a>
        </div>
        <a href="" class="flex gap-60 items-center">
          <img class="rocket" src="~/assets/img/rocket.svg" alt="Ракета" width="39">
          <p class="helper text-red">Онлайн помощник</p>
        </a>
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
    font-size: 16rem;
    padding: 7rem 30rem;
    margin-right: 31rem;
  }
  & .helper{
    font-weight: 700;
    font-size: 16rem;
  }
  & .catalog{
    font-size: 16rem;
  }
  & .rocket{
    width: 38rem;
  }
}
</style>
