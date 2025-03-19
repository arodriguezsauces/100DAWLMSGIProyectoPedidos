# Examen

> Un taller de tractores 🚜   busca estandarizar el formato XML de sus pedidos a los diferentes fabricantes. Para ello, ha establecido que los archivos XML deben cumplir con las siguientes condiciones: 

## ARCHIVO XML PARA LOS PEDIDOS 

* Un pedido debe incluir al menos un tractor. 

* Cada pedido tiene un Identificador de pedido ( idPedido atributo obligatorio, formado por la letra P y tres dígitos) 

* Fecha del pedido (atributo obligatorio con el siguiente formato AAAA-MM-DD) 

* Cada tractor debe estar compuesto por uno o más componentes. 

* Cada tractor tiene un atributo código del fabricante, codigoFabricante obligatorio, formado por la letra F y tres dígitos 

* Un componente debe contener los siguientes elementos:  

* Referencia es un atributo de componente, referencia, es una cadena formada por letras mayúsculas y números y con 10 caracteres. 

* Fecha de entrega (opcional, pero si está presente, el mes y el año son obligatorios, mientras que el día es opcional). 

* Indicador de fragilidad (para especificar si el componente es frágil o no). 

* Peso del componente, que debe incluir:  

* Un elemento de peso valores positivos. 

* Un atributo que especifique la unidad de peso (kg o g). 

* Número de serie del componente es una cadena. 

* Kilometraje máximo (elemento opcional que indica cuándo debe sustituirse el componente tras alcanzar un cierto número de kilómetros, siendo un numero entero positivo). 

* Cantidad es un número positivo entero, por defecto 1 

 

## ARCHIVO XML PARA LOS COMPONENTES 

* El elemento componentes está formado pueden ser una o más componente(s). 

* Cada componente tiene dos atributos: código y nombre 

* El atributo código es una cadena de 10 caracteres alfanuméricos, siendo las letras en mayúsculas. 

* El atributo nombre es la descripción de cada componente. 

 

## ARCHIVO XML PARA LOS FABRICANTES 

* El elemento fabricantes está formado por varias fabricantes. 

* Cada fabricante tiene dos atributos: código y nombre 

* El atributo código es una cadena de 4 caracteres alfanuméricos, siendo la primera letra F y tres dígitos numéricos 

* El atributo nombre es el nombre del fabricante. 

### SE PIDE:

> Validación mediante DTD y Schema
> Transformación del XML en una página web

 
