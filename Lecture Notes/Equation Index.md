# Lecture Notes Equation Index

This index collects equation callouts used across the lecture-note chapters. Entries are alphabetized by callout title (case-insensitive). Each entry reproduces the equation callout verbatim and is followed by a brief explanation of what the equation asserts and how it is typically used.

> [!equation] Capacitive (charging) current
> $$
> i_{\mathrm{C}}=\frac{dq}{dt}=C\,\frac{dE}{dt}
> $$

This relates non-faradaic (capacitive) current to how quickly the interfacial potential is changed, under the capacitor model $q=CE$.

> [!equation] Capacitor relation for interfacial charging
> $$
> q = C\,E
> $$

This is the capacitor constitutive law: stored charge is proportional to potential difference with proportionality constant $C$.

> [!equation] Cathodic limiting current (film approximation)
> $$
> i_{\mathrm{L,c}}=nFA\,m_{\mathrm{O}}\,C_{\mathrm{O}}^{*}
> $$

This gives the transport-limited plateau current for a cathodic (reduction) wave in the film approximation: when $C_{\mathrm{O}}(x=0)\approx 0$, the flux of $\mathrm{O}$ to the surface (and therefore the current) is set by bulk oxidized-form concentration and the oxidized-form mass-transfer coefficient.

> [!equation] Cell potential from half-cell potentials
> $$
> E_{\text{cell}} = E_{\text{cathode}}-E_{\text{anode}}
> $$

This defines the cell voltage in terms of the electrode potentials at the cathode and anode, fixing a sign convention used for spontaneity and bookkeeping.

> [!equation] Cell potential from reaction Gibbs free energy
> $$
> \Delta G_r = -nF E_{\text{cell}}
> $$

For a reversible cell reaction, this equates electrical driving force to thermodynamic driving force: a positive cell voltage corresponds to a negative reaction free energy change in the spontaneous direction.

> [!equation] Charge passed by a constant current
> $$
> Q = I t
> $$

This integrates current over time for the special case of a constant current, giving the total charge passed.

