# java-ejercicios-avanzados
Ejercicios de práctica CaC2023 - Java Avanzado

Realizaremos las siguientes consignas:

Introducción:
En esta guía, aprenderemos a crear un proyecto Java utilizando IntelliJ Community Edition y aplicaremos los siguientes conceptos:

TDD (Desarrollo Dirigido por Pruebas) con JUnit 5.
Git Flow para el control de versiones.
Estructuras de datos en Java (maps, listas, conjuntos, colas y pilas y sus derivados).
Programación funcional en Java (lambdas, streams y operaciones básicas).
Uso de clases abstractas e interfaces.

Paso 1: Creación del Proyecto

Abre IntelliJ IDEA Community Edition.
Haz clic en "File" -> "New" -> "Project".
Selecciona "Java" como el tipo de proyecto.
Define un nombre para el proyecto (por ejemplo, "JavaProjectWithTDD").
Haz clic en "Next".





Paso 2: Configuración de Git Flow
Dentro del proyecto, ve a "VCS" -> "Enable Version Control Integration".
Selecciona "Git" como el sistema de control de versiones.
Configura Git Flow siguiendo las instrucciones de Git Flow.
Crea un repositorio en tu plataforma de hosting de Git (por ejemplo, GitHub) y vincula el repositorio remoto a tu proyecto local.

Paso 3: Estructura del Proyecto
Organiza tu proyecto en paquetes para cada actividad. Por ejemplo:
com.tarea.lista para la lista de tareas.
com.calculadora para la calculadora.

src
	main
		java
			com
				listatareas
				calculadora
				etc


**** Actividad 1: Lista de Tareas ****
Crea una aplicación de lista de tareas con las siguientes características:

Utiliza una lista (List) para almacenar las tareas.
Implementa operaciones de agregar, eliminar y listar tareas.
Usa JUnit 5 para escribir pruebas unitarias.

Descripción: En esta actividad, crearás una aplicación de lista de tareas en Java.

Pasos:

Crea una clase llamada Tarea que represente una tarea con propiedades como id, descripcion, fecha, etc.
Crea una clase llamada ListaTareas que contendrá una lista (List) de tareas y métodos para agregar, eliminar y listar tareas.
Utiliza TDD con JUnit 5 para escribir pruebas unitarias para los métodos de ListaTareas.
Implementa los métodos de ListaTareas y asegúrate de que las pruebas unitarias pasen con éxito.
Resultado Final Esperado: Una aplicación de lista de tareas que permite al usuario agregar, eliminar y listar tareas. Todas las pruebas unitarias deben pasar correctamente.


**** Actividad 2: Calculadora ****

Descripción: Desarrolla una calculadora en Java que realice operaciones básicas (+, -, *, /) utilizando programación funcional y lambdas.

Pasos:

Crea una interfaz funcional llamada Operacion que defina un método calcular para realizar operaciones matemáticas.
Implementa clases con lambdas que representen las operaciones de suma, resta, multiplicación y división.
Crea una clase Calculadora que acepte dos números y una instancia de la interfaz Operacion para realizar la operación.
Utiliza las clases Operacion y Calculadora para realizar operaciones matemáticas.
Resultado Final Esperado: Una calculadora que puede realizar operaciones matemáticas básicas utilizando lambdas y programación funcional.




**** Actividad 3: Uso de Set ****
Descripción: Desarrolla un programa en Java que utilice un conjunto (Set) para eliminar duplicados de una lista de elementos.

Pasos:

Crea una lista de elementos con duplicados.
Utiliza un conjunto (Set) para eliminar los duplicados de la lista.
Imprime la lista resultante sin duplicados.
Resultado Final Esperado: Una lista de elementos sin duplicados, utilizando un conjunto para eliminar duplicados.


**** Actividad 4: Uso de Map ****
Descripción: Desarrolla una aplicación en Java que utilice un mapa (Map) para realizar un seguimiento de las calificaciones de los estudiantes.

Pasos:

Crea un mapa que asocie nombres de estudiantes con sus calificaciones.
Agrega al menos tres estudiantes con calificaciones.
Implementa métodos para agregar, actualizar y consultar calificaciones.
Imprime las calificaciones de todos los estudiantes.
Resultado Final Esperado: Un programa que utiliza un mapa para almacenar y gestionar las calificaciones de los estudiantes.

**** Actividad 5: Uso de Cola (Queue) ****
Descripción: Implementa una cola (Queue) en Java para gestionar una fila de personas en un banco.

Pasos:

Crea una cola (Queue) para representar la fila de personas en un banco.
Implementa métodos para agregar y quitar personas de la cola.
Imprime el estado de la cola después de cada operación.
Resultado Final Esperado: Un programa que utiliza una cola para gestionar una fila de personas en un banco.


**** Actividad 6: Uso de Pila (Stack) ****
Descripción: Crea una aplicación en Java que utilice una pila (Stack) para evaluar expresiones matemáticas en notación posfija (postfix).

Pasos:

Lee una expresión en notación posfija (por ejemplo, "3 4 + 2 *").
Utiliza una pila para evaluar la expresión y calcular el resultado.
Imprime el resultado.
Resultado Final Esperado: Un programa que utiliza una pila para evaluar expresiones matemáticas en notación posfija.


**** Actividad 7: Streams y Filter ****
Descripción: Utiliza streams y la función filter en Java para filtrar elementos de una lista según un criterio específico.

Pasos:

Crea una lista de elementos (por ejemplo, números enteros).
Utiliza streams y la función filter para filtrar elementos que cumplan cierto criterio (por ejemplo, números pares).
Imprime los elementos filtrados.
Resultado Final Esperado: Un programa que utiliza streams y filter para filtrar elementos de una lista según un criterio específico.


**** Actividad 8: Streams y Map ****
Descripción: Utiliza streams y la función map en Java para transformar elementos de una lista en otro tipo de datos.

Pasos:

Crea una lista de elementos (por ejemplo, cadenas de texto).
Utiliza streams y la función map para transformar los elementos en otro tipo de datos (por ejemplo, mayúsculas).
Imprime los elementos transformados.
Resultado Final Esperado: Un programa que utiliza streams y map para transformar elementos de una lista en otro tipo de datos.

Actividad 9: Interfaces Funcionales
Descripción: Crea una interfaz funcional personalizada en Java y utilízala en una aplicación.

Pasos:

Define una interfaz funcional con un único método abstracto.
Implementa una clase que utilice esta interfaz funcional para realizar una operación específica.
Utiliza la clase en tu programa principal.
Resultado Final Esperado: Una aplicación que utiliza una interfaz funcional personalizada en una operación específica.

**** Actividad 10: Clases Abstractas ****
Descripción: Diseña una clase abstracta en Java y crea subclases que la extiendan para implementar comportamientos específicos.

Pasos:

Crea una clase abstracta que contenga un método abstracto y métodos concretos.
Crea al menos dos subclases que extiendan la clase abstracta e implementen el método abstracto de manera diferente.
Utiliza las subclases en tu programa principal.
Resultado Final Esperado: Una aplicación que utiliza una clase abstracta y sus subclases para implementar comportamientos específicos.
