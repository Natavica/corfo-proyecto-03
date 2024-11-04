# corfo-proyecto-03
# Objetivo de la Entrega

El objetivo de esta entrega es **integrar Bootstrap** en un proyecto previamente desarrollado.

## Flujos de Trabajo

Se definen dos flujos de trabajo:

1. **Flujo de referencia:**
   - Este comienza con el archivo `index_ref.html`, donde los estilos se generaron con **SASS** y contienen modificaciones realizadas anteriormente en el proyecto.
  
2. **Flujo de entrega:**
   - Este inicia con el archivo `index.html`, diseñado específicamente para cumplir con los requisitos de la presente entrega. En este flujo, las páginas HTML se adaptaron al sistema de diseño de **Bootstrap 5.3.3** para aprovechar su estructura de componentes y layout.

/corfo-proyecto-03
│
├── /assets/
│   ├── /css/
│       └── styles.css *Estilos del proyecto que complementan Bootstrap
│   ├── /scss/
│       └── main.scss 
│       └── main.css.map
│       └── main.css
│       └── /components/  
│                 └── _footer.scss
│                 └── _header.scss
│                 └── _variables.scss
│  
├── ├── /js/
│   │   └── script.js
│   └── /images/         
*
├── index.html              # Página principal (Home)
├── equipo.html             # Página del equipo médico
└── contacto.html           # Página de contacto
*
├── inde_ref.html           # Referencia de proyecto anterior con SASS
├── equipo_ref.html         # Referencia de proyecto anterior con SASS
└── contacto_ref.html       # PReferencia de proyecto anterior con SASS




### Descripción de Carpetas y Archivos

- **`flujo_referencia/`**: Contiene `index_ref.html`, el archivo de referencia con los estilos en SASS.
- **`flujo_entrega/`**: Incluye `index.html`, ajustado para cumplir con los requisitos de Bootstrap 5.3.3.
- **`assets/`**: Carpeta común que contiene los recursos del proyecto:
  - **`css/`**: Archivos CSS generados.
  - **`images/`**: Carpeta para las imágenes del proyecto.
  - **`js/`**: JavaScript de la versión que no tiene Bootstrao.
  - **`scss/`**: Archivos fuente de SASS.
    - **`components/`**: Contiene componentes individuales como `_footer.scss`, `_header.scss`, y `_variables.scss`.
    - **`main.scss`**: Archivo principal de SASS.
    - **`main.scss.map`**: Mapa de fuente para `main.scss`.







