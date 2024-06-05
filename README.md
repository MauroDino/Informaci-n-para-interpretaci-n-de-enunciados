Para empezar, si hay corte de control y dice:
"el elemnto no debe procesarse": se utiliza WHILE porque parte de una pre-condición, por lo que ésta debe ser verdadera para entrar en el bucle de la estructura de control
Ejemplo: ingresar números enteros hasta que se lea el 0 que no se debe procesar.
var
  num: integer;

read (num); //Se lee un número ingresado por teclado
while (num <> 0) do //Mientras el número ingresado (num) sea distinto a 0 - Mientras el número ingresado (num) no sea 0
  begin
    writln ('El número es: ', num); //Imprime en pantalla el número (num)
  end;

"el elemento debe procesarse": se utiliza REPEAT (todo lo que se debe procesar) UNTIL (dato). 

Ejemplo: ingresar números enteros hasta que se lea el 0 que debe procesarse.
var
  num: integer;

read (num); //Se lee un número ingresado por teclado
repeat
  begin
    writeln ('El número es: ', num); //Imprime en pantalla el número (num)
  end;
until (0); //Una vez que num sea 0, el programa termina luego de procesarlo. Es decir, 0 va a ser el último en ser impreso en pantalla
end;

Si el enunciado dice:
"A lo sumo 10" significa que el máximo es 10
"Al menos 10" significa que el mínimo es 10
Esto generalmente se usa con los ARRAY para determinar Dimensión Lógica o Dimensión Física.
