# Chapter 9 of Sean Carroll's spacetime and geometry
_edited by Liu Boyuan_
> Our ability to find positive- and negative-frequency solutions (as the coefficients of annihilation and creation operators) can be traced to the existence of a timelike Killing vector $\partial_{t}$ in MInkowski spacetime, while the invariance of Fock space under changes of basis can be traced to the fact that all such timelike Killing vectors are related by Lorentz transformations.

### QFT in curverd spacetime
$$\mathcal{L}=\sqrt{-g}\left(-\frac{1}{2}g^{\mu\nu}\nabla_{\mu}\phi\nabla_{\nu}\phi-\frac{1}{2}m^{2}\phi^{2}-\xi R\phi^{2}\right)$$
$$ \pi=\frac{\partial\mathcal{L}}{\partial(\nabla_{0}\phi)}=\sqrt{-g}\nabla_{0}\phi $$ 
$$[\phi(t,\vec{x}),\phi(t,\vec{x}')]=[\pi(t,\vec{x}),\pi(t,\vec{x}')]=0,\quad [\phi(t,\vec{x}),\pi(t,\vec{x}')]=\frac{i}{\sqrt{-g}}\delta^{n-1}(\vec{x}-\vec{x}')$$
$$ \square\phi-m^{2}\phi-\xi R\phi=0 $$
Here $g^{00}=1$**?**

- inner product for a spacelike hypersurface $\Sigma$ with induced metric $\gamma_{ij}$:  
$$ (\phi_{1},\phi_{2})=-i\int_{\Sigma}\left(\phi_{1}\nabla_{\mu}\phi_{2}^{*}-\phi_{2}^{*}\nabla_{\mu}\phi_{1}\right)n^{\mu}\sqrt{\gamma}d^{n-1}x $$

> What we lost in curved spacetime is any reason to prefer one set of modes over any other.
> Different observers disagree with each other on how many particles are observed in certain states, due to different sets of modes, i.e. sets of orthonormal solutions of the equation of motion. 
> **what we cannot  decide on a natural set of basis modes that all inertial observers would identify as particles. **

- Bogolubov transformation (between different sets of modes $g$ and $f$) :  
$$ g_{i}=\sum_{j}(\alpha_{ij}f_{j}+\beta_{ij}f_{j}^{*}),\quad f_{i}=\sum_{j}(\alpha_{ji}^{*}g_{j}-\beta_{ji}g_{j}^{*})  $$
$$ \hat{a}_{i}=\sum_{j}\left(\alpha_{ji}\hat{b}_{j}+\beta_{ji}^{*}\hat{b}_{j}^{\dagger}\right),\quad  \hat{b}_{i}=\sum_{j}\left(\alpha_{ij}^{*}\hat{a}_{j}-\beta_{ij}^{*}\hat{a}_{j}^{\dagger}\right) $$

- an example: the vacuum state of $f$ seen from $g$:  
$$\langle 0_{f}|\hat{n}_{gi}|0_{f}\rangle =\sum_{j}|\beta_{ij}|^{2}$$

- what we detect:  
$$ \frac{D}{d\tau}f_{i}=-i\omega f_{i} $$

> If the detector's trajectory follows along  orbits of the Killing field (the four-velocity $U^{\nu}=dx^{\nu}/d\tau$ is proportional to $K^{\nu}$), the proper time will be proportional to the Killing time $t$, and modes that are positive-frequency with respect to this Killing vector will serve as a natural basis for describing Fock space. 

- Hadamard state (unique singularity structure for the natural vacuum in Minkowski spacetime)  
$$ G(x_{1},x_{2})=\langle\psi|\phi(x_{1})\phi(x_{2})|\psi\rangle=\frac{U(x_{1},x_{2})}{4\pi^{2}\sigma_{\epsilon}}+V(x_{1},x_{2})\ln\sigma_{\epsilon}+W(x_{1},x_{2}) $$
where $\sigma_{\epsilon}=g_{\mu]nu}(x_{1}^{\mu}-x_{2}^{\mu})(x_{1}^{\nu}-x_{2}^{\nu})+2i\epsilon(t_{1}-t_{2})+\epsilon^{2}$, $U$, $V$ and $W$ are regular at $x_{1}=x_{2}$, $U(x,x)=1$.

