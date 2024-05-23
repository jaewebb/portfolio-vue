<script setup lang="ts">

</script>

<template>
  <Transition name="slide" appear>
    <div
      class="
        flex
        md:flex-row flex-col
        items-center
        justify-between
        2xl:w-1/2 w-full
        mx-auto"
    >
      <div class="md:block hidden">
        <h2 class="text-lime-500 neon-green">Jae Webb</h2>
        <h3 class="text-sky-500 neon-blue">Senior App Developer</h3>
      </div>
      <div class="md:w-2/4 w-full">
        <h1 class="text-lime-500">Mobile Friendly Web Sites and Apps</h1>
        <div>
          <p>
            When we plan to go somewhere new, whether that be a beach,
            a board game cafe, or even a new city,
            what's the first thing that we do?
            We look it up online!
          </p>

          <p>
            These days,
            it's vital to have a solid source of information on the web
            in order to attract new customers and keep current ones updated.
            When potential customers are given a choice
            between two similar business options,
            having a strong online presence can tip the scales in your favour.
          </p>

          <p>
            This is where I come in!
            I will work with you to create a custom informational website,
            or web app, that can attract potential customers and communicate
            the unique benefits that your company has to offer.
          </p>
        </div>
      </div>
    </div>
  </Transition>
</template>

<style scoped>
.neon-green {
  animation: neon-green 2s ease-in-out infinite alternate;
}
.neon-blue {
  animation: neon-blue 2s ease-in-out infinite alternate;
}

@keyframes neon-green {
  from {
    text-shadow:
      0 0 4px #84cc1680,
      0 0 8px #84cc1680,
      0 0 12px #84cc1680,
      0 0 16px #84cc165C,
      0 0 20px #84cc165C,
      0 0 24px #84cc165C;
  }
  to {
    text-shadow:
    0 0 1px #84cc1680,
    0 0 2px #84cc1680,
    0 0 3px #84cc1680,
    0 0 4px #84cc165C,
    0 0 5px #84cc165C,
    0 0 6px #84cc165C;
  }
}

@keyframes neon-blue {
  from {
    text-shadow:
      0 0 4px #0ea5e980,
      0 0 8px #0ea5e980,
      0 0 12px #0ea5e980,
      0 0 16px #0ea5e95C,
      0 0 20px #0ea5e95C,
      0 0 24px #0ea5e95C;
  }
  to {
    text-shadow:
    0 0 1px #0ea5e980,
    0 0 2px #0ea5e980,
    0 0 3px #0ea5e980,
    0 0 4px #0ea5e95C,
    0 0 5px #0ea5e95C,
    0 0 6px #0ea5e95C;
  }
}
</style>
