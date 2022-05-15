<script setup lang="ts">
import { RouterLink } from "vue-router";

</script>
<template>
	<div class="bg-rose-400 border-4 border-black flex justify-between px-12 py-4">
		<div>
			<RouterLink
				to="/"
				class="text-2xl text-cyan-300"
			>
				BANGKOK INN
			</RouterLink>
		</div>
		<div class="flex gap-10">
			<RouterLink 
				to="/menu"
				class="text-2xl text-yellow-300"	
			>
				MENU
			</RouterLink>
			<RouterLink 
				to="/about"
				class="text-2xl text-yellow-300"	
			>
				ABOUT
			</RouterLink>
			<RouterLink 
				to="/order"
				class="text-2xl text-yellow-300"	
			>
				ORDER
			</RouterLink>
		</div>
	</div>
</template>