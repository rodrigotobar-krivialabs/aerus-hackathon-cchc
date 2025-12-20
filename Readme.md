# Proyecto Aerus - Equipo Krivia 
## (Inicio TLR-1 Durante Hackathon TRL-3)

  Nuestro desarrollo fue en flutter y enviamos nuestro primer aplicativo validador documental
  Parte fundamental el ecosistema de proyecto Aerus.

  https://we.tl/t-2Vvztsj9h3  (Codigo Fuente)
  https://drive.google.com/file/d/1tQsBB1xuuEGxpKJsYvg0-buJQbUt4wNE/view?pli=1    (Video Pitch)

Plataforma Integral de Gestión de Obras con Inteligencia Artificial Contextual y Trazabilidad Blockchain.

1. Visión General
Aerus se presenta no solo como un software de gestión documental, sino como un ecosistema de gobernanza técnica y legal para la industria de la construcción. Su propuesta de valor radica en la integración de tres mundos tecnológicos que raramente conviven con tanta profundidad: Arquitectura Cloud Nativa, Web3 (Blockchain) y IA Generativa Avanzada (CAG/GraphRAG).

El sistema resuelve el dolor histórico de la construcción: la desconexión entre el cumplimiento normativo (Decreto 44, leyes laborales) y la realidad operativa en terreno.

2. Experiencia de Usuario y Flujo de Valor
El sistema divide inteligentemente las responsabilidades en tres aplicativos interconectados, asegurando que cada rol tenga herramientas específicas sin ruido visual:

🏛️ La Torre de Control (Mandante/Constructora)
Rol: Gobernanza y Fiscalización.

Valor: Transforma al mandante de un mero espectador a un auditor activo. La capacidad de definir reglas documentales y visualizar el "Semáforo de Cumplimiento" de los contratistas en tiempo real elimina los cuellos de botella administrativos antes de que afecten la obra.

Diferenciador: No firma por otros, hace cumplir. Esto reduce la responsabilidad legal subsidiaria al garantizar que cada contratista está "al día" antes de operar.

🏗️ El Motor Operativo (Contratista)
Rol: Ejecución y Gestión.

Valor: Reduce la carga burocrática mediante automatización. La integración de IA para la generación de documentos y la asignación masiva de trabajadores agiliza el onboarding en obra.

Diferenciador: La "Carpeta Documental" deja de ser física y se convierte en un activo digital vivo, que se cierra automáticamente para auditoría solo cuando todo está validado.

👷‍♂️ La Realidad en Terreno (Trabajador / Prevencionista)
Rol: Validación y Firma.

Valor: Democratiza la tecnología en terreno. El uso de Códigos QR para asistencia y firmas convierte procesos complejos en acciones de segundos.

Diferenciador: La validación de identidad y firma digital (con respaldo blockchain) otorga a cada trabajador una identidad soberana dentro del proyecto. El Prevencionista actúa como la compuerta final de seguridad, emitiendo el "Acta de Conformidad".

3. Análisis de Arquitectura y Stack Tecnológico
La arquitectura de Aerus es vanguardista y resiliente, diseñada para escalar horizontalmente y manejar datos complejos.

☁️ Infraestructura y Backend (Robustez)
Kubernetes (K8s) + Cloud Run: Garantiza alta disponibilidad y auto-escalado según la carga de usuarios.

Node.js (Middleware) + Golang/Python (Cerebro): Una separación adecuada donde Node maneja la concurrencia de la red y Python/Go procesan la lógica pesada de IA y datos.

Persistencia Políglota: El uso combinado de AWS S3 (documentos), MongoDB (datos transaccionales), Qdrant (vectores) y Neo4j (grafos) demuestra un diseño maduro donde se usa "la herramienta correcta para cada trabajo".

🧠 Inteligencia Artificial (El Cerebro Legislativo)
Aquí reside la mayor innovación de Aerus. Al alejarse del RAG tradicional y evolucionar hacia una arquitectura CAG (Cognitive Augmented Generation - Concepto Q3 2025) con GraphRAG (Neo4j), el sistema logra algo crítico:

Comprensión Relacional: No solo busca texto (vectores), entiende la relación entre una normativa y un documento específico (grafo).

Especialización: Entrenado con el Decreto 44 y normativa vigente, además de guias de elaboración de documentos y plantillas por defecto como IRL , MIPER o ART. la IA no "alucina", sino que actúa como un asistente prevencionista y legal experto.

Optimización: El uso de chunks asíncronos asegura que la generación de documentos complejos no congele la experiencia del usuario y acelera la carga de documentos versionados.

⛓️ Web3 y Trazabilidad (Confianza)
Solidity + Hardhat (Ethereum Emulado): Implementar lógica de contratos inteligentes para la trazabilidad documental es un acierto para auditorías inmutables.

Nota: El uso de Hardhat sugiere un entorno controlado de alto rendimiento. Esto asegura que la "verdad" de la obra no pueda ser alterada retroactivamente.

----------------

Aerus es un sistema "State-of-the-Art" que supera a los gestores documentales tradicionales de la construcción. No se limita a almacenar PDFs; entiende el contenido de los documentos gracias a su arquitectura de Grafos + Vectores y asegura la validez de los mismos mediante Blockchain.

Es una herramienta que no solo digitaliza la obra, sino que blindan legal y operacionalmente a la empresa constructora y a sus contratistas.

Estado Inicial: Wireframe y planificación con apoyo de integrante (Prevencionista Riesgo)

Estado de Proyecto: Desarrollo 100% Prototipo funcional , 80% api desarrolladas, Arquitectura IA CAG (Cognite Augmentative Generation - Completa y 4 Documentos cargados de decreto 44, 33,18)


-------

EQUIPO KRIVIA : 
- Lider Proyecto - Arquitecto Soluciones IA / Mobile (Rodrigo Tobar)
- Arquitecto IA     (Arturo Linares)
- Arquitecto Blockchain - (Jerman Espindola)
- Prevencionista de Riesgo - (Alex Pereira)
- Datascience - Negocio - (Percy Salcedo)

