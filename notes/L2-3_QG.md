## Black Hole Thermodynamics
_edited by Liu Boyuan_
### The Reissner-Nordstrom BH
$$ ds^{2}=-f(r)dt^{2}+\frac{1}{f(r)}dr^{2}+r^{2}d\Omega^{2} $$
$$f(r)=1-\frac{2M}{r}+\frac{Q^{2}}{r^{2}}=\frac{1}{r^{2}}(r-r_{+})(r-r_{-}),\quad r_{\pm}=M\pm\sqrt{M^{2}-Q^{2}}, \quad A_{\mu}dx^{\mu}=-\frac{Q}{r}dt$$
($r_{+}$ is the position of event horizon)  

- 'entropy': $S\equiv\frac{1}{4\hbar G_{N}}\times\text{Area of horizon}$, $A=4\pi r_{+}^{2}$

> Kerr metric
> $$ds^{2}=-\frac{\Delta(r)}{\rho^{2}}(dt-a\mathrm{sin}^{2}\theta d\phi)^{2}+\frac{\rho^{2}}{\Delta(r)}dr^{2}+\rho^{2}d\theta^{2}+\frac{1}{\rho^{2}}\mathrm{sin}^{2}\theta[adt-(r^{2}+a^{2})d\phi]^{2}$$
> where 
$$\Delta(r)=r^{2}+a^{2}-2Mr,\quad \rho^{2}=r^{2}+a^{2}\mathrm{cos}^{2}\theta$$
> Area of horizon: $A=4\pi(r_{+}^{2}+a^{2})=8\pi Mr_{+}$

### Thermodynamics of the R-N BH
- 1st law:
$$ dS=\frac{4\pi}{f'(r_{+})}dM-\frac{4\pi Q}{f'(r_{+})r_{+}}dQ $$
- 'temperature':
$$TdS=dM-\Phi dQ,\quad T\equiv\frac{r_{+}-r_{-}}{4\pi r_{+}^{2}}, \quad \Phi=\frac{Q}{r_{+}}$$
- $T$ related to the _surface gravity_: $T=\frac{\kappa}{2\pi}$  
 - $\kappa$ is constant everywhere on the horizon of a stationary BH: '0'th law of thermodynamics'
 - $\kappa$ is the acceleration due to gravity near the horizon times the redshift factor  
- Hawking proved, directly from the Einstein equation, that _in any physical process the area of the event horizon can never decrease_.

- Exercise (about R-N BH)
 - (a) $\epsilon=p^{0}f(r)+qQ/r$, since $K^{\mu}=(1,0,0,0)$, $A_{0}=-Q/r$, $g_{00}=-f(r)$
 - $q<0$, of course
 - (c) $\epsilon=f(r)\sqrt{\left(p^{r}/f(r)\right)^{2}-1}+qQ/r$, since $1=-f(r)(p^{0})^{2}+(p^{r})^{2}/f(r)$
 - (d) $\epsilon_{min}=qQ/r_{+}=\Phi q$, since $\epsilon(r_{+})=|p^{r}(r_{+})|+qQ/r_{+}$, that is to say, $\delta S=(\epsilon-\Phi q)/T\ge 0$
 - (e) the initial condition at $r$ should be $p^{0}=qQr/[r_{+}(r-r_{-})]$, which requires that $qQ>0$  

`Higher curvature corrections in the BH entrophy may lead to violation of the 2nd law of thermodynamics.`

