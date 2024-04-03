<template>
    <nav class="navbar navbar-expand-lg navbar-light">
    <div class="container-fluid">
      <!-- Logotipo -->
      <a class="navbar-brand" href="#">Logo</a>

      <!-- Botón de hamburguesa para pantallas pequeñas -->
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Contenedor de elementos de la barra de navegación -->
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style src="../assets/css/NavBar.css" scoped></style>
