## CHAPTER 6

## Chemical equilibrium

Chemical reactions tend to move towards a dynamic equilib－ rium in which both reactants and products are present but have no further tendency to undergo net change．In some cases， the concentration of products in the equilibrium mixture is so much greater than that of the unchanged reactants that for all practical purposes the reaction is＇complete＇．However，in many important cases the equilibrium mixture has significant con－ centrations of both reactants and products．

## 6A The equilibrium constant

This Topic develops the concept of chemical potential and shows how it is used to account for the equilibrium composi－ tion of chemical reactions．The equilibrium composition cor－ responds to a minimum in the Gibbs energy plotted against the extent of reaction．By locating this minimum we establish the relation between the equilibrium constant and the standard Gibbs energy of reaction．

## 6B The response of equilibria to the conditions

The thermodynamic formulation of equilibrium enables us to establish the quantitative effects of changes in the conditions． One very important aspect of equilibrium is the control that can be exercised by varying the conditions，such as the pressure or temperature．

## 6C Electrochemical cells

Because many reactions involve the transfer of electrons，they can be studied（and utilized）by allowing them to take place in a cell equipped with electrodes，with the spontaneous reaction
forcing electrons through an external circuit．We shall see that the electric potential of the cell is related to the reaction Gibbs energy，so providing an electrical procedure for the determina－ tion of thermodynamic quantities．

## 6D Electrode potentials

Electrochemistry is in part a major application of thermody－ namic concepts to chemical equilibria as well as being of great technological importance．As elsewhere in thermodynamics， we see how to report electrochemical data in a compact form and apply it to problems of real chemical significance，espe－ cially to the prediction of the spontaneous direction of reac－ tions and the calculation of equilibrium constants．

## What is the impact of this material？

The thermodynamic description of spontaneous reactions has numerous practical and theoretical applications．We highlight two applications．One is to the discussion of biochemical pro－ cesses，where one reaction drives another（Impact I6．1）．That， ultimately，is why we have to eat，for we see that the reaction that takes place when one substance is oxidized can drive non－ spontaneous reactions，such as protein synthesis，forward． Another makes use of the great sensitivity of electrochemical processes to the concentration of electroactive materials，and we see how specially designed electrodes are used in analysis （Impact I6．2）．

To read more about the impact of this material，scan the QR code，or go to bcs．whfreeman．com／webpub／chemistry／ pchem10e／impact／pchem－6－1．html

## 6A The equilibrium constant

## Contents

6A. 1 The Gibbs energy minimum 245
(a) The reaction Gibbs energy 245

Brief illustration 6A.1: The extent of reaction 245
(b) Exergonic and endergonic reactions 246

Brief illustration 6A.2: Exergonic and endergonic reactions 247
6A.2 The description of equilibrium 247
(a) Perfect gas equilibria 247

Brief illustration 6A.3: The equilibrium constant 247
(b) The general case of a reaction 248

Brief illustration 6A.4: The reaction quotient 248
Brief illustration 6A.5: The equilibrium constant 249
Example 6A.1: Calculating an equilibrium constant 249
Example 6A.2: Estimating the degree of dissociation at equilibrium 250
(c) The relation between equilibrium constants 251

Brief illustration 6A.6: The relation between equilibrium constants 251
(d) Molecular interpretation of the equilibrium constant 251

Brief illustration 6A.7: Contributions to K 252
Checklist of concepts 252
Checklist of equations 252

Why do you need to know this material?
Equilibrium constants lie at the heart of chemistry and are a key point of contact between thermodynamics and laboratory chemistry. The material in this Topic shows how they arise and explains the thermodynamic properties that determine their values.

What is the key idea?
The composition of a reaction mixture tends to change until the Gibbs energy is a minimum.

What do you need to know already?
Underlying the whole discussion is the expression of the direction of spontaneous change in terms of the Gibbs energy of a system (Topic 3C). This material draws on the concept of chemical potential and its dependence on the concentration or pressure of the substance (Topic 5A). You need to know how to express the total Gibbs energy of a mixture in terms of the chemical potentials of its components (Topic 5A).

As explained in Topic 3C, the direction of spontaneous change at constant temperature and pressure is towards lower values of the Gibbs energy, $G$. The idea is entirely general, and in this Topic we apply it to the discussion of chemical reactions. There is a tendency of a mixture of reactants to undergo reaction until the Gibbs energy of the mixture has reached a minimum: that state corresponds to a state of chemical equilibrium. The equilibrium is dynamic in the sense that the forward and reverse reactions continue, but at matching rates. As always in the application of thermodynamics, spontaneity is a tendency: there might be kinetic reasons why that tendency is not realized.

## 6A.1 The Gibbs energy minimum

We locate the equilibrium composition of a reaction mixture by calculating the Gibbs energy of the reaction mixture and identifying the composition that corresponds to minimum G. Here we proceed in two steps: first, we consider a very simple equilibrium, and then we generalize it.

## (a) The reaction Gibbs energy

Consider the equilibrium $\mathrm{A} \rightleftharpoons \mathrm{B}$. Even though this reaction looks trivial, there are many examples of it, such as the isomerization of pentane to 2-methylbutane and the conversion of L-alanine to D-alanine.

Suppose an infinitesimal amount $\mathrm{d} \xi$ of A turns into B, then the change in the amount of A present is $\mathrm{d} n_{\mathrm{A}}=-\mathrm{d} \xi$ and the change in the amount of B present is $\mathrm{d} n_{\mathrm{B}}=+\mathrm{d} \xi$. The quantity $\xi$ (xi) is called the extent of reaction; it has the dimensions of amount of substance and is reported in moles. When the extent of reaction changes by a measurable amount $\Delta \xi$, the amount of A present changes from $n_{\mathrm{A}, 0}$ to $n_{\mathrm{A}, 0}-\Delta \xi$ and the amount of B changes from $n_{\mathrm{B}, 0}$ to $n_{\mathrm{B}, 0}+\Delta \xi$. In general, the amount of a component J changes by $\nu_{\mathrm{J}} \Delta \xi$, where $\nu_{\mathrm{J}}$ is the stoichiometric number of the species J (positive for products, negative for reactants).

## Brief illustration 6A.1 The extent of reaction

If initially 2.0 mol A is present and we wait until $\Delta \xi=+1.5 \mathrm{~mol}$, then the amount of A remaining will be 0.5 mol . The amount of $B$ formed will be 1.5 mol .

Self-test 6A.1 Suppose the reaction is $3 \mathrm{~A} \rightarrow 2 \mathrm{~B}$ and that initially 2.5 mol A is present. What is the composition when $\Delta \xi=+0.5 \mathrm{~mol} ?$

Answer: $1.0 \mathrm{~mol} \mathrm{~A}, 1.0 \mathrm{~mol} \mathrm{~B}$

The reaction Gibbs energy, $\Delta_{\mathrm{r}} G$, is defined as the slope of the graph of the Gibbs energy plotted against the extent of reaction:

$$
\Delta_{\mathrm{r}} G=\left(\frac{\partial G}{\partial \xi}\right)_{p, T} \quad \text { Definition } \quad \text { Reaction Gibbs energy }
$$

Although $\Delta$ normally signifies a difference in values, here it signifies a derivative, the slope of $G$ with respect to $\xi$. However, to see that there is a close relationship with the normal usage, suppose the reaction advances by $\mathrm{d} \xi$. The corresponding change in Gibbs energy is

$$
\mathrm{d} G=\mu_{\mathrm{A}} \mathrm{~d} n_{\mathrm{A}}+\mu_{\mathrm{B}} \mathrm{~d} n_{\mathrm{B}}=-\mu_{\mathrm{A}} \mathrm{~d} \xi+\mu_{\mathrm{B}} \mathrm{~d} \xi=\left(\mu_{\mathrm{B}}-\mu_{\mathrm{A}}\right) \mathrm{d} \xi
$$

This equation can be reorganized into

$$
\left(\frac{\partial G}{\partial \xi}\right)_{p, T}=\mu_{\mathrm{B}}-\mu_{\mathrm{A}}
$$

That is,

$$
\Delta_{\mathrm{r}} G=\mu_{\mathrm{B}}-\mu_{\mathrm{A}}
$$

We see that $\Delta_{\mathrm{r}} G$ can also be interpreted as the difference between the chemical potentials (the partial molar Gibbs energies) of the reactants and products at the current composition of the reaction mixture.

Because chemical potentials vary with composition, the slope of the plot of Gibbs energy against extent of reaction, and therefore the reaction Gibbs energy, changes as the reaction proceeds. The spontaneous direction of reaction lies in the direction of decreasing $G$ (that is, down the slope of $G$ plotted against $\xi$ ). Thus we see from eqn 6A. 2 that the reaction $\mathrm{A} \rightarrow \mathrm{B}$ is spontaneous when $\mu_{\mathrm{A}}>\mu_{\mathrm{B}}$, whereas the reverse reaction is spontaneous when $\mu_{\mathrm{B}}>\mu_{\mathrm{A}}$. The slope is zero, and the reaction is at equilibrium and spontaneous in neither direction, when

$$
\Delta_{\mathrm{r}} G=0
$$

Condition of equilibrium

This condition occurs when $\mu_{\mathrm{B}}=\mu_{\mathrm{A}}$ (Fig. 6A.1). It follows that, if we can find the composition of the reaction mixture that ensures $\mu_{\mathrm{B}}=\mu_{\mathrm{A}}$, then we can identify the composition of the reaction mixture at equilibrium. Note that the chemical potential is now fulfilling the role its name suggests: it represents the potential for chemical change, and equilibrium is attained when these potentials are in balance.

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-03.jpg?height=491&width=812&top_left_y=314&top_left_x=1198)
Figure 6A. 1 As the reaction advances (represented by motion from left to right along the horizontal axis) the slope of the Gibbs energy changes. Equilibrium corresponds to zero slope at the foot of the valley.

## (b) Exergonic and endergonic reactions

The spontaneity of a reaction at constant temperature and pressure can be expressed in terms of the reaction Gibbs energy:

- If $\Delta_{\mathrm{r}} G<0$, the forward reaction is spontaneous.
- If $\Delta_{\mathrm{r}} G>0$, the reverse reaction is spontaneous.
- If $\Delta_{\mathrm{r}} G=0$, the reaction is at equilibrium.

A reaction for which $\Delta_{\mathrm{r}} G<0$ is called exergonic (from the Greek words for work producing). The name signifies that, because the process is spontaneous, it can be used to drive another process, such as another reaction, or used to do nonexpansion work. A simple mechanical analogy is a pair of weights joined by a string (Fig. 6A.2): the lighter of the pair of weights will be pulled up as the heavier weight falls down. Although the lighter weight has a natural tendency to move downward, its coupling to the heavier weight results in it being raised. In biological cells, the oxidation of carbohydrates act as

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-03.jpg?height=414&width=354&top_left_y=1931&top_left_x=1426)
Figure 6A.2 If two weights are coupled as shown here, then the heavier weight will move the lighter weight in its nonspontaneous direction: overall, the process is still spontaneous. The weights are the analogues of two chemical reactions: a reaction with a large negative $\Delta G$ can force another reaction with a smaller $\Delta G$ to run in its non-spontaneous direction.

the heavy weight that drives other reactions forward and results in the formation of proteins from amino acids, muscle contraction, and brain activity. A reaction for which $\Delta_{\mathrm{r}} G>0$ is called endergonic (signifying work consuming). The reaction can be made to occur only by doing work on it, such as electrolysing water to reverse its spontaneous formation reaction.

## Brief illustration 6A. 2 Exergonic and endergonic reactions

The standard Gibbs energy of the reaction $\mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{O}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ at 298 K is $-237 \mathrm{~kJ} \mathrm{~mol}^{-1}$, so the reaction is exergonic and in a suitable device (a fuel cell, for instance) operating at constant temperature and pressure could produce 237 kJ of electrical work for each mole of $\mathrm{H}_{2}$ molecules that react. The reverse reaction, for which $\Delta_{\mathrm{r}} G^{\ominus}=+237 \mathrm{~kJ} \mathrm{~mol}^{-1}$ is endergonic and at least 237 kJ of work must be done to achieve it.

Self-test 6A.2 Classify the formation of methane from its elements as exergonic or endergonic under standard conditions at 298 K .

Answer: Endergonic

## 6A.2 The description of equilibrium

With the background established, we are now ready to see how to apply thermodynamics to the description of chemical equilibrium.

## (a) Perfect gas equilibria

When A and B are perfect gases we can use eqn 5A.14b ( $\mu=\mu^{\ominus}+R T \ln p$, with $p$ interpreted as $p / p^{\ominus}$ ) to write

$$
\begin{aligned}
\Delta_{\mathrm{r}} G & =\mu_{\mathrm{B}}-\mu_{\mathrm{A}}=\left(\mu_{\mathrm{B}}^{\ominus}+R T \ln p_{\mathrm{B}}\right)-\left(\mu_{\mathrm{A}}^{\ominus}+R T \ln p_{\mathrm{A}}\right) \\
& =\Delta_{\mathrm{r}} G^{\ominus}+R T \ln \frac{p_{\mathrm{B}}}{p_{\mathrm{A}}}
\end{aligned}
$$

If we denote the ratio of partial pressures by $Q$, we obtain

$$
\Delta_{\mathrm{r}} G=\Delta_{\mathrm{r}} G^{\ominus}+R T \ln Q \quad Q=\frac{p_{\mathrm{B}}}{p_{\mathrm{A}}}
$$

The ratio $Q$ is an example of a 'reaction quotient', a quantity we define more formally shortly. It ranges from 0 when $p_{\mathrm{B}}=0$ (corresponding to pure A ) to infinity when $p_{\mathrm{A}}=0$ (corresponding to pure B). The standard reaction Gibbs energy, $\Delta_{\mathrm{r}} G^{\ominus}$ (Topic 3C), is the difference in the standard molar Gibbs energies of the reactants and products, so for our reaction

$$
\Delta_{\mathrm{r}} G^{\ominus}=G_{\mathrm{m}}^{\ominus}(\mathrm{B})-G_{\mathrm{m}}^{\ominus}(\mathrm{A})=\mu_{\mathrm{B}}^{\ominus}-\mu_{\mathrm{A}}^{\ominus}
$$

Note that in the definition of $\Delta_{\mathrm{r}} G^{\ominus}$, the $\Delta_{\mathrm{r}}$ has its normal meaning as the difference 'products - reactants'. In Topic 3C we saw that the difference in standard molar Gibbs energies of the products and reactants is equal to the difference in their standard Gibbs energies of formation, so in practice we calculate $\Delta_{\mathrm{r}} G^{\ominus}$ from

$$
\Delta_{\mathrm{r}} G^{\ominus}=\Delta_{\mathrm{f}} G^{\ominus}(\mathrm{B})-\Delta_{\mathrm{f}} G^{\ominus}(\mathrm{A})
$$

At equilibrium, $\Delta_{\mathrm{r}} G=0$. The ratio of partial pressures at equilibrium is denoted $K$, and eqn 6A. 5 becomes

$$
0=\Delta_{\mathrm{r}} G^{\ominus}+R T \ln K
$$

which rearranges to

$$
R T \ln K=-\Delta_{r} G^{\ominus} \quad K=\left(\frac{p_{\mathrm{B}}}{p_{\mathrm{A}}}\right)_{\text {equilibrium }}
$$

This relation is a special case of one of the most important equations in chemical thermodynamics: it is the link between tables of thermodynamic data, such as those in the Resource section, and the chemically important 'equilibrium constant', $K$ (again, a quantity we define formally shortly).

## Brief illustration 6A. 3 The equilibrium constant

The standard Gibbs energy of the isomerization of pentane to 2-methylbutane at 298 K , the reaction $\mathrm{CH}_{3}\left(\mathrm{CH}_{2}\right)_{3} \mathrm{CH}_{3}(\mathrm{~g}) \rightarrow \left(\mathrm{CH}_{3}\right)_{2} \mathrm{CHCH}_{2} \mathrm{CH}_{3}(\mathrm{~g})$, is close to $-6.7 \mathrm{~kJ} \mathrm{~mol}^{-1}$ (this is an estimate based on enthalpies of formation; its actual value is not listed). Therefore, the equilibrium constant for the reaction is

$$
K=\mathrm{e}^{-\left(-6.7 \times 10^{3} \mathrm{~J} \mathrm{~mol}^{-1}\right) /\left(8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times(298 \mathrm{~K})}=\mathrm{e}^{2.7 \cdots}=15
$$

Self-test 6A. 3 Suppose it is found that at equilibrium the partial pressures of A and B in the gas-phase reaction $\mathrm{A} \rightleftharpoons \mathrm{B}$ are equal. What is the value of $\Delta_{\mathrm{r}} G^{\ominus}$ ?

Answer: 0

In molecular terms, the minimum in the Gibbs energy, which corresponds to $\Delta_{\mathrm{r}} G=0$, stems from the Gibbs energy of mixing of the two gases. To see the role of mixing, consider the reaction $\mathrm{A} \rightarrow \mathrm{B}$. If only the enthalpy were important, then $H$ and therefore $G$ would change linearly from its value for pure reactants to its value for pure products. The slope of this straight line is a constant and equal to $\Delta_{\mathrm{r}} G^{\ominus}$ at all stages of the reaction and there is no intermediate minimum in the graph (Fig. 6A.3). However, when the entropy is taken into account, there is an additional contribution to the Gibbs energy that is given by eqn 5A. $16\left(\Delta_{\text {mix }} G=n R T\left(x_{\mathrm{A}} \ln x_{\mathrm{A}}+x_{\mathrm{B}} \ln x_{\mathrm{B}}\right)\right)$. This expression makes a U-shaped contribution to the total change in Gibbs energy.

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-05.jpg?height=491&width=812&top_left_y=314&top_left_x=275)
Figure 6A. 3 If the mixing of reactants and products is ignored, then the Gibbs energy changes linearly from its initial value (pure reactants) to its final value (pure products) and the slope of the line is $\Delta_{\mathrm{r}} G^{\ominus}$. However, as products are produced, there is a further contribution to the Gibbs energy arising from their mixing (lowest curve). The sum of the two contributions has a minimum. That minimum corresponds to the equilibrium composition of the system.

As can be seen from Fig. 6A.3, when it is included there is an intermediate minimum in the total Gibbs energy, and its position corresponds to the equilibrium composition of the reaction mixture.

We see from eqn 6A. 8 that, when $\Delta_{\mathrm{r}} G^{\ominus}>0, K<1$. Therefore, at equilibrium the partial pressure of A exceeds that of B , which means that the reactant A is favoured in the equilibrium. When $\Delta_{\mathrm{r}} G^{\ominus}<0, K>1$, so at equilibrium the partial pressure of $B$ exceeds that of $A$. Now the product $B$ is favoured in the equilibrium.

A note on good practice A common remark is that 'a reaction is spontaneous if $\Delta_{\mathrm{r}} G^{\ominus}<0$ '. However, whether or not a reaction is spontaneous at a particular composition depends on the value of $\Delta_{\mathrm{r}} G$ at that composition, not $\Delta_{\mathrm{r}} G^{\ominus}$. It is far better to interpret the sign of $\Delta_{\mathrm{r}} G^{\ominus}$ as indicating whether $K$ is greater or smaller than 1 . The forward reaction is spontaneous $\left(\Delta_{\mathrm{r}} G<0\right)$ when $Q<K$ and the reverse reaction is spontaneous when $Q>K$.

## (b) The general case of a reaction

We can now extend the argument that led to eqn 6 A .8 to a general reaction. First, we note that a chemical reaction may be expressed symbolically in terms of (signed) stoichiometric numbers as

$$
0=\sum_{\mathrm{J}} v_{\mathrm{J}} \mathrm{~J} \quad \text { Symbolic form Chemical equation }
$$

where J denotes the substances and the $\boldsymbol{\nu}_{\mathrm{J}}$ are the corresponding stoichiometric numbers in the chemical equation. In the reaction $2 \mathrm{~A}+\mathrm{B} \rightarrow 3 \mathrm{C}+\mathrm{D}$, for instance, these numbers have the
values $\nu_{\mathrm{A}}=-2, \nu_{\mathrm{B}}=-1, \nu_{\mathrm{C}}=+3$, and $\nu_{\mathrm{D}}=+1$. A stoichiometric number is positive for products and negative for reactants. Then we define the extent of reaction $\xi$ so that, if it changes by $\Delta \xi$, then the change in the amount of any species J is $v_{\mathrm{J}} \Delta \xi$.

With these points in mind and with the reaction Gibbs energy, $\Delta_{\mathrm{r}} G$, defined in the same way as before (eqn 6A.1) we show in the following Justification that the Gibbs energy of reaction can always be written

$$
\Delta_{\mathrm{r}} G=\Delta_{\mathrm{r}} G^{\ominus}+R T \ln Q \quad \begin{aligned}
& \text { Reaction Gibbs energy } \\
& \text { at an arbitrary stage }
\end{aligned}
$$

with the standard reaction Gibbs energy calculated from

$$
\Delta_{\mathrm{r}} G^{\ominus}=\sum_{\text {Products }} \nu \Delta_{\mathrm{f}} G^{\ominus}-\sum_{\text {Reactants }} \nu \Delta_{\mathrm{f}} G^{\ominus} \begin{aligned}
& \text { Practical } \\
& \text { implemen- } \\
& \text { tation }
\end{aligned} \text { - Reaction } \text { Gibbs }
$$

where the $\nu$ are the (positive) stoichiometric coefficients. More formally,

$$
\Delta_{\mathrm{r}} G^{\ominus}=\sum_{\mathrm{J}} v_{\mathrm{J}} \Delta_{\mathrm{f}} G^{\ominus}(\mathrm{J}) \quad \begin{aligned}
& \text { Formal } \\
& \text { expression }
\end{aligned} \quad \begin{aligned}
& \text { Reaction } \\
& \text { Gibbs } \\
& \text { energy }
\end{aligned}
$$

where the $\nu_{\mathrm{J}}$ are the (signed) stoichiometric numbers. The reaction quotient, $Q$, has the form

$$
Q=\frac{\text { activities of products }}{\text { activities of reactants }} \quad \begin{array}{ll}
\text { General } & \text { Reaction } \\
\text { form } & \text { quotient }
\end{array}
$$

with each species raised to the power given by its stoichiometric coefficient. More formally, to write the general expression for $Q$ we introduce the symbol $\Pi$ to denote the product of what follows it (just as $\Sigma$ denotes the sum), and define $Q$ as

$$
Q=\prod_{\mathrm{J}} a_{\mathrm{J}}^{v_{J^{\prime}}}
$$

Definition Reaction quotient

Because reactants have negative stoichiometric numbers, they automatically appear as the denominator when the product is written out explicitly. Recall from Table 5E. 1 that, for pure solids and liquids, the activity is 1 , so such substances make no contribution to $Q$ even though they may appear in the chemical equation.

## Brief illustration 6A.4 The reaction quotient

Consider the reaction $2 \mathrm{~A}+3 \mathrm{~B} \rightarrow \mathrm{C}+2 \mathrm{D}$, in which case $\nu_{\mathrm{A}}=-2, \nu_{\mathrm{B}}=-3, \nu_{\mathrm{C}}=+1$, and $\nu_{\mathrm{D}}=+2$. The reaction quotient is then

$$
Q=a_{\mathrm{A}}^{-2} a_{\mathrm{B}}^{-3} a_{\mathrm{C}} a_{\mathrm{D}}^{2}=\frac{a_{\mathrm{C}} a_{\mathrm{D}}^{2}}{a_{\mathrm{A}}^{2} a_{\mathrm{B}}^{3}}
$$

