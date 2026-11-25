# Case Study 02: Systematic Manual QA & Closed Testing Orchestration (Google Play 12 Testers / 14 Days)

> **Type:** QA Engineering, Release Operations & Developer Workflow  
> **Focus:** Hands-on Manual Verification on Physical Hardware, 14-Day Retention Tracking & Peer Testing Methodology  
> **Author:** Angel Castillo (`@Angel7Castillo` | `u/Angel07Castillo`)

[ 🇪🇸 Versión en Español ](#-caso-de-estudio-02-orquestación-sistemática-de-qa-manual-y-pruebas-cerradas-en-google-play-12-testers--14-días) &nbsp;|&nbsp; [ 🇬🇧 English Version ](#-1-the-challenge)

---

## 1. The Challenge

Since November 2023, Google Play requires personal developer accounts to complete a mandatory **Closed Testing phase with at least 12 opted-in testers continuously engaged for 14 days** before unlocking Production access.

When shipping mobile applications, treating this requirement as an unstructured daily task creates three operational bottlenecks:
1. **High Phone-to-PC Friction:** Manually opening links on a phone, taking screenshots, transferring files back to a computer, and replying across threads takes hours away from actual product engineering.
2. **Day-2 Retention Drop-off ("Tester Ghosting"):** In community Test-for-Test exchanges, relying on memory or scattered notes leads to forgotten daily app sessions, causing 14-day counters to stall.
3. **Lack of Verifiable QA Feedback:** Google Play evaluates genuine human testing and iterative releases (`.aab` updates). Emulators or automated bots violate policies and fail to catch real-world usability issues.

---

## 2. How We Solved It: Manual QA on Physical Hardware + A Structured 15-Minute Organizer

Drawing on formal Software Testing foundations (**Centro de Ensayos de Software — CES / UdelaR**), we separated the process into two clear responsibilities: **100% human, hands-on testing on a physical Android phone**, supported by a **lightweight local organizer and USB/ADB bridge** that eliminates administrative friction.

```text
┌─────────────────────────────────────────────────────────────────┐
│             DESKTOP CONTROL & TRACKING LAYER (PC)               │
│   Google Group Onboarding · Web Opt-In · 14-Day Queue Tracker   │
└───────────────────────────────┬─────────────────────────────────┘
                                │ USB / ADB Bridge (Evidence Sync)
                                ▼
┌─────────────────────────────────────────────────────────────────┐
│          PHYSICAL ANDROID DEVICE (Manual Human Testing)         │
│  1. Direct Play Store View for Native Installation              │
│  2. Hands-on Manual Navigation, UX Review & Edge-Case Testing   │
│  3. Instant Screenshot Transfer to Local Audit Log              │
└─────────────────────────────────────────────────────────────────┘
```

### 2.1 Frictionless Onboarding via Google Groups
Instead of closed email lists that require manual console updates and slow propagation, our closed testing tracks use open **Google Groups**. Any fellow developer can join the group, accept the web opt-in, and install the build from Google Play in under 15 seconds.

### 2.2 Hands-On Manual Testing Assisted by a Local Queue
To make testing 15–20 peer apps sustainable in 15 minutes every afternoon without losing quality:
* **Human Verification First:** Every peer application is installed and **tested manually by me on a physical Android device**—navigating screens, testing inputs, and checking UI responsiveness.
* **Zero File-Transfer Friction:** Instead of emailing or messaging screenshots from the phone to the PC, a local USB/ADB bridge transfers the real screen capture directly to the desktop workspace while updating the 14-day checklist (`Day X / 14`).
* **Early Configuration Diagnostics:** When a fellow developer forgets to enable all countries/regions in Google Play Console or misconfigures their Google Group, we capture the exact Play Store state on the phone and report it immediately so they can fix their release without losing days.
* **Continuous Release Iteration:** Throughout the 14-day cycle, we ship incremental `.aab` updates to Google Play addressing real usability feedback gathered during testing.

---

## 3. Join Our Closed Testing Ring (Billet — Personal Finance)

We test fellow developers' apps every afternoon and welcome mutual testers for **Billet**, our **offline-first personal finance & expense tracker** for Android (no mandatory cloud accounts, instant startup, local data privacy):

1. **Google Group:** [https://groups.google.com/g/billet-testers](https://groups.google.com/g/billet-testers)
2. **Web Opt-in:** [https://play.google.com/apps/testing/app.billet](https://play.google.com/apps/testing/app.billet)
3. **Google Play Store:** [https://play.google.com/store/apps/details?id=app.billet](https://play.google.com/store/apps/details?id=app.billet)

<br/>

<hr/>

<br/>

# 🇪🇸 Caso de Estudio 02: Orquestación Sistemática de QA Manual y Pruebas Cerradas en Google Play (12 Testers / 14 Días)

> **Tipo:** Ingeniería de QA, Operaciones de Lanzamiento y Flujo de Trabajo  
> **Enfoque:** Ensayo Manual en Dispositivo Físico, Seguimiento Estructurado de 14 Días y Pruebas Mutuas  
> **Autor:** Angel Castillo (`@Angel7Castillo` | `u/Angel07Castillo`)

---

## 1. El Desafío

Para las cuentas personales de Google Play Console, el requisito de **al menos 12 testers activos durante 14 días continuos en Prueba Cerrada** suele convertirse en un cuello de botella operativo para desarrolladores independientes:
1. **Fricción entre Teléfono y PC:** Abrir enlaces manualmente en el celular, sacar capturas, pasarlas a la computadora y responder hilos consume horas que deberían dedicarse a programar.
2. **Pérdida de Constancia al Día 2:** Sin un registro ordenado, es fácil olvidar qué aplicaciones de otros colegas toca probar cada tarde durante las dos semanas.
3. **Calidad Real vs. Atajos:** Google Play busca pruebas humanas reales e iteraciones de código (`.aab`). Los emuladores o bots no sirven ni aportan valor real al producto.

---

## 2. Cómo lo Resolvimos: Pruebas 100% Manuales en Teléfono Físico + Organizador Local de 15 Minutos

Aplicando nuestra base técnica como **Tester de Software (CES — Facultad de Ingeniería UdelaR)** desde Montevideo, Uruguay, estructuramos una metodología donde **las aplicaciones las pruebo yo mismo de forma manual en mi teléfono físico**, apoyado por un organizador local en PC conectado por USB/ADB que elimina el trabajo administrativo repetitivo:

* **Adhesión Ágil con Google Groups:** Vinculamos la pista cerrada a un Google Group abierto para que cualquier colega pueda unirse y descargar la app desde Google Play en segundos, sin esperar cargas manuales de correos.
* **Ensayo Manual Real en Hardware Físico:** Cada tarde pruebo personalmente las aplicaciones comprometidas en mi teléfono Android real, revisando flujos de interfaz, tiempos de respuesta y casos borde.
* **Puente USB/ADB para Evidencia Instantánea:** En lugar de perder tiempo enviando capturas del celular a la PC por mensajería o nube, el puente local toma la captura real de la pantalla del teléfono, la guarda ordenada por fecha y actualiza el contador del día (`Día X / 14`) para que ningún colega quede olvidado a mitad del proceso.
* **Detección Temprana de Bloqueos de Tienda:** Si la aplicación de un colega tiene restricciones de país en Play Console o permisos pendientes en su grupo, le compartimos la captura del diagnóstico en el acto para que pueda corregirlo sin perder días de prueba.
* **Iteración Continua en Play Console:** Durante los 14 días publicamos nuevas versiones (`.aab`) aplicando mejoras de usabilidad detectadas durante las pruebas.

---

## 3. Súmate a la Prueba Cerrada de Billet (Intercambio de Pruebas)

Si estás desarrollando para Android y buscas un intercambio de pruebas serio, manual y constante durante los 14 días (o quieres conocer **Billet**, nuestra aplicación *offline-first* de finanzas personales y control de gastos ya disponible en fase beta en Google Play):

1. **Google Group:** [https://groups.google.com/g/billet-testers](https://groups.google.com/g/billet-testers)
2. **Opt-in Web:** [https://play.google.com/apps/testing/app.billet](https://play.google.com/apps/testing/app.billet)
3. **Google Play Store:** [https://play.google.com/store/apps/details?id=app.billet](https://play.google.com/store/apps/details?id=app.billet)
