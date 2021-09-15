# Unidad 3: Ingeniería de Requerimientos
## **Tema: UML**  

![Mi Imágen](/archivos/individual/act4/UML.png) 


*El ***UML*** es un estándar para describir y documentar los procesos utilizados en las diferentes partes de un software.     También es utilizado para poder diseñar el software antes de hacer cualquier aplicación, optimizando la planificación para asegurar la calidad.*

## **DEFINICIÓN**
**UML** - Son las siglas de **Unified Modeling Language**.
Es un lenguaje estándar de modelado de sistemas orientado a objetos para hacer desarrollos de software.  
Se empezó a utilizar en algunos puntos para modelar procesos de negocios, ahora se ha concentrado y UML se define principalmente para hacer el análisis y el diseño de un sistema de software.  
UML **NO** es una metodología, es una notación para desarrollar modelos. Al utilizarlo aprendemos las reglas para plasmar diagramas con elementos y relaciones con intención de plasmar el análisis diseño.

#### **¿Cuándo se implementó por primera vez?**
Se implementó por primera vez en la década de los 90 gracias a tres ingenieros de software: ***Grady Booch, Ivar Jacobson y James Rumbaugh***.   
Ellos querían desarrollar una forma menos caótica de representar el cada vez más complejo desarrollo de software, a la vez que separaban la metodología del proceso. 
   
Hoy, el UML sigue siendo la indicación estándar para los desarrolladores, así como para gestores de proyectos, propietarios de negocios, empresarios tecnológicos y profesionales de distintos sectores.  
![Mi Imágen](/archivos/individual/act4/UML1.jpg) 

## **USOS**   
Se utiliza para definir un sistema, para detallar los artefactos en el sistema y para documentar y construir. En otras palabras, es el lenguaje en el que está descrito el modelo.  


## **CARACTERÍSTICAS**  
* Visualizar.
* Especificar .
* Construir.
* Documentar y/o ser base de documentación.  

## **VENTAJAS**
 * Simplifica las complejidades.
 * Mantiene abiertas las líneas de comunicación. 
 * Automatiza la producción de software y los procesos.
 * Ayuda a resolver los problemas arquitectónicos constantes. 
 * Aumenta la calidad del trabajo. 
 * Reduce los costos y el tiempo de comercialización. 


## **DIAGRAMAS**  
Existen diferentes tipos de diagramas UML.  

Cada tipo de UML requiere un enfoque y nivel de detalle diferente. El objetivo es que exprese visualmente diagramas que sean fáciles de entendibles para todo el equipo.

#### **Diagrama de Objetos**  
Representa una instancia específica de un diagrama de clases en un momento determinado en el tiempo.  
Un diagrama de objetos se enfoca en los atributos de un conjunto de objetos y cómo esos objetos se relacionan entre sí.  
Los diagramas de objetos son sencillos de crear: se componen de objetos, representados por rectángulos, conectados mediante líneas.

#### Ejemplo  
Los títulos de clase muestran el tipo de cuentas *(ahorros, corriente y tarjeta de crédito)* que un cliente dado podría tener con este banco en particular.  
Los atributos de clase son diferentes para cada tipo de cuenta.  
Por ejemplo, el objeto de tarjeta de crédito tiene un límite de crédito, mientras que las cuentas de ahorros y corriente tienen tasas de interés.  

![Mi Imágen](/archivos/individual/act4/ejemplo1.png) 

#### **Diagrama de Paquetes** 
Los diagramas de paquetes son diagramas estructurales que se emplean para mostrar la organización y disposición de diversos elementos de un modelo en forma de paquetes.  
*Un paquete es una agrupación de elementos UML relacionados, como diagramas, documentos, clases o, incluso, otros paquetes.*  
Cada elemento está anidado dentro de un paquete, que se representa como una carpeta de archivos dentro del diagrama, y que luego se organiza jerárquicamente dentro del diagrama.  
 Los diagramas de paquetes se usan con frecuencia para proporcionar una organización visual de la arquitectura en capas dentro de cualquier clasificador UML, por ejemplo, un sistema de software.
#### Ejemplo   

![Mi Imágen](/archivos/individual/act4/ejemplo2.png) 

