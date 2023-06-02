
**Clase y el Objeto**
	El sistema como tiene datos separados no están agrupados, no están agrupados de una manera real
	El sistema debe parecerse al mundo real
	La clase empieza con Mayúscula y el objeto con minúscula 
	La clase representa un conjunto de objetos
	Un objeto es un elemento de una clase

**Instancia:**
	Es un objeto único 
	Definimos características para identificar el objeto.
	Conjuntos ***diferenciados*** son clases


Acciones:
	Son las características que realiza el objeto.

	Atributo: parámetros de la clase, es una variable. (sustantivo)
	Método: Acciones de la clase, acciones que realiza el objeto, un método se escribe con un (acción) 

-  Las variables son sustantivo

[new asigna un espacio de memoria](https://www.javatpoint.com/new-keyword-in-java#:~:text=The%20Java%20new%20keyword%20is,a%20reference%20to%20that%20memory.)

Clase de tipo primitivo
	Son los tipos de datos int, double, char, etc.

CICLO DE VIDA DEL OBJETO - instancia
1. Para ***manipular*** un objeto tengo que instanciar el objeto con la palabra (new)


_Se debe instanciar de acuerdo al tamaño del arreglo_

```java
/*Ejemplo de Construcción de construcción de case y objeto*/
Registro pedro; // Clase(tipo de dato) - objeto(variable)  
pedro = new Registro(); // crea una instancia -> Asigna una instancia  
pedro.nombre = "Pedro Palotes"; // accede a una de las características de la instancia  
  
pedro.nota1 = 4;  
pedro.nota2 = 8;  
  
System.out.println(pedro.calcularNotas()); // Este es un método);
```


EJEMPLO APLICADO A CLASES (Estructuras)

```java
Registro[] alumnos = new Registro[2]; // Separando espacios para el arreglo  
  
alumnos[0] = new Registro(); // Es una instanciación  
alumnos[0].nombre = "Pedro Palotes";  
alumnos[0].nota1 = 4;  
alumnos[0].nota2 = 8;  
  
alumnos[1] = new Registro(); // Es una instanciación  
alumnos[1].nombre = "Ricky Martin ";  
alumnos[1].nota1 = 8;  
alumnos[1].nota2 = 9;  
  
	for(Registro alumno:alumnos ){  
	System.out.println(alumno.calcularNotas());  
	}
```

Refactorizar:
	Mejorar el código sin cambiar su comportamiento
Niveles de acceso:

Principios de diseño
	Responsabilidad Única
	Cohesión 
	
Top Down

UML

Diagrama de clases 