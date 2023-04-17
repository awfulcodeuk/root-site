<script setup lang="ts">
</script>

<template>
  <div>
    <Suspense>
      <div>
        <Header />
        <HomePageContent />
      </div>
      <template #fallback>
        <div op50 italic>
          <span animate-pulse>Loading...</span>
        </div>
      </template>
    </Suspense>
  </div>
</template>
