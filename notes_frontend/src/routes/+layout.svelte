<script lang="ts">
  import "../app.css";
  import Header from "$lib/components/Header.svelte";
  import Sidebar from "$lib/components/Sidebar.svelte";
  import Editor from "$lib/components/Editor.svelte";
</script>

<div class="container-app">
  <Header />
  <div class="main-area">
    <Sidebar />
    <main>
      <Editor />
    </main>
  </div>
</div>
