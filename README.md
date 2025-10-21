# AppKotlin

A full-stack sample app combining a **Kotlin** frontend with a **Laravel (PHP)** backend.


---

## Project overview

**AppKotlin** demonstrates a Kotlin-based frontend (Android, Kotlin/JS, or Kotlin Multiplatform — adapt as needed) communicating with a Laravel API backend. Use it as a starter template or reference implementation.

---

## Tech stack

- **Frontend:** Kotlin (Android / Kotlin/JS / KMM — adjust to your flavor)  
- **Backend:** Laravel (PHP)  
- **Database:** MySQL / MariaDB (or SQLite for quick local dev)  
- **Tools:** Composer, PHP, Java JDK, Gradle (or included Gradle wrapper), Node.js / npm (if Kotlin/JS)

---

## Repo structure

```text
AppKotlin/
├── backend_laravel/     # Laravel backend app
│   ├── app/
│   ├── bootstrap/
│   ├── config/
│   ├── database/
│   ├── routes/
│   ├── .env.example
│   └── composer.json
└── frontend_kotlin/     # Kotlin frontend app (Android / Kotlin/JS / KMM)
    ├── src/
    ├── build.gradle(.kts) or gradlew
    └── README.md
