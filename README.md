# AI Website & Product Builder with Agents

Plataforma SaaS para transformar ideas, negocios y necesidades en sitios web, aplicaciones y productos digitales funcionales mediante agentes de inteligencia artificial.

---

## 1. Resumen del proyecto

**AI Website & Product Builder with Agents** es una plataforma web SaaS inspirada en experiencias tipo **mgx.dev / Atoms**, diseñada para que un usuario pueda describir una idea, negocio, servicio o producto y obtener automáticamente una solución digital inicial lista para evolucionar.

La plataforma no debe limitarse a generar una simple web corporativa. Debe ser capaz de crear desde páginas de negocio y landings de alta conversión hasta aplicaciones ligeras, herramientas internas, portales y productos digitales con estructura real.

El núcleo del sistema se basa en un equipo de agentes especializados de IA que colaboran para:
- investigar el caso de uso,
- definir la mejor estructura,
- planificar la experiencia,
- redactar el contenido,
- proponer la identidad visual,
- construir componentes editables,
- y ensamblar un resultado usable, navegable y preparado para seguir iterando.

La visión del producto es ofrecer una experiencia donde el usuario pueda pasar de una idea a un producto digital funcional en muy poco tiempo, con una interfaz visual, una lógica modular y una arquitectura escalable.

---

## 2. Problema que resuelve

Actualmente, crear una web profesional implica al menos una de estas dificultades:

- Contratar a diseñadores, copywriters y desarrolladores.
- Invertir muchas horas en herramientas complejas.
- Tener conocimientos técnicos de estructura web, UX, SEO y diseño.
- Enfrentarse a plantillas genéricas que no reflejan bien el negocio.
- Perder tiempo decidiendo qué páginas crear, qué textos escribir y cómo organizar la información.

Esta plataforma resuelve ese problema permitiendo que el usuario describa su negocio y reciba una web generada automáticamente, con lógica estratégica, estructura adecuada y capacidad de edición posterior.

---

## 3. Propuesta de valor

La propuesta de valor principal es:

> **“Convierte una idea en una web, app o producto digital funcional con un equipo de agentes IA que investiga, planifica, diseña, redacta y construye por ti.”**

### Diferenciadores clave

- Generación basada en **múltiples agentes especializados**, no en una única respuesta genérica.
- Capacidad de construir no solo webs, sino también **productos digitales y apps ligeras**.
- Enfoque orientado a **lanzar soluciones útiles**, no solo maquetas visuales.
- **Editor visual** para iterar y refinar el resultado.
- Posibilidad de evolucionar hacia una experiencia con backend, lógica, datos, autenticación e integraciones.
- Plataforma pensada para crear productos con potencial de validación, captación y monetización.

---

## 4. Usuario objetivo

### Usuario principal
Pequeños negocios, autónomos, profesionales, freelancers y emprendedores que necesitan una web profesional sin depender de procesos largos o costosos.

### Perfiles objetivo
- Psicólogos
- Consultores
- Abogados
- Diseñadores
- Negocios locales
- Agencias pequeñas
- Coaches
- Restaurantes
- Servicios del hogar
- Ecommerce simple o catálogo de servicios
- Profesionales con portfolio

### Necesidades del usuario
- Tener una web rápidamente
- Que se vea profesional
- No partir de cero
- Recibir ayuda con textos y estructura
- Poder editar después sin depender de un desarrollador

---

## 5. Objetivos del producto

### Objetivo principal
Permitir que cualquier usuario cree una web funcional, coherente y visualmente atractiva a partir de un briefing guiado.

### Objetivos secundarios
- Reducir el tiempo de creación de una web.
- Mejorar la calidad de la estructura y del copy generado.
- Simplificar la toma de decisiones del usuario.
- Ofrecer un flujo fácil para personas no técnicas.
- Crear una base tecnológica escalable para convertir el producto en un SaaS sólido.

---

## 6. Alcance inicial del producto

La primera versión del producto debe ser capaz de:

