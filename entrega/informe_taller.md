# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 5 - Evaluación de Seguridad con STRIDE_

## 👥 Integrantes del equipo
- Samuel Esptia Cruz - samuelescr@unisabana.edu.co
- Edwin ALejandro Gutierrez Rodriguez - edwingutro@unisabana.edu.co
- Nicolas Stiven Ortiz Cortes - nicolasorco@unisabana.edu.co

## 🧠 Descripción general del trabajo
El objetivo del Taller 5 fue analizar riesgos de seguridad en sistemas de información aplicando el marco STRIDE, con el fin de identificar amenazas potenciales y definir medidas de mitigación que protejan la integridad, confidencialidad y disponibilidad de los datos.

La actividad se desarrolló en dos fases:

**Trabajo en clase:** el equipo seleccionó un flujo crítico del caso base EdukIT (plataforma de educación virtual) y aplicó el marco STRIDE. Para ello se construyó una tabla con las amenazas identificadas (como suplantación de identidad, alteración de datos, divulgación no autorizada o denegación de servicio), evaluando el impacto y proponiendo controles de mitigación. Esta parte permitió practicar el modelo en un entorno guiado.

**Aplicación al cliente real:** después de la clase, el equipo trasladó la metodología al sistema del cliente, escogiendo el proceso de adquisiciones en curso. Se elaboró una tabla con amenazas, riesgos y medidas de seguridad específicas, además de un informe técnico que documenta los hallazgos. Finalmente, se investigaron buenas prácticas de ciberseguridad en el sector correspondiente para enriquecer el análisis y alinear las propuestas con estándares reconocidos.

## 🔧 Proceso de desarrollo
Para el desarrollo del taller se seleccionó el proceso de adquisiciones en curso de la Universidad de La Sabana, al considerarse un flujo crítico por el manejo de información sensible como proveedores, contratos y transacciones económicas. Inicialmente se analizaron los modelos realizados en otro tallers para identificar los actores y sistemas que intervienen, lo que permitió ubicar los puntos de interacción más vulnerables. A partir de este modelo se aplicó el marco STRIDE, evaluando cada categoría de amenaza sobre el flujo (suplantación de identidad en accesos, alteración de solicitudes o contratos, falta de trazabilidad en aprobaciones, divulgación de datos financieros, interrupción del servicio o escalamiento de privilegios indebidos). Para documentar los hallazgos se utilizó una tabla en Excel, donde se consignaron amenazas, impactos y controles propuestos como autenticación multifactor, encriptación de información, auditoría de transacciones y políticas de control de acceso. El modelo se fue ajustando conforme se identificaron nuevos riesgos, priorizando los de mayor impacto en la continuidad del proceso, y finalmente se complementó con la revisión de buenas prácticas de ciberseguridad aplicables al sector educativo y a la gestión administrativa universitaria.

## 🧩 Análisis del modelo propuesto
Incluya un análisis sobre:
- Cómo se estructura el modelo entregado
- Cómo representa las necesidades del cliente
- Qué supuestos se tomaron

## Tabla STRIDE

## 📋 Tabla de actores, entidades o componentes (si aplica)

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Ej: Paciente        | Actor | Usuario que agenda una cita médica | Cliente |

## 🔍 Investigación complementaria
### Buenas Prácticas de Seguridad en el Sector Educativo

#### Introducción

Las instituciones educativas han transitado hacia entornos digitales donde la colaboración, el almacenamiento en la nube y las plataformas de aprendizaje en línea son la norma. Este cambio amplifica la superficie de ataques ciberneticos y exige que se tomen medidas preventivas para evitar ser vulnerados. La UNESCO recomienda integrar las amenazas tecnológicas en el Marco Integral de Seguridad Escolar (CSSF), garantizando un entorno seguro para todos los actores educativos.


#### Principales Amenazas y Retos

- *Phishing:* correos o mensajes falsos que buscan robar credenciales de estudiantes, docentes y administrativos.  

- *Malware:* software malicioso que compromete dispositivos y redes institucionales.  

- *Ransomware:* cifrado de datos críticos de la institución a cambio de rescate, interrumpiendo la continuidad educativa.  

- *Acceso no autorizado:* ausencia de controles de privilegios y contraseñas débiles que facilitan intrusiones.  

