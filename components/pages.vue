<template>
	<div class="grid gap-y-5 fixed z-20 w-full h-10 bg-white/30 backdrop-blur-sm justify-items-center content-center right-0 bottom-0 grid-cols-3 sm:right-10 sm:top-1/2 sm:bottom-1/2 sm:grid-cols-1 sm:bg-transparent sm:w-fit">
        <div @click="go('#intro')" class="bg-white relative text-black rounded-full w-7 h-7 flex justify-center items-center select-none cursor-pointer">
            1
            <div class="w-full h-full absolute left-0 top-0 z-10 hover:animate-ping rounded-full border-[1px] border-solid border-white"></div>
        </div>
        <div @click="go('#skills')" class="bg-white relative text-black rounded-full w-7 h-7 flex justify-center items-center select-none cursor-pointer">
            2
            <div class="w-full h-full absolute left-0 top-0 z-10 hover:animate-ping rounded-full border-[1px] border-solid border-white"></div>
        </div>
        <div @click="go('#contact')" class="bg-white relative text-black rounded-full w-7 h-7 flex justify-center items-center select-none cursor-pointer">
            3
            <div class="w-full h-full absolute left-0 top-0 z-10 hover:animate-ping rounded-full border-[1px] border-solid border-white"></div>
        </div>
	</div>
</template>
<script setup>
function go(el){
    document.querySelector(el).scrollIntoView();
}
</script>