> It can be shown that the renormalized energy-momentum tensor is well-defined and nonsingular in all Hadamard states, and furthermore that it will be singular in any non-Hadamard state. 
> If the Hadamard condition is obeyed on some partial Cauchy surface, it will be obeyed everywhere in the domain of dependence.

### The Unruh effect
 - constant acceleration trajectory in a flat spacetime:  
 $$ x^{2}(\tau)=t^{2}(\tau)+\alpha^{2} $$
 
 - new coodinates ($\eta,\xi$) for $x>|t|$ (Rindler space):  
 $$ t=\frac{1}{a}e^{a\xi}\sinh(a\eta),\quad x=\frac{1}{a}e^{a\xi}\cosh(a\eta)\\
 ds^{2}=e^{2a\xi}(-d\eta^{2}+d\xi^{2}) $$
 
 - the constant acceleration path is given by  
 $$ \eta(\tau)=\frac{\alpha}{a}\tau,\quad \xi(\tau)=\frac{1}{a}\ln\left(\frac{a}{\alpha}\right) $$
 
 - $\partial_{\eta}$ is a Killing vector with certain surface gravity $\kappa$:  
 $$ \partial_{\eta}=a(x\partial_{t}+t\partial_{x}),\quad V=\sqrt{-K^{\mu}K_{\mu}}=e^{a\xi},\quad \kappa=\sqrt{\nabla_{\mu}V\nabla^{\mu}V}=a $$
 
