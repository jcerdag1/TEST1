# Imágenes Buenas y Malas

Este repositorio contiene una colección de imágenes clasificadas en dos categorías: "buenas" y "malas". Además, incluye un archivo JSON que lista las imágenes en cada categoría.

## Estructura del Proyecto

La estructura del proyecto es la siguiente:
- **buenas/**: Contiene las imágenes clasificadas como buenas.
- **malas/**: Contiene las imágenes clasificadas como malas.
- **data.json**: Archivo JSON que lista las imágenes en cada categoría.
- **README.md**: Archivo con la descripción del proyecto.
- **.gitignore**: Archivo que especifica qué archivos o directorios deben ser ignorados por Git.

## Archivo JSON

El archivo `data.json` tiene la siguiente estructura:

```json
{
  "buenas": [
    "buenas/imagen1.jpg",
    "buenas/imagen2.jpg"
  ],
  "malas": [
    "malas/imagen1.jpg",
    "malas/imagen2.jpg"
  ]
}
