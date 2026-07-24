# Guía de Contribución  
**RDM Digital Hub — LDTOCS (MD-X4)**

Esta guía define el cómo, el cuándo y el bajo qué estándares se contribuye a los proyectos del ecosistema RDM Digital Hub.  
Todas las personas que envíen código, documentación, diseño, datos o decisiones deben seguir estas reglas.

---

## 1. Código de Conducta

Antes de contribuir, lee y acepta el [Código de Conducta](./CODE_OF_CONDUCT.md).  
Todas las interacciones —issues, pull requests, comentarios, discusiones y despliegues— están reguladas por él.

El incumplimiento del Código de Conducta puede derivar en bloqueo de PRs, restricción de participación o sanciones según la escalera definida.

---

## 2. Filosofía de Desarrollo Abierto

Todo el trabajo de RDM Digital Hub se realiza de manera abierta en GitHub.  
Tanto el equipo núcleo como personas colaboradoras externas utilizan issues y pull requests, sometidos al mismo proceso de revisión.[web:198][web:199]

Principios:

- Ningún cambio relevante se hace fuera de Git.
- Las decisiones importantes se documentan en issues, PRs o propuestas arquitectónicas.
- Cualquier persona puede revisar, comentar y sugerir mejoras respetando el Código de Conducta.

---

## 3. Estándares de Ingeniería

### 3.1. Calidad mínima aceptable

Cada contribución de código debe aspirar a:

- Ser legible, modular y mantenible.
- Estar cubierta por pruebas (unitarias, de integración, de contrato o E2E según corresponda).[web:202][web:205]  
- Respetar los estándares de estilo y arquitectura definidos en el proyecto.

No se aceptan:

- Cambios sin justificación técnica clara.
- PRs que rompan tests existentes sin explicación y estrategia.
- Refactors masivos sin documentación de impacto.

### 3.2. Pruebas y TDD

Promovemos el enfoque de desarrollo guiado por pruebas (TDD) cuando sea viable.[web:199][web:205]

- Si añades funcionalidad nueva, también añades pruebas nuevas.
- Si corriges un bug, añades una prueba que lo reproduzca y verifique la corrección.
- Si refactorizas, asegúrate de que las pruebas existentes siguen pasando.

---

## 4. Flujo de trabajo con Git y ramas

### 4.1. Rama base

La rama base del desarrollo es `main` (o `master`, según repo).  
Todos los pull requests deben hacerse contra esa rama, salvo que la documentación diga lo contrario.

### 4.2. Convenciones de ramas

Se recomienda crear ramas con nombre descriptivo, por ejemplo:

- `feat/<modulo>-<descripcion-corta>`
- `fix/<modulo>-<bug-id>`
- `chore/<tarea>`
- `docs/<area>-<descripcion>`

Ejemplos:

- `feat/ldocs-territorial-search`
- `fix/mdx4-security-headers`
- `docs/api-dpa`

### 4.3. Commits

Los commits deben ser:

- Pequeños y coherentes: un cambio conceptual por commit.[web:202]  
- Con mensajes claros, en imperativo corto (ej. `Add PQC key rotation`, `Fix arch triage script`).
- Sin “basura” tipo `fix stuff`, `changes` o similares.

Commits que mezclen cambios de seguridad, refactor masivo y nueva funcionalidad sin separación podrán ser rechazados en revisión.

---

## 5. Gestión de issues y bugs

### 5.1. Dónde encontrar tareas

Usamos **GitHub Issues** para:

- Bugs (`[BUG]`, label `bug`).
- Features (`[FEATURE]`, label `enhancement`).
- Seguridad (`[SECURITY]`, label `security`).
- Arquitectura (`[ARCH]`, label `architecture`).  

Revisa primero los issues abiertos antes de crear uno nuevo, especialmente los etiquetados como:

- `good-first-issue`
- `help-wanted`
- `security`
- `architecture`

### 5.2. Reportar nuevos bugs

Al abrir un issue de bug, incluye como mínimo:

- Contexto: qué estabas intentando hacer.
- Pasos de reproducción, claros y ordenados.
- Entorno (navegador, OS, versión, entorno de ejecución).[web:201][web:205]  
- Lo que esperabas que ocurriera y lo que ocurrió.
- Evidencia (logs, capturas, respuestas de API, etc.).

Cuanto más preciso, más fácil será reproducir y corregir el problema.

### 5.3. Issues de seguridad

Para vulnerabilidades o problemas de soberanía de datos:

