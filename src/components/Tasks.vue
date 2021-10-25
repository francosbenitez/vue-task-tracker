<template>
    <div v-for="(task, i) in tasks" :key="i">
        {{ task.text }}
    </div>
</template>

<script>
export default {
    name: 'Tasks',
    props: {
        tasks: Array
    }
}
</script>
