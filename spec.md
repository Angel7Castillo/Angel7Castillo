# Especificación del Proyecto: Marca Profesional Angel Castillo

> **Estado:** Activo / En producción  
> **Última Actualización:** 2026-11-11  
> **Propósito:** Portal de presentación técnica, currículum vivo y repositorio especial de perfil para [github.com/Angel7Castillo](https://github.com/Angel7Castillo).

---

## 1. Visión y Objetivos

* **Posicionamiento:** Desarrollador de Software con especialidad en Sistemas de Escritorio y Móviles (Desktop & Mobile Systems), con núcleo sólido en TypeScript, diseño de arquitecturas limpias y empaquetado nativo.
* **Diferenciación Clave:** En lugar de maquetas o repositorios vacíos, el perfil destaca productos en producción distribuidos en tiendas oficiales (**Google Play** y **Microsoft Store**).
* **Cumplimiento Legal y Propiedad Intelectual:**
  * Cero revelación de clientes confidenciales (proyectos de Vitro, etc.).
  * Código de aplicaciones comerciales protegido en repositorios privados.
  * Solo se exponen casos de estudio abstractos de ingeniería y enlaces de descarga oficial.

---

## 2. Componentes del Repositorio

### 2.1 Portada Pública (`README.md`)
* **Encabezado:** Nombre, rol profesional, ubicación (Montevideo, Uruguay) y switch bilingüe rápido.
* **Sección "Sobre mí":** Tono directo, pragmático y humano (cero clichés de IA, cero Docker).
* **Vitrina de Productos Terminados:**
  * **Billet:** Finanzas personales, Android, offline-first, modularidad TypeScript.
  * **Biblioteca Pastoral:** Gestión de sermones, Windows (10/11), almacenamiento local estructurado, empaquetado Microsoft Store.
* **Criterio de Ingeniería:** Planificación previa, tipado estricto, empaquetado consistente y código mantenible.
* **Herramientas Principales:** TypeScript, JavaScript, SQL, React, Vite, Tailwind CSS, Capacitor, Tauri, Nginx, Linux, Git.
* **Sección en Inglés:** Espejo 1:1 en inglés técnico natural.

### 2.2 Estándares Técnicos (`standards/engineering-principles.md`)
* Principios de diseño previo (Gate 1).
* Tipado estricto como contrato vivo y eliminación de errores en tiempo de compilación.
* Ciclo TDD y confiabilidad (Gate 2 & 4).
* Artesanía de código: funciones atómicas, early returns, inmutabilidad y cero código muerto (Gate 3).
* Compilación y empaquetado determinista.

### 2.3 Casos de Estudio (`case-studies/`)
* **`01-multiplatform-architecture.md`:** Arquitectura de convergencia multiplataforma (Web/Tauri/Capacitor) con lógica de dominio compartida y adaptadores ligeros de plataforma.

### 2.4 Documentación Operativa (`docs/`)
* **`GUIDE.md`:** Protocolo de confidencialidad, plantillas bilingües para nuevas apps y cómo redactar casos de estudio.
* **`ROADMAP.md`:** Historial de fases y backlog de mejoras.

---

## 3. Estado de Fases

- [x] **Fase 1 — Perfil Base y Portada:** Inicializado, subido a GitHub y en vivo en `https://github.com/Angel7Castillo`.
- [x] **Fase 2 — Corrección de Estilo & Cero Docker:** Título normalizado a `## Sobre mí` y todas las referencias a Docker eliminadas.
- [x] **Fase 3 — Adopción y Gobernanza:** Archivos `AGENTS.md` y `spec.md` generados e integrados.
- [x] **Fase 4 — Auditoría Web & Optimización SEO:** Enlaces restaurados a casos de estudio y principios de ingeniería, eliminación de bucles `href="#"` y asociación semántica de stack (TypeScript, Capacitor, Tauri) en fichas de productos.
- [ ] **Fase 5 — Enlaces de Tiendas:** Incorporar URLs definitivas de Google Play y Microsoft Store cuando estén disponibles.
- [ ] **Fase 6 — Nuevos Casos de Estudio:** Optimización de rendimiento y persistencia offline-first.

---

## 4. Requisitos No Funcionales e Invariantes

1. **Privacidad:** Ningún push debe contener archivos con extensiones `.env`, credenciales, datos de clientes o lógica propietaria.
2. **Consistencia de Estilo:** Cada actualización en español debe reflejarse en la sección en inglés del `README.md`.
3. **Restricción de Infraestructura:** No agregar Docker a la configuración ni a las descripciones técnicas.
