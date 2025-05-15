<script setup>
const menuitems = [
  {
    title: "Sign up",
    url: "https://tinyurl.com/Klt289Offcl",
  },
  {
    title: "Log in",
    url: "https://tinyurl.com/Klt289Offcl",
  },
];
</script>

<template>
  <Container>
    <header class="flex flex-row flex-wrap items-center justify-between my-4 gap-x-6 gap-y-4">
      <div class="flex items-center justify-between">
        <a href="/" class="text-2xl font-bold text-zinc-800">
          <span class="text-green-500"><NuxtImg class="rounded-lg" sizes="100vw lg:600px" :src="https://files.sitestatic.net/ImageFile/20240701165425000000bbdc049371YUGELAI__167x44.webp" :alt="imageAlt" v-if="image" /></span> KILAT289
        </a>
      </div>
      <nav class="flex w-auto">
        <ul class="flex flex-row gap-3 text-sm">
          <li v-for="item of menuitems">
            <a :href="item.url" class="flex px-3 py-2 text-gray-600 border rounded-sm hover:text-gray-800">
              {{ item.title }}
            </a>
          </li>
        </ul>
      </nav>
    </header>
  </Container>
</template>
