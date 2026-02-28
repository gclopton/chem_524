

## Chapter: Potentials in Electrochemical Thermodynamics (Part 1)

Electrochemical thermodynamics tracks two coupled driving forces. Chemical transformations and mass transfer are governed by changes in Gibbs free energy, while charged species additionally experience electrical work in an electrostatic field. A consistent framework therefore requires (i) a definition of the electrical potential associated with a phase, (ii) a clear statement that experimentally meaningful potentials are differences between phases, and (iii) a free-energy measure that combines chemical and electrical contributions for ions and electrons. This chapter segment introduces the inner (Galvani) potential, the electrode potential, the chemical potential, and the electrochemical potential.

### 1. Inner potential (Galvani potential) ($\phi$)

The **inner potential** (or **Galvani potential**) of a phase is defined operationally through work on a test charge. Consider bringing a positive test charge from a point at infinity to a point in the interior of a phase, along a quasi-static path. The electrical work required per unit charge defines the potential of that interior point relative to infinity. In symbolic form, for a test charge $q>0$ requiring work $w$,
$$
\phi=\frac{w}{q}.
$$
with the unit relation  
$$
1~\mathrm{V}=1~\mathrm{J/C}.
$$
The inner potential is thus a property of the electrical environment of the phase, including interfacial charge distributions that establish a potential field. The definition emphasizes that $\phi$ pertains to the interior of a phase and is introduced by the idealized “transport a unit positive charge from infinity” thought experiment.

### 2. Electrode potential (E) as a potential difference between phases

An **electrode potential** is fundamentally a **potential difference between phases**. Electrodes are realized as interfaces—most commonly a metal phase in contact with an electrolyte phase—and the meaningful electrical quantity is the potential difference associated with that interfacial arrangement. Because absolute electrical potentials are not directly observable in isolation, electrochemical measurements are constructed from differences: between two phases across an interface, or between an electrode of interest and a chosen reference electrode. Consequently, the theoretical development is organized to express potentials in difference form and to connect those differences to measurable cell voltages.

### 3. Chemical potential ($\mu_i$) as partial molar Gibbs free energy

The chemical driving force for species $i$ is quantified by the **chemical potential**, defined as the partial derivative of Gibbs free energy with respect to the amount of that species at fixed temperature, pressure, and the amounts of all other species:
$$
\mu_i=\left(\frac{\partial G}{\partial n_i}\right)_{T,P,n_{j\neq i}}.
$$
This definition shows that $\mu_i$ is the change in Gibbs free energy per mole of $i$ added under the stated constraints, i.e., a partial molar Gibbs free energy. For solutions and mixtures, the dependence of $\mu_i$ on composition is commonly expressed through activity:
$$
\mu_i=\mu_i^{0}+RT\ln(\alpha_i).
$$
where $\mu_i^{0}$ is the standard chemical potential and $\alpha_i$ is the activity. This logarithmic form is the principal mechanism by which composition enters thermodynamic driving forces in electrochemical systems.

### 4. Electrochemical potential ($\bar{\mu}_i^\alpha$): chemical plus electrical contributions

For a charged species, chemical free energy alone does not determine equilibrium or transport. If species $i$ has charge number $z_i$ and resides in phase $\alpha$ with inner potential $\phi^\alpha$, then placing one mole of that species into the phase requires (or releases) electrical work proportional to $z_iF\phi^\alpha$, where $F$ is Faraday’s constant. The combined quantity is the **electrochemical potential**:
$$
\bar{\mu}_i^{\alpha}=\mu_i^{\alpha}+z_iF\phi^{\alpha}
\qquad
z_i=\text{charge number}.
$$
This definition provides the thermodynamic “potential” that drives diffusion and migration of ions and governs electrochemical equilibrium across phase boundaries.

#### activity form for ($\bar{\mu}_i^\alpha$)

