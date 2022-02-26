<template>
  <div class="w-2/3 h-auto">
    <blog-post-item :isImage='false' :color="`black`" />
    <blog-post-item :isImage='true' :color="`red`" />

    <pagination-component />
  </div>
</template>

<script>
export default {
  components: {
    blogPostItem: () => import('./blogPostItem.vue'),
    paginationComponent: () => import('./pagination-component.vue'),
  }
}
</script>
