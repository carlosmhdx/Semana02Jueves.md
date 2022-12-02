# Semana02Jueves.md
Semana 02 - Día Jueves - 01/12/2022

# Tablas de verdad ✅o❌

T T = T& ✅
T F = F& ❌
F T = T& ❌
F F = F& ❌
T T = T| ✅
T F = F| ✅
F T = T| ✅
F F = F| ❌
~T = T ❌
~F = T ✅
(TF) (F) = T&|~ ✅
(TF ) (FF) = T|&| ❌
~((TF) (FF)) F = T|&|& ✅
~((TF) (FF)) T = F|&|& ✅

# Algoritmo booleano

Algoritmo boolean
	
  a <- 5 == 3
	// Falso 5 no es igual a 3
	b <- 4 <> 3
	// Verdadero 4 es diferente de 3
	c <- 7 > 7
	// Falso 7 no es mayor a 7
	d <- 4 < 4
	// Falso 4 no es menor que 4
	e <- 100 <= 90
	// Falso 100 no es igual o menor que 90
	f <- 40 >= 40
	// Verdadero 40 es igual o mayor que 40
  
FinAlgoritmo

# Identificar Par o Impar

Algoritmo IDODDEVEN
	
	Leer X
	
	Resto <- X % 2
	
	Si Resto = 0 Entonces
		Imprimir "Número ", X, " es par "
	SiNo
		Imprimir "Número ", X, " es impar "
	Fin Si
	
FinAlgoritmo

