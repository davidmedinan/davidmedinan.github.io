# Sitio web personal de David I. Medina Núñez

Repositorio del sitio web personal y curriculum vitae de David I. Medina Núñez, profesor en Matemática y especialista en ciencia de datos.

**Ver el sitio:** [https://davidmedinan.github.io](https://davidmedinan.github.io)

## Contenido del sitio

- **Sobre mí:** presentación, posiciones actuales y áreas de interés.
- **Formación:** títulos obtenidos, formación en curso y postítulos.
- **Experiencia laboral:** ciencia de datos, docencia universitaria y docencia en nivel secundario.
- **Competencias:** cursos de posgrado, habilidades técnicas, idiomas y formación complementaria.
- **Seminarios e Investigación:** proyectos de investigación, becas, extensión, publicaciones y congresos.
- **Proyectos:** descripción de los principales proyectos profesionales y académicos.

## Tecnología

El sitio está construido con [Quarto](https://quarto.org) y publicado mediante GitHub Pages.

## Estructura del repositorio

```
├── _quarto.yml        # Configuración del sitio (menú, tema, salida)
├── custom.scss        # Colores del tema
├── styles.css         # Estilos adicionales
├── index.qmd          # Sobre mí
├── formacion.qmd      # Formación
├── experiencia.qmd    # Experiencia laboral
├── competencias.qmd   # Competencias
├── investigacion.qmd  # Seminarios e Investigación
├── proyectos.qmd      # Proyectos
└── docs/              # Sitio generado por Quarto (publicado por GitHub Pages)
```

## Actualización del sitio

1. Editar los archivos `.qmd` correspondientes.
2. Generar el sitio con `quarto render`.
3. Subir los cambios con `git add .`, `git commit` y `git push`.

GitHub Pages publica automáticamente el contenido de la carpeta `docs`.
