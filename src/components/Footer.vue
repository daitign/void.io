<template>
  <div class="bg-gray-900 h-20 flex justify-center items-center">
    <a class="text-neutral-500 font-light cursor-pointer dark:text-white" href="https://instagram.com/daitignx" target="_blank">
      <h2 class="pt-3 pl-5 flex items-center">
        <font-awesome-icon
          class="fa-2xl f-blue w-20"
          :icon="['fab', 'instagram']"
        />
      </h2>
    </a>
    <a class="text-neutral-500 font-light cursor-pointer dark:text-white" href="https://github.com/daitign" target="_blank">
      <h2 class="pt-3 pl-5 flex items-center">
        <font-awesome-icon
          class="fa-2xl f-blue w-20" 
          :icon="['fab', 'github']" 
        />
      </h2>
    </a>
    <a class="text-neutral-500 font-light cursor-pointer dark:text-white" href="https://t.me/stxngn" target="_blank">
      <h2 class="pt-3 pl-5 flex items-center">
        <font-awesome-icon
          class="fa-2xl f-blue w-20" 
          :icon="['fab', 'telegram']" 
        />
      </h2>
    </a>
  </div>
</template>

<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome';
import { library } from '@fortawesome/fontawesome-svg-core';
import { faGithub, faInstagram, faTelegram } from '@fortawesome/free-brands-svg-icons';

library.add(faGithub, faInstagram, faTelegram);

export default {
  components: {
    FontAwesomeIcon,
  },
};
</script>

<style scoped>
/* Add any custom styling here */
</style>
