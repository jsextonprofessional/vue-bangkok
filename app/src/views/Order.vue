<script setup lang="ts">
	import Favor from "@/components/order/Favor.vue";
	import Hours from "@/components/order/Hours.vue";
	import Location from "@/components/order/Location.vue";
	import Phone from "@/components/order/Phone.vue";
</script>
<template>
	<div class="gap-y-8 grid mx-56 my-8">
		<Phone />
		<Favor />
		<Location />
		<Hours />
	</div>
</template>