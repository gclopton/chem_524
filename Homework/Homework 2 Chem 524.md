
# Question 1

> [!question] 1.)
> The onset of Br - oxidation is around $1 \mathrm{~V} \mathrm{vs} \mathrm{Ag} / \mathrm{AgBr} / \mathrm{Br}$ - ( 1 M ) reference electrode. $\mathrm{EAg} / \mathrm{AgBr}=0.01 \mathrm{~V}$ vs NHE. (30 pts)
> What would be the Br - oxidation vs an $\mathrm{Ag} / \mathrm{AgCl} / 1 \mathrm{M} \mathrm{KCl}$ reference electrode?
>
> 
> 
> ![[Pasted image 20260214232716.png|500]]
> 
> 
> **Figure 1.1.4** Schematic current-potential curve for the cell $\mathrm{Pt} / \mathrm{H}^{+}, \mathrm{Br}^{-}(1 M) / \mathrm{AgBr} / \mathrm{Ag}$, showing the limiting proton reduction and bromide oxidation processes. The cell potential is given for the Pt electrode with respect to the Ag electrode, so it is equivalent to $E_{\mathrm{Pt}}(\mathrm{V}$ vs. AgBr$)$. Since $E_{\mathrm{Ag} / \mathrm{AgBr}}=$
> 

Using the given onset and reference value,
$$
E_{\text{onset}}(\text{vs NHE})=E_{\text{onset}}(\text{vs Ag/AgBr})+E_{\mathrm{Ag/AgBr}}(\text{vs NHE})
$$
$$
E_{\text{onset}}(\text{vs NHE})=1.00+0.01=1.01\ \mathrm{V}.
$$

For $\mathrm{Ag/AgCl}/1\ \mathrm{M}\ \mathrm{KCl}$ we have
$$
E_{\mathrm{Ag/AgCl}}(\text{vs NHE})\approx 0.235\ \mathrm{V}.
$$

Convert the onset to the Ag/AgCl scale:
$$
E_{\text{onset}}(\text{vs Ag/AgCl, 1 M KCl})
=E_{\text{onset}}(\text{vs NHE})-E_{\mathrm{Ag/AgCl}}(\text{vs NHE})
$$
$$
=1.01-0.235=0.775\ \mathrm{V}.
$$

Therefore, the bromide-oxidation onset is approximately
$$
\boxed{0.775\ \mathrm{V\ vs\ Ag/AgCl\ (1\ M\ KCl)}}.
$$






# Question 2

The following electrochemical cell is not chemically reversible, $\mathrm{Zn} / \mathrm{H}^{+}, \mathrm{SO}_4{ }^{2-} / \mathrm{Pt}$. Please do the following to demonstrate that $\mathrm{Zn} / \mathrm{H}^{+}, \mathrm{SO}_4{ }^{2-} / \mathrm{Pt}$ is not chemically reversible. ( $\mathbf{4 0}$ pts total)

> [!question] a.)
> When you short circuit Zn and Pt electrodes, what are the reactions that occur on Zn , and Pt electrodes, respectively? How does the electron flow through external circuit? What is the overall cell reaction? Please draw the picture to demonstrate the whole process. (20 pts)

When Zn and Pt are short-circuited, the Zn electrode is the anode and undergoes oxidation:
$$
\mathrm{Zn} \rightarrow \mathrm{Zn}^{2+}+2e^-
$$
At the Pt electrode, protons are reduced (cathode process):
$$
2\mathrm{H}^{+}+2e^- \rightarrow \mathrm{H}_{2}
$$
Therefore, electrons flow through the external circuit from Zn to Pt. Sulfate is a spectator ion in this process.

The overall cell reaction is
$$
\mathrm{Zn}+2\mathrm{H}^{+}\rightarrow \mathrm{Zn}^{2+}+\mathrm{H}_{2}
$$



![[Pasted image 20260215222156.png|600]]



> [!NOTE] b.)
> If you reverse the current from a), what are the reactions on Zn and Pt electrodes, respectively? What is the overall cell reaction? Please draw the picture to demonstrate the whole process. (20 pts)

To reverse the current from part (a), an external dc source must be applied with sufficient voltage to force electrons in the opposite direction. The electron flow in the external circuit is then from Pt to Zn.

At the Zn electrode, the reaction is reduction of protons and not Zn deposition:
$$
2\mathrm{H}^{+}+2e^- \rightarrow \mathrm{H}_{2}
$$
At the Pt electrode, the reaction is oxidation of water:
$$
2\mathrm{H}_{2}\mathrm{O} \rightarrow \mathrm{O}_{2}+4\mathrm{H}^{+}+4e^-
$$
Balancing electrons gives the net reacton
$$
2\mathrm{H}_{2}\mathrm{O} \rightarrow 2\mathrm{H}_{2}+\mathrm{O}_{2}
$$
So, reversing the current does not regenerate Zn from $\mathrm{Zn}^{2+}$; instead, the system performs water electrolysis. This is why the cell is not chemically reversible.







![[Pasted image 20260215224824.png|600]]


# Question 3



> [!Question]
> In her Ph.D. studies, Prof. Shen did charging current measurements under different scan rates, and observed the results in Table S1 shown below. Please calculate capacitance, Cd. Make sure to include the graph in your answer. (30 pts)
> 
> **Table S1.** Charging current at different scan rates.
> 
>
>
> | Scan rate <br> $/(\mathrm{V} / \mathrm{s})$ | Charging <br> current/A |
> | ---: | ---: |
> | 0.1 | $1.70 \mathrm{E}-07$ |
> | 0.3 | $3.40 \mathrm{E}-07$ |
> | 0.5 | $4.87 \mathrm{E}-07$ |
> | 0.75 | $6.95 \mathrm{E}-07$ |
> | 1 | $8.86 \mathrm{E}-07$ |
> 

The steady charging current magnitude follows
$$
|i_c|=\nu C_d.
$$
So the capacitance is the slope of a plot of $i$ vs. $\nu$.

Using a least-squares fit constrained through the origin (the physical model $i=\nu C_d$),
$$
C_d=\frac{\sum \nu_i i_i}{\sum \nu_i^2}
=\frac{(0.1)(1.70\times10^{-7})+(0.3)(3.40\times10^{-7})+(0.5)(4.87\times10^{-7})+(0.75)(6.95\times10^{-7})+(1.0)(8.86\times10^{-7})}{(0.1)^2+(0.3)^2+(0.5)^2+(0.75)^2+(1.0)^2}
$$
$$
=9.25\times10^{-7}\ \mathrm{F}
=0.925\ \mu\mathrm{F}.
$$

Therefore, the double-layer capacitance is
$$
\boxed{C_d \approx 9.25\times10^{-7}\ \mathrm{F}\ (0.925\ \mu\mathrm{F})}.
$$

For reference, an unconstrained linear fit gives a small positive intercept (residual/background current), but the slope-through-origin value above is the model-consistent $C_d$ for charging current.

![[hw2_q3_charging_current_vs_scan_rate.svg]]

