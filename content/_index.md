+++
title = "Hey There"
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
<p>I'm Benjamin Cordero, a Computer Engineering graduate from Adolfo Ibáñez University, focused on Linux and tech. </p>
<p>Contact me for any inquiries at: </p>
<p><i class="fas fa-envelope"> </i> Email: <a href="mailto:benjamincorderog@gmail.com">benjamincorderog@gmail.com</a>
<p><i class="fab fa-linkedin"></i> LinkedIn: <a href="https://www.linkedin.com/in/benjacordero/">@benjacordero</a></p>
</div>
<img src="hello.jpg" alt="Profile picture" class="profile-img">
</div>

## Tech Stack
- Backend: Python, C, TypeScript, SQL
- DevOps: Docker, CI/CD, GIT
- Specialties: Solving Tech Problems, Cloud Deployment, QA Testing
