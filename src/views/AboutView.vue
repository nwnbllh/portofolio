<script>
export default {
  data() {
    return {
      activeTab: 1,
      tech: [
        {
          id: 1,
          name: 'Illustrator',
          imageUrl: 'https://i.pinimg.com/564x/33/f2/c0/33f2c029855f4d15e828b84b50fac5ca.jpg',
          status: 'Advanced'
        },
        {
          id: 2,
          name: 'Photoshop',
          imageUrl: 'https://i.pinimg.com/564x/55/03/17/550317c33bc9c30e4691e4b0e05074e0.jpg',
          status: 'Advanced'
        },
        {
          id: 3,
          name: 'Corel Draw',
          imageUrl: 'https://seeklogo.com/images/C/coreldraw-x7-logo-747B0DC253-seeklogo.com.png',
          status: 'Intermediate'
        },
        {
          id: 4,
          name: 'Figma',
          imageUrl: 'https://cdn.icon-icons.com/icons2/2699/PNG/512/figma_logo_icon_170157.png',
          status: 'Intermediate'
        },
        {
          id: 5,
          name: 'After Effect',
          imageUrl: 'https://cdn.icon-icons.com/icons2/3070/PNG/512/software_multimedia_adobe_after_effect_visual_effect_icon_191053.png',
          status: 'Beginner'
        },
        {
          id: 6,
          name: 'Canva',
          imageUrl: 'https://upload.wikimedia.org/wikipedia/commons/5/5e/Canva_logo..png',
          status: 'Advanced'
        },
        {
          id: 7,
          name: 'Cisco PT',
          imageUrl: 'https://hurbad.com/wp-content/uploads/2021/12/Cisco-Packet-Tracer.png',
          status: 'Advanced'
        },
        {
          id: 8,
          name: 'Virtual Box',
          imageUrl: 'https://cdn.icon-icons.com/icons2/2699/PNG/512/virtualbox_logo_icon_169253.png',
          status: 'Advanced'
        },
      ],
      tools: [
        {
          id: 1,
          name: 'illustrasion',
          imageUrl: 'https://i.pinimg.com/564x/cf/af/8f/cfaf8f6e1048ff0f2ce6505caa52e1f0.jpg',
          status: 'Brain imagination'
        },
        {
          id: 2,
          name: 'Discipline',
          imageUrl: 'https://i.pinimg.com/564x/8d/3e/f9/8d3ef993fa44d5baded3efb89bc3eb6d.jpg',
          status: 'Managing time'
        },
        {
          id: 3,
          name: 'Creativity',
          imageUrl: 'https://i.pinimg.com/564x/92/89/d8/9289d80ed70b18d25d3d461cf82ed086.jpg',
          status: 'Creative human'
        },
        {
          id: 4,
          name: 'Desire to learn',
          imageUrl: 'https://i.pinimg.com/564x/11/14/78/111478aa4d5171ac20aac9928fb97f44.jpg',
          status: 'Quick response'
        },
        {
          id: 5,
          name: 'Teamwork',
          imageUrl: 'https://i.pinimg.com/564x/d5/60/27/d56027ae804c4ebf0ee05281e110db5d.jpg',
          status: 'Can work together'
        },
        {
          id: 6,
          name: 'Collaboration',
          imageUrl: 'https://i.pinimg.com/564x/97/c5/f7/97c5f7e8b9980226e082c6377c0944ae.jpg',
          status: 'Really like it'
        },
      ]
    };
  }
}
</script>
<template>
  <div
    class="bg-[#1e1e1f] px-5 py-5 md:px-12 md:py-10 text-left border border-[#383838] rounded-3xl text-amber-50 mx-3 mb-5">
    <article data-page="about">

      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          About Me &nbsp;
          <div class="h-[1px] w-32 bg-amber-200 md:w-96 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
        </div>
      </header>

      <section
        class="text-sm md:text-lg text-justify flex flex-col gap-4 md:flex-row md:gap-8 md:justify-left md:items-center">
        <div class="flex justify-center">
          <img class="w-9/12 rounded-full mb-3 fadein-up"
            src="https://i.pinimg.com/736x/df/37/05/df37053d57b0fab26341324d0edf5ea0.jpg" alt="Foto">
        </div>
        <div class="md:w-7/12">
          <p class="mb-3 md:mb-7 fadein-left fadeins-1">
            &nbsp; &nbsp; &nbsp; Hi my name is Najwa Nabilah. I am a graduate of Vocational High School 53 Jakarta, majoring in Computer and Network Engineering. Usually people call me Awa. Born on January 22, 2006 in Jakarta. I have an interest in Illustration and design. Because of that, I have some experience in that field.
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; ✩°｡⋆⸜ 🎧✮ Education | SMK N 53 Jakarta (https://www.smkn53jkt.sch.id) | major in Computer and Network Engginering | Jakarta `2021-2024`
          </p>
          <p class="mb-3 fadein-left fadeins-2">
            &nbsp; &nbsp; &nbsp; `` ~ ୨୧ ♡ · Work Experience | PT. Acer Manufacturing Indonesia (https://www.acer.com/id-id) | Dead On Arrival/DoA | Bekasi `2022-2023`
          </p>
        </div>
      </section>

    </article>
  </div>

  <div class="px-5 py-5 md:px-12 md:py-10 text-left text-amber-50 mx-3">
    <article data-page="about">
      <header>
        <div class="text-2xl font-bold text-white mb-5 fadein-bot title-section flex items-center">
          <div class="h-[1px] w-10 bg-amber-200 md:w-20 aos-init aos-animate" data-aos="zoom-in-left"
            data-aos-duration="600"></div>
          &nbsp; Skills
        </div>
      </header>
      <section>
        <div>
          <ul class="flex flex-wrap text-sm font-medium text-center text-gray-500 dark:text-gray-400 mb-5">
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 1 }" @click="activeTab = 1">Software</button>
            </li>
            <li class="mr-2">
              <button class="inline-block px-4 py-3 rounded-lg hover:text-white"
                :class="{ 'text-amber-200 bg-amber-200 bg-opacity-10': activeTab === 2 }" @click="activeTab = 2">Personal</button>
            </li>
          </ul>
        </div>
        <div v-show="activeTab === 1">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tech" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div v-show="activeTab === 2">
          <div class="grid grid-cols-2 gap-4 pb-32 md:grid-cols-3 md:gap-8 xl:grid-cols-4 xl:gap-10 2xl:gap-12">
            <div v-for="item in tools" :key="item.id">
              <div
                class="item-tech flex cursor-pointer items-center gap-2 rounded border border-amber-200 px-2 py-2 hover:bg-amber-200 hover:bg-opacity-10 md:gap-3 lg:px-3">
                <div class="flex h-12 w-12 items-center justify-center p-0 lg:h-16 lg:w-16 lg:p-2 zoom-in">
                  <img alt="HTML" loading="lazy" width="32" height="32" decoding="async" data-nimg="1"
                    class="img-tech drop-shadow-xl transition-all duration-300 h-[65%] w-[65%] lg:h-[85%] lg:w-[85%]  "
                    :src="item.imageUrl" style="color: transparent;">
                </div>
                <div class="flex items-center text-sm md:text-base lg:text-lg">
                  <div class="tech font-medium text-secondary transition-all duration-300 translate-y-0 ">{{ item.name }}
                  </div>
                  <div
                    class="status-tech opacity-0 absolute mt-5 text-[10px] text-amber-200 transition-all duration-300 md:text-xs lg:text-sm">
                    {{ item.status }}</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </article>
  </div>
</template>

<style>
.fadein-left {
  opacity: 0;
  animation: fadeInLeft 0.5s ease-out forwards;
}

@keyframes fadeInLeft {
  0% {
    opacity: 0;
    transform: translateX(100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

.fadeins-1 {
  animation-delay: 500ms;
}

.fadeins-2 {
  animation-delay: 800ms;
}

.img-tech,
.tech {
  transition: transform 0.3s ease;
}

.item-tech:hover .img-tech {
  transform: scale(1.3);
}

.item-tech:hover .tech {
  transform: translateY(-12px);
}

.item-tech:hover .status-tech {
  opacity: 1;
}
</style>
