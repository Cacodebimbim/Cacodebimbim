mindmap
  %% Configuración de estilos para los nodos y enlaces %%
  skinparam defaultFontName Arial
  skinparam defaultFontSize 14
  skinparam nodeMargin 10

  %% Nodos %%
  1("Conjuntos")  %% Categoría %%
  2("Tipos de Conjuntos")  %% Categoría %%
  3("Operaciones")  %% Categoría %%
  4("Ejemplos")  %% Categoría %%

  %% Enlaces %%
  1 -- 2  %% Enlace entre Categoría y Tipos de Conjuntos %%
  1 -- 3  %% Enlace entre Categoría y Operaciones %%
  2 -- 4  %% Enlace entre Tipos de Conjuntos y Ejemplos %%
  3 -- 4  %% Enlace entre Operaciones y Ejemplos %%

  %% Ejemplos de Tipos de Conjuntos %%
  2.1("Conjunto Vacío")  %% Tipo de Conjunto %%
  2.2("Conjunto Unitario")  %% Tipo de Conjunto %%
  2.3("Conjunto Finito")  %% Tipo de Conjunto %%
  2.4("Conjunto Infinito")  %% Tipo de Conjunto %%
  2.5("Conjunto Igual")  %% Tipo de Conjunto %%

  %% Ejemplos de Operaciones %%
  3.1("Unión")  %% Operación %%
  3.2("Intersección")  %% Operación %%
  3.3("Diferencia")  %% Operación %%
  3.4("Complemento")  %% Operación %%
  3.5("Producto Cartesiano")  %% Operación %%

  %% Ejemplos %%
  4.1("Ejemplo 1")  %% Ejemplo %%
  4.2("Ejemplo 2")  %% Ejemplo %%
  4.3("Ejemplo 3")  %% Ejemplo %%
  4.4("Ejemplo 4")  %% Ejemplo %%
  4.5("Ejemplo 5")  %% Ejemplo %%

  %% Iconos %%
  classDef icon1 fill:#1f77b4,stroke:#1f77b4,stroke-width:0
  classDef icon2 fill:#ff7f0e,stroke:#ff7f0e,stroke-width:0
  classDef icon3 fill:#2ca02c,stroke:#2ca02c,stroke-width:0

  %% Asignación de iconos a los nodos %%
  1.icon1
  2.icon2
  3.icon3

  %% Ubicación de los nodos %%
  1 -!-> 2
  1 -!-> 3
  2 -!-> 4
  3 -!-> 4