#### **Diagrama de Distribución** 
El *diagrama de distribución UML* muestra la arquitectura física de un sistema informático. Puede representar a los equipos y a los dispositivos y también mostrar sus interconexiones y el software que se encontrará en cada máquina.  
Es donde representamos la estructura de hardware donde estará nuestro sistema o software, para ello cada componente lo podemos representar como nodos, el nodo es cualquier elemento que sea un recurso de hardware, es decir, es nuestra denominación genérica para nuestros equipos.

Dentro de la clasificación de los nodos tenemos que hay el nodo que puede ejecutar o procesar y el nodo que no ejecuta ni procesa, estos últimos pueden ser los dispositivos de salida como impresoras o monitores, es decir, los que están en contacto con el exterior.

#### Ejemplo  
![Mi Imágen](/archivos/individual/act4/ejemplo3.png) 

#### **Diagrama de Tiempos**  
Estos gráficos, también conocido como diagrama de temporización se emplean para representar el estado de una línea de vida en cualquier instancia de tiempo y denotan los cambios de un objeto de una forma a otra.  
En un diagrama de tiempos se emplean ondas para visualizar el flujo dentro del programa de software en distintas instancias de tiempo.  

Un diagrama de tiempos ofrece los siguientes beneficios:

* Permite realizar ingeniería inversa y directa.  
* Puede representar el estado de un objeto en una instancia exacta de tiempo.  
* Puede llevar un control de todos los cambios dentro de un sistema.  

También debes tener en cuenta estas posibles desventajas de usar un diagrama de tiempos:  

* Pueden ser difíciles de comprender.
* Pueden ser complicados de mantener con el tiempo.

#### Ejemplo  
![Mi Imágen](/archivos/individual/act4/+.png) 

#### **Diagrama de Comunicación**  
Los diagramas de comunicación se utilizan para mostrar cómo interactúan los objetos para efectuar el comportamiento de un guión de uso concreto, o una parte de un guión de uso.  
Junto con los diagramas de secuencia, los diseñadores utilizan los diagramas de comunicación para definir y aclarar los roles de los objetos que efectúan un flujo de sucesos concreto de un guión de uso. Son el origen principal de información que se utiliza para determinar las responsabilidades y las interfaces de clases.  

A diferencia del diagrama de secuencia, un diagrama de comunicación muestra las relaciones entre los objetos. Los diagramas de secuencia y los diagramas de comunicación expresan una información similar, pero de modos diferentes. Los diagramas de comunicación muestran las relaciones entre objetos y son mejores para comprender todos los efectos en un objeto determinado para el diseño de procedimiento.  


#### Ejemplo  
![Mi Imágen](/archivos/individual/act4/ejemplo5.png) 

#### **Diagrama Global de Interacciones**  
El diagrama global de interacciones ofrece una vista de alto nivel de un modelo de interacción. El diagrama actúa como una vista global del flujo de control entre las distintas interacciones, además del flujo de actividad entre los distintos diagramas.  

Un diagrama de global de interacciones ofrece los siguientes beneficios:  

* Ofrece una vista sin complicaciones de la actividad dentro de un modelo.
* Ofrecen un alto grado de navegabilidad entre los distintos diagramas.
* Permiten el uso de la mayoría de las anotaciones dentro de un diagrama de actividad, junto con elementos adicionales para una mayor claridad. 

#### Ejemplo  
![Mi Imágen](/archivos/individual/act4/ejemplo_ultimo.png) 

### **REFERENCIAS**

* Tutorial de diagramas de interacción. (s. f.). Lucidchart. Recuperado 14 de septiembre de 2021, de https://www.lucidchart.com/pages/es/diagrama-de-interaccion-uml

*  Mancuzo, G. (2021a, agosto 20). Diagramas de UML, qué significa esta metodología. ComparaSoftware Blog. https://blog.comparasoftware.com/diagramas-de-uml-que-significa-esta-metodologia/

* Team, M. (s. f.). La guía sencilla para la diagramación de UML y el modelado de la base de datos. Microsoft. Recuperado 14 de septiembre de 2021, de https://www.microsoft.com/es-mx/microsoft-365/business-insights-ideas/resources/guide-to-uml-diagramming-and-database-modeling

* Qué es el lenguaje unificado de modelado (UML). (s. f.). Lucidchart. Recuperado 14 de septiembre de 2021, de https://www.lucidchart.com/pages/es/que-es-el-lenguaje-unificado-de-modelado-uml
