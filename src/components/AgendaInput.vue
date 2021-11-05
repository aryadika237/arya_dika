<template>
  <div></div>
</template>
<script>
/* eslint-disable */
import axios from "axios";
export default {
  data() {
    return {
      users: [],
    };
  },
  mounted() {
    this.load();
  },
  methods: {
    load() {
      axios
        .get("http://localhost:3000/users")
        .then((res) => {
          this.users = res.data; //respon dari rest api dimasukan ke users
        })
        .catch((err) => {
          console.log(err);
        });
    },
  },
};
</script>
<style></style>