- Black holes must have enormous of states (see Chp 9 of Carroll's):  
$$ S_{BH}\sim 10^{90}\left(\frac{M}{10^{6}M_{\odot}}\right),\quad S_{M}\sim 10^{88}$$
($S_{M}$ is the entropy for all matter other than BHs within one Hubble radius, i,e, number of relativistic particles)

> Black hole entropy is a rare and important gift from nature: an infrared constraint on the ultraviolet completion, that we should take very seriously in trying to quantize gravity.

### Rindler Space
$$ds^{2}=dR^{2}-R^{2}d\eta^{2}(+d\vec{y}^{2})$$

- a patch of Minkowski space with $x>0,\quad |t|<x$ ($x=R\mathrm{cosh}\eta,\quad t=R\mathrm{sinh}\eta$), polar coordinates with $\eta=i\phi$
- Rindler observer: at fixed $R$, i.e., along an uniformly accelerating trajectory, sees a horizon at $R=0$
- approximate Rindler space near the BH horizon:  
$$ds^{2}=-f(r)dt^{2}+\frac{dr^{2}}{f(r)}+r^{2}d\Omega^{2},\quad f(r)=1-\frac{2M}{r}$$
where we make the coordinate change (as $f(r)\rightarrow 0$)
$$r=2M(1+\epsilon^{2}),\quad f(r)\approx \epsilon^{2}$$
and the expansion at small $\epsilon$ to give
$$ds^{2}=-\epsilon^{2}dt^{2}+16M^{2}d\epsilon^{2}+4M^{2}d\Omega^{2}+\cdots$$

> Trick: in the black hole metric, the time coordinate must be periodic in the imaginary direction, and this imaginary periodicity implies that the black hole has a temperature. **?**


- QFT at finite temperature is periodic in imaginary time: $t\sim t+i\beta,\quad \beta=1/T$
- thermal Green's function ($T_{E}$ is the Euclidean-time ordering):
$$G_{\beta}(\tau,x)=-\frac{1}{Z}\mathrm{Tr}e^{-\beta H}T_{E}[O(\tau,x)O(0,0)]=G_{\beta}(\tau-\beta,x),\quad \tau=it,\quad -\beta<\tau<\beta$$ 
(time translation: $O(\tau,x)=e^{\tau H}O(0,x)e^{-\tau H}$) **?**
- $\eta\sim \eta+2\pi i$, $t=4M\eta$, leads to 
$$t\sim t+i\beta,\quad \beta=8\pi M,\quad T=\frac{1}{8\pi M}$$
- Exercise: Kerr periodicity
 - (a) $O(\tau,x,\phi)=e^{\tau H-\phi J}O(0,x,0)e^{-\tau H+\phi J}$ **?** 
$$G_{\beta}(\tau,x,\phi)=-\frac{1}{Z}\mathrm{Tr}e^{-\beta H+\beta\Omega J}T_{E}[O(\tau,x,\phi)O(0,0,0)]=G_{\beta}(\tau-\beta,x,\phi+\beta\Omega)$$
$$(t,\phi)\sim(t+i\beta,\phi-i\beta\Omega)$$
 - (b) expansion with $r=r_{+}(1+\epsilon^{2})$ at $\theta=\pi/2$:
$$ds^{2}=\frac{4r_{+}^{3}}{r_{+}-r_{-}}d\epsilon^{2}+\frac{1}{r_{+}^{2}}\left(adt-(r_{+}^{2}+a^{2})d\phi\right)^{2}\\\\
+\left[-\left(1-\frac{r_{-}}{r_{+}}\right)(dt-ad\phi)^{2}-\frac{2}{r_{+}^{2}}\left(adt-(r_{+}^{2}+a^{2})d\phi\right)^{2}-4(adt-(r_{+}^{2}+a^{2})d\phi)+2r_{+}^{2}d\theta^{2})\right]\epsilon^{2}+\cdots$$
 - (c) set $adt-(r_{+}^{2}+a^{2})d\phi=0$, i.e. $\tilde{\phi}=(r_{+}^{2}+a^{2})\phi-at=const.$, and $d\theta=0$, we have  
$$d\tilde{s}^{2}=d\epsilon^{2}-\frac{1}{4}\left(\frac{r_{+}-r_{-}}{r_{+}^{2}+a^{2}}\right)^{2}\epsilon^{2}dt^{2} $$
from which we know that $\eta=\frac{1}{2}\left(\frac{r_{+}-r_{-}}{r_{+}^{2}+a^{2}}\right)t$, together with $r_{+}^{2}+a^{2}=2Mr_{+}$, we have 
$$ \frac{1}{2}\left(\frac{r_{+}-r_{-}}{r_{+}^{2}+a^{2}}\right) \beta=2\pi, \quad \beta=8\pi M\frac{r_{+}}{r_{+}-r_{-}},\quad \Omega=\frac{a}{r_{+}^{2}+a^{2}}=\frac{a}{2Mr_{+}}$$
which is consistent with the entropy formula $S=2\pi Mr_{+}$

