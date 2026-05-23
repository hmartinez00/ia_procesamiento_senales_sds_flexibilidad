**Title**: Inteligencia Artificial aplicada al Procesamiento de Señales en Satélites Definidos por Software: Mejora de la Flexibilidad Operativa

**Description**: Los satélites definidos por software (SDS) permiten la reconfiguración dinámica de sus payloads y funciones de radio mediante actualizaciones de software. Esta investigación explora la integración de técnicas de Inteligencia Artificial en el procesamiento de señales digitales (DSP) para SDS, con el fin de incrementar significativamente la flexibilidad operativa, la adaptabilidad espectral y la resiliencia en entornos dinámicos. Se propone una arquitectura cognitiva basada en aprendizaje profundo para clasificación de modulación, estimación de parámetros y mitigación de interferencias en tiempo real. Los resultados de simulaciones y pruebas con datasets satelitales reales (como RML24) demuestran mejoras en precisión de reconocimiento, eficiencia espectral y reducción de latencia en reconfiguración.

**General Objective**: Desarrollar e implementar un framework de Inteligencia Artificial para el procesamiento avanzado de señales en satélites definidos por software que incremente su flexibilidad operativa y capacidad cognitiva.

**Specific Objectives**: 
- Revisar el estado del arte en SDS, SDR y aplicaciones de IA en procesamiento de señales satelitales.
- Diseñar una arquitectura cognitiva modular integrable en plataformas SDS con restricciones computacionales onboard.
- Implementar y entrenar modelos de aprendizaje profundo para tareas clave de DSP (clasificación automática de modulación, estimación de parámetros y mitigación de interferencias).
- Evaluar el desempeño del framework propuesto mediante simulaciones y métricas cuantitativas en condiciones realistas de canal espacial.
- Analizar las implicaciones operativas, limitaciones y oportunidades de despliegue en constelaciones LEO y misiones multi-propósito.

**Justification**: La creciente complejidad de las misiones espaciales y la congestión del espectro requieren sistemas satelitales más adaptativos y autónomos. Los SDS tradicionales carecen de capacidades cognitivas para responder en tiempo real a interferencias, cambios de misión o degradaciones del canal. La integración de IA representa un avance técnico fundamental que mejora la eficiencia espectral, reduce costos operativos mediante reconfiguración remota y potencia aplicaciones críticas como comunicaciones de emergencia, observación terrestre y constelaciones de satélites. Socialmente, contribuye a una mayor accesibilidad de servicios espaciales y al avance de la soberanía tecnológica en el sector aeroespacial.

**Methodology**: Enfoque experimental-cuantitativo basado en simulación y validación con datos reales. Se utiliza una revisión sistemática del estado del arte, diseño de arquitectura cognitiva modular, desarrollo de modelos de deep learning (CNN, etc.), entrenamiento con datasets especializados (RML24), implementación en entornos SDR y evaluación comparativa contra baselines tradicionales mediante métricas de precisión, latencia, robustez y eficiencia computacional.

**Scope**: Desarrollo y validación en simulación/onboard de framework IA-DSP para SDS, enfocado en flexibilidad cognitiva y procesamiento de señales TT&C en entornos LEO (máximo 100 caracteres).

**Activities**: 
1. Revisión bibliográfica y análisis de estado del arte.
2. Diseño de la arquitectura cognitiva propuesta.
3. Adquisición y preparación de datasets satelitales.
4. Implementación, entrenamiento y optimización de modelos de IA.
5. Ejecución de experimentos y análisis de resultados.
6. Redacción de discusión, conclusiones y recomendaciones de trabajos futuros.

**Resources**: 
- Datasets: RML24 y modelos de canal espacial.
- Plataformas SDR (USRP u equivalentes).
- Herramientas: Python, TensorFlow/PyTorch, GNU Radio.
- Entornos de simulación satelital.
- Infraestructura computacional GPU para entrenamiento de modelos.

**Limitations**: Restricciones computacionales y energéticas de hardware onboard, disponibilidad limitada de datasets etiquetados en condiciones reales de órbita, efectos impredecibles del canal espacial (Doppler, fading), desafíos regulatorios para actualizaciones en vuelo y posibles limitaciones de generalización entre diferentes constelaciones.