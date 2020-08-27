<template>
  <header class="h-nscreen flex items-center justify-center">
    <div class="bg-white flex flex-col w-3/5 px-8 py-8 items-center shadow-lg rounded">
      <div
        class="text-3xl font-light text-center leading-8 w-2/3"
      >Order food from the widest range of restaurants.</div>

      <div class="mt-8 flex w-full">
        <input
          type="text"
          class="bg-gray-200 w-full py-3 px-5 text-sm font-light focus:outline-none text-gray-700 focus:shadow-inner rounded-l"
          placeholder="Restaurant or Cuisine (leave it blank to browse all)"
        />
        <button
          class="text-xs w-56 text-white bg-green-600 hover:bg-green-700 rounded-r"
        >Find Restaurants</button>
      </div>
    </div>
  </header>
</template>

<style>
header {
  background: url("https://images.pexels.com/photos/313700/pexels-photo-313700.jpeg?auto=compress&cs=tinysrgb&dpr=2&w=1200")
    no-repeat;
  background-size: cover;
}
</style>