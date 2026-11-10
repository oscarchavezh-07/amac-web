# AMAC | Plataforma de vacantes

Proyecto web de AMAC (Asociación de Adultos Mayores A. C.) para consultar vacantes, revisar solicitudes y gestionar perfiles de candidatos y empresas. Incluye pantallas para registros, consulta de vacantes y administración.

## Integrantes y actividades

| Integrante | Actividades asignadas |
| --- | --- |
| Oscar Chavez Hernandez | Manejo general, layout, componentes, variables y estilos base. Páginas de empresa, vacantes, mis solicitudes, detalle de vacante y login. Manejo y administración general del repositorio |
| Marco Monsivais Macias | Propuesta de Registro de empresa, registro de usuario, solicitudes recibidas, Quiénes somos e intento sección de puntos extras. |
| Mariana Gomez del Angel | Gestión general de los archivos de entrega y Git, además de este README.md. |
| Javier Wong Mora | No se especificaron actividades |

## Paleta de colores

Los colores están definidos principalmente en `css/variable.css` y se usan en los estilos del proyecto.

| Variable CSS | Color | Uso |
| --- | --- | --- |
| `--texto` | `#1a1a1a` | Texto principal |
| `--header-y-botones-principales` | `#202945` | Encabezado y botones principales |
| `--fondo` | `#f5f7fa` | Fondo de las páginas |
| `--tarjetas` | `#ffffff` | Tarjetas, campos y modales |
| `--contorno` | `#a8a8a8` | Bordes y separadores |
| `--exito` | `#246412` | Estados de aceptación |
| `--falla` | `#b12424` | Rechazos y errores |
| `--ayuda` | `#fddaad` | Botón de ayuda y pestaña activa |
| `--pantone` | `#cae4ef` | Encabezado de filtros |
| `--pantone2` | `#fddaad` | Encabezado de tarjetas de vacantes |
| `--secundario` | `#ff815c` | Color secundario/naranja del logo |
| `--error` | `#ff815c` | Variable de error definida |

También se usa `#ffc9c9` directamente en el CSS para el fondo de `.alerta-error`.

## Tipografías

| Elemento | Familia | Tamaño | Peso |
| --- | --- | --- | --- |
| Títulos | Baskervville | `2.25rem` | 600 |
| Subtítulos | Baskervville | `1.5rem` | 700 |
| Etiquetas | Work Sans | `1.125rem` | 700 |
| Texto general | Work Sans | `1.125rem` | 400 |
| Botones | Work Sans | `1.25rem` | 500 |

## Componentes reutilizables (sección 5.4)

| Componente | Clases CSS principales | Uso |
| --- | --- | --- |
| Encabezado y navegación | `.header`, `.barra-superior`, `.logo`, `.nav`, `.current-page` | Encabezado y navegación entre páginas |
| Ayuda y menú | `.enlace-ayuda`, `.boton-menu` | Acceso a ayuda y menú adaptable |
| Pie de página | `.footer`, `.footer-contenido`, `.footer-enlaces`, `.footer-legal` | Enlaces e información final |
| Botones | `.boton`, `.boton-principal`, `.boton-secundario`, `.boton-aceptar`, `.boton-cancelar` | Acciones con variantes según su función |
| Formularios | `.input`, `.login-etiqueta`, `.registro-campo`, `.registro-seccion`, `.archivo` | Campos, etiquetas y carga de archivos |
| Buscador | `.campo-busqueda`, `.boton-buscar` | Búsqueda de vacantes |
| Filtros | `.panel-filtros`, `.grupo-filtros`, `.opcion-filtro`, `.rango-edad` | Opciones para filtrar resultados |
| Tarjetas de vacantes | `.tarjeta-vacante`, `.tarjeta-detalle-vacante` | Resumen y detalles de oportunidades |
| Tarjetas de solicitudes | `.mi-solicitud-tarjeta`, `.solicitud-estado` | Solicitudes y sus estados |
| Tarjetas de perfiles | `.tarjeta-perfil`, `.tarjeta-admin` | Información del perfil y administración |
| Mensajes | `.estado-vacio`, `.alerta-error`, `.modal`, `.modal-fondo` | Estados sin resultados, errores y ventanas |


## Capturas de pantalla

### Escritorio — `index.html`

<img width="1342" height="702" alt="image" src="https://github.com/user-attachments/assets/9fbabe7d-847d-4234-b282-cc48ae8e3bcb" />


### Celular — `index.html`

<img width="778" height="700" alt="image" src="https://github.com/user-attachments/assets/688a2231-d5ff-48e7-8c73-a91488812d57" />


## Lighthouse — Accessibility

Se evaluó `index.html` con Lighthouse desde Microsoft Edge, usando un servidor local (`http://127.0.0.1:5500`), el modo **Navigation** y dispositivo **Desktop**.

**Resultado de Accessibility: 100/100.**

<img width="1365" height="717" alt="lighthouse-accessibility" src="https://github.com/user-attachments/assets/2fc6ca50-504a-4037-899d-1c77d31de28d" />









°^°
