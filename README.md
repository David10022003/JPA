## Efecto de agregar @OneToMany
Al agregar la anotación `@OneToMany` a la entidad Competitor sobre la lista de productos, se establece una relación uno a muchos entre un Competitor y sus productos asociados. Esto indica a la base de datos que un usuario, en este caso el Competitor, puede tener varios productos. 

La ventaja de usar esta anotación es que cuando el JPA (Java Persistence API) trae los datos de la base de datos, automáticamente carga los productos asociados a cada Competitor en una única consulta, evitando así la necesidad de realizar consultas adicionales a la base de datos para obtener los productos de cada Competitor por separado.

Esta funcionalidad proporciona una manera eficiente de manejar las relaciones entre entidades en una base de datos relacional utilizando JPA.


