Welcome file

# Guía Completa de React

## ¿Qué significa ser un programador front-end?

Un programador front-end es quien crea la parte visible e interactiva de una aplicación web o móvil. Su trabajo consiste en traducir diseños y conceptos en interfaces funcionales, atractivas y optimizadas para los usuarios finales. Este rol combina habilidades técnicas, creatividad y un profundo entendimiento de las necesidades de los usuarios.

El programador front-end actúa como puente entre los diseñadores y los desarrolladores back-end, asegurando que la lógica de negocio y la experiencia de usuario se unan de manera efectiva.

----------

## Día a día de un programador front-end

1.  Inicio del día: Planificación y comunicación

-   Participar en reuniones stand-up para sincronizar con el equipo (scrum/agile).
    
-   Revisar tareas asignadas en herramientas como Jira o Trello.
    
-   Leer y responder correos o mensajes en plataformas como Slack para aclarar dudas con diseñadores, PMs y back-end.
    

3.  Desarrollo de funcionalidades

-   Convertir diseños de herramientas como Figma o Adobe XD en componentes interactivos usando frameworks como React, Angular o Vue.js.
    
-   Implementar lógica de interacción con datos provenientes de APIs REST o GraphQL.
    
-   Diseñar y ajustar estilos utilizando CSS moderno, preprocesadores (SASS, LESS) o frameworks como TailwindCSS o Material UI.
    

5.  Colaboración y feedback

-   Trabajar junto al equipo de diseño para ajustar detalles como responsividad, animaciones y accesibilidad.
    
-   Revisar y refactorizar código junto a otros desarrolladores mediante pull requests en plataformas como GitHub.
    

7.  Pruebas y depuración

-   Escribir tests unitarios o de integración con herramientas como Jest o Cypress.
    
-   Depurar errores usando herramientas como Chrome DevTools.
    
-   Probar aplicaciones en diferentes navegadores y dispositivos para garantizar compatibilidad.
    

9.  Optimización

-   Mejorar tiempos de carga, tamaños de archivos y rendimiento general de la aplicación.
    
-   Implementar buenas prácticas como lazy loading, code splitting y el uso de CDNs.
    

11.  Aprendizaje continuo

-   Mantenerse al día con nuevas tecnologías, frameworks o herramientas.
    
-   Participar en foros, leer blogs o hacer cursos cortos para estar actualizado.
    

----------

## Habilidades necesarias para ser un buen desarrollador front-end

### Habilidades duras (técnicas):

1.  Lenguajes esenciales:

-   HTML5 y CSS3: Conocimiento profundo, incluyendo accesibilidad (WAI-ARIA) y buenas prácticas de semántica.
    
-   JavaScript: Manejo avanzado de ES6+, asincronía, DOM y herramientas modernas.
    

3.  Frameworks y librerías:

-   React, Vue o Angular para construir interfaces dinámicas y escalables.
    
-   Redux o Context API para manejo de estado global.
    

5.  Estilos y diseño:

-   Experiencia con CSS moderno (grid, flexbox) y frameworks (Bootstrap, TailwindCSS).
    
-   Conocimiento básico de diseño UX/UI y herramientas como Figma.
    

7.  Integración con el back-end:

-   Consumo de APIs REST y GraphQL.
    
-   Conocimiento básico de autenticación (OAuth, JWT) y seguridad en el front-end.
    

9.  Optimización:

-   Técnicas como lazy loading, pre-rendering y tree shaking.
    
-   Familiaridad con herramientas de bundling (Vite, Webpack) y análisis de performance (Lighthouse).
    

11.  Versionado y control de calidad:

-   Uso avanzado de Git.
    
-   Pruebas con Jest, Cypress, Testing Library.
    

### Habilidades blandas:

1.  Comunicación efectiva:

-   Capacidad para transmitir ideas técnicas a equipos no técnicos (diseño, negocio).
    
-   Escuchar activamente y dar feedback constructivo.
    

3.  Trabajo en equipo:

-   Colaborar con otros desarrolladores, diseñadores y gerentes de proyecto.
    
-   Adaptarse a entornos multiculturales y remotos.
    

5.  Resolución de problemas:

-   Pensamiento analítico para depurar errores.
    
-   Buscar soluciones rápidas sin comprometer calidad.
    

7.  Gestión del tiempo:

-   Priorizar tareas en sprints y cumplir plazos.
    
-   Capacidad de dividir problemas complejos en entregables pequeños.
    

9.  Curiosidad y adaptabilidad:

-   Aprender continuamente nuevas tecnologías y adaptarse a cambios rápidos.

11.  Atención al detalle:

-   Observar pequeñas inconsistencias en el diseño o el código.
    
-   Revisar minuciosamente el trabajo antes de enviarlo.
    

----------

## Desafíos de un desarrollador front-end

1.  Mantenerse actualizado con la constante evolución de herramientas y frameworks.
    
2.  Lograr equilibrio entre rendimiento, diseño y funcionalidad.
    
3.  Resolver problemas relacionados con compatibilidad entre navegadores y dispositivos.
    
4.  Colaborar con equipos grandes y multifuncionales, gestionando prioridades en tiempo real.
    

----------

## En resumen:

Un desarrollador front-end en 2024/2025 no solo escribe código; crea experiencias. Debe ser técnico, creativo, colaborador y siempre estar dispuesto a aprender. Es un rol que combina el arte de diseñar con la ciencia de construir, siempre poniendo al usuario en el centro de cada decisión.

# Introducción a React

React es una biblioteca de JavaScript diseñada para construir interfaces de usuario interactivas y dinámicas. Fue desarrollada por Facebook y lanzada en 2013. Su enfoque principal es hacer que el desarrollo de aplicaciones complejas sea más organizado y eficiente.

