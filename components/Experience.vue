<script setup lang="ts">
import { Bolt } from 'lucide-vue-next'
</script>

<template>
    <section class="border-bottom">
        <div class="grid-background p-4 border-x border-[#dedede] container">
            <p class="mb-4">Experience Section</p>
            <p class="mb-4">Lorem ipsum dolor sit amet . Animi eveniet pariatur nulla temporibus veritatis deleniti tempore laborum officia laboriosam minus suscipit similique, porro cum consectetur, doloremque dicta excepturi iste provident.</p>
            <Buttonx class="">
                <span>XP</span>
                <Bolt class="size-4"/>
            </Buttonx>
        </div>
    </section>
</template>

<style>
    /*remove this grid later*/
    .grid-background {
        background-image: linear-gradient(90deg, rgb(246, 246, 246) 1px, rgba(0, 0, 0, 0) 1px), linear-gradient(rgb(246, 246, 246) 1px, rgba(0, 0, 0, 0) 1px);
        background-size: 14px 14px;
    }
</style>