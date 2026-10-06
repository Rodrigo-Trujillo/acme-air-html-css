# ACME AIR

Maquetación de la aplicación web móvil de **ACME AIR**, una aerolínea internacional que renueva su experiencia digital. El proyecto se construye únicamente con **HTML5 y CSS3**, sin JavaScript, a partir de las maquetas del departamento de diseño UI/UX.

## Objetivo

Ofrecer una interfaz limpia, intuitiva y responsiva, con identidad visual coherente y navegación simulada entre las 9 vistas, desde el inicio de sesión hasta la consulta de vuelos.

## Tecnologías

- HTML5 semántico
- CSS3 (variables, Flexbox, CSS Grid y media queries)
- Diseño mobile-first con puntos de quiebre en 320px, 768px y 1024px

## Integrantes

- Rodrigo Trujillo
- Sebastián Panche
- Dainer Cuteño

## Guía de navegación

| Vista | Archivo | Va hacia |
| --- | --- | --- |
| Iniciar sesión | `index.html` | Ingresar → Menú · Crear cuenta → Registro · ¿Olvidaste tu contraseña? → Recuperar contraseña |
| Menú principal | `menu.html` | Buscar vuelos · Registrarse (check-in) · Mis vuelos · Cerrar sesión → Iniciar sesión |
| Registro | `registro.html` | Guardar → Crear contraseña |
| Recuperar contraseña | `recuperar.html` | Enviar → Crear contraseña |
| Crear contraseña | `crear-contraseña.html` | Guardar → Menú |
| Búsqueda de vuelos | `buscar-vuelos.html` | Buscar → Vuelos disponibles |
| Vuelos disponibles | `vuelos.html` | Volver → Menú |
| Registro de entrada | `checkin.html` | Guardar → Menú |
| Mis vuelos | `mis-vuelos.html` | Volver → Menú |


## Capturas de las vistas

| Iniciar sesión | Menú principal | Registro |
| --- | --- | --- |
| ![Iniciar sesión](docs/capturas/01-login.png) | ![Menú principal](docs/capturas/02-menu.png) | ![Registro](docs/capturas/03-registro.png) |

| Recuperar contraseña | Crear contraseña | Búsqueda de vuelos |
| --- | --- | --- |
| ![Recuperar contraseña](docs/capturas/04-recuperar-contrasena.png) | ![Crear contraseña](docs/capturas/05-crear-contrasena.png) | ![Búsqueda de vuelos](docs/capturas/06-buscar-vuelos.png) |

| Vuelos disponibles | Registro de entrada | Mis vuelos |
| --- | --- | --- |
| ![Vuelos disponibles](docs/capturas/07-vuelos-disponibles.png) | ![Registro de entrada](docs/capturas/08-registro-de-entrada.png) | ![Mis vuelos](docs/capturas/09-mis-vuelos.png) |


## Estructura del proyecto

```
acme-air-html-css/
├── index.html
├── menu.html
├── registro.html
├── crear-contraseña.html
├── buscar-vuelos.html
├── vuelos.html
├── checkin.html
├── mis-vuelos.html
├── recuperar.html
├── css/
│   ├── style.css
│   ├── forms.css
│   ├── layout.css
│   └── responsive.css
└── imagen/
    ├── logo.png
    ├── iconos/
    └── fondos/
```