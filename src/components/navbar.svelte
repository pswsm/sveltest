<script>
    import { each } from "svelte/types/runtime/internal/ssr";

let navElems = [
{
text: "aaaaa",
link: "/aaaaa"
}
]
</script>
<nav>
{#each navElems as navElem}
	<a href={navElem.link}>{navElem.text}</a>
{/each}
</nav>
