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
            tagline="Free the child's potential and you will transform into the world"
            author="Nelson Mandela" />
        </div>
      </div>
    </div>
  
    <!-- Programs -->
    <div class="container m-auto min-h-screen">
      <p class="text-4xl text-center mt-12">We are Arunodhaya Montessori</p>
      <div class="flex space-y-4 md:space-y-0 md:space-x-4 flex-col md:flex-row mt-12">
        <p class="text-lg">
            We are devoted to nurturing the whole child – intellectually, socially, emotionally, and beyond. It is the core of all we do. By recognizing that no two children are the same, our approach cultivates the unique potential of each and every child in a caring, safe, and supportive school environment. 
        </p>
      </div>


      <p class="text-4xl text-center mt-12">Philosophy</p>
      <div class="flex space-y-4 md:space-y-0 md:space-x-4 flex-col md:flex-row mt-12">
        <p class="text-lg">
            The philosophy upon which Arunodaya Montessori School is based embraces the most fundamental teachings of Dr. Maria Montessori. Our method is designed to constantly build upon the individual skills and knowledge the child is acquiring, at every age level. By offering multi-aged classrooms rich with Montessori materials, your child will be actively engaged in their own learning process.

            He or she can move through new challenging materials quickly, or on to another experience without the boredom of waiting for others to catch up. His or her own feelings of accomplishment act as a reinforcement to succeed.
        </p>
      </div>
    </div>

   
  </template>