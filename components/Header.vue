<template>
    <div class="hidden md:flex items-center space-x-4 bg-white w-full h-14 border-2 border-gray-100 z-50 px-4 overflow-hidden">
        <NuxtLink to="/">
            <div class="flex items-center">
                <h2 class="font-bold">Arunodaya Montessori</h2>
            </div>
        </NuxtLink>
        
        <p class="hidden md:block flex-grow"></p>
        <div class="hidden md:flex space-x-4">
            <NuxtLink :to="{ path: '/', hash: '#programs' }" :external="true">
                Programs
            </NuxtLink>
            <p>About Us</p>
            <p><NuxtLink to="/staff">Staff</NuxtLink></p>
            <p>Gallery</p>
            <p>Calendar</p>
            <p>Contact</p>
        </div> 
    </div>
    <div class="md:hidden">
        <div class="flex items-center p-4 border-b-2 border-gray-100">
            <h2 class="font-bold">Arunodaya Montessori</h2>
            <p class="flex-grow"></p>
            <font-awesome-icon @click="() => openMenu()" class="" :icon="['fas', 'fa-bars']" />
        </div>
        <div :class="mobileMenuOpen ? '' : 'hidden'" class="flex flex-col space-y-2 p-4">
            <NuxtLink :to="{ path: '/', hash: '#programs' }" :external="true">
                Programs
            </NuxtLink>            
            <p>About Us</p>
            <p>Staff</p>
            <p>Gallery</p>
            <p>Calendar</p>
            <p>Contact</p>
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
            openMenu() {
                this.mobileMenuOpen = !this.mobileMenuOpen
            },
        }
    }
</script>