

## Concentration Profiles, Diffusive Flux, and the Limiting Current

Mass transport to an electrode is most cleanly described by the concentration field of the electroactive solute in the solution adjacent to the surface. Consider a planar electrode with its surface located at ($x=0$), with the solution occupying ($x>0$). Let ($C_0(x,t)$) denote the concentration of species (0) as a function of position and time. Far from the electrode, the solution remains well mixed and the concentration approaches the bulk value  
$$
C_0(x,t)\xrightarrow[x\to\infty]{}; C_0^{*},  
$$
where ($C_0^{*}$) is the bulk (reservoir) concentration.

When the electrode reaction consumes (or produces) species (0), the interfacial concentration ($C_0(x=0,t)$) deviates from ($C_0^{*}$). A concentration gradient develops near the surface, and this gradient drives a diffusive flux. The resulting ($C_0(x,t)$) profile typically steepens and extends farther into solution as time progresses; under sustained forcing with convection present, the profile approaches a quasi-steady shape characterized by a finite boundary-layer thickness.

### Flux–current connection at the electrode

Let (J) denote the molar flux of species (0) normal to the electrode surface (units: (\mathrm{mol,cm^{-2},s^{-1}}) or (\mathrm{mol,m^{-2},s^{-1}})). The electrochemical current is proportional to the rate at which moles are consumed/produced at the interface. For an (n)-electron process, the current (i) (units: A) through electrode area (A) satisfies  
$$
i = n F A\, J,  
$$
or equivalently,  
$$
\frac{i}{n F A}=J,  
$$
where (F) is Faraday’s constant.

Diffusion relates flux to the concentration gradient via Fick’s first law. In one dimension,  
$$
J = -D_0\,\frac{\partial C_0}{\partial x},  
$$
with ($D_0$) the diffusion coefficient of species (0) (units: (\mathrm{cm^2,s^{-1}}) or ($\mathrm{m^2,s^{-1}}$)). Evaluated at the surface, this gives the interfacial transport condition that links measurable current to the local concentration slope.

### Derivation mode: diffusion-layer approximation for the flux

A widely used simplification is the diffusion-layer (film) approximation: the concentration changes primarily within a layer of thickness ($\delta$) adjacent to the electrode, and outside that layer the solution remains at ($C_0^{*}$). Within this picture, the near-surface gradient is approximated by a finite difference,  
$$
\left.\frac{\partial C_0}{\partial x}\right|_{x=0}\approx \frac{C_0(\delta,t)-C_0(0,t)}{\delta}\approx \frac{C_0^{*}-C_0(x=0,t)}{\delta}.  
$$

Using this approximation yields an explicit expression for the flux in terms of ($\delta$):  
$$
\begin{aligned}  
J  
&= -D_0\left.\frac{\partial C_0}{\partial x}\right|_{x=0} \\
&\approx -D_0\left(\frac{C_0^{*}-C_0(x=0,t)}{\delta}\right)\,(-1) \\
&= D_0\,\frac{C_0^{*}-C_0(x=0,t)}{\delta} \\
&\equiv m_0\Big(C_0^{*}-C_0(x=0,t)\Big),  
\end{aligned}  
$$
where the mass-transfer coefficient  
$$
m_0 \equiv \frac{D_0}{\delta}  
$$
has units of velocity (e.g., (\mathrm{cm,s^{-1}}) or ($\mathrm{m,s^{-1}}$)).

This form highlights the physical content: transport is driven by the “driving-force” concentration difference ($C_0^{*}-C_0(x=0,t)$), and the proportionality constant ($m_0$) compresses diffusion and hydrodynamic boundary-layer effects into a single parameter.

### Diffusion-layer thickness and approach to steady state

The diffusion-layer thickness ($\delta$) (units: length) represents the characteristic distance over which the concentration relaxes from its interfacial value back to the bulk value. In transient conditions dominated by diffusion, the region affected by the reaction expands with time. Under many practical experimental conditions, convection (natural or forced) eventually establishes a steady boundary layer, so that ($\delta$) becomes effectively time-independent and the concentration profile approaches a steady shape. In that steady regime, the concentration profile within the layer is often modeled as approximately linear between ($x=0$) and ($x=\delta$), consistent with the flux expression above.

### Limiting current

The limiting current arises when mass transport becomes the rate-determining step and the interfacial concentration of the reactant is driven as low as possible. In the most common idealization for a reactant being consumed at the electrode, the diffusion-limited condition corresponds to  
$$
C_0(x=0)\approx 0,  
$$
so the maximum sustainable flux is  
$$
J_{\text{lim}} = m_0\big(C_0^{*}-0\big)=m_0 C_0^{*}.  
$$

