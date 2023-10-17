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
   
Una ecuación está conformada por una igualdad que relaciona expresiones algebraicas de una o más variables.   
   
Por ejemplo   
   
\begin{equation}   
   3x + 4 = 5   
   \label{eq:lineal}   
\end{equation}   
   
Es usual llamar a las expresiones algebraicas del lado izquierdo y derecho de la igualdad como *lado izquierdo y lado derecho de la ecuación*, respectivamente.   
   
En \eqref{eq:lineal} encontramos una ecuación lineal de una incógnita.   
   
### Ecuaciones lineales   
   
Las ecuaciones lineales siempre tienen solución. Para resolverla debemos recalcar que "toda operación matemática que hagamos del lado izquierdo, debemos hacerla del lado derecho".    
   
$$
3x + 4 =5
$$   
Podemos restar el 4 de ambos lados   
   
$$
3x + 4 - 4 = 5 - 4
$$   
   
y nos queda   
   
$$
3x = 1
$$   
   
Posterior a ello podemos multiplicar ambos lados por $1/3$ y nos queda   
   
$$
\frac{1}{3}(3x) = \frac{1}{3} (1)
$$   
   
Y de ello la solución de la ecuación que es   
   
$$
x = 1
$$   
#### Ejercicios   
   
![](images/Pasted%20image%2020231016175445.png)   
   
![](images/Pasted%20image%2020231016175457.png)   
   
### Ansatz    
   
El significado de *ansatz* proviene del alemán acercarse, y en matemáticas se lo utiliza como una "adivinanza educada". Es decir, intentamos solucionar la ecuación mediante la propuesta de una solución que sospechemos (por experiencia o por un tanteo inteligente) de que esta ecuación es o no solución. Por ejemplo, podemos ver que en la siguiente ecuación   
   
![](images/Pasted%20image%2020231016175535.png)   
   
$x=4$ es una solución. Basta con que reemplacemos el valor de $x$ en donde se requiera y se encuentra que   
   
$$
\dfrac{4^{3/2}}{4 - 6} = 4 - 8 
$$   
   
hacemos las operaciones indicadas y nos queda que   
   
$$
\frac{8}{-2} = -4
$$   
   
es decir que   
   
$$ -4 = -4$$   
   
que es matemáticamente algo cierto. Cuando sucede esto, llegar a algo que es obvio, entonces el ansatz fue correcto.   
   
**Observación importante:** Una ecuación **NO SIEMPRE** tiene soluciones. Antes de proceder a encontrar la o las soluciones de una ecuación, a veces es importante preguntarse si esta ecuación puede ser resuelta en $\mathbb{R}$   
   
   
#### Ejercicios   
   
Pruebe si los ansatz propuestos son o no solución a la ecuación mostrada   
   
![](images/Pasted%20image%2020231016180033.png)   
   
### Wolfram para resolver ecuaciones   
   
Una herramienta poderosa que es usada ampliamente en ciencias y matemáticas para resolver ecuaciones es [Wolfram Alpha](https://www.wolframalpha.com/).     
   
![](images/Pasted%20image%2020231016180225.png)   
   
Esta plataforma nos permite hacer cálculos sencillos pero también posee una herramienta que resuelve ecuaciones de todo tipo. Por ejemplo, resolvamos la ecuación \ref{eq:lineal}    
   
![](images/Pasted%20image%2020231016180920.png)   
   
Basta con ingresarla, luego de ello recorremos un poco la página y encontramos que   
   
![](images/Pasted%20image%2020231016180949.png)   
   
### Dos trucos para resolver ecuaciones   
   
   
**Truco 1**: si se tienen dos expresiones algebraicas $a$ y $b$ tal que   
   
$$\frac{a}{b} = 0$$   
   
entonces implica que $a=0$   
   
Por ejemplo, para resolver el ejercicio:   
   
**Truco 2:** si se tienen dos expresiones algebraicas $a$ y $b$ tal que   
   
$$ab= 0$$   
   
implica que a = 0 y b=0   
   
Por ejemplo si queremos resolver    
   
$$
\frac{3x - 4}{4x^2 + 2 } = 0
$$   
   
usando el truco 1, podemos identificar $a=3x+4$ y $b=4x^2 + 2$. De esta manera, basta con resolver    
   
$$
3x - 4 = 0
$$   
para obtener una solución al problema deseado.    
   
El siguiente problema es interesante porque abarca operaciones algebraicas compuestas.    
   
$$
\frac{x  + 5}{x - 2} = \frac{5}{x + 2}  + \frac{28}{x^2 - 4}
$$   
Esto se puede resolver, primero, factorizando los denominadores como sigue   
   
$$
\frac{x + 5}{x - 2} = \frac{5}{x + 2} + \frac{28}{(x-2)(x+2)}
$$   
Luego, multiplicamos por el mínimo común múltiplo que es $(x-2)(x+2)$ a cado de la ecuación, nos queda   
   
$$
(x - 2)(x + 2)[\frac{x + 5}{x - 2}] =(x - 2)(x + 2) [ \frac{5}{x + 2} + \frac{28}{(x-2)(x+2)}]
$$   
si simplificamos esto, nos queda   
   
$$
(x+2)(x + 5) = 5 (x - 2) + 28
$$   
   
simplificamos cada lado y nos queda   
   
$$
x^2 + 7x + 10 = 5x - 10  + 28
$$   
   
juntamos los términos de un lado y nos queda   
   
$$
x^2 + 2x - 8 =0
$$   
   
que se puede factorizar como   
   
$$
(x + 4)(x - 2)=0
$$   
   
y de ello, por el truco 2, las soluciones de esta ecuación son: $x = -4$ y $x=2$. Sin embargo $x=2$ no es una respuesta al problema original. ¿por qué? Esto puede verse si se analizan los dominios de las [Expresiones racionales](./output/md/Expresiones%20racionales.md).   
   
### Ecuaciones cuadráticas   
   
Una ecuación cuadrática es aquella que involucra un polinomio de orden 2 igualado a 0, es decir   
   
$$
ax^2 + bx + c = 0
$$   
   
Esta solución tiene siempre soluciones pero no todas son reales, depende de una constante llamada discriminante y que es igual a $b^2 -4ac$.    
   
Cuando el discriminante es igual a 0, la ecuación tiene una solución real. Si es mayor que 0 tiene dos soluciones reales, y si es menor que 0 no tiene ninguna solución real.   
   
La fórmula para obtener soluciones de esta ecuación es   
   
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$