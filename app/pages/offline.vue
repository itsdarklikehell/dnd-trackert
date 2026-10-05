<script setup lang="ts">
definePageMeta({
  layout: false,
})
</script>

<template>
  <div class="flex min-h-screen flex-col items-center justify-center bg-[#0a0a0a] px-4 text-center">
    <div class="max-w-md space-y-6">
      <div class="text-6xl">
        🐉
      </div>
      <h1 class="text-3xl font-bold text-white">
        You're Offline
      </h1>
      <p class="text-lg text-gray-400">
        It looks like you've lost your connection. Don't worry — your adventures are saved locally and will sync once you're back online.
      </p>
      <button
        class="rounded-lg bg-purple-600 px-6 py-3 text-white transition-colors hover:bg-purple-700"
        @click="() => window.location.reload()"
      >
        Try Again
      </button>
    </div>
  </div>
</template>
