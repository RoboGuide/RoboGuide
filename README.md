# Roboguide

## 🤖 Descripción del proyecto

Roboguide es un robot guía autónomo diseñado para asistir a personas en la navegación dentro del segundo piso de la Facultad de Ingeniería de la Universidad de Antioquia, específicamente entre los bloques 18, 20 y 21. Este robot puede interactuar con los usuarios y guiarlos eficientemente hacia su destino, combinando tecnologías como percepción multimodal, algoritmos de inteligencia artificial y sistemas embebidos.

---

## 🎯 Motivación

La orientación en universidades puede ser complicada para estudiantes y visitantes debido a señalización deficiente, mapas desactualizados o escasa disponibilidad de personal. Roboguide nace como una solución tecnológica que mejora la experiencia de navegación en campus universitarios.

Además de facilitar la movilidad, este proyecto busca despertar el interés en temas como la robótica, machine learning y electrónica, contribuyendo al entorno académico desde un enfoque práctico, innovador y de alto impacto.

---

## ✅ Requisitos funcionales

- **Movilidad autónoma**: El robot se desplaza de forma autónoma sin intervención del operador.
- **Trazado de rutas**: El robot calcula rutas óptimas según el destino ingresado por el usuario.
- **Interacción**: El usuario interactúa mediante una pantalla led y botones físicos.
- **Detección de obstáculos**: El robot detecta y evita obstáculos en su camino.
- **Control energético**: Monitoreo y gestión eficiente de la batería.
- **Comunicación multilingüe**: El robot se comunica en español o inglés.
- **Localización y mapeo**: El robot determina su posición y actualiza su mapa en tiempo real.

---

## 🧩 Requisitos no funcionales

- **Fiabilidad**: precisión en la navegación y bajo margen de error.
- **Control de motores**: correcciones automáticas de dirección.
- **Mantenimiento**: diseño modular para facilitar ajustes o reparaciones.
- **Portabilidad**: tamaño y peso adecuados para espacios interiores.
- **Escalabilidad**: facilidad para añadir nuevas funcionalidades.
- **Robustez**: operación en entornos ruidosos o con poca iluminación.
- **Duración de batería**: mínimo 12 horas de funcionamiento autónomo.
- **Estética**: diseño visualmente atractivo y amigable para el usuario.

---

## 🛠️ Materiales y herramientas

- **Single Board Computer** (procesamiento central).
- **Motores y llantas** (movilidad).
- **Pantalla** (interacción usuario).
- **Sensores de proximidad, IMU y cámara Kinect** (detección y navegación).
- **AprilTags** (referencias visuales para localización).
- **Buzzer** (alertas sonoras en caminos bloqueados).
- **Batería y porta pilas** (fuente de energía).
- **Botones físicos** (entrada del usuario).

---

## 📊 Diagrama de bloques

El sistema se compone de los siguientes módulos principales:

- **Módulo de percepción**: Sensores, cámara, IMU, LiDAR (opcional).
- **Módulo de decisión**: Procesamiento con machine learning y lógica de navegación.
- **Módulo de acción**: Control de motores, respuesta a obstáculos.
- **Módulo de interfaz**: Pantalla y botones para interacción con el usuario.
- **Módulo energético**: Batería, regulador de voltaje y monitoreo.

---

## 📈 Resultados esperados

- Construcción de un prototipo funcional y evaluado en escenarios reales.
- Mejora en la orientación de visitantes en los bloques 18, 20 y 21.
- Interacción efectiva con usuarios mediante una interfaz clara y sencilla.
- Integración de algoritmos de navegación, SLAM y percepción multimodal.
- Operación eficiente con bajo consumo energético.
- Difusión del proyecto en eventos académicos y generación de ideas para iteraciones futuras.
