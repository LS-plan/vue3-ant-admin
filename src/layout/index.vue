<template>
  <div>
    <todoList :todolist="todolist"></todoList>
  </div>
</template>

<script>
import todoList from "../components/todoList.vue";
export default {
  name: "index",
  components: {
    todoList,
  },
  data() {
    return {
      todolist: [
        { id: 1, task: "吃饭", isCompleted: true },
        { id: 2, task: "睡觉", isCompleted: false },
        { id: 3, task: "打豆豆", isCompleted: false },
      ],
    };
  },
};
</script>

<style></style>
