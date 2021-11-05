<template>
  <div id="app">
    <div class="card">
      <br />
      <agenda-show />
      <br />
      <agenda-input />
    </div>
  </div>
</template>

<script>
import AgendaInput from "./components/AgendaInput.vue";
import AgendaShow from "./components/AgendaShow.vue";
export default {
  name: "App",
  components: {
    AgendaInput,
    AgendaShow,
  },
};
</script>
