# diagnostico
------------------------------
 Programación de Aplicaciones para Dispositivos Móviles 
Diagnóstico
Profesor: Rene Rosales
Alumno: Espíndola Daniel 

1- ¿A que nos referimos cuando hablamos de APP?
Cuando se habla de App, nos referimos a una aplicación, es la abreviación de application.
2- ¿Qué es el Frontend y qué es el Backend? De una definición con sus palabras y explique cómo se comunican habitualmente.
El Frontend es la parte visible con la que interactúa el usuario en la aplicación o página web, incluyendo el diseño, colores, botones, imágenes, formularios, animaciones y toda la interfaz gráfica. Ejemplos de lenguajes principales son: HTML, CSS y JavaScript.
El Backend es la parte de la aplicación o del sitio web que no es visible para el usuario, aunque es esencial para su funcionamiento, es la capa que gestiona la lógica, las bases de datos, este procesa las solicitudes del Frontend, accede a las bases de datos y las funciones que permiten que una aplicación funcione correctamente.
3- ¿Qué es una API REST? ¿Cuál es su función principal cuando desarrollamos una aplicación para dispositivos móviles?
API (Interface Programming Application= Interfaz de Programacion de Aplicaciones) es un conjunto de reglas y herramientas que permiten la comunicación entre dos programas. Una API REST es un tipo específico de API que sigue las reglas del registro arquitectónico REST (Representational State Transfer); es una API diseñada para funcionar sobre internet usando HTTP.
La función principal de una API REST en una app móvil es la de permitir que la aplicación móvil se comunique con un servidor para enviar y recibir datos, actúa como el puente entre el celular y el Backend.

4- ¿Qué es el formato JSON? Escribe un ejemplo simple de cómo se vería un objeto “Alumno” con nombre, apellido y una lista de 3 notas en este formato.
JSON (JavaScript Object Notation) es un formato de texto ligero usado para almacenar y transmitir datos estructurados entre sistemas (por ejemplo: entre un servidor y una aplicación).
Ejemplo de Objeto “Alumno”:
{
  “nombre”: “Daniel”;
  “apellido”: “Espíndola";
  “notas”: [8,7,9]
}
5- ¿Qué es una librería (o biblioteca) y qué es un Framework? ¿Son lo mismo? Justifique su respuesta.
Una librería es un conjunto de funciones, clases o herramientas ya programadas que se puede usar para no tener que escribir todo desde cero; se incorpora al programa cuando se necesita, se controla cuándo y cómo usarla y sirve para resolver tareas específicas.
Un Framework es una estructura o plataforma ya completa que define cómo debe organizarse y funcionar una aplicación; proporciona una base ya preparada, establece reglas y una forma de trabajar y el programa se construye dentro del Framework.
No son lo mismo, la diferencia principal está en quien controla el flujo del programa. Una Librería es como agarrar una herramienta de una caja cuando se la necesita, en cambio un Framework es como trabajar dentro de una fábrica ya armada.

6- ¿Qué es un sistema de control e versiones y para qué sirve? Explique qué sucede si dos desarrolladores modifican la misma línea de código en el mismo archivo y como se resuelve.
Un sistema de control de versiones es un sistema que permite registrar, gestionar y recuperar los cambios realizados en archivos a lo largo del tiempo, tambien en proyectos de software, permite saber: 
Quién hizo cada cambio, cuándo se hizo, qué cosa se modificó y volver a versiones anteriores si algo falla. Sirve para poder trabajar en equipo sin pisarse el trabajo, mantiene un historial de cambios, prueba nuevas funciones sin romper el sistema principal, recupera versiones estables y detecta errores introducidos recientemente.
Si dos desarrolladores modifican una misma línea, se produce un conflicto de versiones; el sistema detecta que hay cambios incompatibles en el mismo lugar del archivo y no puede decidir automáticamente cuál conservar, por lo tanto el conflicto debe resolverse de manera manual; el sistema marca donde está el conflicto y el desarrollador revisa ambas modificaciones y decide con cuál de las dos se queda, guarda el archivo corregido y confirma la resolución
7- ¿Qué es la Programación orientada a Objetos (POO)? Defina brevemente los conceptos de Clase, Objeto y Herencia.
La Programación orientad a Objetos (POO) es un paradigma de programación que organiza el software en objetos, los cuales representan entidades del mundo real y combinan datos (atributos) y comportamientos (métodos), su objetivo es hacer los programas más organizados, reutilizables y fáciles de mantener.
Clase: Puede entenderse como un plano de construcción que indica cómo se va a construir algo.
Objeto: Es una estructura concreta que existe dentro del programa y que fue creada a partir de la clase, representa algo específico.
Herencia: La herencia es un mecanismo mediante el cual una clase puede adquirir las mismas características y comportamientos de otra clase. Es como reutilización.
8- ¿Cuál es el propósito de los modificadores de acceso public y private en el contexto de la programación orientada a objetos?
El propósito del modificador de acceso public quiere decir que cualquier entidad puede acceder a nuestra clase y agregar o modificar nuestro código. En cambio, el modificador de acceso private significa que nadie va a poder acceder a nuestra clase, sólo, a través de un intermediario y así poder cambiar o agregarle cosas a nuestra clase.
9- Explique las principales diferencias entro los sistemas operativos iOS (iPhone) y Android desde el punto de vista del desarrollo (lenguajes nativos, tiendas de aplicaciones y tipos de dispositivos). Además, mencione si conoce algún otro sistema operativo para móviles que exista o hay existido en el mercado.
Diferencias principales entre iOS y Android:
iOS (iPhone): 
Lenguajes nativos: Principalmente Swift, es el actual.
También Objetive-C, es el más antiguo.
Tiendas de aplicaciones: Existe solo una oficial que es la App Store de Apple.
Es muy estricta en normas de seguridad.
Tiene un proceso de revisión obligatorio antes de publicar.
Tipos de dispositivos: Solamente funciona en dispositivos de Apple, como iPhone o iPad.
tiene pocos modelos, una menor fragmentación y es más fácil de optimizar.
Android:
Lenguajes nativos: Principalmente Kotlin, que es el actual, y también Java. 
Tiendas de aplicaciones: La principal es Google Play Store, tiene políticas menos restrictivas que iOS.
Permite instalar apps desde otras tiendas o archivos APK.
Tipos de dispositivos: Funciona en dispositivos de muchas marcas: como Samsung, Xiaomi, Motorola, Huawei y muchas otras más.
Tiene una gran variedad de precios, marcas tamaños y Hardware.
Alta fragmentación, muchas versiones y modelos.
Otros dispositivos móviles que existieron además de iOS e Android;
Windows Phone de Microsoft, ya está descontinuado.
BlackBerry OS de BlackBerry Limited
Symbian, el cual fue muy usado antes de los Smarthphones modernos.
Firefox OS de Mozilla
La mayoría desaparecieron por completo al no poder competir con el dominio de iOS y Android.
10- ¿Cómo piensa que una aplicación móvil podría facilitar la vida a una persona con discapacidad visual en Las Lajitas?
Creo que una aplicación móvil para una persona con discapacidad visual puede ser muy beneficiosa ya que la persona va a tener la posibilidad de ser un poco más independiente ya que no va a necesitar de nadie externo para poder ejecutar y utilizar la app de forma normal.
