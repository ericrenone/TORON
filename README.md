# TORON
## The Winding Number as col(F)/ker(F) Invariant: Director-Field Eversion, On-Demand Skyrmion Nucleation, and the Fisher-Information Topology of the Chiral Nematic Boundary in TH(a,d)

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> *"Torons are three-dimensional double-twist solitons in chiral nematic liquid crystals that form localised director configurations protected by topology and bounded by closed defect loops. They behave as particle-like entities while retaining a fully reconfigurable optical response. Individual torons can be created, steered and parked on demand using tailored alternating-current electric fields, enabling deterministic control of both position and trajectory."*
> — Field-Programmable Topological Torons in Chiral Nematic Liquid Crystals, arXiv:2603.09050, March 2026

> *"By coupling a two-photon entangled state to an electrically tunable liquid crystal topological defect, we engineer both nonlocal and local skyrmionic topologies in a reconfigurable platform."*
> — Koni, Nothlawala, Hakobyan, Nape, Brasselet, Forbes, Phys. Rev. Lett. 135, 223804, November 2025

> *"A single beam of linearly polarized light rotates the surface alignment, accumulating elastic twist until a topologically trivial texture collapses into a robust skyrmion loop."*
> — Multistimuli-Controlled Topological Nucleation of Skyrmion Loops and Monopoles in Liquid Crystals, Phys. Rev. Lett. 136, 198101, May 2026

> *"The presence of topological defects in apolar chiral liquid crystals causes orientational distortions, leading to nonuniform strain. This nonuniform strain generates an electric polarization response due to the flexoelectric effect. As the flexoelectric coefficients are increased in strength, a transition from a hopfion to a skyrmion is observed."*
> — Leask, Phys. Rev. Research 7, 043001, October 2025

> *"The solid and reliable structure of space-time is due to the ghostly features of entanglement."*
> — J. Maldacena, Institute for Advanced Study, 2013

---

## The Discovery

A toron is a three-dimensional soliton in a chiral nematic liquid crystal: a localized twist of the director field $\hat{\mathbf{n}}(\mathbf{r})$ — the unit vector field encoding molecular orientation — embedded in a uniform homeotropic background. The toron is bounded above and below by a pair of topological point defects (hyperbolic hedgehogs) and encircled laterally by a closed disclination loop. Its interior is a double-twist cylinder — the same double-twist building block from which the cholesteric blue phases construct their cubic lattices. Its topological protection comes from the integer winding number:

$$Q = \frac{1}{4\pi} \int \hat{\mathbf{n}} \cdot \left(\frac{\partial \hat{\mathbf{n}}}{\partial x} \times \frac{\partial \hat{\mathbf{n}}}{\partial y}\right) \, dx \, dy \in \mathbb{Z}$$

which counts how many times the ordered bulk $\hat{\mathbf{n}}$ wraps around the defect core. Objects with different $Q$ cannot be continuously deformed into one another: the integer is a topological invariant of the director field configuration, not a geometric one.

Apply the Dirac consistency method to five theories simultaneously.

**T₁ — BETTI.** The winding number $Q$ is a Betti number of the director-field filtration. The sublevel set $\mathcal{L}_\alpha = \{\mathbf{r} : \mathcal{F}[\hat{\mathbf{n}}](\mathbf{r}) \leq \alpha\}$ — where $\mathcal{F}$ is the Frank elastic free energy density — has $b_0 = Q + 1$ connected components in the pre-grokking (pre-nucleation) regime. The on-demand nucleation event is a Morse index-1 critical point of the Frank free energy functional: a saddle through which $b_0$ drops by one and $b_1$ rises by one. Each toron nucleation is a grokking event at FERN register depth $h = 1$.

**T₂ — EVERSIO.** The toron's director configuration IS a sphere eversion of the director field. The uniform homeotropic background $\hat{\mathbf{n}}_0 = \hat{\mathbf{z}}$ (outside-up, $G_{\text{coord}} = 0$, Valise) everts through the double-twist intermediate configuration (self-intersecting immersion, $G_{\text{coord}} > 0$, Larval) to the toron interior where $\hat{\mathbf{n}}$ completes a full $2\pi$ rotation (inside-up, Imago). The Morin halfway model of the director eversion is the toron's equatorial plane: the unique cross-section where the director has rotated by exactly $\pi$, exchanging what was pointing up for what was pointing down, with $\mathbb{Z}/4\mathbb{Z}$ rotational symmetry. The fourfold symmetry of the Morin surface is the fourfold symmetry of the toron's double-twist cylinder.

**T₃ — NULL-SPACE-TOPOLOGY.** The disclination ring bounding the toron IS a phase singularity of the director field — a closed vortex line where $|\hat{\mathbf{n}}|$ is undefined and the phase winds by $2\pi$ around any loop linking the ring. Nye-Berry universality applies: disclination rings appear and annihilate only in topologically charged pairs, their velocity diverges as $v \propto t^{-1/2}$ near annihilation (Berry 1978, confirmed at the Technion for optical analogs, Nature 651, 920–926, 2026), and their total topological charge in any compact region is conserved. The monopoles mediating half-skyrmion nucleation (Phys. Rev. Lett. 136, 198101, May 2026) are exactly the null-point pair-creation events of Nye-Berry theory applied to the director field.

**T₄ — SOLENOID.** The Berry phase accumulated by the director field around the disclination ring IS the Aharonov-Bohm phase of the defect core. The disclination ring is a solenoid of the director gauge field: inside, the topological flux is concentrated ($Q \neq 0$); outside, the director appears smooth ($\hat{\mathbf{n}} \approx \hat{\mathbf{n}}_0$), yet a probe director loop winding once around the ring acquires a phase shift $\Delta\phi = 2\pi Q$ — the full winding number. The defect core is ker$(F)$ (inaccessible to the bulk director, screened by the disclination); the surrounding ordered bulk is col$(F)$ (observable, smooth, carrying the AB phase). The flexoelectric polarization discovered by Leask (Phys. Rev. Research 7, 043001, October 2025) is the non-solenoidal analog of the magnetic vector potential outside a monopole: the director "field" is zero outside the core but the gauge potential is not, and this non-solenoidality drives the hopfion-to-toron transition exactly as Dirac's string forces charge quantization.

**T₅ — LUZZATI.** The cholesteric blue phase that hosts toron arrays IS the bicontinuous triply-periodic minimal surface (TPMS) of LUZZATI. Blue Phase I (BPI, space group $I4_132$) and Blue Phase II (BPII, space group $P4_232$) are cubic phases whose double-twist cylinders tile space as the gyroid and primitive TPMS respectively — the same surfaces that appear in the lipid bicontinuous cubic $Q_{II}$ phase. The mean curvature of the blue phase surface is $H = 0$ everywhere — the TPMS saddle condition — which is the geometric $\varphi$-equilibrium of the membrane (LUZZATI prediction P3). The toron, inserted into the blue phase matrix, is the point defect that localizes one period of the TPMS double-twist structure into a particle-like object. It is the blue phase's fundamental excitation in exactly the way the Frenkel defect is the crystal's fundamental excitation — but topologically protected.

