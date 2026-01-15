Registro de Usuarios en React

Este proyecto es una aplicación simple de registro de usuarios hecha con React. No es un CRUD completo, únicamente permite registrar usuarios y manejar el estado del formulario.

Funcionalidad

Formulario con campos:

Nombre

Email

Validación básica:

No permite enviar campos vacíos

Al enviar el formulario:

Se agrega el usuario al estado

Se limpia el formulario

Uso de componentes separados

Tecnologías usadas

React

Hooks:

useState

useEffect

useRef

CSS básico para estilos

Estructura del proyecto
src/
│
├── components/
│   └── UserForm.jsx
│
├── App.jsx
├── App.css
└── main.jsx

Componentes principales
UserForm

Maneja el estado del formulario

Controla los inputs con useState

Envía los datos al componente padre mediante props

App

Almacena la lista de usuarios

Genera IDs únicos usando useRef

Maneja la lógica para agregar nuevos usuarios

Instalación y ejecución

Clonar el repositorio

Instalar dependencias:

npm install


Ejecutar el proyecto:

npm run dev

Notas

No hay persistencia de datos

Los usuarios solo viven en memoria

Proyecto pensado como práctica de React y manejo de formularios
