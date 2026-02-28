# 21-21 The Relationship of $E_{\text {cell }}^{0}$ to $\Delta G^{0}$ and $K$

In Section 17-12 we studied the relationship between the standard Gibbs free energy change, $\Delta G^{0}$, and the thermodynamic equilibrium constant, $K$.

> [!equation] Gibbs energy and equilibrium constant
> $$
> \Delta G^{0}=-R T \ln K
> $$

There is also a simple relationship between $\Delta G^{0}$ and the standard cell potential, $E_{\text {cell }}^{0}$, for a redox reaction (reactants and products in standard states).

> [!equation] Gibbs energy and standard cell potential
> $$
> \Delta G^{0}=-n F E_{\text {cell }}^{0}
> $$

$\Delta G^{0}$ can be thought of as the negative of the maximum electrical work that can be obtained from a redox reaction. In this equation, $n$ is the number of moles of electrons transferred in the overall process ( $\mathrm{mol} e^{-} / \mathrm{mol} \mathrm{rxn}$ ), and $F$ is the faraday, $96,485 \mathrm{~J} / \mathrm{V} \cdot \mathrm{mol} e^{-}$.

If any one of the three quantities $\Delta G^{0}$, $K$, and $E_{\text {cell }}^{0}$ is known, the other two can be calculated. Combining the two expressions for $\Delta G^{0}$ gives the direct relationship between $K$ and $E_{\text {cell }}^{0}$.

> [!equation] Standard cell potential and equilibrium constant
> $$
> n F E_{\text {cell }}^{0}=R T \ln K
> $$
> 
> $$
> E_{\text {cell }}^{0}=\frac{R T}{n F}\,\ln K
> $$
> 
> $$
> \ln K=\frac{n F}{R T}\,E_{\text {cell }}^{0}
> $$

