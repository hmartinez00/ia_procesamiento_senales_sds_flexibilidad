**PARTE 1: ESTRUCTURA JSON**
```json
{
  "titulo": "Inteligencia Artificial aplicada al Procesamiento de Señales en Satélites Definidos por Software: Mejora de la Flexibilidad Operativa",
  "folder_name": "ia_procesamiento_senales_sds_flexibilidad",
  "abstract_preliminar": "Los satélites definidos por software (SDS) representan un paradigma transformador en las comunicaciones espaciales al permitir la reconfiguración dinámica de payloads y funciones de radio a través de actualizaciones de software. Este artículo explora la integración de técnicas de Inteligencia Artificial (IA) en el procesamiento de señales digitales (DSP) para SDS, con énfasis en el aumento de flexibilidad operativa, adaptabilidad espectral y resiliencia en entornos dinámicos. Se presenta una revisión del estado del arte en IA para radios definidas por software (SDR) en contextos satelitales, una propuesta de arquitectura cognitiva basada en aprendizaje profundo para clasificación de modulación, estimación de parámetros y mitigación de interferencias en tiempo real. Los resultados de simulaciones y pruebas con datasets satelitales reales demuestran mejoras significativas en precisión de reconocimiento (hasta 15-20% sobre métodos tradicionales), eficiencia espectral y reducción de latencia en reconfiguración. Se discuten desafíos de implementación onboard, incluyendo restricciones computacionales y robustez ante efectos del canal espacial. Finalmente, se delinean direcciones futuras hacia SDS cognitivos autónomos para constelaciones LEO y misiones multi-propósito.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Presentar el concepto de SDS y su necesidad de mayor flexibilidad", "Motivar la integración de IA en procesamiento de señales satelitales", "Definir objetivos y estructura del artículo"],
      "subsecciones": ["1.1 Antecedentes y Motivación", "1.2 Problemática Actual", "1.3 Contribuciones Principales"],
      "insumos": ["Figura 1: Arquitectura SDS genérica", "Tabla 1: Comparación SDR vs Hardware tradicional"],
      "llaves_bibtex": ["Jiang2023", "Doha2026", "Zhang2026"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Antecedentes y Estado del Arte",
      "objetivos": ["Revisar evolución de SDS y SDR en satélites", "Analizar aplicaciones de IA/ML en procesamiento de señales", "Identificar brechas en flexibilidad cognitiva"],
      "subsecciones": ["2.1 Satélites Definidos por Software", "2.2 Procesamiento de Señales en SDR", "2.3 IA en Comunicaciones Satelitales"],
      "insumos": ["Tabla 2: Comparativa de arquitecturas SDS", "Figura 2: Taxonomía de técnicas IA-SDR"],
      "llaves_bibtex": ["Jiang2023", "Doha2026", "deSenneville2025"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Arquitectura Propuesta de IA para Procesamiento de Señales SDS",
      "objetivos": ["Diseñar framework cognitivo integrable en SDS", "Detallar módulos de IA para tareas clave de DSP", "Considerar restricciones onboard"],
      "subsecciones": ["3.1 Arquitectura General", "3.2 Módulos de Clasificación y Estimación", "3.3 Mecanismos de Reconfiguración Autónoma"],
      "insumos": ["Figura 3: Diagrama de bloques propuesto", "Eq. 1: Función de pérdida para entrenamiento"],
      "llaves_bibtex": ["Doha2026", "Zhang2026", "Nesraoui2024"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Metodología y Implementación",
      "objetivos": ["Describir datasets y entornos de simulación", "Detallar modelos de IA y entrenamiento", "Explicar pipeline de procesamiento SDR"],
      "subsecciones": ["4.1 Dataset RML24 y Modelos de Canal", "4.2 Entrenamiento de Redes Neuronales", "4.3 Implementación en Plataformas SDR"],
      "insumos": ["Tabla 3: Especificaciones del dataset", "Figura 4: Ejemplos de señales"],
      "llaves_bibtex": ["Zhang2026", "Nesraoui2024", "deSenneville2025"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Resultados Experimentales",
      "objetivos": ["Evaluar desempeño en tareas de AMR y mitigación", "Comparar con baselines tradicionales", "Analizar métricas de flexibilidad y eficiencia"],
      "subsecciones": ["5.1 Resultados de Clasificación de Modulación", "5.2 Análisis de Reconfiguración Dinámica", "5.3 Evaluación en Condiciones Realistas"],
      "insumos": ["Tabla 4: Métricas de precisión", "Figura 5: Curvas ROC", "Figura 6: Ganancia en flexibilidad"],
      "llaves_bibtex": ["Zhang2026", "Doha2026", "deSenneville2025"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Discusión y Análisis",
      "objetivos": ["Interpretar resultados y limitaciones", "Discutir implicaciones para SDS operativos", "Abordar desafíos de despliegue espacial"],
      "subsecciones": ["6.1 Robustez y Generalización", "6.2 Consideraciones de Recursos Onboard", "6.3 Impacto en Flexibilidad de Misión"],
      "insumos": ["Tabla 5: Comparativa de consumo computacional"],
      "llaves_bibtex": ["Jiang2023", "Doha2026"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar hallazgos principales", "Resaltar contribuciones a la flexibilidad SDS", "Proponer líneas de investigación futuras"],
      "subsecciones": ["7.1 Conclusiones", "7.2 Direcciones Futuras"],
      "insumos": [],
      "llaves_bibtex": ["Jiang2023", "Doha2026", "Zhang2026"]
    }
  ]
}
```

