<template>
  <div class="w-1/3 h-auto pl-4">
    <profile-card />
    <category-card />
    <project-card />
  </div>
</template>

<script>
export default {
  components: {
    profileCard: () => import('./sidebar/profileCard.vue'),
    CategoryCard: () => import('./sidebar/CategoryCard.vue'),
    ProjectCard: ()=> import('./sidebar/ProjectCard.vue')
  }
}
</script>
