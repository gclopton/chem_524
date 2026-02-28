# 21-19 The Nernst Equation

Standard electrode potentials, designated $E^{0}$, refer to standard-state conditions. These standard-state conditions are one molar solutions for ions and one atmosphere pressure for gases with all solids and liquids in their standard states at $25^{\circ} \mathrm{C}$. As any of the standard cells described earlier operates, and concentrations or pressures of reactants change, the observed cell voltage drops. Similarly, cells constructed with solution concentrations different from one molar, or gas pressures different from one atmosphere, cause the corresponding potentials to deviate from standard electrode potentials.

The Nernst equation is used to calculate electrode potentials and cell potentials for concentrations and partial pressures other than standard-state values.

> [!equation] Nernst equation (base-10 form)
> $$
> E=E^{0}-\frac{2.303 R T}{n F} \log Q
> $$

where
$E=$ potential under the nonstandard conditions
$E^{0}=$ standard potential
$R=$ gas constant, $8.314 \mathrm{~J} / \mathrm{mol} \cdot \mathrm{K}$
$T=$ absolute temperature in K
$n=$ number of moles of electrons transferred in the reaction or half-reaction
$F=$ faraday, $96,485 \mathrm{C} / \mathrm{mol} e^{-} \times 1 \mathrm{~J} /(\mathrm{V} \cdot \mathrm{C})=96,485 \mathrm{~J} / \mathrm{V} \cdot \mathrm{mol} e^{-}$
$Q=$ reaction quotient
The reaction quotient, $Q$, was introduced in Section 17-4. It involves a ratio of concentrations or pressures of products to those of reactants, each raised to the power indicated by the coefficient in the balanced equation. The $Q$ expression used in the Nernst equation is the thermodynamic reaction quotient; it can include $b o t h$ concentrations and pressures. Substituting these values into the Nernst equation at $25^{\circ} \mathrm{C}$ gives

> [!equation] Nernst equation at $25^{\circ}\mathrm{C}$ (base-10 form)
> $$
> E=E^{0}-\frac{0.0592}{n} \log Q
> $$

> [!note] Stop and Think
> Remember that we refer to thermodynamic standard-state conditions, not standard temperature and pressure as in gas law calculations.

In this equation, the expression following the minus sign represents how much the nonstandard conditions cause the electrode potential to deviate from its standard value, $E^{0}$. The Nernst equation is normally presented in terms of base-10 logarithms, as we will do in this text.

At $25^{\circ} \mathrm{C}$, the value of $\frac{2.303 R T}{F}$ is 0.0592; at any other temperature, this term must be recalculated. Can you show that this term has the units

Metallic Zn is a pure solid, so its concentration does not appear in $Q$.

The potential for this electrode is lower than $E^{0}$ for the standard $\mathrm{Fe}^{3+} / \mathrm{Fe}^{2+}$ electrode, in which both concentrations are 1 M . This should make qualitative sense to you from having studied LeChatelier's Principle. The more products that are present relative to reactants, the less the driving force (lower potential) to make more products.

In general, half-reactions for standard reduction potentials are written

$$
x \mathrm{Ox}+n e^{-} \longrightarrow y \mathrm{Red}
$$

"Ox" refers to the oxidized species and "Red" to the reduced species; $x$ and $y$ are their coefficients, respectively, in the balanced equation. The Nernst equation for any cathode half-cell (reduction half-reaction) is

> [!equation] Nernst equation (reduction half-reaction form, $25^{\\circ}\\mathrm{C}$)
> $$
> E=E^{0}-\frac{0.0592}{n} \log \frac{[\mathrm{Red}]^{y}}{[\mathrm{Ox}]^{x}}
> $$

For the familiar half-reaction involving metallic zinc and zinc ions,

$$
\mathrm{Zn}^{2+}+2 e^{-} \longrightarrow \mathrm{Zn} \quad E^{0}=-0.763 \mathrm{~V}
$$

the corresponding Nernst equation is

$$
E=E^{0}-\frac{0.0592}{2} \log \frac{1}{\left[\mathrm{Zn}^{2+}\right]} \quad \text { (for reduction) }
$$

We substitute the $E^{0}$ value into the equation to obtain

$$
E=-0.763 \mathrm{~V}-\frac{0.0592}{2} \log \frac{1}{\left[\mathrm{Zn}^{2+}\right]}
$$

