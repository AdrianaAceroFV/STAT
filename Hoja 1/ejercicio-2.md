
# EJERCICIO 2

### Demostrar que 
$$   \sum_{i=1}^n \left(x_i-\overline{\rm x}\right)^2 = \min_{a\in {\rm \!R}} \sum_{i=1}^n(x_i-a)^2 $$


##### Se define la función:
$$ g(a) = \sum_{i=1}^n(x_i-a)^2 $$ 

##### Se calcula su derivada 
$$ g'(a) = -2 \sum_{i=1}^{n}(x_i-a) $$ 

##### igualando a cero:
$$\begin{gather*}
-2 \sum_{i=1}^n(x_i-a) = 0 \\
\sum_{i=1}^n x_i - \sum_{i=1}^n a = 0 \\
n \overline{\rm x} = n a \\
\overline{\rm x} = a 
\end{gather*}$$