Converting flux to current gives the limiting current:  
$$
\begin{aligned}  
i_{\text{lim}}  
&= n F A\, J_{\text{lim}} \\
&= n F A\, m_0 C_0^{*} \\
&= n F A \left(\frac{D_0}{\delta}\right) C_0^{*}.  
\end{aligned}  
$$

This expression makes the experimentally important dependencies explicit: the limiting current increases with bulk concentration ($C_0^{*}$), electrode area (A), and diffusion coefficient ($D_0$), and decreases as the diffusion layer thickens (larger ($\delta$)).

### Parameter definitions (as used here)

(J) denotes the molar flux. ($\delta$) denotes the diffusion-layer thickness (length). ($D_0$) denotes the diffusion coefficient of species (0) (length($^2$)/time). ($m_0$) denotes the mass-transfer coefficient (length/time), defined by ($m_0=D_0/\delta$). The limiting current is the transport-controlled maximum current ($i_{\text{lim}}=nFA\,m_0 C_0^{*}$) under the condition ($C_0(x=0)\approx 0$).

If additional parts of the chapter introduce specific reaction stoichiometries, sign conventions (oxidation vs reduction), or time-dependent forms for ($\delta(t)$), those can be layered onto this framework without changing the core flux–current structure developed here.



> [!figure] figure 1
> ![[Pasted image 20260301021621.png]]




# Decomposing an Electrode Reaction into Transport and Charge Transfer

A one-electron redox couple may be represented schematically as  
$$
\mathrm{O} + e^- \rightleftharpoons \mathrm{R},  
$$
where ($\mathrm{O}$) denotes the oxidized form and ($\mathrm{R}$) denotes the reduced form.

In the formation of current from this redox couple, it is useful to separate the overall process into two conceptually distinct steps. The first step is **mass transport** (Step A), which supplies ($\mathrm{O}$) from the bulk solution to the vicinity of the electrode and removes ($\mathrm{R}$) away from the electrode region. The second step is **charge transfer** (Step B), which is the interfacial electron-transfer event converting ($\mathrm{O}$) to ($\mathrm{R}$) (or ($\mathrm{R}$) to ($\mathrm{O}$)) at the electrode surface.

Step A (mass transport) comprises three mechanisms: diffusion, migration, and convection. Diffusion refers to motion driven by concentration gradients, and in many practical situations it is the rate-limiting contribution to transport under conditions where migration is suppressed and convection is controlled. Migration refers to motion driven by an electric field acting on charged species. Convection refers to transport driven by fluid motion (forced or natural), which reshapes the near-electrode concentration field by continuously mixing solution.

Step B (charge transfer) is localized at the electrode–solution interface and accounts for the actual conversion between ($\mathrm{O}$) and ($\mathrm{R}$) through electron exchange with the electrode. In this two-step viewpoint, the observed current can be limited either by how quickly material reaches (and leaves) the interface (Step A) or by how quickly the interfacial electron-transfer event proceeds (Step B). The phrase _mass-transfer limited current_ refers to the regime in which Step A is the controlling limitation.




> [!figure] figure 2
> ![[Pasted image 20260301021721.png|500]]



## Steady-State Voltammetry and the Diffusion-Limited Plateau

In steady-state voltammetry, the current is recorded after the concentration field adjacent to the electrode has established a time-independent (or effectively time-independent) profile. The electrode potential is then varied through a sequence of fixed values, and the corresponding steady currents are paired with those potentials. Symbolically, one may think of sampling the response at a small set of potentials,  
$$
(E_1,i_1),\qquad (E_2,i_2),\qquad (E_3,i_3),  
$$
and then extending that sampling to generate the full current–potential curve (i(E)).

A characteristic outcome for a simple redox couple (\mathrm{O}+ne^- \rightleftharpoons \mathrm{R}) is an S-shaped (i)–(E) relationship that rises from a small current at weak driving force to a plateau at strong driving force. The plateau corresponds to the **diffusion-limited current**, i.e., the regime in which the interfacial reaction is fast enough that the overall rate is controlled by how quickly the reactant can be supplied to the surface by mass transport.

### Concentration profiles at selected potentials

Let ($C_O(x)$) denote the concentration of the oxidized form ($\mathrm{O}$) as a function of distance (x) normal to the electrode surface, with the electrode at ($x=0$). In the diffusion-layer approximation, the concentration relaxes from its surface value ($C_O(0)\equiv C_O(x=0)$) to the bulk value ($C_O^{*}$) over a characteristic thickness ($\delta$). A convenient idealization is a linear profile within the layer,  
$$
C_O(x)\approx C_O(0) + \big(C_O^{*}-C_O(0)\big)\frac{x}{\delta},\qquad 0\le x\le \delta,  
$$
with ($C_O(x)\approx C_O^{*}$) for ($x\gtrsim \delta$).