> [!example] Example 21-5: Nernst equation for a half-cell reaction
> Calculate the potential, $E$, for the $\mathrm{Fe}^{3+} / \mathrm{Fe}^{2+}$ electrode when the concentration of $\mathrm{Fe}^{2+}$ is exactly five times that of $\mathrm{Fe}^{3+}$.

**Plan**

The Nernst equation lets us calculate potentials for concentrations other than one molar. The tabulation of standard reduction potentials gives us the value of $E^{0}$ for the reduction half-reaction. We use the balanced half-reaction and the given concentration ratio to calculate the value of $Q$. Then we substitute this into the Nernst equation, with $n$ equal to the number of moles of electrons involved in the half-reaction.

**Solution**

The reduction half-reaction is

$$
\mathrm{Fe}^{3+}+e^{-} \longrightarrow \mathrm{Fe}^{2+} \quad E^{0}=+0.771 \mathrm{~V}
$$

We are told that the concentration of $\mathrm{Fe}^{2+}$ is five times that of $\mathrm{Fe}^{3+}$, or $\left[\mathrm{Fe}^{2+}\right]=5\left[\mathrm{Fe}^{3+}\right]$. Calculating the value of $Q$,

$$
Q=\frac{[\mathrm{Red}]^{y}}{[\mathrm{Ox}]^{x}}=\frac{\left[\mathrm{Fe}^{2+}\right]}{\left[\mathrm{Fe}^{3+}\right]}=\frac{5\left[\mathrm{Fe}^{3+}\right]}{\left[\mathrm{Fe}^{3+}\right]}=5
$$

The balanced half-reaction shows one mole of electrons, or $n=1$. Putting values into the Nernst equation,

$$
\begin{aligned}
E & =E^{0}-\frac{0.0592}{n} \log Q=+0.771-\frac{0.0592}{1} \log 5=(+0.771-0.041) \mathrm{V} \\
& =+0.730 \mathrm{~V}
\end{aligned}
$$

**You should now work Exercise 82.**

> [!example] Example 21-6: Nernst equation for an overall cell reaction
> A cell is constructed at $25^{\circ} \mathrm{C}$ as follows. One half-cell consists of the $\mathrm{Fe}^{3+} / \mathrm{Fe}^{2+}$ couple in which $\left[\mathrm{Fe}^{3+}\right]=1.00 M$ and $\left[\mathrm{Fe}^{2+}\right]=0.100 M$; the other involves the $\mathrm{MnO}_{4}{ }^{-} / \mathrm{Mn}^{2+}$ couple in acidic solution in which $\left[\mathrm{MnO}_{4}{ }^{-}\right]=1.00 \times 10^{-2} M$, $\left[\mathrm{Mn}^{2+}\right]=1.00 \times 10^{-4} M$, and $\left[\mathrm{H}^{+}\right]=1.00 \times 10^{-3} M$. (a) Find the electrode potential for each half-cell with these concentrations, and (b) calculate the overall cell potential.

**Plan**

(a) We can apply the Nernst equation to find the reduction potential of each half-cell with the stated concentrations. (b) As in Section 21-15, we write the half-reaction with the more positive potential (after correction) along with its potential. We reverse the other halfreaction and change the sign of its $E$ value. We balance the electron transfer and then add the half-reactions and their potentials to find the overall cell potential.

**Solution**

(a) For the $\mathrm{MnO}_{4}{ }^{-} / \mathrm{Mn}^{2+}$ half-cell as a reduction,

$$
\begin{aligned}
& \mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 e^{-} \longrightarrow \mathrm{Mn}^{2+}+\mathrm{H}_{2} \mathrm{O} \quad E^{0}=+1.507 \mathrm{~V} \\
& E=E^{0}-\frac{0.0592}{n} \log \frac{\left[\mathrm{Mn}^{2+}\right]}{\left[\mathrm{MnO}_{4}^{-}\right]\left[\mathrm{H}^{+}\right]^{8}} \\
&=+1.507 \mathrm{~V}-\frac{0.0592}{5} \log \frac{1.00 \times 10^{-4}}{\left(1.00 \times 10^{-2}\right)\left(1.00 \times 10^{-3}\right)^{8}} \\
&=+1.507 \mathrm{~V}-\frac{0.0592}{5} \log \left(1.00 \times 10^{22}\right)=+1.507 \mathrm{~V}-\frac{0.0592}{5}(22.0) \\
&=+1.246 \mathrm{~V}
\end{aligned}
$$

