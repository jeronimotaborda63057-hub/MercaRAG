# MercaRAG

**MercaRAG** es un sistema de gestión y recuperación de información orientado al contexto de un supermercado, que integra una base de datos relacional con tecnologías de búsqueda semántica basadas en *Retrieval-Augmented Generation (RAG)*.

El proyecto permite organizar y relacionar información sobre productos, categorías, marcas, proveedores, puntos de venta, inventarios, clientes, empleados, compras y domicilios. Además, contempla la gestión de documentos e imágenes asociados a los productos, así como el almacenamiento de consultas, resultados de recuperación y evaluaciones.

La base de datos está diseñada en **PostgreSQL**, utilizando **Neon** como servicio de base de datos y la extensión **pgvector** para almacenar y realizar búsquedas por similitud sobre representaciones vectoriales (*embeddings*) de texto e imágenes.

El modelo incorpora claves primarias y foráneas, restricciones de integridad, relaciones entre entidades e índices convencionales y vectoriales, con el objetivo de mantener la consistencia de los datos y facilitar las consultas tradicionales y semánticas.

MercaRAG se desarrolla como un proyecto académico de **Bases de Datos Relacionales**, enfocado en aplicar conceptos de modelado relacional, integridad de datos, normalización y recuperación de información en un escenario de supermercado.