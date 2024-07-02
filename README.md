# Practico 7

### Ejercicio 0: Preparar el entorno
En este ejercicio se preparará todo lo necesario para realizar el práctico de forma adecuada.

1. Forkear el repositorio del práctico a su cuenta de GitHub.
2. Clonar el repositorio en la computadora en la que se realice el práctico.
3. Crear una nueva rama donde se desarrollará del práctico.
4. Realizar la implementación de los ejercicios siguientes en la rama recién creada.

### Ejercicio 1: Lista desplegable y modularización

En este ejercicio se deberá crear una lista de selección e informar al usuario la un dato específico sobre la selección realizada. Esto se realizará en el archivo Ejercicio1.jsx.

**Parte 1**

1. Crear una lista desplegable con 3 productos:
   * Set de cables (Precio: $10)
   * Batería (Precio: $50)
   * Óptica (Precio: $100)
  (Tener en cuenta que posteriormente se mostrará el precio del producto seleccionado)
2. Crear un estado en el que se almacenará la selección de la lista.
3. Implementar una función que guarde el valor seleccionado en el estado creado en el punto anterior.
4. Mostrar un mensaje que le indique al usuario El precio del producto seleccionado actualmente.

**Parte 2**

1. Modularizar el ejercicio anterior en una componente denominada "ListaConDescuento".
2. Esta componente recibirá un valor a través de sus propiedades. Este valor será la cantidad de descuento que se le aplicará a los diferentes artículo (valor entre 0 y 1).
3. En lugar de mostrar el precio tottal del producto (como en la parte 1), se deberá mostrar el precio con descuento.

### Ejercicio 2: Formulario

En este ejercicio se deberá implementar un formulario que pida dos datos al usuario.
El formulario se utilizará para ingresar un producto y su precio.
Posteriormente se mostrarán diferentes mensajes en base a la información brindada.

1. crear un formulario con 2 inputs y un boton se envío. Uno de los inputs deberá ser para texto y el otro para números.
2. Crear un estado donde se almacene el contenido de los inputs. Debe ser un único estado.
3. Crear y utilizar una única función que actualice el estado cuando los inputs son modificados. Mostrar en pantalla el producto y su precio. Por ejemplo, si se ingresan los datos "manzana" y 10, se debe mostrar: "manzana cuesta 10 pesos"
4. Al presionar el botón de envío del formulario, se debe mostrar un mensaje que indique si el precio del producto es barato o caro. Si el producto cuesta más de $50 es caro, mientras que si cuesta $50 o menos es barato. Por ejemplo, para los datos del ejemplo anterior, se debe mostrar "El producto ingresado es barato" al enviar el formulario.