<template>
  <div id="app">
    <the-header />
    <Container>
      <BaseButton>Satın Al</BaseButton>
      <BaseButton :color="'green'">Satın Al</BaseButton>
      <BaseButton :color="'orange'" size="medium">Satın Al</BaseButton>
      <BaseButton :color="'green'" size="large">Ödeme Yap</BaseButton>
    </Container>

    <Container style="margin-top: 20px">
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti, officiis. Voluptatem temporibus, beatae harum placeat praesentium veniam aperiam, cupiditate alias similique cumque perferendis ex illum nisi iusto eius sapiente quidem, ullam assumenda laboriosam incidunt debitis iste expedita quaerat ab. Voluptas eos assumenda quia, delectus ea voluptates aliquam odit dicta iure dolor laudantium vel magnam labore inventore, blanditiis rem id? Commodi natus maxime repellat expedita eaque quos repellendus quam, vero quo aperiam accusamus animi non reiciendis soluta pariatur dolorem saepe iure dolore excepturi optio est quas aliquam? Quis labore, soluta consectetur minima optio non maiores. Molestiae at voluptatibus fugit libero a.
    </Container>
    
  </div>
</template>

<script>
import BaseButton from './components/BaseButton.vue'
import Container from './components/common/Container.vue'
import TheHeader from './components/Shared/TheHeader.vue'
export default {
  name: 'App',
  components: {
    BaseButton,
    Container,
    TheHeader
  }
}
</script>
