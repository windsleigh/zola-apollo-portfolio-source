+++
title = "Hola que tal"
template = "homepage.html"
+++
<style>
.container {
 display: flex;
 align-items: flex-start;
 gap: 2rem;
 flex-direction: row-reverse;
}

.profile-img {
 width: 200px;
 height: 200px;
 border-radius: 50%;
 object-fit: cover;
}

@media (max-width: 768px) {
 .container {
   flex-direction: column;
   align-items: center;
   text-align: center;
 }
 
 .profile-img {
   margin-bottom: 1rem;
 }
}
</style>

<div class="container">
<div>
<p>Soy Benjamin Cordero, graduado en Ingeniería Civil Informática de la Universidad Adolfo Ibáñez, especializado en Linux y tecnología.</p>
<p>Contáctame para cualquier consulta en: </p>
<p><i class="fas fa-envelope"></i> Email: <a href="mailto:benjamincorderog@gmail.com" target="_blank">benjamincorderog@gmail.com</a></p>
<p><i class="fab fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/benjacordero/" target="_blank">@benjacordero</a></p>
</div>
<img src="hello.jpg" alt="Foto de perfil" class="profile-img">
</div>

## Stack Tecnológico
- Backend: Python, C, TypeScript, SQL
- DevOps: Docker, CI/CD, GIT
- Especialidades: Resolución de Problemas Técnicos, Despliegue en la Nube, Pruebas de QA
