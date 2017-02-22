### Rulues
- The classical action is not renormalizable
- Gravity as a low-energy effective theory
- Graviton: massless spin-2 field
- Diffeomorphism invariant  

What is diffeomorphism symmetry**?** 

### Degree of freedom **?**
- DoF for massless particles: transformation under $SO(D-2)$, the group of rotations that preserve a null ray,  
spin-2: sysmmetric traceless tensor rep, $(D-2)(D-1)/2-1$
- dof of the metric:  
$$ \frac{1}{2}D(D+1)-D-D=\frac{1}{2}D(D-3) $$  
(independent components - diffeos - non-dynamical?)


### Effective field
$$ S=\frac{1}{16 G_{N}}\int \sqrt{g}\left(-2\Lambda+R+c_{1}R^{2}+c_{2}R_{\mu\nu}R^{\mu\nu}+c_{3}R_{\mu\nu\rho\sigma}R^{\mu\nu\rho\sigma}+\cdots\right) $$
- $[1/G_{N}]=M_{P}^{D-2}$, if $D>2$, this term is not renormalizable  
 The theory is strongly coupled at the Planck scale: non-sensical, non-unitary answers for $E\gtrsim M_{P}$
- high order terms, coefficients suppressed by the scale of new physics $M_{s}$
- if $M_{s}\ll M_{P}$, $c_{1,2,3}\sim 1/M_{s}^{2}$

### Perturbation
$$ g_{\mu\nu}=\eta_{\mu\nu}+\frac{1}{M_{P}}h_{\mu\nu} $$
- $\sqrt{g}\sim 1+\delta g$, $R\sim \partial^{2}\delta g$, $\delta g=h/M_{P}$  
$$S\sim \int\partial h\partial h+\frac{1}{M_{P}}h\partial h\partial h+\frac{1}{M_{s}^{2}}\left(\partial^{2}h\partial^{2}h+\frac{1}{M_{P}}h\partial^{2}h\partial^{2}h+\cdots\right)$$
- contribution of each diagram: $(E^{2}/M_{P}^{2})^{\text{1+number of loops}}$
- strong coupling scale: $E_{strong}\sim M_{P}^{x}M_{s}^{1-x}$

### Classical corrections
- equation of motion:  
$$ \square h+\frac{1}{M_{s}^{2}}\square\square h=8\pi G_{N}T $$  
- propagator:  
$$\frac{1}{q^{2}+M_{s}^{-2}q^{4}}=\frac{1}{q^{2}}-\frac{1}{q^{2}+M_{s}^{2}}$$
- potential:  
$$ V(r)=-G_{N}m_{1}m_{2}\left[\frac{1}{r}-\frac{e^{-rM_{s}}}{r}\right]$$
- loop corrections:  
$$ \sim \frac{1}{q^{2}}-\frac{1}{M_{s}^{2}}+\frac{1}{q^{2}}\frac{a}{M_{P}^{2}}q^{4}\mathrm{log}\frac{q^{2}}{\Lambda^{2}}\frac{1}{q^{2}}+\cdots $$
- quantum gravity term: $1/(M_{P}^{2}r^{3})$
- `Question: Is there a new scale?` ($M_{s}\ll M_{P}$), new UV physics?
- breakdown: UV-divergent (no "asymptotic safety"**?**)

### UV completion
> Gauge symmetry is not a symmetry. It is a fake, a redundancy introduced by hand to help us keep track of massless particles in quantum field theory.

**?**
> Gauge transformations acting at infinity are _true_ symmetries.
> In gravity, local diffeomorphisms are gauge symmetries. They are redundancies.
> On the other hand, diffeomorphisms that reach infinity (like, say, a global translation) are physical symmetries.
> **So apparently, to construct diff-invariant physical observables, we need to tie them to infinity.**

- Weinberg-Witten theorem: _A 4D Lorentz-invariant QFT with a conserved, gauge-invariant stress tensor $T_{\mu\nu}$ cannot have massless particles with spin > 1_
- possibilities:
> - One is that the graviton appears in the UV theory, along with other degrees of freedom which cure the problems seen in effective field theory. 
> - The other is that the graviton is an
emergent degree of freedom, but the UV theory is not an ordinary 4D QFT.

