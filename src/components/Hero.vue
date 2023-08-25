<template>
  <div
    class="flex h-screen-80 max-w-7xl m-center mt-24 md:flex-col lg:flex-row md:pt-10"
  >
    <div class="info flex flex-col items-start lg:w-3/6 m-auto">
      <h2
        data-aos="fade-right"
        data-aos-delay="500"
        data-aos-duration="500"
        class="text-5xl pb-3 font-extrabold f-black name dark:text-white duration-1000 typewriter"
      >
        Daite Jemark
      </h2>
      <h4
        class="text-lg pb-2 f-gray dark:text-white duration-1000"
        data-aos="fade-right"
        data-aos-delay="700"
        data-aos-duration="500"
      >
      ◉◉◉
      </h4>
      <h5
        class="text-sm pb-12 f-gray dark:text-white duration-1000"
        data-aos="fade-right"
        data-aos-delay="800"
        data-aos-duration="500"
      >
        To use and impart my capabilities I gained to facilitate and provide
        necessary learning required to develop and compete in today’s society. I
        have a strong interest in all areas of work most especially with regard
        to Information Technology. I am passionately committed to promote a
        positive and dynamic environment in doing my job.
      </h5>
      <div data-aos="fade-right" data-aos-delay="800" data-aos-duration="700">
        <a
          class="btn-accent cursor-pointer flex items-center"
          href="mailto:daitejmrk@gmail.com"
        >
          <span> Contact Me&nbsp;</span>
          <span
            ><font-awesome-icon class="w-4" :icon="['fas', 'paper-plane']"
          /></span>
        </a>
      </div>
    </div>
    <div class="profile-image lg:w-3/6 flex hidden md:flex md:m-auto md:pt-16">
      <img
        data-aos="zoom-in-right"
        data-aos-delay="1500"
        data-aos-duration="800"
        :class="`m-auto clipped light ismall img-first md:w-auto`"
        src="https://drive.google.com/uc?id=1qWAWdZrwl-NrbvLuj-e-Ctomeo27NgDO"
        alt=""
        width="400"
      />
      <img
        data-aos="zoom-in-right"
        data-aos-delay="1700"
        data-aos-duration="800"
        class="m-auto clipped light imedium img-center md:w-auto"
        src="https://drive.google.com/uc?id=1LdZ7OWPBdf8v8KF4DFSEgiM6Pio5s0MO"
        alt=""
        width="400"
      />
      <img
        data-aos="zoom-in-right"
        data-aos-delay="1900"
        data-aos-duration="800"
        class="m-auto clipped light ismall img-last md:w-auto"
        src="https://drive.google.com/uc?id=1kOYvI65kWV8InpqKMBIaZW4c0IywgL5Y"
        alt=""
        width="400"
      />
    </div>
  </div>
</template>
<script lang="ts" setup>
import { watch } from "vue";
import { useDark, useToggle } from "@vueuse/core";
const isDark = useDark();
</script>
<style lang="scss" scoped>
.clipped {
  clip-path: polygon(25% 0%, 100% 0%, 75% 100%, 0% 100%);
}
.ismall {
  height: 19rem;
}
.imedium {
  height: 25rem;
}

.img-first {
  margin-left: 12px;
  height: 350px;
  clip-path: polygon(25% 0%, 100.5% 0%, 73% 100%, 0% 100%);
}

.img-center {
  margin-left: -66px;
}

.img-last {
  margin-left: -65px;
}

.light {
  filter: grayscale(40%);
  transition: 0.5s ease-out 100ms;
  cursor: pointer;

  &:hover {
    filter: grayscale(0);
    transform: scale(1.03);
    z-index: 999;
  }

  &.colored {
    filter: grayscale(0) !important;
  }
}

.profile-image {
  &::after {
    content: "";
    position: absolute;
    bottom: 120px;
    background: rgba(80, 80, 80, 0.503);
    width: 25rem;
    height: 50px;
    border-radius: 50%;
    filter: blur(20px);
    margin-left: 6rem;
  }
}
h2{
   
    font-size: 3em;
    color: rgb(35, 37, 37);
}
.typewriter{
    position: relative;
}
.typewriter::after{
    content: '|';
    position: absolute;
    right: 0;
    color: #2563eb;
    width: 100%;
    animation: typing 2s steps(14) alternate infinite,
                line 1s infinite;
}
@keyframes typing{
    to{
        width: 0%;
    }
}
@keyframes line {
    50%{
      width: 100%;
    }
}
</style>