<template>
    <div>
        <TodoItem />
    </div>
</template>

<script>
import TodoItem from './TodoItem.vue'
export default {
    name: "ToDo",
    components: TodoItem,
    props: ["todos"]
}
</script>

<style scoped>

</style>