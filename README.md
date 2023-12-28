[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/aRQGnba4)

# Expresiones Regulares (regex)

## Investiga:

- qué son las expresiones regulares?
  Son un sistema para buscar, capturar o reemplazar texto utilizando unos patrones, estos se representan mediante una cadena de texto donde ciertos simbolos tienen un significado especial.
- Qué problema resuelven? Por qué es importante conocerlas?
  Son muy utiles para la busqueda de texto de manera sencilla y abstracta, de manera que abarquen una gran cantidad de posibilidades que de otra forma seria imposible o muy extensa y compleja(ejemplo en bases de datos)
  Soon importantes porque sirven para definir filtros y nos permiten ahorrar código

## Ejercicio 1:

Escribe las expresiones regulares correctas para validar:

- un email-
  const mailRegexp=/[A-Za-z0-9]+\@[A-Za-z]+\.[a-z]+
- un número de teléfono (español)-
  const telefRegexp=/[0-9]{9}
- un DNI
  const dniRegexp=/[0-9]{8}[A-Z]{1}$

## Ejercicio 2:

Crea un formulario de contacto y utiliza el atributo `pattern` de los elementos `input` para validar los campos usando expresiones regulares. El formulario debe incluir: nombre, apellidos, dni, número de teléfono, email, dni y dirección.

Nota: puedes hacerlo añadiendo un archivo `index.html` en este repositorio.

## Referencias

- [Expresiones Regulares en Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions)
- [Online Regex Editor](https://regex101.com/)
