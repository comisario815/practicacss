# El Diario SMR - Práctica HTML y CSS (UT2.A3)

* **Alumno:** Yerobe Fernández Fuentes
* **Temática:** Periódico digital especializado en la actualidad de GTA VI y videojuegos.

## Respuestas teóricas

### 1. ¿Cuál es la diferencia entre un elemento de bloque y uno en línea?
* **Elementos de bloque (`div`, `h1`, `p`):** Ocupan todo el ancho disponible de su contenedor y provocan un salto de línea antes y después, colocándose uno debajo de otro.
* **Elementos en línea (`span`, `a`, `strong`):** Ocupan únicamente el espacio necesario para su contenido y se colocan uno al lado del otro dentro de la misma línea de texto.

### 2. ¿Qué diferencia existe entre class e id?
* **`id`:** Es un identificador único que solo puede asignarse a un único elemento en toda la página HTML (por ejemplo, `#cabecera`).
* **`class`:** Es una clase reutilizable que puede aplicarse a varios elementos distintos para darles el mismo estilo (por ejemplo, `.noticia`).

### 3. ¿Qué diferencia hay entre margin y padding?
* **`padding`:** Es el espacio de relleno interior situado entre el contenido del elemento y su borde.
* **`margin`:** Es el espacio exterior situado por fuera del borde que separa ese elemento de los demás elementos vecinos.

### 4. ¿Para qué sirve `box-sizing: border-box`?
Sirve para que el navegador incluya el `padding` y el `border` dentro del `width` (ancho) y `height` (alto) establecidos en el elemento. Sin esta propiedad, los rellenos y bordes se suman al tamaño inicial, haciendo las cajas más grandes de lo esperado y descuadrando el diseño.