Self-test 6A.4 Write the reaction quotient for $\mathrm{A}+2 \mathrm{~B} \rightarrow 3 \mathrm{C}$.
Answer: $Q=a_{C}^{3} / a_{A} a_{B}^{2}$

Justification 6A.1 The dependence of the reaction Gibbs energy on the reaction quotient

Consider a reaction with stoichiometric numbers $\nu_{\mathrm{J}}$. When the reaction advances by $\mathrm{d} \xi$, the amounts of reactants and products change by $\mathrm{d} n_{\mathrm{J}}=\nu_{\mathrm{J}} \mathrm{d} \xi$. The resulting infinitesimal change in the Gibbs energy at constant temperature and pressure is

$$
\mathrm{d} G=\sum_{\mathrm{J}} \mu_{\mathrm{J}} \mathrm{~d} n_{\mathrm{J}}=\sum_{\mathrm{J}} \mu_{\mathrm{J}} v_{\mathrm{J}} \mathrm{~d} \xi=\left(\sum_{\mathrm{J}} \mu_{\mathrm{J}} v_{\mathrm{J}}\right) \mathrm{d} \xi
$$

It follows that

$$
\Delta_{\mathrm{r}} G=\left(\frac{\partial G}{\partial \xi}\right)_{p, T}=\sum_{\mathrm{J}} v_{\mathrm{J}} \mu_{\mathrm{J}}
$$

To make progress, we note that the chemical potential of a species J is related to its activity by eqn 5 E .9 ( $\mu_{\mathrm{J}}=\mu_{\mathrm{J}}^{\ominus}+R T \ln a_{\mathrm{J}}$ ). When this expression is substituted into eqn 6A.11 we obtain

$$
\begin{aligned}
\Delta_{\mathrm{r}} G & =\overbrace{\sum_{\mathrm{J}} v_{\mathrm{J}} \mu_{\mathrm{J}}^{\ominus}}^{\Delta_{\mathrm{J}} G^{\ominus}}+R T \sum_{\mathrm{J}} v_{\mathrm{J}} \ln a_{\mathrm{J}} \\
& =\Delta_{\mathrm{r}} G^{\ominus}+R T \sum_{\mathrm{J}} v_{\mathrm{J}} \ln a_{\mathrm{J}}=\Delta_{\mathrm{r}} G^{\ominus}+R T \ln \overbrace{\prod_{\mathrm{J}} a_{\mathrm{J}}^{v_{\mathrm{J}}}}^{0} \\
& =\Delta_{\mathrm{r}} G^{\ominus}+R T \ln Q
\end{aligned}
$$

In the second line we use first $a \ln x=\ln x^{a}$ and then $\ln x+\ln y+\ldots=\ln x y \ldots$, so

$$
\sum_{i} \ln x_{i}=\ln \left(\prod_{i} x_{i}\right)
$$

Now we conclude the argument, starting from eqn 6A.10. At equilibrium, the slope of $G$ is zero: $\Delta_{\mathrm{r}} G=0$. The activities then have their equilibrium values and we can write

$$
K=\left(\prod_{\mathrm{J}} a_{\mathrm{J}}^{v_{\mathrm{J}}}\right)_{\text {equilibrium }} \text { Definition Equilibrium constant }
$$

This expression has the same form as $Q$ but is evaluated using equilibrium activities. From now on, we shall not write the 'equilibrium' subscript explicitly, and will rely on the context to make it clear that for $K$ we use equilibrium values and for $Q$ we use the values at the specified stage of the reaction. An equilibrium constant $K$ expressed in terms of activities (or fugacities) is called a thermodynamic equilibrium constant. Note that, because activities are dimensionless numbers, the thermodynamic equilibrium constant is also dimensionless. In elementary applications, the activities that occur in eqn 6A. 13 are often replaced as follows:

| State | Measure | Approximation <br> for $a_{\mathrm{J}}$ | Definition |
| :--- | :--- | :--- | :--- |
| Solute | molality | $b_{\mathrm{J}} / b_{\mathrm{J}}^{\ominus}$ | $b^{\ominus}=1 \mathrm{~mol} \mathrm{~kg}^{-1}$ |
|  | molar concentration | $\left[\mathrm{J} / c^{\ominus}\right.$ | $c^{\ominus}=1 \mathrm{~mol} \mathrm{dm}^{-3}$ |
| Gas phase | partial pressure | $p_{\mathrm{J}} / p^{\ominus}$ | $p^{\ominus}=1 \mathrm{bar}$ |

In such cases, the resulting expressions are only approximations. The approximation is particularly severe for electrolyte solutions, for in them activity coefficients differ from 1 even in very dilute solutions (Topic 5F).

## Brief illustration 6A.5 The equilibrium constant

The equilibrium constant for the heterogeneous equilibrium $\mathrm{CaCO}_{3}(\mathrm{~s}) \rightleftharpoons \mathrm{CaO}(\mathrm{s})+\mathrm{CO}_{2}(\mathrm{~g})$ is

$$
K=a_{\mathrm{CaCO}_{3}(\mathrm{~s})}^{-1} a_{\mathrm{CaO}(\mathrm{~s})} a_{\mathrm{CO}_{2}(\mathrm{~g})}=\frac{\overbrace{a_{\mathrm{CaO}(\mathrm{~s})}}^{1} a_{\mathrm{CO}_{2}(\mathrm{~g})}}{\underbrace{a_{\mathrm{CaCO}(\mathrm{~s})}}_{1}}=a_{\mathrm{CO}_{2}(\mathrm{~g})}
$$

Provided the carbon dioxide can be treated as a perfect gas, we can go on to write

$$
K=p_{\mathrm{CO}_{2}} / p^{\ominus}
$$

and conclude that in this case the equilibrium constant is the numerical value of the decomposition vapour pressure of calcium carbonate.

Self-test 6A.5 Write the equilibrium constant for the reaction $\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NH}_{3}(\mathrm{~g})$, with the gases treated as perfect.

$$
\text { Answer: } K=a_{\mathrm{NH}_{3}}^{2} / a_{\mathrm{N}_{2}} a_{\mathrm{H}_{2}}^{3}=p_{\mathrm{NH}_{3}}^{2} p^{\ominus 2} / p_{\mathrm{N}_{2}} p_{\mathrm{H}_{2}}^{3}
$$

At this point we set $\Delta_{\mathrm{r}} G=0$ in eqn 6A. 10 and replace $Q$ by $K$. We immediately obtain

$$
\Delta_{\mathrm{r}} G^{\ominus}=-R T \ln K \quad \text { Thermodynamic equilibrium constant }
$$

This is an exact and highly important thermodynamic relation, for it enables us to calculate the equilibrium constant of any reaction from tables of thermodynamic data, and hence to predict the equilibrium composition of the reaction mixture. In Topic 15F we see that the right-hand side of eqn 6 A .14 may be expressed in terms of spectroscopic data for gas-phase species; so this expression also provides a link between spectroscopy and equilibrium composition.

## Example 6A. 1 Calculating an equilibrium constant

Calculate the equilibrium constant for the ammonia synthesis reaction, $\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NH}_{3}(\mathrm{~g})$, at 298 K and show how K is related to the partial pressures of the species at equilibrium
when the overall pressure is low enough for the gases to be treated as perfect.

Method Calculate the standard reaction Gibbs energy from eqn 6A. 10 and convert it to the value of the equilibrium constant by using eqn 6A.14. The expression for the equilibrium constant is obtained from eqn 6A.13, and because the gases are taken to be perfect, we replace each activity by the ratio $p_{\mathrm{J}} / p^{\ominus}$, where $p_{\mathrm{J}}$ is the partial pressure of species J .

Answer The standard Gibbs energy of the reaction is

$$
\begin{aligned}
\Delta_{\mathrm{r}} G^{\ominus} & =2 \Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{NH}_{3}, \mathrm{~g}\right)-\left\{\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{N}_{2}, \mathrm{~g}\right)+3 \Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{H}_{2}, \mathrm{~g}\right)\right\} \\
& =2 \Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{NH}_{3}, \mathrm{~g}\right)=2 \times\left(-16.45 \mathrm{~kJ} \mathrm{~mol}^{-1}\right)
\end{aligned}
$$

Then,
$\ln K=-\frac{2 \times\left(-1.645 \times 10^{4} \mathrm{~J} \mathrm{~mol}^{-1}\right)}{\left(8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times(298 \mathrm{~K})}=\frac{2 \times 1.645 \times 10^{4}}{8.3145 \times 298}=13.2 \ldots$
Hence, $K=5.8 \times 10^{5}$. This result is thermodynamically exact. The thermodynamic equilibrium constant for the reaction is

$$
K=\frac{a_{\mathrm{NH}_{3}}^{2}}{a_{\mathrm{N}_{2}} a_{\mathrm{H}_{2}}^{3}}
$$

and this ratio has the value we have just calculated. At low overall pressures, the activities can be replaced by the ratios $p_{\mathrm{J}} / p^{\ominus}$ and an approximate form of the equilibrium constant is

$$
K=\frac{\left(p_{\mathrm{NH}_{3}} / p^{\ominus}\right)^{2}}{\left(p_{\mathrm{N}_{2}} / p^{\ominus}\right)\left(p_{\mathrm{H}_{2}} / p^{\ominus}\right)^{3}}=\frac{p_{\mathrm{NH}_{3}}^{2} p^{\ominus 2}}{p_{\mathrm{N}_{2}} p_{\mathrm{H}_{2}}^{3}}
$$

Self-test 6A.6 Evaluate the equilibrium constant for $\mathrm{N}_{2} \mathrm{O}_{4}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NO}_{2}(\mathrm{~g})$ at 298 K .

Answer: $K=0.15$

## Example 6A. 2 Estimating the degree of dissociation

at equilibrium
The degree of dissociation (or extent of dissociation, $\alpha$ ) is defined as the fraction of reactant that has decomposed; if the initial amount of reactant is $n$ and the amount at equilibrium is $n_{\text {eq }}$, then $\alpha=\left(n-n_{\text {eq }}\right) / n$. The standard reaction Gibbs energy for the decomposition $\mathrm{H}_{2} \mathrm{O}(\mathrm{g}) \rightarrow \mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{O}_{2}(\mathrm{~g})$ is $+118.08 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 2300 K . What is the degree of dissociation of $\mathrm{H}_{2} \mathrm{O}$ at 2300 K and 1.00 bar?

Method The equilibrium constant is obtained from the standard Gibbs energy of reaction by using eqn 6A.11, so the task is to relate the degree of dissociation, $\alpha$, to $K$ and then to find its numerical value. Proceed by expressing the equilibrium compositions in terms of $\alpha$, and solve for $\alpha$ in terms of $K$. Because the standard reaction Gibbs energy is large and positive, we can anticipate that $K$ will be small, and hence that $\alpha \ll 1$,
which opens the way to making approximations to obtain its numerical value.

Answer The equilibrium constant is obtained from eqn 6A. 14 in the form

$$
\begin{aligned}
\ln K & =-\frac{\Delta_{\mathrm{r}} G^{\ominus}}{R T}=-\frac{1.1808 \times 10^{5} \mathrm{~J} \mathrm{~mol}^{-1}}{\left(8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times(2300 \mathrm{~K})} \\
& =-\frac{1.1808 \times 10^{5}}{8.3145 \times 2300}=-6.17 \ldots
\end{aligned}
$$

It follows that $K=2.08 \times 10^{-3}$. The equilibrium composition can be expressed in terms of $\alpha$ by drawing up the following table:

|  | $\mathrm{H}_{2} \mathrm{O}$ | $\mathrm{H}_{2}$ | $+\frac{1}{2} \mathrm{O}_{2}$ |  |
| :--- | :--- | :--- | :--- | :--- |
| Initial amount | $n$ | 0 | 0 |  |
| Change to reach equilibrium | $-\alpha n$ | $+\alpha n$ | $+\frac{1}{2} \alpha n$ |  |
| Amount at equilibrium | $(1-\alpha) n$ | $\alpha n$ | $\frac{1}{2} \alpha n$ | Total: $\left(1+\frac{1}{2} \alpha\right) n$ |
| Mole fraction, $x_{\mathrm{J}}$ | $\frac{1-\alpha}{1+\frac{1}{2} \alpha}$ | $\frac{\alpha}{1+\frac{1}{2}}$ | $\frac{\frac{1}{2} \alpha}{1+\frac{1}{2} \alpha}$ |  |
| Partial pressure, $p_{\mathrm{J}}$ | $\frac{(1-\alpha) p}{1+\frac{1}{2} \alpha}$ | $\frac{\alpha p}{1+\frac{1}{2}}$ | $\frac{\frac{1}{2} \alpha p}{1+\frac{1}{2} \alpha}$ |  |

where, for the entries in the last row, we have used $p_{\mathrm{J}}=x_{\mathrm{J}} p$ (eqn 1A.8). The equilibrium constant is therefore

$$
K=\frac{p_{\mathrm{H}_{2}} p_{\mathrm{O}_{2}}^{1 / 2}}{p_{\mathrm{H}_{2} \mathrm{O}}}=\frac{\alpha^{3 / 2} p^{1 / 2}}{(1-\alpha)(2+\alpha)^{1 / 2}}
$$

In this expression, we have written $p$ in place of $p / p^{\ominus}$, to simplify its appearance. Now make the approximation that $\alpha \ll 1$, and hence obtain

$$
K \approx \frac{\alpha^{3 / 2} p^{1 / 2}}{2^{1 / 2}}
$$

Under the stated condition, $p=1.00$ bar (that is, $p / p^{\ominus}=1.00$ ), so $\alpha \approx\left(2^{1 / 2} K\right)^{2 / 3}=0.0205$. That is, about 2 per cent of the water has decomposed.

A note on good practice Always check that the approximation is consistent with the final answer. In this case $\alpha \ll 1$, in accord with the original assumption.

Self-test 6A.7 Given that the standard Gibbs energy of reaction at 2000 K is $+135.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$ for the same reaction, suppose that steam at 200 kPa is passed through a furnace tube at that temperature. Calculate the mole fraction of $\mathrm{O}_{2}$ present in the output gas stream.

Answer: 0.00221

## (c) The relation between equilibrium constants

Equilibrium constants in terms of activities are exact, but it is often necessary to relate them to concentrations. Formally, we need to know the activity coefficients, and then to use $a_{\mathrm{J}}=\gamma_{\mathrm{J}} x_{\mathrm{J}}$, $a_{\mathrm{J}}=\gamma_{\mathrm{J}} b_{\mathrm{J}} / b^{\ominus}$, or $a_{\mathrm{J}}=[\mathrm{J}] / c^{\ominus}$, where $x_{\mathrm{J}}$ is a mole fraction, $b_{\mathrm{J}}$ is a molality, and [J] is a molar concentration. For example, if we were interested in the composition in terms of molality for an equilibrium of the form $\mathrm{A}+\mathrm{B} \rightleftharpoons \mathrm{C}+\mathrm{D}$, where all four species are solutes, we would write

$$
K=\frac{a_{\mathrm{C}} a_{\mathrm{D}}}{a_{\mathrm{A}} a_{\mathrm{B}}}=\frac{\gamma_{\mathrm{C}} \gamma_{\mathrm{D}}}{\gamma_{\mathrm{A}} \gamma_{\mathrm{B}}} \times \frac{b_{\mathrm{C}} b_{\mathrm{D}}}{b_{\mathrm{A}} b_{\mathrm{B}}}=K_{\gamma} K_{b}
$$

The activity coefficients must be evaluated at the equilibrium composition of the mixture (for instance, by using one of the Debye-Hückel expressions, Topic 5F), which may involve a complicated calculation, because the activity coefficients are known only if the equilibrium composition is already known. In elementary applications, and to begin the iterative calculation of the concentrations in a real example, the assumption is often made that the activity coefficients are all so close to unity that $K_{\gamma}=1$. Then we obtain the result widely used in elementary chemistry that $K \approx K_{b}$, and equilibria are discussed in terms of molalities (or molar concentrations) themselves.

A special case arises when we need to express the equilibrium constant of a gas-phase reaction in terms of molar concentrations instead of the partial pressures that appear in the thermodynamic equilibrium constant. Provided we can treat the gases as perfect, the $p_{\mathrm{I}}$ that appear in $K$ can be replaced by [J]RT, and

$$
\begin{aligned}
K & =\prod_{\mathrm{J}} a_{\mathrm{J}}^{v_{J}}=\prod_{\mathrm{J}}\left(\frac{p_{\mathrm{J}}}{p^{\ominus}}\right)^{v_{J}}=\prod_{\mathrm{J}}[\mathrm{~J}]^{v_{J}}\left(\frac{R T}{p^{\ominus}}\right)^{v_{J}} \\
& =\prod_{\mathrm{J}}[\mathrm{~J}]^{v_{J}} \times \prod_{\mathrm{J}}\left(\frac{R T}{p^{\ominus}}\right)^{v_{J}}
\end{aligned}
$$

(Products can always be factorized like that: $a b c d e f$ is the same as $a b c \times d e f$. ) The (dimensionless) equilibrium constant $K_{c}$ is defined as

$$
K_{c}=\prod_{\mathrm{J}}\left(\frac{[\mathrm{~J}]}{c^{\ominus}}\right)^{\nu_{\mathrm{J}}} \quad \text { Definition } \quad K_{\mathrm{c}} \text { for gas-phase reactions }
$$

It follows that

$$
K=K_{c} \times \prod_{J}\left(\frac{c^{\ominus} R T}{p^{\ominus}}\right)^{v_{j}}
$$

If now we write $\Delta \nu=\Sigma_{J} \nu_{J}$, which is easier to think of as $\nu$ (products) $-\nu$ (reactants), then the relation between $K$ and $K_{c}$ for a gas-phase reaction is

$$
K=K_{c} \times\left(\frac{c^{\ominus} R T}{p^{\ominus}}\right)^{\Delta v} \quad \begin{aligned}
& \text { Relation between } K \text { and } \\
& K_{c} \text { for gas-phase reactions }
\end{aligned}
$$

(6A.17b)

The term in parentheses works out as $T /(12.03 \mathrm{~K})$.
Brief illustration 6A. 6 The relation between equilibrium constants

For the reaction $\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{NH}_{3}(\mathrm{~g}), \Delta v=2-4=-2$, so

$$
K=K_{c} \times\left(\frac{T}{12.03 \mathrm{~K}}\right)^{-2}=K_{c} \times\left(\frac{12.03 \mathrm{~K}}{T}\right)^{2}
$$

At 298.15 K the relation is

$$
K=K_{c} \times\left(\frac{12.03 \mathrm{~K}}{298.15 \mathrm{~K}}\right)^{2}=\frac{K_{c}}{614.2}
$$

so $K_{c}=614.2 K$. Note that both $K$ and $K_{c}$ are dimensionless.
Self-test 6A.8 Find the relation between $K$ and $K_{\mathrm{c}}$ for the equilibrium $\mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{O}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ at 298 K .

Answer: $K_{c}=123 K$

## (d) Molecular interpretation of the equilibrium constant

Deeper insight into the origin and significance of the equilibrium constant can be obtained by considering the Boltzmann distribution of molecules over the available states of a system composed of reactants and products (Foundations B). When atoms can exchange partners, as in a reaction, the available states of the system include arrangements in which the atoms are present in the form of reactants and in the form of products: these arrangements have their characteristic sets of energy levels, but the Boltzmann distribution does not distinguish between their identities, only their energies. The atoms distribute themselves over both sets of energy levels in accord with the Boltzmann distribution (Fig. 6A.4). At a given temperature, there will be a specific distribution of populations, and hence a specific composition of the reaction mixture.

It can be appreciated from the illustration that, if the reactants and products both have similar arrays of molecular energy levels, then the dominant species in a reaction mixture at equilibrium will be the species with the lower set of energy levels. However, the fact that the Gibbs energy occurs in the expression is a signal that entropy plays a role as well as energy. Its role can be appreciated by referring to Fig. 6A.4. In Fig. 6A.4b we see that, although the B energy levels lie higher than the A energy levels, in this instance they are much more closely spaced. As a result, their total population may be considerable and B could even dominate in the reaction mixture at equilibrium. Closely spaced energy levels correlate with a high

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-09.jpg?height=477&width=853&top_left_y=309&top_left_x=255)
Figure 6A.4 The Boltzmann distribution of populations over the energy levels of two species $A$ and $B$ with similar densities of energy levels. The reaction $A \rightarrow B$ is endothermic in this example. (a) The bulk of the population is associated with the species A, so that species is dominant at equilibrium. (b) Even though the reaction $A \rightarrow B$ is endothermic, the density of energy levels in $B$ is so much greater than that in $A$ that the population associated with $B$ is greater than that associated with $A$, so $B$ is dominant at equilibrium.

entropy (Topic 15E), so in this case we see that entropy effects dominate adverse energy effects. This competition is mirrored in eqn 6A.14, as can be seen most clearly by using $\Delta_{\mathrm{r}} G^{\ominus}= \Delta_{\mathrm{r}} H^{\ominus}-T \Delta_{\mathrm{r}} S^{\ominus}$ and writing it in the form

$$
K=\mathrm{e}^{-\Delta_{\mathrm{r}} H^{\ominus} / R T} \mathrm{e}^{\Delta_{\mathrm{r}} S^{\ominus} / R}
$$

Note that a positive reaction enthalpy results in a lowering of the equilibrium constant (that is, an endothermic reaction can be expected to have an equilibrium composition that favours the reactants). However, if there is positive reaction entropy, then the equilibrium composition may favour products, despite the endothermic character of the reaction.

## Brief illustration 6A. 7 Contributions to $K$

In Example 6A. 1 it is established that $\Delta_{\mathrm{r}} G^{\ominus}=-33.0 \mathrm{~kJ} \mathrm{~mol}^{-1}$ for the reaction $\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NH}_{3}(\mathrm{~g})$ at 298 K . From the tables of data in the Resource section, we can find that $\Delta_{\mathrm{r}} H^{\ominus}=-92.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$ and $\Delta_{\mathrm{r}} S^{\ominus}=-198.8 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. The contributions to $K$ are therefore

$$
\begin{aligned}
K= & \mathrm{e}^{-\left(-9.22 \times 10^{4} \mathrm{Jmol}^{-1}\right) /\left(8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times(298 \mathrm{~K})} \\
& \times \mathrm{e}^{\left(-198.8 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) /\left(8.3145 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}\right)} \\
= & \mathrm{e}^{37.2 \cdots} \times \mathrm{e}^{-23.9 \cdots}
\end{aligned}
$$

We see that the exothermic character of the reaction encourages the formation of products (it results in a large increase in entropy of the surroundings) but the decrease in entropy of the system as H atoms are pinned to N atoms opposes their formation.

Self-test 6A.9 Analyse the equilibrium $\mathrm{N}_{2} \mathrm{O}_{4}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NO}_{2}(\mathrm{~g})$ similarly.

Answer: $K=\mathrm{e}^{-26.7 \cdots} \times \mathrm{e}^{21.1 \cdots}$; enthalpy opposes, entropy encourages

## Checklist of concepts