Starting with the activity representation of the chemical potential in phase $\alpha$,
$$
\mu_i^{\alpha}=\mu_i^{0}+RT\ln\!\big(\alpha_i^{\alpha}\big)
$$
and the definition of electrochemical potential,
$$
\bar{\mu}_i^{\alpha}=\mu_i^{\alpha}+z_iF\phi^{\alpha}
$$
substitution yields
$$
\begin{aligned}
\bar{\mu}_i^{\alpha}
&= \mu_i^{\alpha}+z_iF\phi^{\alpha} \\
&= \left(\mu_i^{0}+RT\ln\!\big(\alpha_i^{\alpha}\big)\right)+z_iF\phi^{\alpha} \\
&= \mu_i^{0}+z_iF\phi^{\alpha}+RT\ln\!\big(\alpha_i^{\alpha}\big).
\end{aligned}
$$
Define a standard electrochemical potential for phase $\alpha$ by grouping the reference-like terms,
$$
\bar{\mu}_i^{0,\alpha}\equiv\mu_i^{0}+z_iF\phi^{\alpha}.
$$
Then the electrochemical potential takes the compact standard-plus-activity form
$$
\bar{\mu}_i^{\alpha}=\bar{\mu}_i^{0,\alpha}+RT\ln\!\big(\alpha_i^{\alpha}\big).
$$
This expression makes explicit that the electrochemical potential differs from the chemical potential by an electrical contribution tied to the Galvani potential of the phase, while retaining the familiar $RT\ln(\text{activity})$ structure.




### 5. Working rules and equilibrium conditions

The definitions of chemical potential and electrochemical potential immediately yield a set of practical rules that simplify common cases and state equilibrium conditions succinctly.

#### 5.1 Pure phases (e.g., $\mathrm{Ag(s)}$, $\mathrm{Zn(s)}$)

For a pure condensed phase, the activity of the component in its standard state is defined as unity, $a_i=1$. For a neutral species, $z_i=0$. Under these conditions, the electrochemical potential reduces to the standard chemical potential.

$$
\begin{aligned}
\bar{\mu}_i
&= \mu_i+z_iF\phi \\
&= \left(\mu_i^{0}+RT\ln(a_i)\right)+z_iF\phi \\
&= \mu_i^{0}+RT\ln(1)+0\cdot F\phi \\
&= \mu_i^{0}.
\end{aligned}
$$

#### 5.2 Electrons in a metal

For an electron, $z_e=-1$. In a metal phase (for example Zn), the electrochemical potential is therefore

$$
\begin{aligned}
\bar{\mu}_e^{\mathrm{Zn}}
&= \mu_e^{\mathrm{Zn}}+z_eF\phi^{\mathrm{Zn}} \\
&= \mu_e^{\mathrm{Zn}}-F\phi^{\mathrm{Zn}}.
\end{aligned}
$$

#### 5.3 Species equilibrium between two phases

A species $i$ is at equilibrium with respect to transfer between two different phases $\alpha$ and $\beta$ when its electrochemical potential is equal in both phases:

$$
\bar{\mu}_i^{\alpha}=\bar{\mu}_i^{\beta}.
$$

#### 5.4 Reaction equilibrium within a single phase

For a reaction occurring entirely within a single phase $\alpha$, equilibrium requires the balance of electrochemical potentials between reactants and products:

$$
\sum \bar{\mu}^{\alpha}_{\text{reactants}}=\sum \bar{\mu}^{\alpha}_{\text{products}}.
$$

Equivalently, using stoichiometric coefficients $\nu_i$ (positive for products, negative for reactants),

$$
\sum_i \nu_i\,\bar{\mu}_i^{\alpha}=0.
$$



### 6. Eliminating the electron term in a measurable cell potential