As the potential is shifted from a value above the formal potential to a value below it, the surface composition moves from “mostly oxidized” toward “mostly reduced.” This appears directly in the family of ($C_O(x)$) profiles:

- At ($E_1 = E^\circ + 0.12~\mathrm{V}$), the surface concentration ($C_O(0)$) remains close to ($C_O^{*}$), so the gradient ($\partial C_O/\partial x$) is small and the current is correspondingly small ($(i_1)$).
    
- At ($E_2 = E^\circ$), the surface concentration is intermediate, producing a larger gradient and a larger current ($(i_2)$).
    
- At ($E_3 = E^\circ - 0.12~\mathrm{V}$), the surface concentration is driven toward depletion, ($C_O(0)\to 0$), maximizing the gradient and producing the diffusion-limited current plateau ($(i_3\approx i_{\text{lim}})$).
    

The same “surface-value” notation applies to the reduced form: ($C_R(0)\equiv C_R(x=0)$) is the concentration of ($\mathrm{R}$) at the electrode surface.

### Interfacial Nernst relation at the surface

Under conditions where the interfacial electron transfer is sufficiently rapid to maintain local equilibrium between ($\mathrm{O}$) and ($\mathrm{R}$) at the surface, the electrode potential is linked to the **surface** concentration ratio by the Nernst equation written in base-10 logarithms:  
$$
E = E^\circ - \frac{0.059}{n}\,\log_{10}\!\left(\frac{C_R(x=0)}{C_O(x=0)}\right).  
\tag{1}  
$$

#### Derivation mode: ratio form implied by the Nernst expression

Starting from (1),  
$$
\begin{aligned}  
E &= E^\circ - \frac{0.059}{n}\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
E^\circ - E &= \frac{0.059}{n}\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
\frac{n}{0.059}(E^\circ - E) &= \log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
10^{\frac{n}{0.059}(E^\circ - E)} &= \frac{C_R(0)}{C_O(0)}.  
\end{aligned}  
$$

This makes the qualitative trend transparent: when the potential is shifted below ($E^\circ$) (so that ($E^\circ-E>0$)), the ratio ($C_R(0)/C_O(0)$) grows, meaning the surface becomes increasingly enriched in ($\mathrm{R}$) and depleted in ($\mathrm{O}$). In the strong-driving-force limit, the ratio becomes very large, which is consistent with ($C_O(0)\to 0$) and hence the emergence of diffusion-limited behavior.




# Connecting surface depletion to the diffusion-limited current

Because the flux of ($\mathrm{O}$) to the surface is set by the near-surface gradient, the diffusion-layer approximation gives  
$$
J_O \approx D_O\,\frac{C_O^{*}-C_O(0)}{\delta},  
$$
and the corresponding current is  
$$
i \approx n F A\, D_O\,\frac{C_O^{*}-C_O(0)}{\delta}.  
$$
When the potential is sufficiently below ($E^\circ$) that ($C_O(0)\approx 0$), the current reaches the plateau  
$$
i_{\text{lim}} \approx n F A\,\frac{D_O}{\delta}\,C_O^{*},  
$$
which is the diffusion-limited current indicated by the upper, nearly horizontal region of the steady-state (i)–(E) curve.



> [!figure] figure 3
> ![[Pasted image 20260301021908.png|500]]




> [!figure] figure 4
> ![[Pasted image 20260301021937.png|500]]





## Worked Example: Computing Interfacial Concentrations from the Nernst Relation

To make the link between potential and surface composition concrete, consider the reversible couple  
$$
\mathrm{O}+e^- \rightleftharpoons \mathrm{R},  
$$
with a bulk solution prepared such that  
$$
C_O^{*}=1~\mathrm{mM},\qquad C_R^{*}=0~\mathrm{mM},  
$$
and assume a one-electron transfer, ($n=1$). Let the electrode surface be at ($x=0$), so that the interfacial concentrations are ($C_O(0)\equiv C_O(x=0)$) and ($C_R(0)\equiv C_R(x=0)$).

Under Nernstian (rapid, locally equilibrated) charge transfer at the interface, the electrode potential is related to the **surface** concentration ratio by  
$$
E = E^\circ - \frac{0.059}{n}\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right).  
\tag{1}  
$$

