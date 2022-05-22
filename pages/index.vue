<template>
  <div>
    <HeaderComponent />
    <MainComponent />
    <AdvantagesComponent />
    <SuccessStories />
    <QuestionsComponent />
    <FooterComponent />
  </div>
</template>

<script>
import HeaderComponent from '~/components/Header'
import MainComponent from '~/components/Main'
import AdvantagesComponent from '~/components/Advantages'
import SuccessStories from '~/components/Success-stories'
import FooterComponent from '~/components/Footer'
import QuestionsComponent from '~/components/Questions'
export default {
  name: 'IndexPage',
  components: { QuestionsComponent, FooterComponent, SuccessStories, AdvantagesComponent, HeaderComponent, MainComponent }
}
</script>
