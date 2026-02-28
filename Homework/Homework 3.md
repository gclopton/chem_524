Homework #3
Chem 524 - Electrochemical Methods
Grady Clopton

**Instructions:** The total points are 100. Answer the questions below and show all the work / detailed steps necessary to arrive at an answer; identify the right equations to use. Include your name on your answer page. Please clearly label the question number in your answer. Please upload the homework to Canvas as a PDF or image file (please do not upload ".HEIC")





> [!p] 1
> Chapter 2 of the textbook: 2.1 (b) (25 pts) (same number for the 2022 edition and older one)
> 2.1 Devise electrochemical cells in which the following reactions could be made to occur. If liquid junctions are necessary, note them in the cell schematic appropriately, but neglect their effects.
> (b) $2 \mathrm{H}_{2}+\mathrm{O}_{2} \rightleftharpoons 2 \mathrm{H}_{2} \mathrm{O}$


## Problem 1 Solution

One convenient way to make the overall reaction
$$
2\mathrm{H}_{2}+\mathrm{O}_{2}\rightarrow 2\mathrm{H}_{2}\mathrm{O}
$$
occur electrochemically is to build an acidic hydrogen–oxygen (fuel-cell) arrangement using inert Pt electrodes. In acidic solution, the relevant half-reactions are
$$
\text{Anode (oxidation):}\qquad \mathrm{H}_{2}\rightarrow 2\mathrm{H}^{+}+2e^{-}
$$
and
$$
\text{Cathode (reduction):}\qquad \mathrm{O}_{2}+4\mathrm{H}^{+}+4e^{-}\rightarrow 2\mathrm{H}_{2}\mathrm{O}.
$$
Multiplying the anode reaction by 2 and adding cancels electrons and protons and yields the desired net reaction. 



Under standard-state conditions (unit activities for solutes, $P_{\mathrm{H_{2}}}=P_{\mathrm{O_{2}}}=1~\mathrm{bar}$, and liquid water with $a_{\mathrm{H_{2}O}}=1$), we have
$$
\mathrm{Pt}\ /\ \mathrm{H}_{2}(1~\mathrm{bar})\ /\ \mathrm{H}^{+}(a=1)\ \Big\|\ \mathrm{H}^{+}(a=1)\ /\ \mathrm{O}_{2}(1~\mathrm{bar})\ /\ \mathrm{Pt}.
$$

With the oxygen electrode written on the right, the cell diagram is aligned with the Chapter 2 convention that the right electrode is the cathode for the associated galvanic (spontaneous) direction, the corresponding overall cell reaction is therefore $2\mathrm{H}_{2}+\mathrm{O}_{2}\rightarrow 2\mathrm{H}_{2}\mathrm{O}$.


Using standard reduction potentials vs. NHE, the hydrogen electrode is defined as $E^{0}=0.000~\mathrm{V}$ for
$$
2\mathrm{H}^{+}+2e^{-}\rightleftharpoons \mathrm{H}_{2},
$$
and the oxygen/water couple is $E^{0}=+1.229~\mathrm{V}$ for
$$
\mathrm{O}_{2}+4\mathrm{H}^{+}+4e^{-}\rightleftharpoons 2\mathrm{H}_{2}\mathrm{O}.
$$
Therefore the standard cell emf for the spontaneous (galvanic) direction is
$$
E^{0}_{\text{cell}}=E^{0}_{\text{cathode}}-E^{0}_{\text{anode}}=1.229-0.000=+1.229~\mathrm{V},
$$
with $n=4$ electrons transferred per overall reaction as written. Because $E^{0}_{\text{cell}}>0$,
$$
\Delta G^{0}=-n F E^{0}_{\text{cell}}\approx -(4)(96485)(1.229)\approx -4.74\times 10^{5}~\mathrm{J\,mol^{-1}},
$$
so the reaction is spontaneous in the galvanic direction, and the hydrogen electrode is the anode (negative electrode) during discharge.



![[Pasted image 20260222224314.png]]



