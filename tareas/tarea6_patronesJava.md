# Singleton

El patrón de diseño Singleton es un patrón creacional que se utiliza para garantizar que una clase tenga solo una instancia y proporcionar un punto de acceso global a esa instancia desde cualquier parte del programa. Esto es útil cuando solo se necesita una única instancia de una clase para controlar acciones como acceso a una base de datos o coordinar acciones en el sistema.

La implementación básica del patrón Singleton implica tener un constructor privado que evita la creación de nuevas instancias fuera de la clase, y un método público que proporciona acceso a la única instancia creada.

# Template

El patrón de diseño Template es un patrón de comportamiento que define el esqueleto de un algoritmo en una operación, delegando algunos de sus pasos a las subclases. Permite que las subclases redefinan ciertos pasos de un algoritmo sin cambiar su estructura general.

Este patrón se utiliza cuando se desea permitir a las subclases extender ciertos pasos de un algoritmo sin cambiar su estructura general. El patrón de Template Method es especialmente útil en situaciones en las que partes del algoritmo son invariantes, pero algunos detalles específicos deben ser implementados por las subclases.

# Strategy

El patrón de diseño Strategy es un patrón de comportamiento que permite definir una familia de algoritmos, encapsular cada uno de ellos y hacerlos intercambiables. Esto permite que el algoritmo varíe independientemente de los clientes que lo utilizan.
