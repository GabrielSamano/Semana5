<template>
  <div>
    <form action="submit">
      <ul class="nav">
  <li class="nav-item">
    <a class="nav-link active" aria-current="page" href="#">Home</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Pasteles</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Pedido</a>
  </li>
  <li class="nav-item">
    <a class="nav-link disabled">About</a>
  </li>
</ul>
<select class="form-select" aria-label="Default select example">
  <option selected>Escoge cual te gustaria</option>
  <option value="1">Pasteles</option>
  <option value="2">Pan</option>
  <option value="3">Galletas</option>
</select>

<div>
  <img src="https://images.unsplash.com/photo-1571115177098-24ec42ed204d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80" alt="">
</div>
<div>
  <table class="table">
  <thead>
    <tr>
      <th scope="col">Precio</th>
      <th scope="col">Pastel</th>
      <th scope="col">Precio</th>
      <th scope="col">Pan</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th scope="row">$250</th>
      <td>Cajeta</td>
      <td>$20</td>
      <td>Dona</td>
    </tr>
    <tr>
      <th scope="row">$230</th>
      <td>Tres Leches</td>
      <td>$15</td>
      <td>Cuernito</td>
    </tr>
    <tr>
      <th scope="row">$230</th>
      <td>Chocolate</td>
      <td>$18</td>
      <td>Concha</td>
    </tr>
  </tbody>
</table>
</div>

    </form>
  </div>
</template>

<style>


</style>