## Características principales de React

-   Declarativa: Describe lo que quieres mostrar en lugar de cómo hacerlo, simplificando el flujo de desarrollo.
    
-   Basada en componentes: Permite dividir la interfaz en piezas pequeñas, independientes y reutilizables.
    
-   Virtual DOM: Utiliza un DOM virtual para realizar cambios eficientes en el DOM real.
    
-   Unidireccionalidad de datos: La comunicación fluye desde los componentes padres hacia los hijos, haciendo que el estado y las propiedades sean más predecibles.
    

## ¿Por qué React es popular?

-   Fácil de aprender para quienes conocen JavaScript.
    
-   Gran ecosistema y comunidad activa.
    
-   Flexibilidad para integrarse con otras herramientas y bibliotecas.
    

----------

## 🚀 Creación de un Proyecto React con Vite

Vite es una herramienta de construcción rápida para proyectos frontend. Nos permite configurar un proyecto de React de manera rápida y optimizada.

---

### 🛠️ Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- [Node.js](https://nodejs.org/) (versión 16 o superior recomendada)
- npm (que viene incluido con Node.js)

Puedes verificar si están instalados ejecutando:

```sh
node -v
npm -v
```
Si ambos comandos devuelven una versión, estás listo para continuar.

### 🔧 Paso a Paso: Creando un Proyecto React con Vite
#### 1️⃣ Abrir la Terminal
Abre la terminal en la ubicación donde deseas crear tu proyecto.

#### 2️⃣ Ejecutar el Comando de Creación
Ejecuta el siguiente comando:

```sh
npm create vite@latest
```

## 🔍 Explicación del comando:

**npm**: Es el gestor de paquetes de Node.js.  
**create**: Indica que vamos a crear un nuevo proyecto.  
**vite@latest**: Especifica que vamos a usar la última versión de Vite para la creación del proyecto.

### 3️⃣ Configurar el Proyecto
Tras ejecutar el comando, la terminal te pedirá que ingreses un nombre para tu proyecto. Escribe el nombre deseado (por ejemplo, ``mi-proyecto-vite``) y presiona Enter.

Luego, te pedirá que selecciones el framework. Usa las flechas del teclado para elegir ``React`` y presiona ``Enter``.

A continuación, te pedirá que selecciones una variante de JavaScript:

``JavaScript`` (JS puro)  
``TypeScript`` (con soporte de TypeScript)  

Selecciona la opción de ``JavaScript``

### 4️⃣ Acceder al Proyecto
Una vez creado el proyecto, entra en la carpeta del mismo con:

```sh
cd mi-proyecto-vite
```
(Recuerda reemplazar mi-proyecto-vite con el nombre de tu proyecto).

### 5️⃣ Instalar Dependencias
Ahora instala las dependencias con:
```sh
npm install
```
#### 🔍 Explicación del comando:

``npm install`` o ``npm i``: Descarga e instala todas las dependencias necesarias para el proyecto.

### 6️⃣ Ejecutar el Proyecto
Para iniciar el servidor de desarrollo y ver tu aplicación en el navegador, usa:

```sh
npm run dev
```
#### 🔍 Explicación del comando:

