# ex3T_ChristianLagunaSuarez
1-Cliente: He considerado que el cliente tiene un ArrayList de mascotas, asi se puede añadir o eliminar mascotas sin problema.Como tal, el cliente lo unico que puede hacer es registrar a sus animales.
2-Mascota: Las mascotas son las que poseen el historial de cosultas, asi el cliente si tiene varios animales puede separar los historiales facilmente. Esta tambien hecho con un ArrayList de la clase Consulta y en ella se encuentra el metodo de registrar la consulta.
3-Consulta: Esta clase tiene de atributos un ArrayList de la clase Tratamiento, y un atributo veterinario para asi tenerlo asignado. 
En esta clase se encuentra el metodo de calcularCoste ya que es donde esta la lista de tratamientos y se le puede añadir algun extra por ejemplo si hay una operacion o del propio coste de la cita.
La consulta es una superclase de otros dos tipos de consulta, si es una consulta general se usaria la superclase, si fueran consultas como cirugia o vacunacion se usarian las clases hijas.
4-Veterinario: Es la clase que se encarga de registrar los tratamientos.

He considerado que el funcionamiento seria el siguiente: Una persona va la clinica con su animal, el animal es diagnosticado por un veterinario, el cual accede a los tratamientos y los receta, esta receta queda guardada en la consulta, pero la consulta queda guardada en el animal, por lo cual se puede acceder a ella desde el animal, los costes se calculan desde la consulta ya que es esta la que tiene los medicamentos asignados, tambien podria haber asignado la lista de tratamientos al animal directamente pero he considerado que es mas ordenado asi.
