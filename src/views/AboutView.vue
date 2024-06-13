<template>
  <div class="about">
    <h2>Todo List Application</h2>
    <br>
    <p>
      TodoList is a CRUD todo tracking application created with vue3 composition API.
    </p>
    <br>
    <p>
      Track your daily task's using this todo tracker with abilites to save, complete, edit and delete todos.
    </p>
    <br>
    <p>
      Feel free to add on to this application with functionalities such as the ability to drag and reorder todos, animate creation/deletion of todos or even create this into a full stack application with the ability to have different lists for different days of tracking todos!
    </p>
    <br>
    <h4>
      Contact:
    </h4>
    <p>Raviraj Khopade</p>
    <a href="mailto:rmkhopade21@gmail.com">rmkhopade21@gmail.com</a>
    <br>
    <a href="https://github.com/Roger9876/todo-list-application.git" target="_blank">Github repo</a>
  </div>
</template>

<script setup>
import { useLink } from 'vue-router';
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
