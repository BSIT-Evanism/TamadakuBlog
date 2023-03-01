<template>
    <div>
        <header>
            <div class="border-dotted b-2">
                <div class="flex justify-center gap-4 p-4">
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/people">People</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/articles">Articles</NuxtLink>
                    </li>
                </div>
            </div>
        </header>
        <div class="p-4 mx-auto">
            <slot />
        </div>
        <footer class="flex bg-coolgray w-screen h-5">
            <div class="flex justify-center align-items gap-2 mx-auto"><marquee class=" w-full" width="100%" behavior="string" direction="left">
                <span>Testing lang po</span>
                <span>Testing uli HUHUHU</span>
                <span>Testing uli HUHUHU</span>
            </marquee></div>
        </footer>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>