To relate an electrode potential to thermodynamic state variables, it is useful to embed the electrode of interest in a complete cell whose terminal potentials are defined at metallic leads. Consider the composite cell written with two distinct copper leads,  
$$
\mathrm{Cu}\,|\,\mathrm{Zn}\,|\,\mathrm{Zn}^{2+}(S)\,;\,;\,\mathrm{H}^+(S)\,|\,\mathrm{H_2}(g)\,|\,\mathrm{Pt}\,|\,\mathrm{Cu}'.
$$
where $\mathrm{Cu}$ and $\mathrm{Cu}'$ denote two different copper terminals (the copper leads of the connectors). The measurable electrical quantity is taken as the Galvani-potential difference between these terminals,
$$
E\equiv \phi^{\mathrm{Cu}'}-\phi^{\mathrm{Cu}}.
$$

#### 6.1 Left-side reduction written against electrons in the copper lead

Three equilibrium statements are combined to rewrite the zinc half-cell in a form that explicitly uses electrons in the external metal lead.

First, electrons are at equilibrium between the copper lead and the zinc metal,  
$$
\bar{\mu}_e^{\mathrm{Cu}}=\bar{\mu}_e^{\mathrm{Zn}}.
$$
Second, the interfacial redox equilibrium at zinc is  
$$
\begin{aligned}
\mathrm{Zn}^{2+}+2e^- &\rightleftharpoons \mathrm{Zn}, \\
\bar{\mu}_{\mathrm{Zn}^{2+}}^{\mathrm{Zn}}+2\bar{\mu}_e^{\mathrm{Zn}} &= \bar{\mu}_{\mathrm{Zn}}^{\mathrm{Zn}}.
\end{aligned}
$$
Third, $\mathrm{Zn}^{2+}$ is at equilibrium between the zinc interface and the bulk solution (with $S$ denoting solution),  
$$
\bar{\mu}_{\mathrm{Zn}^{2+}}^{S}=\bar{\mu}_{\mathrm{Zn}^{2+}}^{\mathrm{Zn}}.
$$

Adding these relations eliminates the intermediate $\bar{\mu}_e^{\mathrm{Zn}}$ and $\bar{\mu}_{\mathrm{Zn}^{2+}}^{\mathrm{Zn}}$, yielding an effective left-half-cell equilibrium written in terms of $\mathrm{Zn}^{2+}$ in solution and electrons in the copper terminal:

$$
\boxed{2\bar{\mu}_e^{\mathrm{Cu}}+\bar{\mu}_{\mathrm{Zn}^{2+}}^{S}=\bar{\mu}_{\mathrm{Zn}}^{\mathrm{Zn}}}
\qquad\Longleftrightarrow\qquad
\mathrm{Zn}^{2+}(S)+2e^-(\mathrm{Cu})\rightleftharpoons \mathrm{Zn}(\mathrm{Zn}).
$$

Expanding the electrochemical potentials using $\bar{\mu}_i=\mu_i+z_iF\phi$, with $z_e=-1$, $z_{\mathrm{Zn}^{2+}}=+2$, and $z_{\mathrm{Zn}}=0$, gives the explicit “left half-cell” equation (labeled as Eq. 2 in the notes):

$$
\boxed{
2\mu_e^{\mathrm{Cu}}-2F\phi^{\mathrm{Cu}}+\mu_{\mathrm{Zn}^{2+}}^{0,S}+RT\ln\!\big(a_{\mathrm{Zn}^{2+}}^{S}\big)+2F\phi^{S}
=\mu_{\mathrm{Zn}}^{0,\mathrm{Zn}}
}
\tag{Eq. 2}
$$

#### 6.2 Right-side reduction (hydrogen) written against electrons in the copper lead

On the right side, the hydrogen equilibrium is written with electrons in the $\mathrm{Cu}'$ terminal:

$$
\begin{aligned}
2\mathrm{H}^+(S)+2e^-(\mathrm{Cu}') &\rightleftharpoons \mathrm{H_2}(g), \\
2\bar{\mu}_{\mathrm{H}^+}^{S}+2\bar{\mu}_e^{\mathrm{Cu}'} &= \bar{\mu}_{\mathrm{H_2}}^{g}.
\end{aligned}
$$

Expanding each electrochemical potential in the same way (with $z_{\mathrm{H}^+}=+1$, $z_e=-1$, $z_{\mathrm{H_2}}=0$) and using $\mu=\mu^0+RT\ln a$ produces the right-half-cell equation (labeled as Eq. 1):

$$
\boxed{
2\Big(\mu_{\mathrm{H}^+}^{0,S}+RT\ln(a_{\mathrm{H}^+}^{S})+F\phi^{S}\Big)
+2\Big(\mu_e^{\mathrm{Cu}'}-F\phi^{\mathrm{Cu}'}\Big)
=\mu_{\mathrm{H_2}}^{0,g}+RT\ln(a_{\mathrm{H_2}}^{g})
}
\tag{Eq. 1}
$$

#### 6.3 Forming the terminal potential difference and identifying the Nernst form

The electron chemical-potential term that appears in Eq. 2 is not directly accessible by itself. The standard elimination step is to combine the two half-cell relations so that the electronic terms cancel. Subtracting Eq. 1 from Eq. 2 and using metallic equilibrium of electrons between the copper terminals,  
$$
\mu_e^{\mathrm{Cu}}=\mu_e^{\mathrm{Cu}'}.
$$
removes the unknown electronic contribution and isolates the terminal Galvani-potential difference.



**Derivation Mode**

$$
\begin{aligned}
&\Big(2\mu_e^{\mathrm{Cu}}-2F\phi^{\mathrm{Cu}}+\mu_{\mathrm{Zn}^{2+}}^{0,S}+RT\ln(a_{\mathrm{Zn}^{2+}}^{S})+2F\phi^{S}\Big) \\
&\qquad-\Big(2\mu_{\mathrm{H}^+}^{0,S}+2RT\ln(a_{\mathrm{H}^+}^{S})+2F\phi^{S}+2\mu_e^{\mathrm{Cu}'}-2F\phi^{\mathrm{Cu}'}\Big) \\
&\qquad=\mu_{\mathrm{Zn}}^{0,\mathrm{Zn}}-\Big(\mu_{\mathrm{H_2}}^{0,g}+RT\ln(a_{\mathrm{H_2}}^{g})\Big) \\
\Longrightarrow\;& 2\mu_e^{\mathrm{Cu}}-2\mu_e^{\mathrm{Cu}'}-2F\phi^{\mathrm{Cu}}+2F\phi^{\mathrm{Cu}'}+\mu_{\mathrm{Zn}^{2+}}^{0,S}+RT\ln(a_{\mathrm{Zn}^{2+}}^{S})-2\mu_{\mathrm{H}^+}^{0,S}-2RT\ln(a_{\mathrm{H}^+}^{S}) \\
&\qquad=\mu_{\mathrm{Zn}}^{0,\mathrm{Zn}}-\mu_{\mathrm{H_2}}^{0,g}-RT\ln(a_{\mathrm{H_2}}^{g}) \\
\Longrightarrow\;& 2F(\phi^{\mathrm{Cu}'}-\phi^{\mathrm{Cu}}) \\
&\qquad=\mu_{\mathrm{Zn}}^{0,\mathrm{Zn}}+2\mu_{\mathrm{H}^+}^{0,S}-\mu_{\mathrm{Zn}^{2+}}^{0,S}-\mu_{\mathrm{H_2}}^{0,g}
-RT\ln\!\left(\frac{a_{\mathrm{Zn}^{2+}}^{S}a_{\mathrm{H_2}}^{g}}{(a_{\mathrm{H}^+}^{S})^2}\right) \\
\Longrightarrow\;& 2F(\phi^{\mathrm{Cu}'}-\phi^{\mathrm{Cu}}) \\
&\qquad=-\Big(\mu_{\mathrm{Zn}^{2+}}^{0,S}+\mu_{\mathrm{H_2}}^{0,g}-\mu_{\mathrm{Zn}}^{0,\mathrm{Zn}}-2\mu_{\mathrm{H}^+}^{0,S}\Big)
-RT\ln\!\left(\frac{a_{\mathrm{Zn}^{2+}}^{S}a_{\mathrm{H_2}}^{g}}{(a_{\mathrm{H}^+}^{S})^2}\right).
\end{aligned}
$$

The standard-state combination is identified as the standard Gibbs free energy of reaction for  
$$
\mathrm{Zn}(\mathrm{s})+2\mathrm{H}^+(S)\rightleftharpoons \mathrm{Zn}^{2+}(S)+\mathrm{H_2}(g),
$$
namely  
$$
\Delta G_r^\circ=\mu_{\mathrm{Zn}^{2+}}^{0,S}+\mu_{\mathrm{H_2}}^{0,g}-\mu_{\mathrm{Zn}}^{0,\mathrm{Zn}}-2\mu_{\mathrm{H}^+}^{0,S}.
$$
With $E\equiv \phi^{\mathrm{Cu}'}-\phi^{\mathrm{Cu}}$, the result becomes
$$
2F E=-\Delta G_r^\circ-RT\ln\!\left(\frac{a_{\mathrm{Zn}^{2+}}^{S}a_{\mathrm{H_2}}^{g}}{(a_{\mathrm{H}^+}^{S})^2}\right).
$$
Using $(\Delta G_r^\circ=-nF E^\circ)$ with $(n=2)$ gives the Nernst-form expression for the terminal potential difference:
$$
\boxed{
E=E^\circ-\frac{RT}{2F}\ln\!\left(\frac{a_{\mathrm{Zn}^{2+}}^{S}a_{\mathrm{H_2}}^{g}}{(a_{\mathrm{H}^+}^{S})^2}\right)
}
$$
which is the desired measurable potential in terms of activities and a standard potential.




> [!exercise] problem
> a) Write down the overall electrochemical reaction of the transfer of ACh+ from water phase (W) to oil phase, nitrobenzene (NB), including phases. Is this a Faradaic process?
> b) To derive the Nernst equation, what is the electrochemical potential correlation? Please expand the electrochemical potential as a function of standard chemical potential, activity, and inner potential (only first step expansion is required).


### 7. Ion transfer at an ITIES: a Nernst-type relation from electrochemical potentials

An interface between two immiscible electrolyte solutions (ITIES) supports **ion-transfer reactions** in which an ionic species moves from one liquid phase to the other without undergoing electron-transfer (redox) chemistry. The thermodynamic description is obtained by enforcing equality of **electrochemical potentials** of the transferring ion across the two phases. This produces a Nernst-type relation between the **interfacial Galvani potential difference** and the ion activities in each phase.

#### 7.1 Overall electrochemical reaction and Faradaic character

For acetylcholine as a monovalent cation, the overall transfer reaction from water (W) to nitrobenzene (NB) is written, including phases, as  
$$
\mathrm{ACh}^+(W)\rightleftharpoons \mathrm{ACh}^+(NB)
$$

This process is **non-redox**: no electrons appear, and no oxidation states change. Nevertheless, it is **Faradaic** in the electrochemical sense that it involves **net transfer of charge across the interface** carried by an ionic species (as opposed to purely capacitive charging of the interfacial double layers). The corresponding current is proportional to the rate of ion transfer across the interface.

#### 7.2 Electrochemical-potential correlation and first-step expansion

At equilibrium with respect to transfer, the electrochemical potential of $\mathrm{ACh}^+$ must be the same in both phases:
$$
\bar{\mu}_{\mathrm{ACh}^+}^{W}=\bar{\mu}_{\mathrm{ACh}^+}^{NB}.
$$

The electrochemical potential in a phase $\alpha\in\{W,NB\}$ is expanded (first-step expansion) in terms of standard chemical potential, activity, and inner (Galvani) potential:
$$
\bar{\mu}_i^{\alpha}=\mu_i^{\alpha}+z_iF\phi^{\alpha}
=\mu_i^{0,\alpha}+RT\ln\!\big(a_i^{\alpha}\big)+z_iF\phi^{\alpha}
$$

For $\mathrm{ACh}^+$, $z=+1$. Substituting the expansion into the equilibrium condition gives the explicit “Nernst starting point”:

$$
\mu_{\mathrm{ACh}^+}^{0,W}+RT\ln\!\big(a_{\mathrm{ACh}^+}^{W}\big)+F\phi^{W}
=
\mu_{\mathrm{ACh}^+}^{0,NB}+RT\ln\!\big(a_{\mathrm{ACh}^+}^{NB}\big)+F\phi^{NB}
$$

#### 7.3 Derivation Mode: interfacial potential difference (Nernst form for ion transfer)

Define the interfacial Galvani potential difference (organic relative to water) as  
$$
\Delta\phi_{W}^{NB}\equiv \phi^{NB}-\phi^{W}
$$

Then:

$$
\begin{aligned}
\mu_{\mathrm{ACh}^+}^{0,W}+RT\ln\!\big(a_{\mathrm{ACh}^+}^{W}\big)+F\phi^{W}
&=
\mu_{\mathrm{ACh}^+}^{0,NB}+RT\ln\!\big(a_{\mathrm{ACh}^+}^{NB}\big)+F\phi^{NB} \\
F(\phi^{NB}-\phi^{W})
&=
\mu_{\mathrm{ACh}^+}^{0,W}-\mu_{\mathrm{ACh}^+}^{0,NB}
+RT\ln\!\left(\frac{a_{\mathrm{ACh}^+}^{W}}{a_{\mathrm{ACh}^+}^{NB}}\right) \\
\Delta\phi_{W}^{NB}
&=
\frac{\mu_{\mathrm{ACh}^+}^{0,W}-\mu_{\mathrm{ACh}^+}^{0,NB}}{F}
+\frac{RT}{F}\ln\!\left(\frac{a_{\mathrm{ACh}^+}^{W}}{a_{\mathrm{ACh}^+}^{NB}}\right).
\end{aligned}
$$

It is common to express the standard-state term using a **standard Gibbs free energy of transfer**. Define
$$
\Delta G_{\mathrm{tr}}^{0,W\to NB}\equiv \mu_{\mathrm{ACh}^+}^{0,NB}-\mu_{\mathrm{ACh}^+}^{0,W}
$$
Then $\mu_{\mathrm{ACh}^+}^{0,W}-\mu_{\mathrm{ACh}^+}^{0,NB}=-\Delta G_{\mathrm{tr}}^{0,W\to NB}$, and the result becomes
$$
\boxed{
\Delta\phi_{W}^{NB}
=-\frac{\Delta G_{\mathrm{tr}}^{0,W\to NB}}{F}
+\frac{RT}{F}\ln\!\left(\frac{a_{\mathrm{ACh}^+}^{W}}{a_{\mathrm{ACh}^+}^{NB}}\right)
}
$$
or, more generally for charge number $z_i$,  
$$
\boxed{
\Delta\phi_{W}^{NB}
=-\frac{\Delta G_{\mathrm{tr}}^{0,W\to NB}}{z_iF}
+\frac{RT}{z_iF}\ln\!\left(\frac{a_{i}^{W}}{a_{i}^{NB}}\right).
}
$$

This is the ITIES analogue of the Nernst equation: the interfacial potential difference required for equilibrium depends on a standard transfer free energy (reflecting solvation preference between phases) and on the logarithm of the activity ratio across the interface.

If the next chunk includes how the applied potential drives current (or how supporting electrolytes enforce electroneutrality), it can be integrated immediately after this section.
