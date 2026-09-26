# Urban Import AI - Fast Prompting

## Descripción del proyecto

Urban Import AI es una prueba de concepto (POC) que explora el uso de
técnicas de Fast Prompting para mejorar la calidad, claridad y
consistencia de las respuestas de un asistente virtual aplicado a
consultas de clientes.

El proyecto forma parte de una propuesta de implementación de
inteligencia artificial orientada a una empresa de importación.

La propuesta combina dos aplicaciones de inteligencia artificial:

- Generación de texto mediante prompts estructurados.
- Generación de imágenes a partir de instrucciones escritas.

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
mediante técnicas de Fast Prompting y cómo complementar las respuestas
textuales con contenido visual generado mediante inteligencia artificial.

---

## Objetivo general

Desarrollar una prueba de concepto de Urban Import AI utilizando
técnicas de Fast Prompting para mejorar la calidad, claridad y
consistencia de las respuestas generadas por un asistente de
inteligencia artificial.

Además, se incorpora un modelo texto → imagen para demostrar cómo la
inteligencia artificial puede utilizarse para generar contenido visual
relacionado con los productos.

### Objetivos específicos

- Diseñar un prompt básico.
- Diseñar un prompt optimizado utilizando Fast Prompting.
- Comparar ambas estrategias.
- Mejorar la claridad de las respuestas.
- Reducir la posibilidad de información inventada.
- Analizar la eficiencia de las consultas.
- Medir el tamaño de los prompts mediante caracteres, palabras y tokens.
- Crear una estructura de prompt reutilizable.
- Simular consultas de clientes.
- Incorporar un modelo texto → imagen.
- Evaluar el resultado de la generación de imágenes.
- Analizar la viabilidad técnica de la propuesta.

---

## Reflexión sobre la Preentrega 1

En la Preentrega 1 se planteó el desarrollo de una propuesta de
inteligencia artificial orientada a responder consultas de clientes
de Urban Import AI.

A partir de esa propuesta inicial, el proyecto fue ampliado mediante
la aplicación de técnicas de Fast Prompting.

La principal mejora consiste en pasar de una instrucción general a una
estructura organizada que define el rol del asistente, el objetivo,
el contexto, las reglas, las restricciones y el formato esperado.

Esta estructura permite tener un mayor control sobre el comportamiento
esperado del modelo y reducir la posibilidad de generar información que
no haya sido proporcionada.

Además, la propuesta final incorpora una comparación entre prompts,
un análisis de eficiencia mediante caracteres, palabras y tokens, una
simulación de cantidad de consultas y una funcionalidad de generación
de imágenes.

---

## Viabilidad técnica

El proyecto es técnicamente viable porque utiliza herramientas
accesibles para desarrollar una prueba de concepto, principalmente
Python, Jupyter Notebook, Visual Studio Code, GitHub y herramientas de
inteligencia artificial para generación de texto e imágenes.

### Recursos disponibles

- Python para la implementación de la lógica.
- Jupyter Notebook para ejecutar y documentar las pruebas.
- Visual Studio Code como entorno de desarrollo.
- GitHub para almacenar y publicar el proyecto.
- Herramientas de inteligencia artificial para generación de texto e
  imágenes.
- La librería `tiktoken` para realizar una medición local de tokens.

### Estimación del tiempo de desarrollo

| Actividad | Tiempo estimado |
|---|---:|
| Análisis del problema | 1 hora |
| Diseño de prompts | 2 horas |
| Desarrollo de la simulación | 2 horas |
| Pruebas y comparación | 1 hora |
| Generación de imagen | 1 hora |
| Documentación y README | 2 horas |
| Revisión final | 1 hora |
| **Total estimado** | **10 horas** |

Estos valores representan una estimación para una prueba de concepto
académica y pueden variar según la experiencia del desarrollador y las
herramientas utilizadas.

### Riesgos y mitigación

Entre los principales riesgos se encuentran las respuestas
incorrectas, la generación de información no proporcionada, las
limitaciones de herramientas gratuitas, los posibles costos de una
API y los errores de configuración.

Para reducir estos riesgos se utilizan prompts estructurados,
restricciones explícitas, datos controlados, pruebas comparativas y
mediciones locales que no requieren llamadas a una API.

---

## Metodología

La POC se desarrolla mediante las siguientes etapas:

1. Definición del problema.
2. Diseño de un prompt básico.
3. Diseño de un prompt optimizado.
4. Aplicación de técnicas de Fast Prompting.
5. Comparación de ambas estrategias.
6. Simulación de consultas.
7. Medición del tamaño de los prompts.
8. Medición local de tokens.
9. Generación de una imagen mediante un modelo texto → imagen.
10. Evaluación de los resultados.
11. Análisis de costos y eficiencia.
12. Elaboración de conclusiones.

---

## Fast Prompting

Las principales técnicas utilizadas en el proyecto son:

### Definición de rol

Se establece que el modelo actúa como asistente virtual de
Urban Import AI.

### Definición del objetivo

Se especifica qué debe lograr el modelo con cada consulta.

### Contexto

Se proporciona información sobre la empresa, los productos y el tipo
de consultas que puede realizar un cliente.

### Instrucciones específicas

Se establecen reglas concretas para orientar la respuesta.

### Restricciones

Se indica al modelo que no debe inventar precios, stock o
características que no hayan sido proporcionados.

### Formato de salida

Se define una estructura esperada para las respuestas.

### Reutilización

La estructura del prompt puede reutilizarse para diferentes consultas
sin tener que construir una instrucción completamente nueva.

---

## Implementación

