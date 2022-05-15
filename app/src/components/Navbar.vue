<script setup lang="ts">
import { RouterLink } from "vue-router";

</script>
<template>
	<div class="border-4 border-black flex justify-between px-12 py-4">
		<RouterLink to="/" class="text-2xl">BANGKOK INN</RouterLink>
		<div class="flex gap-2">
			<RouterLink to="/menu">MENU</RouterLink>
			<RouterLink to="/about">ABOUT</RouterLink>
			<RouterLink to="/order">ORDER</RouterLink>
		</div>
	</div>
</template>