□ 1. The reaction Gibbs energy is the slope of the plot of Gibbs energy against extent of reaction.
□ 4. When the reaction Gibbs energy is zero the reaction quotient has a value called the equilibrium constant.
□ 2. Reactions are either exergonic or endergonic.
□ 3. The reaction Gibbs energy depends logarithmically on the reaction quotient.
□ 5. Under ideal conditions, the thermodynamic equilibrium constant may be approximated by expressing it in terms of concentrations and partial pressures.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Reaction Gibbs energy | $\Delta_{\mathrm{r}} G=(\partial G / \partial \xi)_{p, T}$ | Definition | 6A. 1 |
| Reaction Gibbs energy | $\Delta_{\mathrm{r}} G=\Delta_{\mathrm{r}} G^{\ominus}+R T \ln Q$ |  | 6A. 10 |
| Standard reaction Gibbs energy | $\begin{aligned} \Delta_{\mathrm{r}} G^{\ominus} & =\sum_{\text {Products }} v \Delta_{\mathrm{f}} G^{\ominus}-\sum_{\text {Reactants }} v \Delta_{\mathrm{f}} G^{\ominus} \quad v \text { are positive; } v_{\mathrm{J}} \text { are signed } \\ & =\sum_{\mathrm{J}} v_{\mathrm{J}} \Delta_{\mathrm{f}} G^{\ominus}(\mathrm{J}) \end{aligned}$ |  | 6A. 11 |


| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Reaction quotient | $Q=\prod_{\mathrm{J}} a_{\mathrm{J}}^{\nu_{\mathrm{J}}}$ | Definition; evaluated at arbitrary stage of reaction | 6A. 12 |
| Thermodynamic equilibrium constant | $K=\left(\prod_{\mathrm{J}} a_{\mathrm{J}}^{v_{\mathrm{J}}}\right)_{\text {equilibrium }}$ | Definition | 6A. 13 |
| Equilibrium constant | $\Delta_{\mathrm{r}} G^{\ominus}=-R T \ln K$ |  | 6A. 14 |
| Relation between $K$ and $K_{c}$ | $K=K_{c}\left(c^{\ominus} R T / p^{\ominus}\right)^{\Delta v}$ | Gas-phase reactions; perfect gases | 6A.17b |

## 6B The response of equilibria to the conditions

## Contents

6B. 1 The response to pressure ..... 254
Brief illustration 6B.1: Le Chatelier's principle ..... 255
68.2 The response to temperature ..... 255
(a) The van 't Hoff equation ..... 256
Example 6B.1: Measuring a reaction enthalpy ..... 257
(b) The value of $K$ at different temperatures ..... 257
Brief illustration 6B.2: The temperature dependence of $K$ ..... 257
Checklist of concepts ..... 258
Checklist of equations ..... 258

## Why do you need to know this material?

Chemists, and chemical engineers designing a chemical plant, need to know how an equilibrium will respond to changes in the conditions, such as a change in pressure or temperature. The variation with temperature also provides a way to determine the enthalpy and entropy of a reaction.

## What is the key idea?

A system at equilibrium, when subjected to a disturbance, responds in a way that tends to minimize the effect of the disturbance.

## What do you need to know already?

This Topic builds on the relation between the equilibrium constant and the standard Gibbs energy of reaction (Topic 6 A ). To express the temperature dependence of $K$ it draws on the Gibbs-Helmholtz equation (Topic 3D).

The equilibrium constant for a reaction is not affected by the presence of a catalyst or an enzyme (a biological catalyst). As explained in detail in Topics 20 H and 22C, catalysts increase the rate at which equilibrium is attained but do not affect its position. However, it is important to note that in industry reactions rarely reach equilibrium, partly on account of the rates at which reactants mix. The equilibrium constant is also independent of pressure, but as we shall see, that does not necessarily mean
that the composition at equilibrium is independent of pressure. The equilibrium constant does depend on the temperature in a manner that can be predicted from the standard reaction enthalpy.

## 6B. 1 The response to pressure

The equilibrium constant depends on the value of $\Delta_{\mathrm{r}} G^{\ominus}$, which is defined at a single, standard pressure. The value of $\Delta_{\mathrm{r}} G^{\ominus}$, and hence of $K$, is therefore independent of the pressure at which the equilibrium is actually established. In other words, at a given temperature $K$ is a constant.

The conclusion that $K$ is independent of pressure does not necessarily mean that the equilibrium composition is independent of the pressure, and the effect depends on how the pressure is applied.

The pressure within a reaction vessel can be increased by injecting an inert gas into it. However, so long as the gases are perfect, this addition of gas leaves all the partial pressures of the reacting gases unchanged: the partial pressures of a perfect gas is the pressure it would exert if it were alone in the container, so the presence of another gas has no effect. It follows that pressurization by the addition of an inert gas has no effect on the equilibrium composition of the system (provided the gases are perfect).

Alternatively, the pressure of the system may be increased by confining the gases to a smaller volume (that is, by compression). Now the individual partial pressures are changed but their ratio (as it appears in the equilibrium constant) remains the same. Consider, for instance, the perfect gas equilibrium $\mathrm{A} \rightleftharpoons 2 \mathrm{~B}$, for which the equilibrium constant is

$$
K=\frac{p_{\mathrm{B}}^{2}}{p_{\mathrm{A}} p^{\ominus}}
$$

The right-hand side of this expression remains constant only if an increase in $p_{\mathrm{A}}$ cancels an increase in the square of $p_{\mathrm{B}}$. This relatively steep increase of $p_{\mathrm{A}}$ compared to $p_{\mathrm{B}}$ will occur if the equilibrium composition shifts in favour of A at the expense of B. Then the number of A molecules will increase as the volume of the container is decreased and its partial pressure will rise

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-12.jpg?height=441&width=480&top_left_y=302&top_left_x=482)
Figure 6B. 1 When a reaction at equilibrium is compressed (from $a$ to $b$ ), the reaction responds by reducing the number of molecules in the gas phase (in this case by producing the dimers represented by the linked spheres).

more rapidly than can be ascribed to a simple change in volume alone (Fig. 6B.1).

The increase in the number of A molecules and the corresponding decrease in the number of $B$ molecules in the equilibrium $\mathrm{A} \rightleftharpoons 2 \mathrm{~B}$ is a special case of a principle proposed by the French chemist Henri Le Chatelier, which states that:

> A system at equilibrium, when subjected to a disturbance, responds in a way that tends to minimize the effect of the disturbance.
Le Chatelier's principle

The principle implies that, if a system at equilibrium is compressed, then the reaction will adjust so as to minimize the increase in pressure. This it can do by reducing the number of particles in the gas phase, which implies a shift $\mathrm{A} \leftarrow 2 \mathrm{~B}$.

To treat the effect of compression quantitatively, we suppose that there is an amount $n$ of A present initially (and no B). At equilibrium the amount of A is $(1-\alpha) n$ and the amount of B is $2 \alpha n$, where $\alpha$ is the degree of dissociation of A into 2B. It follows that the mole fractions present at equilibrium are

$$
x_{\mathrm{A}}=\frac{(1-\alpha) n}{(1-\alpha) n+2 \alpha n}=\frac{1-\alpha}{1+\alpha} \quad x_{\mathrm{B}}=\frac{2 \alpha}{1+\alpha}
$$

The equilibrium constant for the reaction is

$$
K=\frac{p_{\mathrm{B}}^{2}}{p_{\mathrm{A}} p^{\ominus}}=\frac{x_{\mathrm{B}}^{2} p^{2}}{x_{\mathrm{A}} p p^{\ominus}}=\frac{4 \alpha^{2}\left(p / p^{\ominus}\right)}{1-\alpha^{2}}
$$

which rearranges to

$$
\alpha=\left(\frac{1}{1+4 p / K p^{\ominus}}\right)^{1 / 2}
$$

This formula shows that, even though $K$ is independent of pressure, the amounts of A and B do depend on pressure (Fig. 6B.2). It also shows that as $p$ is increased, $\alpha$ decreases, in accord with Le Chatelier's principle.

## Brief illustration 6B. 1 Le Chatelier's principle

To predict the effect of an increase in pressure on the composition of the ammonia synthesis at equilibrium, Example 6A.1, we note that the number of gas molecules decreases (from 4 to 2 ). So, Le Chatelier's principle predicts that an increase in pressure will favour the product. The equilibrium constant is

$$
K=\frac{p_{\mathrm{NH}_{3}}^{2} p^{\ominus}}{p_{\mathrm{N}_{2}} p_{\mathrm{H}_{2}}^{3}}=\frac{x_{\mathrm{NH}_{3}}^{2} p^{2} p^{\ominus 2}}{x_{\mathrm{N}_{2}}^{2} x_{\mathrm{H}_{2}}^{3} p^{4}}=\frac{x_{\mathrm{NH}_{3}}^{2} p^{\ominus 2}}{x_{\mathrm{N}_{2}} x_{\mathrm{H}_{2}}^{3} p^{2}}=K_{x} \times \frac{p^{\ominus 2}}{p^{2}}
$$

where $K_{x}$ is the part of the equilibrium constant expression that contains the equilibrium mole fractions of reactants and products (note that, unlike $K$ itself, $K_{x}$ is not an equilibrium constant). Therefore, doubling the pressure must increase $K_{x}$ by a factor of 4 to preserve the value of $K$.

Self-test 6B. 1 Predict the effect of a tenfold pressure increase on the equilibrium composition of the reaction $3 \mathrm{~N}_{2}(\mathrm{~g})+\mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{~N}_{3} \mathrm{H}(\mathrm{g})$.

Answer: 100 -fold increase in $K_{x}$

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-12.jpg?height=525&width=853&top_left_y=1257&top_left_x=1221)
Figure 6B. 2 The pressure dependence of the degree of dissociation, $\alpha$, at equilibrium for an $\mathrm{A}(\mathrm{g}) \rightleftharpoons 2 \mathrm{~B}(\mathrm{~g})$ reaction for different values of the equilibrium constant $K$. The value $\alpha=0$ corresponds to pure A; $\alpha=1$ corresponds to pure B

### 68.2 The response to temperature

Le Chatelier's principle predicts that a system at equilibrium will tend to shift in the endothermic direction if the temperature is raised, for then energy is absorbed as heat and the rise in temperature is opposed. Conversely, an equilibrium can be expected to shift in the exothermic direction if the temperature is lowered, for then energy is released and the reduction in temperature is opposed. These conclusions can be summarized as follows:

Exothermic reactions: increased temperature favours the reactants.

Endothermic reactions: increased temperature favours the products.

We shall now justify these remarks thermodynamically and see how to express the changes quantitatively.

## (a) The van 't Hoff equation

The van 't Hoff equation, which is derived in the following Justification, is an expression for the slope of a plot of the equilibrium constant (specifically, $\ln K$ ) as a function of temperature. It may be expressed in either of two ways:

$$
\begin{array}{lr}
\frac{\mathrm{d} \ln K}{\mathrm{~d} T}=\frac{\Delta_{\mathrm{r}} H^{\ominus}}{R T^{2}} & \text { van 't Hoff equation } \\
\frac{\mathrm{d} \ln K}{\mathrm{~d}(1 / T)}=-\frac{\Delta_{\mathrm{r}} H^{\ominus}}{R} & \begin{array}{l}
\text { Alternative } \\
\text { version }
\end{array} \\
\text { van 't Hoff } \\
\text { equation }
\end{array}
$$

## Justification 6B. 1 The van 't Hoff equation

From eqn 6A.14, we know that

$$
\ln K=-\frac{\Delta_{\mathrm{r}} G^{\ominus}}{R T}
$$

Differentiation of $\ln K$ with respect to temperature then gives

$$
\frac{\mathrm{d} \ln K}{\mathrm{~d} T}=-\frac{1}{R} \frac{\mathrm{~d}\left(\Delta_{\mathrm{r}} \mathrm{G}^{\ominus} / T\right)}{\mathrm{d} T}
$$

The differentials are complete (that is, they are not partial derivatives) because $K$ and $\Delta_{\mathrm{r}} G^{\ominus}$ depend only on temperature, not on pressure. To develop this equation we use the GibbsHelmholtz equation (eqn 3D.10, $\mathrm{d}(\Delta G / T)=-\Delta H / T^{2}$ ) in the form

$$
\frac{\mathrm{d}\left(\Delta_{\mathrm{r}} G^{\ominus} / T\right)}{\mathrm{d} T}=-\frac{\Delta_{\mathrm{r}} H^{\ominus}}{R}
$$

where $\Delta_{\mathrm{r}} H^{\ominus}$ is the standard reaction enthalpy at the temperature $T$. Combining the two equations gives the van 't Hoff equation, eqn 6B.2a. The second form of the equation is obtained by noting that

$$
\frac{\mathrm{d}(1 / T)}{\mathrm{d} T}=-\frac{1}{T^{2}}, \quad \text { so } \mathrm{d} T=-T^{2} \mathrm{~d}(1 / T)
$$

It follows that eqn 6B.2a can be rewritten as

$$
-\frac{\mathrm{d} \ln K}{T^{2} \mathrm{~d}(1 / T)}=\frac{\Delta_{\mathrm{r}} H^{\ominus}}{R T^{2}}
$$

which simplifies into eqn 6B.2b.

Equation 6B.2a shows that $\mathrm{d} \ln K / \mathrm{d} T<0$ (and therefore that $\mathrm{d} K / \mathrm{d} T<0$ ) for a reaction that is exothermic under standard
conditions ( $\Delta_{\mathrm{r}} H^{\ominus}<0$ ). A negative slope means that $\ln K$, and therefore $K$ itself, decreases as the temperature rises. Therefore, as asserted above, in the case of an exothermic reaction the equilibrium shifts away from products. The opposite occurs in the case of endothermic reactions.

Insight into the thermodynamic basis of this behaviour comes from the expression $\Delta_{\mathrm{r}} G^{\ominus}=\Delta_{\mathrm{r}} H^{\ominus}-T \Delta_{\mathrm{r}} S^{\ominus}$ written in the form $-\Delta_{\mathrm{r}} G^{\ominus} / T=-\Delta_{\mathrm{r}} H^{\ominus} / T+\Delta_{\mathrm{r}} S^{\ominus}$. When the reaction is exothermic, $-\Delta_{\mathrm{r}} H^{\ominus} / T$ corresponds to a positive change of entropy of the surroundings and favours the formation of products. When the temperature is raised, $-\Delta_{\mathrm{r}} H^{\ominus} / T$ decreases and the increasing entropy of the surroundings has a less important role. As a result, the equilibrium lies less to the right. When the reaction is endothermic, the principal factor is the increasing entropy of the reaction system. The importance of the unfavourable change of entropy of the surroundings is reduced if the temperature is raised (because then $\Delta_{\mathrm{r}} H^{\ominus} / T$ is smaller), and the reaction is able to shift towards products.

These remarks have a molecular basis that stems from the Boltzmann distribution of molecules over the available energy levels (Foundations B, and in more detail in Topic 15F). The typical arrangement of energy levels for an endothermic reaction is shown in Fig. 6B.3a. When the temperature is increased, the Boltzmann distribution adjusts and the populations change as shown. The change corresponds to an increased population of the higher energy states at the expense of the population of the lower energy states. We see that the states that arise from the B molecules become more populated at the expense of the A molecules. Therefore, the total population of B states increases, and B becomes more abundant in the equilibrium mixture. Conversely, if the reaction is exothermic (Fig. 6B.3b),

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-13.jpg?height=566&width=883&top_left_y=1745&top_left_x=1166)
Figure 6B. 3 The effect of temperature on a chemical equilibrium can be interpreted in terms of the change in the Boltzmann distribution with temperature and the effect of that change in the population of the species. (a) In an endothermic reaction, the population of $B$ increases at the expense of $A$ as the temperature is raised. (b) In an exothermic reaction, the opposite happens.

then an increase in temperature increases the population of the A states (which start at higher energy) at the expense of the B states, so the reactants become more abundant.

The temperature dependence of the equilibrium constant provides a non-calorimetric method of determining $\Delta_{\mathrm{r}} H^{\ominus}$. A drawback is that the reaction enthalpy is actually temperaturedependent, so the plot is not expected to be perfectly linear. However, the temperature dependence is weak in many cases, so the plot is reasonably straight. In practice, the method is not very accurate, but it is often the only method available.

## Example 6B. 1 Measuring a reaction enthalpy

The data below show the temperature variation of the equilibrium constant of the reaction $\mathrm{Ag}_{2} \mathrm{CO}_{3}(\mathrm{~s}) \rightleftharpoons \mathrm{Ag}_{2} \mathrm{O}(\mathrm{s})+\mathrm{CO}_{2}(\mathrm{~g})$. Calculate the standard reaction enthalpy of the decomposition.

| $T / \mathrm{K}$ | 350 | 400 | 450 | 500 |
| :--- | :---: | :---: | :---: | :---: |
| $K$ | $3.98 \times 10^{-4}$ | $1.41 \times 10^{-2}$ | $1.86 \times 10^{-1}$ | 1.48 |

Method It follows from eqn 6B.2b that, provided the reaction enthalpy can be assumed to be independent of temperature, a plot of $-\ln K$ against $1 / T$ should be a straight line of slope $\Delta_{\mathrm{r}} H^{\ominus} / R$.

Answer We draw up the following table:

| $T / \mathrm{K}$ | 350 | 400 | 450 | 500 |
| :--- | :---: | :---: | :---: | :---: |
| $\left(10^{3} \mathrm{~K}\right) / T$ | 2.86 | 2.50 | 2.22 | 2.00 |
| $-\ln K$ | 6.83 | 4.26 | 1.68 | -0.39 |


![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-14.jpg?height=525&width=828&top_left_y=1731&top_left_x=308)
Figure 6B. 4 When $-\ln K$ is plotted against $1 / T$, a straight line is expected with slope equal to $\Delta_{\mathrm{r}} H^{\ominus} / R$ if the standard reaction enthalpy does not vary appreciably with temperature. This is a non-calorimetric method for the measurement of reaction enthalpies.

These points are plotted in Fig. 6B.4. The slope of the graph is $+9.6 \times 10^{3}$, so

$$
\Delta_{\mathrm{r}} H^{\ominus}=\left(+9.6 \times 10^{3} \mathrm{~K}\right) \times R=+80 \mathrm{~kJ} \mathrm{~mol}^{-1}
$$

Self-test 68.2 The equilibrium constant of the reaction $2 \mathrm{SO}_{2}(\mathrm{~g})+\mathrm{O}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{SO}_{3}(\mathrm{~g})$ is $4.0 \times 10^{24}$ at $300 \mathrm{~K}, 2.5 \times 10^{10}$ at 500 K , and $3.0 \times 10^{4}$ at 700 K . Estimate the reaction enthalpy at 500 K .

Answer: $-200 \mathrm{~kJ} \mathrm{~mol}^{-1}$

## (b) The value of $\boldsymbol{K}$ at different temperatures

To find the value of the equilibrium constant at a temperature $T_{2}$ in terms of its value $K_{1}$ at another temperature $T_{1}$, we integrate eqn 6 B .2 b between these two temperatures:

$$
\ln K_{2}-\ln K_{1}=-\frac{1}{R} \int_{1 / T_{1}}^{1 / T_{2}} \Delta_{\mathrm{r}} H^{\ominus} \mathrm{d}(1 / T)
$$

If we suppose that $\Delta_{\mathrm{r}} H^{\ominus}$ varies only slightly with temperature over the temperature range of interest, then we may take it outside the integral. It follows that

$$
\ln K_{2}-\ln K_{1}=-\frac{\Delta_{\mathrm{r}} H^{\ominus}}{R}\left(\frac{1}{T_{2}}-\frac{1}{T_{1}}\right) \quad \begin{aligned}
& \text { Temperature } \\
& \text { dependence of } K
\end{aligned}
$$

## Brief illustration 6B.2 The temperature dependence of $K$

To estimate the equilibrium constant or the synthesis of ammonia at 500 K from its value at $298 \mathrm{~K}\left(6.1 \times 10^{5}\right.$ for the reaction written as $\left.\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NH}_{3}(\mathrm{~g})\right)$ we use the standard reaction enthalpy, which can be obtained from Table 2C. 2 in the Resource section by using $\Delta_{\mathrm{r}} H^{\ominus}=2 \Delta_{\mathrm{f}} H^{\ominus}\left(\mathrm{NH}_{3}, \mathrm{~g}\right)$ and assume that its value is constant over the range of temperatures. Then, with $\Delta_{\mathrm{r}} H^{\ominus}=-92.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$, from eqn 6 B .3 we find

$$
\begin{aligned}
\ln K_{2} & =\ln \left(6.1 \times 10^{5}\right)-\left(\frac{-9.22 \times 10^{4} \mathrm{~J} \mathrm{~mol}^{-1}}{8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}}\right) \times\left(\frac{1}{500 \mathrm{~K}}-\frac{1}{298 \mathrm{~K}}\right) \\
& =-1.7 \ldots
\end{aligned}
$$

It follows that $K_{2}=0.18$, a lower value than at 298 K , as expected for this exothermic reaction.

Self-test 6B.3 The equilibrium constant for $\mathrm{N}_{2} \mathrm{O}_{4}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NO}_{2}(\mathrm{~g})$ was calculated in Self-test 6A.6. Estimate its value at $100^{\circ} \mathrm{C}$.

Answer: 15

## Checklist of concepts

□ 1. The thermodynamic equilibrium constant is independent of pressure.
□ 2. The response of composition to changes in the conditions is summarized by Le Chatelier's principle.
□ 3. The dependence of the equilibrium constant on the temperature is expressed by the van 't Hoff equation and can be explained in terms of the distribution of molecules over the available states.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| van 't Hoff equation | $\mathrm{d} \ln K / \mathrm{d} T=\Delta_{\mathrm{r}} H^{\ominus} / R T^{2}$ |  | 6B.2a |
|  | $\mathrm{d} \ln K / \mathrm{d}(1 / T)=-\Delta_{\mathrm{r}} H^{\ominus} / R$ | Alternative version | 6B.2b |
| Temperature dependence of equilibrium constant | $\ln K_{2}-\ln K_{1}=-\left(\Delta_{\mathrm{r}} H^{\ominus} / R\right)\left(1 / T_{2}-1 / T_{1}\right)$ | $\Delta_{\mathrm{r}} H^{\ominus}$ assumed constant | 6B. 5 |

## 6C Electrochemical cells

## Contents

6C. 1 Half-reactions and electrodes ..... 259
Brief illustration 6C. 1 Redox couples ..... 260
Brief illustration 6C. 2 The reaction quotient ..... 260
6C. 2 Varieties of cells ..... 260
(a) Liquid junction potentials ..... 261
(b) Notation ..... 261
Brief illustration 6C. 3 Cell notation ..... 261
6C. 3 The cell potential ..... 261
Brief illustration 6C. 4 The cell reaction ..... 262
(a) The Nernst equation ..... 262
Brief illustration 6C. 5 The reaction Gibbs energy ..... 263
Brief illustration 6C. 6 The Nernst equation ..... 264
(b) Cells at equilibrium ..... 264
Brief illustration 6C. 7 Equilibrium constants ..... 264
6C.4 The determination of thermodynamic functions ..... 264
Brief illustration 6C. 8 The reaction Gibbs energy ..... 264
Example 6C. 1 Using the temperature coefficient of the cell potential ..... 265
Checklist of concepts ..... 265
Checklist of equations ..... 266

## Why do you need to know this material?

One very special case of the material treated in Topic 6B that has enormous fundamental, technological, and economic significance concerns reactions that take place in electrochemical cells. Moreover, the ability to make very precise measurements of potential differences ('voltages') means that electrochemical methods can be used to determine thermodynamic properties of reactions that may be inaccessible by other methods.

## What is the key idea?

The electrical work that a reaction can perform at constant pressure and temperature is equal to the reaction Gibbs energy.

