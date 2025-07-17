<script setup lang="ts">
definePageMeta({
  layout: 'blog' 
})
</script>
<template>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div v-for="item in 10" :key="item" class="flex justify-center">
            <BlogCard />
        </div>
    </div>
</template>