A second relation is needed to determine the two unknowns ($C_O(0)$) and ($C_R(0)$). For this illustrative calculation, the total concentration of the redox couple at the interface is taken to match the bulk total:  
$$
C_O(0)+C_R(0)=C_O^{*}+C_R^{*}=1~\mathrm{mM}.  
\tag{2}  
$$
(Equation (2) is the standard “conservation of the couple” statement used in simple reversible steady-state treatments.)

With (1) and (2), the surface concentrations can be computed at selected potentials.

### Case A: ($E=E^\circ$)

**Derivation mode**  
$$
\begin{aligned}  
E &= E^\circ - 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
E^\circ &= E^\circ - 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
0 &= -0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
0 &= \log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
10^{0} &= \frac{C_R(0)}{C_O(0)} \\
1 &= \frac{C_R(0)}{C_O(0)} \\
C_R(0) &= C_O(0).  
\end{aligned}  
$$

Combine with (2):  
$$
\begin{aligned}  
C_O(0)+C_R(0) &= 1~\mathrm{mM} \\
C_O(0)+C_O(0) &= 1~\mathrm{mM} \\
2\,C_O(0) &= 1~\mathrm{mM} \\
C_O(0) &= \frac{1}{2}~\mathrm{mM} = 0.5~\mathrm{mM}, \\
C_R(0) &= 0.5~\mathrm{mM}.  
\end{aligned}  
$$

### Case B: ($E=E^\circ-0.12~\mathrm{V}$)

**Derivation mode**  
$$
\begin{aligned}  
E &= E^\circ - 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
E^\circ - 0.12 &= E^\circ - 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
-0.12 &= -0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
0.12 &= 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
\frac{0.12}{0.059} &= \log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
\frac{0.12}{0.059} &= \frac{120}{59} \\
\frac{120}{59} &= 2 + \frac{2}{59} \\
\frac{2}{59} &= 0.033898305\ldots \\
\frac{120}{59} &= 2.033898305\ldots \\
10^{2.033898305\ldots} &= \frac{C_R(0)}{C_O(0)}.  
\end{aligned}  
$$

Define the ratio  
$$
\beta \equiv \frac{C_R(0)}{C_O(0)} = 10^{2.033898305\ldots}.  
$$
Compute ($\beta$) to a convenient approximation:  
$$
\begin{aligned}  
\beta &= 10^{2}\times 10^{0.033898305\ldots} \\
&= 100\times 10^{0.033898305\ldots} \\
10^{0.033898305\ldots} &= \exp\!\big((0.033898305\ldots)\ln 10\big) \\
&= \exp\!\big((0.033898305\ldots)\times 2.302585093\ldots\big) \\
&= \exp(0.07806\ldots) \\
&= 1.0811\ldots \\
\beta &= 100\times 1.0811\ldots \\
\beta &= 108.11\ldots  
\end{aligned}  
$$
so ($\beta \approx 1.08\times 10^{2}$) (often rounded to ($\sim 10^2$) for quick back-of-the-envelope work).

Now use (2) with ($C_R(0)=\beta C_O(0)$):  
$$
\begin{aligned}  
C_O(0)+C_R(0) &= 1~\mathrm{mM} \\
C_O(0)+\beta C_O(0) &= 1~\mathrm{mM} \\
(1+\beta)\,C_O(0) &= 1~\mathrm{mM} \\
C_O(0) &= \frac{1}{1+\beta}~\mathrm{mM}.  
\end{aligned}  
$$

Substitute ($\beta=108.11\ldots$):  
$$
\begin{aligned}  
C_O(0) &= \frac{1}{1+108.11\ldots}~\mathrm{mM} \\
&= \frac{1}{109.11\ldots}~\mathrm{mM} \\
&= 0.009166\ldots~\mathrm{mM}, \\
C_R(0) &= 1~\mathrm{mM} - C_O(0) \\
&= 1~\mathrm{mM} - 0.009166\ldots~\mathrm{mM} \\
&= 0.990834\ldots~\mathrm{mM}.  
\end{aligned}  
$$

Thus, at ($E=E^\circ-0.12~\mathrm{V}$), the surface is overwhelmingly in the reduced form: ($C_R(0)\approx 0.991~\mathrm{mM}$) and ($C_O(0)\approx 9.17\times 10^{-3}~\mathrm{mM}$).

### Case C: ($E=E^\circ+0.12~\mathrm{V}$)

This case mirrors Case B but with the opposite sign in the exponent.

**Derivation mode**  
$$
\begin{aligned}  
E &= E^\circ - 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
E^\circ + 0.12 &= E^\circ - 0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
0.12 &= -0.059\,\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
-\frac{0.12}{0.059} &= \log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right) \\
10^{-\frac{0.12}{0.059}} &= \frac{C_R(0)}{C_O(0)}.  
\end{aligned}  
$$

