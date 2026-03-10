

# M1C2 — Tarea de Flexbox

Durante la segunda sección del Módulo 1 habrás repasado la utilísima herramienta Flexbox. Flexbox es otra herramienta muy útil que los desarrolladores pueden usar para controlar el comportamiento y la distribución de los elementos HTML. Ya la usaste en el curso de Fundamentos de Programación. Ahora que has repasado y aprendido más sobre Flexbox, ¡es hora de practicar!

Deberás usar **HTML y CSS** para completar esta tarea. Se espera que crees y edites los archivos con un editor de texto y que uses una **hoja de estilos externa**.

Una vez terminada, compártela con un mentor a través de la aplicación de soporte para que revise tu trabajo. Esta tarea es **obligatoria** para aprobar esta sección del curso.

---

## Repositorio de inicio

Copia el código inicial desde el siguiente repositorio de GitHub:

🔗 [https://github.com/bottegaMentor/m1c2-flexbox--assignment/tree/main](https://github.com/bottegaMentor/m1c2-flexbox--assignment/tree/main)

---

## Conceptos trabajados en esta tarea

`HTML` · `CSS` · `Flexbox` · `Clases e IDs en HTML` · `Divs` · `Img, h1 y etiquetas de párrafo` · `Background-color` · `Color de texto` · `Hojas de estilo externas y estilos en línea` · `flex-direction` · `flex-wrap` · `flex-basis` · `flex-grow` · `flex-shrink` · `justify-content` · `align-content` · `align-self` · `align-items`

---

## Ejercicios

### Flexbox 1
Selecciona la clase `flexOne`. Usa Flexbox para colocar los elementos del div `flexOne` **uno al lado del otro**. Añade **5 píxeles de margen** a la clase `square` únicamente cuando esté dentro de `flexOne`.

---

### Flexbox 2
Selecciona la clase `flexTwo`. Usa Flexbox. Establece `flex-direction` en `column`. El valor por defecto es `row`, que coloca los elementos uno al lado del otro; con `column` vuelven a apilarse verticalmente. Dale a los cuadrados dentro de `flexTwo` un margen de **2 píxeles**.

---

### Flexbox 3
Selecciona la clase `flexThree`. Repite los pasos de Flexbox 2, pero esta vez establece `flex-direction` en `row-reverse`. Añade los números **1, 2 y 3** dentro de los divs cuadrado correspondientes en `flexThree` para que puedas ver cómo el orden ahora está invertido.

---

### Flexbox 4
Selecciona la clase `flexFour`. Usa Flexbox. Establece el ancho del div en **350px**. Dale un margen de **5px** a los cuadrados dentro de `flexFour`. Establece `flex-flow` en `wrap`. Cambia también el color de fondo a `#3d8b6d`.

Verás que el cuarto cuadrado se desplaza automáticamente a una nueva fila porque no cabe en los 350px junto con los demás. Esto es muy útil para sitios como Instagram, donde conoces el formato que quieres pero no el número de elementos: con `flex-wrap`, el código gestiona el diseño de forma automática.

---

### Flexbox 5
Selecciona la clase `flexFive`. Añade un ancho de **350px** y usa Flexbox. Selecciona la clase `item` para los divs dentro de `flexFive`. Establece el `background-color` en `#0b6643`. Añade un ancho y alto de **100px** y un margen de **2px** para ver los cuadrados individualmente.

Ahora selecciona el id `grow`. Aplica `flex-grow: 2`. Esto hará que el elemento central ocupe el doble del espacio sobrante en comparación con los demás elementos.

---

### Flexbox 6
Selecciona la clase `flexSix`. Añade una **altura de 400px** y un **ancho de 500px**. Establece el color de fondo en `#f1f1f1`. Establece `flex-direction` en `column`.

En cada div hijo (clases `one`, `two` y `three`), usa Flexbox:
- **`one`**: `justify-content: space-around`
- **`two`**: `justify-content: space-between`, `margin: 50px 0`, `background-color: #d6d6d6`
- **`three`**: `justify-content: space-evenly`

Así podrás ver cómo se comportan de forma diferente estas tres variantes de `justify-content`.

---

### Flexbox 7
Selecciona la clase `flexSeven`. Añade una **altura de 400px** y un **ancho de 500px**. Usa Flexbox y establece `justify-content: space-between`. Deja `flex-direction` en su valor por defecto (`row`).

En los divs `one`, `two`, `three` y `four`, usa Flexbox y establece `flex-direction: column`. Luego:
- **`one`**: `justify-content: center`
- **`two`**: `justify-content: flex-end`
- **`three`**: `justify-content: flex-start`
- **`four`**: `justify-content: space-between`

Así podrás ver cómo `justify-content` también permite organizar elementos verticalmente cuando se combina con `flex-direction: column`.

---

### Flexbox 8
Selecciona la clase `flexEight`. Usa Flexbox. Dale una **altura de 400px**, un **ancho de 300px** y un `background-color: #eeeeee`.

Selecciona la clase `one` dentro de `flexEight`. Usa Flexbox y establece `align-items: center`. Haz lo mismo para `two` con `align-items: flex-end`, y para `three` con `align-items: flex-start`.

Verás que `align-items` también permite mover elementos en el eje vertical.

---

### Flexbox 9
Selecciona la clase `flexNine`. Usa Flexbox. Establece un **ancho de 450px**, una **altura de 250px** y un `background-color: #eeeeee`. Usa `align-items` para que los elementos comiencen desde arriba. Usa `justify-content` para espaciarlos de forma uniforme.

Selecciona ahora el id `special`. Usa la propiedad `align-self` y establécela en `flex-end`. De este modo sobreescribirás el comportamiento del tercer cuadrado y hará que empiece desde abajo en lugar de desde arriba.

---

