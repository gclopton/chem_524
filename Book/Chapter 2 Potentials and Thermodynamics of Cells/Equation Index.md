# Chapter 2 Equation Index

This index collects equations from equation callouts in Chapter 2. Equations are listed in alphabetical order by their callout titles.

> [!equation] Activity definition (solute and gas)
> 
> $$
> \begin{equation*}
> a_{j}=\gamma_{j} C_{j} / C_{j}^{0} \quad a_{j}=\gamma_{j} P_{j} / P_{j}^{0} \tag{2.1.34a,b}
> \end{equation*}
> $$
> 

This equation says that the activity $a_{j}$ of a species is the product of (i) a unitless “amount relative to standard state” and (ii) a unitless nonideality correction, the activity coefficient $\gamma_{j}$.

The chunk $C_{j} / C_{j}^{0}$ (or $P_{j} / P_{j}^{0}$ for gases) is a normalized concentration (or pressure): it is dimensionless and equals 1 in the standard state by construction. The chunk $\gamma_{j}$ accounts for the fact that real solutions and gases are not ideal; it is the factor that adjusts the normalized concentration or pressure into the thermodynamically correct activity that appears in free-energy relations and Nernst-type equations.

> [!equation] Cell-reaction emf from electrode potentials
> 
> $$
> \begin{equation*}
> E_{\mathrm{rxn}}=E_{\mathrm{right}}-E_{\mathrm{left}} \tag{2.1.42}
> \end{equation*}
> $$
> 

This equation says that the emf assigned to a written cell reaction, $E_{\mathrm{rxn}}$, is obtained by taking the potential of the right-hand electrode in the cell schematic relative to the left-hand electrode.

The chunk “right minus left” is the sign convention: swapping the schematic (right $\leftrightarrow$ left) flips the sign of $E_{\mathrm{rxn}}$ because it corresponds to writing the reverse reaction. This convention is designed so that (with the associated reaction direction) a spontaneous cell reaction has a positive $E_{\mathrm{rxn}}$, consistent with the signed thermodynamic relation $\Delta G=-n F E_{\mathrm{rxn}}$.

> [!Equation] Debye–Hückel equation (extended form)
> 
> $$
> \begin{equation*}
> \log \gamma_{j}=\frac{-A z_{j}^{2} I^{1 / 2}}{1+B d_{j} I^{1 / 2}} \tag{2.1.35}
> \end{equation*}
> $$
> 

This equation says that, for dilute electrolyte solutions, the activity coefficient $\gamma_{j}$ of ionic species $j$ decreases from 1 as the ionic strength $I$ increases, with a stronger effect for more highly charged ions.

Several chunks have immediate physical meaning. The factor $z_{j}^{2}$ shows that the departure from ideality depends on charge magnitude (a $2+$ ion is affected much more strongly than a $1+$ ion). The factor $I^{1/2}$ captures the characteristic square-root dependence on ionic strength in the Debye–Hückel picture. The denominator $1+B d_{j} I^{1/2}$ introduces a size correction through an effective solvated diameter $d_{j}$, preventing the simplest limiting-law form from being used outside its range. The constants $A$ and $B$ package the solvent and temperature dependence of the theory.

> [!equation] Free energy magnitude from reversible cell potential
> 
> $$
> \begin{align*}
> & |\Delta G|=\text { charge passed × reversible potential difference }  \tag{2.1.20}\\
> & |\Delta G|=n F|E| \tag{2.1.21}
> \end{align*}
> $$
> 
> 

This equation says that, in the reversible limit, the magnitude of the Gibbs free energy change is the electrical energy delivered when a charge passes through a potential difference.

The chunk “charge passed” becomes $nF$ per mole of cell reaction: $n$ is the number of electrons transferred per stoichiometric reaction event, and $F$ is the charge per mole of electrons. The chunk “reversible potential difference” is the equilibrium potential difference during reversible discharge; multiplying charge (coulombs) by potential (volts) produces energy (joules). The absolute values indicate that this is a magnitude statement, separated from the separate issue of sign conventions for $\Delta G$ and for the measured/defined potentials.

> [!equation] Free energy–emf relation (reaction emf, signed)
> 
> $$
> \begin{equation*}
> \Delta G=-n F E_{\mathrm{rxn}} \tag{2.1.25}
> \end{equation*}
> $$
> 

This equation says that the Gibbs free energy change for the written cell reaction is proportional to the reaction emf, with a negative sign that enforces the thermodynamic criterion for spontaneity.

The chunk $nF$ is the charge transferred per mole of reaction as written (moles of electrons times Faraday’s constant). The chunk $E_{\mathrm{rxn}}$ is the emf assigned to that written reaction via the cell-schematic convention. The overall minus sign is what makes a positive $E_{\mathrm{rxn}}$ correspond to a negative $\Delta G$ (spontaneous direction at constant $T$ and $P$).

> [!Equation] Generic electrode half-reaction
> 
> $$
> \begin{equation*}
> \mathrm{O}+n e \rightleftharpoons \mathrm{R} \tag{2.1.16}
> \end{equation*}
> $$
> 

This equation says that an electrode process can be represented generically as interconversion between an oxidized form $\mathrm{O}$ and a reduced form $\mathrm{R}$ by transfer of $n$ electrons.

The chunk “$+n e$” encodes the electron stoichiometry: writing electrons on the left corresponds to the reduction direction (gain of electrons by $\mathrm{O}$ to form $\mathrm{R}$), while writing the reverse corresponds to oxidation. This compact form is what the Nernst equation and related thermodynamic relations refer to when they connect potential to composition.

