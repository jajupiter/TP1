# TP1
Integrantes: Atiencia Juan, Altamirano Jonathan, Garcia Justin, Ladines Harryson

AGENCIA LADINES

Codificación: Decidimos usar en este código el bloque secuencial debido a que nos permite dividir a través de diferentes criterios toda la ropa que entra, y la dividimos según el tipo de prenda, la persona que lo llegue a usar (hombre, mujer, niños), el proveedor de la misma (usamos el código asignado), la talla, tela y color (en la cual usamos sistema hexadecimal).
Código de producto:  prenda + persona + proveedor/marca + talla + tela +color

Ejemplo: 
Vestido para mujer marca Zara talla S de algodón color turquesa. = VM001SA5DC1B9.

Validación: 	

•Nombre de producto: Acepta de 1-75 caracteres.

Validación: No puede quedar vacío el campo, y el sistema ofrecerá los tipos de prendas disponibles conforme escriba para poder tener una clasificación igualitaria. 

•Descripción:  Aceptara de 1 - 250 caracteres. No puede quedar vacía, todo lo entrado al momento será evaluado por una función verificando que las palabras en su mayoría sean parte del diccionario para así poder verificar la veracidad de este

•Stock Inicial: Aceptará hasta 16 dígitos y solo podrá ingresar números al campo. No puede quedar vacía.

•Punto de Pedido: Aceptará hasta16 dígitos y solo podrá ingresar números al campo. No puede quedar vacía.

•Fecha de compra: La fecha será ingresada en formato DD/MM/AAAA, no permite ingresar letras y de necesitarlo el usuario podrá acceder a un calendario. No puede ser vacío.

•Código de proveedor: El código a los proveedores serán códigos de 3 cifras las cuales serán secuenciales en el sistema hexadecimal, conforme a se vayan comprando a estos se la ira añadiendo y de ya existir, existirá una tabla asociado a ellos con su nombre para poder identificarlos de manera más eficiente y eficaz. No puede ser vacío.

•Precio de compra: No puede ser vacío. El valor que tomara será apto para números y la coma o punto decimal, en el caso de que este ingrese un numero entero se rellenaran la parte decimal con 00. 


WIREFRAME


![image](https://github.com/jajupiter/TP1/assets/168550769/fc743bec-f6b9-4030-bd9f-113e517233de)

PROTOTIPO DE LA INTERFAZ


![Captura de pantalla 2024-05-14 221659](https://github.com/jajupiter/TP1/assets/168550769/2bb55824-2823-4dec-acd2-3976e0063d1b)
