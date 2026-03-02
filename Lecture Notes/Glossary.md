# Lecture Notes Glossary

This glossary collects definitions used across the lecture-note chapters. Entries are alphabetized by term (case-insensitive) and are written to be consistent with the book’s usage and notation.

## activity

In these chapters, **activity** $a_i$ is the dimensionless thermodynamic measure of “effective concentration” that appears in equilibrium expressions. It is defined through the activity form of chemical potential, $\mu_i=\mu_i^\circ+RT\ln a_i$, so that non-ideal interactions (when present) are absorbed into $a_i$ rather than treated by modifying the formal structure of equilibrium relations.

## cathodic limiting current

The **cathodic limiting current** $i_{\mathrm{L,c}}$ is the transport-limited plateau current for a cathodic (reduction) wave, reached when the oxidized-form surface concentration becomes negligible, $C_{\mathrm{O}}(x=0)\approx 0$, so that further increases in cathodic driving force cannot increase the reaction rate.

## cell Nernst equation

The **cell Nernst equation** is the relation $E_{\text{cell}}=E_{\text{cell}}^\circ-(RT/nF)\ln\mathcal{Q}$ that connects a cell’s measured voltage to the reaction quotient $\mathcal{Q}$ for the net cell reaction, under reversible, activity-based thermodynamic bookkeeping.

## charge transfer

In these chapters, **charge transfer** is the interfacial electron-transfer step at the electrode/solution boundary that changes the oxidation state (and therefore the chemical identity) of an electroactive species, e.g., $\mathrm{O}+ne^- \rightleftharpoons \mathrm{R}$. Charge transfer occurs at the interface and is conceptually distinct from mass transport in the solution phase.

## charging current

**charging current** is the transient current that flows when the electrode/solution interface accumulates or releases charge in response to a change in applied potential, analogous to charging a capacitor. In non-faradaic windows, charging current (also called **capacitive current**) can dominate the measured current even when no net charge-transfer reaction proceeds.

## chemical potential

The **chemical potential** $\mu_i$ is the partial molar Gibbs free energy of species $i$, defined by $\mu_i=(\partial G/\partial n_i)_{T,P,n_{j\neq i}}$. It is the thermodynamic driving-force measure that tracks how composition (through activities) changes free energy in reactions and in mass transfer.

## chemical reversibility

In these chapters, **chemical reversibility** is the condition that any coupled homogeneous chemistry (before, after, or concurrent with electron transfer) is fast enough, and sufficiently backward-capable, that the overall chemical system can return to its initial composition on the experimental time scale (for example, on the reverse scan in cyclic voltammetry). In voltammetry, chemical irreversibility often appears as suppression of the reverse-scan feature because products are removed (or transformed) by follow-up chemistry.

## current-controlled mode

**current-controlled mode** is an experimental mode in which the imposed input is a current program $i(t)$ and the measured output is the potential response $E(t)$.

## diffuse layer

The **diffuse layer** is the part of the solution-side double layer in which excess ionic charge is distributed into the electrolyte volume (three-dimensionally) rather than confined to a compact plane. In the lecture-note partition, it begins beyond the compact-layer boundary (near the OHP) and extends toward the bulk solution.

## diffusion-layer (film) approximation

The **diffusion-layer (film) approximation** is a simplified transport model for an electrode boundary layer in which the near-surface concentration field is treated as an approximately linear drop from a bulk value $C^*$ to a surface value $C(x=0)$ across a single effective thickness $\delta$. In this picture, the detailed curvature of $C(x)$ is replaced by an effective gradient $(C^*-C(x=0))/\delta$, allowing diffusive fluxes (and limiting currents) to be written in terms of lumped parameters such as $m=D/\delta$.

## diffusion-layer thickness

The **diffusion-layer thickness** $\delta$ is the effective thickness used in the diffusion-layer (film) approximation to represent the near-electrode region over which most of the concentration drop occurs. It is not a sharp physical boundary; it depends on time scale, hydrodynamics, geometry, and the transport regime being modeled.

## diffusion-limited condition

The **diffusion-limited condition** is the transport-controlled limit in which the reactant concentration at the electrode surface is effectively depleted (often idealized as $C(x=0)\approx 0$ for a species being consumed at the electrode). Once this condition is reached, further changes in potential do not significantly increase the concentration gradient, so the faradaic current approaches a limiting plateau.

## diffusion-limited current

