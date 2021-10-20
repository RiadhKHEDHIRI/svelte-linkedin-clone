<script lang="ts">
  import './tailwind.css'
  import Header from "./lib/Header.svelte";
  import Sidebar from "./lib/Sidebar.svelte";
  import Feed from "./lib/Feed.svelte"
</script>

<main class="px-4 py-4 max-w-7xl mx-auto">
  <Header/>
  <div class="flex bg-gray-200 space-x-4 p-2">
    <Sidebar/>
    <Feed />
  </div>
</main>
