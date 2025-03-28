<template>
  <div>
    <!-- Hero Section -->
    <section class="hero">
      <div class="container">
        <div class="row align-items-center">
          <div class="col-lg-6">
            <h1 class="display-4 fw-bold text-white mb-3">Viaja con comodidad y seguridad</h1>
            <p class="lead text-white-75 mb-4">El mejor servicio de transporte terrestre entre Comarapa y Santa Cruz.</p>
            <div class="d-flex gap-3">
              <a href="#horarios" class="btn btn-primary btn-lg">Ver Horarios</a>
              <a href="#contacto" class="btn btn-outline-light btn-lg">Contacto</a>
            </div>
          </div>
          <div class="col-lg-6 d-none d-lg-block">
            <img src="https://images.unsplash.com/photo-1544620347-c4fd4a3d5957?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2069&q=80" alt="Bus Transportation" class="img-fluid rounded-4 shadow-lg">
          </div>
        </div>
      </div>
    </section>

    <!-- Features Section -->
    <section class="features py-5">
      <div class="container">
        <div class="text-center mb-5">
          <h2 class="fw-bold">¿Por qué elegir TransComarapa?</h2>
          <p class="lead text-muted">Servicio de calidad en la ruta Comarapa - Santa Cruz</p>
        </div>
        
        <div class="row g-4">
          <div class="col-md-4">
            <div class="feature-card">
              <div class="feature-icon">
                <i class="bi bi-shield-check"></i>
              </div>
              <h4>Seguridad Garantizada</h4>
              <p>Flota de vehículos modernos con mantenimiento constante y conductores profesionales.</p>
            </div>
          </div>
          
          <div class="col-md-4">
            <div class="feature-card">
              <div class="feature-icon">
                <i class="bi bi-clock-history"></i>
              </div>
              <h4>Puntualidad</h4>
              <p>Cumplimos con los horarios establecidos para que llegues a tiempo a tu destino.</p>
            </div>
          </div>
          
          <div class="col-md-4">
            <div class="feature-card">
              <div class="feature-icon">
                <i class="bi bi-wifi"></i>
              </div>
              <h4>Comodidad a Bordo</h4>
              <p>Asientos reclinables, aire acondicionado, WiFi y entretenimiento durante el viaje.</p>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Horarios Section -->
    <section id="horarios" class="py-5 bg-light">
      <div class="container">
        <div class="text-center mb-5">
          <h2 class="fw-bold">Horarios de Salida</h2>
          <p class="lead text-muted">Consulta nuestros horarios desde Comarapa y Santa Cruz</p>
        </div>
        
        <div class="row mb-4">
          <div class="col-md-6">
            <div class="card h-100">
              <div class="card-header bg-primary text-white">
                <h5 class="mb-0">Salidas desde Comarapa</h5>
              </div>
              <div class="card-body">
                <div class="schedule-item">
                  <div class="d-flex justify-content-between">
                    <div>
                      <h6>Comarapa → Santa Cruz</h6>
                      <p class="small text-muted mb-0">Duración: 3 horas</p>
                    </div>
                    <div class="text-end">
                      <span class="badge bg-primary mb-1">Bs. 80</span>
                    </div>
                  </div>
                  <div class="departure-times mt-2">
                    <span class="time-badge">08:00 AM</span>
                    <span class="time-badge">02:00 PM</span>
                    <span class="time-badge">08:30 PM</span>
                    <span class="time-badge">11:30 PM</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          
          <div class="col-md-6">
            <div class="card h-100">
              <div class="card-header bg-primary text-white">
                <h5 class="mb-0">Salidas desde Santa Cruz</h5>
              </div>
              <div class="card-body">
                <div class="schedule-item">
                  <div class="d-flex justify-content-between">
                    <div>
                      <h6>Santa Cruz → Comarapa</h6>
                      <p class="small text-muted mb-0">Duración: 3 horas</p>
                    </div>
                    <div class="text-end">
                      <span class="badge bg-primary mb-1">Bs. 80</span>
                    </div>
                  </div>
                  <div class="departure-times mt-2">
                    <span class="time-badge">10:30 AM</span>
                    <span class="time-badge">02:00 PM</span>
                    <span class="time-badge">06:30 PM</span>
                    <span class="time-badge">08:30 PM</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        
        <div class="card mt-4">
          <div class="card-body">
            <p class="text-center mb-0">
              <i class="bi bi-info-circle text-primary me-2"></i>
              Para mayor información, puedes llamarnos al <strong>+591 3 1234567</strong> o visitarnos en nuestras oficinas.
            </p>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Testimonials -->
    <section class="testimonials py-5">
      <div class="container">
        <div class="text-center mb-5">
          <h2 class="fw-bold">Lo que dicen nuestros pasajeros</h2>
          <p class="lead text-muted">Experiencias reales de quienes confían en nuestro servicio</p>
        </div>
        
        <div class="row g-4">
          <div class="col-lg-4">
            <div class="testimonial-card">
              <div class="testimonial-quote">
                <i class="bi bi-quote"></i>
              </div>
              <p class="testimonial-text">Viajo frecuentemente con TransComarapa y siempre me ha parecido un servicio excepcional. Los buses son cómodos y los conductores muy profesionales.</p>
              <div class="testimonial-author d-flex align-items-center mt-3">
                <div class="testimonial-avatar">
                  <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="María López">
                </div>
                <div class="ms-3">
                  <h5 class="mb-0">María López</h5>
                  <p class="text-muted mb-0">Viajera Frecuente</p>
                </div>
              </div>
            </div>
          </div>
          
          <div class="col-lg-4">
            <div class="testimonial-card">
              <div class="testimonial-quote">
                <i class="bi bi-quote"></i>
              </div>
              <p class="testimonial-text">Me encanta la puntualidad del servicio. He viajado varias veces y siempre llegan a la hora establecida. Además, el personal es muy amable.</p>
              <div class="testimonial-author d-flex align-items-center mt-3">
                <div class="testimonial-avatar">
                  <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Carlos Méndez">
                </div>
                <div class="ms-3">
                  <h5 class="mb-0">Carlos Méndez</h5>
                  <p class="text-muted mb-0">Empresario</p>
                </div>
              </div>
            </div>
          </div>
          
          <div class="col-lg-4">
            <div class="testimonial-card">
              <div class="testimonial-quote">
                <i class="bi bi-quote"></i>
              </div>
              <p class="testimonial-text">La comodidad de los buses es excelente. Recomiendo ampliamente el servicio, especialmente para viajes largos.</p>
              <div class="testimonial-author d-flex align-items-center mt-3">
                <div class="testimonial-avatar">
                  <img src="https://randomuser.me/api/portraits/women/44.jpg" alt="Ana Flores">
                </div>
                <div class="ms-3">
                  <h5 class="mb-0">Ana Flores</h5>
                  <p class="text-muted mb-0">Estudiante</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    
    <!-- Contact Section -->
    <section id="contacto" class="py-5 bg-light">
      <div class="container">
        <div class="text-center mb-5">
          <h2 class="fw-bold">Contáctanos</h2>
          <p class="lead text-muted">Estamos para ayudarte en lo que necesites</p>
        </div>
        
        <div class="row">
          <div class="col-lg-4 mb-4 mb-lg-0">
            <div class="card h-100">
              <div class="card-body text-center">
                <div class="contact-icon mb-3">
                  <i class="bi bi-geo-alt"></i>
                </div>
                <h5>Oficina Comarapa</h5>
                <p class="mb-0">Av. Principal #123</p>
                <p>Comarapa, Bolivia</p>
                <p class="small text-muted">Lun-Dom: 7:00AM - 9:00PM</p>
              </div>
            </div>
          </div>
          
          <div class="col-lg-4 mb-4 mb-lg-0">
            <div class="card h-100">
              <div class="card-body text-center">
                <div class="contact-icon mb-3">
                  <i class="bi bi-geo-alt"></i>
                </div>
                <h5>Oficina Santa Cruz</h5>
                <p class="mb-0">Terminal Bimodal, Local #45</p>
                <p>Santa Cruz de la Sierra, Bolivia</p>
                <p class="small text-muted">Lun-Dom: 6:00AM - 10:00PM</p>
              </div>
            </div>
          </div>
          
          <div class="col-lg-4">
            <div class="card h-100">
              <div class="card-body text-center">
                <div class="contact-icon mb-3">
                  <i class="bi bi-telephone"></i>
                </div>
                <h5>Teléfonos de Contacto</h5>
                <p class="mb-2">+591 3 1234567 (Comarapa)</p>
                <p class="mb-2">+591 3 7654321 (Santa Cruz)</p>
                <p class="mb-0">info@transcomarapa.com</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
