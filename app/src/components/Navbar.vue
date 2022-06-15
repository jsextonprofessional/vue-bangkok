<script setup lang="ts">
import { RouterLink } from "vue-router";

</script>
<template>
	<div class="bg-white/75 border-8 border-black fixed top-0 flex hover:shadow-xl justify-between px-20 py-8 min-w-full">
		<div>
				<RouterLink
					to="/"
					class="font-medium hover:text-cyan-300 text-4xl text-rose-400"
				>
					<button class="bg-white border-8 border-transparent hover:border-black hover:shadow-xl hover:text-white px-6 py-2 rainbow-bg">
						BANGKOK INN
					</button>
				</RouterLink>
		</div>
		<div class="flex gap-10">
				<RouterLink
					to="/menu"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					<button class="bg-white border-8 border-transparent hover:border-black hover:shadow-xl hover:text-white px-3 py-2 rainbow-bg">
						MENU
					</button>
				</RouterLink>
				<RouterLink
					to="/about"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					<button class="bg-white border-8 border-transparent hover:border-black hover:shadow-xl hover:text-white px-3 py-2 rainbow-bg">
						ABOUT
					</button>
				</RouterLink>
				<RouterLink
					to="/order"
					class="hover:text-cyan-300 text-4xl text-rose-300"
				>
					<button class="bg-white border-8 border-transparent hover:border-black hover:shadow-xl hover:text-white px-3 py-2 rainbow-bg">
						ORDER
					</button>
				</RouterLink>
		</div>
	</div>
</template>
<style>
.rainbow-bg:hover{
		animation: rainbow-bg 3s linear;
		animation-iteration-count: infinite;
}

@keyframes rainbow-bg{
		100%,0%{
			background-color: rgb(255,0,0);
		}
		8%{
			background-color: rgb(255,127,0);
		}
		16%{
			background-color: rgb(255,255,0);
		}
		25%{
			background-color: rgb(127,255,0);
		}
		33%{
			background-color: rgb(0,255,0);
		}
		41%{
			background-color: rgb(0,255,127);
		}
		50%{
			background-color: rgb(0,255,255);
		}
		58%{
			background-color: rgb(0,127,255);
		}
		66%{
			background-color: rgb(0,0,255);
		}
		75%{
			background-color: rgb(127,0,255);
		}
		83%{
			background-color: rgb(255,0,255);
		}
		91%{
			background-color: rgb(255,0,127);
		}
}

</style>