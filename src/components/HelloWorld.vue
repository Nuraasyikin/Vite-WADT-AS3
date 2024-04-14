<template>
  <section class="relative isolate overflow-hidden bg-white px-6 py-24 sm:py-32 lg:px-8">
    <div class="absolute inset-0 -z-10 bg-[radial-gradient(45rem_50rem_at_top,theme(colors.indigo.100),white)] opacity-20" />
    <div class="absolute inset-y-0 right-1/2 -z-10 mr-16 w-[200%] origin-bottom-left skew-x-[-30deg] bg-white shadow-xl shadow-indigo-600/10 ring-1 ring-indigo-50 sm:mr-28 lg:mr-0 xl:mr-16 xl:origin-center" />
    <div class="mx-auto max-w-2xl lg:max-w-4xl">
      <img class="mx-auto h-12" src="https://tailwindui.com/img/logos/workcation-logo-indigo-600.svg" alt="" />
      <figure class="mt-10">
        <blockquote class="text-center text-xl font-semibold leading-8 text-gray-900 sm:text-2xl sm:leading-9">
          <p>“1% can make a difference. Start doing it now than staying 0%”</p>
        </blockquote>
        <figcaption class="mt-10">
          <img src="../assets/profile.jpg" class="mx-auto h-10 w-10 rounded-full" alt="" />
          <div class="mt-4 flex items-center justify-center space-x-3 text-base">
            <div class="font-semibold text-gray-900">Nurul Asyikin Rajali</div>
            <svg viewBox="0 0 2 2" width="3" height="3" aria-hidden="true" class="fill-gray-900">
              <circle cx="1" cy="1" r="1" />
            </svg>
            <div class="text-gray-600">Student of Politeknik Brunei</div>
          </div>
        </figcaption>
      </figure>
    </div>
  </section>

  <div>
    <div class="px-8 py-4 sm:px-16 sm:py-8">
      <h3 class="text-base font-semibold leading-7 text-gray-900">Student Information</h3>
      <p class="mt-1 max-w-2xl text-sm leading-6 text-gray-500">Personal details:</p>
    </div>
    <div class="mt-6 border-t border-gray-100 px-8 py-4 sm:px-16 sm:py-8">
      <dl class="divide-y divide-gray-100">
        <div class="px-4 py-6 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-0">
          <dt class="text-sm font-medium leading-6 text-gray-900">Full name</dt>
          <dd class="mt-1 text-sm leading-6 text-gray-700 sm:col-span-2 sm:mt-0">Nurul Asyikin binti Rajali</dd>
        </div>
        <div class="px-4 py-6 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-0">
          <dt class="text-sm font-medium leading-6 text-gray-900">Student ID</dt>
          <dd class="mt-1 text-sm leading-6 text-gray-700 sm:col-span-2 sm:mt-0">22FTT1504</dd>
        </div>
        <div class="px-4 py-6 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-0">
          <dt class="text-sm font-medium leading-6 text-gray-900">School</dt>
          <dd class="mt-1 text-sm leading-6 text-gray-700 sm:col-span-2 sm:mt-0">School of ICT, Politeknik Brunei</dd>
        </div>
        <div class="px-4 py-6 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-0">
          <dt class="text-sm font-medium leading-6 text-gray-900">Course</dt>
          <dd class="mt-1 text-sm leading-6 text-gray-700 sm:col-span-2 sm:mt-0">Diploma in Web Development</dd>
        </div>
        <div class="px-4 py-6 sm:grid sm:grid-cols-3 sm:gap-4 sm:px-0">
          <dt class="text-sm font-medium leading-6 text-gray-900">About me</dt>
          <dd class="mt-1 text-sm leading-6 text-gray-700 sm:col-span-2 sm:mt-0">
            I am in my fourth semester. I am currently learning about Vue 3 and Tailwind CSS. I am also learning about the basics of web development. I am interested in learning more about web development and I am looking forward to learning more about it. In my free time, I spent time drawings. I used to study at IBTE SSRC taking the course of Information and Library Studies for 2 years. I'm proficient in a range of programming languages and technologies, including HTML, CSS, JavaScript, Java, Angular, and PHP, and I'm always looking for new opportunities in the world of technology. 
          </dd>
        </div>
        
      </dl>
    </div>
  </div>

</template>

<script setup>
import { PaperClipIcon } from '@heroicons/vue/20/solid'





</script>
