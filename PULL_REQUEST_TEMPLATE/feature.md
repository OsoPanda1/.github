# Feature Pull Request

> Tipo: Nueva funcionalidad / mejora significativa

## 1. Resumen

**Issue(s) relacionada(s):**  
- Closes #  
- Relates to #  

**Descripción breve del cambio:**  
Explica en 2–3 frases qué hace este PR y por qué es necesario.

---

## 2. Contexto y objetivo

- ¿Qué problema resuelve este PR?
- ¿Cómo se conecta con la propuesta de feature original (issue)?
- ¿Qué resultado concreto se espera tras desplegarlo?

---

## 3. Alcance del PR

### 3.1. En alcance

Lista concreta de lo que incluye este PR:
- Funcionalidades añadidas.
- Módulos / componentes tocados.
- Endpoints / APIs afectados.
- Cambios de UX relevantes.

### 3.2. Fuera de alcance

Indica explícitamente qué **no** aborda este PR (aunque esté relacionado), para evitar confusiones:
- Tareas que se dejan para otro PR.
- Refactors pendientes.
- Casos extremos pospuestos.

---

## 4. Detalles de implementación

Describe cómo se ha implementado la solución:

- Enfoque principal elegido.
- Estructura del código y patrones usados.
- Decisiones no obvias y por qué se tomaron.
- Cambios en modelos de datos, contratos de API o configuración.
- Migraciones, scripts o tareas de mantenimiento asociadas (si aplica).

---

## 5. Impacto y riesgos

### 5.1. Impacto

Marca y explica las dimensiones relevantes:

- Usuarios / comunidad:
  - [ ] Bajo
  - [ ] Medio
  - [ ] Alto  
  Comentario:

- Territorio / soberanía de datos:
  - [ ] Nulo
  - [ ] Relevante
  - [ ] Crítico  
  Comentario:

- Arquitectura / mantenibilidad:
  - [ ] Menor
  - [ ] Moderado
  - [ ] Mayor  
  Comentario:

- Seguridad / cumplimiento:
  - [ ] Sin impacto
  - [ ] Mejora de seguridad
  - [ ] Introduce nuevos riesgos  
  Comentario:

### 5.2. Riesgos y mitigaciones

- Riesgo 1:
  - Impacto:
  - Probabilidad:
  - Mitigación:
- Riesgo 2:
  - Impacto:
  - Probabilidad:
  - Mitigación:

---

## 6. Pruebas y validación

### 6.1. Pruebas implementadas

Indica qué pruebas se han añadido / actualizado:

- [ ] Unitarias
- [ ] Integración
- [ ] End-to-end
- [ ] De seguridad / regresión
- [ ] Otras:

Describe brevemente:

- Áreas cubiertas por las pruebas.
- Casos clave que se validan.
- Limitaciones conocidas de la cobertura actual.

### 6.2. Resultados

- Comando(s) de test ejecutado(s):
- Resultado:  
  - [ ] Todos los tests pasan.  
  - [ ] Hay tests fallando (explicar por qué):

---

## 7. Compatibilidad y despliegue

- ¿Introduce breaking changes en APIs o contratos?
  - [ ] Sí
  - [ ] No  
  Detalles:

- ¿Requiere pasos especiales de despliegue?  
  (migraciones, cambios de configuración, claves, seeding de datos, etc.)
  - [ ] Sí
  - [ ] No  
  Detalles:

- ¿Existe plan de rollback?
  - [ ] Sí
  - [ ] No  
  Explica cómo revertir el cambio si es necesario.

---

## 8. Checklist del autor

Marca todo lo que apliques antes de pedir revisión:

- [ ] He leído y respetado el `CONTRIBUTING.md`.
- [ ] Este PR está vinculado a al menos un issue.
- [ ] El alcance está alineado con la propuesta original.
- [ ] No he introducido cambios no relacionados (sin justificar).
- [ ] He añadido / actualizado pruebas cuando corresponde.
- [ ] He ejecutado la suite de tests y documentado resultados.
- [ ] He considerado impacto en seguridad y soberanía de datos.
- [ ] He actualizado documentación relevante (si aplica).
- [ ] He verificado que no se rompen integraciones conocidas.

---

## 9. Notas para revisión

- Áreas del código donde quieres especial atención.
- Dudas abiertas o decisiones que podrían cambiar.
- Cualquier contexto extra que facilite una revisión de calidad.

---

## 10. Capturas, ejemplos o evidencia

Incluye capturas de pantalla, GIFs, ejemplos de requests/responses o enlaces a entornos de prueba que ayuden a revisar este PR.
