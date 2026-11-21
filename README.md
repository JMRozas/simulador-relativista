# Simulador relativista

Relatividad especial y general calculadas en el navegador: aberración y Doppler a velocidades extremas, la rotación de Terrell, geodésicas de luz y la caída hacia un agujero negro de Schwarzschild. Funciona en el móvil y en el ordenador.

Tiene cuatro secciones:

- **Viaje interestelar:** viaje con aceleración constante por un cielo real (Hipparcos + Gaia) hasta estrellas, cúmulos y nebulosas.
- **Objetos veloces:** cómo se ven un cubo, una esfera, un tren o una regla a velocidades relativistas.
- **Luz y órbitas:** geodésicas de la luz y órbitas alrededor de una masa.
- **Agujero negro:** la caída hacia un agujero negro de Schwarzschild.

## Cómo usarlo

Abre la página publicada en GitHub Pages. No hace falta instalar nada.

Para ejecutarlo en tu ordenador, sirve la carpeta con un servidor local, porque el navegador no permite leer `datos/` al abrir `index.html` con doble clic:

```
python -m http.server
```

Después, abre `http://localhost:8000`.

## Archivos

- `index.html`: el simulador completo.
- `datos/estrellas.b64.txt`: catálogo de estrellas en binario (float32) codificado en Base64.
- `datos/estrellas.json`: nombres, líneas de constelaciones y datos de las nebulosas.