``npm run dev``: Inicia el servidor de desarrollo de Vite y te proporciona una URL (generalmente ``http://localhost:5173``) para visualizar la aplicación.

### 🎉 ¡Listo! Tu Proyecto React con Vite está Funcionando
Ahora puedes comenzar a desarrollar tu aplicación en el directorio ``src/``, donde encontrarás el archivo ``App.jsx`` (o ``App.tsx`` si elegiste TypeScript).

Para detener el servidor de desarrollo, presiona ``Ctrl + C`` en la terminal.

---
# 📁 Estructura del Proyecto
Al crear el proyecto, se generarán varios archivos y carpetas:
 ```php
 mi-proyecto-vite/
├── node_modules/      # Dependencias instaladas
├── public/            # Archivos estáticos
├── src/               # Código fuente del proyecto
│   ├── App.jsx        # Componente principal
│   ├── main.jsx       # Punto de entrada de la app
│   ├── index.css      # Estilos globales
│   └── assets/        # Carpeta para imágenes u otros recursos
├── .gitignore         # Archivos ignorados por Git
├── index.html         # Archivo HTML principal
├── package.json       # Información y dependencias del proyecto
├── vite.config.js     # Configuración de Vite
└── README.md          # Archivo de documentación del proyecto
 ```
Con esto, ya tienes una base sólida para comenzar a desarrollar en React con Vite. 🚀✨

## 📌 Comandos Útiles en el Proyecto

| Comando           | Descripción |
|------------------|-------------|
| `npm install`    | Instala las dependencias del proyecto |
| `npm run dev`    | Inicia el servidor de desarrollo |
| `npm run build`  | Genera una versión optimizada para producción |
| `npm run preview` | Sirve la aplicación para probar la versión de producción |

¡Ahora puedes comenzar a construir tu aplicación React con Vite de forma rápida y eficiente! 🚀🎨

----------

# JSX y Componentes en React

### JSX: La mezcla de JavaScript y HTML

¿Qué es JSX? JSX (JavaScript XML) es una extensión de JavaScript que permite escribir una combinación de HTML y JavaScript en el mismo archivo. Es una característica clave en React que simplifica la creación de interfaces de usuario al permitir expresar la estructura visual de manera más clara.

Aunque no es obligatorio usar JSX, es ampliamente adoptado porque:

-   Facilita la lectura y el mantenimiento del código.
    
-   Permite aprovechar las características de JavaScript directamente en las plantillas.
    
-   Mejora la integración entre la lógica y la estructura visual.
    

### Ejemplo básico de JSX:

```
const element = <h1>Hola, mundo!</h1>;

```

Esto es equivalente a:

const element = React.createElement(‘h1’, null, ‘Hola, mundo!’);

### Características clave de JSX:

Expresiones JavaScript: Puedes usar expresiones dentro de llaves ({}) en JSX.  
const name = ‘Juan’;

1.  `const element = <h1>Hola, {name}!</h1>;`
    
2.  Atributos: Los elementos JSX pueden tener atributos, similares a HTML, pero algunos nombres difieren (e.g., className en lugar de class).
    
    `const element = <div className="contenedor">Contenido</div>;`
    

Fragmentos: JSX permite envolver múltiples elementos en un contenedor usando <> o React.Fragment.  
return (

```
<>
<h1>Título</h1>
<p>Descripción</p>
</>

```

### ¿Qué son los componentes en React?

Los componentes son como bloques de construcción para una aplicación en React. Piensa en ellos como piezas de Lego que puedes usar para armar una interfaz de usuario (UI). Cada componente es una parte independiente de la pantalla, como un botón, un menú, una tarjeta o incluso una página completa.

-   Funcionalidad: Cada componente puede tener su propia lógica (cómo funciona) y su propia apariencia (cómo se ve).
    
-   Reutilización: Puedes usar el mismo componente en diferentes partes de tu aplicación sin tener que repetir código.
    
-   Organización: Los componentes ayudan a dividir la aplicación en partes más pequeñas y manejables.
    

----------

### Tipos de componentes

#### 1\. Componentes funcionales

Los componentes funcionales son como funciones de JavaScript que retornan algo que se va a mostrar en la pantalla (usando JSX, que es una mezcla de HTML y JavaScript).

-   Simple: Son fáciles de escribir y entender.
    
-   Props: Reciben datos a través de un objeto llamado props (abreviatura de “properties” o propiedades).
    
-   Hooks: Desde React 16.8, los componentes funcionales pueden manejar estados y otras características avanzadas usando Hooks (como useState o useEffect).
    

Ejemplo detallado:

```
// Definimos un componente funcional llamado "Saludo"

const  Saludo = (props) =>  {
// props.nombre es el dato que recibimos desde fuera

return  <h1>Hola,  {props.nombre}!</h1>;    
};

// Usamos el componente en otra parte de la aplicación

const  App  =  ()  =>  {
return  (
<div>
<Saludo nombre="Juan"  />  {/* Aquí pasamos el nombre "Juan" como prop */}
<Saludo nombre="Ana"  />  {/* Reutilizamos el componente con otro nombre */}
</div>
);}
}}

```

¿Qué está pasando aquí?

1.  Creamos un componente llamado Saludo que recibe un props (en este caso, nombre).
2.  Usamos props.nombre para mostrar un mensaje personalizado.
3.  En el componente App, usamos dos veces, pasando diferentes nombres.

#### 2\. Componentes de clase

Los componentes de clase son como clases de JavaScript que heredan de React.Component. Son más complejos que los funcionales y se usaban mucho antes de la introducción de los Hooks.

-   Estado: Pueden manejar un estado interno (datos que pueden cambiar).
    
-   Ciclos de vida: Tienen métodos especiales como componentDidMount o componentDidUpdate que permiten ejecutar código en momentos específicos (por ejemplo, cuando el componente se carga o se actualiza).
    

Ejemplo detallado:

```
// Definimos un componente de clase llamado "Saludo"

class Saludo extends React.Component {
// El método render() define lo que se va a mostrar
render()  {
return  <h1>Hola,  {this.props.nombre}!</h1>;
}
}

```

// Usamos el componente en otra parte de la aplicación

```
class  App  extends  React.Component  {

render()  {
return  (
<div>
<Saludo nombre="Juan"  />  {/* Pasamos el nombre "Juan" como prop */}
<Saludo nombre="Ana"  />  {/* Reutilizamos el componente con otro nombre */}
</div>
);    
}

```

¿Qué está pasando aquí?

1.  Creamos una clase Saludo que extiende React.Component.
    
2.  Usamos this.props.nombre para acceder a los datos que recibimos desde fuera.
    
3.  En el componente App, usamos dos veces, pasando diferentes nombres.
    

----------

### ¿Por qué se prefieren los componentes funcionales?

Desde la introducción de los Hooks en React 16.8, los componentes funcionales se han vuelto más populares porque:

1.  Son más simples: No necesitas escribir una clase completa.
    
2.  Hooks: Puedes manejar estados y ciclos de vida con funciones como useState y useEffect.
    
3.  Menos código: Son más fáciles de leer y mantener.
    

Ejemplo con Hooks:

```
import React,  { useState }  from  'react';

  

const  Contador  =  ()  =>  {

// Usamos useState para manejar el estado "contador"

const  [contador, setContador]  =  useState(0);

return  (
<div>
<p>Has hecho clic {contador} veces</p>
<button onClick={()  =>  setContador(contador +  1)}>Haz clic</button>
</div>); ]
}

```

----------

### Ventajas de usar componentes

1.  Reutilización:

-   Puedes usar el mismo componente en diferentes partes de tu aplicación.
    
-   Ejemplo: Un botón personalizado que puedes usar en múltiples pantallas.
    

3.  Legibilidad:

-   Al dividir la aplicación en componentes, el código es más fácil de entender.
    
-   Ejemplo: Un componente Header para la cabecera y un componente Footer para el pie de página.
    

5.  Mantenimiento:

-   Si algo falla, es más fácil encontrar y arreglar el problema en un componente específico.
    
-   Ejemplo: Si un botón no funciona, solo necesitas revisar el componente Boton.
    

----------

## Props y Renderizado Dinámico

### Props: Propiedades de los componentes

¿Qué son las props? Las props (abreviación de “propiedades”) son datos que se pasan de un componente padre a un componente hijo. Estas permiten personalizar el comportamiento y la apariencia de un componente.

#### Características de las props:

-   De solo lectura: Un componente hijo no puede modificar las props que recibe.
    
-   Flexibles: Se pueden pasar cualquier tipo de datos, como cadenas, números, objetos, funciones, etc.
    

#### Ejemplo básico de props:

```
const Tarjeta = (props) => {

return (
<div>
<h1>{props.titulo}</h1>
<p>{props.descripcion}</p>
</div>
);
};

const App = () => {
return (
<Tarjeta titulo="Bienvenido" descripcion="Este es un ejemplo de props." />
);
};

```

### Renderizado dinámico

El renderizado dinámico permite crear interfaces adaptables según las props o el estado del componente.

#### Ejemplo de renderizado dinámico:

```
const Lista = (props) => {

return (

<ul>

{props.items.map((item, index) => (

<li key={index}>{item}</li>

))}

</ul>

);

};

  

const App = () => {

const frutas = ['Manzana', 'Pera', 'Naranja'];

return <Lista items={frutas} />;

};

```

En este ejemplo:

-   La lista se renderiza dinámicamente en función del array frutas.
    
-   Cada elemento del array se convierte en un `<li>.`
    
    ----------
    

# Configuración de Aplicaciones en React

## 1\. Herramientas de configuración

### 1.1 Create React App (CRA)

Create React App es una herramienta oficial de React que permite configurar un proyecto rápidamente sin necesidad de preocuparse por la configuración inicial. Incluye todo lo necesario para empezar a desarrollar, como Babel y Webpack.

#### Cómo usar Create React App

1.  Instalación:
    
2.  npx create-react-app nombre-del-proyecto
    
3.  Estructura generada:
    

-   src/: Contiene el código fuente de la aplicación.
    
-   public/: Contiene archivos estáticos como index.html.
    
-   package.json: Define las dependencias y scripts del proyecto.
    

5.  Iniciar el servidor de desarrollo:

cd nombre-del-proyecto

5.  npm start

#### Ventajas de CRA

-   Configuración preestablecida: No es necesario configurar Babel o Webpack manualmente.
    
-   Fácil de usar: Ideal para principiantes y proyectos pequeños.
    
-   Soporte para pruebas: Incluye Jest y React Testing Library.
    

----------

### 1.2 Vite

Vite es una herramienta moderna que ofrece una experiencia de desarrollo más rápida en comparación con CRA. Utiliza ES modules nativos del navegador para servir el código, lo que acelera el tiempo de compilación.

#### Cómo usar Vite

1.  Instalación:  
    `npm create vite@latest nombre-del-proyecto`
    
2.  Seleccionar plantilla:
    

-   Elige React como framework.
    
-   Elige JavaScript o TypeScript como variante.
    

5.  Estructura generada:

-   src/: Contiene el código fuente de la aplicación.
    
-   index.html: Punto de entrada de la aplicación.
    
-   vite.config.js: Configuración personalizada de Vite.
    

7.  Iniciar el servidor de desarrollo:
    
    ```
    cd nombre-del-proyecto
    
    npm  install
    
    ```
    
8.  npm run dev
    

#### Ventajas de Vite

-   Rendimiento rápido: Menor tiempo de compilación y recarga en caliente (HMR).
    
-   Configuración flexible: Permite personalizar la configuración fácilmente.
    
-   Moderno: Soporte nativo para ES modules y TypeScript.
    

----------

## 2\. Estructura básica de un proyecto React

### 2.1 Archivo de entrada

El archivo de entrada es el punto donde React interactúa con el DOM para renderizar la aplicación. Suele llamarse index.js o main.jsx.

#### Ejemplo de index.js

```
import React from  'react';

import ReactDOM from  'react-dom';

import App from  './App';

  

ReactDOM.render(

<React.StrictMode>

<App />

</React.StrictMode>,

document.getElementById('root')

);

```

#### Explicación

1.  ReactDOM.render: Renderiza el componente App en el elemento con id root del archivo index.html.
    
2.  React.StrictMode: Es una herramienta de desarrollo que ayuda a identificar problemas potenciales en la aplicación.
    

----------

### 2.2 Componentes

Los componentes son la base de una aplicación React. Se organizan en la carpeta src/components/.

#### Ejemplo de estructura de componentes

src/

├── components/

│ ├── Header.jsx

│ ├── Footer.jsx

│ └── MainContent.jsx

├── App.jsx

└── index.js

----------

### 2.3 Estilos

Los estilos se pueden agregar usando archivos CSS, módulos CSS o bibliotecas como Styled Components.

#### Ejemplo de archivo CSS

```
/* src/styles.css */

body  {

font-family: Arial, sans-serif;

}

  

.header  {

background-color: #333;

color: white;

padding: 10px;

}

```

#### Uso en un componente

```
import  './styles.css';

  

const  Header  =  ()  =>  {

return  <header className="header">Bienvenido a mi aplicación</header>;

};

```

----------

# Eventos y Manejo de Formularios en React

## 1\. Manejo de eventos

### 1.1 Introducción

En React, los eventos se manejan de manera similar a los eventos en el DOM, pero con algunas diferencias clave:

-   Los nombres de los eventos son camelCase (por ejemplo, onClick en lugar de onclick).
    
-   Los manejadores de eventos son funciones que se pasan como props.
    

#### Ejemplo básico

#### const Boton = () => {

```
const  handleClick  =  ()  =>  {

alert('Botón clickeado');

};
return  <button onClick={handleClick}>Haz clic</button>;

};

```

#### Explicación

1.  onClick: Es el evento que se dispara cuando el usuario hace clic en el botón.
    
2.  handleClick: Es la función que se ejecuta cuando ocurre el evento.
    

----------

### 1.2 Pasar parámetros a manejadores de eventos

Si necesitas pasar parámetros a un manejador de eventos, puedes usar una función anónima.

#### Ejemplo

#### const Boton = ({ nombre }) => {

```
const  handleClick  =  (nombre)  =>  {

alert(`Hola, ${nombre}!`);

};



return  (

<button onClick={()  =>  handleClick(nombre)}>Saludar</button>

);

};

```

Lista de eventos más usados en React

1.  Eventos del mouse

onClick: Se activa cuando se hace clic en un elemento.

```
<button onClick={() => alert('Clickeado')}>Haz clic</button>

```

onDoubleClick: Se activa cuando se hace doble clic en un elemento.

```
<div onDoubleClick={() => alert('Doble clic')}>Haz doble clic</div>

```

onMouseEnter: Se activa cuando el puntero del mouse entra en un elemento.

```
<div onMouseEnter={() => console.log('Mouse entró')}>Pasa el mouse</div>

```

onMouseLeave: Se activa cuando el puntero del mouse sale de un elemento.

```
<div onMouseLeave={() => console.log('Mouse salió')}>Pasa el mouse</div>

```

onMouseMove: Se activa cuando el puntero del mouse se mueve sobre un elemento.

```
<div onMouseMove={(e) => console.log(`Posición: ${e.clientX}, ${e.clientY}`)}>

Mueve el mouse

</div>

```

2.  Eventos del teclado

onKeyDown: Se activa cuando una tecla se presiona.

```
<input onKeyDown={(e) => console.log(`Tecla presionada: ${e.key}`)} />

```

onKeyUp: Se activa cuando una tecla se suelta.

```
<input onKeyUp={(e) => console.log(`Tecla liberada: ${e.key}`)} />

```

onKeyPress: Se activa cuando una tecla se presiona y se suelta (no se recomienda su uso en React moderno; en su lugar, usa onKeyDown o onKeyUp).

3.  Eventos de formularios

onChange: Se activa cuando el valor de un campo de formulario cambia (por ejemplo, en un , o ).

```
<input onChange={(e) => console.log(`Valor: ${e.target.value}`)} />

```

onSubmit: Se activa cuando se envía un formulario.

```
<form onSubmit={(e) => { e.preventDefault(); alert('Formulario enviado'); }}>

<button type="submit">Enviar</button>

</form>

```

onFocus: Se activa cuando un elemento recibe el foco (por ejemplo, al hacer clic en un ).

```
<input onFocus={() => console.log('Input enfocado')} />

```

onBlur: Se activa cuando un elemento pierde el foco (por ejemplo, al hacer clic fuera de un ).

```
<input onBlur={() => console.log('Input perdió el foco')} />

```

4.  Eventos de la ventana

onScroll: Se activa cuando se desplaza la ventana o un elemento con scroll.

```
<div onScroll={() => console.log('Desplazamiento detectado')} style={{ height: '100px', overflow: 'scroll' }}>

```

Desplázame

onResize: Se activa cuando se redimensiona la ventana.

```
window.addEventListener('resize', () => console.log('Ventana redimensionada'));

```

5.  Eventos de arrastrar y soltar (Drag and Drop)

onDrag: Se activa cuando un elemento se arrastra.

```
<div draggable onDrag={() => console.log('Arrastrando')}>Arrástrame</div>

```

onDragStart: Se activa cuando comienza el arrastre de un elemento.

```
<div draggable onDragStart={() => console.log('Arrastre iniciado')}>Arrástrame</div>

```

onDragEnd: Se activa cuando termina el arrastre de un elemento.

```
<div draggable onDragEnd={() => console.log('Arrastre finalizado')}>Arrástrame</div>

```

onDrop: Se activa cuando un elemento se suelta en una zona de destino.

```
<div onDrop={() => console.log('Elemento soltado')}>Suelta aquí</div>

```

6.  Eventos de medios

onPlay: Se activa cuando un elemento multimedia (como un video) comienza a reproducirse.

```
<video onPlay={() => console.log('Video reproducido')} controls>

<source src="video.mp4" type="video/mp4" />

</video>

```

onPause: Se activa cuando un elemento multimedia se pausa.

```
<video onPause={() => console.log('Video pausado')} controls>

<source src="video.mp4" type="video/mp4" />

</video>

```

onEnded: Se activa cuando un elemento multimedia termina de reproducirse.

<video onEnded={() => console.log(‘Video terminado’)} controls>

7.  Eventos de toque (Touch)

onTouchStart: Se activa cuando un usuario toca la pantalla.

onTouchMove: Se activa cuando un usuario mueve el dedo sobre la pantalla.

onTouchEnd: Se activa cuando un usuario deja de tocar la pantalla.

```
<div onTouchEnd={() => console.log('Toque finalizado')}>Tócame</div>

```

# Interacción con APIs en React

## 1\. ¿Qué es una API?

Una API (Interfaz de Programación de Aplicaciones) es como un “mensajero” que permite que dos aplicaciones se comuniquen entre sí. Por ejemplo, cuando usas una aplicación del clima en tu teléfono, esta se conecta a una API para obtener datos actualizados sobre el clima.

En React, puedes usar APIs para obtener datos de un servidor y mostrarlos en tu aplicación.

## 2\. ¿Cómo interactuar con una API en React?

Para interactuar con una API en React, seguimos estos pasos:

1.  Hacer una solicitud a la API: Usamos funciones como fetch o bibliotecas como axios para pedir datos a la API.
    
2.  Procesar la respuesta: Una vez que la API responde, convertimos los datos a un formato que React pueda entender (generalmente JSON).
    
3.  Mostrar los datos: Usamos el estado de React para almacenar los datos y mostrarlos en la interfaz de usuario.
    

## 3\. Ejemplo práctico: Obtener datos de una API

Vamos a crear un componente que obtenga datos de una API y los muestre en una lista.

### Paso 1: Crear un componente

Creamos un componente funcional llamado ListaUsuarios.

```
import React, { useState, useEffect } from 'react';

const ListaUsuarios = () => {

const [usuarios, setUsuarios] = useState([]); // Estado para almacenar los usuarios

  
return (
<div>
<h1>Lista de Usuarios</h1>
<ul>
{usuarios.map((usuario) => (
<li key={usuario.id}>{usuario.name}</li>

))}
</ul>
</div>
);
};
export default ListaUsuarios;

```

#### Explicación

1.  useState: Creamos un estado llamado usuarios para almacenar la lista de usuarios que obtengamos de la API.
    
2.  usuarios.map: Recorremos la lista de usuarios y mostramos cada uno en un elemento
    
3.  .

### Paso 2: Hacer la solicitud a la API

Usamos fetch para obtener datos de una API de ejemplo (por ejemplo, \[JSONPlaceholder\]`(https://jsonplaceholder.typicode.com/users)).`

```
import React, { useState, useEffect } from 'react';

const ListaUsuarios = () => {

const [usuarios, setUsuarios] = useState([]);

// Usamos useEffect para hacer la solicitud cuando el componente se monta
useEffect(() => {

fetch('https://jsonplaceholder.typicode.com/users')

.then((response) => response.json()) // Convertimos la respuesta a JSON
.then((data) => setUsuarios(data)) // Guardamos los datos en el estado
.catch((error) => console.error('Error:', error)); // Manejo de errores
}, []); // El array vacío [] significa que esto se ejecuta solo una vez

return (
<div>
<h1>Lista de Usuarios</h1>
<ul>
{usuarios.map((usuario) => (
<li key={usuario.id}>{usuario.name}</li>
))}
</ul>
</div>
);

};
export default ListaUsuarios;

```

#### Explicación

1.  `useEffect`: Es un Hook de React que nos permite ejecutar código cuando el componente se monta (es decir, cuando aparece en la pantalla).
    
2.  `fetch`: Hace una solicitud a la API y devuelve una promesa.
    
3.  `.then(response => response.json()):` Convierte la respuesta de la API a formato JSON.
    
4.  `.then(data => setUsuarios(data))`: Guarda los datos en el estado usuarios.
    
5.  `.catch:` Captura y maneja errores si la solicitud falla.
    

### Paso 3: Probar el componente

Si ejecutas este componente, verás una lista de nombres de usuarios obtenidos de la API.

----------

## 4\. Alternativa: Usar Axios

axios es una biblioteca popular para hacer solicitudes HTTP. Es más fácil de usar que fetch y tiene características adicionales, como la transformación automática de datos JSON.

### Instalación de Axios

```
npm install axios

```

Ejemplo con axios

```
import React, { useState, useEffect } from 'react';

import axios from 'axios';
  
const ListaUsuarios = () => {

const [usuarios, setUsuarios] = useState([]);

useEffect(() => {
    axios.get('https://jsonplaceholder.typicode.com/users')
    
.then((response) => setUsuarios(response.data)) // response.data contiene los datos
.catch((error) => console.error('Error:', error));
}, []);

return (
<div>
<h1>Lista de Usuarios</h1>
<ul>
{usuarios.map((usuario) => (
<li key={usuario.id}>{usuario.name}</li>
))}
</ul>
</div>
);
};
export default ListaUsuarios;

```

#### Ventajas de Axios

-   Transformación automática: No necesitas convertir manualmente la respuesta a JSON.
    
-   Manejo de errores: Proporciona un manejo de errores más detallado.
    
-   Interceptores: Permite modificar las solicitudes y respuestas globalmente.
    

## 5\. Enviar datos a una API (POST)

Además de obtener datos, puedes enviar datos a una API usando fetch o axios.

### Ejemplo con fetch

```
const enviarUsuario = () => {

const nuevoUsuario = { name: 'Juan', email: 'juan@example.com' };
fetch('https://jsonplaceholder.typicode.com/users', {
method: 'POST',
headers: {
'Content-Type': 'application/json',
},
body: JSON.stringify(nuevoUsuario), // Convertimos el objeto a JSON

})
.then((response) => response.json())
.then((data) => console.log('Usuario creado:', data))
.catch((error) => console.error('Error:', error));
};

```

### Ejemplo con axios:

```
const enviarUsuario = () => {

const nuevoUsuario = { name: 'Juan', email: 'juan@example.com' };

axios.post('https://jsonplaceholder.typicode.com/users', nuevoUsuario)

.then((response) => console.log('Usuario creado:', response.data))

.catch((error) => console.error('Error:', error));

};

```

## 6\. Consejos para trabajar con APIs en React

1.  Manejo de carga: Muestra un mensaje de “Cargando…” mientras se obtienen los datos.
    
    ```
    const  [cargando, setCargando]  =  useState(true);
    useEffect(()  =>  {
    fetch('https://jsonplaceholder.typicode.com/users')
    
    .then((response)  => response.json())
    .then((data)  =>  {
    
    setUsuarios(data);
    setCargando(false);  // Desactiva el estado de carga
    
    });
        },  []);
    
    ```
    

`if (cargando) return <p>Cargando...</p>;`

3.  Manejo de errores: Muestra un mensaje de error si la solicitud falla.

Codigo:

```
const  [error, setError]  =  useState(null);
useEffect(()  =>  {
fetch('https://jsonplaceholder.typicode.com/users')
.then((response)  => response.json())
.then((data)  =>  setUsuarios(data))
.catch((error)  =>  setError(error.message));  // Guarda el mensaje de error
},  []);
  if  (error)  return  <p>Error:  {error}</p>;

```

5.  Optimización: Usa useEffect correctamente para evitar solicitudes innecesarias.

----------

## 7\. Conclusión

Interactuar con APIs en React es una habilidad esencial para crear aplicaciones dinámicas. Ya sea que uses fetch o axios, el proceso consiste en:

1.  Hacer una solicitud a la API.
    
2.  Procesar la respuesta.
    
3.  Mostrar los datos en la interfaz.
    

## Integración de React con Tailwind CSS

Tailwind CSS es un framework de CSS que te permite diseñar interfaces rápidamente usando clases utilitarias. En lugar de escribir CSS tradicional, aplicas clases directamente en tu JSX.

### Pasos para integrar Tailwind CSS en React:

Instalar Tailwind CSS: `npm install tailwindcss`

Configurar Tailwind:

-   Crea un archivo de configuración: `npx tailwindcss init`
    
-   Configura el archivo tailwind.config.js para incluir tus archivos de React
    

## Agregar Tailwind a tu CSS:

-   En tu archivo src/index.css, agrega:
    
-   `@tailwind base;`
    
-   `@tailwind components;`
    
-   `@tailwind utilities;`
    
    Usar Tailwind en tus componentes:
    
-   Aplica clases directamente en tu JSX:
    
-   ```
     const  MiComponente  =  ()  =>  {
     return  ( <div  className="bg-blue-500 text-white p-4">
      Hola, Tailwind CSS!
      </div>     ); };
    
    ```
    

----------

## Almacenamiento Local y Manejo de Datos

El almacenamiento local (localStorage) es una forma de guardar datos en el navegador del usuario. Es útil para persistir información como preferencias, tokens de autenticación, etc.

### Cómo usar localStorage en React:

Guardar datos: `localStorage.setItem('clave', 'valor');`

Leer datos: `const valor = localStorage.getItem('clave');`

Eliminar datos: `localStorage.removeItem('clave');`

### Ejemplo en React:

```
const  GuardarDatos  =  ()  =>  {
const  [nombre, setNombre]  = React.useState('');
const  guardar  =  ()  =>  {
localStorage.setItem('nombre', nombre);
}
return  (
<div>
<input
type="text"
value={nombre}
onChange={(e) => setNombre(e.target.value)}
/>
<button onClick={guardar}>Guardar</button>
</div>
);
  };

```

## Buenas Prácticas para el Manejo de Datos

Aquí tienes algunas recomendaciones para manejar datos de manera eficiente en React:

1.  Mantén el estado localizado:

-   No almacenes todo el estado en un componente padre. Divide el estado en componentes más pequeños y específicos.

3.  Usa Context API o Redux para estado global:

-   Si necesitas compartir estado entre muchos componentes, usa Context API o Redux.

5.  Evita renderizados innecesarios:

-   Usa React.memo para memorizar componentes y evitar que se rendericen si sus props no cambian.
    
-   Usa useCallback y useMemo para optimizar funciones y cálculos costosos.
    

7.  Manejo de errores:

-   Siempre valida los datos antes de guardarlos en el estado o en localStorage.
    
-   Usa try-catch para manejar errores en operaciones asíncronas.
    

9.  Separa la lógica de la UI:

-   Mantén la lógica de negocio (como llamadas a APIs o manejo de datos) separada de los componentes de UI.

11.  Usa TypeScript (opcional pero recomendado):

-   TypeScript te ayuda a detectar errores de tipos antes de que ocurran, lo que mejora la calidad del código.

## Ejemplo Práctico

Vamos a crear una pequeña aplicación que usa React, Tailwind CSS y localStorage para guardar y mostrar una lista de tareas.

### Código:

```
import React,  { useState }  from  'react';

const  App= () =>  {
const  [tareas, setTareas]  =  useState([]);
const  [nuevaTarea, setNuevaTarea]  =  useState('');

const  agregarTarea  =  ()  =>  {
if  (nuevaTarea.trim()  ===  '')  return;
const nuevasTareas =  [...tareas, nuevaTarea];
setTareas(nuevasTareas);
localStorage.setItem('tareas',  JSON.stringify(nuevasTareas));
setNuevaTarea('');
};

React.useEffect(()  =>  {
const tareasGuardadas =  JSON.parse(localStorage.getItem('tareas'))  ||  [];
setTareas(tareasGuardadas);
},  []);

return  (
<div className="p-4">
<h1 className="text-2xl font-bold mb-4">Lista de Tareas</h1>

<input
type="text"
value={nuevaTarea}
onChange={(e) => setNuevaTarea(e.target.value)}
className="border p-2 mr-2"
placeholder="Nueva tarea"
/>
<button onClick={agregarTarea} className="bg-blue-500 text-white p-2">
Agregar
</button>
<ul className="mt-4">
{tareas.map((tarea, index)  =>  (
<li key={index} className="mb-2">
{tarea}
</li>
))}
</ul>
</div>
);
};
export  default App;

```

## Hooks

Los hooks en React son funciones que permiten usar características avanzadas, como el estado y el ciclo de vida, en componentes funcionales. Fueron introducidos en la versión 16.8 para mejorar la reutilización de lógica y simplificar el desarrollo en React.

## ¿Qué son los hooks y por qué son útiles?

### Definición

Un hook es una función especial de React que extiende las capacidades de los componentes funcionales. Los hooks permiten:

-   Manejar el estado del componente.
-   Gestionar efectos secundarios (como llamadas a APIs).
-   Reutilizar lógica sin necesidad de usar componentes de clase.

### Reglas de los hooks

1.  Solo se llaman en el nivel superior: No se pueden usar dentro de bucles, condicionales o funciones anidadas.
    
2.  Solo se llaman dentro de componentes funcionales o hooks personalizados: No se pueden usar en funciones normales.
    

## Hooks básicos

### useState

Permite manejar el estado en un componente funcional. Es útil para almacenar datos que cambian con el tiempo, como entradas de usuario o información dinámica.

-   Características:
-   Retorna un valor de estado y una función para actualizarlo.
-   Los cambios de estado provocan un nuevo renderizado del componente.

### useEffect

Se utiliza para manejar efectos secundarios, como:

-   Llamadas a APIs.
-   Manipulación del DOM.
-   Subscripciones a eventos.
-   Características:
-   Puede ejecutarse después del renderizado inicial, cuando cambian ciertas dependencias o al desmontarse un componente.
-   Admite una función de limpieza para manejar tareas como desuscripciones.

### useContext

Permite acceder a valores almacenados en un contexto sin necesidad de pasar props manualmente por cada nivel de la jerarquía de componentes.

-   Características:
-   Facilita compartir información como temas, configuraciones o datos globales.
-   Funciona en conjunto con React.createContext.

## Hooks adicionales

### useReducer

Es una alternativa a useState para manejar estados complejos o múltiples valores relacionados. Funciona de forma similar a un reducer en Redux.

-   Características:
-   Utiliza una función reductora que recibe el estado actual y una acción para calcular el nuevo estado.
-   Útil para manejar lógica de actualización más compleja.

### useRef

Proporciona una referencia mutable que persiste durante el ciclo de vida del componente. Comúnmente se utiliza para:

-   Acceder a elementos del DOM directamente.
-   Almacenar valores que no provocan renderizados, como contadores.

### useMemo

Optimiza el rendimiento de los componentes al memorizar valores calculados. Solo vuelve a calcular el resultado si cambian sus dependencias.

-   Características:
-   Útil para evitar cálculos costosos innecesarios.
-   No memoriza funciones, solo valores.

### useCallback

Devuelve una función memorizada para evitar que se cree una nueva en cada renderizado. Es útil cuando pasas funciones como props a componentes hijos.

### useLayoutEffect

Es similar a useEffect, pero se ejecuta antes de que el navegador realice los dibujos en pantalla. Esto lo hace ideal para casos donde necesitas medir o modificar el DOM inmediatamente.

## Hooks personalizados

### Cómo crear un hook personalizado

Un hook personalizado es simplemente una función de JavaScript que:

1.  Empieza con “use” en su nombre (esto es obligatorio para que React lo reconozca como hook).
2.  Puede usar otros hooks como useState, useEffect, useContext, etc.
3.  Devuelve valores o funciones que el componente que lo use necesite.

### Ejemplos comunes

#### 1\. Manejo de formularios

Un hook personalizado para manejar el estado de un formulario podría simplificar la gestión de inputs.

```
import { useState } from 'react';

function useForm(initialValues) {
const [values, setValues] = useState(initialValues);

const handleChange = (event) => {
const { name, value } = event.target;

setValues({
...values,
[name]: value,
});
};

return [values, handleChange];
}

```

Uso:

```
function FormComponent() {
const [formValues, handleInputChange] = useForm({ name: '', email: '' });

const handleSubmit = (e) => {
e.preventDefault();
console.log('Submitted values:', formValues);
};

return (
<form onSubmit={handleSubmit}>
<input name="name" value={formValues.name} onChange={handleInputChange} />
<input name="email" value={formValues.email} onChange={handleInputChange} />

<button type="submit">Submit</button>   
</form>
);
}

```

#### 2\. Conexión con APIs

Puedes crear un hook que encapsule la lógica para hacer solicitudes HTTP.

```
import { useState, useEffect } from 'react';

function useFetch(url) {

const [data, setData] = useState(null);
const [loading, setLoading] = useState(true);
const [error, setError] = useState(null);

useEffect(() => {
async function fetchData() {

try {
const response = await fetch(url);
const result = await response.json();
setData(result);
} catch (err) {

setError(err);   
} finally {
setLoading(false);
}
}

fetchData();
}, [url]);
   return { data, loading, error };
}

```

Uso:

```
function DataComponent() {
const { data, loading, error } = useFetch('https://api.example.com/data');

if (loading) return <p>Loading...</p>;
if (error) return <p>Error: {error.message}</p>;
return <div>{JSON.stringify(data)}</div>;
}

```

#### 3\. Manejo de autenticación

Si tu aplicación tiene autenticación, puedes crear un hook para manejarla:

```
import { useState, useEffect } from 'react';

function useAuth() {

const [isAuthenticated, setIsAuthenticated] = useState(false);

useEffect(() => {
const token = localStorage.getItem('token');
setIsAuthenticated(!!token);
}, []);

const login = (token) => {
localStorage.setItem('token', token);
setIsAuthenticated(true);
};

const logout = () => {
localStorage.removeItem('token');
setIsAuthenticated(false);
};
return { isAuthenticated, login, logout };
}

```

Uso:

```
function AuthComponent() {

const { isAuthenticated, login, logout } = useAuth();

return (
<div>
{isAuthenticated ? (
<button onClick={logout}>Logout</button>
) : (
<button onClick={() => login('myToken')}>Login</button>
)}
</div>
);
}

```