.hero {
  background: linear-gradient(135deg, #1a2a6c, #b21f1f);
  padding: 6rem 0;
  margin-bottom: 2rem;
}

.text-white-75 {
  color: rgba(255, 255, 255, 0.75);
}

.feature-card {
  padding: 2rem;
  text-align: center;
  border-radius: 8px;
  background-color: #fff;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease;
  height: 100%;
}

.feature-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
}

.feature-icon {
  margin-bottom: 1.5rem;
  font-size: 2.5rem;
  color: #ffc107;
}

.testimonial-card {
  padding: 2rem;
  border-radius: 8px;
  background-color: #fff;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
  height: 100%;
}

.testimonial-quote {
  font-size: 2rem;
  color: #ffc107;
  margin-bottom: 1rem;
}

.testimonial-avatar img {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  object-fit: cover;
}

.btn-primary {
  background-color: #ffc107;
  border-color: #ffc107;
  color: #212529;
}

.btn-primary:hover {
  background-color: #ffca2c;
  border-color: #ffca2c;
}

.badge.bg-primary {
  background-color: #ffc107 !important;
  color: #212529;
}

.card-header.bg-primary {
  background-color: #1a2a6c !important;
}

.schedule-item {
  padding-bottom: 1rem;
  border-bottom: 1px solid #e9ecef;
  margin-bottom: 1rem;
}

.schedule-item:last-child {
  border-bottom: none;
  padding-bottom: 0;
  margin-bottom: 0;
}

.time-badge {
  display: inline-block;
  padding: 0.25rem 0.5rem;
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
  background-color: #f8f9fa;
  color: #212529;
  border-radius: 4px;
  font-size: 0.875rem;
  font-weight: 500;
}

.contact-icon {
  font-size: 2.5rem;
  color: #ffc107;
}

.text-primary {
  color: #ffc107 !important;
}
</style>

