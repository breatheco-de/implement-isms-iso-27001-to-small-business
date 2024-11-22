<!-- hide -->
# Desarrollando un Sistema de Gestión de Seguridad de la Información (SGSI) Básico para una Organización Pública
<!-- endhide -->

<onlyfor saas="true" withBanner="false">
## 🌱 Cómo Iniciar Este Proyecto

Para comenzar este proyecto, asumirás el rol de consultor en ciberseguridad encargado de implementar un SGSI para una organización pública. Tu objetivo es desarrollar un SGSI básico para garantizar que la organización pueda gestionar y proteger adecuadamente su información. Este proyecto te guiará a través de la definición del alcance, la realización de una evaluación de riesgos, la selección de controles y la documentación de políticas y procedimientos de seguridad. Utiliza las instrucciones y listas de verificación proporcionadas para organizar tu trabajo.

## 🔑 Objetivo General

Desarrollar un SGSI fundamental para un escenario de organización pública, asegurando que la organización tenga una estructura formal para la gestión de la seguridad de la información que identifique riesgos, seleccione controles apropiados y mantenga políticas y procedimientos de seguridad efectivos.

</onlyfor>

## 📝 Instrucciones

### Paso 1: Selecciona una Organización Pública

Elige uno de los siguientes tipos de organizaciones públicas para tu proyecto de SGSI:

1. Agencias gubernamentales (locales, estatales, nacionales)
2. Universidades públicas
3. Hospitales públicos
4. Autoridades de transporte
5. Organizaciones sin fines de lucro o ONGs con mandatos públicos

Al seleccionar tu organización, considera los siguientes criterios:

- Disponibilidad de información: La organización debe tener informes accesibles públicamente, políticas de privacidad, documentos de cumplimiento o documentación de TI/seguridad.
- Relevancia para la seguridad de la información: Las organizaciones que gestionan información sensible son preferibles para una experiencia de aprendizaje más realista.
- Complejidad: Elige una organización lo suficientemente compleja como para proporcionar una experiencia desafiante, con una combinación de controles físicos, técnicos y administrativos que abordar.

Para desarrollar un Sistema de Gestión de Seguridad de la Información (SGSI) para una organización pública, es crucial elegir una organización que tenga una cantidad sustancial de información accesible públicamente. A continuación, algunos tipos de organizaciones junto con recomendaciones y enlaces a fuentes de información que facilitarán el proyecto de SGSI:

#### Organizaciones o Empresas Públicas Recomendadas:

