<div align="center">

# Angel Castillo
**Desarrollador Autodidacta · Desktop & Mobile | Tester de Software (CES) | Cursando Máster en Desarrollo con IA**  
*Montevideo, Uruguay*

🌐 [Sitio Web (angel7castillo.github.io)](https://angel7castillo.github.io) &nbsp;·&nbsp; 📱 [Catálogo Tech Service Apps](https://angel7castillo.github.io/apps/) &nbsp;·&nbsp; 📖 [Principios de Ingeniería](./standards/engineering-principles.md) &nbsp;·&nbsp; 🏗️ [Caso de Estudio: Arquitectura Multiplataforma](./case-studies/01-multiplatform-architecture.md) &nbsp;·&nbsp; 📬 [Contacto](mailto:servicios.angelcastillo@gmail.com)

---

</div>

## Sobre mí

Soy un desarrollador de software **autodidacta como regla principal** desde Montevideo, Uruguay. Construyo aplicaciones de escritorio (Windows) y móviles (Android) con dos prioridades innegociables: **que la interfaz responda al instante sin hacerte perder tiempo, y que por dentro la arquitectura sea limpia, privada y verificable**.

En lugar de obligar al usuario a depender de servidores en la nube o lanzar prototipos a ciegas, diseño bajo **5 pilares de ingeniería pragmática**: especificar contratos y reglas del dominio antes de construir (**SDD**), aislar la lógica de negocio de la pantalla visual (**Clean Architecture**), priorizar sistemas **100% Local-First & Zero-Knowledge** (donde los datos viven cifrados en el propio dispositivo del usuario, con `$0` de costo mensual de servidor y opciones honestas de **Pago Único**) y combinar pruebas automatizadas con **ensayos de calidad 100% manuales en dispositivos físicos reales** (aplicando mi formación técnica como Tester de Software en el **CES — Facultad de Ingeniería, UdelaR**).

Mis proyectos principales no son maquetas: son **5 productos reales**, probados, certificados y distribuidos a través de **Google Play Store** y **Microsoft Store** bajo nuestro sello **Tech Service Apps**.

---

## 🛠️ Metodología de Ingeniería y Ciclo de Producto

Cada aplicación que diseño y llevo a producción sigue un ciclo disciplinado de **5 pilares metodológicos**:

1. **Desarrollo Guiado por Especificaciones (Spec-Driven Development — SDD):**
   Ningún sistema se construye a ciegas. Antes de implementar una funcionalidad se documentan formalmente el alcance, las reglas de negocio, los contratos de datos, las fronteras del sistema y los criterios de aceptación verificables.
2. **Arquitectura Limpia y Diseño Modular (Clean Architecture):**
   Separación estricta por capas entre las reglas del dominio y la interfaz de usuario. Este aislamiento permite que un mismo núcleo lógico evolucione de forma mantenible y opere con consistencia tanto en computadoras de escritorio (Windows) como en dispositivos móviles (Android).
3. **Arquitectura Local-First y Privacidad por Diseño (Zero-Knowledge):**
   Prioridad absoluta a la velocidad de respuesta y a la soberanía de los datos del usuario. Las aplicaciones funcionan al 100% sin conexión obligatoria a la nube, resguardando la información sensible en el propio dispositivo y aplicando cifrado de extremo a extremo cuando se requiere sincronización.
4. **Desarrollo Guiado por Pruebas (TDD) y Ensayo Manual en Hardware Físico (QA — CES):**
   Combinación de pruebas automatizadas sobre las reglas críticas de negocio con **ensayos de calidad 100% manuales en dispositivos físicos reales**, aplicando metodología formal de Testing (Centro de Ensayos de Software — CES / UdelaR) para validar flujos, casos borde y usabilidad antes de cada lanzamiento.
5. **Orquestación de Ingeniería Asistida por IA y Entrega Certificada en Tiendas:**
   Integración estructurada de flujos de desarrollo asistidos por inteligencia artificial bajo auditoría humana estricta, llevando cada producto hasta superar los estándares de seguridad, privacidad y certificación de **Google Play Store** y **Microsoft Store**.

---

## 🎓 Formación & Aprendizaje Continuo

* **Autodidacta como regla principal:** Mi motor principal es aprender construyendo. Investigo documentación oficial, diseño arquitecturas modulares y llevo proyectos completos desde cero hasta su certificación y publicación en tiendas.
* **[Máster en Desarrollo con IA con Doble Titulación](https://thebigschool.com/master-desarrollo-con-ia/) — BIG school** *(En curso)*  
  Especialización en desarrollo de software moderno, arquitectura asistida por IA y orquestación estructurada de flujos de ingeniería.
* **Tester de Software — Centro de Ensayos de Software (CES)** *(Montevideo, Uruguay — 2023)*  
  Carrera técnica con el respaldo de la Facultad de Ingeniería (UdelaR) y los programas de Educación Permanente. Esta base formal en QA y ensayo de software define mi forma de trabajar: validar fronteras de entrada, diseñar casos de prueba y asegurar la estabilidad antes de publicar cada versión.

---

## 🚀 Proyectos en Producción (Tiendas Oficiales · Tech Service Apps)

### 1. Billet — Finanzas Personales Multimoneda (`app.billet` · `9MXPKKD2F58R`)
> Aplicación 100% offline-first para gestionar cuentas en 40 divisas con tipos de cambio personalizados, privacidad local y puente criptográfico entre Android y Windows PC.

* **Plataforma:** Android (Google Play) & Windows 10/11 (Microsoft Store)
* **Enfoque Metodológico:** Arquitectura Local-First · Privacidad Zero-Knowledge · Sincronización Criptográfica Offline Móvil ↔ PC
* **Puntos clave de ingeniería:**
  * Enfoque *offline-first*: funciona sin conexión y protege los registros localmente con PIN, biometría y copias de seguridad cifradas en el dispositivo.
  * Puente criptográfico determinístico (`PC-XXXX`) que activa la licencia de Pago Único tanto en el teléfono Android como en la PC Windows sin depender de cuentas ni servidores en la nube.
  * Internacionalización completa en 6 idiomas (`ES`, `EN`, `PT`, `DE`, `FR`, `HI`).
* **Distribución y web oficial:**  
  ![Google Play](https://img.shields.io/badge/Google_Play-Disponible-414141?style=flat-square&logo=googleplay&logoColor=white) ![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Disponible-0078D4?style=flat-square&logo=microsoft&logoColor=white) · 🌐 **[Web Oficial de Billet](https://angel7castillo.github.io/billet/)** · 🔒 [Política de Privacidad](https://angel7castillo.github.io/billet/privacy.html)

---

### 2. Kvota — Presupuestos de Obra y Oficios en PDF A4 (`com.techservice.kvota`)
> Aplicación 100% offline-first para técnicos independientes, electricistas, instaladores y contratistas que genera presupuestos en hoja oficial ISO 216 A4 con membrete, logo y cálculo privado de ganancia neta.

* **Plataforma:** Android (Google Play) & Windows PC
* **Enfoque Metodológico:** Clean Architecture · Aritmética Financiera Exacta en Centavos · Diseño UX Guiado Paso a Paso
* **Puntos clave de ingeniería:**
  * **Doble Vista Inteligente en PDF A4 (`210 × 297 mm`):** permite alternar entre *"Solo Totales"* y *"Detallado por Ítem"* manteniendo 100% privados el costo base, el margen sobre materiales y la ganancia neta del técnico.
  * **Flujo guiado sin fricción (`Paso 0` a `Paso 4`):** membrete con logo desde galería, plantillas rápidas, catálogo separado de materiales y mano de obra, e historial con filtros por estado (`Aceptado`, `Pendiente`, `No aceptado`).
  * **Persistencia local y copias verificadas (`.kvota`):** respaldos locales firmados con suma de verificación criptográfica.
* **Sitio web oficial y privacidad:**  
  ![Google Play](https://img.shields.io/badge/Google_Play-Disponible-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Web Oficial de Kvota](https://angel7castillo.github.io/kvota/)** · 🔒 [Política de Privacidad](https://angel7castillo.github.io/kvota/privacy.html)

---

### 3. Biblioteca Pastoral v2 — Estudio Bíblico, Exégesis Strong y Modo Púlpito (`com.techservice.bibliotecapastoral` · `9N04WK1JQ3L1`)
> Herramienta 100% libre y gratuita para pastores, predicadores y maestros bíblicos que integra redacción de bosquejos homiléticos, Biblia multiversión, Concordancia Strong Hebreo/Griego y Modo Púlpito sin distracciones.

* **Plataforma:** Windows 10/11 (Microsoft Store), Android (Google Play) y Web PWA
* **Enfoque Metodológico:** Clean Architecture · Persistencia Local de Bajo Consumo (`<60 MB` RAM) · Aislamiento Multi-Perfil
* **Puntos clave de ingeniería:**
  * Motor bíblico 100% offline (`RVR1909` + Concordancia Strong `H1–H8674` y `G1–G5624`) con orquestador multiversión y aislamiento estricto de datos por perfil ministerial (*Multi-Tenant Local*).
  * Empaquetado nativo certificado en Microsoft Store y Google Play, disponible en 6 idiomas (`ES`, `EN`, `PT`, `DE`, `FR`, `HI`).
* **Sitio web oficial y tiendas:**  
  ![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Disponible-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Google Play](https://img.shields.io/badge/Google_Play-Disponible-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Sitio Oficial: bibliotecapastoral.org](https://bibliotecapastoral.org)**

---

### 4. NexoTerapia Profesional — Consultorio Clínico Local-First & E2EE (`info.nexoterapia.terapeuta` · `9NB3Q5474Z37`)
> Software clínico para psicólogos, psicoterapeutas y profesionales de salud mental con expedientes cifrados localmente, sincronización Zero-Knowledge entre PC Windows y móvil Android, y puente criptográfico con sus pacientes.

* **Plataforma:** Windows 10/11 (Microsoft Store) & Android Nativo (Google Play)
* **Enfoque Metodológico:** Privacidad por Diseño (Zero-Knowledge) · Cifrado de Extremo a Extremo · Cumplimiento Legal Verificable
* **Puntos clave de ingeniería:**
  * **Bóveda Clínica Zero-Knowledge:** los expedientes, notas de sesión y evolución viven cifrados en el dispositivo del profesional con kit de recuperación `.nexokey`; el servidor de sincronización jamás conoce la llave maestra.
  * **Derecho al Olvido Verificable:** destrucción irreversible de expedientes con emisión de Certificado Legal Criptográfico (Ley 18.331 Uruguay / RGPD Art. 17) e informes clínicos en PDF.
* **Sitio web oficial y tiendas:**  
  ![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Disponible-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Google Play](https://img.shields.io/badge/Google_Play-Disponible-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Sitio Oficial: nexoterapia.info](https://nexoterapia.info)**

---

### 5. NexoTerapia Personal — Acompañamiento del Paciente & Diario Emocional (`info.nexoterapia.paciente`)
> Aplicación móvil de bienestar emocional con doble modalidad adaptativa: Diario Emocional Personal 100% offline y canal clínico vinculado por QR con cifrado de extremo a extremo junto al terapeuta.

* **Plataforma:** Android Nativo (Google Play) & Web PWA iOS (`nexoterapia.info/paciente`)
* **Enfoque Metodológico:** Diseño Adaptativo Centrado en el Usuario · Sobres Criptográficos E2EE · Protección Biométrica Local
* **Puntos clave de ingeniería:**
  * **Doble modalidad sin fricción:** funciona como Diario Emocional independiente (termómetro de 4 momentos del día, micro-hábitos, reportes PDF y bloqueo biométrico) o se vincula gratis mediante código QR con `NexoTerapia Profesional`.
  * **Privacidad de extremo a extremo:** cada registro enviado al profesional viaja dentro de un sobre cifrado en el teléfono que solo la bóveda del terapeuta puede abrir.
* **Sitio web oficial y tienda:**  
  ![Google Play](https://img.shields.io/badge/Google_Play-Disponible-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Sitio Oficial: nexoterapia.info](https://nexoterapia.info)**

---

## 📐 Casos de Estudio & Estándares de Ingeniería

Documentación detallada sobre cómo diseño, estructuro y verifico sistemas de software:

* 🛠️ **[Caso de Estudio 01: Arquitectura de Convergencia Multiplataforma](./case-studies/01-multiplatform-architecture.md)**  
  Diseño de un núcleo de dominio compartido para Web, Escritorio y Móvil, reduciendo el consumo de memoria a `<60 MB` y evitando la duplicación de lógica de negocio.
* 🧪 **[Caso de Estudio 02: Orquestación Sistemática de QA Manual y Pruebas Cerradas en Google Play](./case-studies/02-google-play-closed-testing-workflow.md)**  
  Metodología de ensayo 100% manual en dispositivo Android físico asistida por un organizador local para completar con trazabilidad el ciclo de 14 días de Google Play.
* 📖 **[Manifiesto de Principios y Estándares de Ingeniería](./standards/engineering-principles.md)**  
  Estándares de calidad aplicados en mis proyectos: diseño de contratos previo a construir, ciclo TDD, inmutabilidad y simplicidad estructural.

---

## 📬 Contacto

* **Sitio Web Oficial:** [angel7castillo.github.io](https://angel7castillo.github.io)
* **Catálogo de Aplicaciones:** [angel7castillo.github.io/apps/](https://angel7castillo.github.io/apps/)
* **Email:** [servicios.angelcastillo@gmail.com](mailto:servicios.angelcastillo@gmail.com)
* **GitHub:** [@Angel7Castillo](https://github.com/Angel7Castillo)

<br/>

<hr/>

<br/>

## About Me

I am a **self-taught software developer by core principle** based in Montevideo, Uruguay. I build desktop (Windows) and mobile (Android) applications around two non-negotiable priorities: **interfaces that respond instantly without friction, and clean, verifiable architectures that respect user privacy**.

Instead of forcing cloud accounts for everyday utilities or shipping fragile prototypes, my work relies on **5 pragmatic engineering pillars**: writing formal specifications and data contracts before coding (**SDD**), strictly separating domain logic from visual interfaces (**Clean Architecture**), engineering **100% Local-First & Zero-Knowledge** systems (keeping encrypted records on the user's own device with `$0` monthly server overhead—which enables generous free tiers and honest **One-Time Payment** unlocks), and pairing automated tests with **100% manual QA testing on physical hardware** (backed by my technical training as a Software Tester at **CES — Faculty of Engineering, UdelaR**).

My core projects are not prototypes—they are **5 real products** tested, certified, and distributed through **Google Play Store** and **Microsoft Store** under the **Tech Service Apps** publisher seal.

---

## 🛠️ Engineering Methodology & Product Lifecycle

Every application I design and ship to production follows a disciplined **5-pillar engineering methodology**:

1. **Spec-Driven Development (SDD):**
   No system is built blindly. Scope, business rules, data contracts, system boundaries, and verifiable acceptance criteria are formally specified before implementation begins.
2. **Clean Architecture & Modular Design:**
   Strict layered separation between core domain logic and user interface adapters. This isolation enables a shared business core to evolve cleanly and run consistently across desktop computers (Windows) and mobile devices (Android).
3. **Local-First Architecture & Privacy by Design (Zero-Knowledge):**
   Absolute priority on responsiveness and user data sovereignty. Applications operate 100% offline without mandatory cloud accounts, keeping sensitive records on the user's device and applying end-to-end encryption whenever synchronization is required.
4. **Test-Driven Development (TDD) & Hands-On Physical Hardware QA (CES):**
   Combining automated unit and integration tests on critical domain invariants with **100% manual QA testing on physical hardware**, applying formal software testing methodology (Centro de Ensayos de Software — CES / UdelaR) to validate user flows, edge cases, and release stability.
5. **AI-Assisted Engineering Orchestration & Official Store Certification:**
   Structured integration of AI-assisted engineering workflows under strict human architectural review, taking each product all the way through **Google Play Store** and **Microsoft Store** security, privacy, and certification gates.

---

## 🎓 Education & Continuous Learning

* **Self-Taught by Core Principle:** My primary driver is learning by building—studying official technical documentation, designing modular architectures, and shipping complete products from scratch to official store certification.
* **[Master in AI-Driven Software Development (Dual Degree)](https://thebigschool.com/master-desarrollo-con-ia/) — BIG school** *(In Progress)*  
  Specialization in modern software engineering, systems orchestration, and AI-assisted development workflows.
* **Software Tester — Centro de Ensayos de Software (CES)** *(Montevideo, Uruguay — 2023)*  
  Technical program backed by the Faculty of Engineering (UdelaR). This formal foundation in QA and software testing shapes how I build software: validating input boundaries, designing test cases, and ensuring release stability.

---

## 🚀 Shipped Products (Official Stores · Tech Service Apps)

### 1. Billet — Multi-Currency Personal Finance (`app.billet` · `9MXPKKD2F58R`)
> 100% offline-first application for managing accounts across 40 currencies with custom exchange rates, local privacy, and an offline cryptographic pairing bridge between Android and Windows PC.

* **Platform:** Android (Google Play) & Windows 10/11 (Microsoft Store)
* **Methodological Focus:** Local-First Architecture · Zero-Knowledge Privacy · Offline Mobile-to-PC Cryptographic Pairing
* **Engineering Highlights:**
  * *Offline-first* design: works without internet access, protecting data locally with PIN/biometrics and encrypted `.billet` backups.
  * Deterministic offline cryptographic pairing bridge (`PC-XXXX`) unlocking both Android and Windows PC under a single One-Time Payment license without cloud accounts.
  * Full localization in 6 languages (`ES`, `EN`, `PT`, `DE`, `FR`, `HI`).
* **Official Distribution & Website:**  
  ![Google Play](https://img.shields.io/badge/Google_Play-Available-414141?style=flat-square&logo=googleplay&logoColor=white) ![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Available-0078D4?style=flat-square&logo=microsoft&logoColor=white) · 🌐 **[Billet Official Website](https://angel7castillo.github.io/billet/)** · 🔒 [Privacy Policy](https://angel7castillo.github.io/billet/privacy.html)

---

### 2. Kvota — Trade & Contractor A4 PDF Work Quotes (`com.techservice.kvota`)
> 100% offline-first quoting application for electricians, technicians, installers, and contractors that generates official ISO 216 A4 PDF quotes with custom logo letterhead and private net profit calculation.

* **Platform:** Android (Google Play) & Windows PC
* **Methodological Focus:** Clean Architecture · Exact Integer Cents Financial Arithmetic · Step-by-Step Guided UX
* **Engineering Highlights:**
  * **Smart Dual-View A4 PDF (`210 × 297 mm`):** switch in one tap between *"Summary Only"* and *"Itemized Breakdown"* while keeping material markups and technician net profit 100% private.
  * **Frictionless Guided Flow (`Step 0` to `Step 4`):** company logo letterhead, trade templates, separate materials and labor catalogs, and status/date history filters.
  * **Verified Local Backups (`.kvota`):** signed locally with a cryptographic checksum.
* **Official Website & Privacy:**  
  ![Google Play](https://img.shields.io/badge/Google_Play-Available-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Kvota Official Website](https://angel7castillo.github.io/kvota/)** · 🔒 [Privacy Policy](https://angel7castillo.github.io/kvota/privacy.html)

---

### 3. Biblioteca Pastoral v2 — Biblical Study, Strong's Lexicon & Pulpit Mode (`com.techservice.bibliotecapastoral` · `9N04WK1JQ3L1`)
> 100% free and ad-free software for pastors, preachers, and Bible teachers featuring homiletic outline editing, multi-version Bible comparison, Hebrew/Greek Strong's Concordance, and distraction-free Pulpit Mode.

* **Platform:** Windows 10/11 (Microsoft Store), Android (Google Play) & Web PWA
* **Methodological Focus:** Clean Architecture · Low-Footprint Local Persistence (`<60 MB` RAM) · Multi-Profile Isolation
* **Engineering Highlights:**
  * 100% offline biblical engine (`RVR1909` + Strong's Concordance `H1–H8674` & `G1–G5624`) with multi-version caching and strict local multi-profile isolation.
  * Certified Microsoft Store and Google Play packages localized in 6 languages.
* **Official Website & Stores:**  
  ![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Available-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Google Play](https://img.shields.io/badge/Google_Play-Available-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Official Website: bibliotecapastoral.org](https://bibliotecapastoral.org)**

---

### 4. NexoTerapia Profesional — Local-First E2EE Clinical Practice Suite (`info.nexoterapia.terapeuta` · `9NB3Q5474Z37`)
> Clinical management software for psychologists, psychotherapists, and mental health professionals featuring locally encrypted records, Zero-Knowledge Windows-to-Android vault synchronization, and E2EE patient pairing.

* **Platform:** Windows 10/11 (Microsoft Store) & Native Android (Google Play)
* **Methodological Focus:** Privacy by Design (Zero-Knowledge) · End-to-End Encryption · Verifiable Regulatory Compliance
* **Engineering Highlights:**
  * **Zero-Knowledge Clinical Vault:** patient records and session notes live encrypted on-device with a `.nexokey` recovery kit; the sync relay never sees the master key.
  * **Verifiable Right to Erasure:** irreversible record destruction issuing a Cryptographic Legal Certificate (GDPR Art. 17 / Uruguay Law 18.331) plus clinical evolution PDF reports.
* **Official Website & Stores:**  
  ![Microsoft Store](https://img.shields.io/badge/Microsoft_Store-Available-0078D4?style=flat-square&logo=microsoft&logoColor=white) ![Google Play](https://img.shields.io/badge/Google_Play-Available-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Official Website: nexoterapia.info](https://nexoterapia.info)**

---

### 5. NexoTerapia Personal — Patient Companion & Emotional Journal (`info.nexoterapia.paciente`)
> Adaptive emotional well-being application operating both as a 100% offline personal emotional journal and as a free QR-linked E2EE clinical companion paired with the user's therapist.

* **Platform:** Native Android (Google Play) & iOS/Web PWA (`nexoterapia.info/paciente`)
* **Methodological Focus:** User-Centered Adaptive Design · E2EE Cryptographic Envelopes · Local Biometric Protection
* **Engineering Highlights:**
  * **Adaptive Dual Mode:** works standalone as a private 4-moment daily emotional thermometer and habit tracker with PDF reports, or pairs via QR with `NexoTerapia Profesional`.
  * **End-to-End Encrypted Relay:** entries shared with a therapist are sealed on-device inside encrypted envelopes that only the therapist's vault can decrypt.
* **Official Website & Store:**  
  ![Google Play](https://img.shields.io/badge/Google_Play-Available-414141?style=flat-square&logo=googleplay&logoColor=white) · 🌐 **[Official Website: nexoterapia.info](https://nexoterapia.info)**

---

## 📐 Architecture Case Studies & Engineering Standards

Technical documentation detailing how I design, structure, and verify software systems:

* 🛠️ **[Case Study 01: Multiplatform Convergence Architecture](./case-studies/01-multiplatform-architecture.md)**  
  System design for a shared domain core across Web, Desktop, and Mobile, cutting desktop memory footprint to `<60 MB` and eliminating duplicated business logic.
* 🧪 **[Case Study 02: Systematic Manual QA & Closed Testing Orchestration (Google Play 12 Testers / 14 Days)](./case-studies/02-google-play-closed-testing-workflow.md)**  
  Hands-on manual QA workflow on a physical Android device supported by a local 14-day queue tracker for peer testing retention.
* 📖 **[Engineering Principles & Quality Standards](./standards/engineering-principles.md)**  
  Core tenets applied across projects: contract-first design, TDD verification loops, immutability, and structural simplicity.

---

## 📬 Get in Touch

* **Official Website:** [angel7castillo.github.io](https://angel7castillo.github.io)
* **Apps Catalog:** [angel7castillo.github.io/apps/](https://angel7castillo.github.io/apps/)
* **Email:** [servicios.angelcastillo@gmail.com](mailto:servicios.angelcastillo@gmail.com)
* **GitHub:** [@Angel7Castillo](https://github.com/Angel7Castillo)