- *Brechas de privacidad:* uso inadecuado o excesivo de datos personales sin políticas claras de retención y eliminación.  

- *Vulnerabilidades en plataformas:* fallas en sistemas de gestión de aprendizaje (LMS) y aplicaciones educativas sin parches al día.  


#### Buenas Prácticas Recomendadas

Para fortalecer la seguridad en el sector educativo, es fundamental implantar contraseñas robustas y autenticación multifactor que obliguen a renovar las claves regularmente y protejan los accesos críticos; además, se debe automatizar el parcheo continuo de sistemas operativos, servidores LMS y aplicaciones de apoyo para corregir vulnerabilidades sin demora. También resulta imprescindible cifrar los datos en tránsito y en reposo mediante protocolos TLS y soluciones de cifrado en la nube, al tiempo que se aplica el principio de menor privilegio en la gestión de accesos, asignando y revisando permisos según el rol de cada usuario. Asimismo, conviene diseñar y poner a prueba con frecuencia un plan de copias de seguridad automatizadas y recuperación ante desastres, y complementar esta estrategia con formación y simulacros de ciberhigiene que incluyan talleres de detección de phishing, uso responsable de dispositivos y ejercicios de respuesta a incidentes. De igual modo, la segmentación de redes internas limita el alcance de posibles ataques, mientras que unas políticas claras de privacidad y manejo de datos garantizan procesos transparentes de recolección, almacenamiento y eliminación conforme a normativas vigentes. Finalmente, es clave realizar auditorías y revisiones periódicas para verificar el cumplimiento de todas estas medidas y ajustar los procedimientos según evolucione el panorama de amenazas.

### Resumen:
La investigación sobre buenas prácticas de seguridad en el sector educativo revela una creciente necesidad de proteger los entornos digitales frente a amenazas como el phishing, el ransomware y el acceso no autorizado. Instituciones educativas manejan datos sensibles de estudiantes, docentes y personal administrativo, lo que las convierte en blancos atractivos para atacantes. Según Dynamics and Learning, es esencial implementar contraseñas seguras, autenticación multifactor, cifrado de datos y políticas claras de privacidad para mitigar estos riesgos. La UNESCO también destaca la importancia de integrar la ciberseguridad en el Marco Integral de Seguridad Escolar, abordando no solo amenazas físicas sino también digitales.

Estas prácticas se alinean directamente con el enfoque del modelo STRIDE, utilizado en el taller para identificar amenazas en sistemas informáticos. STRIDE clasifica los riesgos en seis categorías: suplantación de identidad (Spoofing), manipulación de datos (Tampering), repudio (Repudiation), divulgación de información (Information Disclosure), denegación de servicio (Denial of Service) y elevación de privilegios (Elevation of Privilege). Por ejemplo, la autenticación multifactor combate el spoofing, mientras que el cifrado de datos protege contra la divulgación de información. La gestión de accesos y el principio de menor privilegio abordan la elevación de privilegios, y los planes de recuperación ante desastres mitigan los efectos de la denegación de servicio. Así, las buenas prácticas investigadas no solo refuerzan la seguridad operativa, sino que también permiten mapear amenazas concretas dentro del marco STRIDE, facilitando su análisis y prevención sistemática.

## 📚 Referencias

- [1] Dynamics and Learning, “Estrategias para la ciberseguridad en el entorno educativo,” [En línea]. Disponible en: https://dynamicsandlearning.com/es/post/estrategias-ciberseguridad-entorno-educativo/. [Accedido: 20-sep-2025].

- [2] UNESCO, “Proteger la educación frente a todos los peligros y riesgos,” [En línea]. Disponible en: https://www.unesco.org/es/emergencies/education/protecting-hazards. [Accedido: 20-sep-2025].

- [3] Innoversia, “Seguridad y Privacidad en Plataformas Educativas: Fundamentos para un Entorno Digital Seguro,” [En línea]. Disponible en: https://innoversia.net/seguridad-privacidad-plataformas-educativas/. [Accedido: 20-sep-2025].

- [4] Infonucleo, “Buenas Prácticas Digitales: Fomentando una Cultura de Ciberseguridad desde las Escuelas,” [En línea]. Disponible en: https://www.infonucleo.com/buenas-practicas-digitales-fomentando-una-cultura-de-ciberseguridad-desde-las-escuelas/. [Accedido: 20-sep-2025].


_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
