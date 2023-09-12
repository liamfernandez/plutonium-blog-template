<script lang="ts">
	import { goto } from '$app/navigation';
	// import './blog-post.css';
</script>

<div class="pt-10 bg-[#1c1c1c] text-white min-h-screen">
	<span class="flex justify-center gap pb-20">
		<button
			on:click={() => {
				goto('/blog');
			}}
			class="bg-purple-800 hover:bg-purple-900 text-white font-bold py-2 px-4 rounded"
		>
			Back to all posts
		</button>
	</span>
	<article class="prose prose-h1:text-white prose-p:text-white w-[720px] mx-auto">
		<slot />
	</article>
</div>
