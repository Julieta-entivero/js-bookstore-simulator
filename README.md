# Simulador de Libreria - Pago en Cuotas

Simulador interactivo de una libreria que permite seleccionar un libro del catalogo y calcular el pago en cuotas con recargo. Desarrollado con JavaScript vanilla.

## Tecnologias

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Funcionalidades

- Catalogo de 7 libros con titulo, anio de edicion, estado y precio
- Seleccion de producto por anio de edicion
- Calculo de cuotas (1 a 18) con recargo porcentual
- Validacion de entrada numerica
- Clase `Producto` con ES6 para modelar los libros

## Catalogo

| Libro | Edicion | Precio |
|-------|---------|--------|
| Brandon Sanderson | 2021 | $50.000 |
| Cumbres Borrascosas | 2024 | $30.000 |
| Orgullo y Prejuicio | 2019 | $20.000 |
| Harry Potter y el Prisionero de Azkaban | 2002 | $70.000 |
| Percy Jackson y los Dioses del Olimpo | 2014 | $80.000 |
| Peter Pan | 2000 | $15.000 |
| My Lady Jane | 2024 | $25.000 |

## Como usar

1. Abrir `pages/index.html` en el navegador
2. Ingresar el anio del libro deseado
3. Indicar la cantidad de cuotas (entre 1 y 18)
4. El simulador muestra el valor de cada cuota con recargo

## Estructura

```
js-bookstore-simulator/
├── css/
│   └── style.css
├── js/
│   └── main.js
├── pages/
│   └── index.html
└── README.md
```