- Guiar al usuario con un onboarding estructurado.
- Recoger los datos esenciales del negocio.
- Orquestar varios agentes de IA especializados.
- Generar una primera versión de la web.
- Mostrar una preview navegable.
- Permitir edición básica de textos y secciones.
- Guardar el proyecto generado.

No es objetivo del MVP resolver desde el principio:
- un sistema visual ultra avanzado tipo Webflow,
- colaboración multiusuario en tiempo real,
- marketplace de templates,
- CMS completo de blog avanzado,
- publicación distribuida compleja en múltiples entornos.

---

## 7. Visión del producto

El producto debe sentirse como un **constructor inteligente de productos digitales**, no como un simple editor de páginas.

Debe permitir que cualquier usuario describa una idea en lenguaje natural y que el sistema lo acompañe hasta obtener un resultado real, usable y editable.

### Principios del producto
- **De idea a producto**: pasar del concepto a una solución digital inicial en minutos.
- **Multiagente**: cada parte del trabajo debe estar resuelta por agentes con roles claros.
- **Resultado real**: el sistema debe generar experiencias funcionales, no solo diseños bonitos.
- **Control humano**: la IA propone, el usuario decide, corrige y mejora.
- **Velocidad de lanzamiento**: reducir fricción y tiempo de ejecución.
- **Escalabilidad**: preparado para evolucionar a una plataforma SaaS robusta.
- **Negocio primero**: el resultado debe ayudar a validar, captar usuarios o generar ingresos.
---

## 8. Funcionamiento general

### Flujo general
1. El usuario accede a la plataforma.
2. Completa un onboarding guiado.
3. El sistema recoge información del negocio.
4. Se lanza la orquestación multiagente.
5. Los agentes generan:
   - estructura del sitio,
   - páginas recomendadas,
   - secciones,
   - textos,
   - branding básico,
   - layout inicial,
   - componentes renderizables.
6. El sistema ensambla una primera versión navegable.
7. El usuario visualiza el resultado.
8. El usuario puede editar, regenerar o ampliar la web.
9. El proyecto queda guardado para seguir trabajando.
10. En fases posteriores podrá publicarlo con dominio propio.

---

## 9. Sistema multiagente

El núcleo del producto se basa en varios agentes especializados. Cada uno resuelve una parte concreta del problema.

### 9.1 Agente Estratega
**Rol:** definir la estrategia de contenido y la arquitectura del sitio.

**Responsabilidades:**
- Interpretar el objetivo del negocio.
- Detectar el tipo de web más conveniente.
- Definir páginas necesarias.
- Proponer jerarquía de navegación.
- Priorizar secciones según intención del usuario.

**Inputs:**
- tipo de negocio,
- servicios,
- audiencia,
- objetivo de la web,
- idioma,
- tono de marca.

**Outputs:**
- sitemap inicial,
- recomendación de páginas,
- estructura de navegación,
- definición de objetivos por página.

---

### 9.2 Agente UX/UI
**Rol:** convertir la estrategia en una experiencia web clara y usable.

**Responsabilidades:**
- Definir layout de cada página.
- Organizar jerarquía visual.
- Ordenar secciones.
- Mejorar legibilidad y experiencia de navegación.
- Proponer patrones de interfaz consistentes.

**Inputs:**
- sitemap,
- tipo de negocio,
- estilo visual deseado,
- prioridades de contenido.

**Outputs:**
- estructura visual por página,
- definición de bloques,
- orden de secciones,
- recomendaciones de interfaz.

---

### 9.3 Agente Copywriter
**Rol:** redactar textos persuasivos, claros y adaptados al negocio.

**Responsabilidades:**
- Crear titulares y subtítulos.
- Redactar descripciones de servicios.
- Generar CTAs.
- Mantener coherencia tonal.
- Adaptar el copy al perfil del cliente objetivo.

**Inputs:**
- briefing del negocio,
- estilo y tono,
- páginas definidas,
- objetivos de conversión.

**Outputs:**
- copy por sección,
- claims principales,
- CTA por página,
- textos de apoyo.

---

### 9.4 Agente SEO
**Rol:** aplicar una capa de SEO on-page básico desde la generación inicial.

