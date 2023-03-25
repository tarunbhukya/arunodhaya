<template>
    <Header />
  
    <!-- Main  -->
    <div class="flex relative">
      <div class="relative w-full max-h-screen">
        <img src="bg1.jpg" class="object-cover w-full h-full" />
        <div class="absolute top-0 left-0 opacity-40 w-full h-full  bg-black"></div>
      </div>
      <div class="absolute w-full h-full top-0 x-0">
        <div class="container flex m-auto h-full">
          <HomepageBlockquote 
            class="m-auto"
            :is-black="false"
            tagline="To stimulate life, leaving it free, however, to unfold itslef, that is the first duty of the educator"
            author="Maria Montessori" />
          <!-- <p class="text-white text-3xl m-auto font-bold">Hello, Students!</p> -->
        </div>
      </div>
      <!-- <div class="container md:flex m-auto">
        <div class="bg-white border-4 border-white w-64 h-64 rounded-full overflow-hidden m-auto">
          <img src="maria.jpeg" class="shadow rounded-full max-w-full h-auto align-middle border-none" />
        </div>
        <div class="grow m-auto">
          <HomepageBlockquote class="mt-12"
            tagline="To stimulate life, leaving it free, however, to unfold itslef, that is the first duty of the educator"
            author="Maria Montessori" />
        </div>
      </div> -->
    </div>
  
    <!-- Programs -->
    <div id="programs" class="container m-auto min-h-screen">
      <p class="text-4xl text-center mt-12">Our Programs</p>
      <div class="flex space-y-4 md:space-y-0 md:space-x-4 flex-col md:flex-row mt-12">
        <div class="w-full md:w-1/3">
          <HomepageProgramCard 
            color="#8ac0de" 
            title="Language" 
            content="Language is a system of symbols with an agreed upon meaning that is used by a group of people. Language is a means of communication ideas or feelings by the use of conventionalized sounds and signs, thus, being the spoken and written language.  Children can learn up to seven languages in the first six years of their lives. We introduce reading to children in three stages where they first mechanically read the word, then they read and interpret the word and lastly they appreciate the language, style and story behind what they read."
            url="/language-activities"
            />
        </div>
  
        <div class="w-full md:w-1/3">
          <HomepageProgramCard 
            color="#eab159" 
            title="Practical" 
            content="Practical life Exercises are just that, they are Exercises so the child can learn how to do living activities in a purposeful way.The purpose and aim of Practical Life is to help the child gain control in the coordination of his movement, and help the child to gain independence and adapt to his society. It is therefore important to “Teach teaching, not correcting” (Montessori) in order to allow the child to be a fully functionional member in hios own society. Practical Life Exercises also aid the growth and development of the child’s intellect and concentration and will in turn also help the child develop an orderly way of thinking."
            url="/practical-activities"
            />
        </div>
  
        <div class="w-full md:w-1/3">
          <HomepageProgramCard 
            color="#d8534e" 
            title="Sensorial" 
            content="Sensorial activities are used in Montessori learning to help children in discrimination and order. They also help broaden and      refine  a child's senses. When a child combines Montessori designed materials with sensorial work, it helps them become more logical, perceptive, and aware."
            url="/sensorial-activities"
            />
        </div>
      </div>
  
      <HomepageBlockquote 
        class="mt-12"
        :is-black="true"
        tagline="Free the child's potential and you will transform into the world"
        author="Nelson Mandela" />
    </div>

    <!-- About Us -->
    <div id="aboutus" class="container m-auto min-h-screen">
      <div class="p-24 bg-white rounded-md">

      </div>
    </div>
  </template>

<script>
export default {
    data() {
        return {
            mobileMenuOpen: false
        }
    },
    methods: {
     
    },

    mounted() {
      
    }
  }
</script>