> [!equation] Nernst equation (concentration form; formal potential)
> 
> $$
> \begin{equation*}
> E=E^{0^{\prime}}+\frac{R T}{n F} \ln \frac{C_{\mathrm{O}}}{C_{\mathrm{R}}} \tag{2.1.15}
> \end{equation*}
> 
> $$
> 
> 

This equation says that the electrode potential $E$ of the $\mathrm{O}/\mathrm{R}$ couple shifts away from the reference potential $E^{0^{\prime}}$ in a way that depends logarithmically on the oxidized-to-reduced concentration ratio.

The correction term
$$
\frac{R T}{n F}\ln\!\left(\frac{C_{\mathrm{O}}}{C_{\mathrm{R}}}\right)
$$
naturally separates into two chunks. The prefactor $\frac{R T}{n F}$ sets the thermal scale of the potential response: $R T$ is thermal energy per mole, dividing by $F$ converts that energy scale into volts, and dividing by $n$ accounts for how many electrons are transferred per reaction event. The logarithm $\ln\!\left(\frac{C_{\mathrm{O}}}{C_{\mathrm{R}}}\right)$ is a dimensionless measure of composition: increasing $C_{\mathrm{O}}$ relative to $C_{\mathrm{R}}$ increases $E$ in this form, while increasing $C_{\mathrm{R}}$ decreases $E$.

As written here, this is a concentration-form approximation to the activity-based Nernst relation; its accuracy depends on whether activities can be treated as proportional to concentrations under the conditions of interest.

> [!equation] Nernst equation (general activity form)
> $$
> \begin{equation*}
> E=E^{0}+\frac{R T}{n F} \ln \frac{\prod_{j}^{\text {O side }} a_{j}^{\nu_{j}}}{\prod_{j}^{\text {R side }} a_{j}^{\nu_{j}}} \tag{2.1.43}
> \end{equation*}
> $$

This equation says that an electrode potential is determined by a reference potential $E^{0}$ plus a thermal factor times the logarithm of an activity-based reaction quotient for the half-reaction written in the reduction direction.

The prefactor $\frac{RT}{nF}$ is the universal thermal-to-electrical conversion scale, as in any Nernst relation. The fraction inside the logarithm is the reaction quotient $Q$ written in terms of activities: the numerator multiplies activities of all participants on the oxidized (“O side”) side, each raised to its stoichiometric power $\nu_{j}$, and the denominator does the same for participants on the reduced (“R side”) side. Because activities are unitless, the entire logarithm argument is unitless, as required.

> [!equation] Reversible hydrogen electrode potential (activity form)
> 
> $$
> \begin{equation*}
> E_{\mathrm{RHE}}=E_{\mathrm{H}^{+} / \mathrm{H}_{2}}^{0}+\frac{2.303 R T}{2 F} \log \frac{a_{\mathrm{H}^{+}}^{2}}{a_{\mathrm{H}_{2}}} \tag{2.1.59}
> \end{equation*}
> $$
> 

This equation says that the potential of a reversible hydrogen electrode (RHE) follows the Nernst dependence for the hydrogen half-reaction, expressed in terms of the activities of $\mathrm{H}^{+}$ and $\mathrm{H}_{2}$.

The chunk $E_{\mathrm{H}^{+} / \mathrm{H}_{2}}^{0}$ is the standard potential for the $\mathrm{H}^{+}/\mathrm{H}_{2}$ couple under the chosen standard states. The prefactor $\frac{2.303RT}{2F}$ indicates (i) the $n=2$ electron stoichiometry for $\mathrm{H}_{2}$ formation/consumption and (ii) that the logarithm is base-10 (the $2.303$ converts between $\ln$ and $\log_{10}$). The log argument $\frac{a_{\mathrm{H}^{+}}^{2}}{a_{\mathrm{H}_{2}}}$ is the activity-based reaction quotient for $2\mathrm{H}^{+}+2e\rightleftharpoons \mathrm{H}_{2}$.

> [!equation] Reversible hydrogen electrode potential (ideal-gas form)
> 
> $$
> \begin{equation*}
> E_{\mathrm{RHE}}=-\frac{2.303 R T}{F} p \mathrm{H}-\frac{2.303 R T}{2 F} \ln \frac{P_{\mathrm{H}_{2}}}{P^{0}} \quad(\mathrm{~V} \text { vs. } \mathrm{NHE}) \tag{2.1.60}
> \end{equation*}
> $$
> 

This equation says that, when hydrogen is treated as an ideal gas and acidity is summarized by pH, the RHE potential varies (approximately) linearly with pH and with the logarithm of hydrogen partial pressure.

The chunk $-\frac{2.303RT}{F}\,p\mathrm{H}$ is the familiar pH-dependent shift: increasing pH (lower $\mathrm{H}^{+}$ activity) drives the potential more negative by a thermal slope set by $2.303RT/F$. The chunk involving $\frac{P_{\mathrm{H}_{2}}}{P^{0}}$ is the gas-pressure correction written as a dimensionless pressure ratio; its prefactor includes the factor of $1/2$ reflecting the $n=2$ electron stoichiometry of the hydrogen couple.

> [!equation] Volume ionic strength
> $$
> \begin{equation*}
> I=\frac{1}{2} \sum_{\mathrm{m}} z_{\mathrm{m}}^{2} C_{\mathrm{m}} \tag{2.1.36}
> \end{equation*}
> $$

This equation says that the ionic strength $I$ of a solution is a concentration-weighted measure of the total charge content, where each ionic species contributes in proportion to the square of its charge.

The chunk $z_{\mathrm{m}}^{2}$ gives high-valence ions disproportionate weight (a $2+$ ion contributes four times as much as a $1+$ ion at the same concentration). The sum runs over all ionic species present, and the factor of $\tfrac{1}{2}$ is part of the standard definition that prevents double-counting the overall contribution of positive and negative charge carriers in typical electrolyte mixtures.

