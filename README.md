# AA_ED_2Evaluacion
Actividad Aprendizaje de Entornos de Desarrollo 2 Evaluacion

Aplicación que permite mediante menú principal, registrar y mostrar los tres elementos esenciales de viaje en avión. Estos son: Avión, Pasajero y Vuelo. 
A cada uno de ellos se solicita un mínimo de 5 caracterísitcas que pueden tener. Para la solicitud de datos al usuario, se han creado submenús.

Los puntos que se han realizado según la actividad propuesta son los siguientes:

● Crear un repositorio en GitHub para almacenar el código del proyecto de forma que
dispongan de las ramas master y develop. Configurar el fichero
README.md del repositorio.

● Para cada nueva funcionalidad se ha creado una nueva rama feature y se ha fusionado con
develop mediante Pull Request:
  ○ Crear las 3 clases
  ○ Crear las opciones de menú para registrar objetos de las 3 clases
  ○ Crear las opciones de menú para visualizar los objetos creados

● Configurar un job en Jenkins para obtener el código del proyecto del repositorio y
que se compile y empaquete el proyecto

● Añadir al Job la configuración necesaria para que el código del proyecto sea
analizado por un SonarQube

● Instalar y ejecutar VisualVM y monitorizar el rendimiento y el uso de memoria de tu
aplicación


Otras funcionalidades (1 pto cada una)
● Configurar maven para poder lanzar un análisis de código del proyecto directamente
con esta herramienta

● Añadir tests JUnit al proyecto y configurar el Job de Jenkins para que se
ejecuten cada vez que éste se lance

    ○ Test para comprobar que se puede crear cada uno de los objetos, invocando
      al constructor y comprobando luego los valores de sus atributos
    ○ Comprobar el método equals de al menos una de las clases
    
● Añadir una release del proyecto al repositorio para que los usuarios puedan
descargarse la aplicación para usarla directamente.

● Utilizar el gestor de issues para registrar como features cada una de las
funcionalidades. Registrar también, al menos, 3 bugs que se ha encontrado durante su desarrollo.

● Diseñar el diagrama de clases 

● Diseñar una página web utilizando github-pages