(b) For the $\mathrm{Fe}^{3+} / \mathrm{Fe}^{2+}$ half-cell as a reduction,

$$
\begin{aligned}
& \mathrm{Fe}^{3+}+e^{-} \longrightarrow \mathrm{Fe}^{2+} \quad E^{0}=+0.771 \mathrm{~V} \\
& E=E^{0}-\frac{0.0592}{n} \log \frac{\left[\mathrm{Fe}^{2+}\right]}{\left[\mathrm{Fe}^{3+}\right]}=+0.771 \mathrm{~V}-\frac{0.0592}{1} \log \frac{0.100}{1.00} \\
&=+0.771 \mathrm{~V}-\frac{0.0592}{1} \log (0.100)=+0.771 \mathrm{~V}-\frac{0.0592}{1}(-1.00) \\
&=+0.830 \mathrm{~V}
\end{aligned}
$$

The corrected potential for the $\mathrm{MnO}_{4}{ }^{-} / \mathrm{Mn}^{2+}$ half-cell is greater than that for the $\mathrm{Fe}^{3+} / \mathrm{Fe}^{2+}$ half-cell, so we reverse the latter, balance the electron transfer, and add.

$$
\begin{array}{cr}
\mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 e^{-} \longrightarrow \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O} & \frac{\boldsymbol{E} \text { (corrected) }}{+1.246 \mathrm{~V}} \\
5\left(\mathrm{Fe}^{2+} \longrightarrow \mathrm{Fe}^{3+}+e^{-}\right) & -0.830 \mathrm{~V} \\
\hline \mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 \mathrm{Fe}^{2+} \longrightarrow \mathrm{Mn}^{2+} 4 \mathrm{H}_{2} \mathrm{O}+5 \mathrm{Fe}^{3+} & E_{\text {cell }}=0.416 \mathrm{~V}
\end{array}
$$

The cell in Example 21-6 can be represented in shorthand notation as
$\mathrm{Pt}\left|\mathrm{Fe}^{2+}(0.100 M), \mathrm{Fe}^{3+}(1.00 M) \| \mathrm{H}^{+}\left(1.00 \times 10^{-3} M\right), \mathrm{MnO}_{4}{ }^{-}\left(1.00 \times 10^{-2} M\right), \mathrm{Mn}^{2+}\left(1.00 \times 10^{-4} M\right)\right| \mathrm{Pt}$
The reaction as written is product-favored (spontaneous) under the stated conditions, with a potential of +0.416 volt when the cell starts operation. As the cell discharges and current flows, the product concentrations, $\left[\mathrm{Mn}^{2+}\right]$ and $\left[\mathrm{Fe}^{3+}\right]$, increase. At the same time, reactant concentrations, $\left[\mathrm{MnO}_{4}{ }^{-}\right],\left[\mathrm{H}^{+}\right]$, and $\left[\mathrm{Fe}^{2+}\right]$, decrease. This increases the magnitude of $\log Q_{\text {cell }}$, so the correction factor becomes more negative. Thus, the overall $E_{\text {cell }}$ decreases (the reaction becomes less favorable). Eventually the cell potential approaches zero (equilib-

Can you write the shorthand notation for this cell?

When evaluating $Q$ in the Nernst equation, remember that (a) molar concentrations are used for dissolved species, and (b) partial pressures of gases are expressed in atmospheres. Units are omitted.

Now solve Example 21-6 by applying the Nernst equation to the overall cell reaction to determine the cell potential.

We can also find the cell potential for a nonstandard cell by first finding $E^{0}{ }_{\text {cell }}$ for the overall standard cell reaction, and then using the Nernst equation to correct for nonstandard concentrations. The next example illustrates this approach.

> [!example] Example 21-7: Nernst equation for an overall cell reaction
> A cell is constructed at $25^{\circ} \mathrm{C}$ as follows. One half-cell consists of a chlorine/chloride, $\mathrm{Cl}_{2} / \mathrm{Cl}^{-}$, electrode with the partial pressure of $\mathrm{Cl}_{2}=0.100 \mathrm{~atm}$ and $\left[\mathrm{Cl}^{-}\right]=0.100 \mathrm{M}$. The other half-cell involves the $\mathrm{MnO}_{4}{ }^{-} / \mathrm{Mn}^{2+}$ couple in acidic solution with $\left[\mathrm{MnO}_{4}{ }^{-}\right]=0.100 M,\left[\mathrm{Mn}^{2+}\right]=0.100 M$, and $\left[\mathrm{H}^{+}\right]=0.100 M$. Apply the Nernst equation to the overall cell reaction to determine the cell potential for this cell.

**Plan**

First we determine the overall cell reaction and its standard cell potential, $E_{\text {cell }}^{0}$, as in Examples 21-3 and 21-4. Then we apply the Nernst equation to the overall cell.

**Solution**

The $\mathrm{MnO}_{4}{ }^{-} / \mathrm{Mn}^{2+}$ half-reaction has the more positive reduction potential, so we write it first. Then we write the $\mathrm{Cl}_{2} / \mathrm{Cl}^{-}$half-reaction as an oxidation, balance the electron transfer, and add the two half-reactions and their potentials to obtain the overall cell reaction and its $E_{\text {cell }}^{0}$.

| $2\left(\mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 e^{-}\right.$ | $\left.\longrightarrow \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O}\right)$ | $\frac{\boldsymbol{E}^{0}}{+1.507 \mathrm{~V}}$ |
| :---: | ---: | :--- |
| $5\left(2 \mathrm{Cl}^{-}\right.$ | $\left.\longrightarrow \mathrm{Cl}_{2}+2 e^{-}\right)$ | -1.360 V |
| $2 \mathrm{MnO}_{4}^{-}+16 \mathrm{H}^{+}+10 \mathrm{Cl}^{-}$ | $\longrightarrow 2 \mathrm{Mn}^{2+}+8 \mathrm{H}_{2} \mathrm{O}+5 \mathrm{Cl}_{2}$ | $E_{\text {cell }}^{0}=+0.147 \mathrm{~V}$ |

