<script>
    let x = 7;
</script>

{#if x > 10}
    <p>{x} is greater then 10</p>
{:else if 5 > x}
    <p>{x} is less then 5</p>
{:else}
    <p>{x} is between 5 and 10</p>
{/if}