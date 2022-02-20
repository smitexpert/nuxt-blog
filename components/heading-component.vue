<template>
<div class="bg-white py-8 w-full justify-center items-center flex">
  <div class="w-3/4">
    <div class="flex w-full pb-3 border-b items-center">
      <div class="w-1/4">
        <h1 class="text-sm font-bold"><nuxt-link to="/">My Blog</nuxt-link></h1>
      </div>
      <div class="w-2/4 text-center">
        <!-- <p>This is a cute blog</p> -->
      </div>
      <div class="w-1/4 float-end text-right">
        <button v-if="!isSearch" class="bg-white mb-4" @click="getSearch">Search</button>
        <div v-else class="w-full relative">
          <input placeholder="Search..." class="focus:outline-none w-full" ref="search"  @click="getSearch" /><button class="absolute float-left right-0 bg-white">Search</button>
          <div class="w-full border-b mt-4"></div>
        </div>
      </div>
    </div>
    <div class="flex w-full pt-3">
      <div class="w-3/4">
        <ul class="flex flex-wrap">
          <li class="text-sm font-light"><a class="px-4 py-2" href="#">Home</a></li>
          <li class="text-sm font-light"><a class="px-4 py-2" href="#">Home</a></li>
          <li class="text-sm font-light"><a class="px-4 py-2" href="#">Home</a></li>
          <li class="text-sm font-light"><a class="px-4 py-2" href="#">Home</a></li>
        </ul>
      </div>
      <div class="w-1/4 text-right">
        <a href="#" class="tex-sm font-bold">Shop</a>
      </div>
    </div>
  </div>
</div>
</template>
<script>

export default {
  name: 'heading-component',
  data(){
    return {
      isSearch: false
    }
  },

  methods: {
    async getSearch() {
      await this.updateRef();
      this.$refs.search.focus();
    },
    updateRef(){
      this.isSearch = true;
    }
  }
}
</script>

