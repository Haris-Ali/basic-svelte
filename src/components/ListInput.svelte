<script>
    let newItem = ''
    const addItem = () => {

    }
</script>

<div class="listInputBlock">
    <input type="text" name="name" class="listDesc" placeholder="New Item..." bind:value={newItem}>
    <button class="addBtn" on:click="{() => addItem()}">Add</button>
</div>

<style>
    .listInputBlock {
        padding-top: 1.75rem;
        padding-bottom: 3rem;
    }
    
    .listDesc {
        width: 50%;
        padding: 10px 20px;
        border: none;
        border-bottom: 1px solid #FF3E00;
        text-decoration: none;
    }

    .listDesc:focus {
        outline: none;
    }

    .addBtn {
        padding: 10px 20px;
        border-radius: 40px;
        background: #FF3E00;
        color: #FFF;
        border: none;
        cursor: pointer;
    }  
</style>