# Aprendiendo _Markdown_

Esto es un párrafo

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

Aplicando _cursiva_ y **negritas**, **_cursiva y negrita_**

<!-- Para encabezados con  " # " -->

# Encabezado 1

## Encabezado 2

### Encabezado 3

#### Encabezado 4

##### Encabezado 5

###### Encabezado 6

### Otro encabezado de ejemplo

## Enlaces e Imagenes

<!--     ENLACES       -->
<!-- Para enlaces utilizamos entre corchetes el texto visual y en los parentesis el link externo o interno (como para un Temario) Esto porque Markown reconoce a los encabezados como anclas internas.-->

[Youtube](https://youtube.com)

[MyProfile](https://github.com/Samu43lz)

[Aprendiendo _Markdown_](#aprendiendo-markdown)

<!-- Si nuestro encabezado tiene espacios, debemos buscarlo rellenando esos espacios con guiones medios pero aveces no hace falta porque Markdown te lo hace. -->

[Otro encabezado](#otro-encabezado-de-ejemplo)

<!-- IMAGENES -->
<!-- Para imagenes es lo mismo que con los enlaces pero debemos colocar un signo de exclamación al incio, ademas en los corchetes iria información acerca de la imagen por si hubiera un error -->

![This is me](cat.jpg)

## Divisiones

<!-- DIVISIONES -->
<!-- Para divisiones utilizamos 3 guiones medios
es nos dara un división igual al <hr> -->

---

First text

---

Second text

---

## Listas

#### Ordenadas

1. Primavera
1. Verano
1. Otoño
1. Invierno

#### Desordenadas

- Primavera
- Verano
- Otoño
- Invierno

#### Con Sub-listas

- Primavera
  - Septiembre
  - Octubre
  - Noviembre
  - Diciembre
- Verano
  - Diciembre
  - Enero
  - Febrero
  - Marzo
- Otoño
  - Marzo
  - Abril
    - My Birthday Month
  - Mayo
  - Junio
- Invierno
  - Junio
  - Julio
  - Agosto
  - Septiembre

## Citas

#### Cita en Linea

> Siempre tienes opción de no tener opinión. - Marco Aurelio.

#### Cita en Bloque

> Todo lo que escuchamos es una opinión, no un hecho.
>
> Todo lo que vemos es una perspectiva, no la verdad.
>
> Marco Aurelio.

## Tablas

<!-- Las formamos con " | ". Despues de haber creado el encabezado es necesario colocar " | " + guiones bajos " - " segun la cantidad de columnas que tengas para que se cree la tabla -->

| Nombre | Edad | Correo               |
| ------ | ---- | -------------------- |
| Samuel | 19   | widosrevel@gmail.com |
| Juan   | 14   | correo@correo.com    |

## Códigos

#### Código en Linea

<!-- Con la ayuda de Backtics -->

Lorem ipsum dolor sit amet, `Let` consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure

#### Código en Bloque

<!-- Utilizando 3 Backtics al inicio y al final del bloque de código y además si quieres darle un diseño especifico de un lenguaje puedes colocarle su abreviatura. EJ :  JS (Javascript)  -->

```js
function sumar(a, b) {
  return a + b;
}
```

#### Tambien podemos utilizar Código HTML !

<!-- Ya que tambien es un lenguaje de marcado. (Dentro de su soporte, soporta las etiquetas de HTML)-->
<form>
  <label for="q">Buscar :</label>
  <input type="search" name="q" id="q">
</form>