## What do you need to know already?

This Topic develops the relation between the Gibbs energy and non-expansion work (Topic 3C). You need to be aware
> of how to calculate the work of moving a charge through an electrical potential difference (Topic 2A). The equations make use of the definition of the reaction quotient $Q$ and the equilibrium constant $K$ (Topic 6 A ).

An electrochemical cell consists of two electrodes, or metallic conductors, in contact with an electrolyte, an ionic conductor (which may be a solution, a liquid, or a solid). An electrode and its electrolyte comprise an electrode compartment. The two electrodes may share the same compartment. The various kinds of electrode are summarized in Table 6C.1. Any 'inert metal' shown as part of the specification is present to act as a source or sink of electrons, but takes no other part in the reaction other than acting as a catalyst for it. If the electrolytes are different, the two compartments may be joined by a salt bridge, which is a tube containing a concentrated electrolyte solution (for instance, potassium chloride in agar jelly) that completes the electrical circuit and enables the cell to function. A galvanic cell is an electrochemical cell that produces electricity as a result of the spontaneous reaction occurring inside it. An electrolytic cell is an electrochemical cell in which a non-spontaneous reaction is driven by an external source of current.

## 6C.1 Half-reactions and electrodes

It will be familiar from introductory chemistry courses that oxidation is the removal of electrons from a species, a reduction is the addition of electrons to a species, and a redox reaction is a

Table 6C. 1 Varieties of electrode
| Electrode type | Designation | Redox couple | Half-reaction |
| :--- | :--- | :--- | :--- |
| Metal/ metal ion | $\mathrm{M}(\mathrm{s}) \mid \mathrm{M}^{+}(\mathrm{aq})$ | $\mathrm{M}^{+} / \mathrm{M}$ | $\mathrm{M}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{M}(\mathrm{s})$ |
| Gas | $\operatorname{Pt}(\mathrm{s})\left\|\mathrm{X}_{2}(\mathrm{~g})\right\| \mathrm{X}^{+}(\mathrm{aq})$ | $\mathrm{X}^{+} / \mathrm{X}_{2}$ | $\mathrm{X}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \frac{1}{2} \mathrm{X}_{2}(\mathrm{~g})$ |
|  | $\operatorname{Pt}(\mathrm{s})\left\|\mathrm{X}_{2}(\mathrm{~g})\right\| \mathrm{X}^{-}(\mathrm{aq})$ | $\mathrm{X}_{2} / \mathrm{X}^{-}$ | $\frac{1}{2} \mathrm{X}_{2}(\mathrm{~g})+\mathrm{e}^{-} \rightarrow \mathrm{X}^{-}(\mathrm{aq})$ |
| Metal/ insoluble salt | $\mathrm{M}(\mathrm{s})\|\mathrm{MX}(\mathrm{s})\| \mathrm{X}^{-}(\mathrm{aq})$ | MX/M, $\mathrm{X}^{-}$ | $\operatorname{MX}(\mathrm{s})+\mathrm{e}^{-} \rightarrow \mathrm{M}(\mathrm{s})+\mathrm{X}^{-}(\mathrm{aq})$ |
| Redox | $\operatorname{Pt}(\mathrm{s}) \mid \mathrm{M}^{+}(\mathrm{aq}), \mathrm{M}^{2+}(\mathrm{aq})$ | $\mathrm{M}^{2+} / \mathrm{M}^{+}$ | $\mathrm{M}^{2+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{M}^{+}(\mathrm{aq})$ |


reaction in which there is a transfer of electrons from one species to another. The electron transfer may be accompanied by other events, such as atom or ion transfer, but the net effect is electron transfer and hence a change in oxidation number of an element. The reducing agent (or reductant) is the electron donor; the oxidizing agent (or oxidant) is the electron acceptor. It should also be familiar that any redox reaction may be expressed as the difference of two reduction half-reactions, which are conceptual reactions showing the gain of electrons. Even reactions that are not redox reactions may often be expressed as the difference of two reduction half-reactions. The reduced and oxidized species in a half-reaction form a redox couple. In general we write couple as $\mathrm{Ox} /$ Red and the corresponding reduction half-reaction as

$$
\mathrm{Ox}+v \mathrm{e}^{-} \rightarrow \mathrm{Red}
$$

## Brief illustration 6C. 1

Redox couples
The dissolution of silver chloride in water $\mathrm{AgCl}(\mathrm{s}) \rightarrow \mathrm{Ag}^{+}(\mathrm{aq})+\mathrm{Cl}^{-}(\mathrm{aq})$, which is not a redox reaction, can be expressed as the difference of the following two reduction half-reactions:

$$
\begin{aligned}
& \mathrm{AgCl}(\mathrm{~s})+\mathrm{e}^{-} \rightarrow \mathrm{Ag}(\mathrm{~s})+\mathrm{Cl}^{-}(\mathrm{aq}) \\
& \mathrm{Ag}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Ag}(\mathrm{~s})
\end{aligned}
$$

The redox couples are $\mathrm{AgCl} / \mathrm{Ag}, \mathrm{Cl}^{-}$and $\mathrm{Ag}^{+} / \mathrm{Ag}$, respectively.
Self-test 6C. 1 Express the formation of $\mathrm{H}_{2} \mathrm{O}$ from $\mathrm{H}_{2}$ and $\mathrm{O}_{2}$ in acidic solution (a redox reaction) as the difference of two reduction half-reactions.

Answer: $4 \mathrm{H}^{+}(\mathrm{aq})+4 \mathrm{e}^{-} \rightarrow 2 \mathrm{H}_{2}(\mathrm{~g}), \mathrm{O}_{2}(\mathrm{~g})+4 \mathrm{H}^{+}(\mathrm{aq})+4 \mathrm{e}^{-} \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$

We shall often find it useful to express the composition of an electrode compartment in terms of the reaction quotient, $Q$, for the half-reaction. This quotient is defined like the reaction quotient for the overall reaction (Topic 6A, $Q=\prod_{\mathrm{J}} a_{\mathrm{J}}^{v_{j}}$ ), but the electrons are ignored because they are stateless.

## Brief illustration 6C. 2 The reaction quotient

The reaction quotient for the reduction of $\mathrm{O}_{2}$ to $\mathrm{H}_{2} \mathrm{O}$ in acid solution, $\mathrm{O}_{2}(\mathrm{~g})+4 \mathrm{H}^{+}(\mathrm{aq})+4 \mathrm{e}^{-} \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$, is

$$
Q=\frac{a_{\mathrm{H}_{2} \mathrm{O}}^{2}}{a_{\mathrm{H}^{+}}^{4} a_{\mathrm{O}_{2}}} \approx \frac{p^{\ominus}}{a_{\mathrm{H}^{+}}^{4} p_{\mathrm{O}_{2}}}
$$

The approximations used in the second step are that the activity of water is 1 (because the solution is dilute) and the oxygen behaves as a perfect gas, so $a_{\mathrm{O}_{2}} \approx p_{\mathrm{O}_{2}} / p^{\ominus}$.

Self-test 6C.2 Write the half-reaction and the reaction quotient for a chlorine gas electrode.

$$
\text { Answer: } \mathrm{Cl}_{2}(\mathrm{~g})+2 \mathrm{e}^{-} \rightarrow 2 \mathrm{Cl}^{-}(\mathrm{aq}), Q \approx a_{\mathrm{Cl}^{-}}^{2} p^{\ominus} / p_{\mathrm{Cl}_{2}}
$$

The reduction and oxidation processes responsible for the overall reaction in a cell are separated in space: oxidation takes place at one electrode and reduction takes place at the other. As the reaction proceeds, the electrons released in the oxidation $\operatorname{Red}_{1} \rightarrow \mathrm{Ox}_{1}+\nu \mathrm{e}^{-}$at one electrode travel through the external circuit and re-enter the cell through the other electrode. There they bring about reduction $\mathrm{Ox}_{2}+v \mathrm{e}^{-} \rightarrow \operatorname{Red}_{2}$. The electrode at which oxidation occurs is called the anode; the electrode at which reduction occurs is called the cathode. In a galvanic cell, the cathode has a higher potential than the anode: the species undergoing reduction, $\mathrm{Ox}_{2}$, withdraws electrons from its electrode (the cathode, Fig. 6C.1), so leaving a relative positive charge on it (corresponding to a high potential). At the anode, oxidation results in the transfer of electrons to the electrode, so giving it a relative negative charge (corresponding to a low potential).

## 6C.2 Varieties of cells

The simplest type of cell has a single electrolyte common to both electrodes (as in Fig. 6C.1). In some cases it is necessary to immerse the electrodes in different electrolytes, as in the 'Daniell cell' in which the redox couple at one electrode is $\mathrm{Cu}^{2+} / \mathrm{Cu}$ and at the other is $\mathrm{Zn}^{2+} / \mathrm{Zn}$ (Fig. 6C.2). In an electrolyte concentration cell, the electrode compartments are identical except for the concentrations of the electrolytes. In an electrode concentration cell the electrodes themselves have different concentrations, either because they are gas electrodes operating at different pressures or because they are amalgams (solutions in mercury) with different concentrations.

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-17.jpg?height=447&width=566&top_left_y=1827&top_left_x=1321)
Figure 6C. 1 When a spontaneous reaction takes place in a galvanic cell, electrons are deposited in one electrode (the site of oxidation, the anode) and collected from another (the site of reduction, the cathode), and so there is a net flow of current which can be used to do work. Note that the + sign of the cathode can be interpreted as indicating the electrode at which electrons enter the cell, and the - sign of the anode is where the electrons leave the cell.

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-18.jpg?height=396&width=695&top_left_y=318&top_left_x=369)
Figure 6C. 2 One version of the Daniell cell. The copper electrode is the cathode and the zinc electrode is the anode. Electrons leave the cell from the zinc electrode and enter it again through the copper electrode.

## (a) Liquid junction potentials

In a cell with two different electrolyte solutions in contact, as in the Daniell cell, there is an additional source of potential difference across the interface of the two electrolytes. This potential is called the liquid junction potential, $E_{\mathrm{lj}}$. Another example of a junction potential is that between different concentrations of hydrochloric acid. At the junction, the mobile $\mathrm{H}^{+}$ions diffuse into the more dilute solution. The bulkier $\mathrm{Cl}^{-}$ions follow, but initially do so more slowly, which results in a potential difference at the junction. The potential then settles down to a value such that, after that brief initial period, the ions diffuse at the same rates. Electrolyte concentration cells always have a liquid junction; electrode concentration cells do not.

The contribution of the liquid junction to the potential can be reduced (to about 1 to 2 mV ) by joining the electrolyte compartments through a salt bridge (Fig. 6C.3). The reason for the success of the salt bridge is that provided the ions dissolved in the jelly have similar mobilities, then the liquid junction potentials at either end are largely independent of the concentrations of the two dilute solutions, and so nearly cancel.

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-18.jpg?height=469&width=652&top_left_y=1997&top_left_x=391)
Figure 6C.3 The salt bridge, essentially an inverted U-tube full of concentrated salt solution in a jelly, has two opposing liquid junction potentials that almost cancel.

## (b) Notation

We use the following notation for cells:
| A phase boundary
: A liquid junction
|| An interface for which it is assumed that the junction potential has been eliminated

## Brief illustration 6C.3 Cell notation

A cell in which two electrodes share the same electrolyte is

$$
\operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}(\mathrm{aq})|\mathrm{AgCl}| \mathrm{Ag}(\mathrm{~s})
$$

The cell in Fig. 6C. 2 is denoted

$$
\mathrm{Zn}(\mathrm{~s})\left|\mathrm{ZnSO}_{4}(\mathrm{aq}): \mathrm{CuSO}_{4}(\mathrm{aq})\right| \mathrm{Cu}(\mathrm{~s})
$$

The cell in Fig. 6C. 3 is denoted

$$
\mathrm{Zn}(\mathrm{~s})\left|\mathrm{ZnSO}_{4}(\mathrm{aq}) \| \mathrm{CuSO}_{4}(\mathrm{aq})\right| \mathrm{Cu}(\mathrm{~s})
$$

An example of an electrolyte concentration cell in which the liquid junction potential is assumed to be eliminated is

$$
\operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}\left(\mathrm{aq}, b_{1}\right)\left|\left|\mathrm{HCl}\left(\mathrm{aq}, b_{2}\right)\right| \mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{Pt}(\mathrm{~s})
$$

Self-test 6C.3 Write the symbolism for a cell in which the halfreactions are $4 \mathrm{H}^{+}(\mathrm{aq})+4 \mathrm{e}^{-} \rightarrow 2 \mathrm{H}_{2}(\mathrm{~g})$ and $\mathrm{O}_{2}(\mathrm{~g})+4 \mathrm{H}^{+}(\mathrm{aq})+ 4 \mathrm{e}^{-} \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$, (a) with a common electrolyte, (b) with separate compartments joined by a salt bridge.

$$
\begin{array}{r}
\text { Answer: (a) } \mathrm{Pt}(\mathrm{~s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}(\mathrm{aq}, b)\left|\mathrm{O}_{2}(\mathrm{~g})\right| \mathrm{Pt}(\mathrm{~s}) ; \\
\text { (b) } \mathrm{Pt}(\mathrm{~s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}\left(\mathrm{aq}, b_{1}\right)\left|\left|\mathrm{HCl}\left(\mathrm{aq}, b_{2}\right)\right| \mathrm{O}_{2}(\mathrm{~g})\right| \mathrm{Pt}(\mathrm{~s})
\end{array}
$$

## 6C.3 The cell potential

The current produced by a galvanic cell arises from the spontaneous chemical reaction taking place inside it. The cell reaction is the reaction in the cell written on the assumption that the right-hand electrode is the cathode, and hence that the spontaneous reaction is one in which reduction is taking place in the right-hand compartment. Later we see how to predict if the right-hand electrode is in fact the cathode; if it is, then the cell reaction is spontaneous as written. If the left-hand electrode turns out to be the cathode, then the reverse of the corresponding cell reaction is spontaneous.

To write the cell reaction corresponding to a cell diagram, we first write the right-hand half-reaction as a reduction (because we have assumed that to be spontaneous). Then we subtract from it the left-hand reduction half-reaction (for, by implication, that electrode is the site of oxidation).

## Brief illustration 6C. 4 The cell reaction

For the cell $\mathrm{Zn}(\mathrm{s})\left|\mathrm{ZnSO}_{4}(\mathrm{aq}) \| \mathrm{CuSO}_{4}(\mathrm{aq})\right| \mathrm{Cu}(\mathrm{s})$ the two electrodes and their reduction half-reactions are

$$
\begin{aligned}
& \text { Right-hand electrode: } \mathrm{Cu}^{2+}(\mathrm{aq})+2 \mathrm{e}^{-} \rightarrow \mathrm{Cu}(\mathrm{~s}) \\
& \text { Left-hand electrode: } \mathrm{Zn}^{2+}(\mathrm{aq})+2 \mathrm{e}^{-} \rightarrow \mathrm{Zn}(\mathrm{~s})
\end{aligned}
$$

Hence, the overall cell reaction is the difference Right - Left:

$$
\mathrm{Cu}^{2+}(\mathrm{aq})+2 \mathrm{e}^{-}-\mathrm{Zn}^{2+}(\mathrm{aq})-2 \mathrm{e}^{-} \rightarrow \mathrm{Cu}(\mathrm{~s})-\mathrm{Zn}(\mathrm{~s})
$$

which, after cancellation of the $2 \mathrm{e}^{-}$, rearranges to

$$
\mathrm{Cu}^{2+}(\mathrm{aq})+\mathrm{Zn}(\mathrm{~s}) \rightarrow \mathrm{Cu}(\mathrm{~s})+\mathrm{Zn}^{2+}(\mathrm{aq})
$$

Self-test 6C.4 Construct the overall cell reaction for the cells:
(a) $\mathrm{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}(\mathrm{aq}, b)\left|\mathrm{O}_{2}(\mathrm{~g})\right| \mathrm{Pt}(\mathrm{s})$;
(b) $\mathrm{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}\left(\mathrm{aq}, b_{\mathrm{L}}\right) \| \mathrm{HCl}\left(\mathrm{aq}, b_{\mathrm{R}}\right)\left|\mathrm{O}_{2}(\mathrm{~g})\right| \mathrm{Pt}(\mathrm{s})$.

Answer: (a) $2 \mathrm{H}_{2}(\mathrm{~g})+\mathrm{O}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$;<br>(b) $2 \mathrm{H}_{2}(\mathrm{~g})+\mathrm{O}_{2}(\mathrm{~g})+4 \mathrm{H}^{+}\left(b_{\mathrm{R}}\right) \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})+4 \mathrm{H}^{+}\left(b_{\mathrm{L}}\right)$

## (a) The Nernst equation

A cell in which the overall cell reaction has not reached chemical equilibrium can do electrical work as the reaction drives electrons through an external circuit. The work that a given transfer of electrons can accomplish depends on the potential difference between the two electrodes. When the potential difference is large, a given number of electrons travelling between the electrodes can do a large amount of electrical work. When the potential difference is small, the same number of electrons can do only a small amount of work. A cell in which the overall reaction is at equilibrium can do no work, and then the potential difference is zero.

According to the discussion in Topic 3C, we know that the maximum non-expansion work a system can do at constant temperature and pressure is given by eqn 3C.16b $\left(w_{\mathrm{e}, \max }=\Delta G\right)$. In electrochemistry, the non-expansion work is identified with electrical work, the system is the cell, and $\Delta G$ is the Gibbs energy of the cell reaction, $\Delta_{\mathrm{r}} G$. Maximum work is produced when a change occurs reversibly. It follows that, to draw thermodynamic conclusions from measurements of the work that a cell can do, we must ensure that the cell is operating reversibly. Moreover, it is established in Topic 6A that the reaction Gibbs energy is actually a property related, through $R T \ln Q$, to a specified composition of the reaction mixture. Therefore, to make use of $\Delta_{\mathrm{r}} G$ we must ensure that the cell is operating reversibly at a specific, constant composition. Both these conditions are achieved by measuring the cell potential when it is balanced by an exactly opposing source of potential so that the cell reaction occurs reversibly, the composition is constant, and no current flows: in effect, the cell reaction is poised for change, but not actually changing. The
resulting potential difference is called the cell potential, $E_{\text {cell }}$, of the cell.

A note on good practice The cell potential was formerly, and is still widely, called the electromotive force (emf) of the cell. IUPAC prefers the term 'cell potential' because a potential difference is not a force.

As we show in the following Justification, the relation between the reaction Gibbs energy and the cell potential is

$$
-v F E_{\text {cell }}=\Delta_{\mathrm{r}} G
$$

The cell potential
where $F$ is Faraday's constant, $F=e N_{\mathrm{A}}$, and $v$ is the stoichiometric coefficient of the electrons in the half-reactions into which the cell reaction can be divided. This equation is the key connection between electrical measurements on the one hand and thermodynamic properties on the other. It will be the basis of all that follows.

## Justification 6C. 1 The relation between the cell potential and the reaction Gibbs energy

We consider the change in $G$ when the cell reaction advances by an infinitesimal amount $\mathrm{d} \xi$ at some composition. From Justification 6A.1, specifically the equation $\Delta_{\mathrm{r}} G=(\partial G / \partial \xi)_{T, p}$, we can write (at constant temperature and pressure)

$$
\mathrm{d} G=\Delta_{\mathrm{r}} G \mathrm{~d} \xi
$$

The maximum non-expansion (electrical) work that the reaction can do as it advances by $\mathrm{d} \xi$ at constant temperature and pressure is therefore

$$
\mathrm{d} w_{\mathrm{e}}=\Delta_{\mathrm{r}} G \mathrm{~d} \xi
$$

This work is infinitesimal, and the composition of the system is virtually constant when it occurs.
Suppose that the reaction advances by $\mathrm{d} \xi$, then $\nu \mathrm{d} \xi$ electrons must travel from the anode to the cathode. The total charge transported between the electrodes when this change occurs is $-\nu e N_{\mathrm{A}} \mathrm{d} \xi$ (because $\nu \mathrm{d} \xi$ is the amount of electrons in moles and the charge per mole of electrons is $\left.-e N_{\mathrm{A}}\right)$. Hence, the total charge transported is $-\nu F \mathrm{~d} \xi$ because $e N_{\mathrm{A}}=F$. The work done when an infinitesimal charge $-\nu F \mathrm{~d} \xi$ travels from the anode to the cathode is equal to the product of the charge and the potential difference $E_{\text {cell }}$ (see Table 2A.1, the entry $\mathrm{d} w=Q \mathrm{~d} \phi):$

$$
\mathrm{d} w_{\mathrm{e}}=-v F E_{\text {cell }} \mathrm{d} \xi
$$

When this relation is equated to the one above ( $\mathrm{d} w_{\mathrm{e}}=\Delta_{\mathrm{r}} G \mathrm{~d} \xi$ ), the advancement $\mathrm{d} \xi$ cancels, and we obtain eqn 6C.2.

It follows from eqn 6C. 2 that, by knowing the reaction Gibbs energy at a specified composition, we can state the cell

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-20.jpg?height=491&width=803&top_left_y=314&top_left_x=318)
Figure 6C.4 A spontaneous reaction occurs in the direction of decreasing Gibbs energy. When expressed in terms of a cell potential, the spontaneous direction of change can be expressed in terms of the cell potential, $E_{\text {cell }}$. The reaction is spontaneous as written (from left to right on the illustration) when $E_{\text {cell }}>0$. The reverse reaction is spontaneous when $E_{\text {cell }}<0$. When the cell reaction is at equilibrium, the cell potential is zero.

potential at that composition. Note that a negative reaction Gibbs energy, corresponding to a spontaneous cell reaction, corresponds to a positive cell potential. Another way of looking at the content of eqn 6C. 2 is that it shows that the driving power of a cell (that is, its potential) is proportional to the slope of the Gibbs energy with respect to the extent of reaction. It is plausible that a reaction that is far from equilibrium (when the slope is steep) has a strong tendency to drive electrons through an external circuit (Fig. 6C.4). When the slope is close to zero (when the cell reaction is close to equilibrium), the cell potential is small.

## Brief illustration 6C.5 The reaction Gibbs energy

Equation 6C. 2 provides an electrical method for measuring a reaction Gibbs energy at any composition of the reaction mixture: we simply measure the cell potential and convert it to $\Delta_{\mathrm{r}} G$. Conversely, if we know the value of $\Delta_{\mathrm{r}} G$ at a particular composition, then we can predict the cell potential. For example, if $\Delta_{\mathrm{r}} G=-1 \times 10^{2} \mathrm{~kJ} \mathrm{~mol}^{-1}$ and $\nu=1$, then

$$
E_{\text {cell }}=-\frac{\Delta_{\mathrm{r}} G}{\nu F}=-\frac{\left(-1 \times 10^{5} \mathrm{~J} \mathrm{~mol}^{-1}\right)}{1 \times\left(9.6485 \times 10^{4} \mathrm{C} \mathrm{~mol}^{-1}\right)}=1 \mathrm{~V}
$$

where we have used $1 \mathrm{~J}=1 \mathrm{CV}$.
Self-test 6C. 5 Estimate the potential of a fuel cell in which the reaction is $\mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{O}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$.

Answer: 1.2 V

We can go on to relate the cell potential to the activities of the participants in the cell reaction. We know that the
reaction Gibbs energy is related to the composition of the reaction mixture by eqn $6 \mathrm{~A} .10\left(\Delta_{\mathrm{r}} G=\Delta_{\mathrm{r}} G^{\ominus}+R T \ln Q\right)$; it follows, on division of both sides by $-\nu F$ and recognizing that $\Delta_{\mathrm{r}} G /(-\nu F)=E_{\text {cell }}$, that

