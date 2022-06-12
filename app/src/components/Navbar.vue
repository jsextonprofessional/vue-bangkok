<script setup lang="ts">
import { RouterLink } from "vue-router";

</script>
<template>
	<div class="bg-white/75 border-8 border-black fixed top-0 flex justify-between px-20 py-8 min-w-full">
		<div>
				<RouterLink
					to="/"
					class="font-medium hover:text-cyan-300 text-4xl text-rose-400"
				>
					<button class="bg-white border-8 border-transparent hover:border-black px-6 py-2">
						BANGKOK INN
					</button>
				</RouterLink>
		</div>
		<div class="flex gap-10">
				<RouterLink
					to="/menu"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					<button class="bg-white border-8 border-transparent hover:border-black px-3 py-2">
						MENU
					</button>
				</RouterLink>
				<RouterLink
					to="/about"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					<button class="bg-white border-8 border-transparent hover:border-black px-3 py-2">
						ABOUT
					</button>
				</RouterLink>
				<RouterLink
					to="/order"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					<button class="bg-white border-8 border-transparent hover:border-black px-3 py-2">
						ORDER
					</button>
				</RouterLink>
		</div>
	</div>
</template>