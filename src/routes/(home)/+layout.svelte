<script lang="ts">
	import Footer from '$lib/components/Footer.svelte';
	import NavBar from '$lib/components/NavBar.svelte';
	import '../../app.css';
</script>

<div
	class="pt-10 bg-[#1c1c1c] text-white
  flex flex-col justify-between gap-4 items-center min-h-screen"
>
	<div class="flex flex-col items-center gap-4">
		<NavBar />
		<slot />
	</div>
	<Footer />
</div>
