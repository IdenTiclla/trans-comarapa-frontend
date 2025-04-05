<template>
  <nav class="navbar navbar-expand-lg navbar-dark">
    <div class="container">
      <NuxtLink class="navbar-brand" :to="{name: 'index'}">
        <i class="bi bi-bus-front me-2"></i>TransComarapa
      </NuxtLink>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
              aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <NuxtLink class="nav-link" :to="{name: 'index'}" active-class="active">Inicio</NuxtLink>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#horarios">Horarios</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#encomiendas">Encomiendas</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#delegaciones">Delegaciones</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contacto">Contacto</a>
          </li>
        </ul>
        <div class="d-flex align-items-center">
          <span class="text-white me-3 d-none d-md-block">¡Servicio diario Comarapa - Santa Cruz!</span>
          <a href="tel:+59131234567" class="btn btn-outline-light">
            <i class="bi bi-telephone me-1"></i>Llamar Ahora
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.navbar {
  background: linear-gradient(135deg, var(--comarapa-green-dark), var(--comarapa-green));
  padding: 1rem 0;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

.navbar-brand {
  font-weight: bold;
  font-size: 1.5rem;
  color: white;
}

.nav-link {
  color: rgba(255, 255, 255, 0.85) !important;
  font-weight: 500;
  margin: 0 0.5rem;
  transition: all 0.3s ease;
}

.nav-link:hover, .nav-link.active {
  color: white !important;
  border-bottom: 2px solid var(--comarapa-white);
}

.btn-primary {
  background-color: var(--comarapa-green-light);
  border-color: var(--comarapa-green-light);
  color: var(--comarapa-white);
  font-weight: 500;
}

.btn-primary:hover {
  background-color: var(--comarapa-green);
  border-color: var(--comarapa-green);
}

.btn-outline-light:hover {
  background-color: rgba(255, 255, 255, 0.1);
}
</style>