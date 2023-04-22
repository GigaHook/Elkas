<template>
	<Head title="Home" />
	<MainLayout>



		<div>
			<Link href="/dashboard">Тест</Link>
		</div>

	</MainLayout>
</template>

<script setup>
import { Head, Link } from '@inertiajs/vue3';
import MainLayout from '@/Layouts/MainLayout.vue';

defineProps({
	canLogin: {
		type: Boolean,
	},
	canRegister: {
		type: Boolean,
	},
	laravelVersion: {
		type: String,
		required: true,
	},
	phpVersion: {
		type: String,
		required: true,
	},
});


</script>

<style lang="scss" scoped></style>