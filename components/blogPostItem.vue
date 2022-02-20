<template>
  <div class="w-full flex bg-white mb-6 drop-shadow-md">
    <div class="w-4 h-auto flex-none" :style="`background-color: ${color}`"></div>
    <div class="flex-1 w-auto flex flex-wrap">
      <div class="w-full" v-if="isImage">
        <img class="w-full h-auto" src="https://via.placeholder.com/1200x720" />
      </div>
      <div class="w-full p-6">
        <div class="w-full flex pb-4 border-b">
          <div class="w-1/2">
            <p class="font-light text-gray-600 text-sm">January 2, 2022</p>
          </div>
          <div class="w-1/2 text-right">
            <a href="#" class="font-light text-gray-600 text-sm hover:underline" :style="`color: ${color}`">CATEGORY NAME</a>
          </div>
        </div>

        <div class="w-full my-4">
          <h4 class="transition duration-300 ease-in-out no-underline mb-4 hover:underline hover:duration-300">
            <nuxt-link to="single-post" class="pb-4 text-4xl text-black">Lorem ipsum dolor sit.</nuxt-link>
          </h4>
          <p class="text-lg font-light text-gray-400 leading-6">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Eaque veniam nobis nesciunt sit aut reiciendis quidem magnam culpa perferendis aspernatur. Culpa suscipit a, aperiam atque minima eos vitae officiis earum.
          </p>
        </div>
        <div class="w-full flex py-4">
          <div class="w-1/2">
            <a href="#" class="bg-white text-gray-600 px-6 py-2 rounded-full border border-black hover:bg-black hover:text-white btn-hover-animation">Read More</a>
          </div>
          <div class="w-1/2 text-right">
            <a href="#" class="text-gray-600 px-6 py-2 hover:underline">7 Responses</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    isImage: Boolean,
    color: {
      type: String,
      default: 'black'
    }
  }
}
</script>
