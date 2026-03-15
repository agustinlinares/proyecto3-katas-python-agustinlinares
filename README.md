# Proyecto 3 — Katas de Python

Colección de katas desarrollada para el Máster.  
Este tercer proyecto consiste en completar, validar y entregar todos los ejercicios de Python que se plantean en el enunciado.

---

## Organización

- Todas las katas están en un único fichero: `katas.py`.
- Cada ejercicio se implementa como una función independiente (o clase), nombrada con el prefijo `kataXX_…` para mantener el orden del enunciado.
- El código (nombres de funciones, variables, etc.) está en español, y el enunciado original de cada ejercicio se conserva en español dentro del _docstring_ de cada función/clase.
- Se han agrupado mentalmente los ejercicios por tipo de concepto:
  - funciones básicas, `map`, `filter`, `reduce` y funciones `lambda`
  - condicionales y entrada por teclado
  - manejo de excepciones (incluyendo una excepción personalizada para listas vacías)
  - clases (`Arbol`, `UsuarioBanco`) con sus casos de uso
  - procesado de texto con funciones auxiliares y una función orquestadora (`procesar_texto`)
- Algunos ejercicios se han planteado como funciones puras (reciben datos y devuelven resultados) y otros como pequeños programas interactivos que usan `input()` cuando el enunciado lo pide explícitamente.
- Para `reduce` se utiliza el módulo estándar `functools`, cumpliendo el requisito de uso de módulos.

---

## Estructura

```text
/
├── 📄 katas.py
└── 📄 README.md
```

---

## Autor
Agustín Linares Carrera — uso educativo.
