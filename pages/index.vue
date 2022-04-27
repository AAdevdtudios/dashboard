<template>
  <div class="min-h-screen bg-gray-300">
    <div class="h-80 min-w-full fixed bg-indigo-600 p-3">
      <div class="flex justify-between items-center w-full">
        <h1 class="text-2xl font-bold text-white">RCCG Parish Name</h1>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-16 w-16"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-6-3a2 2 0 11-4 0 2 2 0 014 0zm-2 4a5 5 0 00-4.546 2.916A5.986 5.986 0 0010 16a5.986 5.986 0 004.546-2.084A5 5 0 0010 11z"
            clip-rule="evenodd"
          />
        </svg>
      </div>
    </div>
  </div>
</template>

<script>
import CardItem from "~/components/CardItem.vue";
export default {
  components: { CardItem },
  name: "IndexPage",
};
</script>