La implementación se realiza utilizando Python y Jupyter Notebook.

La notebook contiene:

1. Presentación del problema.
2. Viabilidad técnica.
3. Objetivos.
4. Metodología.
5. Herramientas y tecnologías.
6. Prompt básico.
7. Prompt optimizado.
8. Simulación de consultas.
9. Comparación de estrategias.
10. Evaluación de la POC.
11. Medición del tamaño de los prompts.
12. Medición de tokens.
13. Generación de imágenes mediante IA.
14. Evaluación del resultado visual.
15. Análisis de costos y optimización.
16. Conclusiones.
17. Trabajo futuro.

La implementación utiliza una simulación local para demostrar el
funcionamiento de la POC sin realizar llamadas innecesarias a una API.

---

## Análisis de eficiencia y costos

Uno de los objetivos del proyecto es analizar la eficiencia de
diferentes estrategias de prompting.

Para realizar una comparación cuantitativa se midieron los prompts
mediante caracteres, palabras y tokens.

Los resultados obtenidos fueron:

| Medición | Prompt básico | Prompt optimizado |
|---|---:|---:|
| Tokens | 34 | 156 |

La diferencia entre ambos prompts es de 122 tokens.

El prompt optimizado utiliza más tokens porque incorpora información
adicional como el rol del asistente, objetivo, contexto, reglas,
restricciones y formato de respuesta.

Esto demuestra que optimizar un prompt no significa necesariamente
hacerlo más corto. El objetivo es proporcionar instrucciones claras y
estructuradas que permitan controlar mejor el comportamiento esperado
del modelo.

También se realizó una simulación de cantidad de consultas:

| Estrategia | Consultas |
|---|---:|
| Prompt básico | 3 |
| Prompt optimizado | 1 |

La simulación muestra una reducción de 2 consultas en este escenario.

Los valores de consultas corresponden a una simulación de la POC y no
a llamadas reales a una API.

La medición de tokens se realizó localmente mediante la librería
`tiktoken`, sin generar llamadas ni costos de API.

---

## Generación de imágenes mediante IA

Como complemento al modelo texto → texto, el proyecto incorpora un
modelo texto → imagen.

Para la demostración se utilizó como ejemplo el producto:

**Auriculares Bluetooth Urban X1**

El prompt utilizado describe el producto, el estilo visual, la
iluminación, la composición y el objetivo comercial de la imagen.

El resultado obtenido permite demostrar cómo la inteligencia artificial
puede utilizarse para generar contenido visual destinado a una tienda
online.

La imagen generada se encuentra dentro de la carpeta `images` del
proyecto.

---

## Resultados

La comparación realizada permitió observar diferencias entre una
instrucción básica y una estructura de prompt optimizada.

El prompt básico utilizó 34 tokens, mientras que el prompt optimizado
utilizó 156 tokens, presentando una diferencia de 122 tokens.

El prompt optimizado incorpora:

- Rol.
- Objetivo.
- Contexto.
- Reglas.
- Restricciones.
- Formato de respuesta.

Esto proporciona un mayor control sobre el comportamiento esperado del
asistente.

Además, la simulación realizada planteó una diferencia entre 3
consultas para la estrategia básica y 1 consulta para la estrategia
optimizada.

Esta reducción corresponde a un escenario simulado y no a llamadas
reales a una API.

La generación de imágenes amplía la propuesta original al incorporar
una segunda aplicación de inteligencia artificial: la creación de
contenido visual a partir de texto.

---

## Conclusiones

El desarrollo de esta POC permitió aplicar técnicas de Fast Prompting
a un caso de uso concreto: la atención de consultas de clientes de
Urban Import AI.

La comparación entre un prompt básico y uno optimizado demuestra la
importancia de estructurar correctamente las instrucciones.

La utilización de roles, contexto, objetivos, restricciones y formato
esperado permite establecer un comportamiento más controlado y
consistente.

La medición realizada permitió comprobar que el prompt básico utiliza
34 tokens, mientras que el prompt optimizado utiliza 156 tokens.

Esto demuestra que optimizar un prompt no significa necesariamente
utilizar menos tokens, sino utilizar instrucciones estructuradas para
mejorar el control y la calidad esperada de las respuestas.

La simulación de consultas permitió analizar cómo una estrategia
optimizada podría reducir interacciones innecesarias. Sin embargo,
estos valores deberán comprobarse mediante llamadas reales a una API
en una implementación futura.

La incorporación de un modelo texto → imagen permite ampliar la
propuesta hacia la generación de contenido visual para productos.

---

## Trabajo futuro

Como posibles mejoras del proyecto se plantean:

1. Conectar la notebook con un modelo de IA mediante API.
2. Incorporar una interfaz interactiva para que el usuario ingrese
   consultas.
3. Agregar una base de datos de productos.
4. Incorporar información sobre stock y precios en tiempo real.
5. Comparar diferentes modelos y estrategias de prompting.
6. Medir tiempo de respuesta y costos reales mediante una API.
7. Incorporar un sistema de evaluación automática de respuestas.
8. Ampliar la generación de contenido visual para diferentes productos.

---

## Tecnologías

- Python
- Jupyter Notebook
- Visual Studio Code
- GitHub
- Modelos de inteligencia artificial
- Fast Prompting
- Generación de texto
- Generación de imágenes
- tiktoken

---

## Estructura del proyecto

```text
Urban-Import-AI-Fast-Prompting/

│
├── images/
│   └── urban_x1_generada.png
│
├── README.md
├── Urban_Import_AI_Fast_Prompting.ipynb
├── requirements.txt
└── .gitignore