> [!p] 2
> Chapter 2 of the textbook: 2.4 (f) (25 pts) (same number for the 2022 edition and older one)
> 2.4 What are the cell reactions and their emfs in the following systems? Are the reactions spontaneous? Assume that all systems are aqueous.
> (f) $\mathrm{Pt} / \mathrm{Ce}^{3+}(0.01 \mathrm{M}), \mathrm{Ce}^{4+}(0.1 \mathrm{M}), \mathrm{H}_{2} \mathrm{SO}_{4}(1 \mathrm{M}) / /\mathrm{Fe}^{2+}(0.01 \mathrm{M}), \mathrm{Fe}^{3+}(0.1 \mathrm{M}), \mathrm{HCl}(1 \mathrm{M}) / \mathrm{Pt}$

## Problem 2 Solution

The cell has two one-electron redox couples on inert Pt electrodes. Written as reductions,
$$
\mathrm{Ce}^{4+}+e^{-}\rightleftharpoons \mathrm{Ce}^{3+}\qquad (n=1)
$$
and
$$
\mathrm{Fe}^{3+}+e^{-}\rightleftharpoons \mathrm{Fe}^{2+}\qquad (n=1).
$$

Using the Nernst equation in the Chapter 2 form for a reduction half-reaction,
$$
E=E^{0}+\frac{R T}{n F}\ln\frac{a_{\mathrm{Ox}}}{a_{\mathrm{Red}}},
$$
and adopting the approximation that activities are given by the stated molar concentrations (i.e., $a\approx[\ ]$ for these aqueous solutions), we obtain at $T=298~\mathrm{K}$
$$
E_{\mathrm{Ce}}=E^{0}_{\mathrm{Ce}^{4+}/\mathrm{Ce}^{3+}}+\frac{R T}{F}\ln\!\left(\frac{[\mathrm{Ce}^{4+}]}{[\mathrm{Ce}^{3+}]}\right)
=E^{0}_{\mathrm{Ce}^{4+}/\mathrm{Ce}^{3+}}+\frac{R T}{F}\ln(10)
$$
and
$$
E_{\mathrm{Fe}}=E^{0}_{\mathrm{Fe}^{3+}/\mathrm{Fe}^{2+}}+\frac{R T}{F}\ln\!\left(\frac{[\mathrm{Fe}^{3+}]}{[\mathrm{Fe}^{2+}]}\right)
=E^{0}_{\mathrm{Fe}^{3+}/\mathrm{Fe}^{2+}}+\frac{R T}{F}\ln(10).
$$
Since $\frac{R T}{F}\ln(10)=0.05916~\mathrm{V}$ at $298~\mathrm{K}$, both couples are shifted by the same $+0.05916~\mathrm{V}$ under the given concentration ratios (each has $\mathrm{Ox}/\mathrm{Red}=10$).

To associate a reaction with the given cell schematic, we use the convention that the cell-reaction emf is defined as the right electrode potential with respect to the left:
$$
E_{\mathrm{rxn}}\equiv E_{\mathrm{right}}-E_{\mathrm{left}}.
$$
Here, the left electrode is the $\mathrm{Ce}^{4+}/\mathrm{Ce}^{3+}$ electrode and the right electrode is the $\mathrm{Fe}^{3+}/\mathrm{Fe}^{2+}$ electrode, so
$$
E_{\mathrm{rxn}}=E_{\mathrm{Fe}}-E_{\mathrm{Ce}}
=\left(E^{0}_{\mathrm{Fe}^{3+}/\mathrm{Fe}^{2+}}-E^{0}_{\mathrm{Ce}^{4+}/\mathrm{Ce}^{3+}}\right).
$$
The Nernst terms cancel because both sides have the same $\ln(10)$ factor.

