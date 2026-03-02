

In most real-world experiments, the speed of your reaction is not limited by how fast the electrode can work, but by how fast the solution can deliver reactants to the surface. In this chapter, we will focus on the diffusion layer. By understanding the the movement of bulk species, we can describe the steady state: a condition where the rate of supply perfectly matches the rate of consumption. This balance manifests as the plateau in a voltammogram, a signature that the system has reached its physical speed limit.

# Electron-Transfer Reactions at Electrode Interfaces

Electrode reactions are often classified by whether the electron transfer can occur to a solvated species without forming (or breaking) a specific chemical bond to the electrode surface. This distinction—**outer-sphere** versus **inner-sphere** electron transfer—controls how strongly the observed thermodynamics and kinetics depend on the electrode material (e.g., Pt, Au, carbon).

### Outer-sphere electron transfer: thermodynamics largely independent of electrode material

In an **outer-sphere** reaction, the redox species in solution remains separated from the electrode by its solvation shell (and any specifically adsorbed layer). Electron transfer occurs “through” this interfacial region without the reactant forming a surface bond. Because the electrode does not participate as a chemical reactant, the equilibrium potential is set by the solution redox couple itself and is therefore the same on chemically inert conductors such as **Pt** and **Au** (i.e., the same ($E^\circ$) for a given couple).

A convenient generic representation is  
$$
\mathrm{O}+n e^- \rightleftharpoons \mathrm{R},  
$$
where ($\mathrm{O}$) is the oxidized form and ($\mathrm{R}$) is the reduced form.

**Derivation Mode (Nernst form for an outer-sphere couple).**  
At constant (T) and (p), the reaction Gibbs energy satisfies  
$$
\begin{aligned}  
\Delta G  
&= \Delta G^\circ + RT\ln Q \\
&= \Delta G^\circ + RT\ln\!\left(\frac{a_{\mathrm{R}}}{a_{\mathrm{O}}}\right),  
\end{aligned}  
$$
and the electrical work for transferring (n) electrons across a potential difference (E) satisfies  
$$
\Delta G = -nF E.  
$$
Combining and solving for (E),  
$$
\begin{aligned}  
-nF E  
&= \Delta G^\circ + RT\ln\!\left(\frac{a_{\mathrm{R}}}{a_{\mathrm{O}}}\right) \\
E  
&= -\frac{\Delta G^\circ}{nF}-\frac{RT}{nF}\ln\!\left(\frac{a_{\mathrm{R}}}{a_{\mathrm{O}}}\right) \\
E  
&= E^\circ -\frac{RT}{nF}\ln\!\left(\frac{a_{\mathrm{R}}}{a_{\mathrm{O}}}\right),  
\end{aligned}  
$$
where ($E^\circ \equiv -\Delta G^\circ/(nF)$). In this outer-sphere setting, ($E^\circ$) is a property of the ($\mathrm{O}/\mathrm{R}$) couple (at the stated standard state) rather than a property of the electrode material, consistent with observing the _same_ ($E^\circ$) on Pt and Au.

This does not imply that all electrodes give identical current–potential behavior for outer-sphere couples: kinetics can still vary through differences in interfacial structure, electronic density of states, surface cleanliness, and other factors. The key point is that the _equilibrium_ potential for ($\mathrm{O}/\mathrm{R}$) is not set by forming a distinct surface chemical intermediate.

### Inner-sphere electron transfer: surface chemistry makes the reaction electrode-dependent

In an **inner-sphere** reaction, electron transfer is coupled to a specific interaction with the electrode—most commonly adsorption—so that a surface-bound intermediate appears in the reaction pathway. Because adsorption energetics (and the availability/nature of surface sites) depend strongly on the electrode material, the effective thermodynamics associated with the interfacial step can differ between materials such as **carbon** and **Pt**, leading to **different apparent ($E^\circ$)** for the surface-coupled process.

A canonical example is hydrogen evolution/oxidation, which overall can be written as  
$$
2\mathrm{H}^+ + 2e^- \rightleftharpoons \mathrm{H}_2,  
$$
but which, on many electrodes, proceeds through an adsorbed hydrogen intermediate often denoted ($\mathrm{H}_{\mathrm{ads}}$) (or ($\mathrm{H}^\ast$)).

A minimal inner-sphere picture introduces a surface site ($\ast$) and an adsorption/electron-transfer step such as  
$$
\mathrm{H}^+ + e^- + \ast \rightleftharpoons \mathrm{H}_{\mathrm{ads}}.  
$$
Subsequent chemistry (e.g., combination or electrochemical desorption) produces ($\mathrm{H}_2$), while regenerating sites. The essential feature is that ($\mathrm{H}_{\mathrm{ads}}$) is a **surface species**, and its free energy depends on the electrode material.

