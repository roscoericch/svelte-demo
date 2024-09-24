<script lang="ts">
    import Age from "../components/Age.svelte";
    let age:number = 21;
    function add() {
        age += 1
    }
    function minus() {
        age -= 1
    }
</script>

<main class="h-full flex flex-col items-center justify-center">
    <Age {age} />
    <input bind:value={age} type="number" />
    <button on:click={add}>+</button>
    <button on:click={minus}>-</button>
</main>