Using standard reduction potentials vs. NHE (Table C.1 in the textbook), $E^{0}_{\mathrm{Fe}^{3+}/\mathrm{Fe}^{2+}}\approx 0.77~\mathrm{V}$ and $E^{0}_{\mathrm{Ce}^{4+}/\mathrm{Ce}^{3+}}\approx 1.61~\mathrm{V}$, we get
$$
E_{\mathrm{rxn}}\approx 0.77-1.61=-0.84~\mathrm{V}.
$$
Thus, the cell reaction associated with the schematic (right = reduction, left = oxidation) is
$$
\mathrm{Ce}^{3+}+\mathrm{Fe}^{3+}\rightarrow \mathrm{Ce}^{4+}+\mathrm{Fe}^{2+},
$$
and its emf is negative, so this reaction is not spontaneous as written.

The spontaneous (galvanic) direction is the reverse:
$$
\mathrm{Ce}^{4+}+\mathrm{Fe}^{2+}\rightarrow \mathrm{Ce}^{3+}+\mathrm{Fe}^{3+},
$$
with
$$
E_{\text{cell, spont}}=E_{\mathrm{Ce}}-E_{\mathrm{Fe}}\approx +0.84~\mathrm{V}.
$$
Equivalently, for the overall spontaneous reaction the reaction quotient is
$$
Q=\frac{[\mathrm{Ce}^{3+}][\mathrm{Fe}^{3+}]}{[\mathrm{Ce}^{4+}][\mathrm{Fe}^{2+}]}
=\frac{(0.01)(0.1)}{(0.1)(0.01)}=1,
$$
so the concentration correction to the overall cell emf vanishes and $E=E^{0}_{\text{cell}}$ under the stated concentrations.





> [!p] 3
> 3. Thermodynamics. Determine the chemical reversibility of the following electrochemical cell. $\mathrm{Pt} / \mathrm{H}_2 / \mathrm{H}^{+}, \mathrm{Cl} / \mathrm{AgCl} / \mathrm{Ag}$.
> A) When you short circuit Pt and Ag , determine the current flow direction through external circuit. What are the corresponding half reactions on Pt and Ag and overall reaction? Is this cell spontaneous or not? Why? Please use calculations to demonstrate your answers. (25 pts)
> B) What are the half reactions on Pt and Ag and overall reaction when you reverse the current? (15 pts)
> C) Is this cell chemically reversible? Why? All activities are unity. (10 pts)


## Problem 3 Solution

The cell is
$$
\mathrm{Pt} / \mathrm{H}_{2}(a=1) / \mathrm{H}^{+}(a=1),\ \mathrm{Cl}^{-}(a=1)\ /\ \mathrm{AgCl}(\mathrm{s}) / \mathrm{Ag}(\mathrm{s}),
$$
and all activities are unity. We treat the Pt electrode as the hydrogen electrode and the Ag electrode as an Ag/AgCl electrode, and we use the Chapter 2 sign convention that the cell emf for the spontaneous direction is
$$
E_{\text{cell}}=E_{\text{cathode}}-E_{\text{anode}}
$$
and that the free energy change is
$$
\Delta G=-n F E_{\text{cell}}.
$$

The hydrogen reduction half-reaction is
$$
2\mathrm{H}^{+}+2e^{-}\rightleftharpoons \mathrm{H}_{2},
$$
and under the NHE conditions $a_{\mathrm{H}^{+}}=a_{\mathrm{H}_{2}}=1$ its electrode potential is
$$
E_{\mathrm{Pt/H^{+}/H_{2}}}=0~\mathrm{V}\ \text{vs. NHE}.
$$

