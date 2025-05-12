# Desafío 3 - Funciones en JavaScript

Este repositorio contiene el desarrollo completo del Desafío 3 de la unidad de **Javascript - Funciones**, correspondiente en Desafío Latam.

## 🔢 Contenido del Proyecto

### Archivos JavaScript

- `assets/js/1_funcion.js`: Transformación de una función declarativa a función de expresión.
- `assets/js/2_arrow.js`: Transformación de una función a una arrow function de una sola línea.
- `assets/js/script.js`: Contiene lógica compartida para manipulación del DOM, eventos de click y teclas.

### Páginas HTML

- `index.html`: (antes `teclado.html`) Página principal. Permite interactuar con el teclado:
  - `a`, `s`, `d`: Cambian el color de un div principal (`#key`).
  - `q`, `w`, `e`: Generan nuevos divs con colores específicos.
- `4_colores.html`: Contiene 4 divs de colores (azul, rojo, verde, amarillo) que al hacer clic cambian su color a negro usando `addEventListener`.
- `pintar.html`: Estructura básica con evento de click que ejecuta una función `pintar()` desde archivo externo.

## 📆 Estructura del Proyecto

```
DesafioFunciones/
├── index.html
├── 4_colores.html
├── pintar.html
└── assets/
    └── js/
        ├── 1_funcion.js
        ├── 2_arrow.js
        └── script.js
```

## 🚀 Funcionalidades

- Creación y llamada de funciones.
- Uso de parámetros y valores por defecto.
- Eventos DOM (`click`, `keydown`).
- Manipulación del estilo de elementos HTML desde JavaScript.
- Generación de nuevos elementos mediante funciones.

## ✅ Estado del Desafío

- [x] Requerimiento 1 completado
- [x] Requerimiento 2 completado
- [x] Requerimiento 3 (click en div) completado
- [x] Requerimiento 4 (4 colores) completado
- [x] Requerimiento 5 (teclado + creación de divs) completado

## 🎓 Autor

**Williams Esteban Arias Quilodrán**
Estudiante de Desarrollo Fullstack, Ingeniería en Redes y Comunicación, e Ingeniería Industrial & Administración.

---

Repositorio creado como parte del proceso de evaluación de la unidad "Funciones" en el modulo de JavaScript para Desafio Latam.