The **diffusion-limited current** is the limiting-current plateau obtained when diffusion (more broadly, mass transport through the electrolyte) controls the rate rather than interfacial charge-transfer kinetics. In film-type descriptions it is obtained by taking $C(x=0)\approx 0$ for the reactant so that the maximum sustainable flux is set by the bulk-to-surface concentration drop across an effective transport length scale.

## double-layer capacitance

The **double-layer capacitance** $C_{\mathrm{d}}$ is the effective capacitance associated with charge stored in the electrical double layer at an electrode/solution interface. It links interfacial charge and interfacial potential difference through $q=C_{\mathrm{d}}E$ (locally, under the capacitor model) and governs charging transients through time constants such as $\tau=R_{\mathrm{s}}C_{\mathrm{d}}$ in simple series models.

## electric double layer

The **electric double layer** is the structured interfacial region at an electrode/solution boundary in which excess charge on the electrode is balanced by an oppositely signed distribution of charge in the adjacent solution (and by oriented dipoles), so that electroneutrality is maintained overall while charge is spatially separated into layers.

## electrochemical cell reversibility

In these chapters, **electrochemical cell reversibility** is the ability of a full electrochemical cell to be driven in the reverse (non-spontaneous) direction by reversing the imposed current, so that products can be converted back into reactants under the experimental conditions. This notion requires not only correct sign/role bookkeeping (anode vs. cathode) but also that the necessary chemical forms can actually be regenerated (chemical reversibility).

## electrochemical potential

The **electrochemical potential** $\bar{\mu}_i$ is the molar free energy of species $i$ including both chemical and electrical contributions. In the convention used here, $\bar{\mu}_i=\mu_i+z_iF\phi$, where $\mu_i$ is the chemical potential, $z_i$ is the charge number, $F$ is Faraday’s constant, and $\phi$ is the Galvani potential of the phase containing $i$.

## electrochemical reversibility

In these chapters, **electrochemical reversibility** is the condition that the interfacial electron-transfer step is fast enough, relative to the experimental time scale, that the interface remains near equilibrium (Nernstian). Whether a couple appears electrochemically reversible therefore depends on the experiment’s time scale (for example, the scan rate in CV), not only on the identity of the redox couple.

## electrode potential

In these chapters, the **electrode potential** $E$ is the interfacial potential difference for a metal (M)/solution (S) interface defined by the sign convention $E=\phi^{\mathrm{M}}-\phi^{\mathrm{S}}$. A single isolated interface does not provide an independently measurable “absolute” $E$; only differences of electrode potentials (cell voltages, or potentials tabulated relative to a reference electrode) are directly measurable.

## equivalent circuit

An **equivalent circuit** is an electrical-network model (built from idealized circuit elements such as resistors and capacitors) that reproduces the observed input–output behavior of an electrochemical cell over a specified regime (for example, a non-faradaic potential window).

## faradaic process

A **faradaic process** is an interfacial process in which net charge crosses an interface in a stoichiometric way tied to a chemical or mass-transfer event, so that the charge passed can be related to an amount of species transfer (a Faraday-type relation). At a metal/solution electrode this is most often an oxidation–reduction (electron-transfer) reaction; at an interface between immiscible electrolyte solutions it can be transfer of an ion between phases.

## flux

In these chapters, **flux** is the molar flow rate of a species per unit area, typically denoted $J$ (or $J_x$ for a specified direction). It is reported in units of mol m$^{-2}$ s$^{-1}$ and provides the bridge between mass transport in solution and faradaic reaction rate at an electrode surface.

## Galvani potential

The **Galvani potential** $\phi$ is the inner electrical potential of a phase. Differences of $\phi$ across an interface contribute to the electrical work term $z_iF\phi$ in electrochemical potentials and, under a chosen convention, define electrode and cell potentials.

## half-wave potential

The **half-wave potential** $E_{1/2}$ is the potential on a steady-state sigmoidal voltammetric wave at which the current equals one half of the limiting-current plateau (for example, $i=i_{\mathrm{L,c}}/2$ for a cathodic wave). For a reversible couple under steady-state transport control, $E_{1/2}$ is a practical reference point that is shifted from $E^{0}$ by a mass-transfer correction when transport coefficients of oxidized and reduced forms differ.

## ideally polarizable electrode (IPE)

An **ideally polarizable electrode (IPE)** is an idealized electrode/solution interface across which no charge-transfer reaction occurs over the potential range of interest. In this limit, changing the potential changes interfacial charge and structure rather than driving net electron-transfer chemistry.

## inner Helmholtz plane (IHP)

