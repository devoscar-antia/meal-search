<template>
    <header class="bg-white shadow-md h-16 flex justify-between items-stretch">
        <router-link :to="{ name: 'home' }" class="font-semibold inline-flex items-center h-full px-5">
            Home
        </router-link>
        <div class="flex items-center gap-1">
            <router-link :to="{ name: 'byName' }"
                class=" font-semibold inline-flex items-center px-2 h-full transition-colors hover:bg-green-300">
                Search Meals
            </router-link>
            <router-link :to="{ name: 'byLetter' }"
                class=" font-semibold  inline-flex items-center px-2 h-full transition-colors  hover:bg-green-300">
                Meals By Letter
            </router-link>
            <router-link :to="{ name: 'ingredients' }"
                class=" font-semibold  inline-flex items-center px-2 h-full transition-colors  hover:bg-green-300">
                Meals By Ingredients
            </router-link>
        </div>
    </header>
</template>