**Derivation Mode (why the interfacial “standard potential” can become material-dependent).**  
For the surface-coupled step  
$$
\mathrm{H}^+ + e^- + \ast \rightleftharpoons \mathrm{H}_{\mathrm{ads}},  
$$
a standard reaction free energy can be written schematically as  
$$
\begin{aligned}  
\Delta G^\circ_{\text{surf}}  
&= \mu^\circ_{\mathrm{H_{ads}}}-\mu^\circ_{\mathrm{H^+}}-\mu^\circ_{e^-}-\mu^\circ_{\ast}.  
\end{aligned}  
$$
The associated standard potential for this _surface redox step_ is  
$$
\begin{aligned}  
E^\circ_{\text{surf}}  
&= -\frac{\Delta G^\circ_{\text{surf}}}{F}.  
\end{aligned}  
$$
Because ($\mu^\circ_{\mathrm{H_{ads}}}$) and ($\mu^\circ_{\ast}$) encode adsorption energetics and site properties, they vary with electrode material (e.g., Pt versus C), and therefore  
$$
E^\circ_{\text{surf}}(\text{Pt}) \neq E^\circ_{\text{surf}}(\text{C})  
$$
in general. This is the sense in which an inner-sphere process can exhibit a **material-dependent** ($E^\circ$): the electrode is part of the chemistry through the surface intermediate.

In contrast, outer-sphere couples lack such a surface chemical intermediate, so the standard potential is not “re-written” in terms that include electrode-specific surface free energies. This outer-sphere/inner-sphere distinction is one of the most practical ways to anticipate when changing the electrode material should leave the equilibrium potential essentially unchanged (outer-sphere) versus when it can shift the apparent thermodynamics and profoundly alter the interfacial behavior through adsorption and catalysis (inner-sphere).


> [!figure] figure 1
> ![[Pasted image 20260301041039.png|500]]




> [!figure] figure 2
> ![[Pasted image 20260301041125.png|500]]







# Reversibility in Electrochemical Systems

Reversibility in electrochemistry is used in at least two distinct senses. One sense concerns whether the **electron-transfer step** at the electrode can maintain interfacial equilibrium on the experimental time scale. The other concerns whether the **chemical identity** of the electro-generated species is preserved long enough for it to be converted back during the reverse part of an experiment. These are conveniently separated into **electrochemical reversibility** and **chemical reversibility**.

### Electrochemical reversibility

Electrochemical reversibility refers to the electron-transfer step itself. A redox couple is electrochemically reversible when charge transfer at the electrode is sufficiently fast that the interfacial composition satisfies the Nernst relation essentially at all times during the measurement. In that limit, the potential controls the ratio of oxidized and reduced forms at the interface, and the observed response is governed primarily by transport (diffusion, migration, convection) rather than by sluggish interfacial kinetics.

This notion is independent of whether the reduced (or oxidized) product remains chemically intact after it is formed. It is therefore possible for a process to be electrochemically reversible (fast electron transfer) but chemically irreversible (the product reacts away in solution).

### Chemical reversibility

Chemical reversibility concerns the fate of the species produced by electron transfer. A chemically reversible process is one in which the electro-generated species does not undergo a competing chemical transformation on the experimental time scale, so that reversing the driving force can regenerate the original species. In a generic chemical reaction written as  
$$
\mathrm{A}+\mathrm{B}\rightleftharpoons \mathrm{C}+\mathrm{D},  
$$
chemical reversibility in an electrochemical experiment is effectively a statement that the “back-conversion” pathway is accessible before the intermediates are depleted by side chemistry.

A practical way to see the distinction is through solution conditions. Consider the one-electron reduction of nitrobenzene in oxygen-free, dry acetonitrile (MeCN), represented schematically as  
$$
\mathrm{PhNO_2}+e^- \rightleftharpoons \mathrm{PhNO_2^-},  
$$
where ($\mathrm{PhNO_2}$) denotes nitrobenzene and ($\mathrm{PhNO_2^-}$) denotes its reduced form. Under rigorously aprotic, oxygen-free conditions, the reduced species can persist long enough that the reverse scan of a cyclic voltammetry experiment can re-oxidize it back to ($\mathrm{PhNO_2}$). The response is then chemically reversible on the voltammetric time scale.

If the same reduction is carried out in acidic acetonitrile, the reduced species can be intercepted by a coupled chemical reaction, for example a protonation step,  
$$
\mathrm{PhNO_2^-}+\mathrm{H^+}\rightarrow \mathrm{X},  
$$
where ($\mathrm{X}$) represents a chemically transformed product that is not directly converted back to ($\mathrm{PhNO_2}$) on the return scan. In that situation the overall experiment becomes chemically irreversible even if the primary electron-transfer step remains intrinsically fast.

### Cyclic voltammetry signatures of chemical reversibility

