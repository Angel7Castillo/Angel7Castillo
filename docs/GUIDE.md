# Guía de Gestión y Crecimiento del Perfil Profesional

> **Propósito:** Este documento sirve como manual interno para mantener, actualizar y expandir la imagen profesional y el portafolio técnico de **Angel Castillo**, protegiendo siempre la propiedad intelectual y los acuerdos de confidencialidad (NDA).

---

## 1. Estructura del Proyecto

```text
├── README.md                      # Portada pública bilingüe visible en github.com/Angel7Castillo
├── .gitignore                     # Exclusiones de control de versiones
├── standards/
│   └── engineering-principles.md  # Manifiesto de buenas prácticas y estándares de ingeniería
├── case-studies/
│   └── 01-multiplatform-architecture.md # Caso de estudio: Arquitectura multiplataforma (Web/Tauri/Capacitor)
└── docs/
    ├── GUIDE.md                   # Este manual de operaciones y protocolos
    └── ROADMAP.md                 # Registro de futuras mejoras, portfolio web y siguientes casos de estudio
```

---

## 2. Protocolo de Privacidad y Confidencialidad (Regla de Oro)

Para proteger clientes (como Vitro) y tus propios productos comerciales:

| Qué se mantiene PRIVADO 🔒 | Qué se hace PÚBLICO 👁️ |
| :--- | :--- |
| Código fuente de tus aplicaciones de negocio (`billet`, etc.). | Enlaces a tiendas oficiales (Microsoft Store, Google Play). |
| Bases de datos, modelos de datos propietarios y esquemas internos. | Diagramas de arquitectura conceptuales y de alto nivel. |
| Claves de API, credenciales y archivos `.env`. | Decisiones de ingeniería abstractas (Trade-offs, TDD, Docker). |
| Nombres de clientes corporativos protegidos por NDA. | Desafíos técnicos despersonalizados (Problema $\rightarrow$ Solución $\rightarrow$ Métricas). |

---

## 3. Cómo Agregar un Nuevo Proyecto a la Vitrina

Cada vez que lances o quieras destacar un nuevo producto terminado, se agrega a la sección **"Proyectos en Producción"** del `README.md` siguiendo este formato estructurado:

### Plantilla en Español
```markdown
### [Número]. [Nombre del Proyecto] — [Subtítulo descriptivo de 1 línea]
> [Breve descripción de qué resuelve la aplicación y a quién ayuda].

* **Plataforma:** [Android / Windows / Web / Multiplataforma]
* **Puntos clave de ingeniería:**
  * [Aspecto técnico 1: ej. Offline-first, cifrado local, bajo consumo de memoria]
  * [Aspecto técnico 2: ej. Arquitectura modular en TypeScript, navegación táctil fluida]
  * [Aspecto técnico 3: ej. Empaquetado nativo o certificación en tienda]
* **Descarga oficial:**
  [![Badge Tienda](https://img.shields.io/badge/...)] [Enlace a tienda o landing]
```

### Plantilla en Inglés
```markdown
### [Number]. [Project Name] — [One-line descriptive subtitle]
> [Brief description of what problem the application solves].

* **Platform:** [Android / Windows / Web / Cross-Platform]
* **Engineering Highlights:**
  * [Highlight 1: Offline-first, local encryption, minimal memory footprint]
  * [Highlight 2: Modular TypeScript architecture, responsive touch navigation]
  * [Highlight 3: Native packaging or store certification]
* **Official Store:**
  [![Store Badge](https://img.shields.io/badge/...)] [Store or landing link]
```

---

## 4. Cómo Documentar un Nuevo Caso de Estudio

Los casos de estudio se guardan en la carpeta `case-studies/` (ej. `02-performance-optimization.md`). Deben responder a 4 preguntas sin revelar código sensible:
1. **El Desafío (The Challenge):** ¿Qué problema de ingeniería existía? (latencia, sincronización, despliegues lentos).
2. **La Solución Arquitectónica (Architectural Solution):** Diagrama y decisiones técnicas tomadas.
3. **Métricas de Impacto (Impact & Results):** Tiempos antes vs. después, reducción de consumo de memoria o porcentaje de código reutilizado.
4. **Lección Aprendida (Key Takeaway):** El principio de ingeniería aplicado.

---

## 5. Comandos Rápidos de Sincronización con GitHub

Para guardar y subir cambios a tu perfil:

```powershell
# 1. Ver qué archivos se modificaron
git status

# 2. Agregar los cambios
git add .

# 3. Guardar el commit con mensaje claro
git commit -m "docs: actualizar proyectos en perfil"

# 4. Subir a GitHub
git push origin main
```
