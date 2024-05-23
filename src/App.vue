<script setup lang="ts">
import { onMounted, ref } from 'vue';
import { RouterView } from 'vue-router';

import AppHeader from '@/components/AppHeader.vue';
import AppFooter from '@/components/AppFooter.vue';

const loaded = ref(false);

onMounted(() => {
  loaded.value = true;
});
</script>

<template>
  <div class="flex flex-col md:p-8 p-4 min-h-screen w-full justify-between">
    <Transition name="slide" appear>
      <AppHeader />
    </Transition>
    <main>
      <RouterView v-if="loaded" />
    </main>
    <Transition name="slide" appear>
      <AppFooter />
    </Transition>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;700&family=Oxanium:wght@200;400;700&display=swap');
.slide-enter {
  opacity: 0;
}

.slide-enter-active {
  animation: slide-in .5s ease-in forwards;
  transition: opacity 3s;
}

.slide-leave-active {
  animation: slide-out .5s ease-out forwards;
  opacity: 0;
  transition: opacity 3s;
}

@keyframes slide-in {
  from {
    transform: translateY(-20px);
  }
  to {
    transform: translateY(0);
  }
}

@keyframes slide-out {
  from {
    transform: translateY(0);
  }
  to {
    transform: translateY(-20px);
  }
}
</style>
