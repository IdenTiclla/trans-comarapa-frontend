<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <NuxtLink class="navbar-brand" :to="{name: 'index'}">Home</NuxtLink>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <NuxtLink class="nav-link active" aria-current="page" :to="{name: 'blog'}">Blog</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" :to="{name: 'contacto'}">Contacto</NuxtLink>
        </li>   
        <li class="nav-item">
            <NuxtLink class="nav-link" :to="{name: 'login'}">Login</NuxtLink>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
</template>