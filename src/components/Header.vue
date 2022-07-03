<script setup>
import {ArrowRightIcon, ChevronDoubleDownIcon, CodeIcon} from '@heroicons/vue/solid'
</script>
<template>
	<section class="bg-blue-200 flex flex-col justify-center items-center md:px-20 min-h-screen">
		<div class="flex flex-col w-full py-12 px-4 lg:px-0 justify-center items-end">
            <img class="w-50 object-contain absolute inset-0 object-center h-full" src="../assets/me.jpg" alt="Mypic"/>
			<p class="text-2xl text-gray-800 font-medium">哈囉！我是<span class="text-blue-400">王小明</span></p>
			<h1 class="text-5xl text-right text-gray-800 mt-1 font-extrabold">
				一個喜歡寫程式的高中生
			</h1>
			<p class="text-lg text-gray-600 font-light pt-8">
				[自我介紹]
			</p>
			<a
				href="#contact"
				class="mt-3 flex items-center text-xl font-regular pb-2">
				聯絡我
				<ArrowRightIcon class="ml-1 w-5 h-5"/>
			</a>
		</div>

		<a href="#activities" class="animate-bounce cursor-pointer">
            我的專案
			<CodeIcon class="w-16 h-16"/>
		</a>
	</section>
</template>
