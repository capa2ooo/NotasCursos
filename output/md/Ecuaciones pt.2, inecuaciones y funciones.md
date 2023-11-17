---
{}
---
   
<div class="hidden-code">   
```   
<script>   
MathJax = {   
   tex: {   
    tags: 'ams'   
  },   
    chtml: {   
        scale: 1.3   
},   
    svg: {   
         scale: 1.3   
    }   
 };   
</script>   
``` </div>   
   
Esta entrada del sitio web servirá como un pequeño repaso para el examen 2 en los temas de ecuaciones, inecuaciones y funciones. Recuerde que la otra entrada a estudiar debe ser [Expresiones racionales](./output/md/output/md/Expresiones%20racionales.md) y [Ecuaciones](./output/md/Ecuaciones.md).   
   
![](images/Pasted%20image%2020231117161119.png)   
   
Para resolver la primera ecuación recordemos que, cuando exista una expresión que contenga una raíz cuadrada, la forma de despejarla es pasando todo lo que no tenga que ver con ella hacia el otro lado y luego elevar al cuadrado, es decir   
   
$$
\sqrt{x + 1} = 8 -2x
$$   
luego tenemos que   
$$
x + 1 = (8-2x)^2
$$   
procesamos el binomio cuadrado    
$$
x + 1 = 64 - 32x + 4x^2
$$   
recolectamos todos los términos en común de un lado y nos queda   
   
$$
4x^2 -33x - 63
$$   
Utilizamos la fórmula cuadrática para obtener que   
   
$$
x = \frac{33 \pm \sqrt{33^2 - (4)(4)(63)}{}}{2(4)} = \frac{33 \pm 9 }{8}
$$   
Lo cual nos arroja dos soluciones, $x=3$, $x=21/4$.   
   
Esto aún no es la solución del ejercicio. Debemos comprobar que funcionen. Si usamos a $x = 3$ tenemos que   
   
$$
\sqrt{3 + 1} = 8 - 2(3) 
$$   
es decir   
   
$$
2 = 2
$$   
por lo cual sí es solución. En cambio, si probamos con $x=21/4$ no se cumple la ecuación. Compruébelo usted mismo.   
   
Para el segundo literal, recuerde que resolver una ecuación con valor absoluto de la forma $|x| = a$, esto implica que $x  = a$  o que $x = -a$.    
   
De ello tenemos que   
   
$x - 4 = 0.0001$, de lo cual tenemos a la solución $x = 4.0001$   
   
Luego tenemos que   
   
$$
x - 4 = - 0.0001
$$   
   
Y de ello $x = 3.9999$.   
   
Siendo ambas soluciones admisibles.   
   
![](images/Pasted%20image%2020231117163114.png)   
   
Notemos que la nueva esfera debe tener el volumen acumulado de las otras 3.    
   
Es decir    
   
$$
V = \frac{4 \pi (2)^2}{3} +\frac{4 \pi (3)^2}{3} + \frac{4 \pi (4)^2}{3}
$$   
procesando   
   
$$
V = \frac{4 \pi}{3} (29)
$$   
tenemos que   
   
$$
V = \frac{4 \pi}{3} 29
$$   
Ahora tenemos que este volumen es igual a    
   
$$
V = \frac{4 \pi}{3} r^3
$$   
Despejando nos queda que   
   
$$
r = (29)^{1/3}
$$   
![](images/Pasted%20image%2020231117163745.png)   
   
Para la primera inecuación, ya ha sido advertido que hacer multiplicación cruzada llevará a errores, por ello procedemos a restar y tenemos que   
   
$$
\frac{x + 2}{x + 3} - \frac{x - 1}{x - 2} < 0
$$   
con ello   
   
$$
\frac{(x+2)(x-2) - (x-1)(x+3)}{(x+3)(x-2)}<0
$$   
Luego   
   
$$
\frac{x^2  - 4 -(x^2 +2x -3)}{(x +3)(x-2)}<0
$$   
finalmente   
$$
\frac{-(2x+1)}{(x + 3)(x-2)}<0
$$   
Tenemos 3 factores y debemos encontrar los ceros de estos tres factores. De $-(2x + 1)=0$ tenemos que $x=-1/2$ y del denominador deducimos fácilmente que $x=-3$ y $x=2$.    
   