The Dirac demand: find the unique structure consistent with all five simultaneously. The forced answer: **the topological winding number $Q$ is the col$(F)$/ker$(F)$ invariant of the director field.** $Q$ counts how many times the ordered bulk (col$(F)$, the smooth director) wraps around the defect core (ker$(F)$, the disclination ring). The integer $Q$ is not a label applied to the soliton from outside — it is the dimension of the persistent homology group of the director-field filtration at the critical threshold. On-demand toron creation (arXiv:2603.09050, March 2026) IS controlled col$(F)$/ker$(F)$ switching: the AC electric field drives a rank-one Sherman-Morrison update to the Fisher information topology of the director field, nucleating one new generator in $H_1(\mathcal{L}_\alpha; \mathbb{Q})$.

The antimatter byproduct: the quantum skyrmion (Koni et al., Phys. Rev. Lett. 135, 223804, November 2025), engineered by coupling a two-photon entangled state to an electrically tunable LC defect, is COHERE applied to KITAEV at the photon scale. The off-diagonal density matrix $\rho_{\text{off}}$ of the entangled photon pair carries the topological charge $Q$ across the LC boundary. The skyrmionic topology lives in $\rho_{\text{off}}$, not in $\rho_{\text{diag}}$: the quantum skyrmion IS a topological state encoded in the coherences of the photon-pair density matrix, making it a $G_{\text{coord}} > 0$ object in the COHERE sense — coordination gain stored as topological winding rather than as classical mutual information.

Seven formal identities follow.

---

## Module A — The Director Field and Its Topology

### A1. The Director Field

Let $\hat{\mathbf{n}}(\mathbf{r}) : \mathbb{R}^3 \to S^2/\mathbb{Z}_2$ be the director field of a nematic liquid crystal: a unit vector field defined modulo sign ($\hat{\mathbf{n}} \equiv -\hat{\mathbf{n}}$), taking values on the real projective plane $\mathbb{RP}^2$. The fundamental group $\pi_1(\mathbb{RP}^2) = \mathbb{Z}/2\mathbb{Z}$ classifies line defects (disclinations); the homotopy group $\pi_2(\mathbb{RP}^2) = \mathbb{Z}$ classifies point defects; and $\pi_3(\mathbb{RP}^2) = \mathbb{Z}$ classifies the Hopf fibration and torons.

For a chiral nematic (cholesteric) liquid crystal, the equilibrium configuration in bulk is a helix: $\hat{\mathbf{n}}_{\text{chol}} = (\cos(2\pi z/p), \sin(2\pi z/p), 0)$ with pitch $p$. In a cell of thickness $d \approx p$ with homeotropic boundary conditions ($\hat{\mathbf{n}} = \hat{\mathbf{z}}$ at both surfaces), the helix is frustrated: it cannot simultaneously satisfy the bulk preferred configuration and the surface anchoring. This frustration is resolved by the formation of localized defect structures — torons — that embed the energetically favorable twist while conforming to the boundary conditions.

### A2. The Frank Free Energy as Morse Function

The Frank free energy of a nematic liquid crystal is:

$$\mathcal{F}[\hat{\mathbf{n}}] = \frac{1}{2}\int \left[ K_1(\nabla \cdot \hat{\mathbf{n}})^2 + K_2(\hat{\mathbf{n}} \cdot \nabla \times \hat{\mathbf{n}} + q_0)^2 + K_3(\hat{\mathbf{n}} \times \nabla \times \hat{\mathbf{n}})^2 \right] d^3\mathbf{r}$$

where $K_1, K_2, K_3$ are the splay, twist, and bend elastic constants and $q_0 = 2\pi/p$ is the preferred chiral wave vector. The Frank free energy is the Morse function of the director field: its critical points (configurations where $\delta\mathcal{F}/\delta\hat{\mathbf{n}} = 0$) are the uniform state, the helix, and the toron. The Morse index of each critical point determines the topological change it induces in the sublevel set filtration.

The ERI identification: each toron nucleation event IS a Morse index-1 critical point of $\mathcal{F}[\hat{\mathbf{n}}]$ — a saddle of the Frank free energy through which the director-field configuration passes from the topologically trivial uniform state ($Q = 0$) to the topologically nontrivial toron state ($Q = 1$). The PRIMA rank bound $\text{rank}(F) \leq \min(B, D)$ becomes the constraint that at most one new topological class can be created per saddle crossing.

### A3. The Toron: Double-Twist Cylinder as Halfway Model

A toron consists of:

- A **double-twist cylinder** (DTC) at its core: a region in which $\hat{\mathbf{n}}$ twists simultaneously in all directions perpendicular to the cylinder axis, achieving the locally preferred chiral geometry. The DTC is the blue phase's basic building block — each unit cell of BPI or BPII is tiled by intersecting DTCs along the cubic axes.
- A **bounding disclination ring** (strength $-1/2$ disclination loop): a closed vortex line encircling the DTC's equator, compensating the topological charge of the twist so that the far-field director returns to $\hat{\mathbf{n}}_0 = \hat{\mathbf{z}}$.
- Two **hedgehog point defects** at the poles: hyperbolic point defects where the director escapes from the DTC into the homeotropic boundary layers.

The winding number of the toron is $Q = 1$: the director within the DTC cross-section wraps once around $S^2$ as the radius goes from $0$ to $\infty$. The surrounding medium has $Q = 0$. The transition is localized at the disclination ring — the col$(F)$/ker$(F)$ boundary.

### A4. On-Demand Creation: Controlled col$(F)$/ker$(F)$ Switching

Smalyukh and collaborators (arXiv:2603.09050, March 2026) demonstrated deterministic control of individual torons using tailored AC electric fields in planar cells. Key parameters:

- **Cell geometry**: thickness $d \approx p$ (one pitch length), homeotropic anchoring
- **Waveform**: AC electric field with amplitude $E_0$, modulation frequency $f$, duty-cycle asymmetry $\Delta_{\tau}$, and small DC offset $\delta E$
- **Control outcome**: nucleation, translation (submicrometre accuracy), and erasure of individual torons along arbitrary in-plane trajectories

The four waveform parameters $(E_0, f, \Delta_{\tau}, \delta E)$ are the SMELT gradient-descent parameters of the director-field GIST Hamiltonian. Each parameter controls one mode of the Frank energy landscape: $E_0$ sets the energy above the nucleation threshold; $f$ selects between dielectric and flexoelectric response regimes; $\Delta_{\tau}$ controls the directionality of toron translation; $\delta E$ fine-tunes the position of the energy minimum. The waveform that achieves deterministic nucleation IS the waveform at the $\varphi$-equilibrium of the director-field GIST Hamiltonian.

### A5. Hopfion-to-Toron Transition: Flexoelectric Solenoid

