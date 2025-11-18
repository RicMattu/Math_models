# Equations of the atmosphere
The goal of this article is to derive the equations which describes the atmpsphere.

## 1) Navier-Stokes
Let's start from the second Netwton's law[^1] in the differential form:
> $$ \frac{dv}{dt} = \frac{F}{m}$$

Where $v$ is the velocity vector in the three dimensional space $\mathbb{v}=(v_x,v_y,v_z)$, 
it is considered with respect to an absolute reference system[^2].

It is convenient to express the II N. law as:
> $$ \frac{d v}{dt} = M$$

where $M = \frac{F}{m}$ is the force for unit of mass.

Since we observe the events from the Hearth, it is convenient to express equations from this reference system.  
Ignoring the motion of revolution, we have to consider the rotation of the planet around his axis.  
Denting by $\omega$ the angular speed of the Hearth, by $\mathbb{u}$ the speed relative to a system solidal with the Hearth and $\mathbb{r}$ the position respect to the cenetr of the planet:
> $$\mathbb{v} = \mathbb{u} + \omega \times \mathbb{r}$$
---------------------------------------------------------------------------------------------------
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

Synthesis of the quantities
|Quantity|Nature|Full expression| Unit of measurement |
|:---:|:---:|:---|:--:|
$v$ | vector |(v_x,v_y,v_z) |$m/s$|
$t$ | scalar |- |$s$|
$m$ | scalar |- |$kg$|
$F$ | vector |(F_x,F_y,F_z) |$N = kg \cdot m/s^2$|
$M$ | vector | $F/m$ |$N/kg = m/s^2$|



where $M = \frac{F}{m}$ is the force for unit of mass.






## Bibliography
1. Cherchi Annalisa, Corti Susanna *Clima 2050*, Zanichelli Editore, 2025.

[^1]:(https://en.wikipedia.org/wiki/Newton%27s_laws_of_motion)
[^2]: without going into technical details, we can just think about it as a fixed reference system which contains the Hearth and the Sun.
