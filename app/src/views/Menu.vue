<script setup lang="ts">
import Appetizers from "@/components/menu/Appetizers.vue";
import Soup from "@/components/menu/Soup.vue";
import Salad from "@/components/menu/Salad.vue";
import Curry from "@/components/menu/Curry.vue";
import Noodles from "@/components/menu/Noodles.vue";
import Rice from "@/components/menu/Rice.vue";
import Specialties from "@/components/menu/Specialties.vue";
import StirFry from "@/components/menu/StirFry.vue";
import Drinks from "@/components/menu/Drinks.vue";
import Desserts from "@/components/menu/Desserts.vue";
import Extras from "@/components/menu/Extras.vue";

// TODO 4 MENU
// EVENLY SPACE SALAD SOUP/ADD COMMON margin-x FOR 70/30 RULE. ya dig?
</script>
<template>
	<div class="mx-12">
		<Appetizers />
		<div class="flex justify-between">
			<Soup />
			<Salad />
		</div>
		<Curry />
		<div class="grid grid-cols-2">
			<Noodles />
			<Rice />
		</div>
		<Specialties />
		<StirFry />
		<Drinks />
		<div class="grid grid-cols-2">
			<Desserts />
			<Extras />
		</div>
	</div>
</template>