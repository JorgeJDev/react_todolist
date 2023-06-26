### Eng: My first program using the React framework after eleven weeks of starting my Full Stack bootcamp. It creates a task list (ToDo List) through a form and saves the collected information in the LocalStorage.

### Esp: Mi primer programa utilizando el framework React después de once semanas de comenzar mi bootcamp en Full Stack. Se crea una lista de tareas (ToDo List) mediante un formulario, y guardando la información recopilada en el LocalStorage.

### Inicialización del proyecto:
Para inicializar el proyecto abrir la terminal y escribir los siguientes comandos:

Seleccionamos la carpeta en la terminal
```
yarn create vite
```
Creamos el nombre del proyecto y elegimos la tecnología y el lenguaje, en este caso React y Vainilla. Después iniciamos el proyecto y descargamos las librerias necesarias con
```
cd (nombre proyecto)
yarn
yarn vite
```
Ahora podremos inicializarlo con:
```


yarn dev
`````
Se abrirá el navegador en http://localhost:5173/

Se han usado las siguientes tecnologías con estas versiones:
```
"@types/react": "^18.0.28",
"@types/react-dom": "^18.0.11",
"@vitejs/plugin-react": "^3.1.0",
"vite": "^4.2.0"

````



### Funcionalidad principal:
Se ha realizado un programa para crear diferentes tareas y poder marcarlas como pendientes y también poder eliminarlas.

Para ello hemos diferenciado las diferentes funcionalidades en Hooks, reducers, helpers y componentes.