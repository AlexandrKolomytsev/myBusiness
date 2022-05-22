<template>
  <div>
    <HeaderComponent />
    <MainComponent />
    <AdvantagesComponent />
    <SuccessStories />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from '~/components/Header'
import MainComponent from '~/components/Main'
import AdvantagesComponent from '~/components/Advantages'
import SuccessStories from '~/components/Success-stories'
import FooterComponent from '~/components/Footer'
export default {
  name: 'IndexPage',
  components: { FooterComponent, SuccessStories, AdvantagesComponent, HeaderComponent, MainComponent }
}
</script>
