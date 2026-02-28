# 21-20 Using Electrochemical Cells to Determine Concentrations

In Section 21-19, we used known concentrations to predict cell voltage. We can reverse this reasoning and apply the same ideas to measure the voltage of a cell and then use the Nernst equation to solve for an unknown concentration. The following example illustrates such an application.

> [!example] Example 21-8: Using the Nernst equation to find an unknown concentration
> We construct an electrochemical cell at $25^{\circ} \mathrm{C}$ as follows. One half-cell is a standard $\mathrm{Zn}^{2+} / \mathrm{Zn}$ cell, that is, a strip of zinc immersed in a $1.00 M \mathrm{Zn}^{2+}$ solution; the other is a nonstandard hydrogen electrode in which a platinum electrode is immersed in a solution of unknown hydrogen ion concentration with gaseous hydrogen bubbling through it at a pressure of 1.000 atm. The observed cell voltage is 0.522 V. (a) Calculate the value of the reaction quotient $Q$. (b) Calculate $\left[\mathrm{H}^{+}\right]$ in the second half-cell. (c) Determine the pH of the solution in the second half-cell.

**Plan**

We saw in Section 21-12 that the zinc-hydrogen cell operated with oxidation at the zinc electrode and reduction at the hydrogen electrode, with a standard cell potential of 0.763 V .

$$
\text { overall: } \quad \mathrm{Zn}+2 \mathrm{H}^{+} \longrightarrow \mathrm{Zn}^{2+}+\mathrm{H}_{2} \quad E_{\text {cell }}^{0}=0.763 \mathrm{~V}
$$

(a) We rearrange the Nernst equation to solve for the reaction quotient, $Q$, from the measured cell voltage with $n=2$. (b) We substitute concentrations and partial pressures in the expression for $Q$. Then we can solve for the only unknown, $\left[\mathrm{H}^{+}\right]$. (c) The pH can be determined from the [ $\mathrm{H}^{+}$] determined in Part (b).

**Solution**

(a)

$$
E_{\mathrm{cell}}=E_{\mathrm{cell}}^{0}-\frac{0.0592}{n} \log Q
$$

Substituting and solving for $Q$,

$$
\begin{aligned}
0.522 \mathrm{~V} & =0.763 \mathrm{~V}-\frac{0.0592}{2} \log Q \\
\frac{0.0592 \mathrm{~V}}{2} \log Q & =(0.763-0.522) \mathrm{V}=0.241 \mathrm{~V} \\
\log Q & =\frac{(2)(0.241 \mathrm{~V})}{0.0592 \mathrm{~V}}=8.14
\end{aligned}
$$