| Organización | Descripción | Fuentes de Información |
|--------------|-------------|------------------------|
| Servicio Postal de los Estados Unidos (USPS) | Organización de servicio público compleja que maneja información sensible de los ciudadanos. Ideal para un SGSI. | [Informes y Publicaciones del USPS](https://about.usps.com/what/financials/) |
| Instituto Nacional de Estándares y Tecnología (NIST) | Proporciona numerosos recursos para la transparencia pública, incluidas directrices de evaluación de riesgos y políticas. | [Información Pública del NIST](https://www.nist.gov/publications) |
| Sistema de la Universidad de California | Sistema universitario público con documentos accesibles sobre estándares de ciberseguridad, políticas de privacidad y gestión de riesgos. | [Oficina de Seguridad de la Información de la Universidad de California](https://security.ucop.edu/) |
| NYC Health + Hospitals | Maneja amplios datos de pacientes con informes anuales disponibles, informes financieros y estrategias de seguridad de TI. | [Publicaciones de NYC Health + Hospitals](https://www.nychealthandhospitals.org/publications-reports/) |
| Servicio Nacional de Salud (NHS), Reino Unido | Información extensa sobre políticas de privacidad, estrategias de ciberseguridad y gestión de datos de salud pública. | [NHS Digital – Gobernanza de Datos e Información](https://digital.nhs.uk/data) |
| Autoridad Metropolitana de Transporte (MTA), Nueva York | Publica amplia documentación sobre planes operativos, políticas de ciberseguridad y estados financieros. | [Informes Financieros y Presupuestarios de MTA](https://new.mta.info/transparency) |
| Transport for London (TfL) | Proporciona informes de transparencia, documentación de gestión de riesgos y políticas de cumplimiento relacionadas con la tecnología de la información. | [Seguridad & Protección](https://tfl.gov.uk/corporate/safety-and-security/) |
| Organización Mundial de la Salud (OMS) | Documentos disponibles públicamente relacionados con políticas de privacidad y ciberseguridad, junto con informes anuales sobre infraestructura de TI. | [Publicaciones de la OMS](https://www.who.int/publications) |
| UNICEF | Publica informes anuales, estados financieros y políticas de ciberseguridad y privacidad. | [Informes y Datos de UNICEF](https://www.unicef.org/reports) |

Estas organizaciones tienen información extensa en sus sitios web públicos, lo que te ayudará a reunir los datos necesarios para el SGSI, realizar una evaluación de riesgos, seleccionar controles y crear políticas y procedimientos apropiados. Déjame saber si necesitas más detalles o orientación sobre pasos específicos del proyecto SGSI.

### Paso 2: Definición del Alcance

Define el alcance del SGSI para establecer los límites de lo que necesita ser asegurado.

- [ ] **Identificar Activos de Información**

Crea un inventario de todos los activos de información, como computadoras, servidores, bases de datos, información de ciudadanos/estudiantes/pacientes, datos de investigación, etc.

Identifica y clasifica los activos según su importancia para las operaciones (por ejemplo, crítico, alto, medio, bajo).

- [ ] **Definir Límites Físicos**

Determina qué ubicaciones físicas están incluidas en el SGSI (por ejemplo, oficinas, centros de datos, campus).

Identifica áreas que necesitan acceso restringido (por ejemplo, salas de servidores, laboratorios de investigación).

- [ ] **Definir Límites Virtuales**

Identifica redes, entornos en la nube y máquinas virtuales que están incluidas en el SGSI.

Especifica qué sistemas y tipos de datos están bajo el control del SGSI.

- [ ] **Identificación de las Partes Interesadas**

Identifica a las partes interesadas clave (por ejemplo, equipo de TI, gestión, empleados, ciudadanos/estudiantes/pacientes).

Asigna responsabilidades a cada parte interesada para las actividades de seguridad de la información.

- [ ] **Documentar el Alcance del SGSI**

Documenta el propósito del SGSI, incluyendo su alcance, metas y objetivos.

Especifica cualquier limitación o exclusión.

### Paso 3: Evaluación de Riesgos

Identifica y evalúa los riesgos asociados con la organización y sus activos.

- [ ] **Crear una Lista de Inventario de Activos**

Desarrolla una lista completa de todos los activos identificados en la definición del alcance.

Clasifica los activos en categorías como hardware, software, datos y personal.

- [ ] **Identificar Amenazas Potenciales**

Identifica posibles amenazas que puedan afectar a cada activo (por ejemplo, acceso no autorizado, malware, desastres naturales, violaciones de datos).

Considera tanto amenazas externas como internas.

- [ ] **Identificar Vulnerabilidades**

Identifica vulnerabilidades que podrían exponer activos a las amenazas identificadas (por ejemplo, falta de cifrado, contraseñas débiles, sistemas desactualizados).

Evalúa cómo cada vulnerabilidad podría ser explotada.

- [ ] **Evaluar Probabilidad e Impacto**

Para cada riesgo, evalúa la probabilidad de ocurrencia (por ejemplo, alta, media, baja).

Evalúa el impacto potencial en la organización si el riesgo se materializa (por ejemplo, pérdida financiera, daño a la reputación, compromiso de datos sensibles).

- [ ] **Priorización de Riesgos**

Asigna una calificación de riesgo (por ejemplo, alto, medio, bajo) basada en la probabilidad y el impacto.

Prioriza los riesgos que requieren atención o mitigación inmediata.

### Paso 4: Selección de Controles

Selecciona controles de seguridad apropiados para mitigar los riesgos identificados.

- [ ] **Revisar Normas Relevantes**

Revisa normas como ISO/IEC 27001, NIST o CIS para opciones de control.

Determina qué controles son relevantes para los riesgos identificados y cumplen con cualquier regulación sectorial específica (por ejemplo, HIPAA para el sector salud).

- [ ] **Seleccionar Controles**

Elige controles de seguridad que mitiguen eficazmente los riesgos identificados (por ejemplo, firewalls, cifrado, autenticación multifactor, sistemas de control de acceso).

Asegúrate de que los controles seleccionados sean factibles considerando los recursos de la organización y las limitaciones del sector público.

- [ ] **Documentar la Implementación de Controles**

Documenta cada control seleccionado, incluyendo detalles sobre cómo mitigará el riesgo correspondiente.

Especifica roles y responsabilidades para la implementación de cada control.

- [ ] **Planificación de la Implementación**

Crea un plan de implementación que detalle cronogramas y recursos necesarios para la implementación de controles.

Identifica cualquier dependencia o requisito previo para implementar cada control.

### Paso 5: Documentación de Políticas y Procedimientos de Seguridad

Crea documentación formal para establecer prácticas de seguridad.

- [ ] **Desarrollar Política de Seguridad**

Redacta una Política de Seguridad de alto nivel que describa el compromiso de la organización con la seguridad de la información.

Incluye principios clave como confidencialidad, integridad y disponibilidad.

- [ ] **Control de Acceso de Usuarios**

Define cómo se concederá, modificará o revocará el acceso de los usuarios.

Esboza políticas de contraseñas, incluidas los requisitos de complejidad y la frecuencia de rotación.

- [ ] **Plan de Respuesta a Incidentes**

Define qué constituye un incidente de seguridad.

Crea un procedimiento paso a paso para informar, responder y mitigar incidentes de seguridad.

Identifica roles y responsabilidades durante la gestión de incidentes.



- [ ] **Copia de Seguridad y Recuperación de Datos**

Establece procedimientos para copias de seguridad regulares de los datos.

Define roles responsables de realizar copias de seguridad y verifica las capacidades de recuperación a través de pruebas.

- [ ] **Concienciación y Capacitación de los Empleados**

Desarrolla un plan de capacitación para asegurar que los empleados comprendan las políticas de seguridad y sus responsabilidades.

Crea materiales de concienciación (por ejemplo, carteles, directrices) para fomentar las mejores prácticas de seguridad.

- [ ] **Aprobación y Revisión de Documentos**

Asegúrate de que todas las políticas y procedimientos sean revisados y aprobados por la dirección.

Establece un cronograma para revisiones y actualizaciones periódicas de los documentos.

### Paso 6: Preparar Manual de SGSI

Compila toda la documentación en un manual del SGSI.

- [ ] **Organizar Documentación**

Compila todas las políticas, procedimientos, evaluaciones de riesgos y documentación de controles en un manual estructurado.

Incluye una visión general del SGSI, su alcance y objetivos.

- [ ] **Definir Roles y Responsabilidades**

Define claramente los roles y responsabilidades para el mantenimiento y mejora del SGSI.

Incluye una sección sobre el compromiso del liderazgo con el SGSI.

- [ ] **Documentar la Metodología de Evaluación de Riesgos**

Proporciona una explicación detallada del proceso de evaluación de riesgos utilizado.

Incluye plantillas o formularios utilizados en el proceso de evaluación de riesgos.

- [ ] **Describir Monitoreo y Medición**

Define cómo se monitoreará y medirá la efectividad del SGSI.

Incluye indicadores clave de rendimiento (KPIs) para la seguridad de la información.

### Paso 7: Revisar y Presentar el SGSI

Realiza una revisión de tu SGSI y prepara una presentación para las partes interesadas.

- [ ] **Revisar el SGSI**

Revisa todos los componentes del SGSI para asegurar que estén alineados con el alcance y objetivos definidos.

Verifica que todos los riesgos hayan sido evaluados y mitigados adecuadamente.

Asegúrate de que todas las políticas y procedimientos de seguridad estén documentados de manera clara y completa.

- [ ] **Preparar Presentación**

Desarrolla una presentación que resuma el alcance del SGSI, los hallazgos de la evaluación de riesgos, los controles seleccionados y las políticas de seguridad.

Destaca los riesgos clave y las medidas tomadas para mitigarlos.

Identifica áreas de mejora futura y monitoreo continuo.

- [ ] **Presentar a las Partes Interesadas**

Presenta el SGSI a las partes interesadas clave (por ejemplo, dirección, equipo de TI, jefes de departamento).

Recoge retroalimentación y realiza los ajustes necesarios según sus aportes.

## 📦 Entregables

Un informe detallado que incluya:

- Alcance definido del SGSI para la organización pública seleccionada (en formato PDF, aproximadamente 1 página).
- Resultados de la evaluación de riesgos (en formato PDF, aproximadamente 2-3 páginas).
- Lista de controles seleccionados (en formato PDF o hoja de cálculo, 2-3 páginas o equivalente).
- Políticas y procedimientos de seguridad (en formato Word o PDF, aproximadamente 5-6 páginas).
- Manual del SGSI (en formato Word o PDF, aproximadamente 15-20 páginas).
- Un archivo de presentación que resuma tu enfoque del SGSI, hallazgos y recomendaciones (en formato PowerPoint o PDF, 8-10 diapositivas).

Recuerda pensar de manera crítica sobre cada paso y hacer suposiciones razonables cuando te enfrentes a brechas de información. Este proyecto te ayudará a desarrollar habilidades prácticas en evaluación de riesgos, desarrollo de políticas y aplicación de un enfoque basado en riesgos a la seguridad de la información en el contexto del sector público.
