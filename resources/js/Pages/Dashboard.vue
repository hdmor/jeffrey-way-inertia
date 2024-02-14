<script setup>
import AuthenticatedLayout from '@/Layouts/AuthenticatedLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard" />

    <AuthenticatedLayout>
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 dark:text-gray-200 leading-tight">Dashboard</h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white dark:bg-gray-800 overflow-hidden shadow-sm sm:rounded-lg">
                    <div class="px-6 pt-4 pb-2 text-gray-900 dark:text-gray-100">You're logged in!</div>
                    <div class="px-6 pt-2 pb-4 text-gray-900 dark:text-gray-100">We must working on ads for 6mile application in Instagram and others platforms.</div>
                </div>
            </div>
        </div>
    </AuthenticatedLayout>
</template>
