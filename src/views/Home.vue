<template>
  <div class="home">
    <img alt="Vue logo" class="logo" src="../assets/logo.png" />

    <todo-list></todo-list>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "@/components/HelloWorld.vue";
import TodoList from "@/components/TodoList.vue";

export default {
  name: "Home",
  components: {
    TodoList
  }
};
</script>
