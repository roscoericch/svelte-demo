<script lang="ts">
    export let age:number = 10;
    $: factoAge = age * 10
</script>

<section>
<h1>my Age is {age}</h1>
<h1>facto Age is {factoAge}</h1>
</section>