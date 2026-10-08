# mi-hub-estudiantil

Mini-sitio web de 2 páginas desarrollado de forma colaborativa con **HTML**, **CSS** y control de versiones con **Git y GitHub**.

Proyecto de la **Tarea Práctica #2: Integración HTML y CSS / Control de versiones**
Curso: Desarrollo Web 1S3221 · II Semestre 2026 · Profesor: Giovani Sánchez

## Integrantes

| Integrante | Rol principal |
|---|---|
| Joel Torres | Página de perfil (`index.html`) |
| Marc Buchanan | Página de recursos (`recursos.html`) |

## Descripción

El sitio funciona como un hub personal del equipo:

- **Perfil (`index.html`)**: presentación de los integrantes, hobbies e intereses y la meta del semestre.
- **Recursos (`recursos.html`)**: enlaces externos útiles, tabla con el estado de las asignaturas y un formulario de contacto (solo maquetado, sin backend).

## Estructura del proyecto

```
mi-hub-estudiantil/
├── index.html
├── recursos.html
├── css/
│   └── estilos.css
├── img/
│   ├── avatar1.jpg
│   └── avatar2.jpg
└── README.md
```

## Tecnologías y características

- HTML5 con estructura semántica (`header`, `nav`, `main`, `section`, `footer`)
- CSS externo con variables personalizadas (colores y tamaños)
- Tipografía del sistema (`system-ui`)
- Maquetación con Flexbox
- Efectos hover en enlaces, tarjetas, tabla y botones
- Diseño responsivo con media query (≤ 600px: tarjetas en una columna)
- Clases utilitarias para centrar contenido

## Cómo ver el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/USUARIO/mi-hub-estudiantil.git
   ```
2. Abre la carpeta del proyecto.
3. Abre `index.html` en tu navegador.

## Flujo de trabajo con Git

Ambos integrantes trabajamos sobre el mismo repositorio siguiendo este flujo:

```
git pull → modificar → git add → git commit → git push
```

Los commits usan mensajes descriptivos que reflejan avances reales del proyecto.

## Autores

- **Joel Torres**
- **Marc Buchanan**

Creado por Joel Torres y Marc Buchanan – 2026
