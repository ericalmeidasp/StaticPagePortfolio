<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cumque, inventore! Ex maxime veniam necessitatibus vitae ab voluptates quibusdam ullam repellendus, non et quae reprehenderit sint nam id dolores ut facere."
    />
    <Service
      title="Back End"
      description="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cumque, inventore! Ex maxime veniam necessitatibus vitae ab voluptates quibusdam ullam repellendus, non et quae reprehenderit sint nam id dolores ut facere."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cumque, inventore! Ex maxime veniam necessitatibus vitae ab voluptates quibusdam ullam repellendus, non et quae reprehenderit sint nam id dolores ut facere."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({ components: { Service } })
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
