2025-06-27 20:03

Status: #almost-done

Tags:  [[electric fields]] [[force]] [[physics 2]]

# Electric Charges and Forces

**Conductors:** materials through or along which charge moves easily
- Charge moves easily though or along conductors

**Insulators:** materials on or in which charge can't move
- Charge remains fixed in or on an insulator


> [!NOTE] Units and Constants
> $K$ is the electrostatic constant
> $K = 8.99 \times 10^{9} \frac{Nm^2}{C^2}$
> $10nC = 10 \times 10^{-9} C$

> [!NOTE]
> **Protons and Electrons:** $\pm e$ where $e = 1.60 \times 10^{-19} \ C$
> - Opposites attract
> - Like charges repel
> - The force increases as the charge increases
> - The force decreases as the distance increases


The charge of an object is determined by the electrons transferred to that object
- Charge is transferred by contact between objects
- Charged objects are created by adding or removing electrons

Charged objects attract neutral objects:
- Charge polarizes metal by shifting the electron sea
- Charge polarizes atoms, creating electric dipoles
- The polarization force is always an attractive force

- @ TODO: write about the interaction of polarized wool/plastic rods
- @ TODO: talk about electric dipoles

![[Pasted image 20250627203314.png]]

$q$ (the charge) is equal to:
$$
q = (N_{p} - N_{e })e
$$
where $N_{p}$ and $N_{e}$ are the number of protons and electrons contained in the object. When $q = 0$ the object is said to be electrically neutral 

Charging by friction usually creates molecular ions as bonds are broken, exchanging electrons.
![[Pasted image 20250627212737.png]]
### Coulomb's Law
Coulomb's law is an [[inverse-square law]] 

$$
F_{12} = F_{21} = \frac{K|q_{1}q_{2}|}{r^2}
$$

![[Pasted image 20250627201850.png]]

**The angle of the charge might need to be determined, given the force vector**
$$
\phi = \arctan \frac{B_{x}}{B_{y}}
$$
	Given the X and Y values of the force vector, we can determine the angle using arctan 


> [!warning] Epsilon 0 Value
> $$
> \epsilon_{0} = \frac{1}{4\pi K}
> $$

> [!NOTE] Different ways to write the same equation
> There are multiple different ways to write the equations for Force and Electric Fields, as well as different ways to represent the Vector and non-vector forms.
> Examples of Electric Field Equations --- 
> 
> $$
> \vec{E} = \frac{\vec{F}}{q}
> $$
> $$
> \vec{E} = \frac{kq}{r^3} \vec{r}
> $$
> $$
> E = \frac{kq}{r^2}
> $$
> $$
> E = \frac{1}{4\pi \epsilon_{0}} \frac{q}{r^2}
> $$
> Examples of Force equations ---
> $$
> \vec{F} = q \cdot \vec{E}
> $$
> $$
> \vec{F} = \frac{K|q_{1} q_{2}|}{r^3} \vec{r} 
> $$
> $$
> F = \frac{1}{4\pi \epsilon} \frac{|q_{1} q_{2}|}{r^2}
> $$
> $$
> F = \frac{K|q_{1} q_{2}|}{r^2} 
> $$
> 

### Electric Field and Force
"An electric field (sometimes called E-field) is a physical field that surrounds electrically charged particles such as electrons. In classical electromagnetism, the electric field of a single charge (or group of charges) describes their capacity to exert attractive or repulsive forces on another charged object."
$$
\vec{E} = \frac{\vec{ F}}{q}
$$
this also means that the force of a given charge in an electric field is:
$$
\vec{F} = \vec{E} \cdot q
$$

The electric field exists at all points in space


The force of any given object can be determined through out good friend Newton's Law, 
we can also use that to find the acceleration of charged particle. 
$$
F = ma
$$
$$
a = \frac{F}{m }
$$
$$
\vec{a} = \frac{\vec{F}}{ m } = \frac{q}{ m } \vec{E}
$$
What this also mean is that the net force of they system is the sum of the forces acting on the system due the the conservation of energy. 
$$
\vec{F}_{net} = \vec{F}_{1} + \vec{F}_{2} + \vec{F}_{3} + \dots
$$

This is also true for Electric Fields too:
$$
\vec{ E }_{net} = \frac{\vec{F}_{1q}}{ q } + \frac{\vec{F}_{2q}}{ q } + \dots
$$


#### Electric Field models
![[Pasted image 20250628102850.png]]

- % Point charge 
$$
	\vec{E} = \frac{1}{4 \pi \epsilon_{0}} \frac{q}{r^2} \hat{r}
$$
	- ~ As we move away from the point in question the field decreases as $\frac{1}{r^2}$ 
- % Line of charge (infinitely long line)
$$
\vec{E} = \left( \frac{1}{4 \pi \epsilon _{0 }} \frac{2 | \lambda |}{r}, \begin{cases}
\text{away if +} \\
\text{toward if -}
\end{cases}  \right)
$$
	* ~ As we move away from the wire or rod in question the field decreases as $\frac{1}{r^2}$ 

	The Linear charge density $\lambda= \frac{Q}{L}$
	where $Q$ is the total charge of an object and $L$ is the length of that object. 

	- ? Now this equation might be true if we assume a perfectly uniform charged rod, but what if that changes? Well first we have to make an integral of the current solution:
$$
Q = \int_{0}^L \lambda dx
$$
	Taking what we have and substituting some function of x to $\lambda$ will do the job
	
- % Plane of charge (infinitely wide)
$$
\vec{E} \left( \frac{\eta}{2\epsilon_{0}}, \begin{cases}
 \text{ away if +} \\
\text{ toward if -}
\end{cases}  \right)
$$
	The Linear mass density $\eta = \frac{Q}{A}$
	where $Q$ is the total charge of an object and $A$ is the area
	
- % Sphere of charge
$$
\vec{E} = \frac{1}{4 \pi \epsilon _{0 }} \frac{Q}{ r^2 } \hat{r} \text{ for} > R 
$$
- & Special Case ( Disk of Charge )
$$
\eta = \frac{Q}{A} = \frac{Q}{\pi R^2 }
$$
	$R$ notates the radius of the ring, but given the charge of the ring $r_{i}$ the problem must be approached differently

	- ! These are not all of the steps, please look back to 23.4 for a full walk through 
	Calculating the total charge on the ring $i$ is:
$$
(E_{i})_{z} = \frac{1}{4 \pi \epsilon _{ 0 } } \frac{z \Delta Q_{i}}{(z^2 + r^{2}_{ i})^{3/2}}
$$
$$
(E_{\text{ disk }})_{z } = \sum_{i= 1 }^{N} (E_{i})_{z}
$$
	![[Pasted image 20250628111750.png]]
	


> [!abstract] Parallel Plate Capacitors
> A parallel-plate capacitor is just two plates that have equal but opposite charges. This generates a uniform electric field. 
Inside of a field a charged particles accelerate.
> - A charged particle in a uniform field follows a parabolic trajectory
> - A dipole feels a torque that aligns the dipole with the field
> 
> In a real world, the electric field is not uniform and will actually wrap around the edge to the opposing charged side. For this class through there will only be Ideal capacitors being talked about. 

- @ TODO: write down the definition of p (the moment) 
- @ TODO write the field on axis and in the bisecting plane
- @ TODO write the electric field inside ideal capacitor is a uniform electric field 
``
The torque acting on the dipole is:
$$
\tau = p E \sin \theta 
$$
$$
\vec{\tau}  = \vec{ p } \times \vec{E}  
$$
# References

https://en.wikipedia.org/wiki/Electric_field

