# Recursos docentes

Materiales interactivos de Pablo Montaña para usar en clase, ordenados por año y por grupo. Cada recurso es una página web que funciona en el navegador, sin instalar nada.

## Recursos

| Año | Grupo | Recurso | Archivos |
| --- | --- | --- | --- |
| 2026 | 1° EMS · Ciencias Computacionales y Tecnologías Digitales | Del pseudocódigo a Python | [Recurso](2026/1ems/del-pseudocodigo-a-python/index.html) · [Planificación](2026/1ems/del-pseudocodigo-a-python/planificacion.docx) |

## Estructura

```
recursos-docentes/
├── index.html                              portada con enlaces a todos los recursos
├── README.md
└── 2026/                                   una carpeta por año
    └── 1ems/                               una carpeta por grupo
        └── del-pseudocodigo-a-python/      una carpeta por recurso
            ├── index.html                  el recurso interactivo
            └── planificacion.docx          la planificación de la clase
```

## Agregar un recurso nuevo

1. Crear la carpeta del recurso dentro del año y del grupo. Desde la web de GitHub: **Add file → Create new file** y escribir la ruta completa, por ejemplo `2026/1ems/estructuras-de-control/index.html`. Cada `/` crea una carpeta.
2. Subir la planificación a la misma carpeta con **Add file → Upload files**.
3. En `index.html` (portada), agregar una tarjeta dentro del grupo que corresponda. Para un grupo o un año nuevo, copiar el bloque completo del grupo o del año.
4. Agregar una fila en la tabla de este README.

## Publicación

El sitio se publica con GitHub Pages desde la rama `main`. Cada carpeta con un `index.html` queda disponible en una dirección propia, que se puede compartir con los estudiantes.
