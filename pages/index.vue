<template>
  <div>
    <HeaderComponent />
    <MainComponent />
  </div>
</template>

<script>
import HeaderComponent from '~/components/Header'
import MainComponent from '~/components/Main'
export default {
  name: 'IndexPage',
  components: { HeaderComponent, MainComponent }
}
</script>
