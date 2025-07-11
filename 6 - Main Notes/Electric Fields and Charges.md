2025-07-05 10:17

Status: #done

Tags: [[electric fields]] [[physics 2]] [[source charges]]

# Electric Charges

The source charge in physics 2 refers to a charged particle that creates an electric field in the surrounding space. It is the origin of the electric force experienced by test charges. 

The charge of an object is determined by the electrons transferred to that object
- Charge is transferred by contact between objects
- Charged objects are created by adding or removing electrons

Charged objects attract neutral objects:
- Charge polarizes metal by shifting the electron sea
- Charge polarizes atoms, creating electric dipoles
- The polarization force is always an attractive force

- @ TODO: write about the interaction of polarized wool/plastic rods


![[Pasted image 20250627203314.png]]

$q$ (the charge) is equal to:
$$
q = (N_{p} - N_{e })e
$$
where $N_{p}$ and $N_{e}$ are the number of protons and electrons contained in the object. When $q = 0$ the object is said to be electrically neutral 

Charging by friction usually creates molecular ions as bonds are broken, exchanging electrons.
![[Pasted image 20250627212737.png]]
[[Forces]]
The combined electric field is equal to the sum of the electric fields within the region, also read as:
$$
\vec{E}_{iq} = \frac{\vec{F}_{iq}}{q}
$$
$$
\vec{ E }_{net} = \frac{\vec{F}_{1q}}{ q } + \frac{\vec{F}_{2q}}{ q } + \dots
$$
---
The Field on an axis of a dipole is equal to:
$$
\vec{E} = \frac{1}{4\pi \epsilon_{0}} \frac{2\vec{p}}{r^3}
$$

The Field in bisecting plane of a dipole is equal to:
$$
\vec{E} = -\frac{1}{4\pi \epsilon_{0}} \frac{\vec{p}}{r^3}
$$
---

Inside of a parallel-plate capacitor, the electric field inside an ideal capacitor is a uniform electric field from positive to negative:

$$
\vec{E} = \frac{Q}{\epsilon _{0 }A}
$$

---
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
	





# References
https://en.wikipedia.org/wiki/Electric_field

