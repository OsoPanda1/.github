# Código de Conducta del Pacto de Colaboradores  
**RDM Digital Hub — LDTOCS (MD-X4)**

> Versión 1.0 · Este documento es vinculante para toda participación en el ecosistema RDM Digital Hub.

---

## 1. Propósito y alcance

RDM Digital Hub — LDTOCS (MD-X4) es una infraestructura digital soberana orientada a territorios, memoria histórica y comunidades reales.  
Este Código de Conducta define las normas mínimas de comportamiento, ética y colaboración en todos los espacios vinculados al proyecto:

- Repositorios de código, documentación y artefactos.
- Issues, pull requests, discusiones, revisiones y comentarios.
- Despliegues, entornos de prueba y producción (incluyendo Replit y cualquier infraestructura asociada).
- Canales de coordinación, foros, redes sociales oficiales y espacios presenciales donde se represente al proyecto.

Aplica a:

- Mantenedores, colaboradores, revisores y moderadores.
- Usuarias/os, administradores de despliegues y personas que integran el proyecto en terceros sistemas.
- Patrocinadores, aliadas/os y representantes institucionales que actúan en nombre de RDM Digital Hub.

---

## 2. Principios rectores

1. **Respeto irrestricto a la dignidad humana**  
   Ningún objetivo técnico, académico o económico justifica el maltrato, la humillación o la discriminación.

2. **Responsabilidad técnica y ética**  
   Cada contribución (código, decisión, despliegue) debe considerar impacto en seguridad, soberanía de datos y bienestar comunitario.

3. **Soberanía territorial y digital**  
   Las comunidades y territorios a los que sirve el proyecto tienen prioridad sobre intereses personales, corporativos o externos.

4. **Transparencia y trazabilidad**  
   Decisiones relevantes deben quedar documentadas; los cambios sustantivos deben ser rastreables y auditables.

5. **No neutralidad ante el daño**  
   La inacción frente a abuso, discriminación o sabotaje también se considera falta ética.

---

## 3. Conductas esperadas

Toda persona que participe en el proyecto debe:

- Usar lenguaje profesional, claro e inclusivo, evitando insultos, sarcasmo agresivo y ambigüedad maliciosa.
- Respetar tiempos, procesos y roles (revisión, triaje, despliegue, moderación).
- Aceptar la crítica técnica con apertura, sin llevarla al plano personal.
- Documentar decisiones relevantes y justificar cambios estructurales.
- Proteger credenciales, datos sensibles y contexto territorial (DPA).
- Reportar vulnerabilidades de seguridad o riesgos de soberanía de forma responsable.
- Reconocer errores propios y colaborar activamente en su corrección.
- Priorizar lo que es mejor para la comunidad y el territorio por encima del ego o interés individual.

---

## 4. Conductas prohibidas

Se prohíbe expresamente, sin excepciones:

### 4.1. Abuso y acoso

- Insultos, humillaciones, hostigamiento, amenazas directas o veladas.
- Lenguaje discriminatorio o despectivo basado en género, orientación sexual, raza, origen, clase, religión, edad, discapacidad o identidad.
- Trolleo persistente, provocación maliciosa, campañas de desgaste o de odio.
- Sexualización no deseada, insinuaciones, coerción o conductas invasivas.

### 4.2. Sabotaje técnico

- Introducir deliberadamente bugs, backdoors, bombas lógicas o degradación oculta del sistema.
- Modificar código, configuración o infraestructura con intención de causar caída del servicio, pérdida de datos o daño reputacional.
- Ocultar cambios de alto impacto en commits ambiguos, falsos o engañosos.

### 4.3. Violación de soberanía y privacidad

- Exponer datos personales, información territorial sensible o credenciales sin permiso explícito.
- Extraer información de forma abusiva, para venderla, explotarla o perjudicar a la comunidad.
- Ignorar o vulnerar las políticas de DPA y de seguridad PQC definidas en el proyecto.

### 4.4. Abuso de poder y manipulación

- Usar roles de mantenimiento, moderación o coordinación para silenciar, excluir o favorecer de forma injusta.
- Imponer decisiones sin documentación ni proceso de revisión cuando hay impacto estructural.
- Descalificar a personas por su origen territorial, nivel de experiencia o idioma.

---

## 5. Normas operativas concretas

### 5.1. En el código y los PRs

- Todo PR relevante debe:
  - Tener descripción clara del cambio.
  - Indicar módulos afectados y riesgo potencial.
  - Referenciar el issue correspondiente (bug, feature, security, arch).
- No se permiten:
  - PRs masivos sin desglose razonable.
  - Cambios de seguridad sin revisión doble (`security` + `architecture`).
  - Commits que mezclen refactor profundo con cambios funcionales sin explicación.

### 5.2. En issues y discusiones

- Se reportan bugs y propuestas usando los templates definidos (bug, feature, security, architecture).
- No se toleran:
  - Issues usados para ataques personales.
  - Comentarios con lenguaje degradante o burlas hacia personas o territorios.
- La crítica técnica debe centrarse en el código, el diseño o la decisión, nunca en la persona.

### 5.3. En despliegues e infraestructura

