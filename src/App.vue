<template>
  <div class="container">
    <!-- NAVBAR -->
    <nav class="navbar">
      <h1 class="logo">Mi Portafolio</h1>
      <ul class="nav-links">
        <li><a href="#about">Sobre mí</a></li>
        <li><a href="#projects">Proyectos</a></li>
        <li><a href="#contact">Contacto</a></li>
      </ul>
    </nav>

    <!-- CARD PERSONAL -->
    <section id="about" class="about">
      <div class="card">
        <img
          src="https://via.placeholder.com/150"
          alt="Mi Foto"
          class="profile-img"
        />
        <h2>Brian Sastre</h2>
        <p>Estudiante de Programación - UTN</p>
        <div class="links">
          <a href="https://github.com/briansastre-ops" target="_blank">GitHub</a>
          <a href="https://www.linkedin.com" target="_blank">LinkedIn</a>
        </div>
      </div>
    </section>
  </div>
</template>

<script setup>
// Por ahora no lleva lógica, es solo estructura
</script>

<style>
/* RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background-color: #f4f4f9;
}

/* NAVBAR */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background: #004aad;
  padding: 15px 30px;
  color: white;
}

.navbar .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links a {
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: #ffcc00;
}

/* CARD */
.about {
  display: flex;
  justify-content: center;
  margin-top: 50px;
}

.card {
  background: white;
  padding: 20px;
  border-radius: 15px;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
  width: 300px;
  text-align: center;
}

.profile-img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  margin-bottom: 15px;
  border: 4px solid #004aad;
}

.card h2 {
  margin-bottom: 10px;
}

.card p {
  margin-bottom: 20px;
  color: #555;
}

.links {
  display: flex;
  justify-content: center;
  gap: 15px;
}

.links a {
  padding: 8px 16px;
  border-radius: 8px;
  background: #004aad;
  color: white;
  text-decoration: none;
  font-size: 0.9rem;
  transition: background 0.3s;
}

.links a:hover {
  background: #003080;
}
</style>