For the silver/silver chloride electrode, the relevant reduction half-reaction is
$$
\mathrm{AgCl}(\mathrm{s})+e^{-}\rightleftharpoons \mathrm{Ag}(\mathrm{s})+\mathrm{Cl}^{-}.
$$
Its Nernst expression can be written in the Chapter 2 form
$$
E_{\mathrm{AgCl/Ag}}=E^{0}_{\mathrm{AgCl/Ag}}+\frac{R T}{F}\ln\!\left(\frac{a_{\mathrm{AgCl}}}{a_{\mathrm{Ag}}a_{\mathrm{Cl}^{-}}}\right)
=E^{0}_{\mathrm{AgCl/Ag}}-\frac{R T}{F}\ln a_{\mathrm{Cl}^{-}},
$$
since $a_{\mathrm{AgCl}}=a_{\mathrm{Ag}}=1$ for pure solids. With $a_{\mathrm{Cl}^{-}}=1$, this reduces to
$$
E_{\mathrm{AgCl/Ag}}=E^{0}_{\mathrm{AgCl/Ag}}.
$$
Using the standard value from the textbook tables, $E^{0}_{\mathrm{AgCl/Ag}}\approx +0.222~\mathrm{V}$ vs NHE at $25^{\circ}\mathrm{C}$.

### Part A

Because the Ag/AgCl electrode has the higher reduction potential, it acts as the cathode (reduction) in a galvanic discharge, and the hydrogen electrode (Pt) acts as the anode (oxidation). Thus, the Pt electrode is the negative electrode during discharge, and electrons flow through the external circuit from Pt to Ag:
$$
\ominus\ \mathrm{Pt}\ \xrightarrow{\ e^{-}\ }\ \mathrm{Ag}\ \oplus
$$
Equivalently, the conventional current direction in the external circuit is from Ag to Pt.

The anode (Pt) oxidation half-reaction is the reverse of hydrogen reduction:
$$
\mathrm{H}_{2}\rightarrow 2\mathrm{H}^{+}+2e^{-}.
$$
The cathode (Ag) reduction half-reaction is
$$
\mathrm{AgCl}(\mathrm{s})+e^{-}\rightarrow \mathrm{Ag}(\mathrm{s})+\mathrm{Cl}^{-}.
$$
Multiplying the Ag/AgCl half-reaction by 2 and adding gives the overall cell reaction:
$$
\mathrm{H}_{2}+2\mathrm{AgCl}(\mathrm{s})\rightarrow 2\mathrm{Ag}(\mathrm{s})+2\mathrm{H}^{+}+2\mathrm{Cl}^{-}.
$$

The cell emf for this discharge direction is
$$
E_{\text{cell}}=E_{\mathrm{AgCl/Ag}}-E_{\mathrm{Pt/H^{+}/H_{2}}}=0.222-0=+0.222~\mathrm{V}.
$$
Therefore,
$$
\Delta G=-n F E_{\text{cell}}=-(2)(96485~\mathrm{C\,mol^{-1}})(0.222~\mathrm{V})\approx -4.28\times 10^{4}~\mathrm{J\,mol^{-1}}=-42.8~\mathrm{kJ\,mol^{-1}}.
$$
Because $\Delta G<0$ (equivalently, because $E_{\text{cell}}>0$ for the galvanic orientation), the cell reaction above is spontaneous on short circuit.

### Part B

To reverse the current, an external dc source must oppose and slightly exceed the cell voltage so that the Ag electrode is driven negative with respect to Pt. The electrode processes then reverse.

In the external circuit, the electron flow direction is forced to reverse (from Ag to Pt), and the conventional current reverses as well.

At Pt, reduction occurs:
$$
2\mathrm{H}^{+}+2e^{-}\rightarrow \mathrm{H}_{2}.
$$
At Ag/AgCl, oxidation occurs:
$$
\mathrm{Ag}(\mathrm{s})+\mathrm{Cl}^{-}\rightarrow \mathrm{AgCl}(\mathrm{s})+e^{-}.
$$
Multiplying the Ag/AgCl oxidation by 2 and adding gives the forced (electrolytic) net reaction:
$$
2\mathrm{Ag}(\mathrm{s})+2\mathrm{H}^{+}+2\mathrm{Cl}^{-}\rightarrow \mathrm{H}_{2}+2\mathrm{AgCl}(\mathrm{s}),
$$
which is the reverse of the discharge reaction.

### Part C

This cell is chemically reversible because reversing the current causes the electrode reactions to reverse cleanly, and the net process under forced current reversal is the exact reverse of the net process during discharge (with no new electrode reactions appearing).
