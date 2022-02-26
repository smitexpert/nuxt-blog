<template>
  <div class="bg-gray-100 w-full h-auto min-h-screen">
    <LazyHeadingComponent />
    <div class="flex justify-center flex-wrap">
      <div class="container">
        <div class="w-full flex flex-wrap my-8">
          <LazyBannerPost />
          <LazyBannerPost />
        </div>
      </div>
      <div class="container">
        <Nuxt />
        <LazySidebarComponent />
      </div>
    </div>
    <LazyFooterComponent />
  </div>
</template>