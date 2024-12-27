<template>
  <div class="container">
    <div class="container-fluid cover p-0">
            <div class="row">
                <div class="col">
                    <div class="text-center">
                        <h1 class="text mt-5">SMK NEGRI 4</h1>
                        <h3 class="text mt-4">KOTA TASIKMALAYA</h3>
                    </div>
                </div>
            </div>
    </div>

        <!-- sambutan -->
        <div class="container-sam p-4 rounded-5">
          <div class="card container-card p-0 rounded-5">
            <div class="row costum p-5 justify-content-center">
              <h3 class="fw-bold p-5" style="text-align:center">Sambutan Kepala Sekolah</h3>
                <div class="col-lg-3 col-md-4 d-flex">
                  <div class="card flex-fill card rounded-2">
                    <div class="card-body text-center">
                      <img src="../asset/kepsek.jpeg" alt="img-custom" class="card-img-top">
                    </div>
                  </div>
                </div>
                <div class="col-lg-5 col-md-6 text-costum">
                  <h5 class="p-2">Assalamu'alaikum warahmatullohi wabarokatuh</h5>
                  <h5 class="p-4">Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-Nya.
                    Dan atas perkenan-Nya pula kami dapat menghadirkan wesbite SMK NEGERI 4 Tasikmalaya </h5>
                </div>
            </div>
          </div>
        </div>

        <!-- jurusan -->
        <div class="cake ">
          <div class="row justify-content-center">
            <div class="col-lg-2">
              <!-- <div class="text-center"> -->
                <h4>Konsentrasi Keahlian</h4>
                <!-- <hr class="mt-3"> -->
              <!-- </div> -->
             </div>
          </div>
        </div>
  </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Inria+Serif:ital,wght@0,300;0,400;0,700;1,300;1,400;1,700&display=swap');

.cover {
  background: url('../asset/bg2.png') no-repeat center center;
  background-size: cover;
  height: 550px;
  width: 100%;
  max-width: 2000px;
}
.row{
  padding-top: 170px;
  /* color: aliceblue; */
  margin-right: 0;
}

.container-card{
  padding-top: 100px; 
}
.text-center{
  border: 8px solid #0505051d;
  border-radius: 10px;
  backdrop-filter: blur(3px);
}

.text{
  color: aliceblue;
}

p{
  font-size: 20px;
}

h1, h3, h4, h5{
  font-family: "Inria Serif", serif;
  font-weight: 500;
  font-style: normal;
  margin: 0px;
  color:black;
}
</style>