The **inner Helmholtz plane (IHP)** is an idealized plane near the electrode surface associated with the compact, inner-layer structure, including the closest approach of specifically adsorbed ions at the interface.

## inner potential

See **Galvani potential**.

## inner-sphere electron transfer

An **inner-sphere electron transfer** is an electron-transfer process that involves a specifically adsorbed intermediate or bond-forming interaction with the electrode (or a bridging ligand), so that the electrode material and surface chemistry can strongly influence the reaction pathway and kinetics.

## interface between two immiscible electrolyte solutions (ITIES)

An **interface between two immiscible electrolyte solutions (ITIES)** is a boundary between two liquid electrolyte phases (for example, water and nitrobenzene) that remain macroscopically immiscible but can exchange ions across the interface under an applied interfacial potential difference.

## interfacial Galvani potential difference

The **interfacial Galvani potential difference** $\Delta\phi_{W}^{NB}$ is the Galvani-potential difference between two phases at an ITIES, defined (for organic $NB$ relative to aqueous $W$) as $\Delta\phi_{W}^{NB}=\phi^{NB}-\phi^{W}$.

## ion-transfer reaction

An **ion-transfer reaction** is an interfacial process in which an ion moves from one liquid phase to another across an ITIES without undergoing an electron-transfer (redox) transformation.

## limiting current

The **limiting current** $i_{\mathrm{L}}$ is the plateau magnitude of faradaic current reached when mass transport limits the supply (or removal) of an electroactive species at the electrode surface, so that further changes in potential do not increase the reaction rate. In diffusion-controlled film models, it scales as $i_{\mathrm{L}}\propto nFA\,m\,C^*$ with $m=D/\delta$.

## mass transport

In these chapters, **mass transport** is the physical movement of species through the electrolyte that supplies reactant to, and removes product from, the electrode vicinity. It can include diffusion (driven by concentration gradients), migration (driven by electric fields), and convection (driven by fluid motion); which contributions matter depends on the experimental conditions and the approximations being used.

## mass-transfer coefficient

The **mass-transfer coefficient** $m$ is a lumped parameter that converts a bulk-to-surface concentration difference into a transport flux, typically written $J\approx m\,(C^*-C(x=0))$. In the diffusion-layer (film) approximation, $m=D/\delta$ and has units of m s$^{-1}$.

## molar flux

The **molar flux** $J$ is the rate at which moles of a species cross a unit area per unit time in a specified direction (units of mol m$^{-2}$ s$^{-1}$). At an electrode, the normal molar flux evaluated at the surface couples to faradaic current through $i=nFA\,J(x=0)$ under the usual sign conventions and stoichiometric bookkeeping.

## Nernstian

In these chapters, **Nernstian** behavior means that interfacial electron transfer is fast enough to maintain local equilibrium between oxidized and reduced forms at the electrode surface. As a result, the surface composition ratio is constrained by the Nernst equation at each applied potential, and changes in $E$ primarily shift the surface concentrations rather than being limited by charge-transfer kinetics.

## non-faradaic process

A **non-faradaic process** is an interfacial response in which no net charge-transfer chemistry occurs across the electrode/solution interface. The resulting measurable current is associated with charging of the double layer and related interfacial reorganizations.

## non-faradaic window

A **non-faradaic window** is a range of applied potentials over which interfacial charge-transfer (faradaic) reactions are negligible, so the measured current is dominated by charging (capacitive) contributions.

## non-specifically adsorbed ion

A **non-specifically adsorbed ion** is an ion near the interface that is not bound in a specific adsorption site, but instead is distributed in the electrolyte and interacts with the electrode primarily through long-range electrostatic forces as part of the diffuse screening cloud.

## outer Helmholtz plane (OHP)

The **outer Helmholtz plane (OHP)** is an idealized plane marking the outer boundary of the compact (inner) layer, beyond which the diffuse-layer charge distribution extends into the bulk electrolyte.

## outer-sphere electron transfer

An **outer-sphere electron transfer** is an electron-transfer process that does not require formation of a specific chemical bond between the redox species and the electrode surface; the electron is transferred through the interfacial region without a surface-bound intermediate.

## poised system

A **poised system** is a system in which a redox pair is present in bulk solution in a way that allows the electrode potential to be described (over the relevant time scale) by a Nernstian dependence on oxidized/reduced composition.

## potential-controlled mode

**potential-controlled mode** is an experimental mode in which the imposed input is a potential program $E(t)$ and the measured output is the current response $i(t)$.

