# login
html, manejo de iconos, Adding a linear gradient

# 📘 Tutorial de Clases TailwindCSS usadas en el formulario de Login

Este tutorial describe cada clase TailwindCSS usada en tu página de login, para que comprendas su función y cómo contribuyen al diseño.

---

## 🔹 `<body class="min-h-screen bg-gradient-to-r from-indigo-500 to-teal-400 flex items-center justify-center">`

| Clase                        | Descripción |
|-----------------------------|-------------|
| `min-h-screen`              | Establece una altura mínima igual al 100% de la altura de la ventana. |
| `bg-gradient-to-r`          | Aplica un degradado de fondo de izquierda a derecha. |
| `from-indigo-500`           | Color inicial del degradado (tono azul-violeta). |
| `to-teal-400`               | Color final del degradado (verde azulado claro). |
| `flex`                      | Convierte el body en un contenedor Flexbox. |
| `items-center`              | Centra verticalmente el contenido en el eje cruzado (vertical). |
| `justify-center`            | Centra horizontalmente el contenido en el eje principal (horizontal). |

---

## 🔹 Contenedor del formulario

```html
<div class="bg-white rounded-xl shadow-2xl p-8 w-full max-w-md">

| Clase        | Descripción                                        |
| ------------ | -------------------------------------------------- |
| `bg-white`   | Fondo blanco.                                      |
| `rounded-xl` | Bordes redondeados extra grandes.                  |
| `shadow-2xl` | Sombra profunda para efecto de elevación.          |
| `p-8`        | Padding uniforme de 2rem (32px).                   |
| `w-full`     | El contenedor ocupa el 100% del ancho disponible.  |
| `max-w-md`   | Máximo ancho de tamaño "medium" (\~28rem o 448px). |

## Imagen y Título

| Clase           | Descripción                         |
| --------------- | ----------------------------------- |
| `mx-auto`       | Centra el elemento horizontalmente. |
| `h-16`          | Altura de 4rem (64px).              |
| `w-16`          | Ancho de 4rem (64px).               |
| `mt-6`          | Margen superior de 1.5rem (24px).   |
| `text-2xl`      | Tamaño de fuente grande.            |
| `font-bold`     | Fuente en negrita.                  |
| `text-gray-800` | Color gris oscuro para el texto.    |

 ## Inputs del formulario
| Clase                     | Descripción                                         |
| ------------------------- | --------------------------------------------------- |
| `mt-1`                    | Margen superior pequeño (0.25rem).                  |
| `w-full`                  | Ancho completo.                                     |
| `rounded-md`              | Bordes medianamente redondeados.                    |
| `border`                  | Borde por defecto.                                  |
| `border-gray-300`         | Color del borde gris claro.                         |
| `px-3 py-2`               | Padding horizontal de 0.75rem y vertical de 0.5rem. |
| `shadow-sm`               | Sombra suave.                                       |
| `placeholder-gray-400`    | Texto del placeholder en gris claro.                |
| `focus:outline-none`      | Quita el borde azul por defecto al enfocar.         |
| `focus:ring-2`            | Aplica un anillo (resalte) de 2px al enfocar.       |
| `focus:ring-indigo-500`   | Color del anillo de enfoque.                        |
| `focus:border-indigo-500` | Color del borde cuando está enfocado.               |
| `text-gray-900`           | Texto en gris oscuro.                               |

 ## Enlace: ¿Olvidaste tu contraseña?
| Clase             | Descripción                  |
| ----------------- | ---------------------------- |
| `text-sm`         | Tamaño de fuente pequeño.    |
| `text-indigo-600` | Texto en tono índigo medio.  |
| `hover:underline` | Subrayado al pasar el mouse. |

## 🔹 Botón de enviar
| Clase                 | Descripción                                            |
| --------------------- | ------------------------------------------------------ |
| `w-full`              | Botón ocupa el 100% del ancho disponible.              |
| `bg-indigo-600`       | Fondo en tono índigo medio.                            |
| `text-white`          | Texto blanco.                                          |
| `py-2 px-4`           | Padding vertical de 0.5rem y horizontal de 1rem.       |
| `rounded-md`          | Bordes redondeados medianos.                           |
| `hover:bg-indigo-500` | Cambia el fondo a un tono más claro al pasar el mouse. |
| `font-semibold`       | Fuente seminegrita.                                    |
| `transition`          | Suaviza las animaciones como hover.                    |

##  Pie del formulario
| Clase             | Descripción                  |
| ----------------- | ---------------------------- |
| `mt-6`            | Margen superior grande.      |
| `text-center`     | Texto centrado.              |
| `text-sm`         | Tamaño de texto pequeño.     |
| `text-gray-600`   | Texto en gris medio.         |
| `text-indigo-600` | Enlace con tono índigo.      |
| `hover:underline` | Subrayado al pasar el mouse. |
| `font-medium`     | Fuente de peso medio.        |