Using ($\frac{0.12}{0.059}=2.033898305\ldots$) from above,  
$$
\beta \equiv \frac{C_R(0)}{C_O(0)} = 10^{-2.033898305\ldots} = \frac{1}{10^{2.033898305\ldots}} = \frac{1}{108.11\ldots}=0.009248\ldots  
$$

Apply (2) again:  
$$
\begin{aligned}  
C_O(0)+\beta C_O(0) &= 1~\mathrm{mM} \\
(1+\beta)\,C_O(0) &= 1~\mathrm{mM} \\
C_O(0) &= \frac{1}{1+\beta}~\mathrm{mM} \\
&= \frac{1}{1+0.009248\ldots}~\mathrm{mM} \\
&= \frac{1}{1.009248\ldots}~\mathrm{mM} \\
&= 0.990834\ldots~\mathrm{mM}, \\
C_R(0) &= 1~\mathrm{mM} - C_O(0) \\
&= 1~\mathrm{mM} - 0.990834\ldots~\mathrm{mM} \\
&= 0.009166\ldots~\mathrm{mM}.  
\end{aligned}  
$$

At ($E=E^\circ+0.12~\mathrm{V}$), the surface is overwhelmingly in the oxidized form: ($C_O(0)\approx 0.991~\mathrm{mM}$) and ($C_R(0)\approx 9.17\times 10^{-3}~\mathrm{mM}$).

---

These three points summarize the essential Nernstian picture for a one-electron couple: moving the potential by roughly ($\pm 0.12~\mathrm{V}$) relative to ($E^\circ$) shifts the surface ratio ($C_R(0)/C_O(0)$) by about two orders of magnitude, which is exactly the kind of surface depletion/enrichment that drives the transition from small current to the diffusion-limited plateau in the steady-state (i)–(E) curve.




# Establishment of Steady State: Concentration Profiles and Current Response

Consider the reduction  
$$
\mathrm{O}+n e^- \rightleftharpoons \mathrm{R},  
$$
with bulk oxidant concentration ($C_O^{*}$) and an electrode surface located at ($x=0$). Immediately after an experiment begins (or immediately after a change in driving force), the solution is typically uniform in composition near the electrode, so that the concentration field starts from an essentially flat profile,  
$$
C_O(x,0)\approx C_O^{*}.  
$$
Once net reaction proceeds, the interfacial value ($C_O(0,t)$) departs from ($C_O^{*}$), and a concentration gradient develops in the adjacent solution. As time advances, the region of perturbed concentration spreads outward and the profile evolves toward whatever long-time transport regime the experiment enforces. The key geometric fact is that the **slope** of the near-surface concentration profile controls the diffusive flux and therefore the current: a steeper concentration gradient implies a larger flux, and hence a larger current.

This connection is summarized by Fick’s law and the flux–current relation,  
$$
J_O(0,t)=-D_O\left.\frac{\partial C_O}{\partial x}\right|_{x=0},  
\qquad  
i(t)=n F A\,J_O(0,t),  
$$
so that, in magnitude, the current scales directly with the interfacial concentration gradient.

## Transient Diffusion Versus a True Steady State

In an unstirred planar system, diffusion is initially effective at supplying reactant, but the diffusion layer thickens as the perturbation penetrates farther into solution. As the diffusion length scale grows, the concentration gradient at the surface diminishes, so the diffusion-controlled current decreases with time. In the long-time limit of purely planar diffusion, the gradient becomes progressively shallower and the current tends toward zero.

By contrast, a **steady state** is characterized by a time-independent concentration profile near the electrode. In that case the surface gradient becomes time-independent, and the current reaches a constant value rather than decaying. A practical steady state therefore requires a mechanism that prevents indefinite growth of the diffusion layer—either through electrode geometry that produces convergent diffusion or through convection that continually refreshes solution near the surface.

## Electrode Configurations That Produce Diffusion Steady State

Certain electrode geometries naturally promote a steady diffusive flux because diffusion is not strictly one-dimensional. Two common examples are:

A spherical mercury drop electrode, where diffusion is radially convergent toward a finite object. The radial geometry can maintain a persistent concentration gradient at the surface, allowing the diffusive flux (and hence current) to approach a constant value.

A microelectrode disk (e.g., on the order of micrometers in size), where diffusion becomes hemispherical (or quasi-radial) at sufficiently long times. The spreading of diffusion lines in multiple dimensions stabilizes the near-surface gradient, again producing a steady current.

In both cases, the hallmark of diffusion steady state is that the concentration profile ($C_O(x,t)$) evolves from the initially flat profile toward a fixed, time-independent shape. Once that shape is established, the flux no longer changes with time.