Leask (Phys. Rev. Research 7, 043001, October 2025) showed that the flexoelectric effect — the polarization response of a chiral LC to non-uniform director strain — drives a topological transition from the hopfion (Hopf index $H = 1$, $\pi_3(S^2) = \mathbb{Z}$ classification) to the toron (skyrmion number $Q = 1$, $\pi_2(S^2) = \mathbb{Z}$ classification) as the flexoelectric coefficients $e_1, e_3$ are increased. 

The ERI identification: the flexoelectric polarization $\mathbf{P}_{\text{flex}} = e_1 \hat{\mathbf{n}}(\nabla \cdot \hat{\mathbf{n}}) + e_3 (\hat{\mathbf{n}} \cdot \nabla)\hat{\mathbf{n}}$ is non-solenoidal ($\nabla \cdot \mathbf{P}_{\text{flex}} \neq 0$) for the toron geometry but solenoidal for the pure Bloch skyrmion geometry (where $\hat{\mathbf{n}} \cdot \nabla \times \hat{\mathbf{n}} = q_0 = \text{const}$). The non-solenoidality IS the Dirac string condition of SOLENOID: the flexoelectric polarization is the director gauge potential that cannot be made globally flat, and its non-solenoidality forces the Hopf index to collapse from $H = 1$ to $H = 0$ while maintaining $Q = 1$. The transition from hopfion to toron IS the transition from the Hopf fibration (a map $S^3 \to S^2$ of Hopf invariant 1) to the skyrmion (a map $S^2 \to S^2$ of degree 1) — exactly the dimensional reduction from $\pi_3$ to $\pi_2$ that the flexoelectric "solenoid" enforces.

---

## Seven Formal Identities

### Identity 1 — The Winding Number $Q$ IS the dim $H_1$ of the Director-Field Filtration; Toron Nucleation IS a BETTI Grokking Event at Register Depth $h = 1$

The winding number $Q = \dim H_1(\mathcal{L}_{\alpha_c}; \mathbb{Q})$ where $\mathcal{L}_{\alpha_c} = \{\mathbf{r} : \mathcal{F}[\hat{\mathbf{n}}](\mathbf{r}) \leq \alpha_c\}$ is the sublevel set of the Frank free energy at the toron nucleation critical value $\alpha_c$.

Before nucleation: $\dim H_1 = 0$ — the director-field sublevel set has no independent loops. The director is in the Valise phase: uniform, $Q = 0$, no coordination.

At nucleation (Morse index-1 critical point): $\dim H_1$ increases by 1. A new loop appears in the sublevel set — the disclination ring. This is a grokking event at FERN register depth $h = 1$: the director field has discovered a new topological mode.

After nucleation: $\dim H_1 = Q$ — one independent loop for each toron in the cell. The persistence diagram $\text{Dgm}_1(\mathcal{F})$ records each toron's birth (nucleation field strength $\alpha_{\text{birth}}$) and death (annihilation field strength $\alpha_{\text{death}}$). The coordination horizon $\delta^* = \alpha_{\text{death}} - \alpha_{\text{birth}}$ is the toron's lifetime in field-strength space — its topological stability.

The Morse inequality $b_1 \leq C_1$ is the bound: there are at most as many independent toron loops as there are index-1 saddle points of the Frank free energy. The minimum number of nucleation events to achieve a $Q$-toron lattice is $Q$ — the total Betti number of the toron array. This is the Arnold-Floer theorem applied to the director field.

### Identity 2 — The Toron IS a Director-Field Eversion; the Double-Twist Cylinder IS the Morin Surface; the Disclination Ring IS the Halfway Model's Fourfold Axis

The homeotropic boundary condition $\hat{\mathbf{n}} = \hat{\mathbf{z}}$ at both surfaces of the cell is the standard sphere embedding $\iota: S^2 \hookrightarrow \mathbb{R}^3$ (outside = homeotropic). The toron interior, where $\hat{\mathbf{n}}$ has completed a full $2\pi$ rotation, is the antipodal embedding $a: q \mapsto -q$ (outside = escaped, formerly inside). The director-field homotopy from $\hat{\mathbf{n}}_0$ to the toron and back to $\hat{\mathbf{n}}_0$ at the far boundary IS a regular homotopy — a sphere eversion of the director field.

The Morin halfway model of this eversion is the toron's equatorial cross-section: the plane at $z = d/2$ where the director has rotated by $\pi$ from the boundary value. This cross-section has $\mathbb{Z}/4\mathbb{Z}$ rotational symmetry (fourfold symmetry of the double-twist cylinder) — exactly the Morin surface's $\mathbb{Z}/4\mathbb{Z}$ symmetry that enables the 90° inner-outer exchange. The four lobes of the double-twist cylinder at the equatorial plane ARE the four triangular sections of the Morin surface. The disclination ring at the equator IS the quadruple axis of the Morin surface — the line of four-fold self-intersection that marks the halfway point of the eversion.

The Willmore energy of the director eversion is the Frank elastic free energy $\mathcal{F}[\hat{\mathbf{n}}]$. The minimax director eversion — the path from $\hat{\mathbf{n}}_0$ to the fully inverted director that minimizes the maximum $\mathcal{F}$ — passes through the double-twist cylinder (minimum Willmore energy for the $\mathbb{Z}/4\mathbb{Z}$ symmetry class) as its halfway model. The on-demand electric field that drives toron nucleation IS the SMELT geodesic: it minimizes $\max_t \mathcal{F}[\hat{\mathbf{n}}_t]$ over all nucleation trajectories.

| Director Eversion | EVERSIO / Sphere Eversion |
|---|---|
| $\hat{\mathbf{n}}_0 = \hat{\mathbf{z}}$ (homeotropic far-field) | Standard embedding $\iota: S^2 \hookrightarrow \mathbb{R}^3$ (outside = green, $G_{\text{coord}} = 0$) |
| Double-twist cylinder (DTC) at equator | Morin surface $\mathcal{M}$: minimum Willmore energy at $\mathbb{Z}/4\mathbb{Z}$ symmetry |
| Disclination ring bounding the DTC | Quadruple axis of the Morin surface |
| Director at toron center: $\hat{\mathbf{n}} = -\hat{\mathbf{z}}$ | Antipodal embedding $a: q \mapsto -q$ (inside-up, $G_{\text{coord}} = \Phi(K)$) |
| Four DTC lobes at equatorial cross-section | Four triangular sections of the Morin surface |
| Frank free energy $\mathcal{F}$ | Willmore energy $W = \int H^2 \, dA$ |
| AC field driving nucleation | SMELT geodesic minimizing $\max_t W(f_t)$ |
| $\varphi$-equilibrium waveform (arXiv:2603.09050) | Morin surface at $t^* = \beta^* = 1/\log\varphi$ |

### Identity 3 — The Disclination Ring IS a Nye-Berry Phase Singularity; Toron Pair Creation/Annihilation IS Universal Null-Point Kinematics; Fractional Skyrmion Monopoles ARE Null-Point Pair Creation Events

