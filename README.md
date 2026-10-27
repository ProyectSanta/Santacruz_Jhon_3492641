
# Diferencias entre `section` y `div` en HTML

La diferencia principal es que **`section` agrupa contenido relacionado temáticamente, mientras que `div` es un contenedor genérico sin significado semántico**.

## 1. Etiqueta `<section>`

- Es una etiqueta semántica, es decir, tiene un significado específico.
- Se utiliza para agrupar contenido relacionado con un mismo tema.
- Generalmente, contiene un título, como un `<h2>` o `<h3>`.
- Ayuda a organizar la estructura del documento HTML.

### Ejemplo

```html
<section>
  <h2>Servicios</h2>
  <p>Ofrecemos diseño web y desarrollo de aplicaciones.</p>
</section>
```

En este ejemplo, `section` agrupa el título y el párrafo relacionados con los servicios.

## 2. Etiqueta `<div>`

- Es una etiqueta no semántica, es decir, no describe el significado del contenido.
- Se utiliza como contenedor genérico para agrupar elementos HTML.
- Es útil para aplicar estilos CSS, utilizar Flexbox o Grid y organizar elementos.
- No necesita contener un título.

### Ejemplo

```html
<div class="card">
  <h2>Producto</h2>
  <p>Descripción del producto.</p>
</div>
```

En este ejemplo, `div` agrupa los elementos para poder aplicarles estilos CSS.

## 3. Tabla comparativa

| Característica | `<section>` | `<div>` |
|---|---|---|
| Semántica | Sí | No |
| Propósito | Agrupar contenido temático | Agrupar elementos genéricamente |
| Título | Generalmente recomendable | No es necesario |
| Permite CSS | Sí | Sí |
| Permite JavaScript | Sí | Sí |
| Aporta significado al documento | Sí | No, por sí solo |

## 4. ¿Cuándo utilizar cada uno?

### Utiliza `<section>` cuando:

El contenido represente una sección temática de la página.

```html
<section>
  <h2>Sobre nosotros</h2>
  <p>Conoce nuestra empresa.</p>
</section>
```

### Utiliza `<div>` cuando:

Necesites agrupar elementos para organizar el diseño, aplicar estilos o facilitar su manipulación con JavaScript, sin representar una sección temática.

```html
<div class="contenedor">
  <img src="foto.jpg" alt="Fotografía de ejemplo">
  <p>Texto descriptivo.</p>
</div>
```

## 5. ¿Se pueden utilizar juntos?

Sí. Es común utilizar `div` dentro de `section` para organizar el contenido.

```html
<section>
  <h2>Nuestros productos</h2>

  <div class="productos">
    <div class="producto">
      <h3>Producto 1</h3>
      <p>Descripción del producto 1.</p>
    </div>

    <div class="producto">
      <h3>Producto 2</h3>
      <p>Descripción del producto 2.</p>
    </div>
  </div>
</section>
```

En este caso:

- `section` representa la sección temática de los productos.
- `div` con la clase `productos` agrupa las tarjetas.
- Los `div` con la clase `producto` sirven como contenedores individuales.

## 6. Conclusión

**La regla general es:**

- Usa `<section>` cuando el contenido tenga un propósito temático y represente una sección del documento.
- Usa `<div>` cuando necesites un contenedor genérico para agrupar elementos o aplicar estilos.

Ambas etiquetas pueden utilizar CSS y JavaScript. La diferencia fundamental está en la semántica: `section` comunica el significado de la estructura, mientras que `div` no lo hace.

# Diferencias entre `section` y `div` en HTML

La diferencia principal es que **`section` agrupa contenido relacionado temáticamente, mientras que `div` es un contenedor genérico sin significado semántico**.

## 1. Etiqueta `<section>`

- Es una etiqueta semántica, es decir, tiene un significado específico.
- Se utiliza para agrupar contenido relacionado con un mismo tema.
- Generalmente, contiene un título, como un `<h2>` o `<h3>`.
- Ayuda a organizar la estructura del documento HTML.

### Ejemplo

```html
<section>
  <h2>Servicios</h2>
  <p>Ofrecemos diseño web y desarrollo de aplicaciones.</p>
</section>
```

En este ejemplo, `section` agrupa el título y el párrafo relacionados con los servicios.

## 2. Etiqueta `<div>`

- Es una etiqueta no semántica, es decir, no describe el significado del contenido.
- Se utiliza como contenedor genérico para agrupar elementos HTML.
- Es útil para aplicar estilos CSS, utilizar Flexbox o Grid y organizar elementos.
- No necesita contener un título.

### Ejemplo

```html
<div class="card">
  <h2>Producto</h2>
  <p>Descripción del producto.</p>
</div>
```

En este ejemplo, `div` agrupa los elementos para poder aplicarles estilos CSS.

## 3. Tabla comparativa

| Característica | `<section>` | `<div>` |
|---|---|---|
| Semántica | Sí | No |
| Propósito | Agrupar contenido temático | Agrupar elementos genéricamente |
| Título | Generalmente recomendable | No es necesario |
| Permite CSS | Sí | Sí |
| Permite JavaScript | Sí | Sí |
| Aporta significado al documento | Sí | No, por sí solo |

## 4. ¿Cuándo utilizar cada uno?

### Utiliza `<section>` cuando:

El contenido represente una sección temática de la página.

```html
<section>
  <h2>Sobre nosotros</h2>
  <p>Conoce nuestra empresa.</p>
</section>
```

### Utiliza `<div>` cuando:

Necesites agrupar elementos para organizar el diseño, aplicar estilos o facilitar su manipulación con JavaScript, sin representar una sección temática.

```html
<div class="contenedor">
  <img src="foto.jpg" alt="Fotografía de ejemplo">
  <p>Texto descriptivo.</p>
</div>
```

## 5. ¿Se pueden utilizar juntos?

Sí. Es común utilizar `div` dentro de `section` para organizar el contenido.

```html
<section>
  <h2>Nuestros productos</h2>

  <div class="productos">
    <div class="producto">
      <h3>Producto 1</h3>
      <p>Descripción del producto 1.</p>
    </div>

    <div class="producto">
      <h3>Producto 2</h3>
      <p>Descripción del producto 2.</p>
    </div>
  </div>
</section>
```

En este caso:

- `section` representa la sección temática de los productos.
- `div` con la clase `productos` agrupa las tarjetas.
- Los `div` con la clase `producto` sirven como contenedores individuales.

## 6. Conclusión

**La regla general es:**

- Usa `<section>` cuando el contenido tenga un propósito temático y represente una sección del documento.
- Usa `<div>` cuando necesites un contenedor genérico para agrupar elementos o aplicar estilos.

Ambas etiquetas pueden utilizar CSS y JavaScript. La diferencia fundamental está en la semántica: `section` comunica el significado de la estructura, mientras que `div` no lo hace.