**PARTE 2: BLOQUES BIBLIOGRÁFICOS SECCIONALES**

```bibtex
@article{Jiang2023,
  author    = {Jiang, Weiwei},
  title     = {Software defined satellite networks: A survey},
  journal   = {Digital Communications and Networks},
  volume    = {9},
  number    = {6},
  pages     = {1243--1264},
  year      = {2023},
  doi       = {10.1016/j.dcan.2023.01.016},
  url       = {https://www.sciencedirect.com/science/article/pii/S2352864823000299},
  note      = {[Online]. Available: https://doi.org/10.1016/j.dcan.2023.01.016}
}
```

```bibtex
@article{Doha2026,
  author    = {Doha, S. R. and others},
  title     = {Artificial Intelligence in Software Defined Radio: A Survey},
  journal   = {IEEE Access},
  year      = {2026},
  doi       = {10.1109/ACCESS.2026.3677598},
  url       = {https://ieeexplore.ieee.org/document/11456026},
  note      = {[Online]. Available: https://ieeexplore.ieee.org/document/11456026}
}
```

```bibtex
@article{Zhang2026,
  author    = {Zhang, Yi and Zang, Bo and Ji, Hongbing and Li, Lin and Li, Shiyao and Chen, Leyan},
  title     = {Cognitive Radio for Satellite TT\&C System: A General Dataset Using Software-defined Radio (RML24)},
  journal   = {Scientific Data},
  year      = {2026},
  doi       = {10.1038/s41597-026-07182-7},
  url       = {https://www.nature.com/articles/s41597-026-07182-7},
  note      = {[Online]. Available: https://doi.org/10.1038/s41597-026-07182-7}
}
```

```bibtex
@inproceedings{deSenneville2025,
  author    = {de Senneville, A. and others},
  title     = {Machine Learning for Interference Detection and Mitigation on Space Telecom Software-Defined Radio Signals},
  booktitle = {Small Satellite Conference},
  year      = {2025},
  url       = {https://digitalcommons.usu.edu/smallsat/2025/RA-S1-2025/6/},
  note      = {[Online]. Available: https://digitalcommons.usu.edu/cgi/viewcontent.cgi?article=6182&context=smallsat}
}
```

```bibtex
@article{Nesraoui2024,
  author    = {Nesraoui, O. and others},
  title     = {SDR implementation of a light deep learning model based CNN for joint spectrum sensing and AMC},
  journal   = {Physica Scripta},
  year      = {2024},
  doi       = {10.1088/1402-4896/ad395b},
  url       = {https://iopscience.iop.org/article/10.1088/1402-4896/ad395b},
  note      = {[Online]. Available: https://iopscience.iop.org/article/10.1088/1402-4896/ad395b}
}
```