$$
E_{\text {cell }}=-\frac{\Delta_{\mathrm{r}} G^{\ominus}}{\nu F}-\frac{R T}{\nu F} \ln Q
$$

The first term on the right is written

$$
E_{\mathrm{cell}}^{\ominus}=-\frac{\Delta_{\mathrm{r}} G^{\ominus}}{\nu F}
$$

Definition Standard cell potential (6C.3)
and called the standard cell potential. That is, the standard cell potential is the standard reaction Gibbs energy expressed as a potential difference (in volts). It follows that

$$
E_{\text {cell }}=E_{\text {cell }}^{\ominus}-\frac{R T}{\nu F} \ln Q
$$

Nernst equation
(6C.4)

This equation for the cell potential in terms of the composition is called the Nernst equation; the dependence that it predicts is summarized in Fig. 6C.5. One important application of the Nernst equation is to the determination of the pH of a solution and, with a suitable choice of electrodes, of the concentration of other ions (Topic 6D).

We see from eqn 6C. 4 that the standard cell potential can be interpreted as the cell potential when all the reactants and products in the cell reaction are in their standard states, for then all activities are 1 , so $Q=1$ and $\ln Q=0$. However, the fact that the standard cell potential is merely a disguised form of the standard reaction Gibbs energy (eqn 6C.3) should always be kept in mind and underlies all its applications.

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-20.jpg?height=519&width=828&top_left_y=1817&top_left_x=1225)
Figure 6C. 5 The variation of cell potential with the value of the reaction quotient for the cell reaction for different values of $\nu$ (the number of electrons transferred). At 298 K , $R T / F=25.69 \mathrm{mV}$, so the vertical scale refers to multiples of this value.

## Brief illustration 6C. 6 The Nernst equation

Because $R T / F=25.7 \mathrm{mV}$ at $25^{\circ} \mathrm{C}$, a practical form of the Nernst equation is

$$
E_{\text {cell }}=E_{\text {cell }}^{\ominus}-\frac{25.7 \mathrm{mV}}{v} \ln Q
$$

It then follows that, for a reaction in which $\nu=1$, if $Q$ is increased by a factor of 10 , then the cell potential decreases by 59.2 mV .

Self-test 6C. 6 By how much does the cell potential change when $Q$ is decreased by a factor of 10 for a reaction in which $\nu=2$ ?

Answer: -29.6 V

An important feature of a standard cell potential is that it is unchanged if the chemical equation for the cell reaction is multiplied by a numerical factor. A numerical factor increases the value of the standard Gibbs energy for the reaction. However, it also increases the number of electrons transferred by the same factor, and by eqn 6D. 2 the value of $E_{\text {cell }}^{\ominus}$ remains unchanged. A practical consequence is that a cell potential is independent of the physical size of the cell. In other words, the cell potential is an intensive property.

## (b) Cells at equilibrium

A special case of the Nernst equation has great importance in electrochemistry and provides a link to the discussion of equilibrium in Topic 6A. Suppose the reaction has reached equilibrium; then $Q=K$, where $K$ is the equilibrium constant of the cell reaction. However, a chemical reaction at equilibrium cannot do work, and hence it generates zero potential difference between the electrodes of a galvanic cell. Therefore, setting $E_{\text {cell }}=0$ and $Q=K$ in the Nernst equation gives

$$
E_{\text {cell }}^{\ominus}=\frac{R T}{\nu F} \ln K
$$

Equilibrium constant and standard cell potential
(6C.5)

This very important equation (which could also have been obtained more directly by substituting eqn 6A.14, $\Delta_{\mathrm{r}} G^{\ominus}= -R T \ln K$, into eqn 6C.3) lets us predict equilibrium constants from measured standard cell potentials. However, before we use it extensively, we need to establish a further result.

## Brief illustration 6C. 7 Equilibrium constants

Because the standard potential of the Daniell cell is +1.10 V , the equilibrium constant for the cell reaction $\mathrm{Cu}^{2+}(\mathrm{aq})+\mathrm{Zn}(\mathrm{s}) \rightarrow \mathrm{Cu}(\mathrm{s})+\mathrm{Zn}^{2+}(\mathrm{aq})$, for which $\nu=2$, is $K=1.5 \times 10^{37}$ at 298 K . We conclude that the displacement of copper by zinc goes
virtually to completion. Note that a cell potential of about 1 V is easily measurable but corresponds to an equilibrium constant that would be impossible to measure by direct chemical analysis.

Self-test 6C. 7 What would be the standard cell potential for a reaction with $K=1$ ?

Answer: 0

## 6C.4 The determination of thermodynamic functions

The standard potential of a cell is related to the standard reaction Gibbs energy through eqn 6C.3 (written as $-\nu F E_{\text {cell }}^{\ominus}=\Delta_{\mathrm{r}} G^{\ominus}$ ). Therefore, by measuring $E_{\text {cell }}^{\ominus}$ we can obtain this important thermodynamic quantity. Its value can then be used to calculate the Gibbs energy of formation of ions by using the convention explained in Topic 3C, that $\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{H}^{+}, \mathrm{aq}\right)=0$.

## Brief illustration 6C. 8 The reaction Gibbs energy

The reaction taking place in the cell

$$
\operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{H}^{+}(\mathrm{aq})| | \mathrm{Ag}^{+}(\mathrm{aq}) \mid \mathrm{Ag}(\mathrm{~s}) \quad E_{\text {cell }}^{\ominus}=+0.7996 \mathrm{~V}
$$

is

$$
\mathrm{Ag}^{+}(\mathrm{aq})+\frac{1}{2} \mathrm{H}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}^{+}(\mathrm{aq})+\mathrm{Ag}(\mathrm{~s}) \quad \Delta_{\mathrm{r}} \mathrm{G}^{\ominus}=-\Delta_{\mathrm{f}} \mathrm{G}^{\ominus}\left(\mathrm{Ag}^{+}, \mathrm{aq}\right)
$$

Therefore, with $\nu=1$, we find

$$
\begin{aligned}
\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{Ag}^{+}, \mathrm{aq}\right) & =-\left(-F E^{\ominus}\right) \\
& =\left(9.6485 \times 10^{4} \mathrm{Cmol}^{-1}\right) \times(0.7996 \mathrm{~V}) \\
& =+77.15 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

which is in close agreement with the value in Table 2C. 2 of the Resource section.

Self-test 6C. 8 Derive the value of $\Delta_{\mathrm{f}} \mathrm{G}^{\ominus}\left(\mathrm{H}_{2} \mathrm{O}, \mathrm{l}\right)$ at 298 K from the standard potential of the cell $\mathrm{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}(\mathrm{aq})\left|\mathrm{O}_{2}(\mathrm{~g})\right| \mathrm{Pt}$, $E_{\text {cell }}^{\ominus}=+1.23 \mathrm{~V}$.

Answer: $-237 \mathrm{~kJ} \mathrm{~mol}^{-1}$

The temperature coefficient of the standard cell potential, $\mathrm{d} E_{\text {cell }}^{\ominus} / \mathrm{d} T$, gives the standard entropy of the cell reaction. This conclusion follows from the thermodynamic relation $(\partial G / \partial T)_{p}=-S$ derived in Topic 3D and eqn 6C.3, which combine to give

$$
\frac{\mathrm{d} E_{\text {cell }}^{\ominus}}{\mathrm{d} T}=\frac{\Delta_{\mathrm{r}} S^{\ominus}}{v F}
$$

Temperature coefficient of standard cell potential
(6C.6)

The derivative is complete (not partial) because $E_{\text {cell }}^{\ominus}$ like $\Delta_{\mathrm{r}} G^{\ominus}$, is independent of the pressure. Hence we have an electrochemical technique for obtaining standard reaction entropies and through them the entropies of ions in solution.

Finally, we can combine the results obtained so far and use them to obtain the standard reaction enthalpy:

$$
\Delta_{\mathrm{r}} H^{\ominus}=\Delta_{\mathrm{r}} G^{\ominus}+T \Delta_{\mathrm{r}} S^{\ominus}=-v F\left(E_{\text {cell }}^{\ominus}-T \frac{\mathrm{~d} E_{\text {cell }}^{\ominus}}{\mathrm{d} T}\right)
$$

This expression provides a non-calorimetric method for measuring $\Delta_{\mathrm{r}} H^{\ominus}$ and, through the convention $\Delta_{\mathrm{f}} H^{\ominus}\left(\mathrm{H}^{+}\right.$, $\mathrm{aq})=0$ the standard enthalpies of formation of ions in solution (Topic 2C).

Example 6C. 1 Using the temperature coefficient of the cell potential

The standard potential of the cell $\mathrm{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HBr}(\mathrm{aq})|\mathrm{AgBr}(\mathrm{s})| \mathrm{Ag}(\mathrm{s})$ was measured over a range of temperatures, and the data were found to fit the following polynomial:
$E_{\text {cell }}^{\ominus} / \mathrm{V}=0.07131-4.99 \times 10^{-4}(T / \mathrm{K}-298)-3.45 \times 10^{-6}(T / \mathrm{K}-298)^{2}$
The cell reaction is $\mathrm{AgBr}(\mathrm{s})+\frac{1}{2} \mathrm{H}_{2}(\mathrm{~g}) \rightarrow \mathrm{Ag}(\mathrm{s})+\mathrm{HBr}(\mathrm{aq})$. Evaluate the standard reaction Gibbs energy, enthalpy, and entropy at 298 K .

Method The standard Gibbs energy of reaction is obtained by using eqn 6C. 2 after evaluating $E_{\text {cell }}^{\ominus}$ at 298 K and by using $1 \mathrm{VC}=1 \mathrm{~J}$. The standard entropy of reaction is obtained by using eqn 6C.6, which involves differentiating the polynomial with respect to $T$ and then setting $T=298 \mathrm{~K}$. The reaction enthalpy is obtained by combining the values of the standard Gibbs energy and entropy.

## Checklist of concepts

□ 1. A redox reaction is expressed as the difference of two reduction half-reactions; each one defines a redox couple.
□ 2. Galvanic cells are classified as electrolyte concentration and electrode concentration cells.
□ 3. A liquid junction potential arises at the junction of two electrolyte solutions.
□ 4. The cell notation specifies the structure of a cell.

Answer At $T=298 \mathrm{~K}, E_{\text {cell }}^{\ominus} / \mathrm{V}=0.07131 \mathrm{~V}$, so

$$
\begin{aligned}
\Delta_{\mathrm{r}} G^{\ominus} & =-v F E_{\text {cell }}^{\ominus}=-(1) \times\left(9.6485 \times 10^{4} \mathrm{C} \mathrm{~mol}^{-1}\right) \times(0.07131 \mathrm{~V}) \\
& =-6.880 \times 10^{3} \mathrm{CV} \mathrm{~mol}^{-1}=-6.880 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

The temperature coefficient of the cell potential is

$$
\frac{\mathrm{d} E_{\text {cell }}^{\ominus}}{\mathrm{d} T}=-4.99 \times 10^{-4} \mathrm{~V} \mathrm{~K}^{-1}-2\left(3.45 \times 10^{-6}\right)(T / \mathrm{K}-298) \mathrm{V} \mathrm{~K}^{-1}
$$

At $T=298 \mathrm{~K}$ this expression evaluates to

$$
\frac{\mathrm{d} E_{\text {cell }}^{\ominus}}{\mathrm{d} T}=-4.99 \times 10^{-4} \mathrm{VK}^{-1}
$$

So, from eqn 6C. 6 the reaction entropy is

$$
\begin{aligned}
\Delta_{\mathrm{r}} S^{\ominus} & =v F \frac{\mathrm{~d} E_{\text {cell }}^{\ominus}}{\mathrm{d} T}=(1) \times\left(9.6485 \times 10^{4} \mathrm{C} \mathrm{~mol}^{-1}\right) \times\left(-4.99 \times 10^{-4} \mathrm{~V}\right) \\
& =-48.2 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
\end{aligned}
$$

The negative value stems in part from the elimination of gas in the cell reaction. It then follows that

$$
\begin{aligned}
\Delta_{\mathrm{r}} H^{\ominus}= & \Delta_{\mathrm{r}} G^{\ominus}+T \Delta_{\mathrm{r}} S^{\ominus}=-6.880 \mathrm{~kJ} \mathrm{~mol}^{-1} \\
& +(298 \mathrm{~K}) \times\left(-0.0482 \mathrm{~kJ} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}\right) \\
= & -21.2 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

One difficulty with this procedure lies in the accurate measurement of small temperature coefficients of cell potential. Nevertheless, it is another example of the striking ability of thermodynamics to relate the apparently unrelated, in this case to relate electrical measurements to thermal properties.

Self-test 6C.9 Predict the standard potential of the Harned cell at 303 K from tables of thermodynamic data.

Answer: +0.2222 V
□ 5. The Nernst equation relates the cell potential to the composition of the reaction mixture.
□ 6. The standard cell potential may be used to calculate the equilibrium constant of the cell reaction.
□ 7. The temperature coefficient of the cell potential is used to measure thermodynamic properties of electroactive species.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Cell potential and reaction Gibbs energy | $-\nu F E_{\text {cell }}=\Delta_{\mathrm{r}} G$ | Constant temperature and pressure | 6C.2 |
| Standard cell potential | $E_{\text {cell }}^{\ominus}=-\Delta_{\mathrm{r}} G^{\ominus} / \nu F$ | Definition | 6C. 3 |
| Nernst equation | $E_{\text {cell }}=E_{\text {cell }}^{\ominus}-(R T / \nu F) \ln Q$ |  | 6C. 4 |
| Equilibrium constant of cell reaction | $E_{\text {cell }}^{\ominus}=(R T / \nu F) \ln K$ |  | 6C. 5 |
| Temperature coefficient of cell potential | $\mathrm{d} E_{\text {cell }}^{\ominus} / \mathrm{d} T=\Delta_{\mathrm{r}} S^{\ominus} / v F$ |  | 6C. 6 |

## 6D Electrode potentials

## Contents

6D. 1 Standard potentials ..... 267
Brief illustration 6D. 1 Standard electrode potentials ..... 268
(a) The measurement procedure ..... 268
Example 6D.1: Evaluating a standard electrode potential ..... 268
(b) Combining measured values ..... 269
Example 6D.2: Evaluating a standard potential from two others ..... 269
6D. 2 Applications of standard potentials ..... 269
(a) The electrochemical series ..... 269
Brief illustration 6D.2: The electrochemical series ..... 270
(b) The determination of activity coefficients ..... 270
Brief illustration 6D.3: Activity coefficients ..... 270
(c) The determination of equilibrium constants ..... 270
Brief illustration 6D.4: Equilibrium constants ..... 270
Checklist of concepts ..... 271
Checklist of equations ..... 271

## Why do you need to know this material?

A very powerful, compact, and widely used way to report standard cell potentials is to ascribe a potential to each electrode. Electrode potentials are widely used in chemistry to assess the oxidizing and reducing power of redox couples and to infer thermodynamic properties, including equilibrium constants.

## What is the key idea?

Each electrode of a cell can be supposed to make a characteristic contribution to the cell potential; redox couples with low electrode potentials tend to reduce those with higher potentials.

## What do you need to know already?

This Topic develops the concepts in Topic 6D, so you need to understand the concept of cell potential and standard cell potential (Topic 6D); it makes use of the Nernst equation (Topic 6D). The measurement of standard potentials makes use of the Debye-Hückel limiting law (Topic 5F).

As explained in Topic 6C, a galvanic cell is a combination of two electrodes each of which can be considered to make a characteristic contribution to the overall cell potential.

Although it is not possible to measure the contribution of a single electrode, we can define the potential of one of the electrodes as zero and then assign values to others on that basis.

## 6D. 1 Standard potentials

The specially selected electrode is the standard hydrogen electrode (SHE):

$$
\operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{H}^{+}(\mathrm{aq}) \quad E^{\ominus}=0 \quad \text { Convention } \quad \begin{aligned}
& \text { Standard } \\
& \text { potentials }
\end{aligned}
$$

at all temperatures. To achieve the standard conditions, the activity of the hydrogen ions must be 1 (that is, $\mathrm{pH}=0$ ) and the pressure (more precisely, the fugacity) of the hydrogen gas must be 1 bar. The standard potential, $E^{\ominus}(\mathrm{X})$, of another couple X is then assigned by constructing a cell in which it is the right-hand electrode and the standard hydrogen electrode is the left-hand electrode:

$$
\operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{H}^{+}(\mathrm{aq}) \| \mathrm{X} \quad E^{\ominus}(\mathrm{X})=E_{\text {cell }}^{\ominus}
$$

Convention Standard potentials

The standard potential of a cell of the form $\mathrm{L} \| \mathrm{R}$, where L is the left-hand electrode of the cell as written (not as arranged on the bench) and R is the right-hand electrode, is then given by the difference of the two standard potentials:

$$
\mathrm{L} \| \mathrm{R} \quad E_{\text {cell }}^{\ominus}=E^{\ominus}(\mathrm{R})-E^{\ominus}(\mathrm{L}) \quad \text { Standard cell potential }
$$

A list of standard potentials at 298 K is given in Table 6D.1, and longer lists in numerical and alphabetical order are in the Resource section.

Table 6D.1* Standard potentials at $298 \mathrm{~K}, E^{\ominus} / \mathrm{V}$
| Couple | $E^{\ominus} / \mathrm{V}$ |
| :--- | :--- |
| $\mathrm{Ce}^{4+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Ce}^{3+}(\mathrm{aq})$ | +1.61 |
| $\mathrm{Cu}^{2+}(\mathrm{aq})+2 \mathrm{e}^{-} \rightarrow \mathrm{Cu}(\mathrm{s})$ | +0.34 |
| $\mathrm{H}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \frac{1}{2} \mathrm{H}_{2}(\mathrm{~g})$ | 0 |
| $\mathrm{AgCl}(\mathrm{s})+\mathrm{e}^{-} \rightarrow \mathrm{Ag}(\mathrm{s})+\mathrm{Cl}^{-}(\mathrm{aq})$ | +0.22 |
| $\mathrm{Zn}^{2+}(\mathrm{aq})+2 \mathrm{e}^{-} \rightarrow \mathrm{Zn}(\mathrm{s})$ | -0.76 |
| $\mathrm{Na}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Na}(\mathrm{s})$ | -2.71 |


[^0]
## Brief illustration 6D. 1 Standard electrode potentials

The cell $\mathrm{Ag}(\mathrm{s})|\mathrm{AgCl}(\mathrm{s})| \mathrm{HCl}(\mathrm{aq})\left|\mathrm{O}_{2}(\mathrm{~g})\right| \mathrm{Pt}(\mathrm{s})$ can be regarded as formed from the following two electrodes, with their standard potentials taken from the Resource section:

| Electrode | Half-reaction | Standard <br> potential |
| :--- | :--- | :--- |
| $\mathrm{R}: \mathrm{Pt}(\mathrm{s})\left\|\mathrm{O}_{2}(\mathrm{~g})\right\| \mathrm{H}^{+}(\mathrm{aq})$ | $\mathrm{O}_{2}(\mathrm{~g})+4 \mathrm{H}^{+}(\mathrm{aq})+4 \mathrm{e}^{-} \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ | +1.23 V |
| $\mathrm{~L}: \mathrm{Ag}(\mathrm{s})\|\mathrm{AgCl}(\mathrm{s})\| \mathrm{Cl}^{-}(\mathrm{aq})$ | $\mathrm{AgCl}(\mathrm{s})+\mathrm{e}^{-} \rightarrow \mathrm{Ag}(\mathrm{s})+\mathrm{Cl}^{-}(\mathrm{aq})$ | +0.22 V |
|  |  | $E_{\text {cell }}^{\ominus}=$ |

Self-test 6D. 1 What is the standard potential of the cell $\mathrm{Pt}(\mathrm{s}) \mid \mathrm{Fe}^{2+}(\mathrm{aq}), \mathrm{Fe}^{3+}(\mathrm{aq}) \| \mathrm{Ce}^{4+}(\mathrm{aq}), \mathrm{Ce}^{3+}(\mathrm{aq}) \mid \mathrm{Pt}(\mathrm{s}) ?$

Answer: +0.84 V

## (a) The measurement procedure

The procedure for measuring a standard potential can be illustrated by considering a specific case, the silver chloride electrode. The measurement is made on the 'Harned cell':

$$
\begin{aligned}
& \operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HCl}(\mathrm{aq}, b)|\mathrm{AgCl}(\mathrm{~s})| \mathrm{Ag}(\mathrm{~s}) \\
& \quad \frac{1}{2} \mathrm{H}_{2}(\mathrm{~g})+\mathrm{AgCl}(\mathrm{~s}) \rightarrow \mathrm{HCl}(\mathrm{aq})+\mathrm{Ag}(\mathrm{~s}) \\
& E_{\text {cell }}^{\ominus}=E^{\ominus}\left(\mathrm{AgCl} / \mathrm{Ag}, \mathrm{Cl}^{-}\right)-E^{\ominus}(\mathrm{SHE})=E^{\ominus}\left(\mathrm{AgCl} / \mathrm{Ag}, \mathrm{Cl}^{-}\right), v=1
\end{aligned}
$$

for which the Nernst equation is

$$
E_{\text {cell }}=E^{\ominus}\left(\mathrm{AgCl} / \mathrm{Ag}, \mathrm{Cl}^{-}\right)-\frac{R T}{F} \ln \frac{a_{\mathrm{H}^{+}} a_{\mathrm{Cl}^{-}}}{a_{\mathrm{H}_{2}}^{1 / 2}}
$$

We shall set $a_{\mathrm{H}_{2}}=1$ from now on, and for simplicity write the standard potential of the $\mathrm{AgCl} / \mathrm{Ag}, \mathrm{Cl}^{-}$electrode as $E^{\ominus}$; then

$$
E_{\mathrm{cell}}=E^{\ominus}-\frac{R T}{F} \ln a_{\mathrm{H}^{+}} a_{\mathrm{Cl}^{-}}
$$

We show in the following Justification that as the molality $b \rightarrow 0$,

$$
\overbrace{E_{\text {cell }}+\frac{2 R T}{F} \ln b}^{y}=\overbrace{E^{\ominus}}^{\text {intercept }}+\overbrace{C \times b^{1 / 2}}^{\text {slope × } x}
$$

where $C$ is a constant. To use this equation, which has the form $y=$ intercept + slope $\times x$ with $x=b^{1 / 2}$, the expression on the left is evaluated at a range of molalities, plotted against $b^{1 / 2}$, and extrapolated to $b=0$. The intercept at $b^{1 / 2}=0$ is the value of $E^{\ominus}$ for the silver/silver chloride electrode. In precise work, the $b^{1 / 2}$ term is brought to the left, and a higher-order correction term from extended versions of the Debye-Hückel law is used on the right.

## Justification 6D. 1 The Harned cell potential

The activities in the expression for $E_{\text {cell }}$ can be expressed in terms of the molality $b$ of $\mathrm{HCl}(\mathrm{aq})$ through $a_{\mathrm{H}^{+}}=\gamma_{ \pm} b / b^{\ominus}$ and $a_{\mathrm{Cl}^{-}}=\gamma_{ \pm} b / b^{\ominus}$ as established in Topic 5E, so, with $b / b^{\ominus}$ replaced by $b$

