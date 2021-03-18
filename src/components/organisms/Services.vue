<template>
  <div class="services">
    <Service
      title="front end"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores iure pariatur nulla sequi voluptatum eius nostrum, maxime aspernatur repellat alias natus earum deserunt sunt rem culpa veritatis facilis officiis ad!"
    />
    <Service
      title="back end"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores iure pariatur nulla sequi voluptatum eius nostrum, maxime aspernatur repellat alias natus earum deserunt sunt rem culpa veritatis facilis officiis ad!"
    />
    <Service
      title="Manutenção"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Dolores iure pariatur nulla sequi voluptatum eius nostrum, maxime aspernatur repellat alias natus earum deserunt sunt rem culpa veritatis facilis officiis ad!"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
