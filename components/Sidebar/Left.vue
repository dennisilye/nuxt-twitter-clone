<template>
  <div class="h-screen flex flex-col">
    <div class="p-2 my-2 hover:bg-blue-50 rounded-full w-min
    dark:hover:bg-white/20" :class="defaultTransition">
      <nuxt-link to="/">
        <div class="w-8 h-8">
          <LogoTwitter />
        </div>
      </nuxt-link>
    </div>
  </div>
</template>

<script setup lang="ts">
import useTailwindConfig from '../../composables/useTailwindConfig';

const { defaultTransition } = useTailwindConfig()

</script>