$$
\begin{aligned}
E_{\mathrm{cell}} & =E^{\ominus}-\frac{R T}{F} \ln b^{2}-\frac{R T}{F} \ln \gamma_{ \pm}^{2} \\
& =E^{\ominus}-\frac{2 R T}{F} \ln b-\frac{2 R T}{F} \ln \gamma_{ \pm}
\end{aligned}
$$

and therefore

$$
E_{\text {cell }}+\frac{2 R T}{F} \ln b=E^{\ominus}-\frac{2 R T}{F} \ln \gamma_{ \pm}
$$

From the Debye-Hückel limiting law for a 1,1-electrolyte (eqn 5F.8, $\log \gamma_{ \pm}=-A\left|z_{+} z_{-}\right| I^{1 / 2}$ ), as $b \rightarrow 0$

$$
\log \gamma_{ \pm}=-A\left|z_{+} z_{-}\right| I^{1 / 2}=-A\left(b / b^{\ominus}\right)^{1 / 2}
$$

Therefore, because $\ln x=\ln 10 \log x$,

$$
\ln \gamma_{ \pm}=\ln 10 \log \gamma_{ \pm}=-A \ln 10\left(b / b^{\ominus}\right)^{1 / 2}
$$

and the equation for $E_{\text {cell }}$ becomes

$$
E_{\text {cell }}+\frac{2 R T}{F} \ln b=E^{\ominus}+\frac{2 A R T \ln 10}{F\left(b^{\ominus}\right)^{1 / 2}} b^{1 / 2} \quad \text { as } b \rightarrow 0
$$

With the term in blue denoted C, this equation becomes eqn 6D.4.

## Example 6D. 1 Evaluating a standard electrode potential

The potential of the Harned cell at $25^{\circ} \mathrm{C}$ has the following values:

| $b /\left(10^{-3} b^{\ominus}\right)$ | 3.215 | 5.619 | 9.138 | 25.63 |
| :--- | :--- | :--- | :--- | :--- |
| $E_{\text {cell }} / V$ | 0.52053 | 0.49257 | 0.46860 | 0.41824 |

Determine the standard potential of the silver-silver chloride electrode.

Method As explained in the text, evaluate $y=E_{\text {cell }}+(2 R T / F) \ln b$ and plot it against $b^{1 / 2}$; then extrapolate to $b=0$. Use $2 R T / F=0.05139 \mathrm{~V}$.

Answer To determine the standard potential of the cell we draw up the following table:

| $b /\left(10^{-3} b^{\ominus}\right)$ | 3.215 | 5.619 | 9.138 | 25.63 |
| :--- | :--- | :--- | :--- | :--- |
| $\left\{b /\left(10^{-3} b^{\ominus}\right)\right\}^{1 / 2}$ | 1.793 | 2.370 | 3.023 | 5.063 |
| $E_{\text {cell }} / \mathrm{V}$ | 0.52053 | 0.49257 | 0.46860 | 0.41824 |
| $y / \mathrm{V}$ | 0.2256 | 0.2263 | 0.2273 | 0.2299 |

The data are plotted in Fig. 6D.1; as can be seen, they extrapolate to $E^{\ominus}=+0.2232 \mathrm{~V}$ (the value obtained, to preserve the precision of the data, by linear regression).

![](https://cdn.mathpix.com/cropped/59724c3b-b147-4046-9645-5287ccaff395-26.jpg?height=502&width=811&top_left_y=337&top_left_x=316)
Figure 6D. 1 The plot and the extrapolation used for the experimental measurement of a standard cell potential. The intercept at $b^{1 / 2}=0$ is $E_{\text {cell }}^{\ominus}$.

Self-test 6D.2 The data below are for the cell $\operatorname{Pt}(\mathrm{s})\left|\mathrm{H}_{2}(\mathrm{~g})\right| \mathrm{HBr}(\mathrm{aq}, b)|\mathrm{AgBr}(\mathrm{s})| \mathrm{Ag}(\mathrm{s})$ at $25^{\circ} \mathrm{C}$. Determine the standard cell potential.

| $b /\left(10^{-4} b^{\ominus}\right)$ | 4.042 | 8.444 | 37.19 |
| :--- | :--- | :--- | :--- |
| $E_{\text {cell }} / \mathrm{V}$ | 0.47381 | 0.43636 | 0.36173 |

## (b) Combining measured values

The standard potentials in Table 6D. 1 may be combined to give values for couples that are not listed there. However, to do so, we must take into account the fact that different couples may correspond to the transfer of different numbers of electrons. The procedure is illustrated in the following Example.

## Example 6D. 2 Evaluating a standard potential from two others

Given that the standard potentials of the $\mathrm{Cu}^{2+} / \mathrm{Cu}$ and $\mathrm{Cu}^{+} / \mathrm{Cu}$ couples are +0.340 V and +0.522 V , respectively, evaluate $E^{\ominus}\left(\mathrm{Cu}^{2+}\right.$, $\left.\mathrm{Cu}^{+}\right)$.

Method First, we note that reaction Gibbs energies may be added (as in a Hess's law analysis of reaction enthalpies). Therefore, we should convert the $E^{\ominus}$ values to $\Delta_{\mathrm{r}} G^{\ominus}$ values by using eqn 6C. 2 $\left(-v F E^{\ominus}=\Delta_{\mathrm{r}} G^{\ominus}\right)$, add them appropriately, and then convert the overall $\Delta_{\mathrm{r}} G^{\ominus}$ to the required $E^{\ominus}$ by using eqn 6D. 2 again. This roundabout procedure is necessary because, as we shall see, although the factor $F$ cancels, the factor $v$ in general does not.

Answer The electrode half-reactions are as follows:
(a) $\mathrm{Cu}^{2+}(\mathrm{aq})+2 \mathrm{e}^{-} \rightarrow \mathrm{Cu}(\mathrm{s}) \quad E^{\ominus}(\mathrm{a})=+0.340 \mathrm{~V}$, so $\Delta_{\mathrm{r}} G^{\ominus}(\mathrm{a})=-2(0.340 \mathrm{~V}) F$
(b) $\mathrm{Cu}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Cu}(\mathrm{s}) \quad E^{\ominus}(\mathrm{b})=+0.522 \mathrm{~V}$, so $\Delta_{\mathrm{r}} G^{\ominus}(\mathrm{b})=-(0.522 \mathrm{~V}) F$

The required reaction is

$$
\text { (c) } \mathrm{Cu}^{2+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Cu}^{+}(\mathrm{aq}) \quad E^{\ominus}(\mathrm{c})=-\Delta_{\mathrm{r}} G^{\ominus}(\mathrm{c}) / F
$$

Because (c) = (a) - (b), the standard Gibbs energy of reaction (c) is

$$
\begin{aligned}
-\Delta_{\mathrm{r}} G^{\ominus}(\mathrm{c}) & =\Delta_{\mathrm{r}} G^{\ominus}(\mathrm{a})-\Delta_{\mathrm{r}} G^{\ominus}(\mathrm{b})=-(0.680 \mathrm{~V}) F-(-0.522 \mathrm{~V}) F \\
& =(+0.158 \mathrm{~V}) F
\end{aligned}
$$

Therefore, $E^{\ominus}(\mathrm{c})=+0.158 \mathrm{~V}$.
Self-test 6D. 3 Evaluate $E^{\ominus}\left(\mathrm{Fe}^{3+}, \mathrm{Fe}^{2+}\right)$ from $E^{\ominus}\left(\mathrm{Fe}^{3+}, \mathrm{Fe}\right)$ and $E^{\ominus}\left(\mathrm{Fe}^{2+}, \mathrm{Fe}\right)$.

Answer: +0.76 V

The generalization of the calculation in Example 6D. 2 is

$$
\nu_{\mathrm{c}} E^{\ominus}(\mathrm{c})=\nu_{\mathrm{a}} E^{\ominus}(\mathrm{a})-\nu_{\mathrm{b}} E^{\ominus}(\mathrm{b})
$$

with the $v_{\mathrm{r}}$ the stoichiometric coefficients of the electrons in each half-reaction

## 6D. 2 Applications of standard potentials

Cell potentials are a convenient source of data on equilibrium constants and the Gibbs energies, enthalpies, and entropies of reactions. In practice the standard values of these quantities are the ones normally determined.

## (a) The electrochemical series

We have seen that for two redox couples, $\mathrm{Ox}_{\mathrm{L}} / \operatorname{Red}_{\mathrm{L}}$ and $\mathrm{Ox}_{\mathrm{R}} / \operatorname{Red}_{\mathrm{R}}$, and the cell
$L\left\|R=O x_{L} / \operatorname{Red}\right\| O x_{R} / \operatorname{Red}_{R}$
$\mathrm{Ox}_{\mathrm{R}}+v \mathrm{e}^{-} \rightarrow \operatorname{Red}_{\mathrm{R}} \quad \mathrm{Ox}_{\mathrm{L}}+v \mathrm{e}^{-} \rightarrow \operatorname{Red}_{\mathrm{L}} \quad$ Cell convention
6D.6a) $E_{\text {cell }}^{\ominus}=E^{\ominus}(\mathrm{R})-E^{\ominus}(\mathrm{L})$
that the cell reaction

$$
\mathrm{R}-\mathrm{L}: \operatorname{Red}_{\mathrm{L}}+\mathrm{Ox}_{\mathrm{R}} \rightarrow \mathrm{Ox}_{\mathrm{L}}+\operatorname{Red}_{\mathrm{R}}
$$

has $K>1$ as written if $E_{\text {cell }}^{\ominus}>0$, and therefore if $E^{\ominus}(\mathrm{L})<E^{\ominus}(\mathrm{R})$. Because in the cell reaction $\operatorname{Red}_{L}$ reduces $\mathrm{Ox}_{R}$, we can conclude that:
$\operatorname{Red}_{\mathrm{L}}$ has a thermodynamic tendency (in the sense $K>1$ ) to reduce $\mathrm{Ox}_{\mathrm{R}}$ if $E^{\ominus}(\mathrm{L})<E^{\ominus}(\mathrm{R})$

More briefly: low reduces high.

Table 6D.2* The electrochemical series of the metals

Least strongly reducing
Gold
Platinum
Silver
Mercury
Copper
(Hydrogen)
Lead
Tin
Nickel
Iron
Zinc
Chromium
Aluminium
Magnesium
Sodium
Calcium
Potassium
Most strongly reducing
*The complete series can be inferred from Table 6D. 1 in the Resource section.

Table 6D. 2 shows a part of the electrochemical series, the metallic elements (and hydrogen) arranged in the order of their reducing power as measured by their standard potentials in aqueous solution. A metal low in the series (with a lower standard potential) can reduce the ions of metals with higher standard potentials. This conclusion is qualitative. The quantitative value of $K$ is obtained by doing the calculations we have described previously and review below.

## Brief illustration 6D.2 The electrochemical series

Zinc lies above magnesium in the electrochemical series, so zinc cannot reduce magnesium ions in aqueous solution. Zinc can reduce hydrogen ions, because hydrogen lies higher in the series. However, even for reactions that are thermodynamically favourable, there may be kinetic factors that result in very slow rates of reaction.

Self-test 6D. 4 Can nickel reduce hydrogen ions to hydrogen gas?

Answer: Yes

## (b) The determination of activity coefficients

Once the standard potential of an electrode in a cell is known, we can use it to determine mean activity coefficients by measuring the cell potential with the ions at the concentration of interest. For example, the mean activity coefficient of the ions in hydrochloric acid of molality $b$ is obtained from the relation

$$
E_{\text {cell }}+\frac{2 R T}{F} \ln b=E^{\ominus}-\frac{2 R T}{F} \ln \gamma_{ \pm}
$$

in Justification 6D. 1 in the form

$$
\ln \gamma_{ \pm}=\frac{E_{\text {cell }}^{\ominus}-E_{\text {cell }}}{2 R T / F}-\ln b
$$

## Brief illustration 6D. 3 Activity coefficients

The data in Example 6D. 1 include the fact that $E_{\text {cell }}=0.46860 \mathrm{~V}$ when $b=9.138 \times 10^{-3} b^{\ominus}$. Because $2 R T / F=0.05139 \mathrm{~V}$, and in the Example it is established that $E_{\text {cell }}^{\ominus}=0.2232 \mathrm{~V}$, the mean activity coefficient at this molality is

$$
\ln \gamma_{ \pm}=\frac{0.2232 \mathrm{~V}-0.46860 \mathrm{~V}}{0.05139 \mathrm{~V}}-\ln \left(9.138 \times 10^{-3}\right)=-0.0788 \ldots
$$

Therefore, $\gamma_{ \pm}=0.9242$.
Self-test 6D.5 Evaluate the mean activity coefficient when $b=5.619 \times 10^{-3} b^{\ominus}$.

Answer: 0.9417

## (c) The determination of equilibrium constants

The principal use for standard potentials is to calculate the standard potential of a cell formed from any two electrodes. To do so, we construct $E_{\text {cell }}^{\ominus}=E^{\ominus}(\mathrm{R})-E^{\ominus}(\mathrm{L})$ and use eqn 6C. 5 of Topic 6C $\left(E_{\text {cell }}^{\ominus}=(R T / v F) \ln K\right.$, arranged into $\left.\ln K=v F E_{\text {cell }}^{\ominus} / R T\right)$.

## Brief illustration 6D. 4 Equilibrium constants

A disproportionation reaction is a reaction in which a species is both oxidized and reduced. To study the disproportionation $2 \mathrm{Cu}^{+}(\mathrm{aq}) \rightarrow \mathrm{Cu}(\mathrm{s})+\mathrm{Cu}^{2+}(\mathrm{aq})$ at 298 K we combine the following electrodes:
$\mathrm{R}: \mathrm{Cu}(\mathrm{s}) \mid \mathrm{Cu}^{+}(\mathrm{aq})$
$\mathrm{Cu}^{+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Cu}(\mathrm{s})$
$E^{\ominus}(\mathrm{R})=+0.52 \mathrm{~V}$
L: $\operatorname{Pt}(\mathrm{s}) \mid \mathrm{Cu}^{2+}(\mathrm{aq}), \mathrm{Cu}^{+}(\mathrm{aq})$
$\mathrm{Cu}^{2+}(\mathrm{aq})+\mathrm{e}^{-} \rightarrow \mathrm{Cu}^{+}(\mathrm{s})$
$E^{\ominus}(\mathrm{R})=+0.16 \mathrm{~V}$

The standard potential of the cell is therefore

$$
E_{\text {cell }}^{\ominus}=0.52 \mathrm{~V}-0.16 \mathrm{~V}=+0.36 \mathrm{~V}
$$

We can now calculate the equilibrium constant of the cell reaction. Because $\nu=1$, from eqn 6C. 5 with $R T / F=0.025693 \mathrm{~V}$,

$$
\ln K=\frac{0.36 \mathrm{~V}}{0.025693 \mathrm{~V}}=14.0 \ldots
$$

Hence, $K=1.2 \times 10^{6}$.
Self-test 6D. 6 Evaluate the equilibrium constant for the reaction $\mathrm{Sn}(\mathrm{s})+\mathrm{Sn}^{4+}(\mathrm{aq}) \rightleftharpoons 2 \mathrm{Sn}^{2+}(\mathrm{aq})$.

Answer: $6.5 \times 10^{9}$

## Checklist of concepts

□ 1. The standard potential of a couple is the cell potential in which it forms the right-hand electrode and the lefthand electrode is a standard hydrogen electrode.
□ 2. The electrochemical series lists the metallic elements in the order of their reducing power as measured by their standard potentials in aqueous solution: low reduces high.
□ 3. The cell potential is used to measure the activity coefficient of electroactive ions.
□ 4. The standard cell potential is used to infer the equilibrium constant of the cell reaction.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Standard cell potential | $E_{\text {cell }}^{\ominus}=E^{\ominus}(\mathrm{R})-E^{\ominus}(\mathrm{L})$ | Cell: L $\\| \mathrm{R}$ | 6D. 3 |
| Combined potentials | $\nu_{\mathrm{c}} E^{\ominus}(\mathrm{c})=\nu_{\mathrm{a}} E^{\ominus}(\mathrm{a})-\nu_{\mathrm{b}} E^{\ominus}(\mathrm{b})$ |  | 6D. 5 |

## CHAPTER 6 Chemical equilibrium

## TOPIC 6A The equilibrium constant

## Discussion questions

6A. 1 Explain how the mixing of reactants and products affects the position of chemical equilibrium.

## Exercises

6A.1(a) Consider the reaction $\mathrm{A} \rightarrow 2 \mathrm{~B}$. Initially, 1.50 mol A is present and no B. What are the amounts of $A$ and $B$ when the extent of reaction is 0.60 mol ? 6A.1(b) Consider the reaction $2 \mathrm{~A} \rightarrow \mathrm{~B}$. Initially, 1.75 mol A and 0.12 mol B are present. What are the amounts of $A$ and $B$ when the extent of reaction is 0.30 mol ?

6A.2(a) When the reaction $\mathrm{A} \rightarrow 2 \mathrm{~B}$ advances by 0.10 mol (that is, $\Delta \xi=+0.10 \mathrm{~mol}$ ) the Gibbs energy of the system changes by $-6.4 \mathrm{~kJ} \mathrm{~mol}^{-1}$. What is the Gibbs energy of reaction at this stage of the reaction? 6A.2(b) When the reaction $2 \mathrm{~A} \rightarrow \mathrm{~B}$ advances by 0.051 mol (that is, $\Delta \xi=+0.051 \mathrm{~mol}$ ) the Gibbs energy of the system changes by $-2.41 \mathrm{~kJ} \mathrm{~mol}^{-1}$. What is the Gibbs energy of reaction at this stage of the reaction?
6A.3(a) The standard Gibbs energy of the reaction $\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{NH}_{3}(\mathrm{~g})$ is $-32.9 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K . What is the value of $\Delta_{\mathrm{r}} G$ when $Q=$ (i) 0.010 , (ii) 1.0 , (iii) 10.0 , (iv) 100000 , (v) 1000000 ? Estimate (by interpolation) the value of $K$ from the values you calculate. What is the actual value of $K$ ?
6A.3(b) The standard Gibbs energy of the reaction $2 \mathrm{NO}_{2}(\mathrm{~g}) \rightarrow \mathrm{N}_{2} \mathrm{O}_{4}(\mathrm{~g})$ is $-4.73 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K . What is the value of $\Delta_{\mathrm{r}} G$ when $Q=$ (i) 0.10 , (ii) 1.0 , (iii) 10 , (iv) 100 ? Estimate (by interpolation) the value of $K$ from the values you calculate. What is the actual value of $K$ ?

6A.4(a) At 2257 K and 1.00 bar total pressure, water is 1.77 per cent dissociated at equilibrium by way of the reaction $2 \mathrm{H}_{2} \mathrm{O}(\mathrm{g}) \rightleftharpoons 2 \mathrm{H}_{2}(\mathrm{~g})+\mathrm{O}_{2}(\mathrm{~g})$. Calculate $K$. 6A.4(b) For the equilibrium, $\mathrm{N}_{2} \mathrm{O}_{4}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NO}_{2}(\mathrm{~g})$, the degree of dissociation, $\alpha$, at 298 K is 0.201 at 1.00 bar total pressure. Calculate $K$.

6A.5(a) Dinitrogen tetroxide is 18.46 per cent dissociated at $25^{\circ} \mathrm{C}$ and 1.00 bar in the equilibrium $\mathrm{N}_{2} \mathrm{O}_{4}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NO}_{2}(\mathrm{~g})$. Calculate $K$ at (i) $25^{\circ} \mathrm{C}$, (ii) $100^{\circ} \mathrm{C}$ given that $\Delta_{\mathrm{r}} H^{\ominus}=+56.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$ over the temperature range. 6A.5(b) Molecular bromine is 24 per cent dissociated at 1600 K and 1.00 bar in the equilibrium $\mathrm{Br}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{Br}(\mathrm{g})$. Calculate $K$ at (i) $1600^{\circ} \mathrm{C}$, (ii) $2000^{\circ} \mathrm{C}$ given that $\Delta_{\mathrm{r}} H^{\ominus}=+112 \mathrm{~kJ} \mathrm{~mol}^{-1}$ over the temperature range.

6A.6(a) From information in the Resource section, calculate the standard Gibbs energy and the equilibrium constant at (i) 298 K and (ii) 400 K for the reaction $\mathrm{PbO}(\mathrm{s})+\mathrm{CO}(\mathrm{g}) \rightleftharpoons \mathrm{Pb}(\mathrm{s})+\mathrm{CO}_{2}(\mathrm{~g})$. Assume that the reaction enthalpy is independent of temperature.
6A.6(b) From information in the Resource section, calculate the standard Gibbs energy and the equilibrium constant at (i) $25^{\circ} \mathrm{C}$ and (ii) $50^{\circ} \mathrm{C}$ for the reaction $\mathrm{CH}_{4}(\mathrm{~g})+3 \mathrm{Cl}_{2}(\mathrm{~g}) \rightleftharpoons \mathrm{CHCl}_{3}(\mathrm{l})+3 \mathrm{HCl}(\mathrm{g})$. Assume that the reaction enthalpy is independent of temperature.

## Problems

6A. 1 The equilibrium constant for the reaction $\mathrm{I}_{2}(\mathrm{~s})+\mathrm{Br}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{IBr}(\mathrm{g})$ is 0.164 at $25^{\circ} \mathrm{C}$. (a) Calculate $\Delta_{\mathrm{r}} G^{\ominus}$ for this reaction. (b) Bromine gas is introduced into a container with excess solid iodine. The pressure and temperature are held at 0.164 atm and $25^{\circ} \mathrm{C}$, respectively. Find the partial pressure of $\operatorname{IBr}(\mathrm{g})$ at equilibrium. Assume that all the bromine is in the liquid form and that the vapour pressure of iodine is negligible. (c) In fact,

6A.2 What is the justification for not including a pure liquid or solid in the expression for an equilibrium constant?

6A.7(a) Establish the relation between $K$ and $K_{c}$ for the reaction $\mathrm{H}_{2} \mathrm{CO}(\mathrm{g}) \rightleftharpoons \mathrm{CO}(\mathrm{g})+\mathrm{H}_{2}(\mathrm{~g})$.
6A.7(b) Establish the relation between $K$ and $K_{c}$ for the reaction $3 \mathrm{~N}_{2}(\mathrm{~g})+\mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{HN}_{3}(\mathrm{~g})$.

6A.8(a) In the gas-phase reaction $2 \mathrm{~A}+\mathrm{B} \rightleftharpoons 3 \mathrm{C}+2 \mathrm{D}$, it was found that, when $1.00 \mathrm{~mol} \mathrm{~A}, 2.00 \mathrm{~mol} \mathrm{~B}$, and 1.00 mol D were mixed and allowed to come to equilibrium at $25^{\circ} \mathrm{C}$, the resulting mixture contained 0.90 mol C at a total pressure of 1.00 bar. Calculate (i) the mole fractions of each species at equilibrium, (ii) $K_{x}$, (iii) $K$, and (iv) $\Delta_{\mathrm{r}} G^{\ominus}$.
6A.8(b) In the gas-phase reaction $\mathrm{A}+\mathrm{B} \rightleftharpoons \mathrm{C}+2 \mathrm{D}$, it was found that, when $2.00 \mathrm{~mol} \mathrm{~A}, 1.00 \mathrm{~mol} \mathrm{~B}$, and 3.00 mol D were mixed and allowed to come to equilibrium at $25^{\circ} \mathrm{C}$, the resulting mixture contained 0.79 mol C at a total pressure of 1.00 bar. Calculate (i) the mole fractions of each species at equilibrium, (ii) $K_{x}$, (iii) $K$, and (iv) $\Delta_{\mathrm{r}} G^{\ominus}$.

