<template>
	<div>
		<div class="h-[100SVH] w-full bg-gradient-to-bl from-emerald-500 via-sky-500 to-indigo-500 relative font-noto">
			<Intro />
			<div class="w-full -z-10 relative h-[100svh]"></div>
			<div class="w-full z-30 relative bg-gradient-to-br to-emerald-500 via-sky-500 from-indigo-500">
				<Pages />
				<Skills />
				<Contact />
			</div>
		</div>
	</div>
</template>
<script setup>
useHead({
	title: "Daniel Web Dev",
	bodyAttrs: {
		class: "overflow-hidden"
	},
	htmlAttrs: {
		class: "scroll-smooth"
	}
});
</script>