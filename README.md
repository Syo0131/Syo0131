# 🕹️ JAVA BACKEND QUEST: MISSION START 🕹️

<p align="center">
<pre>
      _                       ____             _                      _ 
     | | __ ___   ____ _     | __ )  __ _  ___| | _____ _ __   __| |
  _  | |/ _` \ \ / / _` |    |  _ \ / _` |/ __| |/ / _ \ '_ \ / _` |
 | |_| | (_| |\ V / (_| |    | |_) | (_| | (__|   <  __/ | | | (_| |
  \___/ \__,_| \_/ \__,_|    |____/ \__,_|\___|_|\_\___|_| |_|\__,_|
</pre>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LEVEL-21-blue?style=press-start&color=FFD700" />
  <img src="https://img.shields.io/badge/CLASS-BACKEND_DEVELOPER-red?style=press-start" />
  <img src="https://img.shields.io/badge/HP-100%2F100-brightgreen?style=press-start" />
</p>

---

### 📜 CHARACTER PROFILE
> **MISSION:** Architecting scalable systems and slaying monolithic legacy code.  
> **GUILD:** Open Source Community  
> **LOCATION:** Server-Side Realm  
> **STATUS:** 🟢 Online - Ready for new Boss Fights (Projects)

---

### 🎒 INVENTORY (Tech Stack)

| Slot | Item | Level (Power) |
| :--- | :--- | :--- |
| ⚔️ **Main Weapon** | Java / Spring Boot | ![90%](https://geps.dev/progress/90?dangerColor=800080&accColor=00FF00&nightMode=true) |
| 🛡️ **Shield** | Hibernate / JPA | ![85%](https://geps.dev/progress/85?dangerColor=800080&accColor=00FF00&nightMode=true) |
| 🧪 **Potion** | Docker / Kubernetes | ![75%](https://geps.dev/progress/75?dangerColor=800080&accColor=00FF00&nightMode=true) |
| 📓 **Scroll** | PostgreSQL / MySQL | ![80%](https://geps.dev/progress/80?dangerColor=800080&accColor=00FF00&nightMode=true) |
| ⚡ **Buff** | Kafka / Redis | ![60%](https://geps.dev/progress/60?dangerColor=800080&accColor=00FF00&nightMode=true) |

---

### 🏆 QUEST LOG (Featured Projects)

# 💰 Spendly - Smart Financial Tracker

> Sistema de gestión financiera personal con procesamiento automático de transacciones bancarias mediante análisis de emails.

## 🚀 Tecnologías Principales

### Backend
![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

### Seguridad & Autenticación
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=for-the-badge&logo=auth0&logoColor=white)

### Integraciones
![Gmail API](https://img.shields.io/badge/Gmail_API-EA4335?style=for-the-badge&logo=gmail&logoColor=white)
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![MapStruct](https://img.shields.io/badge/MapStruct-1.6-FF6C37?style=for-the-badge)

## ✨ Características Principales

- 🔐 **Autenticación segura** - JWT + Spring Security con roles de usuario
- 📧 **Integración Gmail API** - Procesamiento automático de emails bancarios con OAuth2
- 🏦 **Multi-banco** - Parser inteligente para banco QIK (República Dominicana)
- 🤖 **Categorización automática** - Sistema de ML básico con diccionario de palabras clave
- ⚡ **Procesamiento asíncrono** - Batch processing con Spring Async
- ⏰ **Scheduler inteligente** - Procesamiento automático para usuarios premium
- 💾 **Persistencia robusta** - PostgreSQL con transacciones ACID
- 🎯 **Metas de ahorro** - Sistema de tracking con historial de contribuciones
- 🔄 **Mapeo automático** - MapStruct para conversión DTO-Entity
- 📊 **API RESTful** - Endpoints documentados con Swagger/OpenAPI

## 🏗️ Arquitectura
spendly/
├── 🎯 Controllers (API REST)
├── 🧠 Services (Lógica de negocio)
├── 💾 Repositories (Acceso a datos)
├── 🗂️ Models (Entidades JPA)
├── 📦 DTOs (Transferencia de datos)
├── 🔄 Mappers (MapStruct)
├── 🛡️ Security (JWT + OAuth2)
├── 🔧 Utils (Utilidades compartidas)
└── 📧 Email Processing (Gmail API)


## 🎯 Casos de Uso

1. **Usuario se registra** → Autentica con JWT
2. **Conecta Gmail** → OAuth2 flow para acceso seguro
3. **Sistema lee emails** → Parser extrae transacciones del banco QIK
4. **Auto-categorización** → Algoritmo clasifica: Alimentación, Transporte, etc.
5. **Dashboard en tiempo real** → Visualiza gastos e ingresos
6. **Metas de ahorro** → Trackea progreso hacia objetivos financieros

## 🔧 Stack Técnico Completo

| Categoría | Tecnología |
|-----------|-----------|
| **Lenguaje** | Java 21 |
| **Framework** | Spring Boot 3.x, Spring Data JPA, Spring Security |
| **Base de Datos** | PostgreSQL 14+ |
| **Autenticación** | JWT (jjwt), OAuth2 |
| **API Externa** | Gmail API (Google Cloud Platform) |
| **Mapeo** | MapStruct 1.6 |
| **Build Tool** | Maven |
| **Testing** | JUnit 5, Spring Boot Test |
| **Containerización** | Docker |
| **Logging** | SLF4J + Logback |

## 🚦 Estado del Proyecto

- ✅ Sistema de autenticación completo
- ✅ Integración Gmail API funcional
- ✅ Parser QIK Bank implementado
- ✅ CRUD de gastos e ingresos
- ✅ Sistema de metas de ahorro
- ✅ Categorización automática
- ✅ Procesamiento batch asíncrono
- 🔄 Dashboard frontend (en desarrollo)
- 📋 Integración con más bancos (planificado)


* **[Side Quest: The API Portal]** *Integración masiva de servicios externos con seguridad OAuth2.* `Spring Security` `JWT`

---
### 📊 SYSTEM DIAGNOSTICS (Stats)

<div align="center">

| 🛠️ GLOBAL STATISTICS | 📚 LANGUAGE PROFICIENCY |
| :---: | :---: |
| <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=Syo0131&show_icons=true&theme=retro&hide_border=true&count_private=true&include_all_commits=true" width="400px" /> | <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Syo0131&layout=compact&theme=retro&hide_border=true&langs_count=6" width="350px" /> |

</div>
---
---

### 📫 LET'S CONNECT

<p align="left">
  <a href="https://linkedin.com/in/DaybelDiaz" target="_blank">
    <img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:diazdaybelsamuel@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---