## Convection-Controlled Steady State

Steady state can also be imposed hydrodynamically. A rotating disk electrode establishes a well-defined convective boundary layer adjacent to the surface, continuously bringing fresh solution toward the electrode and carrying product away. Similarly, thin-layer flow configurations maintain a controlled, continuously renewed near-electrode environment. In these convective steady-state systems, the concentration profile becomes time-independent because fluid motion sets a fixed transport length scale, rather than allowing the diffusion layer to grow without bound.

## The Diffusion-Limited Condition and the (i)–(E) Curve

As the electrode potential is driven in the cathodic direction (more negative for a reduction), the surface equilibrium shifts to favor ($\mathrm{R}$) and deplete ($\mathrm{O}$) at the interface. Under Nernstian interfacial behavior, the surface concentrations satisfy  
$$
E = E^\circ - \frac{0.059}{n}\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right).  
$$
At ($E=E^\circ$), the surface ratio is unity, ($C_R(0)=C_O(0)$); in the common case where the total concentration of the couple near the interface equals the bulk total, this corresponds to ($C_O(0)=\tfrac{1}{2}C_O^{*}$). Driving (E) more negative increases ($C_R(0)/C_O(0)$), pushing ($C_O(0)$) downward.

Transport then sets the current through the gradient required to sustain the interfacial consumption of ($\mathrm{O}$). As ($C_O(0)$) decreases, the difference ($C_O^{*}-C_O(0)$) increases, steepening the concentration gradient and increasing the flux. Eventually, in the strongly driven regime,  
$$
C_O(0)\approx 0,  
$$
and the system reaches the diffusion-limited condition: the concentration profile cannot steepen further because the reactant is effectively depleted at the surface. The current therefore approaches a plateau, the diffusion-limited current, and the steady-state (i)–(E) curve takes on the characteristic sigmoidal form that rises with increasing cathodic driving force and then levels off in the diffusion-limited region.

In summary, a steady diffusion-limited plateau requires not only a sufficiently strong thermodynamic driving force (to drive ($C_O(0)$) toward depletion) but also an experimental configuration that supports a time-independent concentration gradient—either by appropriate electrode geometry (microelectrodes, spherical electrodes) or by controlled convection (rotating disk, flow cells).


> [!figure] figure 5
> ![[Pasted image 20260301023716.png|700]]



> [!figure] figure 6
> ![[Pasted image 20260301023750.png]]


> [!figure] figure 7
> ![[Pasted image 20260301023849.png]]



> [!figure] figure 8
> ![[Pasted image 20260301023917.png|600]]





> [!figure] figure 9
> ![[Pasted image 20260301030500.png|700]]




> [!figure] figure 10
> ![[Pasted image 20260301030540.png|700]]



#  Transport Relations for ($\mathrm{O}$) and ($\mathrm{R}$) and the Steady-State Wave Equation

Consider the reduction  
$$
\mathrm{O}+n e^- \rightleftharpoons \mathrm{R},  
$$
at an electrode located at ($x=0$), with bulk concentrations ($C_O^{*}$) and ($C_R^{*}$). At steady state, mass transport establishes time-independent concentration profiles ($C_O(x)$) and ($C_R(x)$) adjacent to the surface. The steady current is determined by the interfacial fluxes, evaluated at ($x=0$), through  
$$
i = n F A\,J(x=0),  
$$
where (J) is the molar flux normal to the surface.

A convenient description of steady transport uses a diffusion-layer thickness ($\delta$) and a mass-transfer coefficient (m). For species ($\mathrm{O}$), the steady flux toward the electrode may be written in the “film” form  
$$
J_O = m_O\big(C_O^{*}-C_O(0)\big),  
\qquad  
m_O \equiv \frac{D_O}{\delta},  
$$
which is equivalent to the linear-gradient approximation to Fick’s law. The corresponding cathodic current is therefore proportional to the depletion of ($\mathrm{O}$) at the surface.

### Cathodic limiting current and the meaning of ($i_{\ell}^{c}$)

In the strongly driven cathodic regime, the surface is driven toward reactant depletion:  
$$
C_O(0)\approx 0.  
$$
In that diffusion-limited regime the flux reaches its maximum value,  
$$
J_{O,\ell} = m_O C_O^{*},  
$$
and the associated **cathodic limiting current** is  
$$
i_{\ell}^{c} = n F A\, m_O C_O^{*}.  
$$
Here the superscript (c) indicates cathodic (reduction) current and the subscript ($\ell$) indicates limiting.