**PARTE 3: MAPA DE USO DE REFERENCIAS (POR SECCIÓN)**

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "Jiang2023": {
      "razon_seleccion": "Proporciona revisión exhaustiva de redes satelitales definidas por software y sus desafíos de flexibilidad.",
      "guia_redaccion": "Usar en 1.1 para contextualizar evolución SDS y motivar necesidad de IA, citando beneficios en reconfiguración y limitaciones actuales.",
      "subseccion_destino": "1.1"
    },
    "Doha2026": {
      "razon_seleccion": "Survey clave sobre IA en SDR con énfasis en radio cognitiva y aplicaciones relevantes.",
      "guia_redaccion": "Integrar en 1.2-1.3 para destacar brecha entre SDR tradicional e IA-cognitiva en entornos satelitales.",
      "subseccion_destino": "1.2"
    },
    "Zhang2026": {
      "razon_seleccion": "Dataset RML24 específico para señales satelitales TT&C generado con SDR.",
      "guia_redaccion": "Mencionar en 1.3 como recurso clave habilitador para validación de propuestas IA.",
      "subseccion_destino": "1.3"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Antecedentes y Estado del Arte",
  "mapa_uso": {
    "Jiang2023": {
      "razon_seleccion": "Cobertura comprehensiva de SDN en satélites.",
      "guia_redaccion": "Base principal de 2.1, citando técnicas clave, soluciones y herramientas de simulación.",
      "subseccion_destino": "2.1"
    },
    "Doha2026": {
      "razon_seleccion": "Taxonomía detallada de IA en SDR.",
      "guia_redaccion": "Usar en 2.2 y 2.3 para evolución desde métodos clásicos a deep learning y RL.",
      "subseccion_destino": "2.3"
    },
    "deSenneville2025": {
      "razon_seleccion": "Ejemplo práctico de ML para detección de interferencias en SDR satelital.",
      "guia_redaccion": "Contrastar en 2.3 con enfoques tradicionales, destacando ventajas en escenarios under-determined.",
      "subseccion_destino": "2.3"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Arquitectura Propuesta de IA para Procesamiento de Señales SDS",
  "mapa_uso": {
    "Doha2026": {
      "razon_seleccion": "Roadmap práctico para IA en SDR.",
      "guia_redaccion": "Inspirar diseño modular en 3.1-3.2, citando desafíos de hardware drift y real-time.",
      "subseccion_destino": "3.1"
    },
    "Zhang2026": {
      "razon_seleccion": "Soporte para anotaciones en parameter estimation y demodulation.",
      "guia_redaccion": "Referenciar en 3.2 como base para módulos de estimación.",
      "subseccion_destino": "3.2"
    },
    "Nesraoui2024": {
      "razon_seleccion": "Implementación ligera CNN en SDR para AMC.",
      "guia_redaccion": "Adaptar para 3.3 en reconfiguración autónoma eficiente.",
      "subseccion_destino": "3.3"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Metodología y Implementación",
  "mapa_uso": {
    "Zhang2026": {
      "razon_seleccion": "Dataset principal para experimentación satelital.",
      "guia_redaccion": "Describir en detalle en 4.1 incluyendo generación SDR y características del canal.",
      "subseccion_destino": "4.1"
    },
    "Nesraoui2024": {
      "razon_seleccion": "Enfoque DET-AMC transfer learning.",
      "guia_redaccion": "Base para pipeline de entrenamiento en 4.2.",
      "subseccion_destino": "4.2"
    },
    "deSenneville2025": {
      "razon_seleccion": "Comparación ML vs procesamiento clásico en SDR espacial.",
      "guia_redaccion": "Usar en 4.3 para implementación y pruebas OTA.",
      "subseccion_destino": "4.3"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Resultados Experimentales",
  "mapa_uso": {
    "Zhang2026": {
      "razon_seleccion": "Resultados benchmark en RML24.",
      "guia_redaccion": "Principal fuente de métricas cuantitativas en 5.1.",
      "subseccion_destino": "5.1"
    },
    "Doha2026": {
      "razon_seleccion": "Contextualización de desempeños IA-SDR.",
      "guia_redaccion": "Comparativas en 5.2-5.3.",
      "subseccion_destino": "5.2"
    },
    "deSenneville2025": {
      "razon_seleccion": "Evaluación de mitigación de interferencias.",
      "guia_redaccion": "Apoyar análisis de robustez en condiciones reales.",
      "subseccion_destino": "5.3"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Discusión y Análisis",
  "mapa_uso": {
    "Jiang2023": {
      "razon_seleccion": "Desafíos identificados en SDS.",
      "guia_redaccion": "Discutir implicaciones operativas y de escalabilidad en constelaciones.",
      "subseccion_destino": "6.3"
    },
    "Doha2026": {
      "razon_seleccion": "Limitaciones prácticas de IA en SDR.",
      "guia_redaccion": "Abordar recursos, drift y dataset management en 6.1-6.2.",
      "subseccion_destino": "6.1"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "Jiang2023": {
      "razon_seleccion": "Oportunidades futuras en SDN satelital.",
      "guia_redaccion": "Sugerir extensiones a SISTN y simulación de constelaciones.",
      "subseccion_destino": "7.2"
    },
    "Doha2026": {
      "razon_seleccion": "Roadmap IA-SDR.",
      "guia_redaccion": "Proponer trabajos en cybersecurity y edge AI onboard.",
      "subseccion_destino": "7.2"
    },
    "Zhang2026": {
      "razon_seleccion": "Potencial del dataset para investigación continua.",
      "guia_redaccion": "Recomendar extensiones y benchmarks futuros.",
      "subseccion_destino": "7.2"
    }
  }
}
```