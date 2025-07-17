<script setup lang='ts'>
</script>
<template>
<div class="min-h-screen flex flex-col bg-gray-50">
    <Header />
    <main class="flex-1 container mx-auto px-4 py-8">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-8">
            <div class="lg:col-span-9">
                <slot />
            </div>
            <aside class="lg:col-span-3">
                <SidebarBlog />
            </aside>
        </div>
    </main>
    <Footer />
</div>
</template>
<style lang="scss">
</style>
