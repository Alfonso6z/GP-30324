# Algorimtos
## Etapas
Un algoritmo consta de tres etapas para la resolución de un problema:
* <span style="color:#7030A0">Análisis del problema</span>: con qué datos se cuenta, cuáles son necesarios como valores de entrada, qué restricciones deben considerarse, cómo debe ser la salida para que el problema se resuelva.
* <span style="color:#7030A0">Construcción del algoritmo</span>: se refiere a la descripción detallada de los pasos que deben seguirse para resolver el problema.
* <span style="color:#7030A0">Verificación del algoritmo</span>: consiste en el seguimiento de éste, empleando datos que son representativos del problema que se desea resolver (se le conoce como prueba de escritorio).
---
## Ejemplo
### Problema
Se desea realizar el cálculo de la $velocidad$ de un automóvil que recorre una distancia $x$ en un cierto tiempo $t$. (Emplear la fórmula $v=\frac{x}{t}$)

### Análisis
* Como <span style="color:#7030A0">datos de entrada</span> se necesitan el valor de la distancia $x$ y el valor del tiempo $t$.  

* En las <span style="color:#7030A0">restricciones</span> se observa que el $tiempo$ no puede ser cero pues se indetermina la operación, tampoco puede ser negativo. La $distancia$ puede ser positiva o negativa, ya que el automóvil puede ir retrocediendo, pero no puede ser cero porque el problema indica que el automóvil recorre una cierta distancia.  

* Finalmente se obtiene como <span style="color:#7030A0">resultado</span> la velocidad tras aplicar la fórmula $v=\frac{x}{t}$

### Construcción del algoritmo.
Inicio
1. Leer el valor de x
1. Si $x=0$ regresar al paso 1, en caso de lo contrario ir al paso 3.
1. Leer el valor de $t$
1. Si $t≤0$ entonces Teminar, en caso contrario ir al paso 5.
1. Realizar $v=\frac{x}{t}$
1. Mostrar $v$  

Fin

### Prueba de escritorio
---
Dados los valores $x=3$ y $t=0$. 

Inicio
1. $x=3$
1. $¿x=0?$ No, ir al paso 3.
1. t=0
1. $¿t≤0?$ Sí, Terminar.
1. -x-
1. -x-  

Fin

---
Dados los valores $x=5$ y $t=7$.

Inicio
1. $x=5$
1. $¿x=0?$ No, al paso 3.
1. $t=7$
1. $¿t≤0?$ No, ir al paso 5.
1. $v=\frac{5}{7}$
1. $v=0.715$   

Fin 

---
## Errores más comunes que se pueden cometer.
1. Crear un algoritmo sin analizar el problema previamente.
1. Dar por sentado que el algoritmo está bien diseñado sin haber realizado la prueba de escritorio para verificarlo.
1. No detallar los pasos que se siguen en el algoritmo, ya que provocan ambigüedades en el mismo.
1. No realizar la prueba de escritorio tomando valores críticos, pues éstos demostrarían si el algoritmo toma o no en cuenta las restricciones establecidas.
1. Olvidar que los pasos son secuenciales y saltarse algún paso, debido a una suposición, sin que el algoritmo así lo indique.