The difference between chemical reversibility and chemical irreversibility is reflected in the qualitative shape of an (i)–(E) trace in cyclic voltammetry. When the electro-generated species survives long enough to be driven back during the reverse sweep, a return feature appears: the forward sweep produces a peak (or wave) associated with formation of the product, and the reverse sweep produces a corresponding feature associated with its reconversion. When the product is removed by a follow-up chemical step, the return feature is diminished or absent, because little of the original electro-generated species remains available to undergo the reverse electron transfer. The trace then fails to “close” in the manner characteristic of a chemically reversible system.

### Time scale of measurement and the role of scan rate

Whether a process appears chemically reversible is often controlled as much by the **measurement time scale** as by the underlying chemistry. In cyclic voltammetry the relevant experimental knob is the scan rate ($\nu$) (units of V/s). A larger scan rate compresses the experiment into a shorter time window; conversely, a smaller scan rate lengthens the time available for coupled chemistry to occur.

A convenient estimate of the time spent traversing a potential window of width ($\Delta E$) is  
$$
t_{\text{exp}} \sim \frac{\Delta E}{\nu}.  
$$
Thus, as ($\nu$) increases, ($t_{\text{exp}}$) decreases. If a coupled chemical reaction that consumes the electro-generated species is slower than this experimental time scale, then the species can survive long enough to be converted back during the reverse sweep, and the response appears chemically reversible. If the experiment is slow (small ($\nu$)), the coupled chemical reaction has more time to proceed, the electro-generated species is depleted, and the response becomes chemically irreversible. This is why the same redox couple can appear reversible at high scan rate but irreversible at low scan rate when a follow-up chemical step competes on intermediate time scales.

## Half-Cells and Full Electrochemical Reactions

Electrochemical reactions are naturally decomposed into **half-reactions** occurring at two spatially separated electrodes. A half-cell description specifies only one electrode process (anode or cathode), whereas a full electrochemical cell requires both half-reactions along with the direction of electron flow through the external circuit.

### Half-cell notation and identification of anode and cathode

A compact half-cell notation uses vertical bars to denote phase boundaries. Two illustrative half-cells are  
$$
\mathrm{Pt},|,\mathrm{H_2},|,\mathrm{H^+}  
\qquad\text{and}\qquad  
\mathrm{Cl^-},|,\mathrm{AgCl},|,\mathrm{Ag}.  
$$
The left half-cell is a hydrogen electrode on platinum in contact with ($\mathrm{H_2}$) and an acidic solution. The right half-cell is a silver/silver chloride electrode in contact with chloride.

In a galvanic configuration, the **anode** is where oxidation occurs and electrons are produced; the **cathode** is where reduction occurs and electrons are consumed. The external circuit carries electrons from anode to cathode, while conventional current is defined in the opposite direction.

### Constructing the full-cell reaction from half-reactions (Derivation Mode)

For the hydrogen electrode operating as the anode, the oxidation half-reaction is  
$$
\mathrm{H_2}\rightarrow 2\mathrm{H^+}+2e^-.  
$$
For the ($\mathrm{Ag/AgCl}$) electrode operating as the cathode, the reduction half-reaction is  
$$
\mathrm{AgCl}+e^- \rightarrow \mathrm{Ag}+\mathrm{Cl^-}.  
$$
Balancing electrons and adding gives the overall cell reaction:

$$
\begin{aligned}  
\mathrm{H_2} &\rightarrow 2\mathrm{H^+}+2e^- \\
2\bigl(\mathrm{AgCl}+e^-\rightarrow \mathrm{Ag}+\mathrm{Cl^-}\bigr)  
&\Rightarrow 2\mathrm{AgCl}+2e^-\rightarrow 2\mathrm{Ag}+2\mathrm{Cl^-} \\
\bigl(\mathrm{H_2}\rightarrow 2\mathrm{H^+}+2e^-\bigr)  
+\bigl(2\mathrm{AgCl}+2e^-\rightarrow 2\mathrm{Ag}+2\mathrm{Cl^-}\bigr)  
&\Rightarrow \mathrm{H_2}+2\mathrm{AgCl}\rightarrow 2\mathrm{H^+}+2\mathrm{Ag}+2\mathrm{Cl^-}.  
\end{aligned}  
$$

This construction makes the electron bookkeeping explicit: electrons generated at the anode are exactly consumed at the cathode.

### Direction of electron flow and what changes upon reversal

With ($\mathrm{Pt|H_2|H^+}$) acting as the anode and ($\mathrm{Cl^-|AgCl|Ag}$) acting as the cathode, electrons flow through the external circuit from the platinum electrode toward the silver/silver chloride electrode. Conventional current is opposite to the electron flow direction by definition.

If the current (and thus the direction of electron flow) is reversed, the electrode roles interchange. The platinum electrode becomes the cathode and supports reduction,  
$$
2\mathrm{H^+}+2e^- \rightarrow \mathrm{H_2},  
$$
while the silver electrode becomes the anode and supports oxidation consistent with the ($\mathrm{Ag/AgCl}$) chemistry,  
$$
\mathrm{Ag}+\mathrm{Cl^-}\rightarrow \mathrm{AgCl}+e^-,  
$$
with stoichiometric factors chosen as needed to match electron counts. The “anode” and “cathode” labels are therefore not permanent properties of the materials; they are assignments determined by the direction in which the cell is driven.