- No publiques detalles sensibles en issues públicos.
- Usa el canal de seguridad definido en la documentación del proyecto.
- Proporciona información suficiente para evaluar gravedad y reproducir de forma segura.

---

## 6. Proponer cambios

### 6.1. Cambios pequeños

Para correcciones menores (typos, fallos triviales, mejoras de documentación):

- Puedes abrir directamente un pull request.
- Aun así es recomendable referenciar un issue o crear uno pequeño.

### 6.2. Cambios no triviales

Para cambios en:

- API pública.
- Arquitectura del sistema.
- Modelos de datos y soberanía.
- Seguridad, cifrado, DPA, PQC.

Se recomienda primero:

1. Abrir un issue de propuesta (ej. `[ARCH]` o `[SECURITY]`).
2. Describir:
   - Problema actual.
   - Opciones consideradas.
   - Pros y contras.
   - Riesgos.
3. Esperar feedback y acuerdo básico.
4. Recién entonces comenzar la implementación.

Esto evita trabajo descartado y asegura alineación con la visión del proyecto.[web:198][web:204]

---

## 7. Tu primer Pull Request

Si es tu primera contribución:

- Empieza con un `good-first-issue`, una mejora de documentación o un bug pequeño.[web:205][web:207]  
- Anuncia en el issue que vas a trabajar en él para evitar duplicidades.
- Si alguien ya lo reclamó pero no hay actividad por más de 2 semanas, puedes tomarlo y dejar un comentario.

Recursos recomendados para aprender el flujo de PRs en GitHub:

- Guías generales sobre cómo contribuir a proyectos open source.[web:198][web:201][web:205]  

---

## 8. Enviar un Pull Request

Antes de enviar un PR, asegúrate de:

1. Tener tu rama creada desde `main` / `master`.
2. Haber integrado los últimos cambios de la rama base.
3. Haber añadido pruebas cuando corresponde.
4. Haber ejecutado el conjunto de tests y verificado que pasan.
5. Haber actualizado documentación si tu cambio afecta el comportamiento público.

Al abrir el PR:

- Rellena la plantilla de PR (si existe).
- Explica qué problema resuelve o qué funcionalidad introduce.
- Indica riesgos o posibles impactos.
- Referencia los issues relacionados (`Fixes #123`, `Relates to #456`).

El equipo de revisión puede:

- Aceptar y fusionar el PR.
- Solicitar cambios y mejoras.
- Cerrar el PR con explicación si no encaja en la dirección del proyecto.

---

## 9. Estándares de revisión

Las revisiones buscan proteger:

- Calidad técnica.
- Seguridad y soberanía.
- Coherencia con la arquitectura.
- Mantenibilidad y claridad del código.

Durante la revisión:

- Se espera un intercambio respetuoso y centrado en lo técnico.
- Se pueden pedir cambios de estilo, estructura o enfoque.
- Se busca, siempre, un resultado que beneficie al proyecto y a la comunidad.

---

## 10. Licencia y propiedad intelectual

Al contribuir a RDM Digital Hub — LDTOCS (MD-X4):

- Aceptas que tus contribuciones se licencien bajo las licencias del proyecto (por ejemplo, MIT u otra licencia especificada).  
- Garantizas que el código que aportas es tuyo o que tienes derecho a compartirlo.
- Aceptas que el proyecto puede usar, modificar y redistribuir tus contribuciones según la licencia.

No se acepta:

- Código copiado de terceros con licencia incompatible.
- Contribuciones que violen derechos de autor o acuerdos de confidencialidad.

---

## 11. Buenas prácticas generales

- Lee siempre el README, este `CONTRIBUTING.md` y el `CODE_OF_CONDUCT.md` antes de contribuir.[web:198][web:205]  
- Mantén un tono respetuoso en todos los canales.
- Haz preguntas si algo no está claro.
- Sé paciente con los tiempos de revisión: las personas mantenedoras tienen disponibilidad limitada.[web:202]  
- Prefiere cambios pequeños y bien explicados, en lugar de PRs enormes sin contexto.

---

## 12. Actualización de esta guía

Esta guía se revisará periódicamente para:

- Ajustarse a las nuevas necesidades del ecosistema.
- Incorporar aprendizajes de la comunidad y de casos reales.
- Mantenerse alineada con el Código de Conducta y la arquitectura del proyecto.

Contribuciones a esta propia guía son bienvenidas: si ves un área mejorable, abre un issue o PR explicando la propuesta.
