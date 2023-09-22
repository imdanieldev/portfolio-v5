<template>
	<div>
		<div class="min-h-[100SVH] w-full bg-gradient-to-br from-emerald-500 via-sky-500 to-indigo-500 relative font-noto">
			<Pages />
			<Intro />
			<Skills />
			<Contact />
		</div>
	</div>
</template>
<script setup>
useHead({
	title: "Daniel Web Dev",
	bodyAttrs: {
		class: "overflow-hidden"
	},
	htmlAttrs:{
		class: "scroll-smooth"
	}
});
</script>