### Derivation mode: expressing ($C_O(0)$) in terms of (i) and ($i_{\ell}^{c}$)

Start from the transport expression for the current carried by consumption of ($\mathrm{O}$):  
$$
i = n F A\,J_O = n F A\,m_O\big(C_O^{*}-C_O(0)\big).  
$$

Use the definition of ($i_{\ell}^{c}$):  
$$
i_{\ell}^{c} = n F A\,m_O C_O^{*}.  
$$

Then  
$$
\begin{aligned}  
i &= n F A\,m_O\big(C_O^{*}-C_O(0)\big) \\
&= n F A\,m_O C_O^{*} - n F A\,m_O C_O(0) \\
&= i_{\ell}^{c} - n F A\,m_O C_O(0) \\
n F A\,m_O C_O(0) &= i_{\ell}^{c} - i \\
C_O(0) &= \frac{i_{\ell}^{c}-i}{n F A\,m_O}.  
\end{aligned}  
\tag{2}  
$$

Equation (2) makes the steady-state meaning of the plateau transparent: as ($i\to i_{\ell}^{c}$), the interfacial reactant concentration ($C_O(0)\to 0$).

### Product-side transport and ($C_R(0)$)

An analogous transport form may be written for the reduced product ($\mathrm{R}$). In steady state, the flux of ($\mathrm{R}$) away from the electrode is proportional to its surface enrichment above bulk:  
$$
J_R = m_R\big(C_R(0)-C_R^{*}\big).  
$$
The same current must flow through the interfacial reaction, so the steady current may also be expressed as  
$$
i = n F A\,J_R = n F A\,m_R\big(C_R(0)-C_R^{*}\big).  
$$

In the common illustrative case where the bulk initially contains no ($\mathrm{R}$),  
$$
C_R^{*}=0,  
$$
the expression simplifies to  
$$
i = n F A\,m_R C_R(0),  
$$
so that

**Derivation mode**  
$$
\begin{aligned}  
i &= n F A\,m_R C_R(0) \\
C_R(0) &= \frac{i}{n F A\,m_R}.  
\end{aligned}  
\tag{3}  
$$

### Combining transport with the Nernst condition at the surface

When the interfacial electron transfer is reversible (Nernstian), the electrode potential is tied to the **surface** ratio ($C_R(0)/C_O(0)$):  
$$
E = E^\circ - \frac{0.059}{n}\log_{10}\!\left(\frac{C_R(0)}{C_O(0)}\right)  
= E^\circ + \frac{0.059}{n}\log_{10}\!\left(\frac{C_O(0)}{C_R(0)}\right).  
\tag{1}  
$$

Substitute the transport expressions (2)–(3) into (1):

**Derivation mode**  
$$
\begin{aligned}  
E  
&= E^\circ + \frac{0.059}{n}\log_{10}\!\left(\frac{C_O(0)}{C_R(0)}\right) \\
&= E^\circ + \frac{0.059}{n}\log_{10}\!\left(  
\frac{\dfrac{i_{\ell}^{c}-i}{n F A\,m_O}}{\dfrac{i}{n F A\,m_R}}  
\right) \\
&= E^\circ + \frac{0.059}{n}\log_{10}\!\left(  
\frac{i_{\ell}^{c}-i}{n F A\,m_O}\cdot\frac{n F A\,m_R}{i}  
\right) \\
&= E^\circ + \frac{0.059}{n}\log_{10}\!\left(  
\frac{m_R}{m_O}\cdot\frac{i_{\ell}^{c}-i}{i}  
\right) \\
&= E^\circ + \frac{0.059}{n}\left[  
\log_{10}\!\left(\frac{m_R}{m_O}\right)  
+  
\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right)  
\right].  
\end{aligned}  
\tag{4}  
$$

Equation (4) is the steady-state current–potential relationship implied by (i) Nernstian surface equilibrium and (ii) linear mass-transfer laws for both ($\mathrm{O}$) and ($\mathrm{R}$). It also encodes the plateau behavior directly: as the potential is driven more negative for a reduction, (i) increases and approaches ($i_{\ell}^{c}$), forcing the ratio ($(i_{\ell}^{c}-i)/i$) toward zero and thereby pushing ($C_O(0)$) toward depletion.



> [!figure] figure 11
> ![[Pasted image 20260301030828.png|600]]



> [!figure] figure 12
> ![[Pasted image 20260301030913.png]]




#  The Half-Wave Potential ($E_{1/2}$) and Its Use in Steady-State Waves

