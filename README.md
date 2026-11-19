# 🚀 CRM Esplai — mAIte

<p align="center">
  <strong>mAIte · CRM de empleabilidad con IA</strong><br>
  Proyecto finalizado · Bootcamp FullStack Java_10 · Fundación Esplai
</p>

<p align="center">
  Plataforma CRM orientada a la gestión del acompañamiento laboral: alumnado, empresas, vacantes, candidaturas y seguimiento en un único lugar.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/estado-finalizado-22c55e?style=for-the-badge" alt="Proyecto finalizado">
  <img src="https://img.shields.io/badge/equipo-5%20personas-2563eb?style=for-the-badge" alt="Equipo de cinco personas">
</p>

## ✨ Sobre el proyecto

**CRM Esplai**, , también llamado **mAIte**, es una aplicación full-stack de empleabilidad con IA creada para centralizar la gestión de la relación entre el alumnado, las empresas y sus oportunidades laborales. Facilita el seguimiento de candidaturas y entrevistas, la organización de información relevante y el apoyo al proceso de inserción laboral.

> ℹ️ Este repositorio está pensado como muestra de portafolio. Todos los datos que se publiquen son de demostración y nunca contendran información personal, credenciales ni claves de servicios externos.

## 🎬 Demostración

> ⏳ Próximamente se añadirá un vídeo corto y/o una prueba visual de la aplicación desarrollada.

<!-- Sustituye esta sección por el enlace al vídeo cuando esté publicado. -->

## 🧩 Funcionalidades

### 👩‍🎓 Gestión de alumnado

- Alta, edición y consulta de perfiles de alumnos.
- Organización por cursos y estado de búsqueda de empleo.
- Registro de notas, seguimiento y documentos asociados.
- Subida y almacenamiento de CV en Google Drive.

### 🏢 Gestión de empresas

- Directorio de empresas con información de contacto y estado.
- Etiquetas para clasificar y filtrar empresas.
- Notas, seguimiento e histórico de interacciones.
- Importación de empresas desde archivos Excel.

### 💼 Vacantes y candidaturas

- Creación y gestión de ofertas laborales.
- Asociación de alumnos a cada oferta y control del estado de sus candidaturas.
- Consulta de detalles de oferta, empresa y candidato desde la misma aplicación.

### 🗓️ Entrevistas y seguimiento

- Programación de entrevistas y recordatorios.
- Calendario y panel de entrevistas pendientes.
- Seguimiento de acciones e interacciones de alumnos y empresas.

### 🤖 Apoyo con inteligencia artificial

- Análisis de CVs en PDF para extraer competencias, fortalezas y resumen profesional.
- Análisis de ofertas para identificar requisitos técnicos y habilidades valoradas.
- Cálculo de afinidad entre alumno y vacante.
- Ranking de candidatos para cada oferta.

> La IA es un apoyo a la decisión; sus resultados requieren revisión humana.

### 📊 Panel y estadísticas

- Dashboard con información relevante y acciones pendientes.
- Estadísticas de contrataciones y evolución de resultados.
- Búsqueda global de alumnos, empresas y ofertas.
- Centro visual de notificaciones.

### 🔐 Usuarios e integraciones

- Autenticación basada en sesiones y gestión de usuarios con roles.
- Integración con Gmail para comunicaciones.
- Integración con Google Calendar y Google Drive mediante OAuth.

## 🛠️ Tecnologías y herramientas

### 🎨 Frontend

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-8-CA4245?logo=reactrouter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4-06B6D4?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-8-646CFF?logo=vite&logoColor=white)

### ⚙️ Backend

![Java](https://img.shields.io/badge/Java-25-ED8B00?logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-4-6DB33F?logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring_AI-2-6DB33F?logo=spring&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?logo=gradle&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit_5-25A162?logo=junit5&logoColor=white)

### 🗄️ Datos, servicios e infraestructura

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?logo=flyway&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google_Drive-4285F4?logo=googledrive&logoColor=white)
![Google Calendar](https://img.shields.io/badge/Google_Calendar-4285F4?logo=googlecalendar&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-EA4335?logo=gmail&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-AI-000000?logo=groq&logoColor=white)

## 🏗️ Arquitectura

```text
React + TypeScript + Tailwind CSS
              │
              ▼
       API REST · Spring Boot
              │
 ┌────────────┼────────────┐
 ▼            ▼            ▼
PostgreSQL  Google APIs   IA con Groq
```

## 👥 Equipo creador

Proyecto desarrollado por un equipo de **5 personas**:

| Integrante | GitHub | LinkedIn |
| --- | --- | --- |
| Facundo | [@Promerante](https://github.com/Promerante) | [Perfil](https://www.linkedin.com/in/facundo-daniel-benitez-noguera-577a4134b/) |
| Sandra | [@Sfernan92](https://github.com/Sfernan92) | [Perfil](https://www.linkedin.com/in/sandrafern%C3%A1ndez/) |
| Javier | [@alzahira](https://github.com/alzahira) | [Perfil](https://www.linkedin.com/in/javier-jaenes/) |
| Miguel | [@Miguelarcal](https://github.com/Miguelarcal) | [Perfil](https://www.linkedin.com/in/miguel-arroyo-calvo-b071ab306/) |
| Gabriel | [@GabrielPostigo](https://github.com/GabrielPostigo) | [Perfil](https://www.linkedin.com/in/gabriel-postigo-rando-240724191/) |

---

<p align="center">Desarrollado durante el Bootcamp FullStack Java_10 de Fundación Esplai.</p>
