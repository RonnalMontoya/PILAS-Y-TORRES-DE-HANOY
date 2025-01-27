EXPLICACION DEL CODIGO:
Verificación de paréntesis balanceados:
Utilizamos una pila para empujar los caracteres de apertura ({, [, ( ).
Cuando encontramos un carácter de cierre (}, ], )), verificamos que coincida con el último carácter en la pila.
Si la pila está vacía al final, la fórmula está balanceada.

Torres de Hanoi:
Empleamos tres pilas (source, target, auxiliary) para simular los tres postes.
La función recursiva MoveDisks maneja el movimiento de discos entre las pilas, mostrando los pasos necesarios para resolver el problema.
