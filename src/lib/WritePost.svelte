<script>
  import InputOption from './InputOption.svelte'
</script>
<div class="bg-white rounded p-2">
  <form class="flex border px-8 py-2 rounded-full" on:submit|preventDefault action="">
    <div class="relative flex flex-grow items-center">
      <svg xmlns="http://www.w3.org/2000/svg" class="absolute left-2 h-6 w-6" fill="none" viewBox="0 0 24 24"
           stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M15.232 5.232l3.536 3.536m-2.036-5.036a2.5 2.5 0 113.536 3.536L6.5 21.036H3v-3.572L16.732 3.732z"/>
      </svg>
      <input class="flex-grow pl-10 p-2 outline-none" type="text" placeholder="Write here...">
    </div>
    <button class="mx-2 px-7 rounded bg-blue-300 hidden" type="submit">Post</button>
  </form>
  <div class="flex justify-around">
    {#each ['Photo', 'Video', 'Event', 'Write article'] as title, i}
    <InputOption {title} />

    {/each}
  </div>
</div>