<template>
  <div class="bg-gray-100 w-full h-auto min-h-screen">
    <LazyHeadingComponent />
    <div class="flex justify-center flex-wrap">
      <div class="container mt-8">
        <Nuxt />
        <LazySidebarComponent />
      </div>
    </div>
    <LazyFooterComponent />
  </div>
</template>