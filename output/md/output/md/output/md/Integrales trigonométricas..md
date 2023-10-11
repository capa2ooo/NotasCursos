---
{}
---
   
```
<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>
```
   
      
         
         
La primera técnica para resolver estas integrales es dejar una función trigonométrica de la forma $\int f(x) g(x) dx = \int h(u) du$, en donde $du = g(x) dx$ y $g(x)$ es la derivada de una función trigonométrica.         
         
Por ejemplo, en la siguiente integral         
         
![](../../../../images/Pasted%20image%2020231010141430.png)         
El paso clave es reconocer que nuestro cambio de  variable va a ser: $u = cos(x)$ y que por lo tanto $du = -sin(x) dx$         
         
A continuación se deja una tabla, de recordatorio, con la función trigonométrica y su respectiva derivada         
         
         
| Función trigonométrica      | Diferencial |         
| ----------- | ----------- |         
| $cos(x)$      | $-sin(x)$       |         
| $sin(x)$      | $cos(x)$       |         
| $tan(x)$      | $sec^2(x)$       |         
| $sec(x)$      | $tan(x)sec(x)$       |         
| $csc(x)$      | $-csc(x)cot(x)$       |         
| $cot(x)$      | $-csc^2(x)$       |         
         
         
         
Y ejemplos del uso de esta técnica         
         
![](../../../../images/Pasted%20image%2020231010141614.png)         
![](../../../../images/Pasted%20image%2020231010141648.png)         
         
Otras integrales consideran a las siguientes identidades         
         
         
$$sin(x)sin(y) = \frac{1}{2}(cos(x - y) - cos(x + y) )$$         
         
         
además         
         
         
$$cos(x)cos(y) = \frac{1}{2}(cos(x - y) + cos(x + y) )$$         
         
y que         
         
         
$$sin(x)cos(y) = \frac{1}{2} (sen(x-y) + sen(x+y))$$         
         
por ejemplo, las siguientes:         
         
![](../../../../images/Pasted%20image%2020231010141558.png)![](../../../../images/Pasted%20image%2020231010141752.png)         
![](../../../../images/Pasted%20image%2020231010141740.png)