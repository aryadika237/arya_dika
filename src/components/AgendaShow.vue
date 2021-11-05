<template>
  <div class="header">
    <div style="padding: 30px; display: flex">
      <div class="bagian1">
        <p>LLLL</p>
      </div>
      <div class="bagian2">
        <p>LLL</p>
      </div>
    </div>
  </div>
</template>
//
<script>
// /* eslint-disable */
// import axios from "axios";
// export default {
//   data() {
//     return {
//       users: [],
//     };
//   },
//   mounted() {
//     this.load();
//   },
//   methods: {
//     load() {
//       axios
//         .get("http://localhost:3000/users")
//         .then((res) => {
//           this.users = res.data; //respon dari rest api dimasukan ke users
//         })
//         .catch((err) => {
//           console.log(err);
//         });
//     },
//   },
// };
</script>

<style>
/* h4 {
   text-align: right;
 }
 p {
   text-align: right;
 }
 h6 {
   text-align: right;
 } */
.header {
  background-color: bisque;

  margin-top: -30px;
}
.bagian1 {
  width: 30%;
  background-color: gray;
}
.bagian2 {
  background-color: #fff;
  width: 70%;
}
</style>
