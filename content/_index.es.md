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
** }**
.profile-img {
margin-bottom: 1rem;
** }**
}
</style>
<div class="container">
<div>
<p>Soy Benjamin Cordero, graduado de Ingeniería Civil Informática de la Universidad Adolfo Ibáñez.</p>
<!-- <p>¡Mira algunos de mis proyectos!</p> -->
<p>Contáctame para cualquier consulta en: </p>
<p><i class="fas fa-envelope"> </i> Correo: <a href="mailto:benjamincorderog@gmail.com">benjamincorderog@gmail.com</a>
<p><i class="fab fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/benjacordero/">@benjacordero</a></p>
</div>
<img src="hello.jpg" alt="Foto de perfil" class="profile-img">
</div>

## Conocimientos Técnicos

- **Lenguajes de Programación**: Python, C, TypeScript, SQL
- **IaaC**: Docker, GitHub Actions, Terraform, Ansible
- **Sistemas Operativos**: Linux, Windows, MacOS
