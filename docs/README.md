# Pintura‑ArteMina

Este repositorio contiene la estructura base para el portafolio web de Mina Maldonado,
también conocido como **ArteMina**. La organización sigue una lógica de separación
de contenidos que facilita la integración con gestores de contenido como WordPress
o frameworks estáticos.

## Estructura de carpetas

```
Pintura-ArteMina/
├── index.html            # Página principal del sitio
├── style.css             # Hoja de estilos global
├── script.js             # Lógica JavaScript (vacío por defecto)
│
├── assets/               # Recursos estáticos
│   ├── images/           # Carpeta para imágenes de las obras
│   └── pdf/              # Carpeta para documentos PDF
│
├── content/              # Textos descriptivos de las obras
│   ├── Como_el_Sol.txt
│   ├── Proyecto_Verde.txt
│   ├── Anatomia_de_la_Resiliencia.txt
│   ├── Mi_Mente.txt
│   ├── Proyecto_Mina.txt
│   ├── Huesos_y_Flores.txt
│   └── Proyecto_Arte.txt
│
├── pages/                # Páginas adicionales del sitio
│   ├── sobre_mina.html
│   ├── galeria.html
│   ├── contacto.html
│   └── exposiciones.html
│
└── docs/
        └── README.md        # Este archivo
```

## Cómo usar

1. **Añadir contenido real:** Reemplaza los archivos de marcador de posición en `content/` con los textos de
   reseñas correspondientes. Coloca las imágenes y los PDF en las carpetas dentro de `assets/`.
2. **Actualiza los enlaces:** Si cambias nombres de archivos o añades nuevos recursos, modifica los enlaces
   en `index.html` y las páginas de `pages/` según sea necesario.
3. **Publica el sitio:** Puedes servir estos archivos desde GitHub Pages u otro servicio de hosting
   estático. Asegúrate de que las rutas relativas se mantengan consistentes.

## Licencia

El contenido de este repositorio es propiedad de Mina Maldonado. Por favor respeta los derechos de autor
al reutilizar textos e imágenes.
