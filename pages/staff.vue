<template>
    <Header />
  
    <!-- Main  -->
    <div class="flex relative">
      <div class="relative w-full max-h-screen">
        <img src="landing1.webp" class="object-cover w-full h-full" />
        <div class="absolute top-0 left-0 opacity-40 w-full h-full  bg-black"></div>
      </div>
      <div class="absolute w-full h-full top-0 x-0">
        <div class="container flex m-auto h-full">
          <HomepageBlockquote 
            class="m-auto"
            :is-black="false"
            tagline="The greatest sign of success for a teacher is to be able to say,'The children are now working as if I did not exist'"
            author="Maria Montessori" />
        </div>
      </div>
    </div>
  
    <!-- Programs -->
    <div class="container m-auto min-h-screen">
      
    </div>

   
  </template>