- Las personas que despliegan a producción deben:
  - Verificar el estado de CI/CD.
  - Respetar ventanas de mantenimiento y políticas de rollback.
  - Documentar incidentes de forma honesta y completa.
- Cualquier manipulación maliciosa de entornos (Replit, Supabase, etc.) es falta grave.

---

## 6. Comité de Conducta y canales de reporte

El proyecto contará con un **Comité de Conducta y Ética** (CCE), compuesto por al menos 3 personas designadas, con las siguientes responsabilidades:[web:192][web:193]

- Recibir, evaluar y dar seguimiento a reportes de incidentes.
- Definir medidas de protección para personas afectadas.
- Recomendar sanciones a la dirección del proyecto.
- Publicar informes de transparencia periódicos (sin datos sensibles).

Los reportes se podrán realizar por:

- Correo electrónico a un canal oficial del proyecto (definido en la documentación).
- Formulario privado o canal seguro especificado en el repositorio.
- Contacto directo con personas del CCE, cuando esté permitido.

Cada reporte debe incluir:

- Descripción clara del incidente.
- Personas involucradas (si se conocen).
- Contexto (repositorio, canal, fecha, hilo).
- Evidencia disponible (enlaces, capturas, registros).
- Si la situación continúa o ya terminó.

El CCE se compromete a:

- Proteger la identidad de quien reporta en la medida de lo posible.
- No tomar represalias contra quienes denuncian de buena fe.
- Actuar con imparcialidad y trazabilidad.

---

## 7. Protocolo de respuesta y escalera de sanciones

Inspirado en las mejores prácticas de comunidades como Django y Contributor Covenant, RDM Digital Hub adopta una **escalera de sanciones** proporcional.[web:188][web:190][web:196]

### 7.1. Niveles de respuesta

1. **Corrección informal**  
   - Recordatorio privado o público de las normas.
   - Útil para incidentes leves o malentendidos.

2. **Advertencia formal (Warning)**  
   - Mensaje escrito, documentado, que explica la conducta inaceptable.
   - Puede incluir condiciones para continuar participando.

3. **Restricción de espacios**  
   - Limitación temporal de acceso a ciertos canales (ej. discusiones, PR reviews).
   - Se usa cuando la conducta afecta gravemente la dinámica de trabajo.

4. **Suspensión temporal**  
   - Bloqueo de participación en el proyecto por un periodo específico.
   - Aplicable a abuso repetido, sabotaje técnico o desobediencia consciente.

5. **Suspensión extendida**  
   - Prolongación de la suspensión con condiciones estrictas de regreso.
   - Usada en casos donde el daño fue severo pero se considera posible rehabilitación.

6. **Expulsión permanente**  
   - Remoción definitiva del proyecto y sus espacios asociados.
   - Se reserva para casos de violencia extrema, sabotaje grave, ataques sistemáticos, o violaciones severas de seguridad/soberanía.

### 7.2. Criterios de gravedad

Se consideran agravantes:

- Reincidencia.
- Negación sistemática de responsabilidad.
- Daño directo a personas vulnerables o comunidades territoriales.
- Sabotaje consciente de código, infraestructura o datos.
- Publicación de información sensible sin consentimiento.

Se consideran atenuantes:

- Reconocimiento claro y sincero del error.
- Colaboración activa en la reparación.
- Voluntad de formación y cambio de conducta.

---

## 8. Conflictos de interés

Miembros del CCE y del equipo de mantenimiento deben abstenerse de participar en la evaluación de incidentes donde:

- Están personalmente involucrados.
- Tienen relación de poder o dependencia directa con alguna de las partes.
- Pueden beneficiarse o perjudicarse significativamente con la decisión.

En esos casos, se reassigna el caso a otras personas del CCE o a una instancia de revisión independiente.

---

## 9. Transparencia y revisión periódica

El CCE se compromete a:

- Publicar un informe de transparencia anual (o semestral) con:
  - Número de reportes recibidos.
  - Tipos de incidentes (sin datos identificables).
  - Respuestas aplicadas (sin detalles sensibles).
- Revisar este Código de Conducta al menos una vez al año.
- Proponer actualizaciones cuando cambie el contexto del proyecto o se detecten nuevas necesidades.

---

## 10. Relación con otros códigos

Este Código de Conducta se inspira en:

- Contributor Covenant y recursos de moderación.[web:188][web:190][web:197]  
- Código de conducta y manual de aplicación de Django.[web:193][web:196]  
- Buenas prácticas generales de comunidades abiertas y proyectos de software libre.[web:191][web:192]  

Ha sido adaptado específicamente al contexto de **RDM Digital Hub — LDTOCS (MD-X4)**, con énfasis en soberanía digital, territorio, seguridad y memoria comunitaria.

---

## 11. Aceptación

Participar en RDM Digital Hub — LDTOCS supone aceptar este Código de Conducta:

- Cuando se contribuye código, documentación o decisiones.
- Cuando se administra despliegues o infraestructura asociada.
- Cuando se representa al proyecto ante cualquier público.

El proyecto se reserva el derecho de aplicar las medidas descritas en este documento para proteger a la comunidad, el territorio y la integridad del sistema.
