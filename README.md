## Sintaxis de Js
- Case sensitive
  - Numero no es igual a numero
- Es de tipado débil o dinamico
  - Las variables son del tipo que almacenen
- Las sentencias finalizan con ;
  - No es obligatorio pero si recomendable
- Los bloques finalizan con }
  - De forma opcional se puede añadir un ; despues de }
## Variables, constantes y scope.
- Una variable es un espacio que se reserva en memoria para almacenar un dato que podrá cambiar durante la ejecución de nuestro programa.
  - La palabra reservada para declarar variables es 'let' no es recomendable usar 'var'
- Las variables se pueden: declara, inicializar y modificar
- Una constante es un espacio en memoria para almacenar un dato que no cambiará durante la ejecución del programa.
  - La palabra reservada para devlarar una constante es 'const'
- El scope o ámbito es la zona donde existe una variable o constante.
### Declaración, inicialización y modificación
- Una variable se declara de la siguiente forma:
```js
let nombreVariable;
```
- Una variable se inicializa de la siguiente forma:
```js
nombreVariable = 5;
```
- Se puede declarar e inicializar en la misma linea haciendo lo siguiente:
```js
let nombreVariable = 5;
```
- Para modificar el valor de una variable existente  se usa lo siquiente:
```js
nombreVariable = 'valor';
```
Las constantes solo admiten la declaración e inicializacion en la misma sentencia:
```js
const Pi = 3.14;
```
## Tipos de datos en Js
### Primitivos
- Numeros
```js
    let numero = 5;
```
- Strings
```js
    let cadena = 'cadena';
```
- boolean
```js
    let bool = true;
```
- Undefined
- Null
- Symbol
