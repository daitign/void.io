<template>
  <div class="max-w-7xl m-center pt-20 pb-20">
    <div
      class="about-me text-center mt-10 md:mt-32"
      data-aos="fade-up"
      data-aos-delay="100"
      data-aos-duration="800"
    >
      <h2 class="text-5xl dark:text-white">About Me</h2>
      <span class="f-gray text-sm dark:text-white">Personal</span>
    </div>
    <div
      class="details flex mt-20 md:flex-col-reverse lg:flex-row flex-col-reverse"
    >
      <div
        class="image lg:w-3/6 mt-12 lg:m-auto"
        data-aos="fade-right"
        data-aos-delay="500"
        data-aos-duration="500"
      >
        <img
          class="w-11/12 rounded-md drop-shadow-lg m-auto lg:m-0"
          src="https://drive.google.com/uc?id=129um8zPgiVcif0Z7hgvbLO2fMgN_5SwM"
          alt=""
        />
      </div>
      <div
        class="information lg:w-3/6 flex flex-col"
        data-aos="fade-right"
        data-aos-delay="1200"
        data-aos-duration="500"
      >
        <div
          class="cover-letter f-gray text-lg pb-7 dark:text-white text-center lg:text-left md:justify-center lg:justify-start"
        >
          In 2017, I was fascinated by the workings of technology and decided to
          pursue a career in the IT industry. I soon discovered that everything
          I encountered online was the result of meticulously crafted lines of
          code. Now, years later, I'm pursuing my passion for IT by earning a
          bachelor's degree in the field.
        </div>
        <div
          class="summary-experience flex text-center justify-center lg:justify-start"
        >
          <div class="years-exp mr-5 w-2/12">
            <h2 class="text-3xl f-dark-blue font-extrabold dark:text-blue-500">
              4mos
            </h2>
            <span class="text-sm f-gray dark:text-white">Work Experience</span>
          </div>
          <div class="projects mr-5 w-2/12">
            <h2 class="text-3xl f-dark-blue font-extrabold dark:text-blue-500">
              3+
            </h2>
            <span class="text-sm f-gray dark:text-white"
              >Completed projects</span
            >
          </div>
          <div class="companies-worked mr-5 w-2/12">
            <h2 class="text-3xl f-dark-blue font-extrabold dark:text-blue-500">
              2+
            </h2>
            <span class="text-sm f-gray dark:text-white">Companies Worked</span>
          </div>
        </div>
        <div class="resume pt-10">
          <button class="btn-accent flex items-center m-auto lg:m-0">
            <a
              href="https://drive.google.com/file/d/1JsVubfoUTRKsHYsyGtfvqUi1ZYHPqs0z/view"
              target="_blank"
            >
              Download Resume&nbsp;
              <span
                ><font-awesome-icon
                  class="w-4"
                  :icon="['fas', 'arrow-circle-down']"
              /></span>
            </a>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>