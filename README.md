# Hi, I'm Ben 👋

Software developer and 2026 Ontario Tech University Computer Science graduate with enterprise development experience at Ontario Power Generation.

I build, test, and deploy full-stack applications using **Python/FastAPI, Java/Spring Boot, React/TypeScript, SQL, Docker, and automated testing**. My main project is [bortle.app](https://bortle.app/), a live astronomy planning application powered by real ephemeris and weather data.

## Featured projects

### 🔭 [AstroPlanner](https://github.com/days-hub/astroplanner) — [Live demo](https://bortle.app/)

A deployed astronomy session planner that helps users determine what is actually visible from their location and when it is worth observing.

* Computes real-time sky visibility using JPL ephemeris data through Skyfield
* Combines astronomical calculations with hourly weather forecasts
* Includes a grounded LLM advisor restricted to data calculated by the application
* Uses JWT authentication, PostgreSQL, FastAPI, SQLAlchemy, React, and TypeScript
* Runs through Docker Compose with Nginx and automatic TLS on a Linux VPS
* Uses GitHub Actions CI for backend tests, frontend linting and builds, and Docker image validation
* Includes a seeded demo mode with no registration required

### 🏆 [Arena Master](https://github.com/days-hub/arena-master)

A full-stack esports tournament management platform with a **Java/Spring Boot backend**, PostgreSQL database, and React/Material UI frontend.

* Rebuilt the original FastAPI backend in Java using Spring Boot and Spring Data JPA
* Migrated persistence from SQLite to PostgreSQL with versioned Flyway database migrations
* Designed idempotent REST APIs for bracket generation, automatic round advancement, and cross-tournament standings
* Added Bean Validation and centralized exception handling for consistent API validation and errors
* Includes an interactive bracket with click-to-record match results
* Integrates Discord webhooks for live tournament result announcements
* Runs the application and PostgreSQL database through Docker Compose

### 🧠 [FocusFlow](https://github.com/days-hub/FocusFlow)

A cross-platform productivity application developed as a four-person capstone project using Flutter, Firebase, and SQLite.

My primary contributions included:

* Building a K-means clustering system from scratch to identify productive focus windows
* Engineering session-level metrics used for personalized scheduling recommendations
* Developing the offline-first SQLite and Firestore synchronization layer
* Implementing Google Sign-In and contributing to security hardening
* Collaborating through code reviews and Agile iteration

## Professional experience

### Ontario Power Generation

Previously worked as an **Information Systems Technician intern** at OPG and was rehired for the remainder of the summer based on performance.

* Collaborated within a two-developer team to deliver three Power Apps for internal business workflows
* Built JavaScript and Office JS tooling for on-demand Word document generation
* Helped replace a legacy VBA workflow and establish the foundation for migrating a specialized template library
* Gathered requirements, troubleshot workflow issues, documented solutions, and supported adoption

## Core technologies

**Languages:** Python, Java, TypeScript, JavaScript, SQL, C#, Dart
**Backend:** FastAPI, Spring Boot, Spring Data JPA, SQLAlchemy, REST APIs, Node.js, pytest
**Frontend:** React, HTML/CSS, Material UI, Flutter
**Data:** PostgreSQL, MySQL, SQL Server, SQLite, Firebase Firestore, Flyway
**Deployment:** Docker, Docker Compose, Nginx, Linux, GitHub Actions
**Security:** JWT, OAuth 2.0, Google Sign-In, rate limiting, input validation

## What I'm looking for

I'm currently pursuing **new-grad and junior software engineering opportunities** in backend, full-stack, and application development.

Outside of software, I spend a lot of time learning astronomy and attempting to extract unreasonable amounts of detail from planets through an eight-inch telescope.

## Contact

* [LinkedIn](https://www.linkedin.com/in/ben-walsh-7570aa109/)
* [Email](mailto:bwalsh9764@gmail.com)
* [Live project](https://bortle.app/)
