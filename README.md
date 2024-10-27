# Taller-de-especificidad

Parte 1: Introducción Teórica a la Especifidad
-
  ¿Qué es la Especifidad?<br>
    <br/>-La especificidad es la suma de diferentes valores según el tipo de selector que se utice, y es necesaria cuando múltiples reglas de estilo intentan aplicar propiedades diferentes al mismo elemento en una página, generando conflicto en CSS porque solo un conjunto de reglas puede aplicarse para cada propiedad de un elemento, así el navegador decide cuál regla aplicar por medio de la especifidad.<br>
    <br/>-Los selectores básicos ayudan al definir estilos en elementos y son importantes en la especificidad, ya que se asignan diferentes valores a cada tipo de selector, y estos valores se suman para determinar qué reglas tienen prioridad.<br>
    <br/>Reglas de cálculo de Especifidad<br>
    <br/>-Selectores de ID (#id): Aportan 100 puntos de especificidad, tienen una especificidad muy alta, porque son únicos por página.<br>
    <br/>-Selectores de clase, atributos y pseudoclases: Cada uno tiene un valor de 10 puntos, porque, son menos específicas que los ID, pero más específicas que los selectores de elementos.<br>
    <br/>-Selectores de elementos y pseudoelementos: Cada uno tiene un valor de 1 punto, porque, se suelen utilizar para aplicar estilos generales a etiquetas específicas.<br>
    <br/>-Selectores universales, combinadores y pseudoclases negadas: No afectan la especifidad.<br>
    <br/>-!important: Css sigue un orden en cascada y especifidad, pero, cuando hay un !important en una regla se aplica como prioridad, pero, si múltiples reglas tienen !important, el navegador calcula la especificidad para aplicar una.

Parte 2: Ejemplos prácticos
-
Parte 3: Ejercicios prácticos
-
  Ejercicio 1, Calulando la Especifidad:
  Ejercicio 2, Resolviendo Conflictos de Especifidad:
  
Parte 4: Desafío final
-
  Desafío, Diseñando una página completa con Estilos Conflictivos:
  
Parte 5: Revisión y discusión
  Conclusión:
