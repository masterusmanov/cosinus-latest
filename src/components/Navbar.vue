<template>
    <section class="bg-[#171B3F]">
        <div class="container mx-auto flex justify-beetwen items-center">
            <div class="w-[72%] h-[65px] flex items-center gap-[100px]">
                <img src="../assets/images/logo.svg" alt="logo" class="w-[40px] h-[17px] ml-3 md:ml-0 lg:w-[52px] lg:h-[22px]">
                <div class="text-white hidden lg:flex justify-between items-center gap-10">
                    <router-link to="/">Homepage</router-link>
                    <router-link to="/services">Services</router-link>
                    <router-link to="/portfolio">Portfolio</router-link>
                    <router-link to="/about">About Us</router-link>
                    <p>Telegram bot</p>
                    <div class="flex items-center gap-1">
                        <p to="/error">Cosinus academy</p>
                        <p id="yangi" class="text-[10px] mb-5 py-0.5 px-1">Yangi</p>
                    </div>
                </div>
            </div>
            <div class="w-[25%] md:w-[28%] flex justify-end items-center gap-3 text-white">
                <div class="bg-gradient-to-r from-[#34BCA2] to-[#1A16E9] p-0.5 rounded-lg">
                    <button class="bg-[#171B3F] px-2 py-2 rounded-lg"><router-link to="/bogla" class="bg-[#171B3F] px-2 py-2 rounded-lg">Connection</router-link></button>
                </div>
                <button id="dropdownDefaultButton" data-dropdown-toggle="dropdown" class="lg:hidden">
                    <i class='bx bx-menu text-[32px] text-white'></i>
                </button>
                    <!-- Dropdown menu -->
                <div id="dropdown" class="z-10 hidden bg-[#171B3F] divide-y divide-gray-100 rounded-lg shadow w-22 dark:bg-gray-700">
                    <ul class="py-2 text-[16px] font-serif text-white dark:text-gray-200" aria-labelledby="dropdownDefaultButton">
                        <li>
                            <router-link to="/" class="block px-4 py-2">Homepage</router-link>
                        </li>
                        <li>
                            <router-link to="/services" class="block px-4 py-2">Services</router-link>
                        </li>
                        <li>
                            <router-link to="/portfolio" class="block px-4 py-2">Portfolio</router-link>
                        </li>
                        <li>
                            <router-link to="/about" class="block px-4 py-2">About Us</router-link>
                        </li>
                        <li>
                            <p class="block px-4 py-2">Telegram bot</p>
                        </li>
                        <li>
                            <p class="block px-4 py-2">Cosinus academy</p>
                        </li>
                    </ul>
                </div>
                <select id="countries" class="hidden lg:block bg-[#171B3F] border-[#319B9C] text-white text-md rounded-lg w-[85px] ">
                    <option value="lang" class="hidden">Til</option>
                    <option value="uz">O'zbek</option>
                    <option value="ru">Русский</option>
                    <option value="en">English</option>
                </select>
            </div>

        </div>
    </section>
</template>

<script setup>
    import { initFlowbite } from 'flowbite'
    import { ref, onMounted } from "vue";
    import { useRouter } from "vue-router";

    
</script>

<style lang="scss" scoped>
    #yangi{
        background: var(--Gradient, linear-gradient(269deg, rgba(28, 31, 229, 0.68) -13.91%, rgba(54, 197, 158, 0.90) 107.18%));
        background-clip: text;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
    }

    .router-link-exact-active {
        border-bottom: 2px solid #5C7BDD;
      }
      .router-link-exact-active:hover {
        border-bottom: 2px solid #5C7BDD;
      }
</style>