**Responsabilidades:**
- Optimizar títulos y headings.
- Proponer keywords base.
- Mejorar semántica de contenidos.
- Definir metadatos básicos.
- Revisar estructura de encabezados.

**Inputs:**
- negocio,
- sector,
- ubicación si aplica,
- páginas generadas,
- copy base.

**Outputs:**
- títulos SEO base,
- meta descriptions iniciales,
- headings sugeridos,
- recomendaciones semánticas.

---

### 9.5 Agente Branding / Estilo Visual
**Rol:** traducir la identidad deseada a una dirección visual coherente.

**Responsabilidades:**
- Sugerir paleta de color.
- Proponer tipografías.
- Definir estilo visual general.
- Adaptar la estética al perfil del negocio.

**Inputs:**
- tipo de negocio,
- preferencias visuales,
- tono de comunicación,
- referencias de estilo si existen.

**Outputs:**
- tokens visuales iniciales,
- paleta,
- tipografías,
- estilo UI sugerido,
- reglas visuales base.

---

## 9. Sistema multiagente

### 9.1 Agente Researcher
Investiga el contexto del proyecto, detecta oportunidades, necesidades, patrones del mercado y enfoques recomendables.

### 9.2 Agente Strategist
Define la estructura ideal del producto, el objetivo principal, la lógica general y el tipo de solución más adecuada.

### 9.3 Agente Product Manager
Convierte la idea en un alcance realista, prioriza funcionalidades y simplifica el producto para que sea usable y viable.

### 9.4 Agente UX/UI Designer
Define la jerarquía visual, layout, bloques, experiencia de navegación e interacción.

### 9.5 Agente Copywriter
Redacta titulares, propuestas de valor, textos de secciones, CTAs y contenido orientado a conversión.

### 9.6 Agente SEO Specialist
Optimiza semántica, headings, títulos, estructura indexable y base SEO del proyecto.

### 9.7 Agente Engineer / Builder
Convierte la planificación en componentes editables, estructura renderizable y base técnica funcional.

### 9.8 Agente Architect
Garantiza que la solución tenga una arquitectura coherente, modular y escalable.
---

## 10. Relación entre agentes

La orquestación inicial puede seguir este flujo:

1. **Estratega** define la arquitectura del sitio.
2. **UX/UI** organiza la experiencia y la estructura visual.
3. **Branding** propone la identidad visual base.
4. **Copywriter** redacta el contenido por página y sección.
5. **SEO** optimiza la estructura semántica y los metadatos.
6. **Técnico/Compositor** unifica todo en un formato renderizable.

Este modelo puede evolucionar hacia una orquestación más dinámica, pero para el MVP se prioriza una cadena clara y controlable.

---

## 11. Funcionalidades principales

### 11.1 Onboarding inteligente
Formulario guiado para recoger:
- tipo de proyecto,
- nombre del producto o negocio,
- problema que resuelve,
- usuario objetivo,
- funcionalidades deseadas,
- objetivo principal,
- tono y estilo,
- idioma,
- referencias visuales,
- nivel de complejidad esperado.

### 11.2 Generación de productos digitales
La plataforma debe poder generar:
- webs corporativas,
- landing pages,
- portfolios,
- directorios,
- microsaas,
- herramientas internas,
- dashboards simples,
- apps de captación,
- portales de negocio,
- productos digitales ligeros.

### 11.3 Sistema multiagente
Equipo de agentes con roles como:
- Researcher
- Strategist
- Product Manager
- UX/UI Designer
- Copywriter
- SEO Specialist
- Engineer / Builder
- Technical Architect

### 11.4 Editor visual
Permitir:
- editar textos,
- mover bloques,
- cambiar estilos,
- regenerar secciones,
- añadir nuevas páginas,
- ajustar componentes,
- revisar estructura.

### 11.5 Generación de estructura funcional
El sistema debe ser capaz de producir:
- páginas,
- navegación,
- secciones,
- componentes,
- flujos básicos,
- datos de configuración,
- base para futuras integraciones o backend.

