# Recursos docentes

Materiales interactivos de Pablo Montaña para usar en clase, ordenados por año y por grupo. Cada recurso es una página web que funciona en el navegador, sin instalar nada.

## Recursos

| Año | Grupo | Curso | Recurso |
| --- | --- | --- | --- |
| 2026 | 9° EBI | Ciencias de la Computación | [Operadores en Python](2026/9ebi/operadores-python/index.html) |
| 2026 | 1° EMS | Ciencias Computacionales y Tecnologías Digitales | [Del pseudocódigo a Python](2026/1ems/del-pseudocodigo-a-python/index.html) |
| 2026 | 3° MF | Ingeniería del Software (práctica didáctica) | Sin recursos todavía |

## Estructura

```
recursos-docentes/
├── index.html                              portada: un enlace por año
├── README.md
├── assets/
│   └── estilos.css                         estilos compartidos de portada, años y grupos
└── 2026/
    ├── index.html                          página del año: un enlace por grupo
    ├── 9ebi/
    │   ├── index.html                      página del grupo: sus recursos
    │   └── operadores-python/
    │       └── index.html
    ├── 1ems/
    │   ├── index.html
    │   └── del-pseudocodigo-a-python/      una carpeta por actividad
    │       └── index.html                  la actividad interactiva
    └── 3mf/
        └── index.html                      práctica didáctica
```

## Agregar contenido

**Un recurso nuevo**

1. Crear su carpeta dentro del grupo. Desde la web de GitHub: **Add file → Create new file** y escribir la ruta completa, por ejemplo `2026/1ems/estructuras-de-control/index.html`. Cada `/` crea una carpeta.
2. En la página del grupo (`2026/1ems/index.html`), copiar una tarjeta de recurso y cambiar el título, la descripción y los enlaces. En un grupo sin recursos, reemplazar el recuadro "Todavía no hay recursos" por la tarjeta.
3. Actualizar el contador del grupo en la página del año y agregar la fila en este README.

**Un grupo nuevo**

Copiar la carpeta de un grupo (por ejemplo `2026/9ebi/`) con otro nombre, cambiar sus datos y agregar su tarjeta en la página del año.

**Un año nuevo**

Copiar la carpeta `2026/` con el nombre del año nuevo, dejar solo los grupos de ese año y agregar la tarjeta del año en la portada (`index.html`). Las páginas de años y grupos usan `../assets/estilos.css` o `../../assets/estilos.css` según su profundidad.

## Publicación

El sitio se publica con GitHub Pages desde la rama `main`. Cada carpeta con un `index.html` queda disponible en una dirección propia, que se puede compartir con los estudiantes.
