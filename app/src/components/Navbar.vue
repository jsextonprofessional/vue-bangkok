<script setup lang="ts">
import { RouterLink } from "vue-router";

</script>
<template>
	<div class="bg-white border-8 border-black flex justify-between px-20 py-8">
		<div>
			<div class="border-8 border-transparent hover:border-black px-6 py-2">
				<RouterLink
					to="/"
					class="font-medium hover:text-cyan-300 text-4xl text-rose-400"
				>
					BANGKOK INN
				</RouterLink>
			</div>
		</div>
		<div class="flex gap-10">
			<div class="border-8 border-transparent hover:border-black px-3 py-2">
				<RouterLink
					to="/menu"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					MENU
				</RouterLink>
			</div>
			<div class="border-8 border-transparent hover:border-black px-3 py-2">
				<RouterLink
					to="/about"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					ABOUT
				</RouterLink>
			</div>
			<div class="border-8 border-transparent hover:border-black px-3 py-2">
				<RouterLink
					to="/order"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					ORDER
				</RouterLink>
			</div>
		</div>
	</div>
</template>