> Along the surface $t = 0$, $\partial_{\eta}$ is a hypersurface-orthogonal timelike Killing vector, except for the single point x = 0 where it vanishes. 
> This vector can therefore be used to define a set of positive- and negative-frequency modes, on which we can build a Fock basis for the scalar-field Hilbert space.

 - massless Klein-Gordon equation:  
 $$ \square\phi=e^{-2a\xi}(-\partial_{\eta}^{2}+\partial_{\xi}^{2})\phi=0 $$
 
 - normalized plane wave solutions ($\omega=|k|$):  
 $$ g_{k}^{\pm}=\left\{\begin{aligned}
 \frac{1}{\sqrt{4\pi\omega}}e^{\pm i\omega\eta+ik\xi},\quad \text{defined region}\\
 0,\quad \text{undefined region} 
 \end{aligned}
 \right.
 $$
 where $-$ is for $x>|t|$ (as the defined region), while $+$ for $x<-|t|$. These forms a complete set of basis modes.

> An individual Rindler mode can never be written as a sum of positive-frequency Minkowski modes;
> The Rindler annihilation operators (i.e. $\hat{b}_{k}^{\pm}$) are necessarily superpositions of Minkowski creation and annihilation operators, so the two vacua cannot coincide.
 
 - a properly set of normalized modes (with $\hat{c}_{k}^{\pm}$ as annihilation operators) suitable for the whole spacetime:  
 $$ h_{k}^{\pm}=\frac{1}{\sqrt{2\sinh(\pi\omega/a)}}\left[e^{\pi\omega/(2a)}g_{k}^{\pm}+e^{-\pi\omega/(2a)}g_{-k}^{\mp *}\right] $$
 which share the same vaccum state with that of Minkowski spacetime $|0_{M}\rangle$
 
 - the Minkowski vaccum state seen from Rindler space:  
 $$ \langle 0_{M}|\hat{n}_{R}^{-}|0_{M}\rangle=\langle 0_{M}|\hat{b}^{-\dagger}_{k}\hat{b}^{-}_{k}|0_{M}\rangle= \frac{1}{2\sinh(\pi\omega/a)}\langle 0_{M}|e^{-\pi\omega/a}\hat{c}^{-}_{-k}\hat{c}^{-\dagger}_{-k}|0_{M}\rangle=\frac{1}{e^{2\pi\omega/a}-1}\delta(0) $$
 which is a Planck spectrum with temperature $T=a/(2\pi)$ (as the special case with $\xi=0$ **?**)
 
> **It reveals the essentially thermal nature of the vacuum in quantum field theory.**

 - generally speaking $T=\alpha/(2\pi)$, where $\alpha=ae^{-a\xi}=a/V$
 
### The Hawking effect
> ** Assumption: the  quantum state of some scalar field $\phi$ looks like the Minkowski vacuum (free of any particles) as seen by freely-falling observers near the black hole. ** 
> The acceleration is very large compared with the scale set by the event horizon, i.e. the scale of spacetime curvature.
> The vacuum state near the horizon looks nonsingular to freely-falling observers, i.e. the renormalized energy-momentum tensor is taken to be finite at the horizon, or equivalently, the two-point function obeys the Hadamard condition.

- The static observer looks just like a constant-acceleration observer in flat spacetime, and will detect $T_{1}=a_{1}/(2\pi) $, so an observer far away from the horizon will detect (due to redshift)  
$$ T_{2}=\frac{V_{1}}{V_{2}}T_{1},\quad  \lim_{r_{1}\rightarrow r_{\text{horizon}}}T_{2}=\frac{\kappa}{2\pi} $$
where $\kappa=\lim(Va)$ is the surface gravity, $\kappa=1/(4GM)$ for a Schwarzschild BH.

- the general spectrum  
$$ \langle \hat{n}_{\omega}\rangle= \frac{\Gamma(\omega)}{e^{2\pi(\omega-\mu)/\kappa}\pm 1}$$
 where $\mu$ is the chemical potential (characterizing the tendency of the black hole to shed its conserved quantum numbers), **Hawking radiation tends to bring black holes to a Schwarzschild state.**

 - $\Gamma(\omega)$ is a greybody factor, which can be thought of as arising from backscattering of wavepackets off of the gravitational field and into the black hole (significant for low frequencies when the wavelength is greater than the horizon whose area is $A$):  
 $$ \Gamma(\omega)\rightarrow 1,\quad \omega\gg\frac{1}{GM};\quad \Gamma(\omega)\rightarrow\frac{A}{4\pi}\omega^{2},\quad \omega\ll\frac{1}{GM} $$
 (for scalar fields around a Schwarzschild BH)
 
 - virtual particle pair picture  
 > The total energy of the virtual pair must add to zero, but the infailing particle can have a negative energy as viewed from infinity, because the asymptotically-timelike Killing vector is spacelike inside the horizon. **?**
 
- The existence of event horizon is crucial for Hawking radiation. 
- evaporation:  
> As the mass shrinks, the surface gravity increases, and with it the temperature; there is a runaway process in which the entire mass evaporates away in a finite time.

$$ \tau_{BH}=\left(\frac{M}{m_{P}}\right)^{3}\tau_{P}\sim\left(\frac{M}{M_{\odot}}\right)^{3}\times 10^{71}\text{sec} $$

 - information loss paradox: violation of unitarity
 - String Theory: strong coupled --\> weak coupled, information is preserved in a region near the singularity until late times
- nonlocality: the infomation contained in the BH is spread out nonlocally across the horizon  
holographic principle: _The number of degrees of freedom in a region of space is not proportional to the volume of the region (as would be expected in a local field theory), but rather to the area of the boundary of the region._
> One can imagine that all of the physical phenomena we observe in the universe could be described by the nonlocal holographic projection of some ordinary nongravitational theory defined in lower dimensions.
## Supplementary on black holes
 
 
 