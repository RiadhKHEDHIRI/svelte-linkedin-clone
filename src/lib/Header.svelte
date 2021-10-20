<script>
  import HeaderOption from "./HeaderOption.svelte";
</script>

<div class="flex items-center top-0 sticky z-50 bg-white border-b border-gray-200 mb-16">
  <div class="flex flex-1 items-center space-x-4">
    <!-- LinkedIn Icon -->
    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 text-blue-500" fill="none" viewBox="0 0 24 24" stroke="currentColor">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
    </svg>
    <div class="relative flex rounded items-center  text-gray-500">
      <svg xmlns="http://www.w3.org/2000/svg" class="absolute left-1 h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
      </svg>
      <input type="text" class="border focus:border focus:border-blue-500 pl-10 py-2 rounded focus:bg-blue-50 bg-gray-50 outline-none" placeholder="Search anything">
    </div>
  </div>
  <div class="flex space-x-4 items-center">
    <HeaderOption title="Home"/>
    <HeaderOption title="My Network"/>
    <HeaderOption title="Jobs"/>
  </div>
  <div class="flex ml-12">
    <HeaderOption title="Me"/>
  </div>
</div>