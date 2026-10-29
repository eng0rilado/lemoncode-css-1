# Ejercicio 2 · Dos temas CSS

Página que muestra dos temas distintos aplicados a los mismos elementos. Cada tema cambia el **color**, la **fuente**, el **border radius** y la **sombra** (shadow box).

## Estructura

```
ejercicio-2-css/
├── index.html          ← página con los elementos de ejemplo
├── globals.css         ← estilos principales; importa el tema activo
└── themes/
    ├── styles-a.css    ← tema A (variables)
    └── styles-b.css    ← tema B (variables)
```

## Cómo cambiar de tema

1. Abre `globals.css`.
2. En la primera línea, cambia el `@import` por el tema que quieras:

   ```css
   /* Tema B */
   @import "./themes/styles-b.css";

   /* Tema A */
   @import "./themes/styles-a.css";
   ```

3. Guarda y recarga `index.html`.

No hace falta tocar nada más: cada tema solo define variables, y `globals.css` las usa.
