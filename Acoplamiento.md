[[Conceptos]]

Unión entre diferentes objetos. 
A-->B
>Acoplar es juntar los componentes de Clases 

-  **Grado en que los módulos de un programa dependen unos de otros**

| Cohesión |  Mayor |
|------------|  --------------|
| Acoplamiento|  bajo

==Mayor cohesión==

==Bajo Acoplamiento==

- Cuando tengo acoplamiento 0 no tengo relación entre clases

> Un acoplamiento alto significa que los componentes están fuertemente interconectados, mientras que un acoplamiento bajo significa que **los componentes son más independientes**.


Ejemplo:

```plantuml
class Profesor {

} 

class Alumno {

}

Profesor --> "*" Alumno 

```
El código cambia desde el contexto
