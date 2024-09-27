<script lang="ts">
	import '../app.css';
	import { ModeWatcher } from "mode-watcher";
 </script>

<svelte:head> 
  <link rel="preload" as="font" href="/fonts/geist/GeistVF.woff2" type="font/woff2" crossorigin="anonymous"> 
  <link rel="preload" as="font" href="/fonts/geist/GeistMonoVF.woff2" type="font/woff2" crossorigin="anonymous"> 
</svelte:head>
	
 <ModeWatcher />
 <slot />