This cell is similar to the zinchydrogen cell that we discussed in Section 21-12, except that the hydrogen concentration is not (necessarily) 1.00 M .
![](https://cdn.mathpix.com/cropped/c942e4e5-a003-4e4b-91e8-7898f585fef6-30.jpg?height=640&width=454&top_left_y=1770&top_left_x=1285)
(b) We write the expression for $Q$ from the balanced overall equation, and solve for $\left[\mathrm{H}^{+}\right]$.

$$
\begin{aligned}
Q & =\frac{\left[\mathrm{Zn}^{2+}\right] P_{\mathrm{H}_{2}}}{\left[\mathrm{H}^{+}\right]^{2}} \\
{\left[\mathrm{H}^{+}\right]^{2} } & =\frac{\left[\mathrm{Zn}^{2+}\right] P_{\mathrm{H}_{2}}}{Q}=\frac{(1.00)(1.00)}{1.4 \times 10^{8}}=7.1 \times 10^{-9} \\
{\left[\mathrm{H}^{+}\right] } & =8.4 \times 10^{-5} M
\end{aligned}
$$

(c)

$$
\mathrm{pH}=-\log \left[\mathrm{H}^{+}\right]=-\log \left(8.4 \times 10^{-5}\right)=4.08
$$

**You should now work Exercises 85 and 86.**

A pH meter contains a voltaic cell, such as that in Example 21-8, that can be used to measure the $\left[\mathrm{H}^{+}\right]$concentration and thus the pH of an unknown solution. It is inconvenient to bubble hydrogen gas at a controlled pressure through a hydrogen electrode, so the routine use of this electrode in many environments is not practical. A typical commercial pH meter (Figure 21-14) incorporates a miniaturized pair of electrodes that are more portable and less fragile. One of these electrodes is a glass electrode, usually consisting of an AgCl -coated silver wire in contact with an HCl solution of known concentration (usually $1.00 M$ ) in a thin-walled glass bulb (Figure 21-14a). A saturated calomel electrode is often used as the second half-cell (reference electrode). This consists of a platinum wire in contact with a paste of liquid mercury and solid mercury(I) chloride, $\mathrm{Hg}_{2} \mathrm{Cl}_{2}(\mathrm{~s})$, all immersed in a saturated solution of potassium chloride, KCl . When the glass electrode is placed in a solution, a potential is developed across the thin glass membrane; this potential depends on the [ $\mathrm{H}^{+}$] concentration, and hence on the pH . The overall voltage of this cell thus measures the pH of the solution in contact with the glass electrode. Each change of one pH unit causes a voltage change of 0.0592 volts.

> [!figure]
> ![](https://cdn.mathpix.com/cropped/c942e4e5-a003-4e4b-91e8-7898f585fef6-31.jpg?height=806&width=1603&top_left_y=1450&top_left_x=141)
> Figure 21-14 The workings of a commercial pH meter. (a) The glass electrode (left) is a $\mathrm{Ag}(\mathrm{s}) / \mathrm{AgCl}(\mathrm{s})$ half-cell immersed in a standard HCl solution that is enclosed by a thin glass membrane. This electrode develops a potential that is sensitive to the external pH relative to that in the internal HCl standard solution. The saturated calomel electrode is the reference electrode. (b) A portable pH meter


The pH meter is designed to measure very small voltages, and its display is calibrated to give a direct readout of the pH of the solution. Meters of this general design have many routine but important applications in medicine, chemistry, biology, agriculture, environmental analysis, and numerous other areas. Glass electrodes can be made small enough to be implanted into blood vessels or even individual living cells.

Electrochemical procedures that use the principles illustrated here provide a convenient method for making many concentration measurements.

## Enrichment Concentration Cells

As we have seen, different concentrations of ions in a half-cell result in different half-cell potentials. We can use this idea to construct a concentration cell, in which both halfcells are composed of the same species, but in different ion concentrations. Suppose we set up such a cell using the $\mathrm{Cu}^{2+} / \mathrm{Cu}$ half-cell that we introduced in Section 21-9. We put copper electrodes into two aqueous solutions, one that is $0.10 M \mathrm{CuSO}_{4}$ and another that is $1.00 M \mathrm{CuSO}_{4}$. To complete the cell construction, we connect the two electrodes with a wire and join the two solutions with a salt bridge as usual (Figure 21-15). Now the relevant standard reduction half-reaction in either half-cell is

$$
\mathrm{Cu}^{2+}+2 e^{-} \longrightarrow \mathrm{Cu} \quad E^{0}=+0.337 \mathrm{~V}
$$

Thus the $\mathrm{Cu}^{2+}$ ions in the more concentrated half-cell can be considered as the reactant, and those in the more dilute cell as the product.

$$
\mathrm{Cu}^{2+}(1.00 M) \longrightarrow \mathrm{Cu}^{2+}(0.10 M)
$$

The overall cell potential can be calculated by applying the Nernst equation to the overall cell reaction. We must first find $E^{0}$, the standard cell potential at standard concentrations; because the same electrode and the same type of ions are involved in both half-cells, this $E_{\text {cell }}^{0}$ is always zero. Thus,

$$
\begin{aligned}
E_{\text {cell }} & =E_{\text {cell }}^{0}-\frac{0.0592}{n} \log \frac{[\text { dilute solution }]}{[\text { concentrated solution }]} \\
& =0-\frac{0.0592}{2} \log \frac{0.10}{1.00}=+0.030 \mathrm{~V}
\end{aligned}
$$

(continued)

> [!figure]
> ![](https://cdn.mathpix.com/cropped/c942e4e5-a003-4e4b-91e8-7898f585fef6-32.jpg?height=730&width=1554&top_left_y=1625&top_left_x=126)
> Figure 21-15 The concentration cell $\mathrm{Cu}\left|\mathrm{Cu}^{2+}(0.10 \mathrm{M})\right|\left|\mathrm{Cu}^{2+}(1.00 \mathrm{M})\right| \mathrm{Cu}$. The overall reaction


The overall cell potential is positive; the reaction is spontaneous as written.

## (Enrichment, continued)

As the reaction proceeds, $\left[\mathrm{Cu}^{2+}\right]$ decreases in the more concentrated half-cell and increases in the more dilute half-cell until the two concentrations are equal; at that point $E_{\text {cell }}=0$, and equilibrium has been reached. This equilibrium $\left[\mathrm{Cu}^{2+}\right]$ is the same concentration that would have been formed if we had just mixed the two solutions directly to obtain a solution of intermediate concentration.

In any concentration cell, the spontaneous reaction is always in the direction that tends to equalize the concentrations.