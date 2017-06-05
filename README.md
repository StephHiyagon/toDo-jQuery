# To do | programación de tareas con estilo React

- El proyecto consiste en realizar un ToDo similar al de Trello.

## Fuentes consultadas:
- jQuery: url(http://api.jquery.com/)


## Componentes

### header.js
Este es un componente que llamamos desde el app.js en el cual se le hará append a un div creado en este archivo para luego enlazarlo con el div.root<br/>
![Componente HEADER](assets/readme/header.jpg)

### todo.js
Aquí utilizaremos más funcionalidades, tendremos una función en la cual crearemos los cards, obteniendo el dato del input al dar enter("13"), y al formarse el objeto se pusheará al array todo; también se asigna la propiedad completed como false, la cual cambiará al hacer checked y asi pasará al card de completed list; para remover un item se hace un mapeo y un indexOf pasandole este valor al metodo splice<br/>
![Componente TODO](assets/readme/todoItem.jpg)<br/>
![Componente TODO](assets/readme/reRender.jpg)<br/>
![Componente TODO](assets/readme/todo.jpg)<br/>
![Componente TODO](assets/readme/input.jpg)<br/>

## Versión Desktop 
Así se ve en la versión desktop: <br/>
![gif-todo](assets/readme/escritorio.gif)


## Desarrollado con:

`HTML` `JavaScript` `CSS` `JQUERY`  

##  Créditos* 
* [Stephanie Hiyagon](https://github.com/stephHiyagon)
