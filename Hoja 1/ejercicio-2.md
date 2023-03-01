#### EJERCICIO 2

##### Demostrar que 
$$  \[ \sum_{i=1}^n \left(x_i-\avg{x}\right)^2 = \min_{a\in \real} \sum_{i=1}^n(x_i-a)^2 \] $$


Definimos una función $\[ g(a) = \sum_{i=1}^n(x_i-a)^2 \]$ buscamos su derivada $\[ g'(a) = -2 \sum_{i=1}^n(x_i-a) \]$ e igualamos a cero:

$$\begin{gather*}
-2 \sum_{i=1}^n(x_i-a) = 0 \\
\sum_{i=1}^n x_i - \sum_{i=1}^n a = 0 \\
n \avg{x} = n a \\
\avg{x} = a 
\end{gather*}$$