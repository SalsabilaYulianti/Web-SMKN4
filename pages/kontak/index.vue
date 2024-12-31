<script setup>

const kata = "Selamat di SMK NEGARI 4 TASIKMALAYA"

function kirim() {
  alert("Pesan Terkirim " + kata);
}

</script>

<template>
  <div class="container">
    <form>
      <div class="form-group mt-5">
        <label for="exampleInputName">Nama
        </label>
        <input type="text" class="form-control rounded-3 mt-2" aria-describedby="emailHelp">
      </div>
      <div class="form-group mt-3">
        <label for="exampleInputEmail">Email
        </label>
        <input type="email" class="form-control rounded-3 mt-2" aria-describedby="emailHelp">
      </div>
      <div class="form-group mt-3">
        <label for="exampleInputMessage">Pesan
        </label>
        <input type="text" class="form-control rounded-3 mt-2 pesan"  aria-describedby="emailHelp">
      </div>
      <button @click="kirim" class="btn btn-primary mt-3">Submit</button>
    </form>
  </div>
</template>

<style scoped>
.container {
  height: 100vh;
  width: 100%;
}

.pesan{
  height: 80px;
}
</style>