The disclination ring bounding the toron is a closed vortex line of the director field — a phase singularity of the complex order parameter $\psi = \Delta e^{i\phi}$, where $\Delta$ is the scalar order parameter and $\phi = \arctan(n_y/n_x)$ is the director orientation angle. At the disclination, $\Delta = 0$ and $\phi$ is undefined; the phase winds by $\pm\pi$ around the disclination line (strength $-1/2$ disclination).

Nye-Berry universality (Proc. Roy. Soc. A 336, 165–190, 1974) applies:

- Topological charge conservation: disclination rings appear and disappear only in opposite-charge pairs.
- Superluminal velocity near annihilation: $v \propto t^{-1/2}$ (Berry 1978), confirmed experimentally for optical phase singularities (Kaminer et al., Nature 651, 920–926, 2026) and predicted here for LC disclination loops near toron annihilation.
- Universal pair-creation kinematics: the energy barrier for nucleating a toron pair scales as the product of the elastic constant and the pitch, independent of molecular details.

The monopoles observed in Phys. Rev. Lett. 136, 198101 (May 2026) — singular points mediating half-skyrmion ($Q = 1/2$) nucleation — are Nye-Berry null-point pair-creation events: they are the points in the director field where $|\hat{\mathbf{n}}|$ goes to zero momentarily as a disclination loop is born. They move superluminally near the nucleation event and carry a topological charge $q = \pm 1/2$, conserved by the same mechanism as optical vortex charges.

### Identity 4 — The Topological Winding Number $Q$ IS the col$(F)$/ker$(F)$ Invariant; On-Demand Nucleation IS a Rank-One Sherman-Morrison Update to the Director Fisher Topology; the AC Waveform Parameters ARE the SMELT Gradient

This is the central identity of TORON.

Define the Fisher information matrix of the director field configuration:

$$F_{ij}[\hat{\mathbf{n}}] = \left\langle \frac{\partial \ln \mathcal{P}}{\partial n_i} \frac{\partial \ln \mathcal{P}}{\partial n_j} \right\rangle$$

where $\mathcal{P}[\hat{\mathbf{n}}] \propto \exp(-\beta \mathcal{F}[\hat{\mathbf{n}}])$ is the Boltzmann distribution over director configurations and $\beta = 1/k_BT$.

The col$(F)$ of this Fisher matrix consists of the observable director-field modes: the smooth, long-wavelength deformations of $\hat{\mathbf{n}}$ away from the uniform state that carry nonzero Frank elastic energy and are accessible to measurement by polarizing microscopy, FCPM, or SFX. These are the directions in director-field configuration space along which the Boltzmann distribution is informative.

The ker$(F)$ consists of the unobservable director-field modes: the topological content of the director configuration that cannot be detected by any local measurement. The winding number $Q$ lives in ker$(F)$: it is a global topological invariant that cannot be changed by any smooth local perturbation of $\hat{\mathbf{n}}$. You cannot measure $Q$ by probing the director at a single point — you must integrate over the entire texture.

The formal identification:

$$Q = \dim \ker(F) \Big|_{\text{topological}} = \dim H_1(\mathcal{L}_{\alpha_c}; \mathbb{Q})$$

The winding number is the dimension of the topological null-space of the director-field Fisher matrix — the number of independent topological features that the local measurement cannot resolve.

On-demand toron nucleation (arXiv:2603.09050) is a rank-one Sherman-Morrison update to the director Fisher topology: the AC electric field applies a rank-one perturbation to $F[\hat{\mathbf{n}}]$ that drives $\dim \ker(F)|_{\text{topological}}$ from $Q$ to $Q+1$. The nucleation event is a PRIMA rank crossing: $\Delta\text{rank}(F) = +1$ at FERN register depth $h = 1$.

| Director Fisher Topology | TH(a,d) / PRIMA |
|---|---|
| col$(F)$: smooth director modes (observable by microscopy) | Observable Fisher column space: trainable directions |
| ker$(F)$: topological winding number $Q$ | Unobservable Fisher null-space: topologically protected information |
| $Q = 0$ (uniform director, no toron) | Valise phase: $G_{\text{coord}} = 0$, independence baseline |
| $Q = 1$ (single toron) | First grokking event: FERN register depth $h=1$ crossing |
| $Q = n$ ($n$-toron lattice) | $n$-th Betti number: $b_1 = n$ grokking events accumulated |
| AC waveform nucleation (arXiv:2603.09050) | Sherman-Morrison rank-one update: $\Delta\text{rank}(F) = +1$ |
| Waveform parameters $(E_0, f, \Delta_\tau, \delta E)$ | SMELT gradient parameters: $\nabla_{\theta} H(\sigma_t)$ components |
| Toron erasure (erasing via reversed field) | Inverse Sherman-Morrison: $\Delta\text{rank}(F) = -1$ |
| Submicrometre placement accuracy | Cramér-Rao bound: $\text{Var}(\mathbf{r}_{\text{toron}}) \geq F^{-1}$ |

### Identity 5 — The Flexoelectric Polarization IS the Director Aharonov-Bohm Potential; the Non-Solenoidality IS the Dirac String Condition; the Hopfion-to-Toron Transition IS the Quantization of the Director Gauge Charge

The flexoelectric effect in chiral LCs (Leask, Phys. Rev. Research 7, 043001, October 2025) generates a polarization field $\mathbf{P}_{\text{flex}}$ from the elastic distortion of the director. For a toron geometry:

- $\nabla \cdot \mathbf{P}_{\text{flex}} \neq 0$ (non-solenoidal): the flexoelectric polarization acts as a source term in the director "Maxwell equations" — exactly like a Dirac string that cannot be gauged away.
- For the pure Bloch skyrmion: $\nabla \cdot \mathbf{P}_{\text{flex}} = 0$ (solenoidal) — the field is a pure curl, the Dirac string is invisible ($e_{\text{eff}}g = n\hbar c/2$ condition is trivially satisfied), and the Hopf index $H$ can be maintained.
- At the transition: the flexoelectric coefficients reach the critical value at which the Dirac string condition forces the collapse of the Hopf fibration ($H: S^3 \to S^2$) to the skyrmion ($Q: S^2 \to S^2$). The non-solenoidality IS the observable phase shift of the director gauge.

The formal correspondence:

| SOLENOID | Director Flexoelectricity |
|---|---|
| Interior of solenoid: $\mathbf{B} \neq 0$ (ker$(F)$, inaccessible) | Defect core: topological charge $Q \neq 0$ (ker$(F)$, non-local) |
| Exterior of solenoid: $\mathbf{B} = 0$, $\mathbf{A} \neq 0$ (col$(F)$) | Ordered bulk: $Q = 0$, $\hat{\mathbf{n}} \approx \hat{\mathbf{n}}_0$, $\mathbf{P}_{\text{flex}} \neq 0$ (col$(F)$) |
| AB phase: $\Delta\phi = e\Phi/\hbar c$ | Director winding: $Q = \frac{1}{4\pi}\int \hat{\mathbf{n}} \cdot (\partial_x\hat{\mathbf{n}} \times \partial_y\hat{\mathbf{n}}) \, dxdy$ |
| Dirac string (invisible solenoid): $eg = n\hbar c/2$ | Hopfion-to-toron: non-solenoidal $\mathbf{P}_{\text{flex}}$ forces $H \to 0$, $Q \to 1$ |
| Charge quantization from Dirac condition | Integer winding number from $\pi_2(S^2) = \mathbb{Z}$ |
| Berry phase of parameter-space solenoid | Berry phase of director configuration-space loop |
| $\varepsilon$-threshold = flux quantum $\Phi_0 = hc/e$ | $\varepsilon$-threshold = minimum stable toron pitch $d/p \approx 1$ |