6A.9(a) The standard reaction Gibbs energy of the isomerization of borneol $\left(\mathrm{C}_{10} \mathrm{H}_{17} \mathrm{OH}\right)$ to isoborneol in the gas phase at 503 K is $+9.4 \mathrm{~kJ} \mathrm{~mol}^{-1}$. Calculate the reaction Gibbs energy in a mixture consisting of 0.15 mol of borneol and 0.30 mol of isoborneol when the total pressure is 600 Torr.

6A.9(b) The equilibrium pressure of $\mathrm{H}_{2}$ over solid uranium and uranium hydride, $\mathrm{UH}_{3}$, at 500 K is 139 Pa . Calculate the standard Gibbs energy of formation of $\mathrm{UH}_{3}(\mathrm{~s})$ at 500 K .

6A.10(a) The standard Gibbs energy of formation of $\mathrm{NH}_{3}(\mathrm{~g})$ is $-16.5 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K . What is the reaction Gibbs energy when the partial pressures of the $\mathrm{N}_{2}, \mathrm{H}_{2}$, and $\mathrm{NH}_{3}$ (treated as perfect gases) are $3.0 \mathrm{bar}, 1.0 \mathrm{bar}$, and 4.0 bar, respectively? What is the spontaneous direction of the reaction in this case?
6A.10(b) The standard Gibbs energy of formation of $\mathrm{PH}_{3}(\mathrm{~g})$ is $+13.4 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K . What is the reaction Gibbs energy when the partial pressures of the $\mathrm{H}_{2}$ and $\mathrm{PH}_{3}$ (treated as perfect gases) are 1.0 bar and 0.60 bar, respectively? What is the spontaneous direction of the reaction in this case?
6A.11(a) For $\mathrm{CaF}_{2}(\mathrm{~s}) \rightleftharpoons \mathrm{Ca}^{2+}(\mathrm{aq})+2 \mathrm{~F}^{-}(\mathrm{aq}), K=3.9 \times 10^{-11}$ at $25^{\circ} \mathrm{C}$ and the standard Gibbs energy of formation of $\mathrm{CaF}_{2}(\mathrm{~s})$ is $-1167 \mathrm{~kJ} \mathrm{~mol}^{-1}$. Calculate the standard Gibbs energy of formation of $\mathrm{CaF}_{2}(\mathrm{aq})$. 6A.11(b) For $\mathrm{PbI}_{2}(\mathrm{~s}) \rightleftharpoons \mathrm{Pb}^{2+}(\mathrm{aq})+2 \mathrm{I}^{-}(\mathrm{aq}), K=1.4 \times 10^{-8}$ at $25^{\circ} \mathrm{C}$ and the standard Gibbs energy of formation of $\mathrm{PbI}_{2}(\mathrm{~s})$ is $-173.64 \mathrm{~kJ} \mathrm{~mol}^{-1}$. Calculate the standard Gibbs energy of formation of $\mathrm{PbI}_{2}(\mathrm{aq})$.
solid iodine has a measurable vapour pressure at $25^{\circ} \mathrm{C}$. In this case, how would the calculation have to be modified?

6A. 2 Calculate the equilibrium constant of the reaction $\mathrm{CO}(\mathrm{g})+\mathrm{H}_{2}(\mathrm{~g}) \rightleftharpoons \mathrm{H}_{2} \mathrm{CO}(\mathrm{g})$ given that, for the production of liquid formaldehyde, $\Delta_{\mathrm{r}} G^{\ominus}=+28.95 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K and that the vapour pressure of formaldehyde is 1500 Torr at that temperature.

6A. 3 A sealed container was filled with $0.300 \mathrm{~mol} \mathrm{H}_{2}(\mathrm{~g}), 0.400 \mathrm{~mol} \mathrm{I}_{2}(\mathrm{~g})$, and $0.200 \mathrm{~mol} \mathrm{HI}(\mathrm{g})$ at 870 K and total pressure 1.00 bar. Calculate the amounts of the components in the mixture at equilibrium given that $K=870$ for the reaction $\mathrm{H}_{2}(\mathrm{~g})+\mathrm{I}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{HI}(\mathrm{g})$.
6A.4 ${ }^{\ddagger}$ Nitric acid hydrates have received much attention as possible catalysts for heterogeneous reactions that bring about the Antarctic ozone hole. Standard reaction Gibbs energies are as follows:
(i) $\mathrm{H}_{2} \mathrm{O}(\mathrm{g}) \rightarrow \mathrm{H}_{2} \mathrm{O}(\mathrm{s}) \quad \Delta_{\mathrm{r}} G^{\ominus}-23.6 \mathrm{~kJ} \mathrm{~mol}^{-1}$
(ii) $\mathrm{H}_{2} \mathrm{O}(\mathrm{g})+\mathrm{HNO}_{3}(\mathrm{~g}) \rightarrow \mathrm{HNO}_{3} \cdot \mathrm{H}_{2} \mathrm{O}(\mathrm{s}) \quad \Delta_{\mathrm{r}} \mathrm{G}^{\ominus}-57.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$
(iii) $2 \mathrm{H}_{2} \mathrm{O}(\mathrm{g})+\mathrm{HNO}_{3}(\mathrm{~g}) \rightarrow \mathrm{HNO}_{3} \cdot 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{s}) \quad \Delta_{\mathrm{r}} \mathrm{G}^{\ominus}-85.6 \mathrm{~kJ} \mathrm{~mol}^{-1}$
(iv) $3 \mathrm{H}_{2} \mathrm{O}(\mathrm{g})+\mathrm{HNO}_{3}(\mathrm{~g}) \rightarrow \mathrm{HNO}_{3} \cdot 3 \mathrm{H}_{2} \mathrm{O}(\mathrm{s}) \quad \Delta_{\mathrm{r}} \mathrm{G}^{\ominus}-112.8 \mathrm{~kJ} \mathrm{~mol}^{-1}$

Which solid is thermodynamically most stable at 190 K if $p_{\mathrm{H}_{2}}=0.13 \mu$ bar and $p_{\mathrm{HNO}_{3}}=0.41$ nbar Hint: Try computing $\Delta_{\mathrm{r}} G$ for each reaction under the prevailing conditions; if more than one solid form spontaneously, examine $\Delta_{\mathrm{r}} G$ for the conversion of one solid to another.

6A. 5 Express the equilibrium constant of a gas-phase reaction $\mathrm{A}+3 \mathrm{~B} \rightleftharpoons 2 \mathrm{C}$ in terms of the equilibrium value of the extent of reaction, $\xi$, given that initially $A$ and $B$ were present in stoichiometric proportions. Find an expression for $\xi$ as a function of the total pressure, $p$, of the reaction mixture and sketch a graph of the expression obtained.

## TOPIC 6B The response to equilibria to the conditions

## Discussion questions

6B. 1 Suggest how the thermodynamic equilibrium constant may respond differently to changes in pressure and temperature from the equilibrium constant expressed in terms of partial pressures.

6B. 2 Account for Le Chatelier's principle in terms of thermodynamic quantities.
68. 3 Explain the molecular basis of the van 't Hoff equation for the temperature dependence of $K$.

## Exercises

6B.1(a) The standard reaction enthalpy of $\mathrm{Zn}(\mathrm{s})+\mathrm{H}_{2} \mathrm{O}(\mathrm{g}) \rightarrow \mathrm{ZnO}(\mathrm{s})+\mathrm{H}_{2}(\mathrm{~g})$ is approximately constant at $+224 \mathrm{~kJ} \mathrm{~mol}^{-1}$ from 920 K up to 1280 K . The standard reaction Gibbs energy is $+33 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 1280 K . Estimate the temperature at which the equilibrium constant becomes greater than 1 . 6B.1(b) The standard enthalpy of a certain reaction is approximately constant at $+125 \mathrm{~kJ} \mathrm{~mol}^{-1}$ from 800 K up to 1500 K . The standard reaction Gibbs energy is $+22 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 1120 K . Estimate the temperature at which the equilibrium constant becomes greater than 1 .

6B.2(a) The equilibrium constant of the reaction $2 \mathrm{C}_{3} \mathrm{H}_{6}(\mathrm{~g}) \rightleftharpoons \mathrm{C}_{2} \mathrm{H}_{4}(\mathrm{~g})+\mathrm{C}_{4} \mathrm{H}_{8}(\mathrm{~g})$ is found to fit the expression $\ln K=A+B / T+C / T^{2}$ between 300 K and 600 K , with $A=-1.04, B=-1088 \mathrm{~K}$, and $C=1.51 \times 10^{5} \mathrm{~K}^{2}$. Calculate the standard reaction enthalpy and standard reaction entropy at 400 K .
6B.2(b) The equilibrium constant of a reaction is found to fit the expression In $K=A+B / T+C / T^{3}$ between 400 K and 500 K with $A=-2.04, B=-1176 \mathrm{~K}$, and $C=2.1 \times 10^{7} \mathrm{~K}^{3}$. Calculate the standard reaction enthalpy and standard reaction entropy at 450 K .

6B.3(a) Calculate the percentage change in $K_{x}$ for the reaction $\mathrm{H}_{2} \mathrm{CO}(\mathrm{g}) \rightleftharpoons \mathrm{CO}(\mathrm{g})+\mathrm{H}_{2}(\mathrm{~g})$ when the total pressure is increased from 1.0 bar to 2.0 bar at constant temperature.

6B.3(b) Calculate the percentage change in $K_{x}$ for the reaction $\mathrm{CH}_{3} \mathrm{OH}(\mathrm{g})+\mathrm{NOCl}(\mathrm{g}) \rightleftharpoons \mathrm{HCl}(\mathrm{g})+\mathrm{CH}_{3} \mathrm{NO}_{2}(\mathrm{~g})$ when the total pressure is increased from 1.0 bar to 2.0 bar at constant temperature.
6B.4(a) The equilibrium constant for the gas-phase isomerization of borneol $\left(\mathrm{C}_{10} \mathrm{H}_{17} \mathrm{OH}\right)$ to isoborneol at 503 K is 0.106 . A mixture consisting of 7.50 g of borneol and 14.0 g of isoborneol in a container of volume $5.0 \mathrm{dm}^{3}$ is heated to 503 K and allowed to come to equilibrium. Calculate the mole fractions of the two substances at equilibrium.

## Problems

6B. 1 Consider the dissociation of methane, $\mathrm{CH}_{4}(\mathrm{~g})$, into the elements $\mathrm{H}_{2}(\mathrm{~g})$ and C (s, graphite). (a) Given that $\Delta_{\mathrm{f}} H^{\ominus}\left(\mathrm{CH}_{4}, \mathrm{~g}\right)=-74.85 \mathrm{~kJ} \mathrm{~mol}^{-1}$ and that
${ }^{\ddagger}$ These problems were supplied by Charles Trapp and Carmen Giunta.

6B.4(b) The equilibrium constant for the reaction $\mathrm{N}_{2}(\mathrm{~g})+\mathrm{O}_{2}(\mathrm{~g}) \rightleftharpoons 2 \mathrm{NO}(\mathrm{g})$ is $1.69 \times 10^{-3}$ at 2300 K . A mixture consisting of 5.0 g of nitrogen and 2.0 g of oxygen in a container of volume $1.0 \mathrm{dm}^{3}$ is heated to 2300 K and allowed to come to equilibrium. Calculate the mole fraction of NO at equilibrium.

6B.5(a) What is the standard enthalpy of a reaction for which the equilibrium constant is (i) doubled, (ii) halved when the temperature is increased by 10 K at 298 K ?
6B.5(b) What is the standard enthalpy of a reaction for which the equilibrium constant is (i) doubled, (ii) halved when the temperature is increased by 15 K at 310 K ?

6B.6(a) Estimate the temperature at which $\mathrm{CaCO}_{3}$ (calcite) decomposes. 6B.6(b) Estimate the temperature at which $\mathrm{CuSO}_{4} \cdot 5 \mathrm{H}_{2} \mathrm{O}$ undergoes dehydration.

6B.7(a) The dissociation vapour pressure of a salt $\mathrm{A}_{2} \mathrm{~B}(\mathrm{~s}) \rightleftharpoons \mathrm{A}_{2}(\mathrm{~g})+\mathrm{B}(\mathrm{g})$ at $367^{\circ} \mathrm{C}$ is 208 kPa but at $477^{\circ} \mathrm{C}$ it has risen to 547 kPa . Calculate (i) the equilibrium constant, (ii) the standard reaction Gibbs energy, (iii) the standard enthalpy, (iv) the standard entropy of dissociation, all at $422^{\circ} \mathrm{C}$. Assume that the vapour behaves as a perfect gas and that $\Delta H^{\ominus}$ and $\Delta S^{\ominus}$ are independent of temperature in the range given.
6B.7(b) The dissociation vapour pressure of $\mathrm{NH}_{4} \mathrm{Cl}$ at $427^{\circ} \mathrm{C}$ is 608 kPa but at $459^{\circ} \mathrm{C}$ it has risen to 1115 kPa . Calculate (i) the equilibrium constant, (ii) the standard reaction Gibbs energy, (iii) the standard enthalpy, (iv) the standard entropy of dissociation, all at $427^{\circ} \mathrm{C}$. Assume that the vapour behaves as a perfect gas and that $\Delta H^{\ominus}$ and $\Delta S^{\ominus}$ are independent of temperature in the range given.
$\Delta_{\mathrm{r}} S^{\ominus}=-80.67 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$ at 298 K , calculate the value of the equilibrium constant at 298 K . (b) Assuming that $\Delta_{\mathrm{r}} H^{\ominus}$ is independent of temperature, calculate K at $50^{\circ} \mathrm{C}$. (c) Calculate the degree of dissociation, $\alpha$, of methane
at $25^{\circ} \mathrm{C}$ and a total pressure of 0.010 bar. (d) Without doing any numerical calculations, explain how the degree of dissociation for this reaction will change as the pressure and temperature are varied.

6B. 2 The equilibrium pressure of $\mathrm{H}_{2}$ over $\mathrm{U}(\mathrm{s})$ and $\mathrm{UH}_{3}(\mathrm{~s})$ between 450 K and 715 K fits the expression $\ln (p / \mathrm{Pa})=A+B / T+C \ln (T / \mathrm{K})$, with $A=69.32$, $B=-1.464 \times 10^{4} \mathrm{~K}$, and $C=-5.65$. Find an expression for the standard enthalpy of formation of $\mathrm{UH}_{3}(\mathrm{~s})$ and from it calculate $\Delta_{\mathrm{f}} C_{p}^{\ominus}$.
6B. 3 The degree of dissociation, $\alpha$, of $\mathrm{CO}_{2}(\mathrm{~g})$ into $\mathrm{CO}(\mathrm{g})$ and $\mathrm{O}_{2}(\mathrm{~g})$ at high temperatures was found to vary with temperature as follows:

| $T / \mathrm{K}$ | 1395 | 1443 | 1498 |
| :--- | :--- | :--- | :--- |
| $\alpha / 10^{-4}$ | 1.44 | 2.50 | 4.71 |

Assuming $\Delta_{\mathrm{r}} H^{\ominus}$ to be constant over this temperature range, calculate $K$, $\Delta_{\mathrm{r}} G^{\ominus}, \Delta_{\mathrm{r}} H^{\ominus}$, and $\Delta_{\mathrm{r}} S^{\ominus}$. Make any justifiable approximations.

6B. 4 The standard reaction enthalpy for the decomposition of $\mathrm{CaCl}_{2} \cdot \mathrm{NH}_{3}(\mathrm{~s})$ into $\mathrm{CaCl}_{2}(\mathrm{~s})$ and $\mathrm{NH}_{3}(\mathrm{~g})$ is nearly constant at $+78 \mathrm{~kJ} \mathrm{~mol}^{-1}$ between 350 K and 470 K . The equilibrium pressure of $\mathrm{NH}_{3}$ in the presence of $\mathrm{CaCl}_{2} \cdot \mathrm{NH}_{3}$ is 1.71 kPa at 400 K . Find an expression for the temperature dependence of $\Delta_{\mathrm{r}} G^{\ominus}$ in the same range.

6B. 5 Acetic acid was evaporated in a container of volume $21.45 \mathrm{~cm}^{3}$ at 437 K and at an external pressure of 101.9 kPa , and the container was then sealed. The mass of acid present in the sealed container was 0.0519 g . The experiment was repeated with the same container but at 471 K , and it was found that
0.0380 g of acetic acid was present. Calculate the equilibrium constant for the dimerization of the acid in the vapour and the enthalpy of vaporization.

6B. 6 The dissociation of $\mathrm{I}_{2}$ can be monitored by measuring the total pressure, and three sets of results are as follows:

| $T / \mathrm{K}$ | 973 | 1073 | 1173 |
| :--- | :---: | :---: | :---: |
| $100 p / \mathrm{atm}$ | 6.244 | 6.500 | 9.181 |
| $10^{4} n_{\mathrm{I}}$ | 2.4709 | 2.4555 | 2.4366 |

where $n_{\mathrm{I}}$ is the amount of I atoms per mole of $\mathrm{I}_{2}$ molecules in the mixture, which occupied $342.68 \mathrm{~cm}^{3}$. Calculate the equilibrium constants of the dissociation and the standard enthalpy of dissociation at the mean temperature.

6B. $7^{\ddagger}$ The 1980s saw reports of $\Delta_{\mathrm{r}} G^{\ominus}\left(\mathrm{SiH}_{2}\right)$ ranging from 243 to $289 \mathrm{~kJ} \mathrm{~mol}^{-1}$. If the standard enthalpy of formation is uncertain by this amount, by what factor is the equilibrium constant for the formation of $\mathrm{SiH}_{2}$ from its elements uncertain at (a) 298 K , (b) 700 K ?

6B. 8 Find an expression for the standard reaction Gibbs energy at a temperature $T^{\prime}$ in terms of its value at another temperature $T$ and the coefficients $a, b$, and $c$ in the expression for the molar heat capacity listed in Table 2B.1. Evaluate the standard Gibbs energy of formation of $\mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ at 372 K from its value at 298 K .

6B. 9 Derive an expression for the temperature dependence of $K_{c}$ for a gasphase reaction.

## TOPIC 6C Electrochemical cells

## Discussion questions

6C.1 Explain why reactions that are not redox reactions may be used to generate an electric current.

6C.2 Explain the role of a salt bridge.

6C.3 Why is it necessary to measure the cell potential under zero-current conditions?

6C.4 Can you identify other contributions to the cell potential when a current is being drawn from the cell?

## Exercises

6C.1(a) Write the cell reaction and electrode half-reactions and calculate the standard potential of each of the following cells:
(i) $\mathrm{Zn}\left|\mathrm{ZnSO}_{4}(\mathrm{aq}) \|\left|\mathrm{AgNO}_{3}(\mathrm{aq})\right| \mathrm{Ag}\right.$
(ii) $\mathrm{Cd}\left|\mathrm{CdCl}_{2}(\mathrm{aq})\right|\left|\mathrm{HNO}_{3}(\mathrm{aq})\right| \mathrm{H}_{2}(\mathrm{~g}) \mid \mathrm{Pt}$
(iii) $\mathrm{Pt}\left|\mathrm{K}_{3}\left[\mathrm{Fe}(\mathrm{CN})_{6}\right](\mathrm{aq}), \mathrm{K}_{4}\left[\mathrm{Fe}(\mathrm{CN})_{6}\right](\mathrm{aq})\right|\left|\mathrm{CrCl}_{3}(\mathrm{aq})\right| \mathrm{Cr}$

6C.1(b) Write the cell reaction and electrode half-reactions and calculate the standard potential of each the following cells:
(i) $\mathrm{Pt}\left|\mathrm{Cl}_{2}(\mathrm{~g})\right| \mathrm{HCl}(\mathrm{aq})\left|\left|\mathrm{K}_{2} \mathrm{CrO}_{4}(\mathrm{aq})\right| \mathrm{Ag}_{2} \mathrm{CrO}_{4}(\mathrm{~s})\right| \mathrm{Ag}$
(ii) $\mathrm{Pt}\left|\mathrm{Fe}^{3+}(\mathrm{aq}), \mathrm{Fe}^{2+}(\mathrm{aq})\right|\left|\mathrm{Sn}^{4+}(\mathrm{aq}), \mathrm{Sn}^{2+}(\mathrm{aq})\right| \mathrm{Pt}$
(iii) $\mathrm{Cu}\left|\mathrm{Cu}^{2+}(\mathrm{aq})\right|\left|\mathrm{Mn}^{2+}(\mathrm{aq}), \mathrm{H}^{+}(\mathrm{aq})\right| \mathrm{MnO}_{2}(\mathrm{~s}) \mid \mathrm{Pt}$

6C.2(a) Devise cells in which the following are the reactions and calculate the standard cell potential in each case:
(i) $\mathrm{Zn}(\mathrm{s})+\mathrm{CuSO}_{4}(\mathrm{aq}) \rightarrow \mathrm{ZnSO}_{4}(\mathrm{aq})+\mathrm{Cu}(\mathrm{s})$
(ii) $2 \mathrm{AgCl}(\mathrm{s})+\mathrm{H}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{HCl}(\mathrm{aq})+2 \mathrm{Ag}(\mathrm{s})$
(iii) $2 \mathrm{H}_{2}(\mathrm{~g})+\mathrm{O}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$

6C.2(b) Devise cells in which the following are the reactions and calculate the standard cell potential in each case:
(i) $2 \mathrm{Na}(\mathrm{s})+2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l}) \rightarrow 2 \mathrm{NaOH}(\mathrm{aq})+\mathrm{H}_{2}(\mathrm{~g})$
(ii) $\mathrm{H}_{2}(\mathrm{~g})+\mathrm{I}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{HI}(\mathrm{aq})$
(iii) $\mathrm{H}_{3} \mathrm{O}^{+}(\mathrm{aq})+\mathrm{OH}^{-}(\mathrm{aq}) \rightarrow 2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$

6C.3(a) Use the Debye-Hückel limiting law and the Nernst equation to estimate the potential of the cell $\operatorname{Ag}|\operatorname{AgBr}(\mathrm{s})| \operatorname{KBr}(\mathrm{aq}$, $\left.0.050 \mathrm{~mol} \mathrm{~kg}^{-1}\right) \| \mathrm{Cd}\left(\mathrm{NO}_{3}\right)_{2}\left(\mathrm{aq}, 0.010 \mathrm{~mol} \mathrm{~kg}^{-1}\right) \mid \mathrm{Cd}$ at $25^{\circ} \mathrm{C}$.
6C.3(b) Consider the cell $\mathrm{Pt}\left|\mathrm{H}_{2}\left(\mathrm{~g}, \mathrm{p}^{\ominus}\right)\right| \mathrm{HCl}(\mathrm{aq})|\mathrm{AgCl}(\mathrm{s})| \mathrm{Ag}$, for which the cell reaction is $2 \mathrm{AgCl}(\mathrm{s})+\mathrm{H}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{Ag}(\mathrm{s})+2 \mathrm{HCl}(\mathrm{aq})$. At $25^{\circ} \mathrm{C}$ and a molality of HCl of $0.010 \mathrm{~mol} \mathrm{~kg}^{-1}, E_{\text {cell }}=+0.4658 \mathrm{~V}$. (i) Write the Nernst equation for the cell reaction. (ii) Calculate $\Delta_{\mathrm{r}} G$ for the cell reaction. (iii) Assuming that the DebyeHückel limiting law holds at this concentration, calculate $E^{\ominus}\left(\mathrm{Cl}^{-}, \mathrm{AgCl}, \mathrm{Ag}\right)$.

