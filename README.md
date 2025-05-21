# ex3T_ChristianLagunaSuarez
1-Cliente: He considerado que el cliente tiene un ArrayList de mascotas, asi se puede añadir o eliminar mascotas sin problema.Como tal, el cliente lo unico que puede hacer es registrar a sus animales.
2-Mascota: Las mascotas son las que poseen el historial de cosultas, asi el cliente si tiene varios animales puede separar los historiales facilmente. Esta tambien hecho con un ArrayList de la clase Consulta y en ella se encuentra el metodo de registrar la consulta.
3-Consulta: Esta clase tiene de atributos un ArrayList de la clase Tratamiento, y un atributo veterinario para asi tenerlo asignado. 
En esta clase se encuentra el metodo de calcularCoste ya que es donde esta la lista de tratamientos y se le puede añadir algun extra por ejemplo si hay una operacion o del propio coste de la cita.
La consulta es una superclase de otros dos tipos de consulta, si es una consulta general se usaria la superclase, si fueran consultas como cirugia o vacunacion se usarian las clases hijas.
Veterinario: Es la clase que se encarga de registrar los tratamientos.