## quasi-reversible

In these chapters, **quasi-reversible** describes an intermediate kinetic regime in which interfacial electron transfer is neither fast enough to be effectively Nernstian nor slow enough to behave as a fully irreversible limit on the experimental time scale. In CV language, quasi-reversible responses often show shifted/distorted features relative to the electrochemically reversible case.

## reaction quotient

The **reaction quotient** $\mathcal{Q}$ is the activity product $\mathcal{Q}=\prod_k a_k^{\nu_k}$ for a reaction written $\sum_k \nu_k A_k=0$ (with $\nu_k>0$ for products and $\nu_k<0$ for reactants). It determines how composition shifts the reaction free energy through $\Delta G_r=\Delta G_r^\circ+RT\ln\mathcal{Q}$.

## scan rate

The **scan rate** $v$ is the slope of a linear potential ramp, $v=dE/dt$, typically reported in V s$^{-1}$ (or V s$^{-1}$ equivalents such as mV s$^{-1}$). In purely capacitive regimes, it sets the steady charging-current magnitude through $i_{\mathrm{nf}}\approx vC_{\mathrm{d}}$.

## solution resistance

The **solution resistance** $R_{\mathrm{s}}$ is the effective resistance of the electrolyte path that current traverses between electrodes. When current flows, it produces an Ohmic drop $E_{R_{\mathrm{s}}}=iR_{\mathrm{s}}$ and, together with $C_{\mathrm{d}}$, sets charging time scales such as $\tau=R_{\mathrm{s}}C_{\mathrm{d}}$.

## specifically adsorbed ion

A **specifically adsorbed ion** is an ion that resides in the compact part of the double layer in close proximity to the electrode surface, typically treated as having a well-defined closest-approach plane (associated with the IHP) rather than being distributed purely as part of the diffuse layer.

## standard cell potential

The **standard cell potential** $E_{\text{cell}}^\circ$ is the cell voltage under the defined standard-state conditions (typically activities set to 1), with the net cell reaction written in the spontaneous direction at that standard state.

## standard electrode potential

The **standard electrode potential** $E^\circ$ (for a specified half-reaction under the stated conventions) is the constant term in the Nernst form of the electrode potential. In practice, it is tabulated relative to a reference electrode convention and therefore represents a comparative quantity rather than an independently measurable “absolute” potential of a single isolated interface.

## standard Gibbs free energy of reaction

The **standard Gibbs free energy of reaction** $\Delta G_r^\circ$ is the Gibbs free energy change per mole of reaction as written when all reactants and products are in their standard states. It is related to standard cell potential by $\Delta G_r^\circ=-nF E_{\text{cell}}^\circ$.

## standard Gibbs free energy of transfer

The **standard Gibbs free energy of transfer** $\Delta G_{\mathrm{tr}}^{\circ,W\to NB}$ is the standard-state free energy change for transferring a species from phase $W$ to phase $NB$, defined by $\Delta G_{\mathrm{tr}}^{\circ,W\to NB}=\mu_i^{\circ,NB}-\mu_i^{\circ,W}$. It captures (at standard state) the ion’s relative solvation preference between the two liquids and appears as the constant offset in ITIES Nernst-type relations.

## standard rate constant

In these chapters, the **standard rate constant** $k^{0}$ is the kinetic parameter that sets the intrinsic speed of interfacial electron transfer under standard-state conditions, as it appears in electron-transfer rate laws. Larger $k^{0}$ corresponds to faster interfacial kinetics and therefore makes electrochemical reversibility easier to achieve on a given experimental time scale.

## steady state (mass transport)

In electrode mass transport, **steady state** means the concentration field near the electrode is time-independent over the measurement window ($\partial C/\partial t=0$ in the region of interest), so fluxes and the resulting transport-controlled current become time-independent.

## steady-state voltammetry

**steady-state voltammetry** is a mode of measurement in which each current value is recorded after the near-electrode concentration field has reached a steady state at the imposed potential. The resulting $i$–$E$ curve therefore reflects time-independent transport profiles (for each point) rather than transient diffusion-layer growth.

## time constant

In an RC charging model, the **time constant** $\tau$ is the parameter that sets the exponential charging/decay time scale. For a series $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model, $\tau=R_{\mathrm{s}}C_{\mathrm{d}}$, and currents of the form $i(t)=i(0^+)e^{-t/\tau}$ decay to $e^{-1}\approx 0.37$ of their initial value at $t=\tau$.
