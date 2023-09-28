<template>
    <div id="intro" class="flex justify-around items-center h-[100SVH] w-full flex-col fixed top-0 left-0 z-10">
        <div class="text-center">
            <h1 class="mt-6 text-5xl sm:text-6xl">Daniel Web Dev</h1>
            <p class="text-2xl mt-6">Hello I'm Daniel.</p>
            <p class="mt-2">2008/3/7</p>
            <p class="mt-2">Iran - Isfahan</p>
        </div>
        <div @click="go('#skills')" class="w-12 h-12 bg-black/60 rounded-full flex justify-center items-center cursor-pointer animate-bounce">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-6 h-6 fill-white"
                viewBox="0 0 16 16">
                <path fill-rule="evenodd"
                    d="M8 1a.5.5 0 0 1 .5.5v11.793l3.146-3.147a.5.5 0 0 1 .708.708l-4 4a.5.5 0 0 1-.708 0l-4-4a.5.5 0 0 1 .708-.708L7.5 13.293V1.5A.5.5 0 0 1 8 1z" />
            </svg>
        </div>
    </div>
</template>
<script setup>
function go(el){
    document.querySelector(el).scrollIntoView();
}
</script>