In the overall reaction, $n=10$. We then apply the Nernst equation to this overall reaction by substituting appropriate concentration and partial pressure values. Because $\mathrm{Cl}_{2}$ is a gaseous component, its term in the Nernst equation involves its partial pressure, $P_{\mathrm{Cl}_{2}}$, in atm.

$$
\begin{aligned}
E_{\text {cell }} & =E_{\text {cell }}^{0}-\frac{0.0592}{n} \log \frac{\left[\mathrm{Mn}^{2+}\right]^{2}\left(P_{\mathrm{Cl}_{2}}\right)^{5}}{\left[\mathrm{MnO}_{4}^{-}\right]^{2}\left[\mathrm{H}^{+}\right]^{16}\left[\mathrm{Cl}^{-}\right]^{10}} \\
& =0.147 \mathrm{~V}-\frac{0.0592}{10} \log \frac{(0.100)^{2}(0.100)^{5}}{(0.100)^{2}(0.100)^{16}(0.100)^{10}} \\
& =0.147 \mathrm{~V}-\frac{0.0592}{10} \log \left(1.00 \times 10^{21}\right) \\
& =0.147 \mathrm{~V}-\frac{0.0592}{10}(21.00)=0.017 \mathrm{~V}
\end{aligned}
$$

**You should now work Exercises 84 and 90.**

The method illustrated in Example 21-7, applying the Nernst equation to the overall cell reaction, usually involves less calculation than correcting the separate half-reactions as in Example 21-6. We interpret our results as follows: The positive overall cell potentials in Examples 21-6 and 21-7 tell us that each of these cell reactions is spontaneous in the direction written for the concentrations given. If the resulting cell potential were negative, the reverse reaction would be favored at those concentrations. We could then reverse the equation for the overall cell reaction and change the sign of its potential to describe the spontaneous operation of the cell.

> [!tip] Problem-Solving Tip: Be careful about the value of $n$
> How do you know what value of $n$ to use? $n$ must be the number of moles of electrons transferred in the **balanced** process to which you are applying the Nernst equation.
> 
> 1. For a **half-reaction**, $n$ is the number of moles of electrons in that half-reaction. In Example 21-6 we applied the Nernst equation to each half-reaction separately, so we used $n=5$ for
> 
>    $$
>    \mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 e^{-} \longrightarrow \mathrm{Mn}^{2+}+\mathrm{H}_{2} \mathrm{O}
>    $$
> 
>    and we used $n=1$ for
> 
>    $$
>    \mathrm{Fe}^{3+}+e^{-} \longrightarrow \mathrm{Fe}^{2+}
>    $$
> 
> 2. For an **overall reaction**, $n$ is the total number of moles of electrons transferred in the balanced overall reaction. In Example 21-7, 10 moles of electrons are transferred, so $n=10$.