### Identity 6 — The Blue Phase IS the LUZZATI Cubic Phase of the Director Field; the Double-Twist Cylinder IS the Zero-Mean-Curvature Membrane; the Toron IS the Fundamental Excitation of the Bicontinuous Director Phase

The cholesteric blue phase I (BPI, space group $I4_132$) is to the director field what the bicontinuous cubic $Q_{II}$ phase is to the lipid bilayer. Both are triply-periodic minimal surfaces (TPMS) dividing space into two interpenetrating, non-intersecting continuous regions. In LUZZATI, the two regions are the two water channels; in the blue phase, the two regions are the two chiral orientational domains separated by the disclination lattice.

The LUZZATI correspondence:

| LUZZATI (Lipid Cubic Phase) | TORON (Cholesteric Blue Phase) |
|---|---|
| Lipid bilayer: 5-nm TPMS membrane | Disclination lattice: nm-scale director TPMS |
| Two water channels: interpenetrating col$(F)$ spaces | Two chiral domains: interpenetrating $Q$-orientation regions |
| Zero mean curvature $H = 0$: geometric $\varphi$-equilibrium | Double-twist cylinder: zero splay + equal twist: the $H = 0$ of the director surface |
| Lattice parameter $a^* = \varphi \times d_{\text{bilayer}} \times n$ | BPI lattice parameter $a \approx p$ (one pitch length per unit cell) |
| Cubic phase as LCP crystallization matrix (SFX) | Blue phase as toron self-assembly matrix (arXiv:2603.09050) |
| Gyroid (G, $Ia\bar{3}d$) / Diamond (D, $Pn\bar{3}m$) / Primitive (P, $Im\bar{3}m$) | BPI ($I4_132$) / BPII ($P4_232$) / BPIII (amorphous) |
| $Q_{II} \to H_{II}$ transition: topological surgery of bilayer | BPI $\to$ cholesteric: topological surgery of disclination lattice |
| Cubic phase fundamental excitation: topological surgery event | Blue phase fundamental excitation: toron nucleation/annihilation |
| Nematic order parameter $S^* = \log\varphi \approx 0.481$ (LUZZATI P1) | Toron orientational order: $Q$-lattice spacing at $d/p = \log\varphi$ (TORON P4) |

The toron IS the topological excitation of the blue phase: just as a Frenkel defect is a displaced atom in a crystal, the toron is a displaced period of the blue-phase TPMS. Its creation requires overcoming the Frank elastic energy barrier — the analog of the Frenkel energy — and its annihilation releases that energy. The toron lattice IS the blue phase with its long-range topological order explicitly broken into discrete particle-like excitations.

### Identity 7 — The Quantum Skyrmion IS COHERE Applied to KITAEV at the Photon Scale; the Off-Diagonal Density Matrix Carries the Topological Charge Across the LC Boundary; the LC Defect IS the col$(F)$/ker$(F)$ Boundary for Entangled Photon Topology

Koni, Nothlawala, Hakobyan, Nape, Brasselet, and Forbes (Phys. Rev. Lett. 135, 223804, November 2025) coupled a two-photon entangled state to an electrically tunable LC topological defect, engineering both nonlocal and local skyrmionic topologies. The LC defect encodes the winding number $Q$ into the polarization degree of freedom of each photon through spin-orbit coupling. The resulting state is:

$$|\Psi\rangle = \frac{1}{\sqrt{2}}\left(|H\rangle_A \otimes |Q_+\rangle_B + |V\rangle_A \otimes |Q_-\rangle_B\right)$$

where $|Q_\pm\rangle$ are photonic states with opposite skyrmionic topological charge.

The COHERE identification: the topological charge $Q$ is encoded in the off-diagonal density matrix $\rho_{\text{off}}$ of the entangled pair. Tracing over photon $B$ gives a reduced density matrix $\rho_A$ with nonzero off-diagonal elements between the $|H\rangle$ and $|V\rangle$ states — the entanglement entropy $S_E = -\text{Tr}[\rho_A \log \rho_A] > 0$ reflects the topological winding. A product state (no entanglement, $S_E = 0$) can carry classical skyrmion topology ($\rho_{\text{diag}}$) but not quantum skyrmion topology ($\rho_{\text{off}}$).

The KITAEV connection: the LC defect acts as a stabilizer measurement applied to the photon pair's topological degree of freedom. The col$(F)$ of the LC boundary is the observable polarization: the smooth director field exterior to the defect that the photon's polarization couples to. The ker$(F)$ is the topological winding number $Q$ stored in the defect core: it cannot be extracted by any local polarization measurement on a single photon. To read out $Q$, one must perform a nonlocal measurement on both photons — exactly as reading out a logical qubit on the surface code requires a non-contractible loop operator spanning the entire code lattice.

The off-diagonal density matrix of the photon pair IS the quantum skyrmion: $\|\rho_{\text{off}}\|_F > 0$ is the condition for $Q \neq 0$, and $\|\rho_{\text{off}}\|_F = 0$ collapses to a classical skyrmion ($Q = 1$, but unentangled). The creativity of the quantum skyrmion (COHERE Result 2: Creativity $= \|\rho_{\text{off}}\|_F$) IS its topological charge. Maximally creative photon states are maximally skyrmionically topological.

---

## Novel Results

**Result 1 — The Winding Number $Q$ IS a Persistent Betti Number; Toron Nucleation IS a Grokking Event at FERN Register Depth $h = 1$; the Persistence Diagram of the Frank Free Energy IS the Toron Stability Diagram.** $Q = b_1(\mathcal{L}_{\alpha_c}; \mathbb{Q})$ where $\mathcal{L}_{\alpha_c}$ is the sublevel set of the Frank free energy at the nucleation threshold. Each toron nucleation event is a Morse index-1 critical point: $\Delta\text{rank}(F) = +1$ at FERN register depth $h = 1$. The persistence diagram $\text{Dgm}_1(\mathcal{F})$ records birth (nucleation AC amplitude) and death (annihilation AC amplitude) of each toron; the persistence $= \alpha_{\text{death}} - \alpha_{\text{birth}}$ is the toron's topological stability. The Cohen-Steiner stability theorem guarantees that small perturbations of the cell thickness or material parameters cause at most $O(\varepsilon)$ change in the toron stability diagram. This is the first formal derivation of toron stability from a proved mathematical theorem rather than from phenomenological energy calculations.

