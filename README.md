# TPO_Final_ParadigmaOrientadoObjetos
Título: Trabajo Práctico - Paradigma Orientado a Objetos: Desarrollo de Aplicación para un Taller Mecánico
En el contexto del presente trabajo práctico, enmarcado en la asignatura de Paradigma Orientado a Objetos, se ha desarrollado un programa en lenguaje Java. Dicho programa tiene como objetivo la implementación de una interfaz gráfica correspondiente a un taller mecánico. Para alcanzar este propósito, se llevó a cabo la creación de un diagrama de clases que representa los distintos objetos identificados en el enunciado.
Además de la representación gráfica de las clases y sus relaciones, se procedió a la generación de una serie de diagramas de secuencia que reflejan distintos procesos dentro del taller. Estos diagramas incluyen:
1.Registro de una Nueva Reparación
2.Cálculo del Salario de los Técnicos
3.Incorporación de Repuestos y Mano de Obra a una Reparación
4.Retiro de un Vehículo y Cálculo del Costo de Reparación

Enunciado:
Taller Mecanico
Nos contrataron para la confección de una aplicación para la administración y control de las reparaciones de un taller. 
El taller posee una cantidad de clientes registrados, de los mismos se conoce su nombre, su tipo de documento y su número de documento, además los mismos poseen una cuenta corriente que les permite reparar un vehículo y retirarlo sin pagar en el momento cargando el importe de una reparación a la cuenta corriente si lo desea y el límite de crédito de esa cuenta corriente 
También se tiene registro de los vehículos que se reparan, por lo tanto, de cada vehículo se guarda la matrícula (patente), la marca, el modelo y el año y se indica quien es el dueño de ese vehículo. El dueño de un vehículo, siempre es un cliente registrado.
Cada vez que un vehículo entra al taller se registra una nueva reparación, asignándole un número entero y correlativo que la identifica, la fecha en que se registró la reparación, el vehículo a reparar, el cliente que lo trajo (puede ser el dueño o no) y el estado de la reparación.
Para realizar la reparación se utilizan repuestos y mano de obra en cantidades determinadas, junto con el técnico que utiliza el repuesto o efectúa la tarea descripta por la mano de obra (por ejemplo, de la tarea afinación, se usaron 3 horas del técnico de nombre Pepe). 
De los repuestos se guarda el código, que es un número entero y consecutivo, la descripción de ese repuesto, y el precio del mismo. 
De la mano de obra se guarda el código de mano de obra, que es un número entero y consecutivo, la descripción de esa mano de obra y el valor hora de la misma. 
De los técnicos se conoce su nombre, su tipo de documento y su número de documento y además el salario base del mismo. Al momento de calcular el sueldo que debe cobrar cada técnico al salario base se le debe adicionar el 10% de todas las tareas realizadas en las reparaciones terminadas del mes liquidado.
Cuando un cliente trae un vehículo para hacer una reparación, el encargado de recepción, verifica que el cliente y el vehículo se encuentren registrados, de no ser así los registra. Cuando ambos se encuentren registrados, se confecciona una nueva reparación y se le coloca como estado “Pendiente”. 
Al momento de comenzar a realizar la reparación, se cambia el estado de la misma a “En_Proceso” y se comienza a agregar repuestos y mano de obra a la misma en la cantidad que sean necesarias, indicando quien es el técnico que las utiliza (puede ser el mismo para todos los repuestos y mano de obra o más de uno).  
Cuando la reparación finalizó se cambia el estado a “Terminadas”. 
Si una reparación tiene estado de terminada, no se le pueden agregar ni repuestos ni mano de obra.
