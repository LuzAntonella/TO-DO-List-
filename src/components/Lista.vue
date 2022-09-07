<template>
  <div class="cont">
    <h1>TO DO LIST</h1>
    <div class="add-task">
      <input
        type="text"
        placeholder=" Elemento de la lista"
        class="task-input"
      />
      <input type="submit" value="" class="submit-task" title="Add Task" />
    </div>
    <ul class="task-list">
      <li class="task-list-item">
        <label class="task-list-item-label">
          <input type="checkbox" />
          <span>Ir a concierto de jamiroquai</span>
        </label>
        <span class="delete-btn" title="Delete Task"></span>
      </li>
    </ul>
    <br />
    <hr />
    <ul class="task-complet">
      <li>
        <input type="checkbox" name="list" id="nivel1-1" /><label
          class="desplegable"
          for="nivel1-1"
          >Elementos completados</label
        >
        <ul class="interior">
          <li class="task-list-item">
            <label class="task-list-item-label">
              <input type="checkbox" />
              <span>Task</span>
            </label>
            <span class="delete-btn" title="Delete Task"></span>
          </li>
        </ul>
      </li>
    </ul>
  </div>
</template>
<script>
export default {
  name: "Lista",
  data() {},
};
</script>
<style>
@import "../assets/css/styles.css";
</style>