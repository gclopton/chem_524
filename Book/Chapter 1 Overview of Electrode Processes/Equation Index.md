# Chapter 1 Equation Index

This index collects equations from equation callouts in Chapter 1. Equations are listed in alphabetical order by their callout titles.

> [!equation] Capacitor relation for interfacial charging
> $$
> q = C\,E
> $$

This equation says that the charge stored at an interface (treated as a capacitor) is proportional to the potential difference across the interface, with proportionality constant given by the capacitance.

The chunk $C$ encodes how much charge is required per volt to change the interfacial potential. The chunk $E$ is the potential difference across the interface; multiplying farads (coulombs per volt) by volts yields coulombs, consistent with $q$.

> [!equation] Charging current during a linear potential sweep
> $$
> \begin{equation*}
> i= \pm v C_{\mathrm{d}}\left(1-e^{-t / R_{\mathrm{u}} C_{\mathrm{d}}}\right) \quad(+ \text { for neg. scan, }- \text { for pos. scan }) \tag{1.6.23}
> \end{equation*}
> $$

This equation says that, when only double-layer charging occurs, a linear potential sweep produces a charging current that approaches a steady magnitude set by the sweep rate $v$ and the double-layer capacitance $C_{\mathrm{d}}$, after transients governed by the cell time constant $R_{\mathrm{u}}C_{\mathrm{d}}$.

The chunk $\left(1-e^{-t/(R_{\mathrm{u}}C_{\mathrm{d}})}\right)$ captures the approach to steady state; the chunk $\pm vC_{\mathrm{d}}$ is the limiting (long-time) current magnitude, with sign determined by the sweep direction under the stated convention.

> [!equation] Charging current for a potential step (RC circuit)
> $$
> \begin{equation*}
> i=\frac{E}{R_{\mathrm{s}}} e^{-t / R_{\mathrm{s}} C_{\mathrm{d}}} \tag{1.6.6}
> \end{equation*}
> $$

This equation says that, for an RC charging event, the current following a potential step decays exponentially in time, with initial magnitude $E/R_{\mathrm{s}}$ and time constant $R_{\mathrm{s}}C_{\mathrm{d}}$.

The chunk $E/R_{\mathrm{s}}$ is the initial Ohmic current that would flow if the capacitor were uncharged; the exponential factor encodes the progressive reduction of the driving voltage across the resistor as the capacitor charges.

> [!equation] Double-layer charge during a potential step (RC circuit)
> $$
> \begin{equation*}
> q=E C_{\mathrm{d}}\left[1-e^{-t / R_{\mathrm{s}} C_{\mathrm{d}}}\right] \tag{1.6.10}
> \end{equation*}
> $$

This equation says that, following a potential step, the charge accumulated in the double layer rises toward the limiting value $EC_{\mathrm{d}}$ with the same RC time constant that governs the corresponding charging current transient.

The chunk $EC_{\mathrm{d}}$ is the long-time (fully charged) value; the bracketed term shows how rapidly that value is approached as $t$ grows relative to $R_{\mathrm{s}}C_{\mathrm{d}}$.

> [!equation] Double-layer charge-density bookkeeping (metal vs. solution)
> $$
> \sigma^{\mathrm{S}}=\sigma^{\mathrm{i}}+\sigma^{\mathrm{d}}=-\sigma^{\mathrm{m}}
> $$

This equation says that the total excess charge density on the solution side of the interface, $\sigma^{\mathrm{S}}$, can be decomposed into an inner-layer (compact-layer) contribution $\sigma^{\mathrm{i}}$ and a diffuse-layer contribution $\sigma^{\mathrm{d}}$, and that the solution-side charge balances the metal-side charge density $\sigma^{\mathrm{m}}$ with equal magnitude and opposite sign.

The chunk $\sigma^{\mathrm{i}}+\sigma^{\mathrm{d}}$ is a partition of where the electrolyte charge resides; the equality to $-\sigma^{\mathrm{m}}$ is the interfacial charge-neutrality statement.

> [!equation] Faraday’s law (electrons from charge)
> $$
> n(e^-)=\frac{Q}{F}
> $$
> 
> $$
> N(e^-)=n(e^-)\,N_{\mathrm{A}}
> $$

This equation says that the amount of electron transfer is proportional to the charge passed: dividing charge $Q$ by Faraday’s constant $F$ gives moles of electrons, and multiplying by Avogadro’s number gives the corresponding number of electrons.

The chunk $Q/F$ is “charge in coulombs” divided by “coulombs per mole,” yielding moles. The chunk $n(e^-)N_{\mathrm{A}}$ converts moles of electrons into a particle count.

> [!equation] Hydrogen electrode half-reaction (written in reduction direction)
> $$
> 2\mathrm{H}^+ + 2e^- \rightleftharpoons \mathrm{H}_2
> $$

This equation is the hydrogen redox couple written in the reduction direction. It is the reference half-reaction underlying hydrogen-electrode potential scales and the context in which Nernst-equation dependence on acidity and hydrogen activity/pressure is discussed.

The chunk $2\mathrm{H}^+ + 2e^-$ encodes the two-electron stoichiometry; the direction written corresponds to reduction of protons to hydrogen gas.

> [!equation] Parallel-plate capacitance model
> $$
> C=\varepsilon\,\varepsilon_{0}\,\frac{A}{d}
> $$

This equation says that, in the parallel-plate approximation, capacitance increases with electrode area $A$ and dielectric permittivity $\varepsilon\varepsilon_0$, and decreases as the separation distance $d$ increases.

The chunk $\varepsilon\varepsilon_0$ captures material response (dielectric screening), while the geometric factor $A/d$ captures how much interfacial “plate area” is available per unit separation.

