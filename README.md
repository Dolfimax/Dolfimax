# Adolfo Dario Saavedra

**Licenciado en Inteligencia Artificial y Robótica**  
**Edge AI • IoT Industrial • Visión Artificial • Automatización • Robótica Aplicada**

Soy profesional técnico con más de 20 años de experiencia en entornos industriales, mantenimiento eléctrico, supervisión técnica y resolución de problemas en campo.

Mi diferencial es combinar experiencia real en operaciones industriales con herramientas modernas de inteligencia artificial, automatización, IoT, visión artificial y robótica.

Actualmente estoy desarrollando **Sur Robotics & AI**, una propuesta de consultoría orientada a crear soluciones aplicadas de **Edge AI, automatización y robótica desde la Patagonia**, con foco en empresas, pymes, emprendimientos tecnológicos e industrias que necesitan transformar ideas en prototipos funcionales.

---

Además, investigo la adaptación de modelos de clasificación de sonidos cardíacos para un dispositivo de bajo costo, con foco en sistemas embebidos y Edge AI.

## Qué hago

Trabajo en el diseño y desarrollo de soluciones aplicadas para:

- Edge AI en entornos industriales
- IoT industrial con sensores, MQTT, bases de datos y Docker
- Visión artificial con Python, OpenCV y modelos livianos
- Automatización de procesos técnicos
- Robótica aplicada a problemas reales
- Agentes IA para asistencia técnica y documentación industrial
- Prototipos tecnológicos para validación rápida
- Sistemas de monitoreo, diagnóstico y mantenimiento inteligente

---

## Enfoque profesional

Mi objetivo es ayudar a empresas y equipos técnicos a pasar de una necesidad concreta a una solución funcional, comenzando por pilotos simples, medibles y de bajo riesgo.

Creo en una inteligencia artificial aplicada, cercana al territorio y útil para resolver problemas reales de producción, mantenimiento, seguridad, operación y eficiencia.

Desde Neuquén, Comodoro Rivadavia y la Patagonia, busco posicionarme como referente regional en el desarrollo e implementación de soluciones de **Edge AI, IoT industrial y robótica aplicada**.

---

## Áreas de interés

- Edge AI industrial
- TinyML
- Procesamiento de señales y clasificación de sonidos cardíacos
- IoT y comunicaciones industriales
- Automatización y control
- Visión artificial
- Robótica móvil
- Agentes inteligentes
- Gemelos digitales
- Mantenimiento predictivo y prescriptivo
- IA aplicada a seguridad industrial

---

## Tecnologías y herramientas

- Python
- OpenCV
- Docker
- MQTT
- PostgreSQL
- MySQL
- ESP32
- HTML, CSS y JavaScript
- Linux
- GitHub
- Robótica aplicada
- Sistemas embebidos
- Plataformas de IA generativa

---

## Investigación actual: dispositivo de bajo costo para análisis de sonidos cardíacos

Junto con **Luciano Pescio**, trabajo en el estudio de factibilidad y desarrollo de un **dispositivo de bajo costo para analizar sonidos cardíacos mediante inteligencia artificial**, explorando su implementación en un **ESP32-S3 con PSRAM**.

Esta línea conecta procesamiento de señales, aprendizaje profundo y sistemas embebidos con mi interés por la **Edge AI aplicada a problemas reales**.

**Repositorio:** [Dolfimax/AutomaticHeartSoundClassification](https://github.com/Dolfimax/AutomaticHeartSoundClassification)  
**Desarrollo experimental:** [rama investigacion-docker](https://github.com/Dolfimax/AutomaticHeartSoundClassification/tree/investigacion-docker)

### Antecedentes y contribución actual

El proyecto parte de un fork de [SiyuLou/AutomaticHeartSoundClassification](https://github.com/SiyuLou/AutomaticHeartSoundClassification) y utiliza su arquitectura `simple_cnn`. Los datos empleados proceden del [PhysioNet/Computing in Cardiology Challenge 2016](https://physionet.org/content/challenge-2016/1.0.0/). El framework de base utiliza [pytorch-template](https://github.com/victoresque/pytorch-template).

La arquitectura y la implementación de base, así como los resultados del README original, son antecedentes preexistentes y corresponden a sus respectivos autores. El conjunto de datos también conserva su autoría y atribución originales.

**Nuestra contribución se centra en la experimentación, adaptación y evaluación de esa base para un dispositivo económico**, incluyendo:

- Preparación de un entorno de investigación reproducible con Docker.
- Entrenamiento y evaluación experimental sobre el subconjunto `training-a`, con comparación de estrategias de ponderación de clases.
- Caracterización de parámetros, activaciones y tiempos de inferencia en CPU.
- Exportación a ONNX y verificación de equivalencia con PyTorch sobre 41 grabaciones de validación.
- Conversión y cuantización preliminar a INT8 mediante ESP-PPQ, con generación de un modelo ESP-DL orientado al ESP32-S3.

### Estado del desarrollo

La documentación registra avances en la caracterización computacional y la preparación del modelo para su eventual ejecución embebida. La equivalencia PyTorch–ONNX conservó las decisiones de clasificación en las 41 entradas evaluadas; este resultado mide concordancia entre implementaciones, no exactitud diagnóstica.

La siguiente etapa comprende validar el modelo cuantizado, comprobar su ejecución en el ESP32-S3 e integrar la adquisición y el procesamiento del audio, midiendo memoria, latencia, consumo energético y costo total del prototipo.

El proyecto se encuentra en **investigación exploratoria y factibilidad tecnológica**. Los resultados actuales no constituyen validación clínica ni demuestran capacidad de diagnóstico de patologías específicas. La independencia entre pacientes de las particiones de datos permanece pendiente de verificación.

**Documentación:**

- [Registro de experimentos](https://github.com/Dolfimax/AutomaticHeartSoundClassification/blob/investigacion-docker/experimentos/documentacion/registro_experimentos.md)
- [Caracterización computacional y preparación para el dispositivo](https://github.com/Dolfimax/AutomaticHeartSoundClassification/blob/investigacion-docker/experimentos/documentacion/rendimiento_dispositivo.md)

---

## Proyectos destacados

### Sur Robotics & AI

Consultora orientada a Edge AI, automatización, IoT industrial y robótica aplicada desde la Patagonia.

### Sistema robótico autónomo para polígono de tiro

Proyecto de robótica aplicada con control remoto, visión artificial y puntuación automática.  
Integra robótica móvil, comunicación inalámbrica, software web y procesamiento de imágenes.

### Stack IoT industrial

Arquitectura base para prototipos industriales con MQTT, Docker, PostgreSQL, Nginx y servicios web.

### Visión artificial aplicada

Prototipos con Python y OpenCV para detección, inspección, análisis visual y clasificación de imágenes.

---

## Qué puedo aportar

- Experiencia técnica de campo en industria real
- Capacidad para traducir problemas operativos en soluciones tecnológicas
- Desarrollo de prototipos funcionales
- Integración entre hardware, software, datos e IA
- Visión práctica para implementar tecnología en entornos productivos
- Formación en inteligencia artificial, robótica y automatización

---

## Contacto

**Nombre:** Adolfo Dario Saavedra  
**Ubicación:** Patagonia Argentina  
**Área de trabajo:** Edge AI, IoT industrial, visión artificial, automatización y robótica aplicada  

**LinkedIn:** https://www.linkedin.com/in/adolfo-dario-saavedra/  
**Sitio web:** https://surroboticsai.net/  
**Email:** adolfodsaavedra@gmail.com
---

> Desarrollo soluciones de inteligencia artificial aplicada, automatización y robótica para resolver problemas reales en entornos productivos.
