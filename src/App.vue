

<template>
  <div class="container">
    <!-- NAVBAR -->
    <nav class="navbar">
      <h1 class="logo">Brian Sastre</h1>
      <ul class="nav-links">
        <li><a href="#about" @click="scrollTo('about')">Sobre mí</a></li>
        <li><a href="#education" @click="scrollTo('education')">Educación</a></li>
        <li><a href="#projects" @click="scrollTo('projects')">Proyectos</a></li>
        <li><a href="#skills" @click="scrollTo('skills')">Habilidades</a></li>
        <li><a href="#contact" @click="scrollTo('contact')">Contacto</a></li>
      </ul>
    </nav>

    <!-- HERO SECTION -->
    <section id="about" class="hero">
      <div class="hero-content">
        <div class="profile-card">
          <div class="profile-img-container">
            <img
              src="../public/perfil.png"
              alt="Brian Sastre"
              class="profile-img"
            />
          </div>
          <div class="profile-info">
            <h1 class="name">Brian Sastre</h1>
            <h2 class="title">Técnico Electromecánico & Desarrollador Full Stack</h2>
            <p class="location">📍 Concepción del Uruguay, Entre Ríos</p>
            <p class="description">
              Técnico Electromecánico con un fuerte interés en el Front-End y una sólida 
              formación en programación. Proactivo, creativo y orientado a resultados, 
              con habilidades avanzadas en React y TypeScript.
            </p>
            <div class="social-links">
              <a href="https://github.com/briansastre-ops" target="_blank" class="social-btn github">
                <span>GitHub</span>
              </a>
              <a href="https://www.linkedin.com/in/brian-sastre-a137452" target="_blank" class="social-btn linkedin">
                <span>LinkedIn</span>
              </a>
              <a href="https://briansastre-portfolio.vercel.app/" target="_blank" class="social-btn portfolio">
                <span>Portfolio</span>
              </a>
              <a href="mailto:briansastre159@gmail.com" class="social-btn email">
                <span>Email</span>
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- EDUCACIÓN -->
    <section id="education" class="section">
      <div class="section-content">
        <h2 class="section-title">Educación</h2>
        <div class="timeline">
          <div class="timeline-item">
            <div class="timeline-marker current"></div>
            <div class="timeline-content">
              <h3>Tecnicatura Universitaria en Programación – Full Stack</h3>
              <h4>Universidad Tecnológica Nacional (UTN) – San Rafael</h4>
              <p class="period">2025 – Actualidad (En curso)</p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-marker"></div>
            <div class="timeline-content">
              <h3>Full Stack Python</h3>
              <h4>Codo a Codo 4.0 – Ciudad de Buenos Aires</h4>
              <p class="period">Abril 2024 – Julio 2024</p>
            </div>
          </div>
          <div class="timeline-item">
            <div class="timeline-marker"></div>
            <div class="timeline-content">
              <h3>Técnico Electromecánico</h3>
              <h4>Escuela Técnica N.° 2 "Francisco Ramírez"</h4>
              <p class="period">Marzo 2014 – Diciembre 2022</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- PROYECTOS -->
    <section id="projects" class="section bg-alt">
      <div class="section-content">
        <h2 class="section-title">Proyectos Destacados</h2>
        <div class="projects-grid">
          <div class="project-card">
            <div class="project-header">
              <h3>
                <a href="https://travelapp-bms.netlify.app/" target="_blank" style="color:inherit;text-decoration:none;">
                  Travel App
                </a>
              </h3>
              <div class="project-tags">
                <span class="tag">HTML</span>
                <span class="tag">CSS</span>
                <span class="tag">JavaScript</span>
              </div>
            </div>
            <p>Aplicación web para planificar viajes, destacando el enmaquetado de una App de Campamentos y Viajes con diseño responsive.</p>
          </div>
          <div class="project-card">
            <div class="project-header">
              <h3>
                <a href="https://obsidian-saas.netlify.app/" target="_blank" style="color:inherit;text-decoration:none;">
                  Full Responsive Web Application, obsidian SaaS
                </a>
              </h3>
              <div class="project-tags">
                <span class="tag">react</span>
                <span class="tag">CSS</span>
                <span class="tag">vite</span>
              </div>
            </div>
            <p>Aplicación web completamente responsive con diseño adaptativo para garantizar una experiencia fluida en todos los dispositivos.</p>
          </div>
          <div class="project-card">
            <div class="project-header">
              <h3>
                <a href="https://pizzeriacac.netlify.app/" target="_blank" style="color:inherit;text-decoration:none;">
                  Food App - Pizzería CAC
                </a>
              </h3>
              <div class="project-tags">
                <span class="tag">html</span>
                <span class="tag">css</span>
                <span class="tag">JavaScript</span>
              </div>
            </div>
            <p>Sistema de gestión de inventario que permite seguimiento eficiente, administración de productos y generación de informes detallados.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- HABILIDADES -->
    <section id="skills" class="section">
      <div class="section-content">
        <h2 class="section-title">Habilidades</h2>
        <div class="skills-container">
          <div class="skills-category">
            <h3>Tecnologías Principales</h3>
            <div class="skills-grid">
              <div class="skill-item">React</div>
              <div class="skill-item">TypeScript</div>
              <div class="skill-item">JavaScript</div>
              <div class="skill-item">Next.js</div>
              <div class="skill-item">Python</div>
              <div class="skill-item">Flask</div>
              <div class="skill-item">HTML</div>
              <div class="skill-item">CSS</div>
            </div>
          </div>
          <div class="skills-category">
            <h3>Habilidades Blandas</h3>
            <div class="soft-skills">
              <div class="soft-skill">✓ Comunicación efectiva</div>
              <div class="soft-skill">✓ Trabajo en equipo</div>
              <div class="soft-skill">✓ Adaptabilidad</div>
              <div class="soft-skill">✓ Capacidad de aprendizaje rápido</div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CONTACTO -->
    <section id="contact" class="section bg-alt">
      <div class="section-content">
        <h2 class="section-title">Contacto</h2>
        <div class="contact-info">
          <div class="contact-item">
            <h3>📧 Email</h3>
            <a href="mailto:briansastre159@gmail.com">briansastre159@gmail.com</a>
          </div>
          
          <div class="contact-item">
            <h3>📍 Ubicación</h3>
            <p>Concepción del Uruguay, Entre Ríos</p>
          </div>
        </div>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
      <p>&copy; 2025 Brian Sastre. Todos los derechos reservados.</p>
    </footer>
  </div>
</template>

<script setup>
import './App.css'
const scrollTo = (elementId) => {
  const element = document.getElementById(elementId);
  if (element) {
    element.scrollIntoView({ behavior: 'smooth' });
  }
}
</script>