### 11.6 Preview y validación
- vista previa navegable,
- revisión de estructura,
- comprobación de coherencia visual,
- revisión del enfoque de negocio.

### 11.7 Guardado de proyectos
Persistencia de:
- briefing,
- decisiones del sistema,
- arquitectura generada,
- páginas,
- componentes,
- configuración visual,
- historial de regeneración.

### 11.8 Evolución futura
- autenticación,
- base de datos,
- backend integrado,
- integraciones,
- publicación,
- dominios personalizados,
- exportación de código o sincronización futura.

---

## 12. Flujo de usuario

### Flujo principal del MVP
1. Registro o acceso.
2. Crear nuevo proyecto.
3. Completar onboarding.
4. Revisar resumen del briefing.
5. Lanzar generación.
6. Ver resultado inicial.
7. Editar textos y bloques.
8. Guardar el proyecto.

### Flujo ideal a futuro
1. Crear proyecto.
2. Elegir nivel de guía o automatización.
3. Generación inicial.
4. Feedback del usuario.
5. Regeneración asistida.
6. Ajustes visuales.
7. Publicación.
8. Dominio personalizado.
9. Analítica y mejoras continuas.

---

## 13. Arquitectura funcional

### 13.1 Frontend
Responsable de:
- onboarding,
- dashboard,
- editor visual,
- preview,
- gestión de proyectos,
- autenticación y experiencia de usuario.

### 13.2 Backend
Responsable de:
- lógica de negocio,
- gestión de proyectos,
- orquestación multiagente,
- persistencia,
- control de usuarios,
- integraciones externas.

### 13.3 Motor de orquestación de agentes
Capa encargada de:
- secuenciar agentes,
- enviar inputs adecuados,
- validar outputs,
- ensamblar resultados,
- gestionar reintentos o regeneraciones.

### 13.4 Base de datos
Almacena:
- usuarios,
- proyectos,
- briefings,
- páginas,
- componentes,
- resultados generados,
- historial básico.

### 13.5 Sistema de almacenamiento
Para:
- assets subidos,
- imágenes,
- logos,
- configuraciones exportables,
- snapshots del proyecto.

### 13.6 Sistema de renderizado
Transforma estructuras guardadas en páginas web navegables dentro del editor o preview.

---

## 14. Stack técnico recomendado

## Frontend
- **Next.js**
- **React**
- **TypeScript**
- **Tailwind CSS**
- **shadcn/ui** o librería equivalente para acelerar UI consistente

### Motivos
- Excelente experiencia de desarrollo
- Routing moderno
- SSR/ISR si hiciera falta
- Muy buen ecosistema para SaaS y paneles

## Backend
- **Next.js API / Route Handlers** para una primera fase, o
- **NestJS** si se busca una separación backend más robusta desde el inicio

### Recomendación inicial
Para MVP, empezar con **Next.js full-stack** puede acelerar mucho el desarrollo.

## Base de datos
- **PostgreSQL**

## ORM
- **Prisma**

## Autenticación
- **Auth.js** o solución equivalente
- Opcionalmente Clerk o Supabase Auth según velocidad de implementación

## Almacenamiento
- **Supabase Storage**, **AWS S3** o equivalente

## Orquestación IA
- Servicio propio de orquestación en backend
- Integración con modelos LLM vía proveedor compatible
- Estructuras intermedias en JSON para asegurar outputs consistentes

## Infraestructura
- **Vercel** para frontend/full-stack rápido en MVP
- Base de datos gestionada tipo **Neon**, **Supabase** o **Railway**
- Evolución futura a una arquitectura más desacoplada si el producto escala

---

## 15. Estructura técnica sugerida del proyecto

```bash
/apps
  /web
    /src
      /app
      /components
      /features
      /lib
      /styles

/packages
  /ui
  /types
  /config
  /prompts
  /agent-core

/services
  /orchestrator
  /generation
  /rendering
  /seo
  /copy

/prisma
  schema.prisma

/docs
  README.md
  architecture.md
  roadmap.md
