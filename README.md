# FisioVR 🖐️🥽

Aplicación de rehabilitación física en VR para extremidad superior, con clasificación de movimientos por Machine Learning. Desarrollada para Meta Quest 3 con Unity.

**Autor:** Kevin García

## Demo
<img width="501" height="412" alt="menu" src="https://github.com/user-attachments/assets/ce8e6255-2dc4-44db-9a85-065b3b571501" />
<img width="507" height="412" alt="ejercicio" src="https://github.com/user-attachments/assets/ec49393c-eb58-44a8-a926-4179aee6e679" />



## Qué hace
- 8 ejercicios de rehabilitación basados en protocolos clínicos reales
- Avatar 3D que guía y corrige el movimiento en tiempo real
- Feedback visual, auditivo y del avatar según la calidad del movimiento
- Clasificador SVM (kernel RBF) que evalúa el movimiento en tiempo real
- Historial de progreso del paciente (JSON + dashboard HTML)

## Stack

Unity 6000.0.34f1 · Meta Quest 3 · OVRSkeleton/OVRHand · Blender + Mixamo · SVM (C# nativo) · Python/scikit-learn

## Resultados del modelo

- 81.6% accuracy / 84.8% F1-score (validación cruzada 5-fold)
- Entrenado con ~96,000 frames de movimiento

## Instalación

```bash
git clone https://github.com/TU_USUARIO/VR-Physical-Therapy-Assistant.git
```

Abrir en Unity Hub (6000.0.34f1+), conectar el Quest 3 vía Quest Link o hacer build directo al dispositivo.
## Proyecto completo

El repositorio incluye el código fuente completo. Los assets pesados de audio y entorno 3D (Sketchfab), por límites de tamaño de GitHub, están disponibles en:

📦 https://drive.google.com/file/d/1FygtKoeRGfYo8SwWfxxgO_g0ewxaFlgq/view?usp=sharing

