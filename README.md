🎓 FacultadAuto: Gestión Académica Inteligente con n8n e IA
Este proyecto es un ecosistema de automatización diseñado para centralizar y optimizar la vida universitaria. Utiliza n8n como orquestador principal para integrar herramientas de Google Suite con modelos avanzados de Inteligencia Artificial, permitiendo una gestión proactiva de exámenes y materiales de estudio.

🛠️ Funcionalidades Principales
El flujo se divide en tres módulos estratégicos:

1. Control de Exámenes y Notificaciones
Registro Centralizado: Permite dar de alta nuevos exámenes mediante formularios, guardando la información en Google Sheets.

Alertas Inteligentes: Un proceso diario a las 08:00 AM filtra los exámenes próximos y envía recordatorios automáticos vía Gmail cuando faltan 3 días para la fecha.

Confirmaciones Visuales: Al registrar un examen, el sistema envía un correo con un diseño HTML confirmando los datos ingresados.

2. Generador Automático de Cronogramas
Procesamiento de PDF: Al subir el programa de una materia a una carpeta de Google Drive, el sistema extrae el contenido automáticamente.

Análisis con IA: Utiliza OpenAI (GPT-4o-mini) para analizar las unidades temáticas y la bibliografía, diseñando un plan de estudio semanal estructurado.

Salida Documentada: Crea y organiza el cronograma final en un Google Doc dentro de una carpeta específica para cada materia.

3. Asistente Académico Multimodal
Modo QA (Preguntas y Respuestas): Un agente de chat que permite practicar conceptos específicos de una materia, evaluando las respuestas del usuario y brindando feedback.

Planificador de Trabajos Grupales: Dado un tema y la cantidad de participantes, la IA propone un reparto equitativo de tareas y un cronograma de entregas.

🧰 Stack Tecnológico
n8n: Orquestación de flujos de trabajo y lógica de nodos.

OpenAI (GPT-4o-mini): Procesamiento de lenguaje natural y agentes inteligentes.

Google Workspace: Google Sheets, Drive, Docs y Gmail para la persistencia y comunicación.

JavaScript: Lógica personalizada en nodos de código para el filtrado dinámico de fechas.
