Tarea
==============================

----

## Aplicaciones Moviles

#### Carlos Fernando Torres Luna

##### cf.torresluna@gmail.com 

--- 
---



# Arquitecturas MVP y MVC



#### Modelo Vista Controlador (MVC) 
Es un patrón o modelo de abstracción de desarrollo de software que separa los datos de una aplicación, la interfaz de usuario, y la lógica de negocio en tres componentes distintos (modelo, vista y controlador). El patrón de llamada y retorno MVC , se ve frecuentemente en aplicaciones web, donde la vista es la página HTML y el código que provee de datos dinámicos a la página, el modelo es el Sistema de Gestión de Base de Datos y la Lógica de negocio, y el controlador es el responsable de recibir los eventos de entrada desde la vista.

+ Modelo: Esta es la representación específica de la información con la cual el sistema opera. En resumen, el modelo se limita a lo relativo de la vista y su controlador facilitando las presentaciones visuales complejas. El sistema también puede operar con más datos no relativos a la presentación, haciendo uso integrado de otras lógicas de negocio y de datos afines con el sistema modelado.
+ Vista: Este presenta el modelo en un formato adecuado para interactuar, usualmente la interfaz de usuario.
+ Controlador: Este responde a eventos, usualmente acciones del usuario, e invoca peticiones al modelo y, probablemente, a la vista.

#### Modelo Vista Presentador (MVP)

La idea de este patrón es codificar la interfaz de usuario muy, muy facil, que tenga el menor código posible, de forma que no merezca la pena testearla. En su lugar, toda la lógica de la interfaz de usuario, la hacemos en una clase separada (que se conoce como Presenter), que no dependa en absoluto de los componentes de la interfaz gráfica y que, por tanto, es más fácil de testear. 

#### Diferencias entre MVC Y MVP

El Modelo Vista Controlador (MVC) y el Modelo Vista Presentador son Paradigmas de Diseño de software. La idea principal de estos paradigmas es separar la interfaz gráfica, la lógica, y la "cola" que los une en distintos modulos en el programa.

La diferencia esencial entre MVC y MVP es que los objetos que son parte de la interfaz gráfica del software, delegan sus acciones al controlador para responder a las interacciones del usuario, mientras que en el MVP, los objetos de la interfaz gráfica se encargan de responder al usuario, en vez de delegar las acciones al Controlador como lo haría MVC.

