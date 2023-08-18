<script setup lang="ts">
import MainButton from '@/components/MainButton.vue'
</script>

<template>
    <div class="flex items-center justify-between py-5 px-12 lg:px-24 xl:px-48">
        <img src="../assets/Images/Logo.svg" alt="">
        <div class="flex gap-8">
            <p>Individual</p>
            <p>Business</p>
            <p>Pricing</p>
            <p>Set your payroll</p>
        </div>
        <div class="gap-5 flex">
            <MainButton text="Log in" :color="true" />
            <MainButton text="Register"/>
        </div>
    </div>
</template>