A steady-state voltammetric wave for the reduction ($\mathrm{O}+n e^- \rightleftharpoons \mathrm{R}$) rises from near-zero current to a diffusion-limited plateau ($i_{\ell}^{c}$). A particularly important reference point on this sigmoidal curve is the **half-wave potential**, denoted ($E_{1/2}$). By definition, ($E_{1/2}$) is the potential at which the current has reached one-half of its diffusion-limited value:  
$$
i(E_{1/2})=\frac{1}{2},i_{\ell}^{c}.  
$$
Because the definition is tied to the limiting current, ($E_{1/2}$) is read directly from the wave without requiring extrapolation to infinite driving force.

## Derivation mode: evaluating (E) at ($i=\tfrac{1}{2}i_{\ell}^{c}$)

From the steady-state transport–Nernst combination derived previously,  
$$
E  
= E^\circ + \frac{0.059}{n}\left[  
\log_{10}\!\left(\frac{m_R}{m_O}\right)  
+  
\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right)  
\right].  
\tag{1}  
$$

At the half-wave point ($i=\tfrac{1}{2}i_{\ell}^{c}$), the current ratio becomes  
$$
\begin{aligned}  
\frac{i_{\ell}^{c}-i}{i}  
&=\frac{i_{\ell}^{c}-\tfrac{1}{2}i_{\ell}^{c}}{\tfrac{1}{2}i_{\ell}^{c}}\\
&=\frac{\tfrac{1}{2}i_{\ell}^{c}}{\tfrac{1}{2}i_{\ell}^{c}}\\
&=1.  
\end{aligned}  
$$
Therefore  
$$
\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right)=\log_{10}(1)=0,  
$$
and (1) reduces to  
$$
\begin{aligned}  
E_{1/2}  
&= E^\circ + \frac{0.059}{n}\log_{10}\!\left(\frac{m_R}{m_O}\right).  
\end{aligned}  
\tag{2}  
$$

Equation (2) shows why ($E_{1/2}$) is so useful: the “current-dependent” logarithmic term vanishes exactly at half-height, leaving only a constant offset from ($E^\circ$) that depends on the relative mass-transfer coefficients of ($\mathrm{R}$) and ($\mathrm{O}$). When transport is symmetric for oxidized and reduced forms (for example, when ($m_R=m_O$)), the offset disappears and ($E_{1/2}=E^\circ$).

## Writing the wave in a compact “half-wave” form

Starting again from (1), substitute (2) to eliminate ($E^\circ + \frac{0.059}{n}\log_{10}(m_R/m_O)$) in favor of ($E_{1/2}$). This gives the standard steady-state wave equation:

**Derivation mode**  
$$
\begin{aligned}  
E  
&= E^\circ + \frac{0.059}{n}\log_{10}\!\left(\frac{m_R}{m_O}\right)

- \frac{0.059}{n}\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right) \\
    &= E_{1/2} + \frac{0.059}{n}\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right).  
    \end{aligned}  
    \tag{3}  
$$
    

Equation (3) is the most common working form for interpreting a steady-state sigmoidal wave: the potential is referenced to ($E_{1/2}$), and the entire current dependence enters only through the dimensionless ratio ($(i_{\ell}^{c}-i)/i$).

## Linearization and the diagnostic slope

Equation (3) can be rearranged to yield a straight-line relationship suitable for analysis. Solving (3) for the logarithm,

**Derivation mode**  
$$
\begin{aligned}  
E - E_{1/2}  
&= \frac{0.059}{n}\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right) \\
\log_{10}\!\left(\frac{i_{\ell}^{c}-i}{i}\right)  
&= \frac{n}{0.059}(E - E_{1/2}).  
\end{aligned}  
\tag{4}  
$$

Thus, a plot of ($\log_{10}\!\big((i_{\ell}^{c}-i)/i\big)$) versus (E) is linear, with slope  
$$
\text{slope}=\frac{n}{0.059},  
$$
and an intercept corresponding to ($-\frac{n}{0.059}E_{1/2}$) when written in the usual (y=mx+b) form. In practice, the linearization is implemented by tabulating measured pairs ((E,i)), computing ($(i_{\ell}^{c}-i)/i$) from the limiting plateau, taking the base-10 logarithm, and checking that the resulting line has the expected slope. This provides a direct diagnostic of the electron number (n) within the assumptions of a reversible steady-state wave.

Finally, the conceptual importance of ($E_{1/2}$) is that it replaces ($E^\circ$) as the experimentally accessible reference potential for the wave: the midpoint of the diffusion-limited rise is measurable, and it anchors both the sigmoidal representation (i(E)) and the linearized representation in (4).





> [!figure] figure 13
> ![[Pasted image 20260301031012.png|600]]





> [!figure] figure 14
> ![[Pasted image 20260301031104.png|600]]
