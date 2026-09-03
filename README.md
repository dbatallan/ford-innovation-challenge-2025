# Ford Innovation Challenge - Features Edition 2025
## Sistema de Monitoreo de Carga y Estabilidad: "Stability Check" / "Pesos Pesados"

Este repositorio contiene la arquitectura de software, modelado funcional, análisis de riesgos y activos de diseño 3D para la propuesta de ingeniería **Stability Check**, desarrollada para la nueva línea de pickups Ford en el marco del **Ford Innovation Challenge 2025**[cite: 1, 3].

---

## 📄 Entregables y Documentación Oficial (`/docs`)

Los documentos finales presentados para la evaluación del desafío se encuentran disponibles en la carpeta [`/docs`](./docs/):

* 📑 [**Entregables - Pesos Pesados.pdf**](./docs/Entregables%20-%20Pesos%20Pesados.pdf): Documento integral con los Boundary Diagrams, Descomposición Sistemática, Máquina de Estados y Diagramas de Secuencia UML[cite: 3].
* 📑 [**DFMEA - Pesos Pesados.pdf**](./docs/DFMEA%20-%20Pesos%20Pesados.pdf): Matriz completa de Análisis de Modo y Efectos de Falla, incluyendo prevención, detección y mapeo de señales/tests[cite: 2].

---

## 🛠️ Arquitectura e Ingeniería de Sistemas

El proyecto incluye la documentación técnica exigida por los estándares de diseño funcional[cite: 1]:

* **Boundary Diagrams:** Diagramas de entradas/salidas y fronteras del sistema[cite: 1, 3].
* **Diagrama de Descomposición Sistemática:** Estructura modular e interacción entre componentes (Sistema de Diagnóstico, Caja y Peso, HMI y Audio)[cite: 1, 2, 3].
* **Máquina de Estados (State Machine):** Modelado del comportamiento del sistema bajo las condiciones `Feature Apagado` y `Feature Encendido` (Diagnóstico, Calibración, Estado Nominal y disparadores de Alerta por Sobrepeso, Desplazamiento y Caída)[cite: 1, 3].
* **Diagramas de Secuencia (UML):** Flujo temporal de mensajes de señal (`_rqst`, `_st`) entre subsistemas en tiempo de ejecución[cite: 1, 2, 3].
* **DFMEA Simplificado:** Análisis de modos de falla, sus efectos, causas root y métodos de prevención/detección[cite: 1, 2].

---

## 🎨 Diseños 3D y Recursos Visuales (`/assets`)

La carpeta [`/3D Models`](<./assets/CAD_models/3D Models/>) contiene las representaciones físicas y prototipos conceptuales del sistema:

* **Modelos OpenSCAD (`.scad`):** Definición paramétrica mediante código de los componentes visuales e interfaces físicas (divisores, estructuras y caja).
* **Renderizado y Animación:** Elementos de apoyo gráfico generados con Blender y Python para las demostraciones técnicas del video conceptual[cite: 1].

---

## 👥 Equipo
* David Batallan[cite: 3]
* Sebastián García[cite: 3]
* Carlos Porras[cite: 3]