Ahora, resolvemos por el método de tanteo en cada uno de los 4 intervalos abiertos resultantes de dividir a la recta numérica en estos cortes. Se eligieron 4 representantes de cada intervalo, y se muestra en la siguiente imagen cuáles cumplen las condiciones requeridas.   
   
![](Imagen%20de%20WhatsApp%202023-11-17%20a%20las%2017.08.01_9cca0fa5.jpg)   
   
Como podemos ver, los intervalos que si cumplen la desigualdad son $(-3, 1/2)$ y $(2, \infty)$. Es decir que la solución de nuestra inecuación es   
   
$$
x \in (-3, 1/2) \cup (2, \infty)
$$   
Para la segunda inecuación se da que   
   
$$
3 -|2x-4| \leq 1
$$   
Despejamos y tenemos que   
   
$$
-|2x - 4| \leq -2
$$   
El cambiar los signos de la desigualdad implica a su vez cambiar la orientación de la desigualdad, lo que nos da   
$$
|2x-4| \geq 2
$$   
Y esto da paso a resolver dos inecuaciones, la primera siendo   
   
$$
2x - 4 \geq 2
$$   
cuya solución es   
$$
x \geq 3
$$   
La otra en cambio es   
   
$$
2x -4 \leq -2
$$   
resuelta por   
$$
x \leq 1
$$   
La solución completa, que es la unión de ambas soluciones, es:   
   
$$
x \in ( - \infty, 1) \cup (3, \infty)
$$   
![](images/Pasted%20image%2020231117172325.png)   
Este ejercicio se resuelve planteando el hecho de que $T$, que es la temperatura, es una función de $x$, y queremos encontrar la región en donde $T(x)$ sea menor que 500. Es decir que   
   
$$
 \frac{600000}{x^2 + 300} < 500
$$   
$$
600000 < ( x^2 + 300 )(500)
$$   
   
nótese que aquí he realizado la multiplicación cruzada, justificada por el hecho de que $x^2 + 300$ es siempre mayor que 0.   
   
$$
600000 < 500 x^2 + 150000
$$   
Arreglamos un poco la ecuación y tenemos que   
$$
500 x^2 - 450000 > 0
$$   
   
Lo que vamos a hacer aquí es dividir para 500 y tenemos que   
   
$$
x^2 > 90 
$$   
La ecuación cuadrática nos ayuda y nos queda que   
$$
x > 30
$$   
y que   
   
$x < 30$   
   
Como estamos hablando de distancia, la única solución que nos importa es la positiva. De lo cual tenemos que estar a más de 30 metros para sentir menos de 500 grados centígrados.   
   
![](images/Pasted%20image%2020231117173324.png)   
   
Para la primera tenemos que   
   
$$
L(0.5c) = 10 \sqrt{1 - \frac{(0.5c)^2}{c^2}} = 10 \sqrt{1 - 0.25} = 10 \sqrt{0.75} = 10 \sqrt{0.75} \approx 8.66
$$   
Para la segunda tenemos que   
   
$$
L(0.9c) = 10 \sqrt{1 - \frac{(0.9c)^2}{c^2}} = 10 \sqrt{1 - 0.81} = 10 \sqrt{0.19} = 10 \sqrt{0.19} \approx 4.36
$$   
El dominio se encuentra haciendo que la raíz cuadrada no sea negativa, es decir que   
   
$$
1 - \frac{v^2}{c^2} \geq 0
$$   
   
De ello tenemos que   
   
$$
v^2/c^2 \leq 1
$$   
es decir que   
   
$$
v = \leq c
$$   
Esto significa que los objetos pueden alcanzar como máximo la velocidad de la luz para que las leyes de la física se cumplan.   
   
![](images/Pasted%20image%2020231117174337.png)   
![](images/Pasted%20image%2020231117174519.png)   
La función se ve más o menos así. El dominio es $[-3, 5]$, el rango es $[-525, 4]$. Los cortes en x son -1.41, 0, 1.41. El corte en y es 0.   
   
$g(x)$ nos queda   
   
![](images/Pasted%20image%2020231117174802.png)   
 El dominio es $[-3, 5]$, el rango es $[-4, 525]$. Los cortes en x son -1.41, 0, 1.41. El corte en y es 0.