## Problems

6C.1 A fuel cell develops an electric potential from the chemical reaction between reagents supplied from an outside source. What is the cell potential of a cell fuelled by (a) hydrogen and oxygen, (b) the combustion of butane at 1.0 bar and 298 K ?

6C. 2 Although the hydrogen electrode may be conceptually the simplest electrode and is the basis for our reference state of electrical potential in electrochemical systems, it is cumbersome to use. Therefore, several substitutes for it have been devised. One of these alternatives is the quinhydrone electrode (quinhydrone, $\mathrm{Q} \cdot \mathrm{QH}_{2}$, is a complex of quinone, $\mathrm{C}_{6} \mathrm{H}_{4} \mathrm{O}_{2}=\mathrm{Q}$, and hydroquinone, $\mathrm{C}_{6} \mathrm{H}_{4} \mathrm{O}_{2} \mathrm{H}_{2}=\mathrm{QH}_{2}$ ). The electrode halfreaction is $\mathrm{Q}(\mathrm{aq})+2 \mathrm{H}^{+}(\mathrm{aq})+2 \mathrm{e}^{-} \rightarrow \mathrm{QH}_{2}(\mathrm{aq}), E^{\ominus}=+0.6994 \mathrm{~V}$. If the cell $\mathrm{Hg}\left|\mathrm{Hg}_{2} \mathrm{Cl}_{2}(\mathrm{~s})\right| \mathrm{HCl}(\mathrm{aq})\left|\mathrm{Q} \cdot \mathrm{QH}_{2}\right| \mathrm{Au}$ is prepared, and the measured cell potential
is +0.190 V , what is the pH of the HCl solution? Assume that the DebyeHückel limiting law is applicable.

6C. 3 Fuel cells provide electrical power for spacecraft (as in the NASA space shuttles) and also show promise as power sources for automobiles. Hydrogen and carbon monoxide have been investigated for use in fuel cells, so their solubilities in molten salts are of interest. Their solubilities in a molten $\mathrm{NaNO}_{3} / \mathrm{KNO}_{3}$ mixture were found to fit the following expressions:

$$
\log s_{\mathrm{H}_{2}}=-5.39-\frac{980}{T / \mathrm{K}} \quad \log s_{\mathrm{CO}}=-5.98-\frac{980}{T / \mathrm{K}}
$$

where $s$ is the solubility in $\mathrm{mol} \mathrm{cm}^{-3} \mathrm{bar}^{-1}$. Calculate the standard molar enthalpies of solution of the two gases at 570 K .

## TOPIC 6D Electrode potentials

## Discussion questions

6D. 1 Describe a method for the determination of the standard potential of a redox couple.

## Exercises

6D.1(a) Calculate the equilibrium constants of the following reactions at $25^{\circ} \mathrm{C}$ from standard potential data:
(i) $\mathrm{Sn}(\mathrm{s})+\mathrm{Sn}^{4+}(\mathrm{aq}) \rightleftharpoons 2 \mathrm{Sn}^{2+}(\mathrm{aq})$
(ii) $\mathrm{Sn}(\mathrm{s})+2 \mathrm{AgCl}(\mathrm{s}) \rightleftharpoons \mathrm{SnCl}_{2}(\mathrm{aq})+2 \mathrm{Ag}(\mathrm{s})$

6D.1(b) Calculate the equilibrium constants of the following reactions at $25^{\circ} \mathrm{C}$ from standard potential data:

## Problems

6D. 1 The potential of the cell $\mathrm{Pt}\left|\mathrm{H}_{2}\left(\mathrm{~g}, p^{\ominus}\right)\right| \mathrm{HCl}(\mathrm{aq}, b)\left|\mathrm{Hg}_{2} \mathrm{Cl}_{2}(\mathrm{~s})\right| \mathrm{Hg}(\mathrm{l})$ has been measured with high precision with the following results at $25^{\circ} \mathrm{C}$ :

| $b /\left(\mathrm{mmol} \mathrm{kg}^{-1}\right)$ | 1.6077 | 3.0769 | 5.0403 | 7.6938 | 10.9474 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $E / \mathrm{V}$ | 0.60080 | 0.56825 | 0.54366 | 0.52267 | 0.50532 |

Determine the standard cell potential and the mean activity coefficient of HCl at these molalities. (Make a least-squares fit of the data to the best straight line.)

## Integrated activities

$6.1^{\ddagger}$ Thorn et al. (J. Phys. Chem. 100, 14178 (1996)) carried out a study of $\mathrm{Cl}_{2} \mathrm{O}(\mathrm{g})$ by photoelectron ionization. From their measurements, they report $\Delta_{\mathrm{f}} H^{\ominus}\left(\mathrm{Cl}_{2} \mathrm{O}\right)=+77.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$. They combined this measurement with literature data on the reaction $\mathrm{Cl}_{2} \mathrm{O}(\mathrm{g})+\mathrm{H}_{2} \mathrm{O}(\mathrm{g}) \rightarrow 2 \mathrm{HOCl}(\mathrm{g})$, for which $K=8.2 \times 10^{-2}$ and $\Delta_{\mathrm{r}} S^{\ominus}=+16.38 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$, and with readily available thermodynamic data on water vapour to report a value for $\Delta_{\mathrm{f}} H^{\ominus}$ (HOCl). Calculate that value. All quantities refer to 298 K .

6D. 2 Devise a method for the determination of the pH of an aqueous solution.
(i) $\mathrm{Sn}(\mathrm{s})+\mathrm{CuSO}_{4}(\mathrm{aq}) \rightleftharpoons \mathrm{Cu}(\mathrm{s})+\mathrm{SnSO}_{4}(\mathrm{aq})$
(ii) $\mathrm{Cu}^{2+}(\mathrm{aq})+\mathrm{Cu}(\mathrm{s}) \rightleftharpoons 2 \mathrm{Cu}^{+}(\mathrm{aq})$

6D.2(a) The potential of the cell $\mathrm{Ag}|\mathrm{AgI}(\mathrm{s})| \mathrm{AgI}(\mathrm{aq}) \mid \mathrm{Ag}$ is +0.9509 V at $25^{\circ} \mathrm{C}$. Calculate (i) the solubility product of AgI and (ii) its solubility. 6D.2(b) The potential of the cell $\mathrm{Bi}\left|\mathrm{Bi}_{2} \mathrm{~S}_{3}(\mathrm{~s})\right| \mathrm{Bi}_{2} \mathrm{~S}_{3}(\mathrm{aq}) \mid \mathrm{Bi}$ is -0.96 V at $25^{\circ} \mathrm{C}$. Calculate (i) the solubility product of $\mathrm{Bi}_{2} \mathrm{~S}_{3}$ and (ii) its solubility.

6D. 2 The standard potential of the $\mathrm{AgCl} / \mathrm{Ag}, \mathrm{Cl}^{-}$couple fits the expression

$$
\begin{aligned}
E^{\ominus} / \mathrm{V}= & 0.23659-4.8564 \times 10^{-4}\left(\theta /{ }^{\circ} \mathrm{C}\right)-3.4205 \times 10^{-6}\left(\theta /{ }^{\circ} \mathrm{C}\right)^{2} \\
& +5.869 \times 10^{-9}\left(\theta /{ }^{\circ} \mathrm{C}\right)^{3}
\end{aligned}
$$

Calculate the standard Gibbs energy and enthalpy of formation of $\mathrm{Cl}^{-}(\mathrm{aq})$ and its entropy at 298 K .
6.3 Consider the cell, $\mathrm{Zn}(\mathrm{s})\left|\mathrm{ZnCl}_{2}\left(0.0050 \mathrm{~mol} \mathrm{~kg}^{-1}\right)\right| \mathrm{Hg}_{2} \mathrm{Cl}_{2}(\mathrm{~s}) \mid \mathrm{Hg}(\mathrm{l})$, for which the cell reaction is $\mathrm{Hg}_{2} \mathrm{Cl}_{2}(\mathrm{~s})+\mathrm{Zn}(\mathrm{s}) \rightarrow 2 \mathrm{Hg}(\mathrm{l})+2 \mathrm{Cl}^{-}(\mathrm{aq})+\mathrm{Zn}^{2+}(\mathrm{aq})$. Given that $E^{\ominus}\left(\mathrm{Zn}^{2+}, \mathrm{Zn}\right)=-0.7628 \mathrm{~V}, E^{\ominus}\left(\mathrm{Hg}_{2} \mathrm{Cl}_{2}, \mathrm{Hg}\right)=+0.2676 \mathrm{~V}$, and that the cell potential is +1.2272 V , (a) write the Nernst equation for the cell. Determine (b) the standard cell potential, (c) $\Delta_{\mathrm{r}} G, \Delta_{\mathrm{r}} G^{\ominus}$, and $K$ for the cell reaction, (d) the mean ionic activity and activity coefficient of $\mathrm{ZnCl}_{2}$ from the measured cell potential, and ( e ) the mean ionic activity coefficient of $\mathrm{ZnCl}_{2}$ from the Debye-Hückel limiting law. (f) Given that $\left(\partial E_{\text {cell }} / \partial T\right)_{p}=-4.52 \times 10^{-4} \mathrm{~V} \mathrm{~K}^{-1}$, calculate $\Delta_{\mathrm{r}} S$ and $\Delta_{\mathrm{r}} H$.
6.4 Careful measurements of the potential of the cell $\mathrm{Pt}\left|\mathrm{H}_{2}\left(\mathrm{~g}, p^{\ominus}\right)\right| \mathrm{NaOH}(\mathrm{aq}$, $\left.0.0100 \mathrm{~mol} \mathrm{~kg}^{-1}\right), \mathrm{Nacl}\left(\mathrm{aq}, 0.01125 \mathrm{~mol} \mathrm{~kg}^{-1}\right)|\mathrm{AgCl}(\mathrm{s})| \mathrm{Ag}(\mathrm{s})$ have been reported. Among the data is the following information:

| $\theta /{ }^{\circ} \mathrm{C}$ | 20.0 | 25.0 | 30.0 |
| :--- | :---: | :---: | :---: |
| $E_{\text {cell }} / \mathrm{V}$ | 1.04774 | 1.04864 | 1.04942 |

Calculate $\mathrm{p} K_{\mathrm{w}}$ at these temperatures and the standard enthalpy and entropy of the autoprotolysis of water at $25.0^{\circ} \mathrm{C}$.
6.5 Measurements of the potential of cells of the type $\mathrm{Ag}|\mathrm{AgX}(\mathrm{s})| \mathrm{MX}\left(b_{1}\right) \mid \mathrm{M}_{x} \mathrm{Hg}\left|\mathrm{MX}\left(b_{2}\right)\right| \mathrm{AgX}(\mathrm{s}) \mid \mathrm{Ag}$, where $\mathrm{M}_{x} \mathrm{Hg}$ denotes an amalgam and the electrolyte is an LiCl in ethylene glycol, are given below. Estimate the activity coefficient at the concentration marked * and then use this value to calculate activity coefficients from the measured cell potential at the other concentrations. Base your answer on the Davies equation (eqn 5F.11) with $A=1.461, B=1.70$, $C=0.20$, and $I=b / b^{\ominus}$. For $b_{2}=0.09141 \mathrm{~mol} \mathrm{~kg}^{-1}$ :

| $b_{1} /\left(\mathrm{mol} \mathrm{kg}^{-1}\right)$ | 0.0555 | 0.09141 | 0.1652 | 0.2171 | 1.040 | $1.350^{*}$ |
| :--- | ---: | :--- | :--- | :--- | :--- | :--- |
| $E / \mathrm{V}$ | -0.0220 | 0.0000 | 0.0263 | 0.0379 | 0.1156 | 0.1336 |

6.6 ${ }^{\ddagger}$ The table below summarizes the potential of the cell $\mathrm{Pd} \mid \mathrm{H}_{2}(\mathrm{~g}, 1$ bar $) \mid \mathrm{BH}(\mathrm{aq}, b), \mathrm{B}(\mathrm{aq}, b)|\mathrm{AgCl}(\mathrm{s})| \mathrm{Ag}$. Each measurement is made at equimolar concentrations of 2-aminopyridinium chloride (BH) and 2-aminopyridine (B). The data are for $25^{\circ} \mathrm{C}$ and it is found that $E^{\ominus}=0.22251 \mathrm{~V}$. Use the data to determine $\mathrm{p} K_{\mathrm{a}}$ for the acid at $25^{\circ} \mathrm{C}$ and the mean activity coefficient ( $\gamma_{ \pm}$) of BH as a function of molality (b) and ionic strength ( $I$ ). Use the Davies equation (eqn 5F.11) with $A=0.5091$ and $B$ and $C$ are parameters that depend upon the ions. Draw a graph of the mean activity coefficient with $b=0.04 \mathrm{~mol} \mathrm{~kg}^{-1}$ and $0 \leq I \leq 0.1$.

| $b /\left(\mathrm{mol} \mathrm{kg}^{-1}\right)$ | 0.01 | 0.02 | 0.03 | 0.04 | 0.05 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $E_{\text {cell }}\left(25^{\circ} \mathrm{C}\right) / \mathrm{V}$ | 0.74452 | 0.72853 | 0.71928 | 0.71314 | 0.70809 |
| $b /\left(\mathrm{mol} \mathrm{kg}^{-1}\right)$ | 0.06 | 0.07 | 0.08 | 0.09 | 0.10 |
| $E_{\text {cell }}\left(25^{\circ} \mathrm{C}\right) / \mathrm{V}$ | 0.70380 | 0.70059 | 0.69790 | 0.69571 | 0.69338 |

Hint: Use mathematical software or a spreadsheet.
6.7 Here we investigate the molecular basis for the observation that the hydrolysis of ATP is exergonic at $\mathrm{pH}=7.0$ and 310 K . (a) It is thought that the exergonicity of ATP hydrolysis is due in part to the fact that the standard entropies of hydrolysis of polyphosphates are positive. Why would an increase in entropy accompany the hydrolysis of a triphosphate group into a diphosphate and a phosphate group? (b) Under identical conditions, the Gibbs energies of hydrolysis of $\mathrm{H}_{4} \mathrm{ATP}$ and $\mathrm{MgATP}^{2-}$, a complex between the $\mathrm{Mg}^{2+}$ ion and ATP ${ }^{4-}$, are less negative than the Gibbs energy of hydrolysis of ATP ${ }^{4-}$. This observation has been used to support the hypothesis that electrostatic repulsion between adjacent phosphate groups is a factor that controls the exergonicity of ATP hydrolysis. Provide a rationale for the hypothesis and discuss how the experimental evidence supports it. Do these electrostatic effects contribute to the $\Delta_{\mathrm{r}} H$ or $\Delta_{\mathrm{r}} S$ terms that determine the exergonicity of the reaction? Hint. In the $\mathrm{MgATP}{ }^{2-}$ complex, the $\mathrm{Mg}^{2+}$ ion and ATP ${ }^{4-}$ anion form two bonds: one that involves a negatively charged oxygen belonging to the terminal phosphate group of ATP ${ }^{4-}$ and another that involves a negatively charged oxygen belonging to the phosphate group adjacent to the terminal phosphate group of ATP ${ }^{4-}$.
6.8 To get a sense of the effect of cellular conditions on the ability of ATP to drive biochemical processes, compare the standard Gibbs energy of hydrolysis of ATP to ADP with the reaction Gibbs energy in an environment at $37^{\circ} \mathrm{C}$ in which $\mathrm{pH}=7.0$ and the ATP, ADP, and $\mathrm{P}_{\mathrm{i}}^{-}$concentrations are all 1.0 mmol $\mathrm{dm}^{-3}$.
6.9 Under biochemical standard conditions, aerobic respiration produces approximately 38 molecules of ATP per molecule of glucose that is completely oxidized. (a) What is the percentage efficiency of aerobic respiration under biochemical standard conditions? (b) The following conditions are more likely to be observed in a living cell: $p_{\mathrm{CO}_{2}}=5.3 \times 10^{-2} \mathrm{~atm}, p_{\mathrm{O}_{2}}=0.132 \mathrm{~atm}$, [glucose] $=5.6 \mathrm{pmol} \mathrm{dm}{ }^{-3}$, [ATP ] $=[\mathrm{ADP}]=\left[\mathrm{P}_{\mathrm{i}}\right]=0.10 \mathrm{mmol} \mathrm{dm}^{-3}, \mathrm{pH}=7.4$, $T=310 \mathrm{~K}$. Assuming that activities can be replaced by the numerical values of molar concentrations, calculate the efficiency of aerobic respiration under these physiological conditions. (c) A typical diesel engine operates between $T_{\mathrm{c}}=873 \mathrm{~K}$ and $T_{\mathrm{h}}=1923 \mathrm{~K}$ with an efficiency that is approximately 75 per cent of the theoretical limit of $1-T_{\mathrm{c}} / T_{\mathrm{h}}$ (see Topic 3A). Compare the efficiency of a typical diesel engine with that of aerobic respiration under typical physiological conditions (see part b). Why is biological energy conversion more or less efficient than energy conversion in a diesel engine?
6.10 In anaerobic bacteria, the source of carbon may be a molecule other than glucose and the final electron acceptor is some molecule other than $\mathrm{O}_{2}$. Could a bacterium evolve to use the ethanol/nitrate pair instead of the glucose/ $\mathrm{O}_{2}$ pair as a source of metabolic energy?
6.11 The standard potentials of proteins are not commonly measured by the methods described in this chapter because proteins often lose their native structure and function when they react on the surfaces of electrodes. In an alternative method, the oxidized protein is allowed to react with an appropriate electron donor in solution. The standard potential of the protein is then determined from the Nernst equation, the equilibrium concentrations of all species in solution, and the known standard potential of the electron donor. We illustrate this method with the protein cytochrome $c$. The oneelectron reaction between cytochrome $c$, cyt, and 2,6-dichloroindophenol, D, can be followed spectrophotometrically because each of the four species in solution has a distinct absorption spectrum. We write the reaction as $\mathrm{cyt}_{\mathrm{ox}}+\mathrm{D}_{\mathrm{red}} \rightleftharpoons \mathrm{cyt}_{\mathrm{red}}+\mathrm{D}_{\mathrm{ox}}$, where the subscripts 'ox' and 'red' refer to oxidized and reduced states, respectively. (a) Consider $E_{\mathrm{cyt}}^{\ominus}$ and $E_{\mathrm{D}}^{\ominus}$ to be the standard potentials of cytochrome $c$ and D , respectively. Show that, at equilibrium, a plot of $\ln \left(\left[\mathrm{D}_{\text {ox }}\right]_{\text {eq }} /\left[\mathrm{D}_{\text {red }}\right]_{\text {eq }}\right)$ versus $\ln \left(\left[\mathrm{cyt}_{\text {ox }}\right]_{\text {eq }} /\left[\mathrm{cyt}_{\text {red }}\right]_{\text {eq }}\right)$ is linear with slope of 1 and $y$-intercept $F\left(E_{\mathrm{cyt}}^{\ominus}-E_{\mathrm{D}}^{\ominus}\right) / R T$, where equilibrium activities are replaced by the numerical values of equilibrium molar concentrations. (b) The following data were obtained for the reaction between oxidized cytochrome $c$ and reduced D in a pH 6.5 buffer at 298 K . The ratios $\left[\mathrm{D}_{\text {ox }}\right]_{\text {eq }} /\left[\mathrm{D}_{\text {red }}\right]_{\text {eq }}$ and $\left[\mathrm{cyt}_{\text {ox }}\right]_{\text {eq }} /\left[\mathrm{cyt}_{\text {red }}\right]_{\text {eq }}$ were adjusted by titrating a solution containing oxidized cytochrome $c$ and reduced D with a solution of sodium ascorbate, which is a strong reductant. From the data and the standard potential of D of 0.237 V , determine the standard potential cytochrome $c$ at pH 6.5 and 298 K .

| $\left[\mathrm{D}_{\text {ox }}\right]_{\text {eq }} /\left[\mathrm{D}_{\text {red }}\right]_{\text {eq }}$ | 0.00279 | 0.00843 | 0.0257 | 0.0497 | 0.0748 | 0.238 | 0.534 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\left[\mathrm{cyt}_{\text {ox }}\right]_{\text {eq }} /\left[\mathrm{cyt}_{\text {red }}\right]_{\text {eq }}$ | 0.0106 | 0.0230 | 0.0894 | 0.197 | 0.335 | 0.809 | 1.39 |

6.12 ${ }^{\ddagger}$ The dimerization of ClO in the Antarctic winter stratosphere is believed to play an important part in that region's severe seasonal depletion of ozone. The following equilibrium constants are based on measurements on the reaction $2 \mathrm{ClO}(\mathrm{g}) \rightarrow(\mathrm{ClO})_{2}(\mathrm{~g})$.

| $T / \mathrm{K}$ | 233 | 248 | 258 | 268 | 273 | 280 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $K$ | $4.13 \times 10^{8}$ | $5.00 \times 10^{7}$ | $1.45 \times 10^{7}$ | $5.37 \times 10^{6}$ | $3.20 \times 10^{6}$ | $9.62 \times 10^{5}$ |
| $T / \mathrm{K}$ | 288 | 295 | 303 |  |  |  |
| $K$ | $4.28 \times 10^{5}$ | $1.67 \times 10^{5}$ | $6.02 \times 10^{4}$ |  |  |  |

[^1]$6.13^{\ddagger}$ Suppose that an iron catalyst at a particular manufacturing plant produces ammonia in the most cost-effective manner at $450^{\circ} \mathrm{C}$ when the pressure is such that $\Delta_{\mathrm{r}} G$ for the reaction $\frac{1}{2} \mathrm{~N}_{2}(\mathrm{~g})+\frac{3}{2} \mathrm{H}_{2}(\mathrm{~g}) \rightarrow \mathrm{NH}_{3}(\mathrm{~g})$ is equal to $-500 \mathrm{~J} \mathrm{~mol}^{-1}$. (a) What pressure is needed? (b) Now suppose that a new catalyst is developed that is most cost-effective at $400^{\circ} \mathrm{C}$ when the pressure gives the same value of $\Delta_{\mathrm{r}} G$. What pressure is needed when the new
catalyst is used? What are the advantages of the new catalyst? Assume that (i) all gases are perfect gases or that (ii) all gases are van der Waals gases. Isotherms of $\Delta_{\mathrm{r}} G(T, p)$ in the pressure range $100 \mathrm{~atm} \leq p \leq 400 \mathrm{~atm}$ are needed to derive the answer. (c) Do the isotherms you plotted confirm Le Chatelier's principle concerning the response of equilibrium changes in temperature and pressure?


[^0]:    * More values are given in the Resource section.

[^1]:    (a) Derive the values of $\Delta_{\mathrm{r}} H^{\ominus}$ and $\Delta_{\mathrm{r}} S^{\ominus}$ for this reaction. (b) Compute the standard enthalpy of formation and the standard molar entropy of $(\mathrm{ClO})_{2}$ given $\Delta_{\mathrm{r}} H^{\ominus}(\mathrm{ClO}, \mathrm{g})=+101.8 \mathrm{~kJ} \mathrm{~mol}^{-1}$ and $S_{\mathrm{m}}^{\ominus}(\mathrm{ClO}, \mathrm{g})=266.6 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$.