> [!figure] figure 3
> ![[Pasted image 20260301041427.png|500]]




> [!figure] figure 4
> ![[Pasted image 20260301041519.png|500]]



> [!figure] figure 5
> ![[Pasted image 20260301041604.png|500]]





# Kinetic Categories of Electron Transfer in Cyclic Voltammetry

The terms _reversible_, _quasi-reversible_, and _irreversible_ are also used in a specifically **kinetic** sense: they describe how rapidly the heterogeneous electron-transfer step proceeds relative to the experimental time scale and mass-transport time scale. In this usage the controlling parameter is the **standard heterogeneous rate constant** ($k^0$). When ($k^0$) is very large, interfacial electron transfer is effectively instantaneous on the voltammetric time scale and the interface remains close to Nernstian equilibrium. As ($k^0$) decreases, the electrode must be driven farther from equilibrium (larger overpotentials) to sustain the same flux, producing measurable distortions in the voltammogram. In the limiting case of very small ($k^0$), the response becomes kinetically irreversible.

To make this quantitative, consider the one-step outer-sphere couple  
$$
\mathrm{O}+ne^- \rightleftharpoons \mathrm{R}.  
$$
The interfacial electron-transfer rate is commonly written in Butler–Volmer form. A convenient way to express it is in terms of the net Faradaic current density (j) (current per area) as a difference of forward and backward interfacial fluxes:

$$
\begin{aligned}  
j &= nF\left(k_f C_{\mathrm{O}}(0,t)-k_b C_{\mathrm{R}}(0,t)\right),\\
k_f &= k^0 \exp\!\left(-\alpha\,\frac{nF}{RT}\,\eta\right),\\
k_b &= k^0 \exp\!\left((1-\alpha)\,\frac{nF}{RT}\,\eta\right),  
\end{aligned}  
$$
where ($C_{\mathrm{O}}(0,t)$) and ($C_{\mathrm{R}}(0,t)$) are the interfacial concentrations, ($\alpha$) is the transfer coefficient, and ($\eta$) is the overpotential,  
$$
\eta \equiv E - E_{\mathrm{eq}}(t),  
\qquad  
E_{\mathrm{eq}}(t) = E^0 + \frac{RT}{nF}\ln\!\left(\frac{a_{\mathrm{O}}(0,t)}{a_{\mathrm{R}}(0,t)}\right).  
$$
Here ($E_{\mathrm{eq}}(t)$) is the Nernstian equilibrium potential corresponding to the instantaneous interfacial composition. The kinetic classification can then be understood as a statement about how small ($\eta$) remains during the measurement.

**Derivation Mode (Nernstian limit as ($k^0\to\infty$)).**  
If interfacial electron transfer is much faster than mass transport and the imposed potential sweep, the interface relaxes to local equilibrium essentially instantly. In that regime the current is not limited by charge transfer; instead the interface adjusts so that ($\eta$) remains small. Formally, take the Butler–Volmer form and consider the limit ($k^0 \to \infty$) while keeping finite diffusional supply. To avoid an unbounded interfacial flux, the exponential factors must remain bounded, which requires  
$$
\eta \to 0.  
$$
Thus,  
$$
\eta \to 0  
;\Rightarrow;  
E \to E_{\mathrm{eq}}(t)  
;\Rightarrow;  
E = E^0 + \frac{RT}{nF}\ln\!\left(\frac{a_{\mathrm{O}}(0,t)}{a_{\mathrm{R}}(0,t)}\right),  
$$
so that the interfacial ratio ($a_{\mathrm{R}}(0,t)/a_{\mathrm{O}}(0,t)$) is slaved to the applied potential through the Nernst relation. This is the kinetic meaning of a _reversible (Nernstian)_ electron transfer.

When ($k^0$) is not large enough for ($\eta$) to remain negligible, the interface cannot maintain Nernstian equilibrium during the sweep. A finite overpotential develops, and the voltammogram departs from the ideal reversible form. This intermediate regime is termed _quasi-reversible_. When ($k^0$) is so small that the current is dominated by sluggish charge transfer (so the reverse conversion is strongly suppressed and peak positions shift markedly), the process is termed _irreversible_ in the kinetic sense.

## How ($k^0$) Manifests in Cyclic Voltammetry

### Microelectrode voltammetry and kinetic extraction by simulation

Microelectrodes are often used to interrogate electron-transfer kinetics because radial diffusion can establish a quasi–steady state, producing smooth, sigmoidal (i)–(E) responses with well-defined limiting currents. In an ideal reversible case (large ($k^0$)), the transition from low current to the diffusion-limited plateau is relatively sharp and occurs at a potential closely tied to the thermodynamic couple (often discussed in terms of a half-wave potential). When ($k^0$) is smaller (quasi-reversible), the same limiting plateau can still be approached, but the rise is broadened and shifted because additional overpotential is required to drive the interfacial flux.

