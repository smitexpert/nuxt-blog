<template>
  <div class="bg-gray-50 w-full h-auto min-h-screen">
    <heading-component />
    <div class="flex justify-center">
      <div class="container">
        <main-component />
        <sidebar-component />
      </div>
    </div>
    <footer-component />
  </div>
</template>

<script>

export default {
  components: {
    headingComponent: ()=> import('../components/heading-component.vue'),
    blogPostItem: ()=> import('../components/blogPostItem.vue'),
    mainComponent: ()=> import('../components/mainComponent.vue'),
    sidebarComponent: ()=> import('../components/sidebarComponent.vue'),
    footerComponent: () => import('../components/footerComponent.vue'),
    },
  name: 'IndexPage',
}
</script>
