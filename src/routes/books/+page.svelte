<script lang="ts">
	import { books } from '$lib/books';
</script>

<h1>Books</h1>

<ul>
	{#each books as book}
		<li>
			<a href="/books/{book.id}">{book.title}</a>
		</li>
	{/each}
</ul>
