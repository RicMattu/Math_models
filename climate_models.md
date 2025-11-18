# Equations of the atmosphere

### 1) Navier-Stokes
Let's start from the second Netwton's law in the differential form:
> $$ \frac{dv}{dt} = \frac{F}{m}$$

Now let's consider the velocity vector in a three dimensional space $V_a$  
where the index $a$ stands for _absolute_ meaning that the velocity is 
considered respect to an absolute reference system

> $$ \frac{d_a V_a}{dt} = M$$

and $M = \frac{F}{m}$ is the force for unit of mass.

Since we want to consider the Hearth system, ignoring the motion of revolution, we consider the rotation of the planet arounf his axis.  
Denting by $\Omega$ the angular speed, $V$ the speed relative to a system solidal with the Hearth and $r$ the position respect to the cenetr of the planet:
> $$V_a = V + \Omega \times r$$

> Example

The following equality holds for any vector of the form such as $V_a$:
> $$\frac{d_a V_a}{dt} = \frac{d_a V_a}{dt} + \Omega \times  V_a$$

Then the equation of our model becames
> $$\frac{d_a V_a}{dt} = \frac{d_a (V + \Omega \times r)}{dt} + \Omega \times  (V + \Omega \times r)$$
> 
 Che può scriversi come:
> $$\frac{d_a V_a}{dt} = \frac{d_a V}{dt} + 2\Omega \times  V + \Omega \times (\Omega \times r)$$


The main forces which appears in athmospheric motus are:
- gradient of the pression $\nabla p$
- the specific volume $\alpha$
- the gravitation $g_a$
-  the friction $f$

Putting them in the previous result we obtain the equation of the motus of a system in rotant coordinates:
> $$\frac{d V}{dt} = -\alpha \nabla p - 2\Omega \times  V + g + f$$

where $g = g_a - \Omega \times (\Omega \times r)$.

The term $2\Omega \times  V$ is often called aceleration of Coriolis

The last equation we wrote, that is the Newton equations for fluids is called Navier-Stokes eq.
> citation

### 2) Conservation of mass

### 3) Equazione di stato della termodinamica
Let's suppose we have a perfect gas that satisfies the Boyle's Law:
> $$ p \alpha = RT$$
where R and T are respectively ...


### 4) First Law of the termodynamics 
> $$\dot{Q} = frac{d I}{dt} + \dot{W}$$

> $$\dot{Q} = c_v frac{d T}{dt} + p frac{d \alpha}{dt}$$


### Final system
$$
\begin{cases}
\displaystyle 
\frac{d V}{dt} = -\alpha \nabla p - 2\Omega \times V + g + f \\
\text{mass conservation}, \\[6pt]
p\alpha = RT, \\
\ldots
\end{cases}
$$






## Bibliography
1. Cherchi Annalisa, Corti Susanna *Clima 2050*, Zanichelli Editore, 2025.
