# Quantum Physics I (MIT 8.04 - Spring 2013)

My goal here is to be able to do all the assignments using Sympy for the algebra.

## Equations Cheat Sheet

### Material Properties

#### Definition of density

$$ \rho = \frac{m}{V} $$

Where:

- $\rho$ is the density of the object
- $m$ is the mass of the object
- $V$ is the volume of the object


#### Thermal energy

$$ E_K = k_B T $$

- $E_K$ is the internal thermal energy of the object
- $T$ is the temperature of the object
- $k_B$ is the Boltzmann constant


#### Definition of heat capacity

$$ \frac{\delta Q}{\mathrm{d}T} = c_P m $$

- $c_P$ is the specific heat capacity at constant pressure
- $\delta Q$ is the heat transfer of the object
- $\mathrm{d}T$ is the change in temperature of the object
- $m$ is the mass of the object


### Kinematics

$$ \vec{v} = \frac{\mathrm{d}\vec{x}}{\mathrm{d}t} $$

$$ \vec{a} = \frac{\mathrm{d}\vec{v}}{\mathrm{d}t} = \frac{\mathrm{d}^2\vec{v}}{\mathrm{d}t^2}$$

Where:

- $\vec{x}$ is the position vector of the object
- $\vec{v}$ is the velocity vector of the object
- $\vec{a}$ is the acceleration vector of the object
- $t$ is time


#### Uniform circular motion

$$ v = \frac{2 \pi r}{T} = 2 \pi r f $$

$$ \vec{v} = \vec{r} \times \vec{\omega} $$

$$ a = \frac{v^2}{r} $$

$$ f = \frac{1}{T} = \frac{\omega}{2 \pi} $$

Where:

- $a$ is the centripedial acceleration of the object
- $v$ is the tangential velocity of the object
- $\omega$ is the angular velocity of the object
- $r$ is the radius of the circular path
- $f$ is the frequency
- $T$ is the period


#### Gravity on Earth (and other planets)

$$ E_g = m g x $$

Where:

- $E_g$ is the gravitational potential energy of the object
- $m$ is mass of the object
- $x$ is height position of the object
- $g$ is acceleration due to gravity


### Dynamics

#### Newton's second law

$$ \vec{F} = m \vec{a} $$

Where:

- $\vec{F}$ is the total force vector on the object
- $m$ is the mass of the object
- $\vec{a}$ is the acceleration vector of the object


#### Momentum

$$ \vec{p} = m \vec{v} $$

Where:

- $\vec{p}$ is the momentum vector the object
- $m$ is the mass of the object
- $\vec{v}$ is the velocity vector of the object


#### Definition of kinetic energy

$$ E_K = \frac{m v^2}{2} $$

Where:

- $E_K$ is the kinetic energy of the object
- $m$ is the mass of the object
- $v$ is the velocity of the object


#### Definition of electric potential

$$ E_V = q V $$

Where:

- $E_V$ is the electric potential energy of the object
- $q$ is the charge of the object
- $V$ is the electric potential of the electric field the object is in


#### Coulomb's law

$$ \vec{F}_{12} = \frac{1}{4 \pi \varepsilon_0} \frac{q_1 q_2}{r^2} \hat{r}_{12} = k_e \frac{q_1 q_2}{r^2} \hat{r}_{12} $$

$$ E_V = \frac{1}{4 \pi \varepsilon_0} \frac{q_1 q_2}{r} = k_e \frac{q_1 q_2}{r} $$

Where:

- $\vec{F}_1$ is the total force vector on object $1$ induced by object $2$
- $E_V$ is the electric potential energy
- $q_1$ is the charge of object $1$
- $q_2$ is the charge of object $2$
- $r$ is the distance between object $1$ and object $2$
- $\hat{r}_{12}$ is a normalized position vector pointing from object $1$ to object $2$
- $k_e$ is Coulomb's constant
- $\varepsilon_0$ is the vacuum permitivity


#### Waves

$$ v_p = \frac{\lambda}{T} $$

$$ \lambda = \frac{2 \pi}{k} $$

$$ f = \frac{1}{T} = \frac{\omega}{2 \pi} $$

Where:

- $v_p$ is the phase velocity of the wave
- $\lambda$ is the wavelength of the wave
- $T$ is the period of the wave
- $k$ is the angular wavenumber
- $\omega$ is the angular velocity

References:

- https://en.wikipedia.org/wiki/Phase_velocity

#### Dispertion relation

$$ \omega^2 = g k \tanh(k h) $$

Where:

- $\omega$ is angular velocity of the wave
- $k$ is the angular wave number
- $h$ is the depth of the medium (usually water)
- $g$ is the acceleration due to gravity

References:

- https://en.wikipedia.org/wiki/Dispersion_(water_waves)

### Quantum Mechanics

#### Larmor formula

$$ P = \frac{2}{3} \frac{q^2 a^2}{4 \pi \varepsilon_0 c^3} = \frac{2}{3} \frac{k_e}{c^3} q^2 a^2 $$

Where:

- $P$ is power radiated from the object
- $q$ is the charge of the object
- $a$ is the acceleration of the object
- $k_e$ is Coulomb's constant
- $\varepsilon_0$ is the vacuum permitivity
- $c$ is the speed of light in a vaccuum


#### Heisenberg's uncertainty principle

$$ \sigma_x \sigma_p \geq \frac{\hbar}{2} $$

Where:

- $\sigma_x$ is uncertainty in position of the object
- $\sigma_p$ is uncertainty in momentum of the object
- $\hbar$ is the reduced Planck constant


#### Photons

$$ c = \lambda f $$

$$ E_\gamma = h f = \frac{hc}{\lambda} = p c $$

Where:

- $\lambda$ is wavelength of the photon
- $f$ is frequency of the photon
- $E_\gamma$ is the energy of the photon
- $p$ is the momentum of the photon
- $h$ is the Planck constant
- $c$ is the speed of light in a vaccuum


#### deBroglie wavelength

$$ \lambda = \frac{h}{p} $$

Where:

- $\lambda$ is the deBroglie wavelength of the object
- $p$ is the momentum of the object
- $h$ is the Planck constant



