# 🧱 backend-starter

Proyecto base para microservicios con Spring Boot, diseñado como plantilla para pruebas de integración con IA, despliegue en la nube y seguridad aplicada.

## 🚀 Características

- Arquitectura limpia por capas (Controller, Service, Repository)
- Documentación automática con Swagger (OpenAPI)
- Soporte para Docker
- Configuración con `application.properties`
- Logging estructurado con SLF4J
- Base de datos desacoplada (PostgreSQL configurado opcionalmente)

## 📁 Estructura

src 
├── main │ 
 ├── java │ 
  │ └── com │ 
   │ └── carlosrdev │  
     ├── controller │ 
     ├── service │ │
     ├── repository │ 
     └── model │ 
     └── resources │ 
     ├── application.properties 
     │ └── static


## 🐳 Cómo levantar con Docker

1. Construir el `.jar`:
./mvnw clean package
Construir la imagen Docker:

docker build -t backend-starter .
Ejecutar:

docker run -p 8080:8080 backend-starter

🔍 Documentación API
Una vez levantado el proyecto, accede a la documentación Swagger en:

http://localhost:8080/swagger-ui/index.html
✅ Pendientes
 Integrar API externa de prueba (para pruebas IA)

 Añadir seguridad básica con JWT

 Configurar CI/CD en GitHub Actions

🧠 Notas
Este proyecto forma parte de un roadmap personal de exploración backend, abarcando inteligencia artificial, despliegue cloud y prácticas de seguridad.

Carlos Adrián Rivera Rodríguez – LinkedIn
https://www.linkedin.com/in/carlosrdev/