> [!equation] Charge–current relations
> $$
> i(t)=\frac{dq}{dt}
> $$
> 
> $$
> q(t)=\int_{0}^{t} i(t')\,dt'
> $$

These are kinematic identities: current is the time derivative of stored charge, and charge is the time integral of current.

> [!equation] Chemical potential from activity
> $$
> \mu_i^\alpha=\mu_i^{\circ,\alpha}+RT\ln a_i^\alpha
> $$

This is the activity form of chemical potential; it defines activity $a_i^\alpha$ relative to a standard chemical potential $\mu_i^{\circ,\alpha}$ and introduces the thermodynamic factor $RT$.

> [!equation] Current-step potential response (non-faradaic, $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model)
> $$
> E(t)=i\!\left(R_{\mathrm{s}}+\frac{t}{C_{\mathrm{d}}}\right)
> $$

For a constant current step through a series $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ interface, this gives an Ohmic intercept $iR_{\mathrm{s}}$ plus a linear-in-time capacitive term with slope $i/C_{\mathrm{d}}$.

> [!equation] Diffusion-layer (film) approximation for flux
> $$
> J \approx D\,\frac{C^{*}-C(x=0)}{\delta}
> $$

This approximates the diffusive flux by assuming a linear concentration profile across an effective diffusion-layer thickness $\delta$.

> [!equation] Double-layer charge-density bookkeeping (metal vs. solution)
> $$
> \sigma^{\mathrm{S}}=\sigma^{\mathrm{i}}+\sigma^{\mathrm{d}}=-\sigma^{\mathrm{m}}
> $$

This states charge balance in the electric double layer: the total solution-side charge density (inner-layer plus diffuse-layer contributions) balances the metal-side charge density with opposite sign.

> [!equation] Electrochemical potential (definition)
> $$
> \bar{\mu}_i^\alpha=\mu_i^\alpha+z_iF\phi^\alpha
> $$

This defines electrochemical potential as chemical potential plus an electrical work contribution $z_iF\phi^\alpha$, the starting point for equilibrium conditions involving charged species.

> [!equation] Equilibrium across phases (electrochemical potential)
> $$
> \bar{\mu}_i^\alpha=\bar{\mu}_i^\beta
> $$

This is the equilibrium criterion for a species distributed across phases: the electrochemical potential must be the same in each phase at equilibrium.

> [!equation] Faraday’s law (electrons from charge)
> $$
> n(e^-)=\frac{Q}{F}
> $$
> 
> $$
> N(e^-)=n(e^-)\,N_{\mathrm{A}}
> $$

These convert a passed charge $Q$ into an amount of electron transfer: moles of electrons via $F$ and number of electrons via $N_{\mathrm{A}}$.

> [!equation] Fick’s first law (one-dimensional diffusion)
> $$
> J_x = -D\,\frac{dC}{dx}
> $$

This is the constitutive relation for one-dimensional diffusion: the flux component $J_x$ in the $+x$ direction is proportional to the concentration gradient with proportionality $D$, and the minus sign indicates that diffusion carries material down-gradient.

> [!equation] Flux–current relation (faradaic current as a reaction flux)
> $$
> i = nFA\,J
> $$

This converts a molar flux $J$ of an electroactive species at an electrode into an electrical current, using stoichiometric electron count $n$, Faraday’s constant $F$, and area $A$.

> [!equation] Free energy and cell potential
> $$
> \Delta G = -nF E_{\text{cell}}
> $$

This links thermodynamic driving force to electrical driving force for a cell reaction: a positive $E_{\text{cell}}$ corresponds to $\Delta G<0$ for the spontaneous direction.

> [!equation] Half-wave potential (mass-transfer corrected)
> $$
> E_{1/2}=E^{0}+\frac{0.059}{n}\,\log_{10}\!\left(\frac{m_{\mathrm{R}}}{m_{\mathrm{O}}}\right)
> $$

This gives the steady-state half-wave potential including unequal mass-transfer coefficients for reduced and oxidized forms; it reduces to $E^{0}$ when $m_{\mathrm{R}}=m_{\mathrm{O}}$. 

> [!equation] Hydrogen electrode half-reaction (written in reduction direction)
> $$
> 2\mathrm{H}^+ + 2e^- \rightleftharpoons \mathrm{H}_2
> $$

This records the canonical hydrogen redox couple in reduction form, often used for reference-electrode and Nernst-equation discussions.

> [!equation] Interfacial Galvani-potential drop for $\mathrm{Zn}^{2+}/\mathrm{Zn}$ (electrochemical-potential form)
> $$
> \phi^{\mathrm{S}}-\phi^{\mathrm{M}}
> =
> \frac{\mu_{\mathrm{Zn}}^{\circ,\mathrm{M}}-\mu_{\mathrm{Zn}^{2+}}^{\circ,\mathrm{S}}-2\mu_e^{\mathrm{M}}}{2F}
> -
> \frac{RT}{2F}\ln a_{\mathrm{Zn}^{2+}}^{\mathrm{S}}
> $$

This isolates the potential difference across a metal/solution interface for the $\mathrm{Zn}^{2+}+2e^- \rightleftharpoons \mathrm{Zn}$ half-reaction by substituting electrochemical potentials; it exhibits a Nernst-type dependence on $\ln a_{\mathrm{Zn}^{2+}}$ plus a constant term set by standard-state and metal-electron reference choices.

> [!equation] Limiting current under diffusion control (film approximation)
> $$
> i_{\mathrm{L}} = nFA\,m\,C^{*}
> $$

This gives the diffusion-limited current for a species of bulk concentration $C^*$ under the film approximation, with $m=D/\delta$ acting as a mass-transfer coefficient.

> [!equation] Linearized steady-state Nernst plot (slope form)
> $$
> \log_{10}\!\left(\frac{i_{\mathrm{L,c}}-i}{i}\right)=\frac{n}{0.059}\,(E-E_{1/2})
> $$

This is a linearized form of the steady-state $i$–$E$ relation: plotting the left-hand logarithmic combination versus $E$ yields a straight line of slope $n/0.059$ at 298 K.

> [!equation] Mass-transfer coefficient definition (film approximation)
> $$
> m=\frac{D}{\delta}
> $$

This defines the film-model mass-transfer coefficient $m$ as diffusivity divided by diffusion-layer thickness.

> [!equation] Nernst equation (activity ratio for $\mathrm{O}/\mathrm{R}$)
> $$
> E = E^{0} + \frac{RT}{nF}\ln\!\left(\frac{a_{\mathrm{O}}}{a_{\mathrm{R}}}\right)
> $$

This gives the equilibrium potential of a reversible $\mathrm{O}+ne^- \rightleftharpoons \mathrm{R}$ couple in terms of the activity ratio at the interface.

> [!equation] Nernst equation (base-10 concentration form, 298 K)
> $$
> E = E^{0} - \frac{0.059}{n}\,\log_{10}\!\left(\frac{C_{\mathrm{R}}(x=0)}{C_{\mathrm{O}}(x=0)}\right)
> $$

This is a base-10 specialization of the Nernst relation at 298 K written in terms of surface concentrations; it emphasizes that voltammetry depends on interfacial composition, not bulk composition.

> [!equation] Nernst equation (cell, activity form)
> $$
> E_{\text{cell}} = E_{\text{cell}}^\circ - \frac{RT}{nF}\ln \mathcal{Q}
> $$

This is the cell-level Nernst equation: the measured cell voltage differs from its standard value by a composition-dependent term involving the reaction quotient $\mathcal{Q}$ for the net cell reaction.

> [!equation] Nernst form for a metal/ion electrode (activity form)
> $$
> E = E^\circ_{\mathrm{M}^{z+}/\mathrm{M}}+\frac{RT}{zF}\ln a_{\mathrm{M}^{z+}}^{\mathrm{S}}
> $$

This is the Nernst form for a metal/ion electrode under the convention $E=\phi^{\mathrm{M}}-\phi^{\mathrm{S}}$; it shows how the electrode potential shifts with the activity of the ionic form in solution.

> [!equation] Nernst form for the $\mathrm{Zn}^{2+}/\mathrm{Zn}$ electrode (activity form)
> $$
> E
> =
> E^\circ_{\mathrm{Zn}^{2+}/\mathrm{Zn}}
> +
> \frac{RT}{2F}\ln a_{\mathrm{Zn}^{2+}}^{\mathrm{S}}
> $$

This is the $\mathrm{Zn}^{2+}+2e^- \rightleftharpoons \mathrm{Zn}$ specialization of the metal/ion Nernst form, with the electron stoichiometric number fixed at 2 and the composition dependence appearing through $\ln a_{\mathrm{Zn}^{2+}}$.

> [!equation] Parallel-plate capacitance model
> $$
> C=\varepsilon\,\varepsilon_{0}\,\frac{A}{d}
> $$

This is the parallel-plate capacitor expression used as an interface analogy: capacitance scales with area and permittivity and inversely with an effective separation distance, motivating geometric/dielectric scaling in simple lumped interface models.

> [!equation] Reaction equilibrium condition (electrochemical potentials)
> $$
> \sum_k \nu_k\,\bar{\mu}_k = 0
> $$

This is the general reaction equilibrium statement written in terms of electrochemical potentials; it is the charged-species analog of $\sum_k \nu_k \mu_k=0$ and is especially convenient for electrode half-reactions.

> [!equation] Reaction Gibbs free energy (activity form)
> $$
> \Delta G_r = \Delta G_r^\circ + RT\ln \mathcal{Q}
> $$

This expresses the reaction free energy as a standard-state constant plus a term that depends on composition through the activity-based reaction quotient $\mathcal{Q}$.

> [!equation] Scan rate and linear ramp
> $$
> v=\frac{dE}{dt}
> $$
> 
> $$
> E(t)=E(t_1)+v(t-t_1)
> $$

These define scan rate as the slope of a linear potential ramp and give the explicit ramp form used in ramp-driven charging calculations.

> [!equation] Series combination of interfacial capacitances
> $$
> \frac{1}{C_{\mathrm{tot}}}=\frac{1}{C_{\mathrm{d}}}+\frac{1}{C_{\mathrm{SCE}}}
> $$

This gives the effective capacitance of two capacitors in series, used to combine working- and reference-electrode capacitive contributions into a single $C_{\mathrm{tot}}$.

> [!equation] Standard free energy and standard cell potential
> $$
> \Delta G_r^\circ = -nF E_{\text{cell}}^\circ
> $$

This defines the standard cell potential as the standard reaction free energy expressed in electrical units; it is the standard-state analog of $\Delta G_r=-nF E_{\text{cell}}$.

> [!equation] Steady-state $i$–$E$ relation (reversible couple with cathodic limiting current)
> $$
> E=E_{1/2}+\frac{0.059}{n}\,\log_{10}\!\left(\frac{i_{\mathrm{L,c}}-i}{i}\right)
> $$

This relates steady-state current and potential for a reversible couple under cathodic limiting-current conditions; it is a steady-state analog of the Nernst relation expressed in terms of measurable current.

> [!equation] Surface concentrations in steady-state mass transport (film approximation)
> $$
> C_{\mathrm{R}}(x=0)=\frac{i}{nFA\,m_{\mathrm{R}}},
> \qquad
> C_{\mathrm{O}}(x=0)=\frac{i_{\mathrm{L,c}}-i}{nFA\,m_{\mathrm{O}}}
> $$

These express how steady-state flux balance links surface concentrations to current via mass-transfer coefficients for reduced and oxidized forms.

> [!equation] Voltage partition in the $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ series model
> $$
> \Delta E = E_{R_{\mathrm{s}}}+E_{C_{\mathrm{d}}} = iR_{\mathrm{s}} + \frac{q}{C_{\mathrm{d}}}
> $$

This partitions an applied voltage step into an Ohmic drop across solution resistance and a capacitive drop across the double-layer capacitance, yielding the governing first-order charging equation when combined with $i=dq/dt$.

> [!equation] Voltage-ramp charging current (non-faradaic, $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model)
> $$
> i(t)=vC_{\mathrm{d}}\!\left(1-e^{-t/(R_{\mathrm{s}}C_{\mathrm{d}})}\right)
> $$

This gives the non-faradaic current response to a linear potential ramp: after a transient set by $\tau=R_{\mathrm{s}}C_{\mathrm{d}}$, the current approaches the steady value $vC_{\mathrm{d}}$.

> [!equation] Voltage-step charging current (non-faradaic, $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model)
> $$
> i(t)=\frac{\Delta E}{R_{\mathrm{s}}}\,e^{-t/(R_{\mathrm{s}}C_{\mathrm{d}})}
> $$

This is the exponential decay of charging current after a voltage step across a series $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ interface; the time constant is $\tau=R_{\mathrm{s}}C_{\mathrm{d}}$ and the initial current is $\Delta E/R_{\mathrm{s}}$.

> [!equation] Voltage-step stored charge (non-faradaic, $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model)
> $$
> q(t)=\Delta E\,C_{\mathrm{d}}\!\left(1-e^{-t/(R_{\mathrm{s}}C_{\mathrm{d}})}\right)
> $$

This gives the exponential approach of stored interfacial charge to its long-time limit $\Delta E\,C_{\mathrm{d}}$ after a voltage step across a series $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ interface.
