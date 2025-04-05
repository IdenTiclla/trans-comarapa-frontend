<template>
  <footer class="footer">
    <div class="container">
      <div class="row gy-4">
        <div class="col-lg-4 col-md-6">
          <h5 class="text-white mb-3">TransComarapa</h5>
          <p class="text-white-80">Servicio de transporte de pasajeros entre Comarapa y Santa Cruz. Viaja cómodo y seguro con nosotros.</p>
          <div class="social-links mt-3">
            <a href="#" class="social-icon"><i class="bi bi-facebook"></i></a>
            <a href="#" class="social-icon"><i class="bi bi-twitter"></i></a>
            <a href="#" class="social-icon"><i class="bi bi-instagram"></i></a>
            <a href="#" class="social-icon"><i class="bi bi-whatsapp"></i></a>
          </div>
        </div>

        <div class="col-lg-4 col-md-6">
          <h5 class="text-white mb-3">Horarios de Atención</h5>
          <ul class="list-unstyled footer-contact">
            <li class="text-white-80"><strong class="text-white">Comarapa:</strong> Lun-Dom: 7:00AM - 9:00PM</li>
            <li class="text-white-80"><strong class="text-white">Santa Cruz:</strong> Lun-Dom: 6:00AM - 10:00PM</li>
            <li class="mt-3 text-white-80"><i class="bi bi-info-circle text-warning"></i> Recomendamos llegar 30 minutos antes de la salida</li>
          </ul>
        </div>

        <div class="col-lg-4 col-md-6">
          <h5 class="text-white mb-3">Contacto</h5>
          <ul class="list-unstyled footer-contact">
            <li class="text-white-80"><i class="bi bi-geo-alt text-warning"></i> Av. Principal #123, Comarapa, Bolivia</li>
            <li class="text-white-80"><i class="bi bi-geo-alt text-warning"></i> Terminal Bimodal, Local #45, Santa Cruz</li>
            <li class="text-white-80"><i class="bi bi-telephone text-warning"></i> +591 3 1234567 (Comarapa)</li>
            <li class="text-white-80"><i class="bi bi-telephone text-warning"></i> +591 3 7654321 (Santa Cruz)</li>
            <li class="text-white-80"><i class="bi bi-envelope text-warning"></i> info@transcomarapa.com</li>
          </ul>
        </div>
      </div>

      <hr class="my-4 bg-light">

      <div class="row">
        <div class="col-md-12 text-center">
          <p class="text-white-80 mb-0">&copy; {{ new Date().getFullYear() }} TransComarapa. Todos los derechos reservados.</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.footer {
  background: linear-gradient(135deg, var(--comarapa-green-dark), var(--comarapa-green));
  color: #fff;
  padding: 3rem 0 1.5rem;
}

.text-white-80 {
  color: rgba(255, 255, 255, 0.9) !important;
}

.footer-contact li {
  padding: 0.3rem 0;
}

.footer-contact i {
  margin-right: 0.5rem;
}

.text-warning {
  color: var(--comarapa-green-light) !important;
}

.social-links {
  display: flex;
  gap: 10px;
}

.social-icon {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;
  height: 36px;
  border-radius: 50%;
  background-color: rgba(255, 255, 255, 0.2);
  color: white;
  transition: all 0.3s ease;
}

.social-icon:hover {
  background-color: var(--comarapa-green-light);
  color: var(--comarapa-white);
  transform: translateY(-3px);
}

hr {
  border-color: rgba(255, 255, 255, 0.2);
}
</style>