> [!figure]
> ![](https://cdn.mathpix.com/cropped/c942e4e5-a003-4e4b-91e8-7898f585fef6-33.jpg?height=290&width=494&top_left_y=1382&top_left_x=111)
> Diagram: combining $\Delta G^{0}=-R T \ln K$ and $\Delta G^{0}=-n F E_{\text {cell }}^{0}$ to relate $K$ and $E_{\text {cell }}^{0}$.

| Forward reaction | $\Delta G^{0}$ | $K$ | $E_{\text {cell }}^{0}$ |
| :--- | :---: | :---: | :---: |
| product-favored (spontaneous) | $-$ | $>1$ | $+$ |
| at equilibrium | $0$ | $1$ | $0$ |
| reactant-favored (nonspontaneous) | $+$ | $<1$ | $-$ |

> [!example] Example 21-9: Calculating $\Delta G^{0}$ from cell potentials
> Use tabulated standard electrode potentials to calculate the standard Gibbs free energy change, $\Delta G^{0}$ (in $\mathrm{J}\,\mathrm{mol}^{-1}$ of reaction), at $25^{\circ} \mathrm{C}$ for the following reaction:
> 
> $$
> 3 \mathrm{Sn}^{4+}+2 \mathrm{Cr} \longrightarrow 3 \mathrm{Sn}^{2+}+2 \mathrm{Cr}^{3+}
> $$

**Plan**

We evaluate the standard cell potential as we have done before. Then we apply the relationship $\Delta G^{0}=-n F E_{\text {cell }}^{0}$.

**Solution**

The standard reduction potential for the $\mathrm{Sn}^{4+} / \mathrm{Sn}^{2+}$ couple is +0.15 volt; that for the $\mathrm{Cr}^{3+} / \mathrm{Cr}$ couple is -0.74 volt. The equation for the reaction shows Cr being oxidized to $\mathrm{Cr}^{3+}$, so the sign of the $E^{0}$ value for the $\mathrm{Cr}^{3+} / \mathrm{Cr}$ couple is reversed. The overall reaction, the sum of the two half-reactions, has a cell potential equal to the sum of the two halfreaction potentials.

$$
\begin{array}{rr}
\mathrm{Sn}^{4+}+2 e^{-} \longrightarrow \mathrm{Sn}^{2+} & +0.15 \mathrm{~V} \\
\mathrm{Cr} \longrightarrow \mathrm{Cr}^{3+}+3 e^{-} & +0.74 \mathrm{~V} \\
\hline 3 \mathrm{Sn}^{4+}+2 \mathrm{Cr} \longrightarrow 3 \mathrm{Sn}^{2+}+2 \mathrm{Cr}^{3+} & E_{\text {cell }}^{0}=+0.89 \mathrm{~V}
\end{array}
$$

The positive value of $E_{\text {cell }}^{0}$ indicates that the forward reaction is spontaneous.

$$
\begin{aligned}
\Delta G^{0} & =-n F E_{\text {cell }}^{0}=-\left(\frac{6 \mathrm{~mol} e^{-}}{\mathrm{mol} \mathrm{rxn}}\right)\left(\frac{9.65 \times 10^{4} \mathrm{~J}}{\mathrm{~V} \cdot \mathrm{~mol} e^{-}}\right)(+0.89 \mathrm{~V}) \\
& =-5.2 \times 10^{5} \mathrm{~J} / \mathrm{mol} \mathrm{rxn} \text { or }-5.2 \times 10^{2} \mathrm{~kJ} / \mathrm{mol} \mathrm{rxn}
\end{aligned}
$$

**You should now work Exercise 101.**

> [!example] Example 21-10: Calculating $K$ from cell potentials
> Use the standard cell potential to calculate the value of the equilibrium constant, $K$, at $25^{\circ} \mathrm{C}$ for the following reaction:
> 
> $$
> 2 \mathrm{Cu}+\mathrm{PtCl}_{6}^{2-} \longrightarrow 2 \mathrm{Cu}^{+}+\mathrm{PtCl}_{4}^{2-}+2 \mathrm{Cl}^{-}
> $$

**Plan**

We calculate $E_{\text {cell }}^{0}$ for the reaction as written. Then we use it to calculate $K$.

**Solution**

First we find the appropriate half-reactions. As the equation is written, Cu is oxidized to $\mathrm{Cu}^{+}$, so we write the $\mathrm{Cu}^{+} / \mathrm{Cu}$ couple as an oxidation and reverse the sign of its tabulated $E^{0}$ value. We balance the electron transfer and then add the half-reactions. The resulting $E_{\text {cell }}^{0}$ value can be used to calculate the equilibrium constant, $K$, for the reaction as written.

$$
\begin{array}{rrl}
2\left(\mathrm{Cu} \longrightarrow \mathrm{Cu}^{+}+e^{-}\right) & -(+0.521 \mathrm{~V}) \\
\mathrm{PtCl}_{6}^{2-}+2 e^{-} \longrightarrow \mathrm{PtCl}_{4}^{2-}+2 \mathrm{Cl}^{-} & +0.68 \mathrm{~V} \\
\hline 2 \mathrm{Cu}+\mathrm{PtCl}_{6}^{2-} \longrightarrow 2 \mathrm{Cu}^{+}+\mathrm{PtCl}_{4}^{2-}+2 \mathrm{Cl}^{-} & E_{\text {cell }}^{0}=+0.16 \mathrm{~V}
\end{array}
$$

Then we calculate $K$.

$$
\begin{aligned}
\ln K & =\frac{n F E_{\text {cell }}^{0}}{R T}=\frac{(2)\left(9.65 \times 10^{4} \mathrm{~J} / \mathrm{V} \cdot \mathrm{~mol}\right)(+0.16 \mathrm{~V})}{(8.314 \mathrm{~J} / \mathrm{mol} \cdot \mathrm{~K})(298 \mathrm{~K})}=12.5 \\
K & =e^{12.5}=2.7 \times 10^{5}
\end{aligned}
$$

At equilibrium, $K=\frac{\left[\mathrm{Cu}^{+}\right]^{2}\left[\mathrm{PtCl}_{4}{ }^{2-}\right]\left[\mathrm{Cl}^{-}\right]^{2}}{\left[\mathrm{PtCl}_{6}{ }^{2-}\right]}=2.7 \times 10^{5}$.
The forward reaction is product-favored (spontaneous), and the equilibrium lies far to the right.

> [!note] Stop and Think
> The negative value of $\Delta G^{0}$ tells us that the standard reaction is product-favored (spontaneous), consistent with the positive value of $E_{\text {cell }}^{0}$. This tells us nothing about how fast the reaction would occur.

> [!note] Stop and Think
> As the problem is stated, we keep the equation as written and accept the corresponding sign of $E_{\text {cell }}^{0}$. A negative value of $E_{\text {cell }}^{0}$ would lead to $K<1$ for the reaction as written.

We use batteries as portable sources of electrical energy in many ways-in flashlights, cell phones, notebook computers, calculators, automobiles, etc. A battery is a voltaic cell (or a set of voltaic cells coupled together) that has been designed for practical use.

## Primary Voltaic Cells

As any voltaic cell produces current (discharges), chemicals are consumed. Primary voltaic cells cannot be "recharged." Once the chemicals have been consumed, further chemical action is not possible. The electrolytes or electrodes (or both) cannot be regenerated by reversing the current flow through the cell using an external direct current source. The most familiar examples of primary voltaic cells are the ordinary "dry" cells that are used as energy sources in flashlights and other small appliances.