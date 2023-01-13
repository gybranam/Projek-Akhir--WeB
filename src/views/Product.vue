<template>
    <div>
        <NavBar/>
        <h2>Daftar Produk</h2>
        <table class="table">
  <thead>
    <tr>
      <th scope="col">id</th>
      <th scope="col">Nama</th>
      <th scope="col">UOM</th>
      <th scope="col">Stock</th>
      <th scope="col">Harga</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">1</th>
      <td>Mark</td>
      <td>Otto</td>
      <td>@mdo</td>
    </tr>
    <tr>
      <th scope="row">2</th>
      <td>Jacob</td>
      <td>Thornton</td>
      <td>@fat</td>
    </tr>
    <tr>
      <th scope="row">3</th>
      <td colspan="2">Larry the Bird</td>
      <td>@twitter</td>
    </tr>
  </tbody>
</table>
    </div>
</template>

<script>
// @ is an alias to /src
import NavBar from '@/components/NavBar.vue'

export default {
  name: 'Product',
  components: {
    NavBar

  }
}
</script>
