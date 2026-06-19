# Lección 4 — CSS: dale estilo a tu página (12 min)

> Guion de narración. Video **no listado**. Demostración **solo** en CodePen. Sin branding ni referencia a los autores.
>
> 🔗 Termina la **página del videojuego** dándole estilo. El starter de esta lección es el `completed` de la 3.

## 🎯 Objetivo
Al terminar, el estudiante podrá aplicar CSS usando selectores de elemento, clase e id, dar color y tipografía, usar el modelo de caja, centrar contenido y crear una tarjeta con bordes, esquinas redondeadas, sombra y efecto al pasar el cursor.

## 🎬 Guion

### Segmento 1 — Recap y meta del día (0:00 – 0:45)
- **[En pantalla]**: la página del videojuego sin estilo contra una vista previa con estilo tipo tarjeta.
- **[Narración]**: "Tu página ya tiene todo el contenido, pero se ve plana. Hoy le damos vida con CSS y la convertimos en una tarjeta bonita."

### Segmento 2 — Qué es CSS y anatomía de una regla (0:45 – 2:30)
- **[En pantalla]**: el panel CSS de CodePen y `body { background-color: lightblue; }` señalando selector, propiedad y valor.
- **[Narración]**: "Si HTML es la estructura, CSS es el estilo. En CodePen el CSS va en su propio panel. Una regla CSS tiene tres partes. El selector, a qué elemento le cambias el estilo. La propiedad, qué quieres cambiar. Y el valor, cómo lo quieres. No olvides el punto y coma al final de cada línea, ese sí va, es parte del código."

### Segmento 3 — Tres formas de seleccionar (2:30 – 5:00)
- **[En pantalla]**: `h2 { }`, `.descripcion { }` con `class="descripcion"`, y `#titulo { }` con `id="titulo"`.
- **[Narración]**: "Hay tres formas principales de elegir qué estilizar. Por elemento, si escribes `h2`, le cambias el estilo a todos los `<h2>`. Por clase, le pones un atributo `class` a un elemento y en el CSS lo llamas con un punto adelante. La clase puedes repetirla en varios elementos. Y por id, que es único, solo uno por página. Le pones `id` al elemento y en el CSS lo llamas con un numeral. Regla simple, el elemento para todos, la clase para un grupo, el id para uno solo."

### Segmento 4 — Color y tipografía (5:00 – 7:00)
- **[En pantalla]**: `body { background-color: #f0f4f8; color: #333; font-family: Arial, sans-serif; text-align: center; }` y `#titulo { color: #3366ff; }`.
- **[Narración]**: "Ahora las propiedades más usadas. `background-color` cambia el fondo. `color` cambia el texto. Puedes usar nombres o códigos hexadecimal, que empiezan con numeral. Con `font-family` eliges el tipo de letra. Con `text-align: center` centras el texto. Mira cómo con pocas líneas la página ya tiene personalidad."

### Segmento 5 — El modelo de caja (7:00 – 8:30)
- **[En pantalla]**: una caja con `padding` por dentro y `margin` por fuera.
- **[Narración]**: "Cada elemento es una caja. El `padding` es el espacio por dentro, entre el borde y el contenido. El `margin` es el espacio por fuera, entre esa caja y las demás. Con estos dos controlas casi todo el orden visual."

### Segmento 6 — La tarjeta y centrar con Flexbox (8:30 – 10:45)
- **[En pantalla]**: `<div class="tarjeta">` envolviendo el contenido. En el CSS, `body { display: flex; justify-content: center; }` y `.tarjeta { max-width: 400px; padding: 30px; background-color: #fff; border: 1px solid #ddd; border-radius: 12px; }`.
- **[Narración]**: "Para agrupar todo usamos un `<div>`, un contenedor, con `class="tarjeta"`. Y ahora, ¿cómo la centramos? Por defecto los elementos se apilan uno debajo de otro, eso se llama `block`. La forma moderna de acomodarlos es Flexbox. Al `body` le ponemos `display: flex` y con `justify-content: center` empujamos la tarjeta al centro de la pantalla. A la tarjeta le damos un ancho máximo, un `padding` generoso, un borde fino y esquinas redondeadas con `border-radius`. Ya parece una página de verdad."

### Segmento 7 — Efecto al pasar el cursor (10:45 – 11:20)
- **[En pantalla]**: `a:hover { color: #ff6600; }`.
- **[Narración]**: "Un toque profesional. Con `hover` cambias cómo se ve algo cuando pasas el cursor por encima. Escribes el selector, dos puntos, `hover`. Mira, al pasar el cursor el enlace cambia de color."

### ⏸️ Segmento 8 — Pausa y practica (11:15 – 12:00)
- **[En pantalla]**: CodePen starter con la página de la Lección 3.
- **[Narración]**: "Abre el enlace. Pausa el video y dale estilo a tu página. Color y tipografía al `body`, un id para el título, una tarjeta que envuelva todo y un efecto `hover` en los enlaces. En la lección 5 viene lo grande. Vas a construir tu página de perfil personal desde cero, tú solo, aplicando todo esto."

## 🔗 Recursos
- **Video**: `<enlace-yt-4>`
- **Editor inicial (starter)**: `<enlace-editor-4>`
- **Código**: `starter-files/leccion-4/` y `completed-examples/leccion-4/` (página del videojuego terminada)
