# Modelado de Base de Datos para "Club Del Libro" 📚

¡Hola! Este repositorio contiene los modelos de base de datos que **he desarrollado** para simular el funcionamiento de "Club Del Libro", una tienda de libros. **Mi objetivo** en este proyecto fue diseñar una estructura de datos que nos permitiera gestionar eficientemente la información clave de la tienda, abordando las siguientes necesidades específicas que **identifiqué**:

## Situación a Modelar 💡

**Me propuse** modelar la siguiente situación para "Club Del Libro":

**Respecto a los Clientes:** 🧑‍🤝‍🧑

* **Quiero** almacenar sus **datos personales**
* **Necesito** distinguir si son **Personas Físicas o Jurídicas**
* Para **Personas Físicas**, **requiero** su **DNI y CUIL**
* Para **Personas Jurídicas**, **necesito** su **CUIT y NÚMERO DE PERSONERÍA JURÍDICA**
* Adicionalmente, para ambos tipos de clientes, **me pareció fundamental** recolectar y almacenar su **nombre, dirección, teléfono e e-mail **.

**Respecto a los Libros:** 📚

* El producto principal son los **libros**.
* Cada libro debe contener información asociada como el **título, categoría, ISBN (International Standard Book Number), año de publicación, valor, la casa editorial que hizo la publicación, y también el autor/a de la obra**.

**Respecto a las Editoriales:** 🏢

* Los libros son provistos por las editoriales.
* **Necesito** tener el **número de teléfono de la editorial (con un máximo de 2 números de teléfono)**, el **nombre de contacto** y el **e-mail**.
* **Fue importante para mí** destacar que **no podemos tener el mismo libro viniendo de varias editoriales; un libro es exclusivo de una editorial**.

**Respecto a las Compras:** 🛒

* Los clientes pueden **comprar uno o más libros a través de un pedido de compra**.
* Siempre que se realice una compra, **es crucial para mí** verificar en el inventario si el libro está o no disponible antes de efectuar la operación.

## Modelos Desarrollados ✨

Para abordar esta problemática, **desarrollé y comprendí** en profundidad los siguientes modelos de bases de datos:

* **Modelo Conceptual:** Este modelo **me permitió** plasmar las ideas iniciales y las relaciones fundamentales entre las entidades de negocio, sin preocuparme por detalles técnicos de implementación. Lo encontrarás representado en el archivo `modelo.drawio`. 🧠
* **Modelo Lógico:** Aquí **transformé** el modelo conceptual en una estructura más detallada, definiendo atributos, claves primarias y foráneas, y las cardinalidades entre las entidades. Este modelo es independiente de cualquier sistema de gestión de bases de datos específico. Se encuentra en el archivo `modelo-logico.drawio`. 🧩
* **Modelo Físico:** Finalmente, este modelo representa la implementación específica de la base de datos, considerando el tipo de datos, restricciones y la estructura de tablas para un sistema de gestión de bases de datos relacional. El archivo `modelado-fisico.architect` contiene este diseño. 🏗️

A lo largo de este proyecto, **afiancé mis conocimientos** en:

* **Entidades:** **Identificando** los objetos principales del negocio (clientes, libros, editoriales, pedidos).
* **Relaciones entre Entidades:** **Estableciendo** cómo se conectan estas entidades entre sí (ej., un cliente realiza un pedido, un libro pertenece a una editorial).
* **Atributos:** **Definiendo** las características específicas de cada entidad (ej., nombre del cliente, título del libro).
* **Cardinalidad:** **Comprendiendo** la cantidad de instancias de una entidad que pueden relacionarse con instancias de otra entidad (ej., un cliente puede tener muchos pedidos, un libro tiene un solo autor).

**Espero** que estos modelos sean de utilidad para entender la estructura de datos que **propuse** para "Club Del Libro". 😊

---

¡Gracias por visitar **mi** repositorio! 😄
