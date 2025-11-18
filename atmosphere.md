# Equations of the atmosphere
The goal of this article is to derive the equations which describes the atmosphere.

## 1) Navier-Stokes
Let's start from the Netwton's second law[^1] in differential form:
> $$ \frac{dv}{dt} = \frac{F}{m}$$

Where $v$ is the velocity vector in three-dimensional space $\mathbb{v}=(v_x,v_y,v_z)$, 
it is considered with respect to an absolute (inertial) reference frame[^2].

It is convenient to express the II N.L. as:
>  $$\frac{d v}{dt} = M$$  
where $M = \frac{F}{m}$ is the force per unit of mass.

Since we observe the events from the Hearth, it is convenient to express equations from an Hearth-fixes reference frame.  
Ignoring the motion of revolution, we consider only the rotation of the planet around his axis (which makes the frame non-inertial). 
Denoting by $\Omega$ the angular velocity of the Hearth ($\Omega = 7.3 \cdot 10^{-5} s^{-1}$) , by $\mathbb{u}$ the veocity relative to a rotating system solidal with the Hearth and by $\mathbb{r}$ the position vector with respect to the planet's center, the famous Poisson's relationship[^3] holds:
> $$\mathbb{v} = \mathbb{u} + \omega \times \mathbb{r}$$

which reads: 
> *The velocity of a body in a fixed (inertial) reference system is equivalent to the velocity in the rotating system, plus the vectorial product between the angualar velocity and the position with respect to the rotating reference.*

<!--
#### Example
An ordinary airbus for voli di linea, such as the Airbus A330 has a cruise speed of around $1000 \frac{km}{h}$.  
It is measured with respect to the air around, but let's assume that is day without wind so the velocity is relative to an observator in the grouns (solidal with the Hearth): $u = 10^3 km/h$.  
Now, we know that $\Omega = 7.3 \cdot 10^{-5} s^{-1}$ and that it planes at $11 \cdot 10^3 m$ over the observer.  
The Hearth radius is of $6.371 km$ so  
-->
Applying the Poisson relation to $v$ instead of $r$ one has:
>$$ (\frac{d}{dt} v)_{fix} = (\frac{d}{dt} v)_{rot} + \Omega \times v$$

Then, substituting the P.R. for $r$, the equation becomes
> $$(\frac{d}{dt} v)_{fix} = (\frac{d}{dt} u)_{rot} + 2\Omega \times u + \Omega \times (\Omega \times r)$$

Where
- $2\Omega \times u$ represents the Coriolis acceleration  
- $\Omega \times (\Omega \times r)$ is the centrifugal acceleration

Now let's focus on the right-hand side of the N.L. The main forces (for unit of mass) which appears in athmospheric motus are:
- gradient of the pressure $\nabla p$ multiplied by the specific volume $\alpha$
- the gravitation $g_a$
- the friction $f$
Thus
> $$ M = - \alpha \nabla p + g_a +f $$
<!--
Perché il meno?
-->
Putting them in the previous result we obtain the equation of the motion of a system in rotating coordinates:

> $$\frac{d u}{dt} = -\alpha \nabla p - 2\Omega \times  V + g + f$$  

where $g = g_a - \Omega \times (\Omega \times r)$.  
That equation, which is the Newton equations for fluids in rotating frames, is called Navier-Stokes eq.[^4]
<!--
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
-->






## Bibliography
1. Cherchi Annalisa, Corti Susanna *Clima 2050*, Zanichelli Editore, 2025.

[^1]: [Newton Laws](https://en.wikipedia.org/wiki/Newton%27s_laws_of_motion)
[^2]: Without going into technical details, we can just think about it as a fixed reference system which contains the Hearth and the Sun.
[^3]: [Poisson relation](https://it.wikipedia.org/wiki/Relazione_di_Poisson)
[^4]: [Navier-Stokes](https://en.wikipedia.org/wiki/Navier%E2%80%93Stokes_equations)