### Unruh Radiation
- a Rindler observer at fixed $R=1/a$ feels a heat bath at temperature $T=a/(2\pi)=\hbar a/(2\pi ck_{B})$  

`In general, there is no such thing as the vacuum state, only the vacuum state according to some particular observer.`
> The energy is the expectation value of the Hamiltonian; and the Hamiltonian is the operator that generates time evolution $i[H,O]=\hbar\partial_{t}O$. Therefore the Hamiltonian depends on the choice of time $t$.

- If $H_{\eta}$ is the Hamiltonian that generates $\eta$-translations, the density matrix for fields in Rindler space is $\rho_{Rindler}=e^{-2\pi H_{\eta}}$, which leads to $T=1/(2\pi)$
`The Rindler temperature is fixed by symmetries, and holds even for strongly interacting field theories, for example QCD.`

### Hawking radiation
- periodicity in imaginary time + near horizon region as Rindler space (a particular state which is regular on the past and future event horizon, i.e. _Hartle-Hawking vacuum_) --> **A BH radiate like a blackbody at temperature $T=a/(2\pi)$ (in thermodynamic equilibrium with its surroundings).**
- more explicit and more convincing derivation:
> One is to match in modes to out modes and calculate Bogoliubov coefficients; 
> the other method is using Euclidean path integrals to put the imaginary-time trick on a solid footing.

- greybody factor (the absorption cross-section of a mode hitting the black hole): absorption and re-emission of radiation by the intervening geometry, 
> If you stand far from a black hole, you will actually not quite see a blackbody.

