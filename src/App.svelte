<script>
	import ListInput from './components/ListInput.svelte'
	import TodoList from './components/TodoList.svelte'
	let todoList = [
		{ id: '1', 'name': 'hello world'},
		{ id: '2', 'name': 'hello world'},
		{ id: '3', 'name': 'hello world'},
		{ id: '4', 'name': 'hello world'},
	]
</script>

<main class="mainContainer">
	<h1>Todo List App with Svelte</h1>
	<ListInput />
	<TodoList {todoList} />
</main>