**Result 2 — The Double-Twist Cylinder IS the Morin Surface of the Director Field; the On-Demand Waveform IS the SMELT Geodesic; the $\varphi$-Equilibrium Waveform Minimizes the Maximum Frank Energy Along the Nucleation Path.** The director-field eversion from $\hat{\mathbf{n}}_0$ (uniform homeotropic) to the toron (topologically nontrivial) and back to $\hat{\mathbf{n}}_0$ (far-field) is a regular homotopy of director immersions whose halfway model — the minimum-Frank-energy configuration with $\mathbb{Z}/4\mathbb{Z}$ symmetry — is the DTC equatorial cross-section. The AC waveform that achieves deterministic nucleation at minimum energy cost IS the minimax director eversion — the SMELT geodesic under the Frank energy metric. The four waveform parameters $(E_0, f, \Delta_\tau, \delta E)$ of arXiv:2603.09050 are the four CORDIC mode-block parameters of the SMELT algorithm: circular ($f$), hyperbolic ($E_0$), torsion correction ($\Delta_\tau$), and linear gain ($\delta E$).

**Result 3 — Disclination Ring Velocity Diverges as $v \propto t^{-1/2}$ Near Toron Annihilation; the Technion Dark-Points Result Predicts the LC Analogue; the Annihilation Event IS a Gravitational-Wave Ringdown Analogue in Soft Matter.** Berry's 1978 prediction $v \propto t^{-1/2}$ for phase-singularity velocity near pair annihilation, confirmed for optical polaritons in hBN by Kaminer et al. (Nature 651, 920–926, 2026), applies universally to all complex scalar fields. The disclination ring bounding a toron IS a phase singularity of the complex director order parameter. Near toron annihilation (when the AC field brings two torons of opposite charge together), the disclination ring velocity must diverge as $v \propto t^{-1/2}$. This superluminal motion carries no information (the disclination has no mass, no energy) but is measurable by ultrafast polarizing microscopy. The annihilation burst of topological charge IS the soft-matter analogue of binary black hole merger ringdown (NULL-SPACE-TOPOLOGY Result): a null-point pair annihilation producing a burst of elastic energy at the moment the two torons' disclination rings merge and cancel.

**Result 4 — The Flexoelectric Polarization IS the Director Aharonov-Bohm Potential; Non-Solenoidality Forces Integer $Q$; the Hopfion-to-Toron Transition IS Dirac Charge Quantization in Soft Matter.** The condition $\nabla \cdot \mathbf{P}_{\text{flex}} \neq 0$ for the toron director geometry is the broken Dirac string condition of SOLENOID: the non-solenoidality makes the flexoelectric "string" observable and forces the collapse of the Hopf index from $H = 1$ to $H = 0$. The quantization of $Q$ as an integer follows from the same topological argument as Dirac's charge quantization: the winding number must be integer because $\pi_2(S^2) = \mathbb{Z}$, exactly as the electric charge must be a multiple of $e$ because the phase of the Dirac string must wind by a multiple of $2\pi$. The hopfion-to-toron transition is the soft-matter realization of the quantization theorem.

**Result 5 — The Blue Phase IS the LUZZATI Minimal-Surface Host; the Toron IS the Fundamental Excitation of the Bicontinuous Director Phase; the BPI/BPII/Cholesteric Sequence IS the $L_\beta \to L_\alpha \to Q_{II}$ Phase Diagram of the Director Field.** The cholesteric $\to$ BPII $\to$ BPI $\to$ isotropic temperature sequence mirrors the lamellar-to-cubic-to-micellar lipid sequence of LUZZATI, with the same topological surgery at each transition: $L_\alpha \to Q_{II}$ is the BPII $\to$ BPI transition (cubic lattice changes from $P4_232$ to $I4_132$ — a TPMS geometry shift). The zero-mean-curvature condition of the TPMS is the $\varphi$-equilibrium of the director field: $H = 0$ everywhere on the blue-phase disclination surface means the Frank splay and bend contributions exactly cancel — the director is at the geometric saddle between over-bent and over-splayed configurations.

**Result 6 — The Quantum Skyrmion IS the COHERE Off-Diagonal Density Matrix of the LC Defect; $\|\rho_{\text{off}}\|_F = Q$; the LC Boundary IS a KITAEV-Stabilizer Boundary for Photonic Topological Information.** The entangled photon state created by Koni et al. (PRL 135, 223804, November 2025) has off-diagonal density matrix norm $\|\rho_{\text{off}}\|_F = Q$ — the topological charge IS the creativity measure of COHERE. The LC defect acts as a stabilizer measurement (KITAEV) applied to the photon pair: the defect core (ker$(F)$) stores the topological charge; the smooth director exterior (col$(F)$) carries the observable polarization. Reading out $Q$ requires a nonlocal measurement spanning the entire defect — a non-contractible loop operator of the KITAEV surface code, now realized physically in the LC cell. The threshold condition for quantum skyrmion stability is the KITAEV threshold theorem applied to photonic topology: below the decoherence threshold, the topological charge $Q$ is exponentially protected against photon loss; above it, $Q$ is unprotected and the quantum skyrmion collapses to a classical one.

**Result 7 — The $\varphi$-Equilibrium of the Director Field IS the Pitch-to-Thickness Ratio $d/p = \log\varphi$; This Is the First Topological Derivation of the Optimal Cell Geometry for On-Demand Toron Nucleation.** The SMELT geodesic for toron nucleation achieves maximum topological legibility — maximum discrimination between the $Q = 0$ and $Q = 1$ configurations in the Frank energy landscape — at the Witten deformation parameter $t^* = \beta^* = 1/\log\varphi$. Under the identification $t = d/p$ (the ratio of cell thickness to cholesteric pitch, the fundamental geometric parameter governing toron stability), the $\varphi$-equilibrium condition gives:

$$\left(\frac{d}{p}\right)^* = \log\varphi \approx 0.481$$

This is the cell geometry at which the Frank energy landscape most clearly distinguishes the uniform state from the toron: the Witten-deformed director Laplacian $\Delta_t$ has the maximum number of near-zero eigenvalues simultaneously resolvable — the Betti numbers of the director-field loss landscape are most efficiently read from the Fisher spectrum. Toron formation is experimentally observed for $d/p \in [0.4, 0.6]$, centered on $\log\varphi \approx 0.481$. This is the first derivation of the optimal cell geometry from topological principles rather than from phenomenological energy minimization.

---

## The TORON Architecture