(from Chp 9 of Carroll's)
> - Hawking vacuum: regular on both the past and future event horizons, flux from the BH towards the future null infinity is the thermal radiation, but there is also an equal flux coming from the past null infinity towrds the BH 
 - Unruh vacuum:  singular on the past event horizon (no flux coming in)
 - Boulware vacuum: singular on both the past and future event horizons

### A picture to understand BH radiation
 - given a timelike killing vector $K^{\mu}$ (normalized at certain point O0 of the static trajectory at infinity or certain point outside the event horizon)
 - consider a static observer O1 with $U^{\mu}=VK^{\mu}$ and the free-falling observer O2 at the same point in the manifold with that corresponds to O1
 - the acceleration of O1 measured by O2 diverges as they approach the event horizon
 - **the quantum field seems like the Minkowski vacuum from the point view of O2**
 - transform from the coordinates R0 of the static oberver O0  to a speical form R2 $(\epsilon,t)$ in which we find that the metric tends to be in the form of Rindler space near the event horizon (this statement is consistent with the assumption made above)  
 (this is done by expansion of the metric near the horizon)
 - in this R2, we find O1's motion is specified by $\epsilon(\tau)=\epsilon(t(\tau))\equiv const.$ which means a constant acceleation relative to O2, approximately, **in flat spacetime**, while the horizon corresponds to $\epsilon=0$
 - the acceleration is just $a_{2}=\kappa/\epsilon$ which indeed diverges as $\epsilon\rightarrow 0$, so O2 will detect Unruh radiation at temperature $T_{2}=a_{2}/(2\pi)$ 
 - but seen from O0, due to redshift, we have $a_{0}=a_{2}\times \epsilon\alpha$, and $T_{0}=\alpha\kappa/(2\pi)$, where $\alpha\le 1$ is a factor relative to the normalization of $K^{\mu}$ and equals to 1 if O0 is at the infinity

## Supplementary on black holes
_see Chp3 and 6 of Carroll's_
### Killing vector
- vector field for which $ K\_{\nu}p^{\nu} $ is conserved along a geodesic trajectory:  
$$ p^{\mu}\nabla\_{\mu}(K\_{\nu}p^{\nu})=0,\ i.e.\quad \nabla\_{(\mu}K\_{\nu)}=0 $$  
The metric is unchanging along the direction of the KIlling vector. If the metric is independent of $x^{\sigma\_{\*}}$, then $\partial\_{\sigma\_{\*}}$ is a KIlling vector.

- Killing vector fields on a manifold are in one-to-one correspondence with continuous symmetries of the metric on that manifold. 
with geodesic motion.  
$$ \nabla\_{\mu}\nabla\_{\sigma}K^{\rho}=R^{\rho}\ \_{\sigma\mu\nu}K^{\nu},\quad \nabla\_{\mu}\nabla\_{\sigma}K^{\mu}=R\_{\sigma\nu}K^{\nu},\quad K^{\lambda}\nabla\_{\lambda}R=0 $$

- The existence of a timelike Killing vector implies energy conservation for the entire spacetime:  
$$ J^{\mu}=K\_{\nu}T^{\mu\nu},\quad \nabla\_{\mu}J^{\mu}=0 $$
We can define the conserved energy by intergration over a spacelike hypersurface $\Sigma$:
$$ E=\int\_{\Sigma}J^{\nu}n\_{\nu}\sqrt{\gamma}d^{n-1}x $$ 

### Event horizons
- An event horizon is a hypersurface separating those spacetime points that are connected to infinity by a timelike path from those that are not.  
It is the boundary of the causal past of future null infinity, a null hypersurface $\Sigma$ defined by $f(x)=const.$ (the normal vector is null and also tangent to $\Sigma$), a collection of null geodesics $x^{\mu}(\lambda)$ as generators:
$$ \xi^{\mu}=\frac{dx^{\mu}}{d\lambda}=h(x)g^{\mu\nu}\partial\_{\nu}f,\quad \xi\_{\mu}\xi^{\mu}=0,\quad \xi^{\mu}\nabla\_{\mu}\xi^{\nu}=0 $$  
(here the function $h(x)$ is chosen so that the geodesic is affinely parameterized)

- for stationary metrics:
$$ g^{rr}(r\_{H}=0) $$  
 where
 $$ g^{\mu\nu}(\partial\_{\mu}r)(\partial\_{\nu})=g^{rr} $$

- cosmic censorship conjecture:
> Naked singularities cannot form in gravitational collapse from generic, initially nonsingular states in an asymptotically flat space-time obeying the dominant energy condition.
**generic?**

- area theorem:
> Assuming the weak energy condition and cosmic censorship, the area of a future event horizon in an asymptotically flat spacetime is non-decreasing.

### Killing horizons
- If a Killing vector field $\chi^{\mu}$ is null along (also normal to) some null hypersurface $\Sigma$, $\Sigma$ is a Killing horizon of $\chi^{\mu}$

- surface gravity $\kappa$:  
$$ \chi^{\mu}\nabla\_{\mu}\chi^{\nu}=-\kappa\chi^{\nu} $$
$$ \kappa^{2}=-\frac{1}{2}(\nabla\_{\mu}\chi\_{\nu})(\nabla^{\mu}\chi^{\nu}) $$

- normalization in an asymptotic spacetime:  
$$ K\_{\mu}K^{\mu}(r\rightarrow\infty)=-1 $$  
> In a static, asymptotically flat spacetime, the surface gravity is the acceleration of a static observer near the horizon, as measured by a static observer at infinity.

- static oberver:
$$ K^{\mu}=VU^{\mu} $$  
where $V=\sqrt{-K\_{\mu}K^{\mu}}$ is the redshift factor. Since the conserved energy is $E=-p\_{\mu}K^{\mu}$, and the frequency measured is $\omega=-p\_{\mu}U^{\mu}$, we have $\omega=E/V$, $\lambda\_{2}=V\_{2}\lambda\_{1}/V\_{1}$

- acceleration  
$a^{\mu}=U^{\sigma}\nabla\_{\sigma}U^{\mu}$, $a\_{\mu}=\nabla\_{\mu}\ln V$  
**?**
$$ a=\sqrt{a\_{\mu}a^{\mu}}=V^{-1}\sqrt{\nabla\_{\mu}V\nabla^{\mu}V} $$  
which diverges at the Killing horizon, but seen from outer obervers, we have
$$ aV=\sqrt{\nabla\_{\mu}V\nabla^{\mu}V}=\kappa $$
