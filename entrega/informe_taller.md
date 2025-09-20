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
### Tema investigado:
(Ej: Buenas prácticas BPMN, comparación TOGAF vs C4, principios de seguridad STRIDE, etc.)

### Resumen:
Describa en 2–3 párrafos lo investigado, citando fuentes cuando sea necesario. Incluya cómo se relaciona con el taller.

## 📚 Referencias
- [1] Apellido, Nombre. *Título*. Año. URL o DOI.
- [2] Fuente oficial BPMN: https://www.omg.org/spec/BPMN/

---

_Este documento hace parte de la entrega del taller X del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