The practical point is that ($k^0$) enters the problem through the interfacial boundary condition (Butler–Volmer kinetics coupled to diffusion). For microelectrodes, the diffusion field and resulting (i)–(E) curve can be computed with relatively few complications, so ($k^0$) is commonly obtained by **fitting experimental voltammograms to simulated ones** that solve transport with Butler–Volmer (or related) kinetic boundary conditions.

### Macroelectrode cyclic voltammetry: reversible vs quasi-reversible peak structure

At macroelectrodes under cyclic voltammetry, diffusion is predominantly planar on the timescale of a scan, and the response to a potential sweep typically displays peaks rather than steady plateaus. In the reversible (Nernstian) limit, the interface composition tracks the applied potential, and the current is governed by diffusion to (and from) the electrode. The resulting voltammogram shows a forward peak (during reduction or oxidation, depending on scan direction) and a corresponding reverse peak when the scan is reversed, with relatively “tight” peak positions and a characteristically symmetric appearance.

As ($k^0$) decreases into the quasi-reversible regime, the peaks broaden and shift. Physically, charge transfer no longer keeps up with the changing potential, so the system must be driven farther from equilibrium to achieve comparable interfacial flux. The separation between forward and reverse features increases, the peak shapes become less ideal, and the currents at a given potential are depressed relative to the reversible benchmark. In the limiting kinetically irreversible case, the reverse peak can become very small or effectively absent over the scanned window, because the backward electron-transfer step is too slow on the experimental timescale to regenerate the original species during the return sweep.

## Chemical Reversibility Distinguished from Kinetic Reversibility in a CV

Even when an electron-transfer step is kinetically fast (electrochemically reversible), the overall voltammetric response can still appear _irreversible_ if the electro-generated species is removed by a follow-up chemical reaction. This is the signature of **chemical irreversibility** superimposed on otherwise rapid electron transfer.

A prototypical situation is an EC mechanism:  
$$
\mathrm{O}+ne^- \rightleftharpoons \mathrm{R}  
\qquad\text{followed by}\qquad  
\mathrm{R} \xrightarrow{k_c} \mathrm{X},  
$$
where ($\mathrm{X}$) is not electroactive (or not electroactive within the scanned window). In such a case the forward scan can still show a strong peak associated with the fast ($\mathrm{O}/\mathrm{R}$) electron transfer, but the reverse scan is diminished because ($\mathrm{R}$) is depleted chemically before it can be converted back to ($\mathrm{O}$). The voltammogram then exhibits an apparent loss of the return peak or a strong asymmetry between forward and reverse currents even though the underlying heterogeneous electron transfer could be intrinsically Nernstian.

This provides a useful diagnostic logic: distortions driven primarily by ($k^0$) (kinetic quasi-reversibility) tend to shift and broaden both directions in a manner consistent with sluggish charge transfer, whereas distortions driven by chemical follow-up reactions primarily suppress the reverse feature by removing the intermediate needed for the back reaction. Scan rate again controls which behavior is observed: shortening the experiment can “outrun” the chemical step and recover a more reversible-looking return trace, while longer experiments provide time for chemical depletion and therefore amplify chemical irreversibility.




> [!figure] figure 6
> ![[Pasted image 20260301041808.png|500]]




> [!figure] figure 7
> ![[Pasted image 20260301041836.png|500]]




> [!figure] figure 8
> ![[Pasted image 20260301041916.png|500]]



# Cell Potentials from Half-Cell Potentials: A Pt(|)($\mathrm{H_2}$)(|)($\mathrm{H^+}$) vs ($\mathrm{Cl^-}$)(|)($\mathrm{AgCl}$)(|)($\mathrm{Ag}$) Example

A full electrochemical cell is specified by its two half-cells together with the direction of electron flow implied by oxidation at the anode and reduction at the cathode. Consider the cell  
$$
\mathrm{Pt},|,\mathrm{H_2},|,\mathrm{H^+};,;\mathrm{Cl^-},|,\mathrm{AgCl},|,\mathrm{Ag},  
$$
for which the standard cell potential is recorded as  
$$
E^\circ_{\text{cell}} = 0.222~\text{V}.  
$$
In the galvanic direction shown, the platinum hydrogen electrode functions as the **anode** (oxidation; loss of electrons), while the silver/silver chloride electrode functions as the **cathode** (reduction; gain of electrons). Electron flow proceeds through the external circuit from anode to cathode, while conventional current is opposite.

### Half-reactions and overall reaction

