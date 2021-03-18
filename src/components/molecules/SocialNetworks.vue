<template>
  <div class="social-networks">
    <SocialLinks name="Github" to="https://github.com" icon="github.svg" />
    <SocialLinks name="Twitter" to="https://Twitter.com" icon="twitter.svg" />
    <SocialLinks
      name="Facebook"
      to="https://facebook.com"
      icon="facebook.svg"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { SocialLinks } from '@/components/atoms'

export default defineComponent({
  components: { SocialLinks }
})
</script>

<style lang="scss" scoped>
.social-networks {
  display: grid;
  grid-gap: 1rem;
}
</style>