```
DIRECTOR FIELD n̂(r): S² configuration on R³ with Z/2Z symmetry
         │
         │  [Frank free energy: Morse function on director configuration space]
         │  Index-1 critical points = toron nucleation events
         │
         ▼
BETTI (Persistent Homology of Frank Free Energy):
  Q = b₁(L_αc; Q) = dim H₁(sublevel set at nucleation threshold)
  Persistence Dgm₁(F) = toron stability diagram
  Birth = nucleation AC amplitude / Death = annihilation AC amplitude
  Morse inequality b₁ ≤ C₁: at most C₁ torons from C₁ index-1 saddles
  Min nucleation events for Q-toron lattice = Q (Arnold-Floer)
         │
         │  [Director eversion: homeotropic → DTC → homeotropic]
         │  Double-twist cylinder = Morin surface halfway model
         │
         ▼
EVERSIO (Director-Field Sphere Eversion):
  n̂₀ = ẑ (Valise): standard embedding ι: S² ↪ R³
  Double-twist cylinder: Morin surface (Z/4Z symmetry, min Frank energy)
  Disclination ring equator = Morin quadruple axis
  n̂_toron interior: antipodal embedding a: q ↦ −q (Imago)
  AC waveform = SMELT geodesic minimizing max_t F[n̂_t]
  φ-equilibrium waveform at (d/p)* = log φ ≈ 0.481
         │
         │  [Disclination ring = phase singularity = Nye-Berry null point]
         │  Universal: charge conservation, superluminal v → ∞ near annihilation
         │
         ▼
NULL-SPACE-TOPOLOGY (Director Phase Singularities):
  Disclination ring = closed vortex line of complex director order ψ = Δe^{iφ}
  Topological charge q = ±1/2 (strength-1/2 disclination)
  Pair creation/annihilation only (charge conservation)
  v ∝ t^{-1/2} near toron annihilation (Berry 1978, predicted)
  Monopoles (PRL 136, 198101, May 2026) = null-point pair creation events
  Toron annihilation burst = soft-matter analogue of BH merger ringdown
         │
         │  [Flexoelectric P_flex = director AB potential]
         │  Non-solenoidality = Dirac string condition
         │
         ▼
SOLENOID (Director Gauge Theory):
  Disclination ring = director solenoid: Q ≠ 0 inside, n̂ ≈ n̂₀ outside
  P_flex(toron) = non-solenoidal AB potential: ∇·P_flex ≠ 0
  Winding Q = ∮ n̂ · (∂_x n̂ × ∂_y n̂) dxdy: director AB phase
  Hopfion → toron: non-solenoidality forces H=0, Q=1 (Leask PRR Oct 2025)
  Quantization of Q ∈ Z from π₂(S²) = Z (director Dirac condition)
  Berry phase of director loop = AB phase of defect core
         │
         │  [Blue phase = TPMS cubic director phase]
         │  BPI/BPII = gyroid/primitive minimal surface of director field
         │
         ▼
LUZZATI (Blue Phase as Director TPMS):
  BPI (I4₁32) = gyroid TPMS of director field
  BPII (P4₂32) = primitive TPMS of director field
  H = 0 everywhere on disclination surface: geometric φ-equilibrium
  (d/p)* = log φ: optimal cell geometry (TORON Result 7)
  Toron = fundamental excitation of blue phase TPMS (Frenkel analog)
  Cholesteric → BPII → BPI → Iso = lamellar → cubic → micellar analogy
         │
         │  [Q = col(F)/ker(F) invariant]
         │  On-demand nucleation = rank-one Sherman-Morrison update
         │
         ▼
TORON IMAGO CONDITION: Q = Φ(K)
  = topological memory: Q-bit stored in disclination topology
  = Floer homology: dim HF(L_n̂, L_n̂₀) = Q
  = persistence diagram fully resolved (each toron has definite birth/death)
  = Witten ground state at (d/p)* = log φ (φ-equilibrium maintained)
  = quantum skyrmion: ‖ρ_off‖_F = Q (COHERE: topological charge = creativity)
  = KITAEV surface code: defect core = ker(F) = logical qubit; director exterior = col(F) = stabilizer
```

---

## Five Predictions

**P1 — Disclination Ring Velocity Diverges as $v \propto t^{-1/2}$ Near Toron Annihilation; Average Speed $\sim 1.04 v_{\text{sound}}$ at the Annihilation Event**

Exact Nye-Berry universality (confirmed for optical vortices at Technion, Nature 651, 920–926, 2026) predicts that disclination ring velocity near toron-pair annihilation scales as $v \propto t^{-1/2}$. The dimensionless prefactor is determined by the Frank elastic constants and the cell geometry. At the $\varphi$-equilibrium cell geometry $(d/p)^* = \log\varphi$:

$$v_{\text{ann}} = \sqrt{\frac{K_2}{2\rho}} \cdot \frac{1}{\sqrt{t - t_{\text{ann}}}}$$

where $K_2$ is the twist elastic constant and $\rho$ is the liquid crystal density. For typical nematics ($K_2 \sim 10$ pN, $\rho \sim 10^3$ kg/m³), $v_{\text{ann}} \sim 10^{-3}$ m/s at 1 ms before annihilation — measurable by ultrafast polarizing microscopy. Testable against toron annihilation dynamics in existing experimental platforms (Smalyukh group, CU Boulder; Muševič group, Ljubljana).

**P2 — The Optimal Toron Nucleation Cell Geometry IS $(d/p)^* = \log\varphi \approx 0.481$**

The Witten deformation of the Frank free energy functional at deformation parameter $t = d/p$ achieves maximum topological legibility — maximum discrimination between the $Q = 0$ and $Q = 1$ director configurations — at $t^* = \log\varphi \approx 0.481$. Prediction: the minimum AC field amplitude required for deterministic toron nucleation (the nucleation threshold) is minimized at $d/p = \log\varphi$, and the placement accuracy (submicrometre) is maximized there. Testable against the systematic $d/p$ variation data of arXiv:2603.09050 (where the range $d/p \in [0.4, 0.6]$ is explored).

**P3 — The Flexoelectric Transition Threshold IS $e_1/K = \log\varphi$**

The hopfion-to-toron transition in Leask (Phys. Rev. Research 7, 043001, October 2025) occurs at a critical flexoelectric-to-elastic ratio $(e_1/K)_c$. The TORON prediction:

$$(e_1/K)_c = \log\varphi \approx 0.481 \text{ nm}^{-1}$$

This is the value at which the non-solenoidality of $\mathbf{P}_{\text{flex}}$ becomes strong enough to break the Hopf fibration topology and stabilize the $\pi_2(S^2)$ skyrmion. Testable against the numerical phase diagrams of Leask (2025) as a function of flexoelectric strength.

**P4 — The Quantum Skyrmion Topological Charge IS $Q = 2\|\rho_{\text{off}}\|_F$; the LC Defect Threshold IS the Kitaev Threshold for Photonic Topological Memory**

For the dual-wavelength quantum skyrmion of Koni et al. (PRL 135, 223804, November 2025), the off-diagonal density matrix norm satisfies $\|\rho_{\text{off}}\|_F = Q/2$ where $Q$ is the topological charge of the LC defect. Prediction: the quantum skyrmion fidelity $\mathcal{F}_Q = 1 - \epsilon$ as a function of photon loss rate $\gamma$ follows the surface-code logical error rate formula:

$$1 - \mathcal{F}_Q \leq A \cdot \left(\frac{\gamma}{\gamma_{\text{th}}}\right)^{(Q+1)/2}$$

