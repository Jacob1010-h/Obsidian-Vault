2025-07-05 11:07

Status: #done 

Tags: [[physics 2]] [[source charges]] 

# The Electric Potential

`V`, The electric potential is created by [[source charges]], just like electric fields [[Electric Fields and Charges]]

There are 2 different ways to calculate the electric potential energy

The potential of a point charge:
$$
V_{\text{ point }} = \frac{1}{4\pi\epsilon_{0 }} \frac{q}{r}
$$
The principle of superposition
$$
V = V_{1 } + V _{2 } + V_{3 }+ \dots
$$


> [!example] What to do for a continuous distribution of charge
**Model** Model as a simple charge distribution.
>
>**Visualize** Draw a pictorial representation.
>
>- Establish a coordinate system.
>- Identify where the potential will be calculated.
>
>**Solve** Set up a sum.
>
>- Divide the charge into point-like .
  >  
>- Find the potential due to each .
  >  
>- Use the charge density to replace with an integration coordinate, then sum by integrating.
  >  
>
>_V_ is easier to calculate than because potential is a scalar.

# Electric Potential Energy
`q` is places in an electric potential `V`, the system's electric potential energy is:
$$
U_{\text{ elec}} = qV
$$

The electric potential energy of two point charges is
$$
U_{q_{1} + q_{2} } = \frac{Kq_{1} q_{2}}{r} = \frac{1}{4\pi\epsilon _{0 }} \frac{q_{1} q_{2}}{r}
$$
The potential energy of two opposite charges is negative because when two opposite charges interact with each other the energy released generates kinetic energy, subtracting from the potential energy. 

---
We can see this by looking at the formula for `K/KE` or Kinetic Energy 
$$
KE = \frac{1}{2 }mv^2
$$
In physics 1 we might remember the law of the conservation of energy, though this we know that $\Delta K = \Delta U$ [[Potential and Field#Conservation of Energy]]
There are a few different ways that we can show this relationship but here is one of the most popular:
$$
K_{1} + U_{1} = K_{2} + U_{2}
$$
To sum it up, the total energy in the system `E` is the combination of `KE`,  `U`, and `E_th` (the thermal energy of the system) (the mechanical energy is the same equation but without thermal energy) 
$$
E = K + U + E_{th}
$$
---

By taking a look at the relationship between our Kinetic and potential, we can derive the equation telling us that the Mechanical energy of the system is conserved:
$$
K_{f} + q V_{f} = K_{i} + qV_{i} 
$$
This is only true if the $U_{\text{ elec}} = qV$

---

The potential energy in an electric field of an electric **dipole** with dipole moment $\vec{p}$ is 
$$
U_{\text{elec}} = -pE\cos \theta = -\vec{p} \cdot \vec{E}
$$

> [!example] Solving conservation of energy problems
> 
> **Model** Model as an isolated system.
> 
> **Visualize** Draw a before-and-after representation.
> 
> **Solve** Mechanical energy is conserved.
> 
> - Mathematically $K_{f} + q V_{f} = K_{i} + qV_{i}$.
>     
> - $K$ is the sum of the kinetic energies of all particles.
>     
> - $V$ is the potential due to the source charges.


---
Inside of a Parallel-plate capacitor
$$
V = Es
$$
$$
U_{\text{elec}} = qEs
$$
where s is measured from the negative plate to the positive plate. 


The electric field inside this plate can be resumed by the the potential difference of the capacitor $\Delta V_{C}$ (or the distance `d` multiplied by `E`) (in other words, `s = d`)
$$
\Delta V_{C }= V_{+} - V_{-} = Ed
$$
$$
E = \frac{\Delta V_{C}}{d}
$$

This means that $V = (\frac{\Delta V_{C}}{d})s$ inside of a capacitor 


> [!NOTE] Units
> Electric potential: 1 V = 1 J/C
> 
> Electric field 1 V/m = 1 N/C

# References


