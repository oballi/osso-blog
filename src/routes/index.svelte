<script context="module">
    export async function load() {
        const url = `https://jsonplaceholder.typicode.com/posts`;
        const res = await fetch(url);
        const posts = await res.json();
        return {
            props: {posts}
        }
    }
</script>

<script>
    export let posts;

import Card from '../components/Card.svelte';
</script>

<Card {posts} />