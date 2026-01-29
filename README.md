# Knowledge Quest

Knowledge Quest is a quiz web application designed to spark curiosity by exploring
lesser-known but fascinating fields of knowledge.  
The goal of this project is to encourage people of all ages—especially young learners—
to discover new subjects, hobbies, and potential passions through interactive quizzes.

The application is fully deployed and accessible online.

## Live Demo
https://knowledge-quest-bufo.onrender.com/

---

## Tech Stack

### Core Technologies
- [**Django**](https://docs.djangoproject.com/en/6.0/) – Full-stack Python web framework  
  
- [**Python**](https://www.python.org/) – High-level interpreted programming language  
  
- [**PostgreSQL**] – Production-grade relational database  
  (Hosted on **Neon**)

### Authentication
- **Django Allauth** – Secure and feature-rich authentication system  
  https://docs.allauth.org/en/dev/introduction/index.html

> Note: Email verification is currently disabled due to the lack of a transactional
> email service. This feature is planned for future implementation.

### Deployment & Infrastructure
- [**Render**](https://render.com/) – PaaS for application deployment  
  
- [**Neon**](https://neon.com/) – Serverless PostgreSQL hosting  
  

---

## Additional Tools & Libraries
- **Bootstrap 5 (CDN)** – Minimal styling and responsive layout  
- **psycopg3** – PostgreSQL adapter for Python  
- **Uvicorn** – High-performance ASGI server  
- **Gunicorn** – WSGI server managing multiple Uvicorn workers  
- **WhiteNoise** – Static file serving in production

All other dependencies are listed in the `requirements.txt` file.

---

## Future Improvements
- Enable email verification via a transactional email service
- Add more quiz categories and difficulty levels
- Improve UI/UX with enhanced styling
- User analytics and progress tracking

