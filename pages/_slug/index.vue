<template>
  <div class="bg-gray-50 w-full h-auto min-h-screen">
    <heading-component />
    <div class="flex justify-center">
      <div class="container">
        <single-post-component />
      </div>
    </div>
    <footer-component />
  </div>
</template>

<script>

export default {
  components: {
    headingComponent: ()=> import('@/components/heading-component.vue'),
    singlePostComponent: ()=> import('@/components/SinglePost.vue'),
    footerComponent: () => import('@/components/footerComponent.vue'),
    },
  name: 'IndexPage',
}
</script>
