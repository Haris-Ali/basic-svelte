<script>
    export let todoList = []
</script>

{#each todoList as list (list.id)}
    <p class="listItem">{list.id}. {list.name}</p>
{/each}

<style>
    .listItem {
        width: 70%;
        background: #ecf0f1;
        margin: 1rem auto;
        text-align: start;
        padding: 10px 20px;
        border-radius: 10px;
    }
</style>

