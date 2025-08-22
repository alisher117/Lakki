<template>
  <nav class="navbar fixed-top navbar-expand-lg bg-pink rounded">
    <div class="container-fluid">

      <!-- Mobile Toggler Button -->
      <button
        class="navbar-toggler collapsed"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarsExample10"
        aria-controls="navbarsExample10"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <!-- Collapsible Navbar Content -->
      <div class="navbar-collapse justify-content-md-center collapse" id="navbarsExample10">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Главная</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#sector2">О нас</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#sector3">Контакты</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#sector4">Услуги</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
import "@/assets/navbar.css"
export default {};
</script>
