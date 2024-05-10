<script setup lang="ts">
</script>

<template>
  <div class="mx-auto container">
    <Suspense>
      <ClientOnly>
        <div class="text-center text-purple">
          Hello World!
        </div>
      </ClientOnly>
      <template #fallback>
        <div italic op50>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
  </div>
</template>
