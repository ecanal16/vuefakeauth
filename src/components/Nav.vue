<template>
<div class="text-indigo-200 bg-indigo-800">
<div class="container mx-auto flex items-center justify-between">
    <h1 class="text-3xl font-thin tracking-tighter">
        Vue<span class="font-normal">FakeAuth</span>
      </h1>
    <nav>
        <ul class="flex space-x-4">
            <router-link to="/"><li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-300 hover:text-white">Home</li></router-link>
            <router-link to="/about"><li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-300 hover:text-white">About</li></router-link>
            <router-link to="/login"><li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-300 hover:text-white">Login</li></router-link>
            <router-link to="/secret"><li class="py-8 px-4 hover:cursor-pointer hover:bg-yellow-300 hover:text-white">Secret</li></router-link>
        </ul>
    </nav>
</div>
</div>

</template>