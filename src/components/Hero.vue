<template>
  <div class="hero">
    <!-- Desktop -->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2>
                <strong>BARANG TERBAIK,</strong>
                <br />CUMAN ADA DISINI!!
              </h2>
              <router-link class="btn btn-lg btn-success" to="/product">
                <b-icon-arrow-right></b-icon-arrow-right>Pesan Sekarang
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/images/shopping.png" width="100%" />
        </div>
      </div>
    </div>
  </div>
</template>
  
  <script>
export default {
  name: "Hero",
};
</script>
  
  <style>
</style>