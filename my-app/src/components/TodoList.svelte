<script>
	// import TodoControls from "./TodoControls.svelte";
	import TodoAitem from "./TodoAitem.svelte";
</script>

<div class="todo-list">
    <!-- <TodoControls/> -->
    <div class="todo-list__field">
        <TodoAitem/>   
    </div>
</div>


<style>
    .todo-list {
        width: 700px;
        height: 80%;
        background: gray;
        border-radius: 15px;
    }

</style>