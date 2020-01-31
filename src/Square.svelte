<script>
    export let value;
    export let handleClick;
</script>

<style>
    .square {
        flex: 1 0 25%;
        width: 140px;
        height: 140px;
        background-color: lightgoldenrodyellow;
        border: none;
        border-radius: 0.5em;
        margin: 5px;
        padding: 5px;
        text-align: center;
        font-size: 40px;
        color: lightsalmon;
    }

    .square:hover {
        background: lightsalmon;
    }
</style>

<button class="square" on:click={handleClick}>{value || ""}</button>