For the hydrogen electrode operating as an anode, the oxidation half-reaction is written (with two electrons to match stoichiometry across the cell)  
$$
\mathrm{H_2} ;-; 2e^- \;\rightleftharpoons\; 2\mathrm{H^+}.  
$$
For the silver/silver chloride electrode operating as a cathode, the reduction half-reaction is written in two-electron form as  
$$
2\mathrm{AgCl} + 2e^- \;\rightleftharpoons\; 2\mathrm{Ag} + 2\mathrm{Cl^-}.  
$$
Adding these yields the net cell reaction:  
$$
\mathrm{H_2} + 2\mathrm{AgCl} \;\rightleftharpoons\; 2\mathrm{H^+} + 2\mathrm{Ag} + 2\mathrm{Cl^-}.  
$$

## The Nernst Equation Applied to Each Electrode

The electrode potential under nonstandard conditions is obtained by applying the Nernst equation to each half-reaction and then combining the two half-cell potentials into the cell potential.

### Hydrogen electrode (written in reduction form)

The hydrogen electrode Nernst relation is written for  
$$
2\mathrm{H^+}+2e^- \rightleftharpoons \mathrm{H_2}.  
$$

**Derivation Mode**  
$$
\begin{aligned}  
E_{\text{anode}}  
&= E^\circ_{\mathrm{H^+/H_2}} - \frac{0.05916}{2}\log_{10}\!\left(\frac{a_{\mathrm{H_2}}}{a_{\mathrm{H^+}}^{2}}\right)  
\qquad (\text{base-10 log at }25^\circ\text{C}).  
\end{aligned}  
$$

### Silver/silver chloride electrode (two-electron form)

The silver/silver chloride electrode is written in the two-electron form  
$$
2\mathrm{AgCl}+2e^- \rightleftharpoons 2\mathrm{Ag}+2\mathrm{Cl^-},  
$$
so that the reaction quotient is ($Q=a_{\mathrm{Cl^-}}^{2}$) (activities of the pure solids ($\mathrm{AgCl}$) and ($\mathrm{Ag}$) taken as unity). The Nernst relation is then

**Derivation Mode**  
$$
\begin{aligned}  
E_{\text{cathode}}  
&= E^\circ_{\mathrm{AgCl/Ag}} - \frac{0.05916}{2}\log_{10}\!\left(a_{\mathrm{Cl^-}}^{2}\right),  
\end{aligned}  
$$
with the standard-state case corresponding to ($a_{\mathrm{Cl^-}}=1$), giving ($E_{\text{cathode}}=E^\circ_{\mathrm{AgCl/Ag}}$).

## Cell Potential, Spontaneity, and the Sign of ($\Delta G$)

The cell potential is defined by the difference between the cathode and anode potentials:  
$$
E_{\text{net}} = E_{\text{cathode}} - E_{\text{anode}}.  
$$
Under standard conditions (standard-state activities and ($E^\circ_{\mathrm{H^+/H_2}}=0$) by convention for the standard hydrogen electrode), the standard cell potential is  
$$
E^\circ_{\text{cell}} = E^\circ_{\mathrm{AgCl/Ag}} - E^\circ_{\mathrm{H^+/H_2}} = 0.222~\text{V} > 0.  
$$

**Derivation Mode**  
$$
\begin{aligned}  
\Delta G^\circ  
&= -nF E^\circ_{\text{cell}} \\
&= -(2)(96485~\mathrm{C,mol^{-1}})(0.222~\mathrm{V}) \\
&= -4.2839\times 10^{4}~\mathrm{J,mol^{-1}} \\
&= -42.84~\mathrm{kJ,mol^{-1}} \\
&<0.  
\end{aligned}  
$$
Thus, with ($E^\circ_{\text{cell}}>0$), the corresponding ($\Delta G^\circ$) is negative, and the galvanic direction is spontaneous under standard conditions.

## How Changing Chloride Activity Shifts the Cell Voltage

Because  
$$
E_{\text{net}} = E_{\text{cathode}} - E_{\text{anode}},  
$$
reducing the net cell voltage (for fixed anode conditions) requires reducing the cathode potential. From  
$$
E_{\text{cathode}} = E^\circ_{\mathrm{AgCl/Ag}} - \frac{0.05916}{2}\log_{10}\!\left(a_{\mathrm{Cl^-}}^{2}\right),  
$$
an increase in chloride activity ($a_{\mathrm{Cl^-}}$) increases ($\log_{10}(a_{\mathrm{Cl^-}}^{2})$) and therefore **decreases** ($E_{\text{cathode}}$). Consequently, increasing ($a_{\mathrm{Cl^-}}$) decreases ($E_{\text{net}}$). This provides a direct thermodynamic lever for tuning the cell voltage through electrolyte composition: increasing chloride activity shifts the ($\mathrm{AgCl/Ag}$) half-cell potential downward and thereby diminishes the overall driving force of the cell.




> [!figure] figure 9
> ![[Pasted image 20260301042250.png|500]]





# Reversal of Current and Electrochemical-Cell Reversibility

