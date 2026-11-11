# AGENTS.md — Reglas y Orquestación para el Repositorio de Marca Profesional

> **Repositorio:** `Angel7Castillo/Angel7Castillo` (Perfil Especial de GitHub)  
> **Titular:** Angel Castillo  
> **Objetivo:** Gestión y evolución de la imagen técnica profesional, presentación de productos terminados en tiendas oficiales (Google Play y Microsoft Store) y documentación de casos de estudio de ingeniería sin revelar propiedad intelectual ni violar acuerdos de confidencialidad (NDA).

---

## 1. Principios Mandatorios del Repositorio

1. **Privacidad y NDA Absoluto:**
   * Jamás incluir código fuente de aplicaciones comerciales (`billet`, proyectos de Vitro, etc.) ni claves de API o secretos.
   * El código comercial reside exclusivamente en repositorios privados.
   * Aquí solo residen: portadas (`README.md`), especificaciones (`spec.md`), estándares (`standards/`), casos de estudio arquitectónicos despersonalizados (`case-studies/`) y guías operativas (`docs/`).

2. **Cero Docker:**
   * Por preferencia explícita del titular, no se utiliza ni se referencia Docker en este perfil.
   * El enfoque de despliegue y empaquetado es nativo (tiendas oficiales, Nginx, empaquetado de plataforma).

3. **Tono y Comunicación:**
   * Tono 100% humano, sobrio y pragmático.
   * Prohibidos clichés de IA (*"apasionado por transformar el mundo digital"*, listas infladas de 40 tecnologías).
   * Enfoque en hechos comprobables: aplicaciones terminadas descargables en tiendas oficiales y rigor metodológico (TypeScript estricto, planificación previa, Clean Architecture).

4. **Soporte Bilingüe:**
   * El `README.md` debe mantenerse en **Español 🇪🇸** e **Inglés 🇬🇧** con enlaces de navegación limpios.
   * El título en español es estrictamente `## Sobre mí` (sin prefijos redundantes).

---

## 2. Estructura de Directorios

```text
├── README.md                      # Portada pública del perfil visible en github.com/Angel7Castillo
├── AGENTS.md                      # Este manual de contexto y reglas para agentes
├── spec.md                        # Especificación funcional viva del repositorio
├── .gitignore                     # Filtros de git
├── standards/
│   └── engineering-principles.md  # Manifiesto de calidad, tipado y arquitectura
├── case-studies/
│   └── 01-multiplatform-architecture.md # Caso de estudio: Arquitectura multiplataforma (Web/Tauri/Capacitor)
└── docs/
    ├── GUIDE.md                   # Manual de operaciones y plantillas para nuevos proyectos
    └── ROADMAP.md                 # Registro de fases, mejoras y siguientes pasos
```

---

## 3. Protocolos de Modificación y Entrega

### Al agregar un nuevo proyecto a la portada:
1. Seguir la plantilla bilingüe definida en [`docs/GUIDE.md`](file:///c:/Users/Angel/Documents/Proyectos/GITHUB%20desarrollador%20Angel/docs/GUIDE.md).
2. Verificar que incluya enlace a tienda oficial, plataforma y 3 puntos clave de ingeniería.
3. Actualizar la versión en español y la versión en inglés en [`README.md`](file:///c:/Users/Angel/Documents/Proyectos/GITHUB%20desarrollador%20Angel/README.md).

### Al redactar un nuevo caso de estudio:
1. Crear el archivo en `case-studies/0X-nombre-descriptivo.md`.
2. Estructurar bajo el método: *Desafío $\rightarrow$ Solución Arquitectónica $\rightarrow$ Resultados & Métricas $\rightarrow$ Conclusión*.
3. Enlazarlo en [`README.md`](file:///c:/Users/Angel/Documents/Proyectos/GITHUB%20desarrollador%20Angel/README.md) y en [`spec.md`](file:///c:/Users/Angel/Documents/Proyectos/GITHUB%20desarrollador%20Angel/spec.md).

---

## 4. Comandos de Sincronización

```powershell
# Estado y cambios
git status

# Commit con formato Conventional Commits
git commit -am "docs: <descripción del cambio>"

# Push seguro a GitHub
git push origin main
```
