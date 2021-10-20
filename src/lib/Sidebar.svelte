<script>
  export let name = 'John Smith'
  export let title = 'Managing Director'
</script>

<div class="flex flex-col flex-initial w-64">
  <div class="flex flex-col rounded bg-white space-y-4 content-center">
    <img class="bg-img rounded-t"
         src="https://unsplash.com/photos/ZzuZPx4d6VA/download?ixid=MnwxMjA3fDB8MXxhbGx8fHx8fHx8fHwxNjM0NTg2NTUy&force=true&w=640"
         alt="">
    <div class="flex flex-col items-center">
      <img class="rounded-full object-cover h-24 w-24" src="https://unsplash.com/photos/ZFNXdi58O5Q/download?ixid=MnwxMjA3fDB8MXx0b3BpY3x8dG93SlpGc2twR2d8fHx8fDJ8fDE2MzQ3MzI4MjU&force=true&w=640" alt="">
      <p class="font-bold">{name}</p>
      <p class="text-gray-500">{title}</p>
    </div>
    <div class="p-2 py-4">
      <div class="">
        <div class="flex">
          <div class="flex-1">Who viewed your profile</div>
          <a href="#" class="font-bold text-blue-700">1,457</a>
        </div>
        <div class="flex">
          <div class="flex-1">Views of your posts</div>
          <a href="#" class="font-bold text-blue-700">3,259</a>
        </div>
      </div>
    </div>
  </div>

  <div class="rounded bg-white mt-4 p-1 py-4">
    <p class="font-bold px-2">Recent</p>
    <div class="flex flex-col">
      <a href="#" class="rounded p-1 px-2 text-gray-400 hover:text-blue-700 hover:bg-gray-50">#svelte</a>
      <a href="#" class="rounded p-1 px-2 text-gray-400 hover:text-blue-700 hover:bg-gray-50">#front-end</a>
      <a href="#" class="rounded p-1 px-2 text-gray-400 hover:text-blue-700 hover:bg-gray-50">#ux-design</a>
    </div>
  </div>
</div>

<style>
  .bg-img {
    margin-bottom: -60px;
    object-fit: cover;
  }
</style>