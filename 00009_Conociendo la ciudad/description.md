Nos queda el último pasito, hacer que un facilitador recorra una ciudad completa. Así es cómo se ve una ciudad de seis calles en nuestro tablero:

<gs-board>
  GBB/1.0
    size 6 7
    cell 0 0 Rojo 6
    cell 0 1 Verde 3
    cell 2 1 Azul 6 Negro 3
    cell 3 1 Azul 13
    cell 0 2 Verde 5
    cell 1 2 Negro 3
    cell 3 2 Negro 7
    cell 4 2 Azul 13 Negro 13
    cell 5 2 Azul 5 Negro 1
    cell 0 3 Verde 2
    cell 1 3 Azul 15 Negro 4
    cell 2 3 Azul 11 Negro 1
    cell 0 4 Verde 3
    cell 1 4 Azul 4 Negro 4
    cell 2 4 Negro 7
    cell 3 4 Negro 10
    cell 0 5 Verde 4
    cell 4 5 Azul 2 Negro 2
    cell 0 6 Verde 1
    cell 1 6 Azul 1 Negro 2
    head 0 0
</gs-board>

Cada ciudad tiene una cantidad de calles diferente, y a su vez cada calle tiene su propia longitud. Esto ya viene señalizado por nosotros en el tablero de la siguiente manera:

* las bolitas rojas del origen indican **cuántas calles tiene** nuestra ciudad;
* las bolitas verdes de cada fila indican **qué tan larga es la calle**.

> Tu trabajo es escribir el procedimiento `RecorrerCiudad()`, que realice un **recorrido** por todas las calles de la ciudad, haciendo el trabajo necesario.