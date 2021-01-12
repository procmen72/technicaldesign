# Caso practico "Automatización de gasolinera"
Una gasolinera va a operar de forma automatizada. Los clientes introducen la tarjeta de prepago en un lector conectado a la bomba de suministro. 

El dispositivo lector se comunica con los servicios del proveedor de la tarjeta de prepago para validar el estado de la tarjeta. Si la tarjeta tiene saldo (Expresado en litros) y está tiene vigencia, desbloquea la manguera de la bomba para permitir la carga de combustible. 

La carga de combustible no debe exceder el saldo de la tarjeta (limite en litros). Una vez que se completa la carga de combustible debe aplicarse el descuento en litros al saldo de la tarjeta de prepago. 

Si la tarjeta no es válida, ya sea por vigencia o no tener saldo, la bomba no debe permitir la liberación de la manguera.

#### Diagramas a desarrollar

- Elabore un diagrama de arquitectura conceptual donde se represente la interacción del lector – bomba – servicios del proveedor de la tarjeta.
- Elabore un diagrama de clases de los objetos involucrados en este caso, utilice su experiencia propia para la definición tanto de los atributos como para los métodos de cada clase.
- Elabore el diagrama de secuencia para la operación de carga de combustible si la tarjeta es válida o no.
- Elabore el diagrama de componentes tanto para el lector empotrado en la bomba como para los servicios del proveedor de la tarjeta de prepago.
- Elabore un diagrama de despliegue para los componentes de los servicios del proveedor de la tarjeta de prepago.

**Pueden hacer suposiciones acerca de los sistemas involucrados al momento de realizar el diseño.**
