# Urban Import AI - Fast Prompting

## Descripción del proyecto

Urban Import AI es una prueba de concepto (POC) que explora el uso
de técnicas de Fast Prompting para mejorar la calidad, claridad y
consistencia de las respuestas de un asistente virtual aplicado a
consultas de clientes.

El proyecto forma parte de una propuesta de implementación de
inteligencia artificial orientada a una empresa de importación.

---

## Problema

Los clientes de una empresa de importación pueden realizar consultas
sobre productos, disponibilidad, precios y características.

Responder estas consultas de forma consistente puede resultar
complicado cuando las instrucciones proporcionadas a un modelo de
inteligencia artificial son demasiado generales.

Un prompt poco estructurado puede generar respuestas ambiguas,
información innecesaria o incluso información que no fue proporcionada.

Por este motivo, el proyecto analiza cómo mejorar las instrucciones
mediante técnicas de prompting.

---

## Objetivo general

Desarrollar una prueba de concepto de Urban Import AI utilizando
técnicas de Fast Prompting para mejorar la calidad, claridad y
consistencia de las respuestas generadas por un asistente de
inteligencia artificial.

### Objetivos específicos

- Diseñar un prompt básico.
- Diseñar un prompt optimizado.
- Comparar ambas estrategias.
- Mejorar la claridad de las respuestas.
- Reducir la posibilidad de información inventada.
- Analizar la eficiencia de las consultas.
- Crear una estructura de prompt reutilizable.
- Incorporar interacción con consultas de clientes.

---

## Metodología

La POC se desarrolla mediante una comparación entre diferentes
configuraciones de prompts.

Primero se construye un prompt básico con instrucciones generales.

Luego se desarrolla un prompt optimizado incorporando:

- Definición de rol.
- Objetivo específico.
- Contexto.
- Reglas.
- Restricciones.
- Formato de respuesta.
- Reutilización de la estructura.

Finalmente se comparan ambas propuestas considerando claridad,
estructura, control de información y eficiencia.

---

## Fast Prompting

Las principales técnicas utilizadas en el proyecto son:

### Definición de rol

Se establece que el modelo actúa como asistente virtual de
Urban Import AI.

### Definición del objetivo

Se especifica qué debe lograr el modelo con cada consulta.

### Instrucciones específicas

Se establecen reglas concretas para orientar la respuesta.

### Restricciones

Se indica al modelo que no debe inventar precios, stock o
características que no hayan sido proporcionados.

### Formato de salida

Se define una estructura esperada para las respuestas.

### Reutilización

Se desarrolla una función que permite utilizar la misma estructura
para diferentes consultas.

---

## Implementación

La implementación se realiza utilizando Python y Jupyter Notebook.

La notebook contiene:

1. Presentación del problema.
2. Prompt básico.
3. Prompt optimizado.
4. Comparación.
5. Análisis de eficiencia.
6. Simulación de consultas.
7. Función reutilizable para construir prompts.
8. Resultados.
9. Conclusiones.

La implementación está preparada para conectarse posteriormente a una
API de modelos de lenguaje.

---

## Eficiencia y costos

Una de las consideraciones principales del proyecto es minimizar las
consultas innecesarias a la API.

La estrategia propuesta consiste en concentrar las instrucciones
necesarias dentro de un único prompt estructurado.

De esta forma se busca mejorar la calidad de las respuestas sin
aumentar innecesariamente la cantidad de consultas realizadas.

---

## Tecnologías

- Python
- Jupyter Notebook
- OpenAI API
- Fast Prompting
- GitHub

---

## Estructura del proyecto

```text
Urban-Import-AI/
│
├── README.md
├── Urban_Import_AI_Fast_Prompting.ipynb
├── requirements.txt
└── .gitignore