A full cell that operates galvanically in one direction can be driven in the _opposite_ direction by reversing the direction of charge flow through the external circuit. When this reversal causes the original products to be consumed and the original reactants to be regenerated—without invoking side reactions that permanently alter the chemical inventory—the cell is said to exhibit **electrochemical-cell reversibility** in the chemical sense. In other words, the cell behaves as a **chemically reversible electrochemical cell**: the overall reaction runs forward in one direction of current and runs backward when the current is reversed.

### Electrode-role interchange under current reversal

For the cell  
$$
\mathrm{Pt},|,\mathrm{H_2},|,\mathrm{H^+};,;\mathrm{Cl^-},|,\mathrm{AgCl},|,\mathrm{Ag},  
$$
the galvanic direction previously identified corresponds to oxidation at the hydrogen electrode and reduction at the ($\mathrm{AgCl/Ag}$) electrode, giving the net reaction  
$$
\mathrm{H_2}+2\mathrm{AgCl};\rightarrow;2\mathrm{H^+}+2\mathrm{Ag}+2\mathrm{Cl^-}.  
$$
If the external circuit is forced so that electrons flow in the opposite direction, the functional roles of the electrodes interchange: the hydrogen electrode becomes the **cathode** (reduction), while the silver electrode becomes the **anode** (oxidation). The half-reactions then reverse.

**Derivation Mode (half-reactions and net reaction after reversal).**  
$$
\begin{aligned}  
\text{Hydrogen electrode (now cathode, reduction):}\qquad  
&2\mathrm{H^+}+2e^- \rightleftharpoons \mathrm{H_2},\\[4pt]  
\text{Silver/chloride electrode (now anode, oxidation):}\qquad  
&2\mathrm{Ag}-2e^-+2\mathrm{Cl^-}\rightleftharpoons 2\mathrm{AgCl}.  
\end{aligned}  
$$
Adding and canceling electrons gives  
$$
\begin{aligned}  
\bigl(2\mathrm{H^+}+2e^- \rightarrow \mathrm{H_2}\bigr)  
+\bigl(2\mathrm{Ag}-2e^-+2\mathrm{Cl^-}\rightarrow 2\mathrm{AgCl}\bigr)  
&\Rightarrow  
2\mathrm{H^+}+2\mathrm{Ag}+2\mathrm{Cl^-}\rightarrow \mathrm{H_2}+2\mathrm{AgCl}.  
\end{aligned}  
$$
Thus, after current reversal the net reaction is the reverse of the galvanic reaction:  
$$
2\mathrm{H^+}+2\mathrm{Ag}+2\mathrm{Cl^-};\rightarrow;\mathrm{H_2}+2\mathrm{AgCl}.  
$$
This “reactants become products” interchange is precisely what is meant by electrochemical-cell reversibility in the chemical sense.

### Thermodynamic condition for reversal: moving through equilibrium

The direction of spontaneous operation is set by the sign of the cell driving force. Under any specified composition, the equilibrium condition is  
$$
\Delta G = 0  
\qquad\Longleftrightarrow\qquad  
E_{\text{cell}} = E_{\text{eq}}.  
$$
When the cell is allowed to run freely (galvanic mode) and ($E_{\text{cell}}>0$) for the chosen direction of reaction, the free energy change is negative:  
$$
\Delta G = -nF E_{\text{cell}} <0,  
$$
and the cell delivers electrical work to the external circuit. Reversing the direction of net reaction requires passing through the equilibrium state and then driving the system so that the _opposite_ overall reaction has ($\Delta G<0$) under the imposed electrical constraints. Operationally, this is achieved by applying an external driving voltage (or current) that forces the electrode potentials to move to the opposite side of their equilibrium values, thereby changing the sign of the net cell driving force for the original direction.

### Why the phrase “chemically reversible electrochemical cell” is meaningful

This cell-level notion of reversibility is stronger than merely saying that each electrode can, in principle, sustain electron transfer in both directions. It asserts that, upon reversing the current, the cell chemistry cleanly retraces itself: ($\mathrm{H_2}$) can be regenerated from ($\mathrm{H^+}$) at the hydrogen electrode, and ($\mathrm{AgCl}$) can be regenerated from ($\mathrm{Ag}$) and ($\mathrm{Cl^-}$) at the silver electrode, so that the net reaction reverses exactly. In practice, this requires that no competing chemistry (corrosion, passivation, gas loss, precipitation away from the interface, or other side pathways) irreversibly consumes the relevant species on the experimental time scale. When that condition is met, reversing current reverses the overall reaction, and the cell is appropriately described as an electrochemically reversible (chemically reversible) electrochemical cell.





> [!figure] figure 10
> ![[Pasted image 20260301042406.png|500]]




# Electrochemical-Cell Reversibility and the Role of Competing Reactions

A cell can be “reversible” in a strictly thermodynamic sense (its direction is set by the sign of ($E_{\text{cell}}$) under given activities), yet still fail to be **electrochemically reversible as a system** when one attempts to reverse the current. In the system-level usage emphasized here, an electrochemical cell is _electrochemically reversible_ only if reversing the current causes the original products to be converted back into the original reactants—so that the **net chemical reaction runs backward** rather than being replaced by some different chemistry.

