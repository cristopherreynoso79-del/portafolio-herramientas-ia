# Modelo

**Identificador:** `Jordo23/vehicle-classifier`  
**Model Card:** [Jordo23/vehicle-classifier en Hugging Face](https://huggingface.co/Jordo23/vehicle-classifier)

| Dato | Descripción |
|---|---|
| Tarea | Clasificación de imágenes (`image-classification`) |
| Arquitectura | EfficientNet-B4, mediante `timm` |
| Entrada | Fotografía RGB redimensionada a 380 × 380 píxeles |
| Salida | Clasificación entre 8,949 combinaciones de marca, modelo y año; consulta de las cinco opciones mejor puntuadas |
| Licencia declarada | MIT |
| Limitaciones declaradas | Oclusiones, ángulos inusuales y vehículos raros, antiguos o modificados; el color se procesa por separado |

La Model Card declara aproximadamente 19 millones de parámetros. La estimación con la capa de salida de 8,949 clases es de unos 33.6 millones; el cálculo y sus límites se explican en [Viabilidad de hardware](README.md#3-viabilidad-de-hardware).

Equipo responsable: [Equipo](Equipo.md). Seguimiento: [Bitácora](Bit%C3%A1cora.md).