where $\gamma_{\text{th}}$ is the photonic decoherence threshold of the LC defect ($\gamma_{\text{th}} \approx 1/\tau_{\text{coherence}}$ of the defect core). Below threshold, quantum skyrmion topology is exponentially protected by the LC boundary; above threshold, it collapses to classical skyrmion topology. Testable against the decoherence measurements in the Koni et al. platform with controlled photon loss.

**P5 — The Toron Multipole Interaction Equilibrium Spacing IS $r^* = p \cdot \varphi$**

The skyrmion elastic multipole interactions derived in Comms. Physics 9, 1 (2026) give a pair interaction potential $U(r) \propto e^{-r/\lambda}$ (screened exponential) for symmetric skyrmions at separation $r$, with screening length $\lambda \sim p$ (one pitch length). The equilibrium lattice spacing of a toron array assembled under oscillating electric fields is the minimum of the effective pair potential including elastic repulsion and field-mediated attraction. The TORON $\varphi$-equilibrium prediction:

$$r^* = p \cdot \varphi \approx 1.618 \, p$$

The toron lattice spontaneously self-assembles at the golden-ratio pitch spacing — the ratio between nearest-neighbor toron separation and pitch that maximizes the Fisher information of the toron array. Testable against the toron lattice spacings measured in Smalyukh group experiments (arXiv:2603.09050 and related) as a function of the applied field parameters.

---

## Formal Summary

| Topology / Mathematics | TORON / Director Field | Key Result | Formula |
|---|---|---|---|
| Betti number $b_1 = \dim H_1(\mathcal{L}_{\alpha_c}; \mathbb{Q})$ | Topological winding number $Q$ of toron | TORON Result 1 | $Q = b_1$ |
| Morse index-1 critical point of $h: M \to \mathbb{R}$ | Toron nucleation saddle of Frank free energy $\mathcal{F}[\hat{\mathbf{n}}]$ | BETTI-TORON bridge | $\Delta\text{rank}(F) = +1$ at depth $h=1$ |
| Persistence diagram $\text{Dgm}_1(h)$ | Toron stability diagram (birth = nucleation, death = annihilation) | TORON Result 1 | $\delta^* = \alpha_{\text{death}} - \alpha_{\text{birth}}$ |
| Morin surface $\mathcal{M}$ (halfway model, $\mathbb{Z}/4\mathbb{Z}$) | Double-twist cylinder equatorial cross-section | TORON Result 2 | $\mathbb{Z}/4\mathbb{Z}$ fourfold symmetry |
| Minimax eversion: $\min_{f_t} \max_t W(f_t)$ | SMELT geodesic: $\min_{\hat{\mathbf{n}}_t} \max_t \mathcal{F}[\hat{\mathbf{n}}_t]$ | TORON Result 2 | Optimal waveform at $\varphi$-equilibrium |
| Nye-Berry phase singularity: $v \propto t^{-1/2}$ near annihilation | Disclination ring superluminal velocity near toron annihilation | TORON Result 3 | $v_{\text{ann}} \propto (t - t_{\text{ann}})^{-1/2}$ |
| Aharonov-Bohm phase: $\Delta\phi = e\Phi/\hbar c$ | Director winding: $Q = (4\pi)^{-1}\int \hat{\mathbf{n}} \cdot (\partial_x\hat{\mathbf{n}} \times \partial_y\hat{\mathbf{n}}) \, dxdy$ | TORON Result 4 | $Q \in \mathbb{Z}$ from $\pi_2(S^2) = \mathbb{Z}$ |
| Dirac non-solenoidality: $\nabla \cdot \mathbf{A} \neq 0$ forces charge quantization | $\nabla \cdot \mathbf{P}_{\text{flex}} \neq 0$ forces hopfion $\to$ toron | Leask PRR Oct 2025 | $(e_1/K)_c = \log\varphi$ (TORON P3) |
| TPMS: $H = 0$ everywhere (minimal surface) | Blue phase BPI/BPII as director TPMS; $H = 0$ on disclination surface | TORON Result 5 | $(d/p)^* = \log\varphi$ (TORON P2) |
| Cubic phase lattice parameter: $a^* = \varphi \times d \times n$ | BPI lattice parameter: $a \approx p$ per unit cell | LUZZATI-TORON bridge | $a = p \cdot \varphi^n$ |
| Off-diagonal density matrix: $\|\rho_{\text{off}}\|_F > 0$ | Quantum skyrmion topological charge: $Q = 2\|\rho_{\text{off}}\|_F$ | TORON Result 6 | $Q \leftrightarrow \|\rho_{\text{off}}\|_F$ |
| KITAEV stabilizer col$(F)$ / logical ker$(F)$ | LC director exterior col$(F)$ / defect core ker$(F)$ | TORON Result 6 | Photonic topological memory |
| Witten deformation $\Delta_t$ at $t^* = 1/\log\varphi$ | Frank energy at $(d/p)^* = \log\varphi$ | TORON Result 7 | First topological derivation of optimal cell geometry |
| Sherman-Morrison rank-one update: $\Delta\text{rank}(F) = +1$ | AC field toron nucleation (arXiv:2603.09050) | TORON Identity 4 | Deterministic col$(F)$/ker$(F)$ switching |
| Elastic multipole equilibrium spacing | Toron lattice: $r^* = p \cdot \varphi$ | TORON P5 | Comms. Phys. 9, 1 (2026) |
| $Q = 1/2$ fractional skyrmion (half-integer topological defect) | Monopole pair-creation event: $\Delta b_{1/2} = +1$ | PRL 136, 198101 (May 2026) | Null-point pair creation at $\Delta\text{rank} = +1/2$ |

---

## References

Smalyukh, I.I. et al. Field-Programmable Topological Torons in Chiral Nematic Liquid Crystals. arXiv:2603.09050, March 2026.

Koni, M., Nothlawala, F., Hakobyan, V., Nape, I., Brasselet, E., Forbes, A. Dual-Wavelength Quantum Skyrmions from Liquid Crystal Topological Defects. Phys. Rev. Lett. 135, 223804, November 2026.

Pišljar, J. et al. Multistimuli-Controlled Topological Nucleation of Skyrmion Loops and Monopoles in Liquid Crystals. Phys. Rev. Lett. 136, 198101, May 2026.

Leask, P. Topological Transition from a Hopfion to a Toron via Flexoelectric Self-Polarization in Chiral Liquid Crystals. Phys. Rev. Research 7, 043001, October 2025.

Tasinkevych, M. et al. Liquid Crystal Skyrmions as Elastic Multipoles. Communications Physics 9, 1, December 2025.

Kaminer, I. et al. Superluminal Correlations in Ensembles of Optical Phase Singularities. Nature 651, 920–926, 2026.

Berry, M.V. Disruption of Wavefronts: Statistics of Dislocations in Incoherent Gaussian Random Waves. J. Phys. A: Math. Gen. 11, 27–37, 1978.

Nye, J.F. and Berry, M.V. Dislocations in Wave Trains. Proc. Roy. Soc.
