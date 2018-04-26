Luego de entregar las netbooks, el facilitador debe realizar un informe donde conste la situación de cada escuela que haya visitado. Dicho informe lo representaremos “marcando” cada escuela con bolitas verdes o rojas, dependiendo de la situación.

Pueden darse tres situaciones:

1. que haya **más** netbooks que estudiantes, en cuyo caso dejaremos tantas bolitas de color `Verde` como computadoras sobren. Por ejemplo:

<gs-board>
  GBB/1.0
  size 1 1 
  cell 0 0 Azul 30 Negro 38 Verde 8
  head 0 0
</gs-board>

2. que haya **menos** netbooks que estudiantes, en cuyo caso dejaremos tantas bolitas de color `Rojo` como computadoras falten. Por ejemplo:

<gs-board>
  GBB/1.0
  size 1 1 
  cell 0 0 Azul 35 Negro 29 Rojo 6
  head 0 0
</gs-board>

3. que haya exactamente la misma cantidad, en cuyo caso no haremos nada.

> * Definí las funciones `colorSobrantes()` y `colorFaltantes()` para **encapsular** el color de las marcas.
> * Escribí el procedimiento `ReportarSituacion` que, asumiendo que el facilitador está en una escuela, informe la situación correspondiente según lo explicado anteriormente. ¡Utilizá las funciones que creaste!
