[[Clases y Objetos]]
Colocar cosas de la realidad y colocarlos en un programa de código

Ver las características necesarias para el objeto.

Ejemplo: 
**Bolsillo**

- Contenido
- Capacidad 

**null solo puedo retornar en objetos**


**MÉTODO CONSTRUCTOR**
	Es un método que se invoca una sola vez 
	Se utiliza para ==inicializar==
	**Inicializando o instanciando** 

```java
Bolsillo bolsillo = new Bolsillo();
```

En diagrama UML
	Lo rojo es privado (-)
	Lo verde es publico  (+)
	Mochila --> "*" Bolsillo : bolsillos [Atributos]  ((Para mostrar relación gráficamente ))
	--> Esta flecha es sólida
- Las clases son públicas 

Dependencia
	Establece una asociación entre clases 

Ejemplo:

>Una mochila tiene muchos bolsillos
