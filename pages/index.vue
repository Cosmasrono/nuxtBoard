<template>
  <main class=" ">
    <div class=" flex items-center justify-center flex-col ">
      <div class=" text-xl flex gap-8  justify-end">
      <nuxt-link to="">codes</nuxt-link>
      <nuxt-link to="">Languages</nuxt-link>
      <nuxt-link to="">videos</nuxt-link>
      <nuxt-link to="">Category</nuxt-link>
     
      </div>
 <img src="../assets/image1.jpg" alt="" class=" h-1/2 w-screen m-4 p-4">
      <!-- <div class="">
        <carousel :per-page="3" :navigation-enabled="true" :pagination-enabled="true">
          <slide v-for="(item, index) in items" :key="index">
            <img :src="item.image" alt="item image">
            <h3>{{ item.title }}</h3>
            <p>{{ item.description }}</p>
          </slide>
        </carousel>
      </div>
  -->
    </div>
  
    <div class=" gap-5 m-3 flex-col grid p-12 ">
      <div class="  p-6 flex flex-row  text-white rounded-lg shadow">
        <div class="sm:flex-row">
         <a href="#">
             <h5 class="mb-2 text-2xl font-bold tracking-tight  dark:text-white">THE NUXT</h5>
         </a>
         <p class="mb-3 font-normal ">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
         <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
             Read more
         </a>
         </div>
         <div class="">
           <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0 " alt="">
         </div>
</div>

<div class="  p-6 flex flex-row  rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
 <div class="">
  <a href="#">
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">THE VUE</h5>
  </a>
  <p class="mb-3 font-normal text-white ">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
  <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
      Read more
  </a>
  </div>
  <div class="">
    <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0"  alt="">
  </div>
</div>

<div class="  p-6 flex flex-row  rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
  <div class="">
   <a href="#">
       <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">DJANGO</h5>
   </a>
   <p class="mb-3 font-normal text-white ">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
   <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
       Read more
   </a>
   </div>
   <div class="">
     <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0" alt="">
   </div>
 </div>
 <div class="  p-6 flex flex-row rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
  <div class="">
   <a href="#">
       <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">THE PYTHON</h5>
   </a>
   <p class="mb-3 font-normal text-white">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
   <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
       Read more
   </a>
   </div>
   <div class="">
     <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0" alt="">
   </div>
 </div>
 <div class="  p-6 flex flex-row  rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
  <div class="">
   <a href="#">
       <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">DATA SCIENCE</h5>
   </a>
   <p class="mb-3 font-normal text-white ">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
   <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
       Read more
   </a>
   </div>
   <div class="">
     <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0" alt="">
   </div>
 </div>
 <div class="  p-6 flex flex-row shadow dark:bg-gray-800 dark:border-gray-700">
  <div class="">
   <a href="#">
       <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">BOOTSTRAP</h5>
   </a>
   <p class="mb-3 font-normal text-white">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
   <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
       Read more
   </a>
   </div>
   <div class="">
     <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0" alt="">
   </div>
 </div>
<div class="  p-6 flex flex-row  shadow dark:bg-gray-800 dark:border-gray-700">
  <div class=" sm:flex-row">
   <a href="#">
       <h5 class="mb-2 text-2xl font-bold tracking-tight  text-white">TAILWIND</h5>
   </a>
   <p class="mb-3 font-normal text-white">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
   <a href="https://nuxt.com/docs/getting-started/introduction" class="inline-flex items-center px-3 py-2 text-sm font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">
       Read more
   </a>
   </div>
   <div class="">
     <img src="../assets/photo.jpg" class=" w-full sm:w-1/2 mb-4 sm:mb-0" alt="">
   </div>
 </div>
</div>

     
    <div class=" flex flex-col items-center justify-center m-3">
    <h2>THE VUE</h2>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Iusto assumenda quae deleniti doloremque vero porro iste omnis tempore molestias beatae? Modi ab quos obcaecati, veritatis aspernatur quo hic pariatur illo!
    </div>
    <div class=" flex flex-col items-center justify-center m-3 ">
    <h1>PYTHON</h1>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus amet suscipit facilis! Nihil, in illo! Libero placeat ad eos facere, accusamus, vero velit, praesentium error quis minima eum labore accusantium. 
    </div>
    <div class=" flex flex-col items-center justify-center m-3  "> 
    <h1>DATA SCIENCE</h1>
    Lorem ipsum dolor sit amet consectetur, adipisicing elit. Esse possimus suscipit adipisci voluptatum maiores inventore, error fuga quos accusantium nisi doloribus hic quod sequi nam accusamus fugit? Cum, obcaecati sequi?
     </div>
     <div class=" flex flex-col items-center justify-center m-3  ">
     <h1>BOOTSTRAP</h1>
     Lorem ipsum dolor sit amet consectetur adipisicing elit. Laborum quidem ratione iusto itaque rem, tenetur assumenda a harum? Maiores, blanditiis. Laborum laboriosam deserunt nemo ad veniam delectus reprehenderit molestias et!
     </div>
     <div class=" flex flex-col items-center justify-center m-3 ">
     <h1>DJANGO</h1>
     Lorem ipsum dolor sit amet consectetur adipisicing elit. Vel itaque saepe minus sit accusamus facere harum corporis! Odio nesciunt, sit eveniet recusandae explicabo voluptatibus natus animi! Non laborum possimus dolor!
    </div>

<!-- <div id="default-carousel" class="relative" data-carousel="static">
  
  <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
      
      <div class="hidden duration-700 ease-in-out" data-carousel-item>
          <span class="absolute text-2xl font-semibold text-white -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 sm:text-3xl dark:text-gray-800">First Slide</span>
          <img src="../assets/image1.jpg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
      </div>
     
      <div class="hidden duration-700 ease-in-out" data-carousel-item>
          <img src="../assets/image3.jpg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
      </div>
       
      <div class="hidden duration-700 ease-in-out" data-carousel-item>
          <img src="../assets/image4.jpg" class="absolute block w-full -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2" alt="...">
      </div>
  </div>
  
  <div class="absolute z-30 flex space-x-3 -translate-x-1/2 bottom-5 left-1/2">
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 1" data-carousel-slide-to="0"></button>
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
      <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
  </div>
  
  <button type="button" class="absolute top-0 left-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev>
      <span class="inline-flex items-center justify-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
          <svg aria-hidden="true" class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"></path></svg>
          <span class="sr-only">Previous</span>
      </span>
  </button>
  <button type="button" class="absolute top-0 right-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next>
      <span class="inline-flex items-center justify-center w-8 h-8 rounded-full sm:w-10 sm:h-10 bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
          <svg aria-hidden="true" class="w-5 h-5 text-white sm:w-6 sm:h-6 dark:text-gray-800" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
          <span class="sr-only">Next</span>
      </span>
  </button>
</div>
   
 -->
  </main>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          image: '~/assets/image1.jpg',
          title: 'Item 1',
          description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
        },
        {
          image: 'path/to/image2.jpg',
          title: 'Item 2',
          description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
        },
        {
          image: 'path/to/image3.jpg',
          title: 'Item 3',
          description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
        },
        {
          image: 'path/to/image4.jpg',
          title: 'Item 4',
          description: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.'
        }
      ]
    }
  }
}
</script>