The central practical point is that a forced current reversal does not guarantee that the reverse of the discharge half-reactions will occur. Electrodes and electrolytes typically permit _multiple_ Faradaic processes, and the system follows whichever reactions are kinetically accessible at the required rates and potentials. If an alternative pathway is easier (lower overpotential, faster kinetics, more available reactants), the cell will “choose” that pathway, and the overall chemistry will not retrace itself.

## Example: Zinc in Acidic Medium with a Pt Hydrogen Electrode (Not System-Reversible)

Consider a zinc electrode in acidic solution (e.g., an acidic sulfate medium) coupled to an inert platinum electrode that supports the ($\mathrm{H^+/H_2}$) couple. In discharge (galvanic operation), zinc oxidizes and protons reduce to hydrogen gas.

**Derivation Mode (half-reactions and net discharge reaction).**  
$$
\begin{aligned}  
\text{Anode (oxidation at Zn):}\qquad  
&\mathrm{Zn} \rightarrow \mathrm{Zn^{2+}} + 2e^- ,\\[4pt]  
\text{Cathode (reduction at Pt):}\qquad  
&2\mathrm{H^+} + 2e^- \rightarrow \mathrm{H_2}.  
\end{aligned}  
$$
Adding gives the net reaction:  
$$
\begin{aligned}  
\mathrm{Zn} + 2\mathrm{H^+} \rightarrow \mathrm{Zn^{2+}} + \mathrm{H_2}.  
\end{aligned}  
$$

In an _ideal_ chemically reversible cell, reversing the current would simply reverse these two half-reactions:

- zinc ions would be reduced back to zinc metal (plating),
    
- hydrogen gas would be oxidized back to protons (consumed),
    

so that the overall chemical change would run backward:  
$$
\mathrm{Zn^{2+}} + \mathrm{H_2} \rightarrow \mathrm{Zn} + 2\mathrm{H^+}.  
$$

### What actually happens upon forced reversal: water electrolysis dominates

In acidic aqueous media, the attempted reverse operation is typically undermined by **competing water/proton reactions**. In particular:

1. **At the would-be cathode (where Zn plating is desired):** reduction of ($\mathrm{H^+}$) to ($\mathrm{H_2}$) is usually far easier than reduction of ($\mathrm{Zn^{2+}}$) to ($\mathrm{Zn}$) under these conditions, so the cathodic current is taken up by hydrogen evolution rather than zinc deposition.
    
2. **At the would-be anode (where ($\mathrm{H_2}$) oxidation is desired):** if hydrogen is not supplied/maintained at the electrode at a rate commensurate with the imposed anodic current (or if conditions favor it), anodic current can instead be sustained by water oxidation (oxygen evolution).
    

When these competing processes take over, the net effect of “reversing the cell” is no longer the reverse of the zinc–acid discharge chemistry. Instead, the system performs **electrolysis of water**:

**Derivation Mode (net reaction under the competing pathway).**  
$$
\begin{aligned}  
\text{Cathode (hydrogen evolution):}\qquad  
&2\mathrm{H^+}+2e^- \rightarrow \mathrm{H_2},\\[4pt]  
\text{Anode (oxygen evolution, acidic form):}\qquad  
&2\mathrm{H_2O} \rightarrow \mathrm{O_2}+4\mathrm{H^+}+4e^-.  
\end{aligned}  
$$
Multiply the cathode reaction by 2 and add:  
$$
\begin{aligned}  
4\mathrm{H^+}+4e^- \rightarrow 2\mathrm{H_2}\\
2\mathrm{H_2O} \rightarrow \mathrm{O_2}+4\mathrm{H^+}+4e^-\\
\hline  
2\mathrm{H_2O} \rightarrow 2\mathrm{H_2}+\mathrm{O_2}.  
\end{aligned}  
$$

That is exactly the hallmark of a **non–electrochemically reversible system** in the cell-level sense: when the current is reversed, the original products do _not_ simply become reactants. Instead, the cell finds a different set of electrode reactions that can carry the imposed current more readily, and the overall chemistry becomes water splitting rather than “charging” the zinc reaction backward.

## Meaning of “electrochemically reversible system” at the cell level

This motivates the system-level definition: an **electrochemically reversible cell** (equivalently, a chemically reversible electrochemical cell) is one for which current reversal swaps the electrode roles _and_ the same chemical couple is retraced in reverse—so that the net reaction reverses cleanly. Cells that admit easier parasitic pathways (hydrogen evolution, oxygen evolution, passivation, corrosion, precipitation, gas loss, etc.) fail this criterion even if the discharge reaction itself is well-defined and spontaneous in the forward direction.




> [!figure] figure 11
> ![[Pasted image 20260301042539.png|500]]




