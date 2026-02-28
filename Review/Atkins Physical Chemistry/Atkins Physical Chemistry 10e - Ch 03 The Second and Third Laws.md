## CHAPTER 3

## The Second and Third Laws

Some things happen naturally，some things don＇t．Some aspect of the world determines the spontaneous direction of change，the direction of change that does not require work to bring it about．An important point，though，is that throughout this text＇spontaneous＇must be interpreted as a natural tendency that may or may not be realized in practice． Thermodynamics is silent on the rate at which a spontaneous change in fact occurs，and some spontaneous processes（such as the conversion of diamond to graphite）may be so slow that the tendency is never realized in practice whereas others （such as the expansion of a gas into a vacuum）are almost instantaneous．

## 3A Entropy

The direction of change is related to the distribution of energy and matter，and spontaneous changes are always accompanied by a dispersal of energy or matter．To quantify this concept we introduce the property called＇entropy＇，which is central to the formulation of the＇Second Law of thermodynamics＇．That law governs all spontaneous change．

## 3B The measurement of entropy

To make the Second Law quantitative，it is necessary to meas－ ure the entropy of a substance．We see that measurement，per－ haps with calorimetric methods，of the energy transferred as heat during a physical process or chemical reaction leads to determination of the entropy change and，consequently，the direction of spontaneous change．The discussion in this Topic also leads to the＇Third Law of thermodynamics＇，which helps us to understand the properties of matter at very low tempera－ tures and to set up an absolute measure of the entropy of a substance．

## 3C Concentrating on the system

One problem with dealing with the entropy is that it requires separate calculations of the changes taking place in the system and the surroundings．Providing we are willing to impose cer－ tain restrictions on the system，that problem can be overcome by introducing the＇Gibbs energy＇．Indeed，most thermody－ namic calculations in chemistry focus on the change in Gibbs energy，not the direct measurement of the entropy change．

## 3D Combining the First and Second Laws

Finally，we bring the First and Second Laws together and begin to see the considerable power of thermodynamics for account－ ing for the properties of matter．

## What is the impact of this material？

The Second Law is at the heart of the operation of engines of all types，including devices resembling engines that are used to cool objects．See Impact I3．1 for an application to the tech－ nology of refrigeration．Entropy considerations are also impor－ tant in modern electronic materials for it permits a quantitative discussion of the concentration of impurities．See Impact I3．2 for a note about how measurement of the entropy at low tem－ peratures gives insight into the purity of materials used as superconductors．

To read more about the impact of this material，scan the QR code，or go to bcs．whfreeman．com／webpub／chemistry／ pchem10e／impact／pchem－3－1．html

## 3A Entropy

## Contents

3A. 1 The Second Law 113
3A. 2 The definition of entropy 115
(a) The thermodynamic definition of entropy 115

Example 3A. 1 Calculating the entropy change for the isothermal expansion of a perfect gas 115
Brief illustration 3A. 1 The entropy change of the surroundings 116
(b) The statistical definition of entropy 116

Brief illustration 3A. 2 The Boltzmann formula 117
3A. 3 The entropy as a state function 117
(a) The Carnot cycle 118

Brief illustration 3A. 3 The Carnot cycle 118
Brief illustration 3A.4 Thermal efficiency 119
(b) The thermodynamic temperature 120

Brief illustration 3A. 5 The thermodynamic temperature 120
(c) The Clausius inequality 120

Brief illustration 3A.6 The Clausius inequality 121
3A.4 Entropy changes accompanying specific processes 121
(a) Expansion 121

Brief illustration 3A. 7 Entropy of expansion 122
(b) Phase transitions 122

Brief illustration 3A. 8 Trouton's rule 123
(c) Heating 123

Brief illustration 3A. 9 Entropy change on heating 123
(d) Composite processes 124

Example 3A. 2 Calculating the entropy change for a composite process 124
Checklist of concepts 124
Checklist of equations 125

Why do you need to know this material?
Entropy is the concept on which almost all applications of thermodynamics in chemistry are based: it explains why some reactions take place and others do not.

What is the key idea?
The change in entropy of a system can be calculated from the heat transferred to it reversibly.

## What do you need to know already?

You need to be familiar with the First-Law concepts of work, heat, and internal energy (Topic 2A). The Topic draws on the expression for work of expansion of a perfect gas (Topic 2A) and on the changes in volume and temperature that accompany the reversible adiabatic expansion of a perfect gas (Topic 2D).

What determines the direction of spontaneous change? It is not the total energy of the isolated system. The First Law of thermodynamics states that energy is conserved in any process, and we cannot disregard that law now and say that everything tends towards a state of lower energy. When a change occurs, the total energy of an isolated system remains constant but it is parcelled out in different ways. Can it be, therefore, that the direction of change is related to the distribution of energy? We shall see that this idea is the key, and that spontaneous changes are always accompanied by a dispersal of energy or matter.

## 3A. 1 The Second Law

We can begin to understand the role of the dispersal of energy and matter by thinking about a ball (the system) bouncing on a floor (the surroundings). The ball does not rise as high after each bounce because there are inelastic losses in the materials of the ball and floor. The kinetic energy of the ball's overall motion is spread out into the energy of thermal motion of its particles and those of the floor that it hits. The direction of spontaneous change is towards a state in which the ball is at rest with all its energy dispersed into disorderly thermal motion of molecules in the air and of the atoms of the virtually infinite floor (Fig. 3A.1).

A ball resting on a warm floor has never been observed to start bouncing. For bouncing to begin, something rather special would need to happen. In the first place, some of the thermal motion of the atoms in the floor would have to accumulate in a single, small object, the ball. This accumulation requires a spontaneous localization of energy from the myriad vibrations of the atoms of the floor into the much smaller number of atoms that constitute the ball (Fig. 3A.2). Furthermore, whereas the thermal motion is random, for the ball to move upwards its

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-03.jpg?height=459&width=573&top_left_y=316&top_left_x=391)
Figure 3A. 1 The direction of spontaneous change for a ball bouncing on a floor. On each bounce some of its energy is degraded into the thermal motion of the atoms of the floor, and that energy disperses. The reverse has never been observed to take place on a macroscopic scale.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-03.jpg?height=472&width=625&top_left_y=1066&top_left_x=366)
Figure 3A. 2 The molecular interpretation of the irreversibility expressed by the Second Law. (a) A ball resting on a warm surface; the atoms are undergoing thermal motion (vibration, in this instance), as indicated by the arrows. (b) For the ball to fly upwards, some of the random vibrational motion would have to change into coordinated, directed motion. Such a conversion is highly improbable.

atoms must all move in the same direction. The localization of random, disorderly motion as concerted, ordered motion is so unlikely that we can dismiss it as virtually impossible. ${ }^{1}$

We appear to have found the signpost of spontaneous change: we look for the direction of change that leads to dispersal of the total energy of the isolated system. This principle accounts for the direction of change of the bouncing ball, because its energy is spread out as thermal motion of the atoms of the floor. The reverse process is not spontaneous because it is highly improbable that energy will become localized, leading to uniform motion of the ball's atoms.

Matter also has a tendency to disperse in disorder. A gas does not contract spontaneously because to do so the random motion of its molecules, which spreads out the distribution of

[^0]molecules throughout the container, would have to take them all into the same region of the container. The opposite change, spontaneous expansion, is a natural consequence of matter becoming more dispersed as the gas molecules occupy a larger volume.

The recognition of two classes of process, spontaneous and non-spontaneous, is summarized by the Second Law of thermodynamics. This law may be expressed in a variety of equivalent ways. One statement was formulated by Kelvin:

No process is possible in which the sole result is the absorption of heat from a reservoir and its complete conversion into work.

For example, it has proved impossible to construct an engine like that shown in Fig. 3A.3, in which heat is drawn from a hot reservoir and completely converted into work. All real heat engines have both a hot source and a cold sink; some energy is always discarded into the cold sink as heat and not converted into work. The Kelvin statement is a generalization of the everyday observation that we have already discussed, that a ball at rest on a surface has never been observed to leap spontaneously upwards. An upward leap of the ball would be equivalent to the conversion of heat from the surface into work. Another statement of the Second Law is due to Rudolf Clausius (Fig. 3A.4):

Heat does not flow spontaneously from a cool body to a hotter body.

To achieve the transfer of heat to a hotter body, it is necessary to do work on the system, as in a refrigerator.

These two empirical observations turn out to be aspects of a single statement in which the Second Law is expressed in terms of a new state function, the entropy, $S$. We shall see that the entropy (which we shall define shortly, but is a measure of the energy and matter dispersed in a process) lets us assess whether one state is accessible from another by a spontaneous change:

The entropy of an isolated system increases in the course of a spontaneous change: $\Delta S_{\text {tot }}>0$

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-03.jpg?height=352&width=575&top_left_y=2077&top_left_x=1316)
Figure 3A. 3 The Kelvin statement of the Second Law denies the possibility of the process illustrated here, in which heat is changed completely into work, there being no other change. The process is not in conflict with the First Law because energy is conserved.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-04.jpg?height=539&width=258&top_left_y=314&top_left_x=592)
Figure 3A. 4 The Clausius statement of the Second Law denies the possibility of the process illustrated here, in which energy as heat migrates from a cool source to a hot sink, there being no other change. The process is not in conflict with the First Law because energy is conserved.

where $S_{\text {tot }}$ is the total entropy of the system and its surroundings. Thermodynamically irreversible processes (like cooling to the temperature of the surroundings and the free expansion of gases) are spontaneous processes, and hence must be accompanied by an increase in total entropy.

In summary, the First Law uses the internal energy to identify permissible changes; the Second Law uses the entropy to identify the spontaneous changes among those permissible changes.

## 3А. 2 The definition of entropy

To make progress, and to turn the Second Law into a quantitatively useful expression, we need to define and then calculate the entropy change accompanying various processes. There are two approaches, one classical and one molecular. They turn out to be equivalent, but each one enriches the other.

## (a) The thermodynamic definition of entropy

The thermodynamic definition of entropy concentrates on the change in entropy, $\mathrm{d} S$, that occurs as a result of a physical or chemical change (in general, as a result of a 'process'). The definition is motivated by the idea that a change in the extent to which energy is dispersed depends on how much energy is transferred as heat. As explained in Topic 2A, heat stimulates random motion in the surroundings. On the other hand, work stimulates uniform motion of atoms in the surroundings and so does not change their entropy.

The thermodynamic definition of entropy is based on the expression

$$
\mathrm{d} S=\frac{\mathrm{d} q_{\mathrm{rev}}}{T}
$$

Definition Entropy change
(3A.1)

For a measurable change between two states i and f,

$$
\Delta S=\int_{\mathrm{i}}^{\mathrm{f}} \frac{\mathrm{~d} q_{\mathrm{rev}}}{T}
$$

That is, to calculate the difference in entropy between any two states of a system, we find a reversible path between them, and integrate the energy supplied as heat at each stage of the path divided by the temperature at which heating occurs.

A note on good practice According to eqn 3A.1, when the energy transferred as heat is expressed in joules and the temperature is in kelvins, the units of entropy are joules per kelvin ( $\mathrm{JK}^{-1}$ ). Entropy is an extensive property. Molar entropy, the entropy divided by the amount of substance, $S_{\mathrm{m}}=S / n$, is expressed in joules per kelvin per mole $\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$. The units of entropy are the same as those of the gas constant, $R$, and molar heat capacities. Molar entropy is an intensive property.

Example 3A. 1 Calculating the entropy change for the isothermal expansion of a perfect gas

Calculate the entropy change of a sample of perfect gas when it expands isothermally from a volume $V_{\mathrm{i}}$ to a volume $V_{\mathrm{f}}$.

Method The definition of entropy instructs us to find the energy supplied as heat for a reversible path between the stated initial and final states regardless of the actual manner in which the process takes place. A simplification is that the expansion is isothermal, so the temperature is a constant and may be taken outside the integral in eqn 3A.2. The energy absorbed as heat during a reversible isothermal expansion of a perfect gas can be calculated from $\Delta U=q+w$ and $\Delta U=0$, which implies that $q=-w$ in general and therefore that $q_{\text {rev }}=-w_{\text {rev }}$ for a reversible change. The work of reversible isothermal expansion is calculated in Topic 2 A . The change in molar entropy is calculated from $\Delta S_{\mathrm{m}}=\Delta S / n$.

Answer Because the temperature is constant, eqn 3A. 2 becomes

$$
\Delta S=\frac{1}{T} \int_{\mathrm{i}}^{\mathrm{f}} \mathrm{~d} q_{\mathrm{rev}}=\frac{q_{\mathrm{rev}}}{T}
$$

From Topic 2A we know that

$$
q_{\mathrm{rev}}=-w_{\mathrm{rev}}=n R T \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}
$$

It follows that

$$
\Delta S=n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}} \quad \text { and } \quad \Delta S_{\mathrm{m}}=R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}
$$

Self-test 3A.1 Calculate the change in entropy when the pressure of a fixed amount of perfect gas is changed isothermally from $p_{\mathrm{i}}$ to $p_{\mathrm{f}}$. What is this change due to?

Answer: $\Delta S=n R \ln \left(p_{\mathrm{i}} / p_{\mathrm{f}}\right)$; the change in volume when the gas is compressed or expands

The definition in eqn 3A. 1 is used to formulate an expression for the change in entropy of the surroundings, $\Delta S_{\text {sur }}$. Consider an infinitesimal transfer of heat $\mathrm{d} q_{\text {sur }}$ to the surroundings. The surroundings consist of a reservoir of constant volume, so the energy supplied to them by heating can be identified with the change in the internal energy of the surroundings, $\mathrm{d} U_{\text {sur. }}{ }^{2}$ The internal energy is a state function, and $\mathrm{d} U_{\text {sur }}$ is an exact differential. These properties imply that $\mathrm{d} U_{\text {sur }}$ is independent of how the change is brought about and in particular is independent of whether the process is reversible or irreversible. The same remarks therefore apply to $\mathrm{d} q_{\text {sur }}$, to which $\mathrm{d} U_{\text {sur }}$ is equal. Therefore, we can adapt the definition in eqn 3A.1, delete the constraint 'reversible', and write

$$
\mathrm{d} S=\frac{\mathrm{d} q_{\mathrm{rev}, \mathrm{sur}}}{T_{\mathrm{sur}}}=\frac{\mathrm{d} q_{\mathrm{sur}}}{T_{\mathrm{sur}}} \quad \text { Entropy change of the surroundings }
$$

Furthermore, because the temperature of the surroundings is constant whatever the change, for a measurable change

$$
\Delta S_{\mathrm{sur}}=\frac{q_{\mathrm{sur}}}{T_{\mathrm{sur}}}
$$

That is, regardless of how the change is brought about in the system, reversibly or irreversibly, we can calculate the change of entropy of the surroundings by dividing the heat transferred by the temperature at which the transfer takes place.

Equation 3A. 3 makes it very simple to calculate the changes in entropy of the surroundings that accompany any process. For instance, for any adiabatic change, $q_{\text {sur }}=0$, so

$$
\Delta S_{\mathrm{sur}}=0
$$

Adiabatic change
(3A.4)
This expression is true however the change takes place, reversibly or irreversibly, provided no local hot spots are formed in the surroundings. That is, it is true so long as the surroundings remain in internal equilibrium. If hot spots do form, then the localized energy may subsequently disperse spontaneously and hence generate more entropy.

## Brief illustration 3A. 1 The entropy change of the surroundings

To calculate the entropy change in the surroundings when $1.00 \mathrm{~mol} \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ is formed from its elements under standard conditions at 298 K , we use $\Delta H^{\ominus}=-286 \mathrm{~kJ}$ from Table 2C.2. The energy released as heat is supplied to the surroundings, now regarded as being at constant pressure, so $q_{\text {sur }}=+286 \mathrm{~kJ}$. Therefore,

$$
\Delta S_{\text {sur }}=\frac{2.86 \times 10^{5} \mathrm{~J} \mathrm{~mol}^{-1}}{298 \mathrm{~K}}=+960 \mathrm{JK}^{-1}
$$

[^1]This strongly exothermic reaction results in an increase in the entropy of the surroundings as energy is released as heat into them.

Self-test 3A.2 Calculate the entropy change in the surroundings when $1.00 \mathrm{~mol} \mathrm{~N}_{2} \mathrm{O}_{4}(\mathrm{~g})$ is formed from $2.00 \mathrm{~mol} \mathrm{NO}_{2}(\mathrm{~g})$ under standard conditions at 298 K .

Answer: $-192 \mathrm{JK}^{-1}$

We are now in a position to see how the definition of entropy is consistent with Kelvin's and Clausius's statements of the Second Law. In the arrangement shown in Fig. 3A.3, the entropy of the hot source is reduced as energy leaves it as heat, but no other change in entropy occurs (the transfer of energy as work does not result in the production of entropy); consequently the arrangement does not produce work. In Clausius version, the entropy of the cold source in Fig 3A. 4 decreases when a certain quantity of energy leaves it as heat, but when that heat enters the hot sink the rise in entropy is not as great. Therefore, overall there is a decrease in entropy: the process is not spontaneous.

## (b) The statistical definition of entropy

The entry point into the molecular interpretation of the Second Law of thermodynamics is Boltzmann's insight, first mentioned in Foundations B, that an atom or molecule can possess only certain values of the energy, called its 'energy levels'. The continuous thermal agitation that molecules experience at $T>0$ ensures that they are distributed over the available energy levels. Boltzmann also made the link between the distribution of molecules over energy levels and the entropy. He proposed that the entropy of a system is given by

$$
S=k \ln \mathcal{W} \quad \text { Boltzmann formula for the entropy }
$$

where $k=1.381 \times 10^{-23} \mathrm{~J}^{-1}$ and $\mathcal{W}$ is the number of microstates, the number of ways in which the molecules of a system can be arranged while keeping the total energy constant. Each microstate lasts only for an instant and corresponds to a certain distribution of molecules over the available energy levels. When we measure the properties of a system, we are measuring an average taken over the many microstates the system can occupy under the conditions of the experiment. The concept of the number of microstates makes quantitative the ill-defined qualitative concepts of 'disorder' and 'the dispersal of matter and energy' that are used widely to introduce the concept of entropy: a more disorderly distribution of matter and a greater dispersal of energy corresponds to a greater number of microstates associated with the same total energy. This point is discussed in much greater detail in Topic 15E.

Equation 3A. 5 is known as the Boltzmann formula and the entropy calculated from it is sometimes called the statistical
entropy. We see that if $\mathcal{W}=1$, which corresponds to one microstate (only one way of achieving a given energy, all molecules in exactly the same state), then $S=0$ because $\ln 1=0$. However, if the system can exist in more than one microstate, then $\mathscr{W}>1$ and $S>0$. If the molecules in the system have access to a greater number of energy levels, then there may be more ways of achieving a given total energy; that is, there are more microstates for a given total energy, $\mathcal{W}$ is greater, and the entropy is greater than when fewer states are accessible. Therefore, the statistical view of entropy summarized by the Boltzmann formula is consistent with our previous statement that the entropy is related to the dispersal of energy and matter. In particular, for a gas of particles in a container, the energy levels become closer together as the container expands (Fig. 3A.5; this is a conclusion from quantum theory that is verified in Topic 8A). As a result, more microstates become possible, $W$ increases, and the entropy increases, exactly as we inferred from the thermodynamic definition of entropy.

## Brief illustration 3A. 2 The Boltzmann formula

Suppose that each diatomic molecule in a solid sample can be arranged in either of two orientations and that there are $N=6.022 \times 10^{23}$ molecules in the sample (that is, 1 mol of molecules). Then $\mathcal{W}=2^{N}$ and the entropy of the sample is

$$
\begin{aligned}
S & =k \ln 2^{N}=N k \ln 2=\left(6.022 \times 10^{23}\right) \times\left(1.381 \times 10^{-23} \mathrm{JK}^{-1}\right) \ln 2 \\
& =5.76 \mathrm{JK}^{-1}
\end{aligned}
$$

Self-test 3A. 3 What is the molar entropy of a similar system in which each molecule can be arranged in four different orientations?

Answer: $11.5 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$

The molecular interpretation of entropy advanced by Boltzmann also suggests the thermodynamic definition given

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-06.jpg?height=441&width=603&top_left_y=1986&top_left_x=416)
Figure 3A. 5 When a box expands, the energy levels move closer together and more become accessible to the molecules. As a result the number of ways of achieving the same energy (the value of $\mathscr{W}$ ) increases, and so therefore does the entropy.

by eqn 3A.1. To appreciate this point, consider that molecules in a system at high temperature can occupy a large number of the available energy levels, so a small additional transfer of energy as heat will lead to a relatively small change in the number of accessible energy levels. Consequently, the number of microstates does not increase appreciably and neither does the entropy of the system. In contrast, the molecules in a system at low temperature have access to far fewer energy levels (at $T=0$, only the lowest level is accessible), and the transfer of the same quantity of energy by heating will increase the number of accessible energy levels and the number of microstates significantly. Hence, the change in entropy upon heating will be greater when the energy is transferred to a cold body than when it is transferred to a hot body. This argument suggests that the change in entropy for a given transfer of energy as heat should be greater at low temperatures than at high, as in eqn 3A.1.

## 3A.3 The entropy as a state function

Entropy is a state function. To prove this assertion, we need to show that the integral of $\mathrm{d} S$ is independent of path. To do so, it is sufficient to prove that the integral of eqn 3A. 1 around an arbitrary cycle is zero, for that guarantees that the entropy is the same at the initial and final states of the system regardless of the path taken between them (Fig. 3A.6). That is, we need to show that

$$
\oint \mathrm{d} S=\oint \frac{\mathrm{d} q_{\mathrm{rev}}}{T}=0
$$

where the symbol $\oint$ denotes integration around a closed path. There are three steps in the argument:

1. First, to show that eqn 3A. 6 is true for a special cycle (a 'Carnot cycle') involving a perfect gas.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-06.jpg?height=482&width=837&top_left_y=1977&top_left_x=1243)
Figure 3A. 6 In a thermodynamic cycle, the overall change in a state function (from the initial state to the final state and then back to the initial state again) is zero.

2. Then to show that the result is true whatever the working substance.
3. Finally, to show that the result is true for any cycle.

## (a) The Carnot cycle

A Carnot cycle, which is named after the French engineer Sadi Carnot, consists of four reversible stages (Fig. 3A.7):

1. Reversible isothermal expansion from A to B at $T_{\mathrm{h}}$; the entropy change is $q_{\mathrm{h}} / T_{\mathrm{h}}$, where $q_{\mathrm{h}}$ is the energy supplied to the system as heat from the hot source.
2. Reversible adiabatic expansion from B to C. No energy leaves the system as heat, so the change in entropy is zero. In the course of this expansion, the temperature falls from $T_{\mathrm{h}}$ to $T_{\mathrm{c}}$, the temperature of the cold sink.
3. Reversible isothermal compression from C to D at $T_{\mathrm{c}}$. Energy is released as heat to the cold sink; the change in entropy of the system is $q_{\mathrm{c}} / T_{\mathrm{c}}$; in this expression $q_{\mathrm{c}}$ is negative.
4. Reversible adiabatic compression from D to A. No energy enters the system as heat, so the change in entropy is zero. The temperature rises from $T_{\mathrm{c}}$ to $T_{\mathrm{h}}$.

The total change in entropy around the cycle is the sum of the changes in each of these four steps:

$$
\oint \mathrm{d} S=\frac{q_{\mathrm{h}}}{T_{\mathrm{h}}}+\frac{q_{\mathrm{c}}}{T_{\mathrm{c}}}
$$

However, we show in the following Justification that for a perfect gas

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-07.jpg?height=486&width=806&top_left_y=1813&top_left_x=277)
Figure 3A. 7 The basic structure of a Carnot cycle. In Step 1, there is isothermal reversible expansion at the temperature $T_{\mathrm{h}}$. Step 2 is a reversible adiabatic expansion in which the temperature falls from $T_{\mathrm{h}}$ to $T_{\mathrm{c}}$. In Step 3 there is an isothermal reversible compression at $T_{\mathrm{c}^{\prime}}$ and that isothermal step is followed by an adiabatic reversible compression, which restores the system to its initial state.

$$
\frac{q_{\mathrm{h}}}{q_{\mathrm{c}}}=-\frac{T_{\mathrm{h}}}{T_{\mathrm{c}}}
$$

Substitution of this relation into the preceding equation gives zero on the right, which is what we wanted to prove.

## Justification 3A. 1 Heating accompanying reversible adiabatic expansion

This Justification is based on two features of the cycle. One feature is that the two temperatures $T_{\mathrm{h}}$ and $T_{\mathrm{c}}$ in eqn 3A. 7 lie on the same adiabat in Fig. 3A.7. The second feature is that the energy transferred as heat during the two isothermal stages are

$$
q_{\mathrm{h}}=n R T_{\mathrm{h}} \ln \frac{V_{\mathrm{B}}}{V_{\mathrm{A}}} \quad q_{\mathrm{c}}=n R T_{\mathrm{c}} \ln \frac{V_{\mathrm{D}}}{V_{\mathrm{C}}}
$$

We now show that the two volume ratios are related in a very simple way. From the relation between temperature and volume for reversible adiabatic processes $\left(V T^{c}=\right.$ constant, Topic 2D):

$$
V_{\mathrm{A}} T_{\mathrm{h}}^{c}=V_{\mathrm{D}} T_{\mathrm{c}}^{c} \quad V_{\mathrm{C}} T_{\mathrm{c}}^{c}=V_{\mathrm{B}} T_{\mathrm{h}}^{\mathrm{c}}
$$

Multiplication of the first of these expressions by the second gives

$$
V_{\mathrm{A}} V_{\mathrm{C}} T_{\mathrm{h}}^{c} T_{\mathrm{c}}^{c}=V_{\mathrm{D}} V_{\mathrm{B}} T_{\mathrm{h}}^{c} T_{\mathrm{c}}^{c}
$$

which, on cancellation of the temperatures, simplifies to

$$
\frac{V_{\mathrm{D}}}{V_{\mathrm{C}}}=\frac{V_{\mathrm{A}}}{V_{\mathrm{B}}}
$$

With this relation established, we can write

$$
q_{\mathrm{c}}=n R T_{\mathrm{c}} \ln \frac{V_{\mathrm{D}}}{V_{\mathrm{C}}}=n R T_{\mathrm{c}} \ln \frac{V_{\mathrm{A}}}{V_{\mathrm{B}}}=-n R T_{\mathrm{c}} \ln \frac{V_{\mathrm{B}}}{V_{\mathrm{A}}}
$$

and therefore

$$
\frac{q_{\mathrm{h}}}{q_{\mathrm{c}}}=\frac{n R T_{\mathrm{h}} \ln \left(V_{\mathrm{B}} / V_{\mathrm{A}}\right)}{-n R T_{\mathrm{c}} \ln \left(V_{\mathrm{B}} / V_{\mathrm{A}}\right)}=-\frac{T_{\mathrm{h}}}{T_{\mathrm{c}}}
$$

as in eqn 3A.7. For clarification, note that $q_{\mathrm{h}}$ is negative (heat is withdrawn from the hot source) and $q_{\mathrm{c}}$ is positive (heat is deposited in the cold sink), so their ratio is negative.

## Brief illustration 3A. 3 The Carnot cycle

The Carnot cycle can be regarded as a representation of the changes taking place in an actual idealized engine, where heat is converted into work. (However, other cycles are closer approximations to real engines.) In an engine running in accord with the Carnot cycle, 100 J of energy is withdrawn
from the hot source $\left(q_{\mathrm{h}}=-100 \mathrm{~J}\right)$ at 500 K and some is used to do work, with the remainder deposited in the cold sink at 300 K . According to eqn 3A.7, the amount of heat deposited is

$$
q_{\mathrm{c}}=-q_{\mathrm{h}} \times \frac{T_{c}}{T_{\mathrm{h}}}=-(-100 \mathrm{~J}) \times \frac{300 \mathrm{~K}}{500 \mathrm{~K}}=+60 \mathrm{~J}
$$

That means that 40 J was used to do work.
Self-test 3A.4 How much work can be extracted when the temperature of the hot source is increased to 800 K ?

Answer: 62 J

In the second step we need to show that eqn 3A. 6 applies to any material, not just a perfect gas (which is why, in anticipation, we have not labelled it in blue). We begin this step of the argument by introducing the efficiency, $\eta$ (eta), of a heat engine:

$$
\eta=\frac{\text { work performed }}{\text { heat absorbed from hot source }}=\frac{|w|}{\left|q_{\mathrm{h}}\right|} \quad \begin{aligned}
& \text { Definition of } \\
& \text { efficiency }
\end{aligned}
$$

We are using modulus signs to avoid complications with signs: all efficiencies are positive numbers. The definition implies that the greater the work output for a given supply of heat from the hot reservoir, the greater is the efficiency of the engine. We can express the definition in terms of the heat transactions alone, because (as shown in Fig. 3A.8), the energy supplied as work by the engine is the difference between the energy supplied as heat by the hot reservoir and returned to the cold reservoir:

$$
\eta=\frac{\left|q_{\mathrm{h}}\right|-\left|q_{\mathrm{c}}\right|}{\left|q_{\mathrm{h}}\right|}=1-\frac{\left|q_{\mathrm{c}}\right|}{\left|q_{\mathrm{h}}\right|}
$$

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-08.jpg?height=550&width=365&top_left_y=1836&top_left_x=535)
Figure 3A. 8 Suppose an energy $q_{\mathrm{h}}$ (for example, 20 kJ ) is supplied to the engine and $q_{c}$ is lost from the engine (for example, $q_{c}=-15 \mathrm{~kJ}$ ) and discarded into the cold reservoir. The work done by the engine is equal to $q_{\mathrm{h}}+q_{\mathrm{c}}$ (for example, $20 \mathrm{~kJ}+(-15 \mathrm{~kJ})=5 \mathrm{~kJ})$. The efficiency is the work done divided by the energy supplied as heat from the hot source.

It then follows from eqn 3A. 7 written as $\left|q_{\mathrm{c}}\right| /\left|q_{\mathrm{h}}\right|=T_{\mathrm{c}} / T_{\mathrm{h}}$ (see the concluding remark in Justification 3A.1) that

$$
\eta=1-\frac{T_{\mathrm{c}}}{T_{\mathrm{h}}} \quad \text { Carnot efficiency }
$$

## Brief illustration 3A. 4 Thermal efficiency

A certain power station operates with superheated steam at $300^{\circ} \mathrm{C}\left(T_{\mathrm{h}}=573 \mathrm{~K}\right)$ and discharges the waste heat into the environment at $20^{\circ} \mathrm{C}\left(T_{\mathrm{c}}=293 \mathrm{~K}\right)$. The theoretical efficiency is therefore

$$
\eta=1-\frac{293 \mathrm{~K}}{573 \mathrm{~K}}=0.489, \text { or } 48.9 \text { per cent }
$$

In practice, there are other losses due to mechanical friction and the fact that the turbines do not operate reversibly.

Self-test 3A.5 At what temperature of the hot source would the theoretical efficiency reach 80 per cent?

Answer: 1465 K

Now we are ready to generalize this conclusion. The Second Law of thermodynamics implies that all reversible engines have the same efficiency regardless of their construction. To see the truth of this statement, suppose two reversible engines are coupled together and run between the same two reservoirs (Fig. 3A.9). The working substances and details of construction of the two engines are entirely arbitrary. Initially, suppose that engine $A$ is more efficient than engine $B$, and that we choose a setting of the controls that causes engine $B$ to acquire energy as heat $q_{\mathrm{c}}$ from the cold reservoir and to release a certain

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-08.jpg?height=571&width=846&top_left_y=1822&top_left_x=1225)
Figure 3A. 9 (a) The demonstration of the equivalence of the efficiencies of all reversible engines working between the same thermal reservoirs is based on the flow of energy represented in this diagram. (b) The net effect of the processes is the conversion of heat into work without there being a need for a cold sink: this is contrary to the Kelvin statement of the Second Law.

quantity of energy as heat into the hot reservoir. However, because engine A is more efficient than engine B , not all the work that A produces is needed for this process, and the difference can be used to do work. The net result is that the cold reservoir is unchanged, work has been done, and the hot reservoir has lost a certain amount of energy. This outcome is contrary to the Kelvin statement of the Second Law, because some heat has been converted directly into work. In molecular terms, the random thermal motion of the hot reservoir has been converted into ordered motion characteristic of work. Because the conclusion is contrary to experience, the initial assumption that engines A and B can have different efficiencies must be false. It follows that the relation between the heat transfers and the temperatures must also be independent of the working material, and therefore that eqn 3A. 10 is always true for any substance involved in a Carnot cycle.

For the final step in the argument, we note that any reversible cycle can be approximated as a collection of Carnot cycles and the integral around an arbitrary path is the sum of the integrals around each of the Carnot cycles (Fig. 3A.10). This approximation becomes exact as the individual cycles are allowed to become infinitesimal. The entropy change around each individual cycle is zero (as demonstrated above), so the sum of entropy changes for all the cycles is zero. However, in the sum, the entropy change along any individual path is cancelled by the entropy change along the path it shares with the neighbouring cycle. Therefore, all the entropy changes cancel except for those along the perimeter of the overall cycle. That is,

$$
\sum_{\text {all }} \frac{q_{\mathrm{rev}}}{T}=\sum_{\text {perimeter }} \frac{q_{\mathrm{rev}}}{T}=0
$$

In the limit of infinitesimal cycles, the non-cancelling edges of the Carnot cycles match the overall cycle exactly, and the sum

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-09.jpg?height=470&width=755&top_left_y=1870&top_left_x=300)
Figure 3A. 10 A general cycle can be divided into small Carnot cycles. The match is exact in the limit of infinitesimally small cycles. Paths cancel in the interior of the collection, and only the perimeter, an increasingly good approximation to the true cycle as the number of cycles increases, survives. Because the entropy change around every individual cycle is zero, the integral of the entropy around the perimeter is zero too.

becomes an integral. Equation 3A. 6 then follows immediately. This result implies that $\mathrm{d} S$ is an exact differential and therefore that $S$ is a state function.

## (b) The thermodynamic temperature

Suppose we have an engine that is working reversibly between a hot source at a temperature $T_{\mathrm{h}}$ and a cold sink at a temperature $T$, then we know from eqn 3A. 10 that

$$
T=(1-\eta) T_{\mathrm{h}}
$$

This expression enabled Kelvin to define the thermodynamic temperature scale in terms of the efficiency of a heat engine: we construct an engine in which the hot source is at a known temperature and the cold sink is the object of interest. The temperature of the latter can then be inferred from the measured efficiency of the engine. The Kelvin scale (which is a special case of the thermodynamic temperature scale) is currently defined by using water at its triple point as the notional hot source and defining that temperature as 273.16 K exactly. ${ }^{3}$

## Brief illustration 3A.5 The thermodynamic temperature

A heat engine was constructed that used a hot source at the triple point temperature of water and used as a cold source a cooled liquid. The efficiency of the engine was measured as 0.400 . The temperature of the liquid is therefore

$$
T=(1-0.400) \times(273.16 \mathrm{~K})=164 \mathrm{~K}
$$

Self-test 3A. 6 What temperature would be reported for the hot source if a thermodynamic efficiency of 0.500 was measured when the cold sink was at 273.16 K ?

Answer: 546 K

## (c) The Clausius inequality

We now show that the definition of entropy is consistent with the Second Law. To begin, we recall that more work is done when a change is reversible than when it is irreversible. That is, $\left|\mathrm{d} w_{\text {rev }}\right| \geq|\mathrm{d} w|$. Because $\mathrm{d} w$ and $\mathrm{d} w_{\text {rev }}$ are negative when energy leaves the system as work, this expression is the same as $-\mathrm{d} w_{\text {rev }} \geq-\mathrm{d} w$, and hence $\mathrm{d} w-\mathrm{d} w_{\text {rev }} \geq 0$. Because the internal energy is a state function, its change is the same for irreversible and reversible paths between the same two states, so we can also write:

$$
\mathrm{d} U=\mathrm{d} q+\mathrm{d} w=\mathrm{d} q_{\mathrm{rev}}+\mathrm{d} w_{\mathrm{rev}}
$$

[^2]It follows that $\mathrm{d} q_{\text {rev }}-\mathrm{d} q=\mathrm{d} w-\mathrm{d} w_{\text {rev }} \geq 0$, or $\mathrm{d} q_{\text {rev }} \geq \mathrm{d} q$, and therefore that $\mathrm{d} q_{\text {rev }} / T \geq \mathrm{d} q / T$. Now we use the thermodynamic definition of the entropy (eqn 3A.1; $\mathrm{d} S=\mathrm{d} q_{\text {rev }} / T$ ) to write

$$
\mathrm{d} S \geq \frac{\mathrm{d} q}{T}
$$

Clausius inequality

This expression is the Clausius inequality. It proves to be of great importance for the discussion of the spontaneity of chemical reactions, as is shown in Topic 3C.

## Brief illustration 3A. 6 The Clausius inequality

Consider the transfer of energy as heat from one system-the hot source-at a temperature $T_{\mathrm{h}}$ to another system-the cold sink-at a temperature $T_{\mathrm{c}}$ (Fig. 3A.11).

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-10.jpg?height=513&width=520&top_left_y=993&top_left_x=460)
Figure 3A. 11 When energy leaves a hot reservoir as heat,

the entropy of the reservoir decreases. When the same quantity of energy enters a cooler reservoir, the entropy increases by a larger amount. Hence, overall there is an increase in entropy and the process is spontaneous. Relative changes in entropy are indicated by the sizes of the arrows.

When $|\mathrm{d} q|$ leaves the hot source (so $\mathrm{d} q_{\mathrm{h}}<0$ ), the Clausius inequality implies that $\mathrm{d} S \geq \mathrm{d} q_{\mathrm{h}} / T_{\mathrm{h}}$. When $|\mathrm{d} q|$ enters the cold sink the Clausius inequality implies that $\mathrm{d} S \geq \mathrm{d} q_{\mathrm{c}} / T_{\mathrm{c}}$ (with $\mathrm{d} q_{\mathrm{c}}>0$ ). Overall, therefore,

$$
\mathrm{d} S \geq \frac{\mathrm{d} q_{\mathrm{h}}}{T_{\mathrm{h}}}+\frac{\mathrm{d} q_{\mathrm{c}}}{T_{\mathrm{c}}}
$$

However, $\mathrm{d} q_{\mathrm{h}}=-\mathrm{d} q_{\mathrm{c}}$, so

$$
\mathrm{d} S \geq-\frac{\mathrm{d} q_{\mathrm{c}}}{T_{\mathrm{h}}}+\frac{\mathrm{d} q_{\mathrm{c}}}{T_{\mathrm{c}}}=\left(\frac{1}{T_{\mathrm{c}}}-\frac{1}{T_{\mathrm{h}}}\right) \mathrm{d} q_{\mathrm{c}}
$$

which is positive (because $\mathrm{d} q_{\mathrm{c}}>0$ and $T_{\mathrm{h}} \geq T_{\mathrm{c}}$ ). Hence, cooling (the transfer of heat from hot to cold) is spontaneous, as we know from experience.

Self-test 3A.7 What is the change in entropy when 1.0 J of energy as heat transfers from a large block of iron at $30^{\circ} \mathrm{C}$ to another large block at $20^{\circ} \mathrm{C}$ ?

Answer: $+0.1 \mathrm{~mJ} \mathrm{~K}^{-1}$

Entropy change for the isothermal expansion of a perfect gas

We now suppose that the system is isolated from its surroundings, so that $\mathrm{d} q=0$. The Clausius inequality implies that

$$
\mathrm{d} S \geq 0
$$

and we conclude that in an isolated system the entropy cannot decrease when a spontaneous change occurs. This statement captures the content of the Second Law.

## 3A.4 Entropy changes accompanying specific processes

We now see how to calculate the entropy changes that accompany a variety of basic processes.

## (a) Expansion

We established in Example 3A. 1 that the change in entropy of a perfect gas that expands isothermally from $V_{\mathrm{i}}$ to $V_{\mathrm{f}}$ is

$$
\Delta S=n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}
$$

(3A.14)

Because $S$ is a state function, the value of $\Delta S$ of the system is independent of the path between the initial and final states, so this expression applies whether the change of state occurs reversibly or irreversibly. The logarithmic dependence of entropy on volume is illustrated in Fig. 3A.12.

The total change in entropy, however, does depend on how the expansion takes place. For any process the energy lost as heat from the system is acquired by the surroundings, so $\mathrm{d} q_{\text {sur }}=-\mathrm{d} q$. For a reversible change we use the expression in Example 3A. 1 $\left(q_{\text {rev }}=n R T \ln \left(V_{\mathrm{f}} / V_{\mathrm{i}}\right)\right)$; consequently, from eqn 3A.3b

$$
\Delta S_{\mathrm{sur}}=\frac{q_{\mathrm{sur}}}{T}=-\frac{q_{\mathrm{rev}}}{T}=-n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}
$$

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-10.jpg?height=519&width=825&top_left_y=2054&top_left_x=1230)
Figure 3A. 12 The logarithmic increase in entropy of a perfect gas as it expands isothermally.

This change is the negative of the change in the system, so we can conclude that $\Delta S_{\text {tot }}=0$, which is what we should expect for a reversible process. If, on the other hand, the isothermal expansion occurs freely ( $w=0$ ), then $q=0$ (because $\Delta U=0$ ). Consequently, $\Delta S_{\text {sur }}=0$, and the total entropy change is given by eqn 3A. 17 itself:

$$
\Delta S_{\mathrm{tot}}=n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}
$$

In this case, $\Delta S_{\text {tot }}>0$, as we expect for an irreversible process.

## Brief illustration 3A. 7 Entropy of expansion

When the volume of any perfect gas is doubled at any constant temperature, $V_{\mathrm{f}} / V_{\mathrm{i}}=2$ and the change in molar entropy of the system is

$$
\Delta S_{\mathrm{m}}=\left(8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times \ln 2=+5.76 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
$$

If the change is carried out reversibly, the change in entropy of the surroundings is $-5.76 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ (the 'per mole' meaning per mole of gas molecules in the sample). The total change in entropy is 0 . If the expansion is free, the change in molar entropy of the gas is still $+5.76 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$, but that of the surroundings is 0 , and the total change is $+5.76 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$.

Self-test 3A.8 Calculate the change in entropy when a perfect gas expands isothermally to 10 times its initial volume (a) reversibly, (b) irreversibly against zero pressure.

$$
\begin{array}{r}
\text { Answer: (a) } \Delta S_{\mathrm{m}}=+19 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}, \Delta S_{\text {surr }}=-19 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}, \Delta S_{\mathrm{tot}}=0 ; \\
\text { (b) } \Delta S_{\mathrm{m}}=+19 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}, \Delta S_{\text {surr }}=0, \Delta S_{\mathrm{tot}}=+19 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}
\end{array}
$$

## (b) Phase transitions

The degree of dispersal of matter and energy changes when a substance freezes or boils as a result of changes in the order with which the molecules pack together and the extent to which the energy is localized or dispersed. Therefore, we should expect the transition to be accompanied by a change in entropy. For example, when a substance vaporizes, a compact condensed phase changes into a widely dispersed gas and we can expect the entropy of the substance to increase considerably. The entropy of a solid also increases when it melts to a liquid and when that liquid turns into a gas.

Consider a system and its surroundings at the normal transition temperature, $T_{\mathrm{trs}}$, the temperature at which two phases are in equilibrium at 1 atm . This temperature is $0^{\circ} \mathrm{C}(273 \mathrm{~K})$ for ice in equilibrium with liquid water at 1 atm , and $100^{\circ} \mathrm{C} (373 \mathrm{~K})$ for water in equilibrium with its vapour at 1 atm . At the transition temperature, any transfer of energy as heat between the system and its surroundings is reversible because the two phases in the system are in equilibrium. Because at
constant pressure $q=\Delta_{\text {trs }} H$, the change in molar entropy of the system is ${ }^{4}$

$$
\Delta_{\mathrm{trs}} S=\frac{\Delta_{\mathrm{trs}} H}{T_{\mathrm{trs}}} \quad \begin{array}{ll}
\text { At the } & \text { Entropy } \\
\text { transition } & \text { of phase } \\
\text { temperature } & \text { transition }
\end{array}
$$

If the phase transition is exothermic ( $\Delta_{\text {trs }} H<0$, as in freezing or condensing), then the entropy change of the system is negative. This decrease in entropy is consistent with the increased order of a solid compared with a liquid and with the increased order of a liquid compared with a gas. The change in entropy of the surroundings, however, is positive because energy is released as heat into them, and at the transition temperature the total change in entropy is zero. If the transition is endothermic ( $\Delta_{\text {trs }} H>0$, as in melting and vaporization), then the entropy change of the system is positive, which is consistent with dispersal of matter in the system. The entropy of the surroundings decreases by the same amount, and overall the total change in entropy is zero.

Table 3A. 1 lists some experimental entropies of transition. Table 3A. 2 lists in more detail the standard entropies of vaporization of several liquids at their boiling points. An interesting feature of the data is that a wide range of liquids give approximately the same standard entropy of vaporization (about $85 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ ): this empirical observation is called

Table 3A.1* Standard entropies (and temperatures) of phase transitions, $\Delta_{\text {trs }} S^{\ominus} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$
|  | Fusion (at $T_{\mathrm{f}}$ ) | Vaporization (at $T_{\mathrm{b}}$ ) |
| :--- | :--- | :---: |
| Argon, Ar | 14.17 (at 83.8 K ) | 74.53 (at 87.3 K ) |
| Benzene, $\mathrm{C}_{6} \mathrm{H}_{6}$ | 38.00 (at 279 K ) | 87.19 (at 353 K ) |
| Water, $\mathrm{H}_{2} \mathrm{O}$ | 22.00 (at 273.15 K ) | 109.0 (at 373.15 K ) |
| Helium, He | 4.8 (at 8 K and 30 bar) | 19.9 (at 4.22 K ) |


* More values are given in the Resource section.

Table 3A.2* The standard enthalpies and entropies of vaporization of liquids at their normal boiling points
|  | $\Delta_{\text {vap }} H^{\ominus} /\left(\mathrm{kJ} \mathrm{mol}^{-1}\right)$ | $\theta_{\mathrm{b}} /{ }^{\circ} \mathrm{C}$ | $\Delta_{\text {vap }} S^{\ominus} /$ ( $\mathrm{J} \mathrm{K}^{-1} \mathrm{~mol}^{-1}$ ) |
| :--- | :--- | :--- | :--- |
| Benzene | 30.8 | 80.1 | 87.2 |
| Carbon tetrachloride | 30 | 76.7 | 85.8 |
| Cyclohexane | 30.1 | 80.7 | 85.1 |
| Hydrogen sulfide | 18.7 | -60.4 | 87.9 |
| Methane | 8.18 | -161.5 | 73.2 |
| Water | 40.7 | 100.0 | 109.1 |


* More values are given in the Resource section.

[^3]Trouton's rule. The explanation of Trouton's rule is that a comparable change in volume occurs when any liquid evaporates and becomes a gas. Hence, all liquids can be expected to have similar standard entropies of vaporization. Liquids that show significant deviations from Trouton's rule do so on account of strong molecular interactions that result in a partial ordering of their molecules. As a result, there is a greater change in disorder when the liquid turns into a vapour than for a fully disordered liquid. An example is water, where the large entropy of vaporization reflects the presence of structure arising from hydrogen-bonding in the liquid. Hydrogen bonds tend to organize the molecules in the liquid so that they are less random than, for example, the molecules in liquid hydrogen sulfide (in which there is no hydrogen bonding). Methane has an unusually low entropy of vaporization. A part of the reason is that the entropy of the gas itself is slightly low $\left(186 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}\right.$ at 298 K$)$; the entropy of $\mathrm{N}_{2}$ under the same conditions is $192 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$. As explained in Topic 12B, fewer rotational states are accessible at room temperature for molecules with low moments of inertia (like $\mathrm{CH}_{4}$ ) than for molecules with relatively high moments of inertia (like $\mathrm{N}_{2}$ ), so their molar entropy is slightly lower.

## Brief illustration 3A. 8 Trouton's rule

There is no hydrogen bonding in liquid bromine and $\mathrm{Br}_{2}$ is a heavy molecule that is unlikely to display unusual behaviour in the gas phase, so it is safe to use Trouton's rule. To predict the standard molar enthalpy of vaporization of bromine given that it boils at $59.2^{\circ} \mathrm{C}$, we use the rule in the form

$$
\Delta_{\text {vap }} H^{\ominus}=T_{\mathrm{b}} \times\left(85 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)
$$

Substitution of the data then gives

$$
\begin{aligned}
\Delta_{\text {vap }} H^{\ominus} & =(332.4 \mathrm{~K}) \times\left(85 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)=+2.8 \times 10^{3} \mathrm{~J} \mathrm{~mol}^{-1} \\
& =+28 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

The experimental value is $+29.45 \mathrm{~kJ} \mathrm{~mol}^{-1}$.
Self-test 3A. 9 Predict the enthalpy of vaporization of ethane from its boiling point, $-88.6^{\circ} \mathrm{C}$.

Answer: $16 \mathrm{~kJ} \mathrm{~mol}^{-1}$

## (c) Heating

Equation 3A. 2 can be used to calculate the entropy of a system at a temperature $T_{\mathrm{f}}$ from a knowledge of its entropy at another temperature $T_{\mathrm{i}}$ and the heat supplied to change its temperature from one value to the other:

$$
S\left(T_{\mathrm{f}}\right)=S\left(T_{\mathrm{i}}\right)+\int_{T_{\mathrm{i}}}^{T_{\mathrm{f}}} \frac{\mathrm{~d} q_{\mathrm{rev}}}{T}
$$

We shall be particularly interested in the entropy change when the system is subjected to constant pressure (such as from the atmosphere) during the heating. Then, from the definition of constant-pressure heat capacity (eqn 2B.5, $C_{p}=(\partial H / \partial T)_{p}$, written as $\mathrm{d} q_{\mathrm{rev}}=C_{p} \mathrm{~d} T$ ):

$$
S\left(T_{\mathrm{f}}\right)=S\left(T_{\mathrm{i}}\right)+\int_{T_{\mathrm{i}}}^{T_{\mathrm{f}}} \frac{C_{p} \mathrm{~d} T}{T} \quad \begin{aligned}
& \text { Constant } \\
& \text { pressure }
\end{aligned} \quad \begin{aligned}
& \text { Entropy variation } \\
& \text { with temperature }
\end{aligned}
$$

The same expression applies at constant volume, but with $C_{p}$ replaced by $C_{V}$. When $C_{p}$ is independent of temperature in the temperature range of interest, it can be taken outside the integral and we obtain

$$
S\left(T_{\mathrm{f}}\right)=S\left(T_{\mathrm{i}}\right)+C_{p} \int_{T_{\mathrm{i}}}^{T_{\mathrm{f}}} \frac{\mathrm{~d} T}{T}=S\left(T_{\mathrm{i}}\right)+C_{p} \ln \frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}
$$

with a similar expression for heating at constant volume. The logarithmic dependence of entropy on temperature is illustrated in Fig. 3A.13.

## Brief illustration 3A. 9 Entropy change on heating

The molar constant-volume heat capacity of water at 298 K is $75.3 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. The change in molar entropy when it is heated from $20^{\circ} \mathrm{C}(293 \mathrm{~K})$ to $50^{\circ} \mathrm{C}(323 \mathrm{~K})$, supposing the heat capacity to be constant in that range, is therefore

$$
\begin{aligned}
\Delta S_{\mathrm{m}} & =S_{\mathrm{m}}(323 \mathrm{~K})-S_{\mathrm{m}}(293 \mathrm{~K})=\left(75.3 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times \ln \frac{323 \mathrm{~K}}{293 \mathrm{~K}} \\
& =+7.34 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
\end{aligned}
$$

Self-test 3A. 10 What is the change when further heating takes the temperature from $50^{\circ} \mathrm{C}$ to $80^{\circ} \mathrm{C}$ ?

Answer: $+5.99 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-12.jpg?height=521&width=828&top_left_y=1858&top_left_x=1227)
Figure 3A.13 The logarithmic increase in entropy of a substance as it is heated at constant volume. Different curves correspond to different values of the heat capacity (which is assumed constant over the temperature range) expressed as $C_{\mathrm{m}} / R$.

## (d) Composite processes

In many cases, more than one parameter changes. For instance, it might be the case that both the volume and the temperature of a gas are different in the initial and final states. Because $S$ is a state function, we are free to choose the most convenient path from the initial state to the final state, such as reversible isothermal expansion to the final volume, followed by reversible heating at constant volume to the final temperature. Then the total entropy change is the sum of the two contributions.

## Example 3A.2 Calculating the entropy change for a composite process

Calculate the entropy change when argon at $25^{\circ} \mathrm{C}$ and 1.00 bar in a container of volume $0.500 \mathrm{dm}^{3}$ is allowed to expand to $1.000 \mathrm{dm}^{3}$ and is simultaneously heated to $100^{\circ} \mathrm{C}$.

Method As remarked in the text, use reversible isothermal expansion to the final volume, followed by reversible heating at constant volume to the final temperature. The entropy change in the first step is given by eqn 3A. 16 and that of the second step, provided $C_{V}$ is independent of temperature, by eqn 3A. 20 (with $C_{V}$ in place of $C_{p}$ ). In each case we need to know $n$, the amount of gas molecules, and can calculate it from the perfect gas equation and the data for the initial state from $n=p_{\mathrm{i}} V_{\mathrm{i}} / R T_{\mathrm{i}}$. The molar heat capacity at constant volume is given by the equipartition theorem as $\frac{3}{2} R$. (The equipartition theorem is reliable for monatomic gases: for others and in general use experimental data like that in Tables 2C. 1 and 2C. 2 of the Resource section, converting to the value at constant volume by using the relation $C_{p, \mathrm{~m}}-C_{V, \mathrm{~m}}=R$.)

Answer From eqn 3A. 16 the entropy change in the isothermal expansion from $V_{\mathrm{i}}$ to $V_{\mathrm{f}}$ is

$$
\Delta S(\text { Step 1 })=n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}
$$

From eqn 3A.20, the entropy change in the second step, from $T_{\mathrm{i}}$ to $T_{\mathrm{f}}$ at constant volume, is

$$
\Delta S\left(\text { Step 2) }=n C_{V, \mathrm{~m}} \ln \frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}=\frac{3}{2} n R \ln \frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}=n R \ln \left(\frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}\right)^{3 / 2}\right.
$$

The overall entropy change of the system, the sum of these two changes, is

$$
\Delta S=n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}+n R \ln \left(\frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}\right)^{3 / 2}=n R \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}\left(\frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}\right)^{3 / 2}
$$

(We have used $\ln x+\ln y=\ln x y$.) Now we substitute $n=p_{\mathrm{i}} V_{\mathrm{i}} / R T_{\mathrm{i}}$ and obtain

$$
\Delta S=\frac{p_{i} V_{i}}{T_{i}} \ln \frac{V_{\mathrm{f}}}{V_{\mathrm{i}}}\left(\frac{T_{\mathrm{f}}}{T_{\mathrm{i}}}\right)^{3 / 2}
$$

At this point we substitute the data:

$$
\begin{aligned}
\Delta S & =\frac{\left(1.00 \times 10^{5} \mathrm{~Pa}\right) \times\left(0.500 \times 10^{-3} \mathrm{~m}^{3}\right)}{298 \mathrm{~K}} \times \ln \frac{1.000}{0.500}\left(\frac{373}{298}\right)^{3 / 2} \\
& =+0.173 \mathrm{JK}^{-1}
\end{aligned}
$$

A note on good practice It is sensible to proceed as generally as possible before inserting numerical data so that, if required, the formula can be used for other data and to avoid rounding errors.

Self-test 3A.11 Calculate the entropy change when the same initial sample is compressed to $0.0500 \mathrm{dm}^{3}$ and cooled to $-25^{\circ} \mathrm{C}$.

Answer: $-0.44 \mathrm{~J}^{-1}$

## Checklist of concepts

□ 1. The entropy acts as a signpost of spontaneous change.
□ 2. Entropy change is defined in terms of heat transactions (the Clausius definition).
□ 3. The Boltzmann formula defines absolute entropies in terms of the number of ways of achieving a configuration.
□ 6. The Clausius inequality is used to show that the entropy increases in a spontaneous change and therefore that the Clausius definition is consistent with the Second Law.
□ 7. The entropy of a perfect gas increases when it expands isothermally.
□ 4. The Carnot cycle is used to prove that entropy is a state function.
□ 8. The change in entropy of a substance accompanying a change of state at its transition temperature is calculated from its enthalpy of transition.
□ 5. The efficiency of a heat engine is the basis of the definition of the thermodynamic temperature scale and one realization, the Kelvin scale.
□ 9. The increase in entropy when a substance is heated is expressed in terms of its heat capacity.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Thermodynamic entropy | $\mathrm{d} S=\mathrm{d} q_{\text {rev }} / T$ | Definition | 3A. 1 |
| Entropy change of surroundings | $\Delta S_{\text {sur }}=q_{\text {sur }} / T_{\text {sur }}$ |  | 3A.3b |
| Boltzmann formula | $S=k \ln \mathcal{W}$ | Definition | 3A. 5 |
| Carnot efficiency | $\eta=1-T_{\mathrm{c}} / T_{\mathrm{h}}$ | Reversible processes | 3A. 10 |
| Thermodynamic temperature | $T=(1-\eta) T_{\mathrm{h}}$ |  | 3A. 11 |
| Clausius inequality | $\mathrm{d} S \geq \mathrm{d} q / T$ |  | 3A. 12 |
| Entropy of isothermal expansion | $\Delta S=n R \ln \left(V_{\mathrm{f}} / V_{\mathrm{i}}\right)$ | Perfect gas | 3A. 14 |
| Entropy of transition | $\Delta_{\mathrm{trs}} S=\Delta_{\mathrm{trs}} H / T_{\mathrm{trs}}$ | At the transition temperature | 3A. 17 |
| Variation of the entropy with temperature | $S\left(T_{\mathrm{f}}\right)=S\left(T_{\mathrm{i}}\right)+C \ln \left(T_{\mathrm{f}} / T_{\mathrm{i}}\right)$ | The heat capacity, $C$, is independent of temperature and no phase transitions occur | 3A. 20 |

## 3B The measurement of entropy

## Contents

3B. 1 The calorimetric measurement of entropy ..... 126
Brief illustration 3B.1: The standard molar entropy ..... 127
Example 3B.1: Calculating the entropy at low temperatures ..... 127
3B. 2 The Third Law ..... 127
(a) The Nernst heat theorem ..... 127
Brief illustration 3B.2: The Nernst heat theorem ..... 128
Example 3B.2: Estimating a residual entropy ..... 128
(b) Third-Law entropies ..... 129
Brief illustration 3B.3: The standard reaction entropy ..... 129
Brief illustration 3B.4: Absolute and relative ion entropies ..... 130
Checklist of concepts ..... 130
Checklist of equations ..... 130

## Why do you need to know this material?

For entropy to be a quantitatively useful concept it is important to be able to measure it: the calorimetric procedure is described here. The discussion also introduces the Third Law of thermodynamics, which has important implications for the measurement of entropies and (as shown in later Topics) the attainment of absolute zero.

What is the key idea?
The entropy of a perfectly crystalline solid is zero at $T=0$.
What do you need to know already?
You need to be familiar with the expression for the temperature dependence of entropy and how entropies of transition are calculated (Topic 3A). The discussion of residual entropy draws on the Boltzmann formula for the entropy (Topic 3A).

The entropy of a substance can be determined in two ways. One, which is the subject of this Topic, is to make calorimetric measurements of the heat required to raise the temperature of a sample from $T=0$ to the temperature of interest. The other,
which is described in Topic 15E, is to use calculated parameters or spectroscopic data and to calculate the entropy by using Boltzmann's statistical definition.

### 38.1 The calorimetric measurement of entropy

It is established in Topic 3A that the entropy of a system at a temperature $T$ is related to its entropy at $T=0$ by measuring its heat capacity $C_{p}$ at different temperatures and evaluating the integral in eqn 3A. $19\left(S\left(T_{\mathrm{f}}\right)=S\left(T_{\mathrm{i}}\right)+\int_{T_{\mathrm{i}}}^{T_{\mathrm{f}}} C_{p} \mathrm{~d} T / T\right)$. The entropy of transition ( $\Delta_{\mathrm{trs}} H / T_{\mathrm{trs}}$ ) for each phase transition between $T=0$ and the temperature of interest must then be included in the overall sum. For example, if a substance melts at $T_{\mathrm{f}}$ and boils at $T_{\mathrm{b}}$, then its molar entropy above its boiling temperature is given by

All the properties required, except $S_{\mathrm{m}}(0)$, can be measured calorimetrically, and the integrals can be evaluated either graphically or, as is now more usual, by fitting a polynomial to the data and integrating the polynomial analytically. The former procedure is illustrated in Fig. 3B.1: the area under the curve of $C_{p, \mathrm{~m}} / T$ against $T$ is the integral required. Provided all measurements are made at 1 bar on a pure material, the final value is the standard entropy, $S^{\ominus}(T)$ and, on division by the amount of substance $n$, its standard molar entropy, $S_{\mathrm{m}}^{\ominus}(T)=S^{\ominus}(T) / n$. Because $\mathrm{d} T / T=\mathrm{d} \ln T$, an alternative procedure is to evaluate the area under a plot of $C_{p, \mathrm{~m}}$ against $\ln T$.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-16.jpg?height=502&width=803&top_left_y=314&top_left_x=280)
Figure 3B. 1 The variation of $C_{p} / T$ with the temperature for a sample is used to evaluate the entropy, which is equal to the area beneath the upper curve up to the corresponding temperature, plus the entropy of each phase transition passed.

## Brief illustration 3B.1 The standard molar entropy

The standard molar entropy of nitrogen gas at $25^{\circ} \mathrm{C}$ has been calculated from the following data:

|  | $S_{\mathrm{m}}^{\ominus} /\left(\mathrm{J} \mathrm{K}^{-1} \mathrm{~mol}^{-1}\right)$ |
| :--- | :--- |
| Debye extrapolation* | 1.92 |
| Integration, from 10 K to 35.61 K | 25.25 |
| Phase transition at 35.61 K | 6.43 |
| Integration, from 35.61 K to 63.14 K | 23.38 |
| Fusion at 63.14 K | 11.42 |
| Integration, from 63.14 K to 77.32 K | 11.41 |
| Vaporization at 77.32 K | 72.13 |
| Integration, from 77.32 K to 298.15 K | 39.20 |
| Correction for gas imperfection | 0.92 |
| Total | 192.06 |

Therefore, $S_{\mathrm{m}}^{\ominus}(298.15 \mathrm{~K})=S_{\mathrm{m}}(0)+192.1 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$.
${ }^{\star}$ This extrapolation is explained immediately following.

One problem with the determination of entropy is the difficulty of measuring heat capacities near $T=0$. There are good theoretical grounds for assuming that the heat capacity of a non-metallic solid is proportional to $T^{3}$ when $T$ is low (see Topic 7A), and this dependence is the basis of the Debye extrapolation. In this method, $C_{p}$ is measured down to as low a temperature as possible and a curve of the form $a T^{3}$ is fitted to the data. That fit determines the value of $a$, and the expression $C_{p, \mathrm{~m}}=a T^{3}$ is assumed valid down to $T=0$.

## Example 3B. 1 Calculating the entropy at low temperatures

The molar constant-pressure heat capacity of a certain solid at 4.2 K is $0.43 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. What is its molar entropy at that temperature?

Method Because the temperature is so low, we can assume that the heat capacity varies with temperature as $a T^{3}$, in which case we can use eqn 3A. 19 (quoted in the opening paragraph of 3B.1) to calculate the entropy at a temperature $T$ in terms of the entropy at $T=0$ and the constant $a$. When the integration is carried out, it turns out that the result can be expressed in terms of the heat capacity at the temperature $T$, so the data can be used directly to calculate the entropy.

Answer The integration required is

$$
\begin{aligned}
S_{\mathrm{m}}(T) & =S_{\mathrm{m}}(0)+\int_{0}^{T} \frac{a T^{3}}{T} \mathrm{~d} T=S_{\mathrm{m}}(0)+a \int_{0}^{T} T^{2} \mathrm{~d} T \\
& =S_{\mathrm{m}}(0)+\frac{1}{3} a T^{3}=S_{\mathrm{m}}(0)+\frac{1}{3} C_{p, \mathrm{~m}}(T)
\end{aligned}
$$

from which it follows that

$$
S_{\mathrm{m}}(4.2 \mathrm{~K})=S_{\mathrm{m}}(0)+0.14 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
$$

Self-test 3B. 1 For metals, there is also a contribution to the heat capacity from the electrons which is linearly proportional to $T$ when the temperature is low. Find its contribution to the entropy at low temperatures.

Answer: $S(T)=S(0)+C_{p}(T)$

## 3B. 2 The Third Law

We now address the problem of the value of $S(0)$. At $T=0$, all energy of thermal motion has been quenched, and in a perfect crystal all the atoms or ions are in a regular, uniform array. The localization of matter and the absence of thermal motion suggest that such materials also have zero entropy. This conclusion is consistent with the molecular interpretation of entropy, because $S=0$ if there is only one way of arranging the molecules and only one microstate is accessible (all molecules occupy the ground state, $\mathcal{W}=1$ ).

## (a) The Nernst heat theorem

The experimental observation that turns out to be consistent with the view that the entropy of a regular array of molecules is zero at $T=0$ is summarized by the Nernst heat theorem:

The entropy change accompanying any physical or chemical transformation approaches zero as the temperature approaches zero: $\Delta S \rightarrow 0$ as $T \rightarrow 0$ provided all the substances involved are perfectly ordered.
Nernst heat theorem

## Brief illustration 3B.2 The Nernst heat theorem

Consider the entropy of the transition between orthorhombic sulfur, $\alpha$, and monoclinic sulfur, $\beta$, which can be calculated from the transition enthalpy $\left(-402 \mathrm{~J} \mathrm{~mol}^{-1}\right)$ at the transition temperature $(369 \mathrm{~K})$ :

$$
\begin{aligned}
\Delta_{\mathrm{trs}} S & =S_{\mathrm{m}}(\beta)-S_{\mathrm{m}}(\alpha)=\frac{-402 \mathrm{Jmol}^{-1}}{369 \mathrm{~K}} \\
& =-1.09 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
\end{aligned}
$$

The two individual entropies can also be determined by measuring the heat capacities from $T=0$ up to $T=369 \mathrm{~K}$. It is found that $S_{\mathrm{m}}(\alpha)=S_{\mathrm{m}}(\alpha, 0)+37 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$ and $S_{\mathrm{m}}(\beta)=S_{\mathrm{m}}(\beta, 0) +38 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. These two values imply that at the transition temperature

$$
\Delta_{\mathrm{trs}} S=S_{\mathrm{m}}(\alpha, 0)-S_{\mathrm{m}}(\beta, 0)=-1 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
$$

On comparing this value with the one above, we conclude that $S_{\mathrm{m}}(\alpha, 0)-S_{\mathrm{m}}(\beta, 0) \approx 0$, in accord with the theorem.

Self-test 3B. 2 Two forms of a metallic solid (see Self-test 3B.1) undergo a phase transition at $T_{\text {trs }}$, which is close to $T=0$. What is the enthalpy of transition at $T_{\text {trs }}$ in terms of the heat capacities of the two polymorphs?

Answer: $\Delta_{\text {trs }} H\left(T_{\text {trs }}\right)=T_{\text {trs }} \Delta C_{p}\left(T_{\text {trs }}\right)$

It follows from the Nernst theorem, that if we arbitrarily ascribe the value zero to the entropies of elements in their perfect crystalline form at $T=0$, then all perfect crystalline compounds also have zero entropy at $T=0$ (because the change in entropy that accompanies the formation of the compounds, like the entropy of all transformations at that temperature, is zero). This conclusion is summarized by the Third Law of thermodynamics:

The entropy of all perfect crystalline substances is zero at $T=0$.

Third Law of thermodynamics

As far as thermodynamics is concerned, choosing this common value as zero is a matter of convenience. The molecular interpretation of entropy, however, justifies the value $S=0$ at $T=0$ because then, as we have remarked, $W=1$.

In certain cases $\mathcal{W}>1$ at $T=0$ and therefore $S(0)>0$. This is the case if there is no energy advantage in adopting a particular orientation even at absolute zero. For instance, for a diatomic molecule AB there may be almost no energy difference between the arrangements $\ldots \mathrm{AB} \mathrm{AB} \mathrm{AB} \ldots$ and $\ldots \mathrm{BA} \mathrm{AB} \mathrm{BA} \ldots$, so $\mathcal{W}>1$ even at $T=0$. If $S(0)>0$ we say that the substance has a residual entropy. Ice has a residual entropy of $3.4 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$. It stems from the arrangement of the hydrogen bonds between neighbouring water molecules: a given O atom has two short $\mathrm{O}-\mathrm{H}$ bonds and
two long $\mathrm{O} \cdots \mathrm{H}$ bonds to its neighbours, but there is a degree of randomness in which two bonds are short and which two are long.

## Example 3B. 2 Estimating a residual entropy

Estimate the residual entropy of ice by taking into account the distribution of hydrogen bonds and chemical bonds about the oxygen atom of one $\mathrm{H}_{2} \mathrm{O}$ molecule. The experimental value is $3.4 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$.

Method Focus on the O atom, and consider the number of ways that that O atom can have two short (chemical) bonds and two long hydrogen bonds to its four neighbours. Refer to Fig. 3B.2.
(a)
![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-17.jpg?height=225&width=249&top_left_y=931&top_left_x=1225)
(b)
![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-17.jpg?height=450&width=251&top_left_y=1161&top_left_x=1221)

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-17.jpg?height=450&width=247&top_left_y=1161&top_left_x=1501)
Figure 3B. 2 The model of ice showing (a) the local structure of an oxygen atom and (b) the array of chemical and hydrogen bonds used to calculate the residual entropy of ice.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-17.jpg?height=450&width=249&top_left_y=1161&top_left_x=1781)

Answer Suppose each H atom can lie either close to or far from its 'parent' O atom, as depicted in Fig. 3B.2. The total number of these conceivable arrangements in a sample that contains $N \mathrm{H}_{2} \mathrm{O}$ molecules and therefore $2 N \mathrm{H}$ atoms is $2^{2 N}$. Now consider a single central O atom. The total number of possible arrangements of locations of H atoms around the central O atom of one $\mathrm{H}_{2} \mathrm{O}$ molecule is $2^{4}=16$. Of these 16 possibilities, only 6 correspond to two short and two long bonds. That is, only $\frac{6}{16}=\frac{3}{8}$ of all possible arrangements are possible, and for $N$ such molecules only $(3 / 8)^{N}$ of all possible arrangements are possible. Therefore, the total number of allowed arrangements in the crystal is $2^{2 N}(3 / 8)^{N}=4^{N}(3 / 8)^{N}=(3 / 2)^{N}$. If we suppose that all these arrangements are energetically identical, the residual entropy is

$$
S(0)=k \ln \left(\frac{3}{2}\right)^{N}=N k \ln \frac{3}{2}=n N_{A} k \ln \frac{3}{2}=n R \ln \frac{3}{2}
$$

and the residual molar entropy would be

$$
S_{\mathrm{m}}(0)=R \ln \frac{3}{2}=3.4 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
$$

in accord with the experimental value.
Self-test 3B.3 What would be the residual molar entropy of $\mathrm{HCF}_{3}$ on the assumption that each molecule could take up one of four tetrahedral orientations in a crystal?

Answer: $11.5 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$

## (b) Third-Law entropies

Entropies reported on the basis that $S(0)=0$ are called ThirdLaw entropies (and commonly just 'entropies'). When the substance is in its standard state at the temperature $T$, the standard (Third-Law) entropy is denoted $S^{\ominus}(T)$. A list of values at 298 K is given in Table 3B.1.

The standard reaction entropy, $\Delta_{\mathrm{r}} S^{\ominus}$, is defined, like the standard reaction enthalpy in Topic 2C, as the difference between the molar entropies of the pure, separated products and the pure, separated reactants, all substances being in their standard states at the specified temperature:

$$
\Delta_{\mathrm{r}} S^{\ominus}=\sum_{\text {Products }} \nu S_{\mathrm{m}}^{\ominus}-\sum_{\text {Reactants }} \nu S_{\mathrm{m}}^{\ominus} \quad \text { Definition } \quad \begin{aligned}
& \text { Standard } \\
& \text { reaction } \\
& \text { entropy }
\end{aligned}
$$

In this expression, each term is weighted by the appropriate stoichiometric coefficient. A more sophisticated approach is to adopt the notation introduced in Topic 2C and to write

Table 3B.1* Standard Third-Law entropies at 298 K , $S_{\mathrm{m}}^{\ominus} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$
|  | $S_{\mathrm{m}}^{\ominus} /\left(\mathrm{J} \mathrm{K}^{-1} \mathrm{~mol}^{-1}\right)$ |
| :--- | :--- |
| Solids |  |
| Graphite, C(s) | 5.7 |
| Diamond, C(s) | 2.4 |
| Sucrose, $\mathrm{C}_{12} \mathrm{H}_{22} \mathrm{O}_{11}(\mathrm{~s})$ | 360.2 |
| Iodine, $\mathrm{I}_{2}(\mathrm{~s})$ | 116.1 |
| Liquids |  |
| Benzene, $\mathrm{C}_{6} \mathrm{H}_{6}(\mathrm{l})$ | 173.3 |
| Water, $\mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ | 69.9 |
| Mercury, $\mathrm{Hg}(\mathrm{l})$ | 76.0 |
| Gases |  |
| Methane, $\mathrm{CH}_{4}(\mathrm{~g})$ | 186.3 |
| Carbon dioxide, $\mathrm{CO}_{2}(\mathrm{~g})$ | 213.7 |
| Hydrogen, $\mathrm{H}_{2}(\mathrm{~g})$ | 130.7 |
| Helium, He(g) | 126.2 |
| Ammonia, $\mathrm{NH}_{3}(\mathrm{~g})$ | 192.4 |


[^4]
## Brief illustration 3B.3 The standard reaction entropy

To calculate the standard reaction entropy of $\mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{O}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ at 298 K , we use the data in Table 2C. 5 of the Resource section to write

$$
\begin{aligned}
\Delta_{\mathrm{r}} S^{\ominus} & =S_{\mathrm{m}}^{\ominus}\left(\mathrm{H}_{2} \mathrm{O}, \mathrm{l}\right)-\left\{S_{\mathrm{m}}^{\ominus}\left(\mathrm{H}_{2}, \mathrm{~g}\right)+\frac{1}{2} S_{\mathrm{m}}^{\ominus}\left(\mathrm{O}_{2}, \mathrm{~g}\right)\right\} \\
& =69.9 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}-\left\{130.7+\frac{1}{2}(205.1)\right\} \mathrm{JK}^{-1} \mathrm{~mol}^{-1} \\
& =-163.4 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}
\end{aligned}
$$

The negative value is consistent with the conversion of two gases to a compact liquid.

A note on good practice Do not make the mistake of setting the standard molar entropies of elements equal to zero: they have nonzero values (provided $T>0$ ), as we have already discussed.

Self-test 3B.4 Calculate the standard reaction entropy for the combustion of methane to carbon dioxide and liquid water at 298 K.

Answer: $-243 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$

$$
\Delta_{\mathrm{r}} S^{\ominus}=\sum_{\mathrm{J}} v_{\mathrm{J}} S_{\mathrm{m}}^{\ominus}(\mathrm{J})
$$

where the $\nu_{\mathrm{J}}$ are signed ( + for products, - for reactants) stoichiometric numbers. Standard reaction entropies are likely to be positive if there is a net formation of gas in a reaction, and are likely to be negative if there is a net consumption of gas.

Just as in the discussion of enthalpies in Topic 2C, where it is acknowledged that solutions of cations cannot be prepared in the absence of anions, the standard molar entropies of ions in solution are reported on a scale in which the standard entropy of the $\mathrm{H}^{+}$ions in water is taken as zero at all temperatures:

$$
S^{\ominus}\left(\mathrm{H}^{+}, \mathrm{aq}\right)=0
$$

Convention Ions in solution

The values based on this choice are listed in Table 2C. 5 in the Resource section. ${ }^{1}$ Because the entropies of ions in water are values relative to the hydrogen ion in water, they may be either positive or negative. A positive entropy means that an ion has a higher molar entropy than $\mathrm{H}^{+}$in water and a negative entropy means that the ion has a lower molar entropy than $\mathrm{H}^{+}$in water. Ion entropies vary as expected on the basis that they are related to the degree to which the ions order the water molecules around them in the solution. Small, highly charged ions induce local structure in the surrounding water, and the disorder of

[^5]the solution is decreased more than in the case of large, singly charged ions. The absolute, Third-Law standard molar entropy of the proton in water can be estimated by proposing a model of the structure it induces, and there is some agreement on the value $-21 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. The negative value indicates that the proton induces order in the solvent.

## Brief illustration 3B.4 Absolute and relative ion

entropies
The standard molar entropy of $\mathrm{Cl}^{-}(\mathrm{aq})$ is $+57 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ and that of $\mathrm{Mg}^{2+}(\mathrm{aq})$ is $-128 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. That is, the partial molar
entropy of $\mathrm{Cl}^{-}(\mathrm{aq})$ is $57 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ higher than that of the proton in water (presumably because it induces less local structure in the surrounding water), whereas that of $\mathrm{Mg}^{2+}(\mathrm{aq})$ is $128 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ lower (presumably because its higher charge induces more local structure in the surrounding water).

Self-test 3B. 5 Estimate the absolute values of the partial molar entropies of these ions.

Answer: $+36 \mathrm{JK}^{-1} \mathrm{~mol}^{-1},-149 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$

## Checklist of concepts

□ 1. Entropies are determined calorimetrically by measuring the heat capacity of a substance from low temperatures up to the temperature of interest.
□ 2. The Debye- $T^{3}$ law is used to estimate heat capacities of non-metallic solids close to $T=0$.
□ 3. The Nernst heat theorem states that the entropy change accompanying any physical or chemical transformation approaches zero as the temperature approaches zero: $\Delta S \rightarrow 0$ as $T \rightarrow 0$ provided all the substances involved are perfectly ordered.
□ 4. The Third Law of thermodynamics states that the entropy of all perfect crystalline substances is zero at $T=0$.
□ 5. The residual entropy of a solid is the entropy arising from disorder that persists at $T=0$.
□ 6. Third-Law entropies are entropies based on $S(0)=0$.
□ 7. The standard entropies of ions in solution are based on setting $S^{\ominus}\left(\mathrm{H}^{+}, \mathrm{aq}\right)=0$ at all temperatures.
□ 8. The standard reaction entropy, $\Delta_{\mathrm{r}} S^{\ominus}$, is the difference between the molar entropies of the pure, separated products and the pure, separated reactants, all substances being in their standard states.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Standard molar entropy from calorimetry | See eqn 3B. 1 | Sum of contributions from $T=0$ to temperature of interest | 3B. 1 |
| Standard reaction entropy | $\begin{aligned} \Delta_{\mathrm{r}} S^{\ominus} & =\sum_{\text {Products }} v S_{\mathrm{m}}^{\ominus}-\sum_{\text {Reactants }} v S_{\mathrm{m}}^{\ominus} \\ \Delta_{\mathrm{r}} S^{\ominus} & =\sum_{\mathrm{J}} v_{\mathrm{J}} S_{\mathrm{m}}^{\ominus}(\mathrm{J}) \end{aligned}$ | $\nu$ : (positive) stoichiometric coefficients; $\nu_{\mathrm{J}}$ : (signed) stoichiometric numbers | 3B. 2 |

## 3C Concentrating on the system

## Contents

3C.1 The Helmholtz and Gibbs energies 131
(a) Criteria of spontaneity 131

Brief illustration 3C.1: Spontaneous changes at constant volume

132
Brief illustration 3C.2: The spontaneity of endothermic reactions

132
(b) Some remarks on the Helmholtz energy 133

Brief illustration 3C.3: Spontaneous change at constant volume

133
(c) Maximum work 133

Example 3C.1: Calculating the maximum available work
(d) Some remarks on the Gibbs energy

134
(e) Maximum non-expansion work

134
Example 3C.2: Calculating the maximum non-expansion work of a reaction

135
135
3C. 2 Standard molar Gibbs energies
136
(a) Gibbs energies of formation

136
Brief illustration 3C.4: The standard reaction Gibbs energy

136
Brief illustration 3C.5: Gibbs energies of formation of ions
(b) The Born equation

Brief illustration 3C.6: The Born equation
Checklist of concepts
Checklist of equations

Why do you need to know this material?
Most processes of interest in chemistry occur at constant temperature and pressure. Under these conditions, thermodynamic processes are discussed in terms of the Gibbs energy, which is introduced in this Topic. The Gibbs energy is the foundation of the discussion of phase equilibria, chemical equilibrium, and bioenergetics.

What is the key idea?
The Gibbs energy is a signpost of spontaneous change at constant temperature and pressure, and is equal to the maximum non-expansion work that a system can do.

What do you need to know already?
This Topic develops the Clausius inequality (Topic 3A) and draws on information about standard states and reaction enthalpy introduced in Topic 2C. The derivation of the Born equation uses information about the energy of one electric charge in the field of another (Foundations B).

Entropy is the basic concept for discussing the direction of natural change, but to use it we have to analyse changes in both the system and its surroundings. In Topic 3A it is shown that it is always very simple to calculate the entropy change in the surroundings (from $\Delta S_{\text {sur }}=q_{\text {sur }} / T_{\text {sur }}$ ); here we see that it is possible to devise a simple method for taking that contribution into account automatically. This approach focuses our attention on the system and simplifies discussions. Moreover, it is the foundation of all the applications of chemical thermodynamics that follow.

## 3c. 1 The Helmholtz and Gibbs energies

Consider a system in thermal equilibrium with its surroundings at a temperature $T$. When a change in the system occurs and there is a transfer of energy as heat between the system and the surroundings, the Clausius inequality (eqn 3A.12, $\mathrm{d} S \geq \mathrm{d} q / T$ ) reads

$$
\mathrm{d} S-\frac{\mathrm{d} q}{T} \geq 0
$$

We can develop this inequality in two ways according to the conditions (of constant volume or constant pressure) under which the process occurs.

## (a) Criteria of spontaneity

First, consider heating at constant volume. Then, in the absence of additional (non-expansion) work, we can write $\mathrm{d} q_{V}=\mathrm{d} U$; consequently

$$
\mathrm{d} S-\frac{\mathrm{d} U}{T} \geq 0
$$

The importance of the inequality in this form is that it expresses the criterion for spontaneous change solely in terms of the state functions of the system. The inequality is easily rearranged into

$$
T \mathrm{~d} S \geq \mathrm{d} U \text { (constant } V, \text { no additional work) }
$$

Because $T>0$, at either constant internal energy ( $\mathrm{d} U=0$ ) or constant entropy ( $\mathrm{d} S=0$ ) this expression becomes, respectively,

$$
\mathrm{d} S_{U, V} \geq 0 \quad \mathrm{~d} U_{S, V} \leq 0
$$

where the subscripts indicate the constant conditions.
Equation 3C. 4 expresses the criteria for spontaneous change in terms of properties relating to the system. The first inequality states that, in a system at constant volume and constant internal energy (such as an isolated system), the entropy increases in a spontaneous change. That statement is essentially the content of the Second Law. The second inequality is less obvious, for it says that if the entropy and volume of the system are constant, then the internal energy must decrease in a spontaneous change. Do not interpret this criterion as a tendency of the system to sink to lower energy. It is a disguised statement about entropy and should be interpreted as implying that if the entropy of the system is unchanged, then there must be an increase in entropy of the surroundings, which can be achieved only if the energy of the system decreases as energy flows out as heat.

When energy is transferred as heat at constant pressure, and there is no work other than expansion work, we can write $\mathrm{d} q_{p}=\mathrm{d} H$ and obtain

$$
T \mathrm{~d} S \geq \mathrm{d} H \quad \text { (constant } p \text {, no additional work) }
$$

At either constant enthalpy or constant entropy this inequality becomes, respectively,

$$
\mathrm{d} S_{H, p} \geq 0 \quad \mathrm{~d} H_{S, p} \leq 0
$$

The interpretations of these inequalities are similar to those of eqn 3C.4. The entropy of the system at constant pressure must increase if its enthalpy remains constant (for there can then be no change in entropy of the surroundings). Alternatively, the enthalpy must decrease if the entropy of the system is constant, for then it is essential to have an increase in entropy of the surroundings.

## Brief illustration 3C. 1 volume

A concrete example of the criterion $\mathrm{d} S_{U, V} \geq 0$ is the diffusion of a solute B through a solvent A that form an ideal solution (in the sense of Topic 5B, in which AA, BB, and AB interactions are identical). There is no change in internal energy or volume
of the system or the surroundings as B spreads into A, but the process is spontaneous.

Self-test 3C. 1 Invent an example of the criterion $\mathrm{d} U_{S, V} \leq 0$.
Answer: A phase change in which one perfectly ordered phase changes into another of lower energy and equal density at $T=0$

Because eqns 3C. 4 and 3C. 6 have the forms $\mathrm{d} U-T \mathrm{~d} S \leq 0$ and $\mathrm{d} H-T \mathrm{~d} S \leq 0$, respectively, they can be expressed more simply by introducing two more thermodynamic quantities. One is the Helmholtz energy, $A$, which is defined as

$$
A=U-T S
$$

Definition Helmholtz energy

The other is the Gibbs energy, $G$ :

$$
G=H-T S
$$

Definition Gibbs energy
(3C.8)
All the symbols in these two definitions refer to the system.
When the state of the system changes at constant temperature, the two properties change as follows:
(a) $\mathrm{d} A=\mathrm{d} U-T \mathrm{~d} S$
(b) $\mathrm{d} G=\mathrm{d} H-T \mathrm{~d} S$
(3C.9)
When we introduce eqns 3C. 4 and 3C.6, respectively, we obtain the criteria of spontaneous change as
(a) $\mathrm{d} A_{T, V} \leq 0$
(b) $\mathrm{d} G_{T, p} \leq 0$

Criteria of spontaneous change

These inequalities, especially the second, are the most important conclusions from thermodynamics for chemistry. They are developed in subsequent sections, Topics, and chapters.

## Brief illustration 3C.2 The spontaneity of endothermic reactions

The existence of spontaneous endothermic reactions provides an illustration of the role of $G$. In such reactions, $H$ increases, the system rises spontaneously to states of higher enthalpy, and $\mathrm{d} H>0$. Because the reaction is spontaneous we know that $\mathrm{d} G<0$ despite $\mathrm{d} H>0$; it follows that the entropy of the system increases so much that $T \mathrm{~d} S$ outweighs $\mathrm{d} H$ in $\mathrm{d} G=\mathrm{d} H-T \mathrm{~d} S$. Endothermic reactions are therefore driven by the increase of entropy of the system, and this entropy change overcomes the reduction of entropy brought about in the surroundings by the inflow of heat into the system ( $\mathrm{d} S_{\text {sur }}=-\mathrm{d} H / T$ at constant pressure).

Self-test 3C.2 Why are so many exothermic reactions spontaneous?

[^6]
## (b) Some remarks on the Helmholtz energy

A change in a system at constant temperature and volume is spontaneous if $\mathrm{d} A_{T, V} \leq 0$. That is, a change under these conditions is spontaneous if it corresponds to a decrease in the Helmholtz energy. Such systems move spontaneously towards states of lower $A$ if a path is available. The criterion of equilibrium, when neither the forward nor reverse process has a tendency to occur, is

$$
\mathrm{d} A_{T, V}=0
$$

The expressions $\mathrm{d} A=\mathrm{d} U-T \mathrm{~d} S$ and $\mathrm{d} A<0$ are sometimes interpreted as follows. A negative value of $\mathrm{d} A$ is favoured by a negative value of $\mathrm{d} U$ and a positive value of $T \mathrm{~d} S$. This observation suggests that the tendency of a system to move to lower $A$ is due to its tendency to move towards states of lower internal energy and higher entropy. However, this interpretation is false because the tendency to lower $A$ is solely a tendency towards states of greater overall entropy. Systems change spontaneously if in doing so the total entropy of the system and its surroundings increases, not because they tend to lower internal energy. The form of $\mathrm{d} A$ may give the impression that systems favour lower energy, but that is misleading: $\mathrm{d} S$ is the entropy change of the system, $-\mathrm{d} U / T$ is the entropy change of the surroundings (when the volume of the system is constant), and their total tends to a maximum.

## Brief illustration 3C. 3 volume

A bouncing ball comes to rest. The spontaneous direction of change is one in which the energy of the ball (potential at the top of its bounce, kinetic when it strikes the floor) spreads out into the surroundings on each bounce. When the ball is still, the energy of the universe is the same as initially, but the energy of the ball is dispersed over the surroundings.

Self-test 3C. 3 What other spontaneous similar mechanical processes have a similar explanation?

Answer: One example: A pendulum coming to rest through friction.

## (c) Maximum work

It turns out, as we show in the following Justification, that $A$ carries a greater significance than being simply a signpost of spontaneous change: the change in the Helmholtz function is equal to the maximum work accompanying a process at constant temperature:

$$
\mathrm{d} w_{\max }=\mathrm{d} A \quad \text { Constant temperature Maximum work }
$$

As a result, $A$ is sometimes called the 'maximum work function', or the 'work function.' ${ }^{1}$

## Justification 3C. 1 Maximum work

To demonstrate that maximum work can be expressed in terms of the changes in Helmholtz energy, we combine the Clausius inequality $\mathrm{d} S \geq \mathrm{d} q / T$ in the form $T \mathrm{~d} S \geq \mathrm{d} q$ with the First Law, $\mathrm{d} U=\mathrm{d} q+\mathrm{d} w$, and obtain

$$
\mathrm{d} U \leq T \mathrm{~d} S+\mathrm{d} w
$$

$\mathrm{d} U$ is smaller than the term of the right because $\mathrm{d} q$ has been replaced by $T \mathrm{~d} S$, which in general is larger than $\mathrm{d} q$. This expression rearranges to

$$
\mathrm{d} w \geq \mathrm{d} U-T \mathrm{~d} S
$$

It follows that the most negative value of $\mathrm{d} w$, and therefore the maximum energy that can be obtained from the system as work, is given by

$$
\mathrm{d} w_{\max }=\mathrm{d} U-T \mathrm{~d} S
$$

and that this work is done only when the path is traversed reversibly (because then the equality applies). Because at constant temperature $\mathrm{d} A=\mathrm{d} U-T \mathrm{~d} S$, we conclude that $\mathrm{d} w_{\text {max }}=\mathrm{d} A$.

When a macroscopic isothermal change takes place in the system, eqn 3C. 12 becomes

$$
w_{\max }=\Delta A \quad \text { Constant temperature } \quad \text { Maximum work }
$$

with

$$
\Delta A=\Delta U-T \Delta S
$$

Constant temperature

This expression shows that, depending on the sign of $T \Delta S$, not all the change in internal energy may be available for doing work. If the change occurs with a decrease in entropy (of the system), in which case $T \Delta S<0$, then the right-hand side of this equation is not as negative as $\Delta U$ itself, and consequently the maximum work is less than $\Delta U$. For the change to be spontaneous, some of the energy must escape as heat in order to generate enough entropy in the surroundings to overcome the reduction in entropy in the system (Fig. 3C.1). In this case, Nature is demanding a tax on the internal energy as it is converted into work. This is the origin of the alternative name 'Helmholtz free energy' for $A$, because $\Delta A$ is that part of the change in internal energy that we are free to use to do work.

Further insight into the relation between the work that a system can do and the Helmholtz energy is to recall that work is

[^7]![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-23.jpg?height=418&width=470&top_left_y=314&top_left_x=444)
Figure 3C. 1 In a system not isolated from its surroundings, the work done may be different from the change in internal energy. Moreover, the process is spontaneous if overall the entropy of the global, isolated system increases. In the process depicted here, the entropy of the system decreases, so that of the surroundings must increase in order for the process to be spontaneous, which means that energy must pass from the system to the surroundings as heat. Therefore, less work than $\Delta U$ can be obtained.

energy transferred to the surroundings as the uniform motion of atoms. We can interpret the expression $A=U-T S$ as showing that $A$ is the total internal energy of the system, $U$, less a contribution that is stored as energy of thermal motion (the quantity $T S$ ). Because energy stored in random thermal motion cannot be used to achieve uniform motion in the surroundings, only the part of $U$ that is not stored in that way, the quantity $U-T S$, is available for conversion into work.

If the change occurs with an increase of entropy of the system (in which case $T \Delta S>0$ ), the right-hand side of the equation is more negative than $\Delta U$. In this case, the maximum work that can be obtained from the system is greater than $\Delta U$. The explanation of this apparent paradox is that the system is not isolated and energy may flow in as heat as work is done. Because the entropy of the system increases, we can afford a reduction of

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-23.jpg?height=420&width=468&top_left_y=1918&top_left_x=441)
Figure 3C. 2 In this process, the entropy of the system increases; hence we can afford to lose some entropy of the surroundings. That is, some of their energy may be lost as heat to the system. This energy can be returned to them as work. Hence the work done can exceed $\Delta U$.

the entropy of the surroundings yet still have, overall, a spontaneous process. Therefore, some energy (no more than the value of $T \Delta S$ ) may leave the surroundings as heat and contribute to the work the change is generating (Fig. 3C.2). Nature is now providing a tax refund.

## Example 3C. 1 Calculating the maximum available work

When $1.000 \mathrm{~mol} \mathrm{C}_{6} \mathrm{H}_{12} \mathrm{O}_{6}$ (glucose) is oxidized to carbon dioxide and water at $25^{\circ} \mathrm{C}$ according to the equation $\mathrm{C}_{6} \mathrm{H}_{12} \mathrm{O}_{6}(\mathrm{~s})+6 \mathrm{O}_{2}(\mathrm{~g}) \rightarrow 6 \mathrm{CO}_{2}(\mathrm{~g})+6 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ calorimetric measurements give $\Delta_{\mathrm{r}} U^{\ominus}=-2808 \mathrm{~kJ} \mathrm{~mol}^{-1}$ and $\Delta_{\mathrm{r}} S^{\ominus}= +182.4 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ at $25^{\circ} \mathrm{C}$. How much of this energy change can be extracted as (a) heat at constant pressure, (b) work?

Method We know that the heat released at constant pressure is equal to the value of $\Delta H$, so we need to relate $\Delta_{\mathrm{r}} H^{\ominus}$ to $\Delta_{\mathrm{r}} U^{\ominus}$, which is given. To do so, we suppose that all the gases involved are perfect, and use eqn $2 \mathrm{~B} .4\left(\Delta H=\Delta U+\Delta n_{\mathrm{g}} R T\right)$ in the form $\Delta_{\mathrm{r}} H=\Delta_{\mathrm{r}} U+\Delta \nu_{\mathrm{g}} R T$. For the maximum work available from the process we use eqn 3C.13.

Answer (a) Because $\Delta \nu_{\mathrm{g}}=0$, we know that $\Delta_{\mathrm{r}} H^{\ominus}=\Delta_{\mathrm{r}} U^{\ominus}= -2808 \mathrm{~kJ} \mathrm{~mol}^{-1}$. Therefore, at constant pressure, the energy available as heat is $2808 \mathrm{~kJ} \mathrm{~mol}^{-1}$. (b) Because $T=298 \mathrm{~K}$, the value of $\Delta_{\mathrm{r}} A^{\ominus}$ is

$$
\Delta_{\mathrm{r}} A^{\ominus}=\Delta_{\mathrm{r}} U^{\ominus}-T \Delta_{\mathrm{r}} S^{\ominus}=-2862 \mathrm{~kJ} \mathrm{~mol}^{-1}
$$

Therefore, the combustion of $1.000 \mathrm{~mol} \mathrm{C}_{6} \mathrm{H}_{12} \mathrm{O}_{6}$ can be used to produce up to 2862 kJ of work. The maximum work available is greater than the change in internal energy on account of the positive entropy of reaction (which is partly due to the generation of a large number of small molecules from one big one). The system can therefore draw in energy from the surroundings (so reducing their entropy) and make it available for doing work.

Self-test 3C. 4 Repeat the calculation for the combustion of $1.000 \mathrm{~mol} \mathrm{CH}_{4}(\mathrm{~g})$ under the same conditions, using data from Table 2C.4.

$$
\text { Answer: }\left|q_{p}\right|=890 \mathrm{~kJ},\left|w_{\max }\right|=813 \mathrm{~kJ}
$$

## (d) Some remarks on the Gibbs energy

The Gibbs energy (the 'free energy') is more common in chemistry than the Helmholtz energy because, at least in laboratory chemistry, we are usually more interested in changes occurring at constant pressure than at constant volume. The criterion $\mathrm{d} G_{T, p} \leq 0$ carries over into chemistry as the observation that, at constant temperature and pressure, chemical reactions are spontaneous in the direction of decreasing Gibbs energy. Therefore, if we want to know whether a reaction is
spontaneous, the pressure and temperature being constant, we assess the change in the Gibbs energy. If $G$ decreases as the reaction proceeds, then the reaction has a spontaneous tendency to convert the reactants into products. If $G$ increases, then the reverse reaction is spontaneous. The criterion for equilibrium, when neither the forward nor reverse process is spontaneous, under conditions of constant temperature and pressure is

$$
\mathrm{d} G_{T, p}=0
$$

The existence of spontaneous endothermic reactions provides an illustration of the role of $G$. In such reactions, $H$ increases, the system rises spontaneously to states of higher enthalpy, and $\mathrm{d} H>0$. Because the reaction is spontaneous we know that $\mathrm{d} G<0$ despite $\mathrm{d} H>0$; it follows that the entropy of the system increases so much that $T \mathrm{~d} S$ outweighs $\mathrm{d} H$ in $\mathrm{d} G=\mathrm{d} H-T \mathrm{~d} S$. Endothermic reactions are therefore driven by the increase of entropy of the system, and this entropy change overcomes the reduction of entropy brought about in the surroundings by the inflow of heat into the system ( $\mathrm{d} S_{\text {sur }}=-\mathrm{d} H / T$ at constant pressure).

## (e) Maximum non-expansion work

The analogue of the maximum work interpretation of $\Delta A$, and the origin of the name 'free energy', can be found for $\Delta G$. In the following Justification, we show that at constant temperature and pressure, the maximum additional (non-expansion) work, $w_{\text {add, } \text { max }}$, is given by the change in Gibbs energy:

$$
\begin{array}{lll}
\mathrm{d} w_{\text {add, } \max }=\mathrm{d} G & \begin{array}{l}
\text { Constant } \\
\text { temperature } \\
\text { and pressure }
\end{array} & \text { Maximum } \\
& \text { non-expansion } & \text { work }
\end{array}
$$

The corresponding expression for a measurable change is

$$
\begin{array}{lll}
w_{\text {add, } \max }=\Delta G & \text { Constant } & \text { Maximum } \\
& \text { temperature } & \text { non-expansion } \\
\text { and pressure } & \text { work }
\end{array}
$$

This expression is particularly useful for assessing the electrical work that may be produced by fuel cells and electrochemical cells, and we shall see many applications of it.

## Justification 3C.2 Maximum non-expansion work

Because $H=U+p V$, the change in enthalpy for a general change in conditions is

$$
\mathrm{d} H=\mathrm{d} q+\mathrm{d} w+\mathrm{d}(p V)
$$

The corresponding change in Gibbs energy ( $G=H-T S$ ) is

$$
\mathrm{d} G=\mathrm{d} H-T \mathrm{~d} S-S \mathrm{~d} T=\mathrm{d} q+\mathrm{d} w+\mathrm{d}(p V)-T \mathrm{~d} S-S \mathrm{~d} T
$$

When the change is isothermal we can set $\mathrm{d} T=0$; then

$$
\mathrm{d} G=\mathrm{d} q+\mathrm{d} w+\mathrm{d}(p V)-T \mathrm{~d} S
$$

When the change is reversible, $\mathrm{d} w=\mathrm{d} w_{\text {rev }}$ and $\mathrm{d} q=\mathrm{d} q_{\text {rev }}=T \mathrm{~d} S$, so for a reversible, isothermal process

$$
\mathrm{d} G=T \mathrm{~d} S+\mathrm{d} w_{\text {rev }}+\mathrm{d}(p V)-T \mathrm{~d} S=\mathrm{d} w_{\text {rev }}+\mathrm{d}(p V)
$$

The work consists of expansion work, which for a reversible change is given by $-p \mathrm{~d} V$, and possibly some other kind of work (for instance, the electrical work of pushing electrons through a circuit or of raising a column of liquid); this additional work we denote $\mathrm{d} w_{\text {add }}$. Therefore, with $\mathrm{d}(p V)=p \mathrm{~d} V+V \mathrm{~d} p$,

$$
\mathrm{d} G=\left(-p \mathrm{~d} V+\mathrm{d} w_{\text {add, rev }}\right)+p \mathrm{~d} V+V \mathrm{~d} p=\mathrm{d} w_{\text {add,rev }}+V \mathrm{~d} p
$$

If the change occurs at constant pressure (as well as constant temperature), we can set $\mathrm{d} p=0$ and obtain $\mathrm{d} G=\mathrm{d} w_{\text {add, rev }}$. Therefore, at constant temperature and pressure, $\mathrm{d} w_{\text {add,rev }}=\mathrm{d} G$. However, because the process is reversible, the work done must now have its maximum value, so eqn 3C. 16 follows.

## Example 3C. 2 Calculating the maximum non-expansion work of a reaction

How much energy is available for sustaining muscular and nervous activity from the combustion of 1.00 mol of glucose molecules under standard conditions at $37^{\circ} \mathrm{C}$ (blood temperature)? The standard entropy of reaction is $+182.4 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$.

Method The non-expansion work available from the reaction is equal to the change in standard Gibbs energy for the reaction ( $\Delta_{\mathrm{r}} G^{\ominus}$, a quantity defined more fully below). To calculate this quantity, it is legitimate to ignore the temperature-dependence of the reaction enthalpy, to obtain $\Delta_{\mathrm{r}} H^{\ominus}$ from Table 2C.5, and to substitute the data into $\Delta_{\mathrm{r}} G^{\ominus}=\Delta_{\mathrm{r}} H^{\ominus}-T \Delta_{\mathrm{r}} S^{\ominus}$.

Answer Because the standard reaction enthalpy is $-2808 \mathrm{~kJ} \mathrm{~mol}^{-1}$, it follows that the standard reaction Gibbs energy is

$$
\begin{aligned}
\Delta_{\mathrm{r}} G^{\ominus} & =-2808 \mathrm{~kJ} \mathrm{~mol}^{-1}-(310 \mathrm{~K}) \times\left(182.4 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \\
& =-2865 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

Therefore, $w_{\text {add, } \max }=-2865 \mathrm{~kJ}$ for the combustion of 1 mol glucose molecules, and the reaction can be used to do up to 2865 kJ of non-expansion work. To place this result in perspective, consider that a person of mass 70 kg needs to do 2.1 kJ of work to climb vertically through 3.0 m ; therefore, at least 0.13 g of glucose is needed to complete the task (and in practice significantly more).

Self-test3C.5 How much non-expansion work can be obtained from the combustion of $1.00 \mathrm{~mol} \mathrm{CH}_{4}(\mathrm{~g})$ under standard conditions at 298 K ? Use $\Delta_{\mathrm{r}} S^{\ominus}=-243 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$.

Answer: 818 kJ

## 3C.2 Standard molar Gibbs energies

Standard entropies and enthalpies of reaction can be combined to obtain the standard Gibbs energy of reaction (or 'standard reaction Gibbs energy'), $\Delta_{\mathrm{r}} G^{\ominus}$ :

$$
\Delta_{\mathrm{r}} G^{\ominus}=\Delta_{\mathrm{r}} H^{\ominus}-T \Delta_{\mathrm{r}} S^{\ominus} \quad \text { Definition }
$$

$$
\begin{aligned}
& \text { Standard Gibbs } \\
& \text { energy of } \\
& \text { reaction }
\end{aligned}
$$

The standard Gibbs energy of reaction is the difference in standard molar Gibbs energies of the products and reactants in their standard states at the temperature specified for the reaction as written.

## (a) Gibbs energies of formation

As in the case of standard reaction enthalpies, it is convenient to define the standard Gibbs energies of formation, $\Delta_{\mathrm{f}} G^{\ominus}$, the standard reaction Gibbs energy for the formation of a compound from its elements in their reference states. ${ }^{2}$ Standard Gibbs energies of formation of the elements in their reference states are zero, because their formation is a 'null' reaction. A selection of values for compounds is given in Table 3C.1. From the values there, it is a simple matter to obtain the standard Gibbs energy of reaction by taking the appropriate combination:

$$
\Delta_{r} G^{\ominus}=\sum_{\text {Products }} \nu \Delta_{\mathrm{f}} G_{\mathrm{m}}^{\ominus}-\sum_{\text {Reactants }} \nu \Delta_{\mathrm{f}} G_{\mathrm{m}}^{\ominus}
$$

$$
\begin{aligned}
& \text { Practical } \\
& \text { implemen- } \\
& \text { tation }
\end{aligned}
$$

In the notation introduced in Topic 2C,

$$
\Delta_{\mathrm{r}} G^{\ominus}=\sum_{\mathrm{J}} v_{\mathrm{J}} \Delta_{\mathrm{f}} G_{\mathrm{m}}^{\ominus}(\mathrm{J})
$$

Table 3C.1* Standard Gibbs energies of formation at $298 \mathrm{~K}, \Delta_{\mathrm{f}} \mathrm{G}^{\ominus} /\left(\mathrm{kJ} \mathrm{mol}^{-1}\right)$
|  | $\Delta_{\mathrm{f}} G^{\ominus} /\left(\mathrm{kJ} \mathrm{mol}^{-1}\right)$ |
| :--- | :--- |
| Diamond, C(s) | +2.9 |
| Benzene, $\mathrm{C}_{6} \mathrm{H}_{6}(\mathrm{l})$ | +124.3 |
| Methane, $\mathrm{CH}_{4}(\mathrm{~g})$ | -50.7 |
| Carbon dioxide, $\mathrm{CO}_{2}(\mathrm{~g})$ | -394.4 |
| Water, $\mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ | -237.1 |
| Ammonia, $\mathrm{NH}_{3}(\mathrm{~g})$ | -16.5 |
| Sodium chloride, $\mathrm{NaCl}(\mathrm{s})$ | -384.1 |


[^8][^9]
## Brief illustration 3C. 4 The standard reaction Gibbs energy

To calculate the standard Gibbs energy of the reaction $\mathrm{CO}(\mathrm{g})+\frac{1}{2} \mathrm{O}_{2}(\mathrm{~g}) \rightarrow \mathrm{CO}_{2}(\mathrm{~g})$ at $25^{\circ} \mathrm{C}$, we write

$$
\begin{aligned}
\Delta_{\mathrm{r}} G^{\ominus} & =\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{CO}_{2}, \mathrm{~g}\right)-\left\{\Delta_{\mathrm{f}} G^{\ominus}(\mathrm{CO}, \mathrm{~g})+\frac{1}{2} \Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{O}_{2}, \mathrm{~g}\right)\right\} \\
& =-394.4 \mathrm{~kJ} \mathrm{~mol}^{-1}-\left\{(-137.2)+\frac{1}{2}(0)\right\} \mathrm{kJ} \mathrm{~mol}^{-1} \\
& =-257.2 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

Self-test 3C. 6 Calculate the standard reaction Gibbs energy for the combustion of $\mathrm{CH}_{4}(\mathrm{~g})$ at 298 K .

Answer: $-818 \mathrm{~kJ} \mathrm{~mol}^{-1}$

Just as is done in Topics 2C and 3B, where it is acknowledged that solutions of cations cannot be prepared without their accompanying anions, we define one ion, conventionally the hydrogen ion, to have zero standard Gibbs energy of formation at all temperatures:

$$
\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{H}^{+}, \mathrm{aq}\right)=0 \quad \text { Convention } \quad \text { lons in solution }
$$

In essence, this definition adjusts the actual values of the Gibbs energies of formation of ions by a fixed amount, which is chosen so that the standard value for one of them, $\mathrm{H}^{+}(\mathrm{aq})$, has the value zero.

## Brief illustration 3C.5 Gibbs energies of formation of ions

For the reaction
$\frac{1}{2} \mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{Cl}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}^{+}(\mathrm{aq})+\mathrm{Cl}^{-}(\mathrm{aq}) \quad \Delta_{\mathrm{r}} \mathrm{G}^{\ominus}=-131.23 \mathrm{~kJ} \mathrm{~mol}^{-1}$
we can write

$$
\Delta_{\mathrm{r}} G^{\ominus}=\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{H}^{+}, \mathrm{aq}\right)+\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{Cl}^{-}, \mathrm{aq}\right)=\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{Cl}^{-}, \mathrm{aq}\right)
$$

and hence identify $\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{Cl}^{-}, \mathrm{aq}\right)$ as $-131.23 \mathrm{~kJ} \mathrm{~mol}^{-1}$.
Self-test 3C. 7 Evaluate $\Delta_{\mathrm{f}} \mathrm{G}^{\ominus}\left(\mathrm{Ag}^{+}, \mathrm{aq}\right)$ from $\mathrm{Ag}(\mathrm{s})+\frac{1}{2} \mathrm{Cl}_{2}(\mathrm{~g}) \rightarrow \mathrm{Ag}^{+}(\mathrm{aq})+\mathrm{Cl}^{-}(\mathrm{aq}), \Delta_{\mathrm{r}} G^{\ominus}=-54.12 \mathrm{~kJ} \mathrm{~mol}^{-1}$

Answer: $+77.11 \mathrm{~kJ} \mathrm{~mol}^{-1}$

The factors responsible for the magnitude of the Gibbs energy of formation of an ion in solution can be identified by analysing it in terms of a thermodynamic cycle. As an illustration, we consider the standard Gibbs energy of formation of $\mathrm{Cl}^{-}$in water, which is $-131 \mathrm{~kJ} \mathrm{~mol}^{-1}$. We do so by treating the formation reaction

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-26.jpg?height=660&width=801&top_left_y=318&top_left_x=318)
Figure 3C. 3 The thermodynamic cycles for the discussion of the Gibbs energies of solvation (hydration) and formation of (a) chloride ions, (b) iodide ions in aqueous solution. The changes in Gibbs energies around the cycle sum to zero because $G$ is a state function.

$$
\frac{1}{2} \mathrm{H}_{2}(\mathrm{~g})+\frac{1}{2} \mathrm{X}_{2}(\mathrm{~g}) \rightarrow \mathrm{H}^{+}(\mathrm{aq})+\mathrm{X}^{-}(\mathrm{aq})
$$

as the outcome of the sequence of steps shown in Fig. 3C.3 (with values taken from the Resource section). The sum of the Gibbs energies for all the steps around a closed cycle is zero, so

$$
\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{Cl}^{-}, \mathrm{aq}\right)=1287 \mathrm{~kJ} \mathrm{~mol}^{-1}+\Delta_{\text {solv }} G^{\ominus}\left(\mathrm{H}^{+}\right)+\Delta_{\text {solv }} G^{\ominus}\left(\mathrm{Cl}^{-}\right)
$$

The standard Gibbs energies of formation of the gas-phase ions are unknown. We have therefore used ionization energies and electron affinities and have assumed that any differences from the Gibbs energies arising from conversion to enthalpy and the inclusion of entropies to obtain Gibbs energies in the formation of $\mathrm{H}^{+}$are cancelled by the corresponding terms in the electron gain of X . The conclusions from the cycles are therefore only approximate. An important point to note is that the value of $\Delta_{\mathrm{f}} G^{\ominus}$ of an ion X is not determined by the properties of X alone but includes contributions from the dissociation, ionization, and hydration of hydrogen.

## (b) The Born equation

Gibbs energies of solvation of individual ions may be estimated from an equation derived by Max Born, who identified $\Delta_{\text {solv }} G^{\ominus}$ with the electrical work of transferring an ion from a vacuum into the solvent treated as a continuous dielectric of relative permittivity $\varepsilon_{\mathrm{r}}$. The resulting Born equation, which is derived in the following Justification, is

$$
\Delta_{\text {solv }} G^{\ominus}=-\frac{z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}}}{8 \pi \varepsilon_{0} r_{\mathrm{i}}}\left(1-\frac{1}{\varepsilon_{\mathrm{r}}}\right) \quad \text { Born equation }
$$

where $z_{\mathrm{i}}$ is the charge number of the ion and $r_{\mathrm{i}}$ its radius ( $N_{\mathrm{A}}$ is Avogadro's constant). Note that $\Delta_{\text {solv }} G^{\ominus}<0$, and that $\Delta_{\text {solv }} G^{\ominus}$ is strongly negative for small, highly charged ions in media of high relative permittivity. For water, for which $\varepsilon_{\mathrm{r}}=78.54$ at $25^{\circ} \mathrm{C}$,

$$
\Delta_{\text {solv }} G^{\ominus}=-\frac{z_{\mathrm{i}}^{2}}{r_{\mathrm{i}} / \mathrm{pm}} \times 6.86 \times 10^{4} \mathrm{~kJ} \mathrm{~mol}^{-1}
$$

## Brief illustration 3C. 6 The Born equation

To see how closely the Born equation reproduces the experimental data, we calculate the difference in the values of $\Delta_{\mathrm{f}} G^{\ominus}$ for $\mathrm{Cl}^{-}$and $\mathrm{I}^{-}$in water at $25^{\circ} \mathrm{C}$, given their radii as 181 pm and 220 pm , respectively, is

$$
\begin{aligned}
\Delta_{\text {solv }} G^{\ominus}\left(\mathrm{Cl}^{-}\right)-\Delta_{\text {solv }} G^{\ominus}\left(\mathrm{I}^{-}\right) & =-\left(\frac{1}{181}-\frac{1}{220}\right) \times 6.86 \times 10^{4} \mathrm{~kJ} \mathrm{~mol}^{-1} \\
& =-67 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

This estimated difference is in good agreement with the experimental difference, which is $-61 \mathrm{~kJ} \mathrm{~mol}^{-1}$.

Self-test3C. 8 Estimate the value of $\Delta_{\text {solv }} G^{\ominus}\left(\mathrm{Cl}^{-}\right)-\Delta_{\text {solv }} G^{\ominus}\left(\mathrm{Br}^{-}\right)$ in water from experimental data and from the Born equation.

Answer: $-26 \mathrm{~kJ} \mathrm{~mol}^{-1}$ experimental; $-29 \mathrm{~kJ} \mathrm{~mol}^{-1}$ calculated

## Justification 3C. 3 The Born equation

The strategy of the calculation is to identify the Gibbs energy of solvation with the work of transferring an ion from a vacuum into the solvent. That work is calculated by taking the difference of the work of charging an ion when it is in the solution and the work of charging the same ion when it is in a vacuum.

The Coulomb interaction between two charges $Q_{1}$ and $Q_{2}$ separated by a distance $r$ is described by the Coulombic potential energy:

$$
V(r)=\frac{Q_{1} Q_{2}}{4 \pi \varepsilon r}
$$

where $\varepsilon$ is the medium's permittivity. The relative permittivity (formerly called the 'dielectric constant') of a substance is defined as $\varepsilon_{\mathrm{r}}=\varepsilon / \varepsilon_{0}$. Ions do not interact as strongly in a solvent of high relative permittivity (such as water, with $\varepsilon_{\mathrm{r}}=80$ at 293 K ) as they do in a solvent of lower relative permittivity (such as ethanol, with $\varepsilon_{\mathrm{r}}=25$ at 293 K ). See Topic 16A for more details. The potential energy of a charge $Q_{1}$ in the presence of a charge $Q_{2}$ can be expressed in terms of the Coulomb potential, $\phi$ :

$$
V(r)=Q_{1} \phi(r) \quad \phi(r)=\frac{Q_{2}}{4 \pi \varepsilon r}
$$

We model an ion as a sphere of radius $r_{\mathrm{i}}$ immersed in a medium of permittivity $\varepsilon$. The charge of the sphere is $Q$, the electric potential, $\phi$, at its surface is the same as the potential due to
a point charge at its centre, so we can use the last expression and write

$$
\phi\left(r_{\mathrm{i}}\right)=\frac{Q}{4 \pi \varepsilon r_{\mathrm{i}}}
$$

The work of bringing up a charge $\mathrm{d} Q$ to the sphere is $\phi\left(r_{\mathrm{i}}\right) \mathrm{d} Q$. Therefore, the total work of charging the sphere from 0 to $z_{i} e$ is

$$
w=\int_{0}^{z_{\mathrm{i}} e} \phi\left(r_{\mathrm{i}}\right) \mathrm{d} Q=\frac{1}{4 \pi \varepsilon r_{\mathrm{i}}} \int_{0}^{z_{\mathrm{i}} e} Q \mathrm{~d} Q=\frac{z_{\mathrm{i}}^{2} e^{2}}{8 \pi \varepsilon r_{\mathrm{i}}}
$$

This electrical work of charging, when multiplied by Avogadro's constant, is the molar Gibbs energy for charging the ions.

The work of charging an ion in a vacuum is obtained by set$\operatorname{ting} \varepsilon=\varepsilon_{0}$, the vacuum permittivity. The corresponding value for charging the ion in a medium is obtained by setting $\varepsilon=\varepsilon_{\mathrm{r}} \varepsilon_{0}$, where $\varepsilon_{\mathrm{r}}$ is the relative permittivity of the medium. It follows
that the change in molar Gibbs energy that accompanies the transfer of ions from a vacuum to a solvent is the difference of these two quantities:

$$
\begin{aligned}
\Delta_{\text {solv }} G^{\ominus} & =\frac{z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}}}{8 \pi \varepsilon r_{\mathrm{i}}}-\frac{z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}}}{8 \pi \varepsilon_{0} r_{\mathrm{i}}}=\frac{z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}}}{8 \pi \varepsilon_{\mathrm{r}} \varepsilon_{0} r_{\mathrm{i}}}-\frac{z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}}}{8 \pi \varepsilon_{0} r_{\mathrm{i}}} \\
& =-\frac{z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}}}{8 \pi \varepsilon_{0} r_{\mathrm{i}}}\left(1-\frac{1}{\varepsilon_{\mathrm{r}}}\right)
\end{aligned}
$$

which is eqn 3B.20.

Calorimetry (for $\Delta H$ directly, and for $S$ via heat capacities) is only one of the ways of determining Gibbs energies. They may also be obtained from equilibrium constants (Topic 6A) and electrochemical measurements (Topic 6D), and for gases they may be calculated using data from spectroscopic observations (Topic 15F).

## Checklist of concepts

□ 1. The Clausius inequality implies a number of criteria for spontaneous change under a variety of conditions that may be expressed in terms of the properties of the system alone; they are summarized by introducing the Helmholtz and Gibbs energies.
□ 2. A spontaneous process at constant temperature and volume is accompanied by a decrease in the Helmholtz energy.
□ 3. The change in the Helmholtz function is equal to the maximum work accompanying a process at constant temperature.
□ 4. A spontaneous process at constant temperature and pressure is accompanied by a decrease in the Gibbs energy.
□ 5. The change in the Gibbs function is equal to the maximum non-expansion work accompanying a process at constant temperature and pressure.
□ 6. Standard Gibbs energies of formation are used to calculate the standard Gibbs energies of reactions.
□ 7. The standard Gibbs energies of formation of ions may be estimated from a thermodynamic cycle and the Born equation.

## Checklist of equations

| Property | Equation |  | Comment | Equation number |
| :--- | :--- | :--- | :--- | :--- |
| Criteria of spontaneity | (a) $\mathrm{d} S_{U, V} \geq 0$ | (b) $\mathrm{d} U_{S, V} \leq 0$ | Constant volume (etc.)* | 3C. 4 |
|  | (a) $\mathrm{d} S_{H, p} \geq 0$ | (b) $\mathrm{d} H_{S, p} \leq 0$ | Constant pressure (etc.) | 3C. 6 |
| Helmholtz energy | $A=U-T S$ |  | Definition | 3C. 7 |
| Gibbs energy | $G=H-T S$ |  | Definition | 3C. 8 |
|  | (a) $\mathrm{d} A_{T, V} \leq 0$ | (b) $\mathrm{d} G_{T, p} \leq 0$ | Constant temperature (etc.) | 3C. 10 |
| Equilibrium | $\mathrm{d} A_{T, V}=0$ |  | Constant volume (etc.) | 3C. 11 |
| Maximum work | $\begin{aligned} & \mathrm{d} w_{\max }=\mathrm{d} A, \\ & w_{\max }=\Delta A \end{aligned}$ |  | Constant temperature | 3C. 12 |


| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Equilibrium | $\mathrm{d} G_{T, p}=0$ | Constant pressure (etc.) | 3C. 15 |
| Maximum non-expansion work | $\begin{aligned} & \mathrm{d} w_{\mathrm{add}, \max }=\mathrm{d} G, \\ & w_{\mathrm{add}, \max }=\Delta G \end{aligned}$ | Constant temperature and pressure | 3C. 16 |
| Standard Gibbs energy of reaction | $\Delta_{\mathrm{r}} G^{\ominus}=\Delta_{\mathrm{r}} H^{\ominus}-T \Delta_{\mathrm{r}} S^{\ominus}$ | Definition | 3C. 17 |
|  | $\Delta_{\mathrm{r}} G^{\ominus}=\sum_{\mathrm{J}} \nu_{\mathrm{J}} \Delta_{\mathrm{f}} G_{\mathrm{m}}^{\ominus}(\mathrm{J})$ | Practical implementation | 3C. 18 |
| Ions in solution | $\Delta_{\mathrm{f}} G^{\ominus}\left(\mathrm{H}^{+}, \mathrm{aq}\right)=0$ | Convention | 3C. 19 |
| Born equation | $\Delta_{\text {solv }} G^{\ominus}=-\left(z_{\mathrm{i}}^{2} e^{2} N_{\mathrm{A}} / 8 \pi \varepsilon_{0} r_{\mathrm{i}}\right)\left(1-1 / \varepsilon_{\mathrm{r}}\right)$ | Solvent a continuum | 3C. 20 |

[^10]
## 3D Combining the First and Second Laws

## Contents

3D. 1 Properties of the internal energy ..... 140
(a) The Maxwell relations ..... 141
Example 3D.1: Using the Maxwell relations ..... 141
(b) The variation of internal energy with volume ..... 141
Example 3D.2: Deriving a thermodynamic relation ..... 142
3D. 2 Properties of the Gibbs energy ..... 142
(a) General considerations ..... 142
Brief illustration 3D.1: The variation of molar Gibbs energy ..... 143
(b) The variation of the Gibbs energy with temperature ..... 144
(c) The variation of the Gibbs energy with pressure ..... 144
Example 3D.3: Evaluating the pressure dependence of a Gibbs energy of transition ..... 145
Brief illustration 3D.2: The pressure dependence of the Gibbs energy of a gas ..... 145
(d) The fugacity ..... 146
Brief illustration 3D.3: The fugacity of a real gas ..... 147
Checklist of concepts ..... 148
Checklist of equations ..... 148

## Why do you need to know this material?

The First and Second Laws of thermodynamics are both relevant to the behaviour of bulk matter, and we can bring the whole force of thermodynamics to bear on a problem by setting up a formulation that combines them.

## What is the key idea?

The fact that infinitesimal changes in thermodynamic functions are exact differentials leads to relations between a variety of properties.

## What do you need to know already?

You need to be aware of the definitions of the state functions $U$ (Topic 2A), $H$ (Topic 2B), $S$ (Topic 3A), and $A$ and $G$ (Topic 3 C ). The mathematical derivations in this Topic draw frequently on the properties of partial derivatives and exact differentials, which are described in Mathematical background 2.

The First Law of thermodynamics may be written $\mathrm{d} U=\mathrm{d} q+\mathrm{d} w$. For a reversible change in a closed system of constant composition, and in the absence of any additional (non-expansion) work, we may set $\mathrm{d} w_{\text {rev }}=-p \mathrm{~d} V$ and (from the definition of entropy) $\mathrm{d} q_{\mathrm{rev}}=T \mathrm{~d} S$, where $p$ is the pressure of the system and $T$ its temperature. Therefore, for a reversible change in a closed system,

$$
\mathrm{d} U=T \mathrm{~d} S-p \mathrm{~d} V
$$

The fundamental equation

However, because $\mathrm{d} U$ is an exact differential, its value is independent of path. Therefore, the same value of $\mathrm{d} U$ is obtained whether the change is brought about irreversibly or reversibly. Consequently, eqn 3D. 1 applies to any change-reversible or irreversible-of a closed system that does no additional (nonexpansion) work. We shall call this combination of the First and Second Laws the fundamental equation.

The fact that the fundamental equation applies to both reversible and irreversible changes may be puzzling at first sight. The reason is that only in the case of a reversible change may $T \mathrm{~d} S$ be identified with $\mathrm{d} q$ and $-p \mathrm{~d} V$ with $\mathrm{d} w$. When the change is irreversible, $T \mathrm{~d} S>\mathrm{d} q$ (the Clausius inequality) and $-p \mathrm{~d} V>\mathrm{d} w$. The sum of $\mathrm{d} w$ and $\mathrm{d} q$ remains equal to the sum of $T \mathrm{~d} S$ and $-p \mathrm{~d} V$, provided the composition is constant.

## 3D. 1 Properties of the internal energy

Equation 3D. 1 shows that the internal energy of a closed system changes in a simple way when either $S$ or $V$ is changed ( $\mathrm{d} U \propto \mathrm{~d} S$ and $\mathrm{d} U \propto \mathrm{~d} V$ ). These simple proportionalities suggest that $U$ is best regarded as a function of $S$ and $V$. We could regard $U$ as a function of other variables, such as $S$ and $p$ or $T$ and $V$, because they are all interrelated; but the simplicity of the fundamental equation suggests that $U(S, V)$ is the best choice.

The mathematical consequence of $U$ being a function of $S$ and $V$ is that we can express an infinitesimal change $\mathrm{d} U$ in terms of changes $\mathrm{d} S$ and $\mathrm{d} V$ by

$$
\mathrm{d} U=\left(\frac{\partial U}{\partial S}\right)_{V} \mathrm{~d} S+\left(\frac{\partial U}{\partial V}\right)_{S} \mathrm{~d} V
$$

The two partial derivatives are the slopes of the plots of $U$ against $S$ and $V$, respectively. When this expression is compared
term-by-term to the thermodynamic relation, eqn 3D.1, we see that for systems of constant composition,

$$
\left(\frac{\partial U}{\partial S}\right)_{V}=T \quad\left(\frac{\partial U}{\partial V}\right)_{S}=-p
$$

The first of these two equations is a purely thermodynamic definition of temperature as the ratio of the changes in the internal energy (a First-Law concept) and entropy (a SecondLaw concept) of a constant-volume, closed, constant-composition system. We are beginning to generate relations between the properties of a system and to discover the power of thermodynamics for establishing unexpected relations.

## (a) The Maxwell relations

An infinitesimal change in a function $f(x, y)$ can be written $\mathrm{d} f=g \mathrm{~d} x+h \mathrm{~d} y$, where $g$ and $h$ may be functions of $x$ and $y$. The mathematical criterion for $\mathrm{d} f$ being an exact differential (in the sense that its integral is independent of path) is that

$$
\left(\frac{\partial g}{\partial y}\right)_{x}=\left(\frac{\partial h}{\partial x}\right)_{y}
$$

This criterion is discussed in Mathematical background 2. Because the fundamental equation, eqn 3D.1, is an expression for an exact differential, the functions multiplying $\mathrm{d} S$ and $\mathrm{d} V$ (namely $T$ and $-p$ ) must pass this test. Therefore, it must be the case that

$$
\left(\frac{\partial T}{\partial V}\right)_{S}=-\left(\frac{\partial p}{\partial S}\right)_{V}
$$

A Maxwell relation
(3D.5)

We have generated a relation between quantities which, at first sight, would not seem to be related.

Equation 3D. 5 is an example of a Maxwell relation. However, apart from being unexpected, it does not look particularly interesting. Nevertheless, it does suggest that there might be other similar relations that are more useful. Indeed, we can use the fact that $H, G$, and $A$ are all state functions to derive three more Maxwell relations. The argument to obtain them runs in the same way in each case: because $H, G$, and $A$ are state functions, the expressions for $\mathrm{d} H, \mathrm{~d} G$, and $\mathrm{d} A$ satisfy relations like eqn 3D.4. All four relations are listed in Table 3D.1.

## Example 3D. 1 Using the Maxwell relations

Use the Maxwell relations in Table 3D. 1 to show that the entropy of a perfect gas is proportional to $\ln V$.

Method The natural place to start, given that you are invited to use the Maxwell relations, is by considering the relation for $(\partial S / \partial V)_{T}$, as that differential coefficient shows how the entropy
varies with volume at constant temperature. Be alert for an opportunity to use the perfect gas equation of state.

Answer From Table 3D.1,

$$
\left(\frac{\partial S}{\partial V}\right)_{T}=\left(\frac{\partial p}{\partial T}\right)_{V}
$$

Now use the perfect gas equation of state to write

$$
\left(\frac{\partial p}{\partial T}\right)_{V}=\left(\frac{\partial(n R T / V)}{\partial T}\right)_{V}=\frac{n R}{V}
$$

At this point, we can write

$$
\left(\frac{\partial S}{\partial V}\right)_{T}=\frac{n R}{V}
$$

and therefore, at constant temperature

$$
\int \mathrm{d} S=n R \int \frac{\mathrm{~d} V}{V}=n R \ln V+\text { constant }
$$

The integral of the left is $S+$ constant, which completes the demonstration.

Self-test 3D.1 How does the entropy depend on the volume of a van der Waals gas? Discuss.

Answer: $S$ varies as $n R \ln (V-n b)$; molecules in a smaller available volume

Table 3D. 1 The Maxwell relations
| State function | Exact differential | Maxwell relation |
| :--- | :--- | :--- |
| $U$ | $\mathrm{d} U=T \mathrm{~d} S-p \mathrm{~d} V$ | $\left(\frac{\partial T}{\partial V}\right)_{S}=-\left(\frac{\partial p}{\partial S}\right)_{V}$ |
| H | $\mathrm{d} H=T \mathrm{~d} S+V \mathrm{~d} p$ | $\left(\frac{\partial T}{\partial p}\right)_{S}=\left(\frac{\partial V}{\partial S}\right)_{p}$ |
| A | $\mathrm{d} A=-p \mathrm{~d} V-S \mathrm{~d} T$ | $\left(\frac{\partial p}{\partial T}\right)_{V}=\left(\frac{\partial S}{\partial V}\right)_{T}$ |
| G | $\mathrm{d} G=V \mathrm{~d} p-S \mathrm{~d} T$ | $\left(\frac{\partial V}{\partial T}\right)_{p}=-\left(\frac{\partial S}{\partial p}\right)_{T}$ |


## (b) The variation of internal energy with volume

The quantity $\pi_{T}=(\partial U / \partial V)_{T}$, which represents how the internal energy changes as the volume of a system is changed isothermally, plays a central role in the manipulation of the First Law, and in Topic 2D we use the relation

$$
\pi_{T}=T\left(\frac{\partial p}{\partial T}\right)_{V}-p \quad \text { A thermodynamic equation of state }
$$

This relation is called a thermodynamic equation of state because it is an expression for pressure in terms of a variety of thermodynamic properties of the system. We are now ready to derive it by using a Maxwell relation.

Justification 3D. 1 The thermodynamic equation of state
We obtain an expression for the coefficient $\pi_{T}$ by dividing both sides of eqn 3D. 1 by $\mathrm{d} V$, imposing the constraint of constant temperature, which gives

$$
\overbrace{\left(\frac{\partial U}{\partial V}\right)_{T}}^{\pi_{T}}=\overbrace{\left(\frac{\partial U}{\partial S}\right)_{V}}^{T}\left(\frac{\partial S}{\partial V}\right)_{T}+\overbrace{\left(\frac{\partial U}{\partial V}\right)_{S}}^{p}
$$

Next, we introduce the two relations in eqn 3D. 3 (as indicated by the annotations) and the definition of $\pi_{T}$ to obtain

$$
\pi_{T}=T\left(\frac{\partial S}{\partial V}\right)_{T}-p
$$

The third Maxwell relation in Table 3D. 1 turns $(\partial S / \partial V)_{T}$ into $(\partial p / \partial T)_{V}$, which completes the derivation of eqn 3D.6.

## Example 3D. 2 Deriving a thermodynamic relation

Show thermodynamically that $\pi_{T}=0$ for a perfect gas, and compute its value for a van der Waals gas.
Method Proving a result 'thermodynamically' means basing it entirely on general thermodynamic relations and equations of state, without drawing on molecular arguments (such as the existence of intermolecular forces). We know that for a perfect gas, $p=n R T / V$, so this relation should be used in eqn 3D.6. Similarly, the van der Waals equation is given in Table 1C.3, and for the second part of the question it should be used in eqn 3D.6.

Answer For a perfect gas we write

$$
\left(\frac{\partial p}{\partial T}\right)_{V}=\left(\frac{\partial n R T / V}{\partial T}\right)_{V}=\frac{n R}{V}
$$

Then, eqn 3D. 6 becomes

$$
\pi_{T}=\frac{n R T}{V}-p=0
$$

The equation of state of a van der Waals gas is

$$
p=\frac{n R T}{V-n b}-a \frac{n^{2}}{V^{2}}
$$

Because $a$ and $b$ are independent of temperature,

$$
\left(\frac{\partial p}{\partial T}\right)_{V}=\left(\frac{\partial n R T /(V-n b)}{\partial T}\right)_{V}=\frac{n R}{V-n b}
$$

Therefore, from eqn 3D.6,

$$
\pi_{T}=\frac{n R T}{V-n b}-p=\frac{n R T}{V-n b}-\left(\frac{n R T}{V-n b}-a \frac{n^{2}}{V^{2}}\right)=a \frac{n^{2}}{V^{2}}
$$

This result for $\pi_{T}$ implies that the internal energy of a van der Waals gas increases when it expands isothermally (that is, $(\partial U / \partial V)_{T}>0$ ), and that the increase is related to the parameter $a$, which models the attractive interactions between the particles. A larger molar volume, corresponding to a greater average separation between molecules, implies weaker mean intermolecular attractions, so the total energy is greater.

Self-test 3D.2 Calculate $\pi_{T}$ for a gas that obeys the virial equation of state (Table 1C.3).

$$
\text { Answer: } \pi_{T}=R T^{2}(\partial B / \partial T)_{V} / V_{\mathrm{m}}^{2}+\cdots
$$

## 3D.2 Properties of the Gibbs energy

The same arguments that we have used for $U$ can be used for the Gibbs energy $G=H-T S$. They lead to expressions showing how $G$ varies with pressure and temperature that are important for discussing phase transitions and chemical reactions.

## (a) General considerations

When the system undergoes a change of state, $G$ may change because $H, T$, and $S$ all change and

$$
\mathrm{d} G=\mathrm{d} H-\mathrm{d}(T S)=\mathrm{d} H-T \mathrm{~d} S-S \mathrm{~d} T
$$

Because $H=U+p V$, we know that

$$
\mathrm{d} H=\mathrm{d} U+\mathrm{d}(p V)=\mathrm{d} U+p \mathrm{~d} V+V \mathrm{~d} p
$$

and therefore

$$
\mathrm{d} G=\mathrm{d} U+p \mathrm{~d} V+V \mathrm{~d} p-T \mathrm{~d} S-S \mathrm{~d} T
$$

For a closed system doing no non-expansion work, we can replace $\mathrm{d} U$ by the fundamental equation $\mathrm{d} U=T \mathrm{~d} S-p \mathrm{~d} V$ and obtain

$$
\mathrm{d} G=T \mathrm{~d} S-p \mathrm{~d} V+p \mathrm{~d} V+V \mathrm{~d} p-T \mathrm{~d} S-S \mathrm{~d} T
$$

Four terms now cancel on the right, and we conclude that for a closed system in the absence of non-expansion work and at constant composition

$$
\mathrm{d} G=V \mathrm{~d} p-S \mathrm{~d} T
$$

This expression, which shows that a change in $G$ is proportional to a change in $p$ or $T$, suggests that $G$ may be best regarded as a function of $p$ and $T$. It may be regarded as the fundamental equation of chemical thermodynamics as it is so central to the application of thermodynamics to chemistry: it suggests that $G$ is an important quantity in chemistry because the pressure and temperature are usually the variables under our control. In other words, $G$ carries around the combined consequences of the First and Second Laws in a way that makes it particularly suitable for chemical applications.

The same argument that led to eqn 3D.3, when applied to the exact differential $\mathrm{d} G=V \mathrm{~d} p-S \mathrm{~d} T$, now gives

$$
\left(\frac{\partial G}{\partial T}\right)_{p}=-S \quad\left(\frac{\partial G}{\partial p}\right)_{T}=V
$$

These relations show how the Gibbs energy varies with temperature and pressure (Fig. 3D.1). The first implies that:

- Because $S>0$ for all substances, $G$ always decreases when the temperature is raised (at constant pressure and composition).
- Because $(\partial G / \partial T)_{p}$ becomes more negative as $S$ increases, $G$ decreases most sharply with increasing temperature when the entropy of the system is large.

Therefore, the Gibbs energy of the gaseous phase of a substance, which has a high molar entropy, is more sensitive to temperature than its liquid and solid phases (Fig. 3D.2). Similarly, the second relation implies that:

- Because $V>0$ for all substances, $G$ always increases when the pressure of the system is increased (at constant temperature and composition).
Physical interpretation

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-32.jpg?height=513&width=627&top_left_y=1902&top_left_x=405)
Figure 3D. 1 The variation of the Gibbs energy of a system with (a) temperature at constant pressure and (b) pressure at constant temperature. The slope of the former is equal to the negative of the entropy of the system and that of the latter is equal to the volume.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-32.jpg?height=466&width=766&top_left_y=314&top_left_x=1262)
Figure 3D. 2 The variation of the Gibbs energy with the temperature is determined by the entropy. Because the entropy of the gaseous phase of a substance is greater than that of the liquid phase, and the entropy of the solid phase is smallest, the Gibbs energy changes most steeply for the gas phase, followed by the liquid phase, and then the solid phase of the substance.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-32.jpg?height=466&width=764&top_left_y=1116&top_left_x=1264)
Figure 3D. 3 The variation of the Gibbs energy with the pressure is determined by the volume of the sample. Because the volume of the gaseous phase of a substance is greater than that of the same amount of liquid phase, and the entropy of the solid phase is smallest (for most substances), the Gibbs energy changes most steeply for the gas phase, followed by the liquid phase, and then the solid phase of the substance. Because the volumes of the solid and liquid phases of a substance are similar, their molar Gibbs energies vary by similar amounts as the pressure is changed.

- Because $(\partial G / \partial p)_{T}$ increases with $V, G$ is more sensitive to pressure when the volume of the system is large.

Because the molar volume of the gaseous phase of a substance is greater than that of its condensed phases, the molar Gibbs energy of a gas is more sensitive to pressure than its liquid and solid phases (Fig. 3D.3).

## Brief illustration 3D. 1 The variation of molar Gibbs energy

The standard molar entropy of liquid water at 298 K is $69.91 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. It follows that when the temperature is increased by 5.0 K , the molar Gibbs energy changes by

$$
\begin{aligned}
\delta G_{\mathrm{m}} & \approx\left(\frac{\partial G_{\mathrm{m}}}{\partial T}\right)_{p} \delta T=-S_{\mathrm{m}} \delta T=-\left(69.91 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times(5.0 \mathrm{~K}) \\
& =-0.35 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

Self-test 3D. 3 The mass density of liquid water is $0.9970 \mathrm{~g} \mathrm{~cm}^{-3}$ at 298 K . By how much does its molar Gibbs energy change when the pressure is increased by 0.10 bar?

Answer: $+0.18 \mathrm{~J} \mathrm{~mol}^{-1}$

## (b) The variation of the Gibbs energy with temperature

Because the equilibrium composition of a system depends on the Gibbs energy, to discuss the response of the composition to temperature we need to know how $G$ varies with temperature.

The first relation in eqn 3D.8, $(\partial G / \partial T)_{p}=-S$, is our starting point for this discussion. Although it expresses the variation of $G$ in terms of the entropy, we can express it in terms of the enthalpy by using the definition of $G$ to write $S=(H-G) / T$. Then

$$
\left(\frac{\partial G}{\partial T}\right)_{p}=\frac{G-H}{T}
$$

In Topic 6A it is shown that the equilibrium constant of a reaction is related to $G / T$ rather than to $G$ itself, and it is easy to deduce from the last equation (see the following Justification) that

$$
\left(\frac{\partial G / T}{\partial T}\right)_{p}=-\frac{H}{T^{2}} \quad \text { Gibbs-Helmholtz equation }
$$

This expression is called the Gibbs-Helmholtz equation. It shows that if we know the enthalpy of the system, then we know how $G / T$ varies with temperature.

## Justification 3D. 2 The Gibbs-Helmholtz equation

First, we note that

$$
\begin{aligned}
\left(\frac{\partial G / T}{\partial T}\right)_{p} & =\frac{1}{T}\left(\frac{\partial G}{\partial T}\right)_{p}+G \frac{\mathrm{~d}(1 / T)}{\mathrm{d} T}=\frac{1}{T}\left(\frac{\partial G}{\partial T}\right)_{p}-\frac{G}{T^{2}} \\
& =\frac{1}{T}\left\{\left(\frac{\partial G}{\partial T}\right)_{p}-\frac{G}{T}\right\}
\end{aligned}
$$

Then we use eqn 3D. 9 to write

$$
\left(\frac{\partial G}{\partial T}\right)_{p}-\frac{G}{T}=\frac{G-H}{T}-\frac{G}{T}=-\frac{H}{T}
$$

When this expression is substituted in the preceding one, we obtain eqn 3D.10.

The Gibbs-Helmholtz equation is most useful when it is applied to changes, including changes of physical state and chemical reactions at constant pressure. Then, because $\Delta G=G_{\mathrm{f}}-G_{\mathrm{i}}$ for the change of Gibbs energy between the final and initial states and because the equation applies to both $G_{\mathrm{f}}$ and $G_{\mathrm{i}}$, we can write

$$
\left(\frac{\partial \Delta G / T}{\partial T}\right)_{p}=-\frac{\Delta H}{T^{2}}
$$

This equation shows that if we know the change in enthalpy of a system that is undergoing some kind of transformation (such as vaporization or reaction), then we know how the corresponding change in Gibbs energy varies with temperature. As we shall see, this is a crucial piece of information in chemistry.

## (c) The variation of the Gibbs energy with pressure

To find the Gibbs energy at one pressure in terms of its value at another pressure, the temperature being constant, we set $\mathrm{d} T=0$ in eqn 3D.7, which gives $\mathrm{d} G=V \mathrm{~d} p$, and integrate:

$$
G\left(p_{\mathrm{f}}\right)=G\left(p_{\mathrm{i}}\right)+\int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} V \mathrm{~d} p
$$

For molar quantities,

$$
G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+\int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} V_{\mathrm{m}} \mathrm{~d} p
$$

This expression is applicable to any phase of matter, but to evaluate it we need to know how the molar volume, $V_{\mathrm{m}}$, depends on the pressure.

The molar volume of a condensed phase changes only slightly as the pressure changes (Fig. 3D.4), so we can treat $V_{\mathrm{m}}$ as a constant and take it outside the integral:

$$
G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+V_{\mathrm{m}} \int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} \mathrm{~d} p
$$

That is,

$$
G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+\left(p_{\mathrm{f}}-p_{\mathrm{i}}\right) V_{\mathrm{m}} \quad \begin{aligned}
& \text { Incompressible } \\
& \text { solid or liquid }
\end{aligned} \quad \begin{aligned}
& \text { Molar } \\
& \text { Gibbs } \\
& \text { energy }
\end{aligned}
$$

Under normal laboratory conditions $\left(p_{\mathrm{f}}-p_{\mathrm{i}}\right) V_{\mathrm{m}}$ is very small and may be neglected. Hence, we may usually suppose that the Gibbs energies of solids and liquids are independent of pressure. However, if we are interested in geophysical problems, then because pressures in the Earth's interior are huge, their effect on the Gibbs energy cannot be ignored. If the pressures are so great that there are substantial volume changes over the range of integration, then we must use the complete expression, eqn 3D.12.

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-34.jpg?height=487&width=787&top_left_y=318&top_left_x=328)
Figure 3D. 4 The difference in Gibbs energy of a solid or liquid at two pressures is equal to the rectangular area shown. We have assumed that the variation of volume with pressure is negligible.

## Example 3D. 3 Evaluating the pressure dependence of a Gibbs energy of transition

Suppose that for a certain phase transition of a solid $\Delta_{\mathrm{trs}} V=+1.0 \mathrm{~cm}^{3} \mathrm{~mol}^{-1}$ is independent of pressure. By how much does that Gibbs energy of transition change when the pressure is increased from $1.0 \mathrm{bar}\left(1.0 \times 10^{5} \mathrm{~Pa}\right)$ to 3.0 Mbar $\left(3.0 \times 10^{11} \mathrm{~Pa}\right) ?$

Method Start with eqn 3D.12b to obtain expressions for the Gibbs energy of each of the phases 1 and 2 of the solid

$$
\begin{aligned}
& G_{\mathrm{m}, 1}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}, 1}\left(p_{\mathrm{i}}\right)+\int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} V_{\mathrm{m}, 1} \mathrm{~d} p \\
& G_{\mathrm{m}, 2}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}, 2}\left(p_{\mathrm{i}}\right)+\int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} V_{\mathrm{m}, 2} \mathrm{~d} p
\end{aligned}
$$

Now subtract the second expression from the first, noting that $G_{\mathrm{m}, 2}-G_{\mathrm{m}, 1}=\Delta_{\mathrm{trs}} G$ and $V_{\mathrm{m}, 2}-V_{\mathrm{m}, 1}=\Delta_{\mathrm{trs}} V$ :

$$
\Delta_{\mathrm{trs}} G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=\Delta_{\mathrm{trs}} G_{\mathrm{m}}\left(p_{i}\right)+\int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} \Delta_{\mathrm{trs}} V_{\mathrm{m}} \mathrm{~d} p
$$

Use the data to complete the calculation.
Answer Because $\Delta_{\text {trs }} V$ is independent of pressure, the expression above simplifies to

$$
\begin{aligned}
\Delta_{\mathrm{trs}} G_{\mathrm{m}}\left(p_{\mathrm{f}}\right) & =\Delta_{\mathrm{trs}} G_{\mathrm{m}}\left(p_{i}\right)+\Delta_{\mathrm{trs}} V_{\mathrm{m}} \int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} \mathrm{~d} p \\
& =\Delta_{\mathrm{trs}} G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+\Delta_{\mathrm{trs}} V_{\mathrm{m}}\left(p_{\mathrm{f}}-p_{\mathrm{i}}\right)
\end{aligned}
$$

Inserting the data gives

$$
\begin{aligned}
\Delta_{\mathrm{trs}} G(3 \mathrm{Mbar})= & \Delta_{\mathrm{trs}} G(1 \mathrm{bar})+\left(1.0 \times 10^{-6} \mathrm{~m}^{3} \mathrm{~mol}^{-1}\right) \times \\
& \left(3.0 \times 10^{11} \mathrm{~Pa}-1.0 \times 10^{5} \mathrm{~Pa}\right) \\
= & \Delta_{\mathrm{trs}} G(1 \mathrm{bar})+3.0 \times 10^{2} \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

where we have used $1 \mathrm{Pam}^{3}=1 \mathrm{~J}$.

Self-test 3D. 4 Calculate the change in $G_{\mathrm{m}}$ for ice at $-10^{\circ} \mathrm{C}$, with density $917 \mathrm{~kg} \mathrm{~m}^{-3}$, when the pressure is increased from 1.0 bar to 2.0 bar.

Answer: $+2.0 \mathrm{~J} \mathrm{~mol}^{-1}$

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-34.jpg?height=463&width=755&top_left_y=592&top_left_x=1266)
Figure 3D. 5 The difference in Gibbs energy for a perfect gas at two pressures is equal to the area shown below the perfect-gas isotherm.

The molar volumes of gases are large, so the Gibbs energy of a gas depends strongly on the pressure. Furthermore, because the volume also varies markedly with the pressure, we cannot treat it as a constant in the integral in eqn 3D.12b (Fig. 3D.5). For a perfect gas we substitute $V_{\mathrm{m}}=R T / p$ into the integral, treat $R T$ as a constant, and find

$$
G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+R T \int_{p_{\mathrm{i}}}^{p_{\mathrm{f}}} \frac{1}{p} \mathrm{~d} p=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+R T \ln \frac{p_{\mathrm{f}}}{p_{\mathrm{i}}}
$$

This expression shows that when the pressure is increased tenfold at room temperature, the molar Gibbs energy increases by $R T \ln 10 \approx 6 \mathrm{~kJ} \mathrm{~mol}^{-1}$. It also follows from this equation that if we set $p_{\mathrm{i}}=p^{\ominus}$ (the standard pressure of 1 bar), then the molar Gibbs energy of a perfect gas at a pressure $p$ (set $p_{\mathrm{f}}=p$ ) is related to its standard value by

$$
G_{\mathrm{m}}(p)=G_{\mathrm{m}}^{\ominus}+R T \ln \frac{p}{p^{\ominus}}
$$

## Perfect gas

energy

## Brief illustration 3D. 2 The pressure dependence of the Gibbs energy of a gas

Suppose we are interested in the molar Gibbs energy of water vapour (treated as a perfect gas) when the pressure is increased isothermally from 1.0 bar to 2.0 bar at 298 K . According to eqn 3D. 14

$$
\begin{aligned}
G_{\mathrm{m}}(2.0 \text { bar })= & G_{\mathrm{m}}^{\ominus}(1.0 \text { bar })+\left(8.3145 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \times(298 \mathrm{~K}) \times \\
& \ln \left(\frac{2.0 \text { bar }}{1.0 \text { bar }}\right)=G_{\mathrm{m}}^{\ominus}(1.0 \text { bar })+1.7 \mathrm{~kJ} \mathrm{~mol}^{-1}
\end{aligned}
$$

Note that whereas the change in molar Gibbs energy for a condensed phase is a few joules per mole, for a gas the change is of the order of kilojoules per mole

Self-test 3D.5 By how much does the molar Gibbs energy of a perfect gas differ from its standard value at 298 K when its pressure is 0.10 bar?

Answer: $-5.7 \mathrm{~kJ} \mathrm{~mol}^{-1}$

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-35.jpg?height=496&width=796&top_left_y=735&top_left_x=282)
Figure 3D. 6 The molar Gibbs energy of a perfect gas varies as $\ln p$, and the standard state is reached at $p^{\ominus}$. Note that, as $p \rightarrow 0$, the molar Gibbs energy becomes negatively infinite.

The logarithmic dependence of the molar Gibbs energy on the pressure predicted by eqn 3D. 15 is illustrated in Fig. 3D.6. This very important expression, the consequences of which we unfold in the following chapters, applies to perfect gases (which is usually a good enough approximation). The following section shows how to accommodate imperfections.

## (d) The fugacity

At various stages in the development of physical chemistry it is necessary to switch from a consideration of idealized systems to real systems. In many cases it is desirable to preserve the form of the expressions that have been derived for an idealized system. Then deviations from the idealized behaviour can be expressed most simply. For instance, the pressure-dependence of the molar Gibbs energy of a real gas might resemble that shown in Fig. 3D.7. To adapt eqn 3D. 14 to this case, we replace the true pressure, $p$, by an effective pressure, called the fugacity, ${ }^{1} f$, and write

$$
G_{\mathrm{m}}=G_{\mathrm{m}}^{\ominus}+R T \ln \left(f / p^{\ominus}\right) \quad \text { Definition Fugacity }
$$

The fugacity, a function of the pressure and temperature, is defined so that this relation is exactly true. A very similar approach is taken in the discussion of real solutions (Topic 5E),

[^11]![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-35.jpg?height=473&width=755&top_left_y=318&top_left_x=1225)
Figure 3D. 7 The molar Gibbs energy of a real gas. As $p \rightarrow 0$, the molar Gibbs energy coincides with the value for a perfect gas (shown by the purple line). When attractive forces are dominant (at intermediate pressures), the molar Gibbs energy is less than that of a perfect gas and the molecules have a lower 'escaping tendency'. At high pressures, when repulsive forces are dominant, the molar Gibbs energy of a real gas is greater than that of a perfect gas. Then the 'escaping tendency' is increased.

where 'activities' are effective concentrations. Indeed, $f / p^{\ominus}$ may be regarded as a gas-phase activity.

Although thermodynamic expressions in terms of fugacities derived from this expression are exact, they are useful only if we know how to interpret fugacities in terms of actual pressures. To develop this relation we write the fugacity as

$$
f=\phi p
$$

Definition Fugacity coefficient
where $\phi$ is the dimensionless fugacity coefficient, which in general depends on the temperature, the pressure, and the identity of the gas. We show in the following Justification that the fugacity coefficient is related to the compression factor, $Z$, of a gas (Topic 1C) by

$$
\ln \phi=\int_{0}^{p} \frac{Z-1}{p} \mathrm{~d} p
$$

Provided we know how $Z$ varies with pressure up to the pressure of interest, this expression enable us to determine the fugacity coefficient and hence, through eqn 3D.17, to relate the fugacity to the pressure of the gas.

## Justification 3D. 3 The fugacity coefficient

Equation 3D.12a is true for all gases whether real or perfect. Expressing it in terms of the fugacity by using eqn 3D. 16 turns it into

$$
\begin{aligned}
\int_{p^{\prime}}^{p} V_{\mathrm{m}} \mathrm{~d} p=G_{\mathrm{m}}(p)-G_{\mathrm{m}}\left(p^{\prime}\right)= & \left\{G_{\mathrm{m}}^{\ominus}+R T \ln \frac{f}{p^{\ominus}}\right\}- \\
& \left\{G_{\mathrm{m}}^{\ominus}+R T \ln \frac{f^{\prime}}{p^{\ominus}}\right\}=R T \ln \frac{f}{f^{\prime}}
\end{aligned}
$$

In this expression, $f$ is the fugacity when the pressure is $p$ and $f^{\prime}$ is the fugacity when the pressure is $p^{\prime}$. If the gas were perfect, we would write

$$
\int_{p^{\prime}}^{p} \overbrace{V_{\text {perfect }, \mathrm{m}}}^{R T / p} \mathrm{~d} p=R T \int_{p^{\prime}}^{p} \frac{1}{p} \mathrm{~d} p=R T \ln \frac{p}{p^{\prime}}
$$

The difference between the two equations is

$$
\begin{aligned}
\int_{p^{\prime}}^{p}\left(V_{\mathrm{m}}-V_{\text {perfect }, \mathrm{m}}\right) \mathrm{d} p & =R T\left(\ln \frac{f}{f^{\prime}}-\ln \frac{p}{p^{\prime}}\right)=R T \ln \frac{f / f^{\prime}}{p / p^{\prime}} \\
& =R T \ln \frac{f / p}{f^{\prime} / p^{\prime}}
\end{aligned}
$$

which can be rearranged into

$$
\ln \frac{f / p}{f^{\prime} / p^{\prime}}=\frac{1}{R T} \int_{p^{\prime}}^{p}\left(V_{\mathrm{m}}-V_{\text {perfect }, \mathrm{m}}\right) \mathrm{d} p
$$

When $p^{\prime} \rightarrow 0$, the gas behaves perfectly and $f^{\prime}$ becomes equal to the pressure, $p^{\prime}$. Therefore, $f^{\prime} / p^{\prime} \rightarrow 1$ as $p^{\prime} \rightarrow 0$. If we take this limit, which means setting $f^{\prime} / p^{\prime}=1$ on the left and $p^{\prime}=0$ on the right, the last equation becomes

$$
\ln \frac{f}{p}=\frac{1}{R T} \int_{0}^{p}\left(V_{\mathrm{m}}-V_{\text {perfect, } \mathrm{m}}\right) \mathrm{d} p
$$

Then, with $\phi=f / p$,

$$
\ln \phi=\frac{1}{R T} \int_{0}^{p}\left(V_{\mathrm{m}}-V_{\text {perfect }, \mathrm{m}}\right) \mathrm{d} p
$$

For a perfect gas, $V_{\text {perfect, } \mathrm{m}}=R T / p$. For a real gas, $V_{\mathrm{m}}=R T Z / p$, where $Z$ is the compression factor of the gas (Topic 1C). With these two substitutions, we obtain eqn 3D.18.

For a perfect gas, $\phi=1$ at all pressures and temperatures. We know from Fig. 1C. 9 that for most gases $Z<1$ up to moderate pressures, but that $Z>1$ at higher pressures. If $Z<1$ throughout the range of integration, then the integrand in eqn 3D. 18 is negative and $\phi<1$. This value implies that $f<p$ (the molecules tend to stick together) and that the molar Gibbs energy of the gas is less than that of a perfect gas. At higher pressures, the range over which $Z>1$ may dominate the range over which $Z<1$. The integral is then positive, $\phi>1$, and $f>p$ (the repulsive interactions are dominant and tend to drive the particles apart). Now the molar Gibbs energy of the gas is greater than that of the perfect gas at the same pressure.

Figure 3D.8, which has been calculated using the full van der Waals equation of state, shows how the fugacity coefficient depends on the pressure in terms of the reduced variables

![](https://cdn.mathpix.com/cropped/ba3070c5-84cf-4ad7-89bd-19e91704c8f6-36.jpg?height=664&width=880&top_left_y=314&top_left_x=1205)
Figure 3D. 8 The fugacity coefficient of a van der Waals gas plotted using the reduced variables of the gas. The curves are labelled with the reduced temperature $T_{\mathrm{r}}=T / T_{\mathrm{c}}$.

Table 3D.2* The fugacity of nitrogen at 273 K , f/atm
| $p /$ atm | $f /$ atm |
| :--- | :--- |
| 1 | 0.99955 |
| 10 | 9.9560 |
| 100 | 97.03 |
| 1000 | 1839 |


* More values are given in the Resource section.
(Topic 1C). Because critical constants are available in Table 1C.2, the graphs can be used for quick estimates of the fugacities of a wide range of gases. Table 3D. 2 gives some explicit values for nitrogen.


## Brief illustration 3D. 3 The fugacity of a real gas

To use Fig. 3D. 8 to estimate the fugacity of carbon dioxide at 400 K and 400 atm , we note from Table 1C. 2 that its critical constants are $p_{\mathrm{c}}=72.85 \mathrm{~atm}$ and $T_{\mathrm{c}}=304.2 \mathrm{~K}$. In terms of reduced variables, the gas has $p_{\mathrm{r}}=(400 \mathrm{~atm}) /(72.85 \mathrm{~atm})=5.5$ and $T_{\mathrm{r}}=(400 \mathrm{~K}) /(304.2 \mathrm{~K})=1.31$. From Fig. 3D. 8 (interpolating by eye), these conditions correspond to $\phi \approx 0.4$ and therefore to $f \approx 160 \mathrm{~atm}$.

Self-test 3D. 6 At what temperature would carbon dioxide have a fugacity of 400 atm when its pressure is 400 atm ?

Answer: At about $T_{\mathrm{r}}=2.5$, corresponding to $T=760 \mathrm{~K}$

## Checklist of concepts

□ 1. The fundamental equation, a combination of the First and Second Laws, is an expression for the change in internal energy that accompanies changes in the volume and entropy of a system.
□ 2. Relations between thermodynamic properties are generated by combining thermodynamic and mathematical expressions for changes in their values.
□ 3. The Maxwell relations are a series of relations between derivatives of thermodynamic properties based on criteria for changes in the properties being exact differentials.
□ 4. The Maxwell relations are used to derive the thermodynamic equation of state and to determine how the internal energy of a substance varies with volume.
□ 5. The variation of the Gibbs energy of a system suggests that it is best regarded as a function of pressure and temperature.
□ 6. The Gibbs energy of a substance decreases with temperature and increases with pressure.
□ 7. The variation of Gibbs energy with temperature is related to the enthalpy by the Gibbs-Helmholtz equation.
□ 8. The Gibbs energies of solids and liquids are almost independent of pressure; those of gases vary linearly with the logarithm of the pressure.
□ 9. The fugacity is a kind of effective pressure of a real gas.

## Checklist of equations

| Property | Equation | Comment | Equation number |
| :--- | :--- | :--- | :--- |
| Fundamental equation | $\mathrm{d} U=T \mathrm{~d} S-p \mathrm{~d} V$ | No additional work | 3D. 1 |
| Fundamental equation of chemical thermodynamics | $\mathrm{d} G=V \mathrm{~d} p-S \mathrm{~d} T$ | No additional work | 3D. 7 |
| Variation of $G$ | $(\partial G / \partial p)_{T}=V$ and $(\partial G / \partial T)_{p}=-S$ | Composition constant | 3D. 8 |
| Gibbs-Helmholtz equation | $(\partial(G / T) / \partial T)_{p}=-H / T^{2}$ | Composition constant | 3D. 10 |
| Pressure dependence of $G$ | $G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+\left(p_{\mathrm{f}}-p_{\mathrm{i}}\right) V_{\mathrm{m}}$ | Incompressible substance | 3D. 13 |
|  | $G_{\mathrm{m}}\left(p_{\mathrm{f}}\right)=G_{\mathrm{m}}\left(p_{\mathrm{i}}\right)+R T \ln \left(p_{\mathrm{f}} / p_{\mathrm{i}}\right)$ | Perfect gas | 3D. 14 |
|  | $G_{\mathrm{m}}=G_{\mathrm{m}}^{\ominus}+R T \ln \left(p / p^{\ominus}\right)$ | Perfect gas | 3D. 15 |
| Fugacity | $G_{\mathrm{m}}=G_{\mathrm{m}}^{\ominus}+R T \ln \left(f / p^{\ominus}\right)$ | Definition | 3D. 16 |
| Fugacity coefficient | $f=\phi p$ | Definition | 3D. 17 |
|  | $\ln \phi=\int_{0}^{p}\{(Z-1) / p\} \mathrm{d} p$ | Determination | 3D. 18 |

## CHAPTER 3 The Second and Third Laws

Assume that all gases are perfect and that data refer to 298.15 K unless otherwise stated.

## TOPIC 3A Entropy

## Discussion questions

3A. 1 The evolution of life requires the organization of a very large number of molecules into biological cells. Does the formation of living organisms violate the Second Law of thermodynamics? State your conclusion clearly and present detailed arguments to support it.

3A. 2 Discuss the significance of the terms 'dispersal' and 'disorder' in the context of the Second Law.

## Exercises

3A.1(a) During a hypothetical process, the entropy of a system increases by $125 \mathrm{~J} \mathrm{~K}^{-1}$ while the entropy of the surroundings decreases by $125 \mathrm{~J} \mathrm{~K}^{-1}$. Is the process spontaneous?
3A.1(b) During a hypothetical process, the entropy of a system increases by $105 \mathrm{~J} \mathrm{~K}^{-1}$ while the entropy of the surroundings decreases by $95 \mathrm{~J} \mathrm{~K}^{-1}$. Is the process spontaneous?

3A.2(a) A certain ideal heat engine uses water at the triple point as the hot source and an organic liquid as the cold sink. It withdraws 10.00 kJ of heat from the hot source and generates 3.00 kJ of work. What is the temperature of the organic liquid?
3A.2(b) A certain ideal heat engine uses water at the triple point as the hot source and an organic liquid as the cold sink. It withdraws 2.71 kJ of heat from the hot source and generates 0.71 kJ of work. What is the temperature of the organic liquid?

3A.3(a) Calculate the change in entropy when 100 kJ of energy is transferred reversibly and isothermally as heat to a large block of copper at (i) $0^{\circ} \mathrm{C}$, (ii) $50^{\circ} \mathrm{C}$.

3A.3(b) Calculate the change in entropy when 250 kJ of energy is transferred reversibly and isothermally as heat to a large block of lead at (i) $20^{\circ} \mathrm{C}$, (ii) $100^{\circ} \mathrm{C}$.

3A.4(a) Which of $\mathrm{F}_{2}(\mathrm{~g})$ and $\mathrm{I}_{2}(\mathrm{~g})$ is likely to have the higher standard molar entropy at 298 K ?
3A.4(b) Which of $\mathrm{H}_{2} \mathrm{O}(\mathrm{g})$ and $\mathrm{CO}_{2}(\mathrm{~g})$ is likely to have the higher standard molar entropy at 298 K ?

3A.5(a) Calculate the change in entropy when 15 g of carbon dioxide gas is allowed to expand from $1.0 \mathrm{dm}^{3}$ to $3.0 \mathrm{dm}^{3}$ at 300 K .
3A.5(b) Calculate the change in entropy when 4.00 g of nitrogen is allowed to expand from $500 \mathrm{~cm}^{3}$ to $750 \mathrm{~cm}^{3}$ at 300 K .
3A.6(a) Predict the enthalpy of vaporization of benzene from its normal boiling point, $80.1^{\circ} \mathrm{C}$.
3A.6(b) Predict the enthalpy of vaporization of cyclohexane from its normal boiling point, $80.7^{\circ} \mathrm{C}$.

3A.7(a) Calculate the molar entropy of a constant-volume sample of neon at 500 K given that it is $146.22 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$ at 298 K .
3A.7(b) Calculate the molar entropy of a constant-volume sample of argon at 250 K given that it is $154.84 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ at 298 K .

3A.8(a) Calculate $\Delta S$ (for the system) when the state 3.00 mol of perfect gas atoms, for which $C_{p, \mathrm{~m}}=\frac{5}{2} R$, is changed from $25^{\circ} \mathrm{C}$ and 1.00 atm to $125^{\circ} \mathrm{C}$ and 5.00 atm . How do you rationalize the sign of $\Delta S$ ?

3A. 3 Discuss the relationships between the various formulations of the Second Law of thermodynamics.

3A. 4 Account for deviations from Trouton's rule for liquids such as water and ethanol. Is their entropy of vaporization larger or smaller than $85 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ ? Why?

3A.8(b) Calculate $\Delta S$ (for the system) when the state of 2.00 mol diatomic perfect gas molecules, for which $C_{p, \mathrm{~m}}=\frac{5}{2} R$, is changed from $25^{\circ} \mathrm{C}$ and 1.50 atm to $135^{\circ} \mathrm{C}$ and 7.00 atm . How do you rationalize the sign of $\triangle S$ ?

3A.9(a) Calculate $\Delta S_{\text {tot }}$ when two copper blocks, each of mass 1.00 kg , one at $50^{\circ} \mathrm{C}$ and the other at $0^{\circ} \mathrm{C}$ are placed in contact in an isolated container. The specific heat capacity of copper is $0.385 \mathrm{JK}^{-1} \mathrm{~g}^{-1}$ and may be assumed constant over the temperature range involved.
3A.9(b) Calculate $\Delta S_{\text {tot }}$ when two iron blocks, each of mass 10.0 kg , one at $100^{\circ} \mathrm{C}$ and the other at $25^{\circ} \mathrm{C}$, are placed in contact in an isolated container. The specific heat capacity of iron is $0.449 \mathrm{~J}^{-1} \mathrm{~g}^{-1}$ and may be assumed constant over the temperature range involved.

3A.10(a) Calculate the change in the entropies of the system and the surroundings, and the total change in entropy, when a sample of nitrogen gas of mass 14 g at 298 K and 1.00 bar doubles its volume in (i) an isothermal reversible expansion, (ii) an isothermal irreversible expansion against $p_{\mathrm{ex}}=0$, and (iii) an adiabatic reversible expansion.
3A.10(b) Calculate the change in the entropies of the system and the surroundings, and the total change in entropy, when the volume of a sample of argon gas of mass 21 g at 298 K and 1.50 bar increases from $1.20 \mathrm{dm}^{3}$ to $4.60 \mathrm{dm}^{3}$ in (i) an isothermal reversible expansion, (ii) an isothermal irreversible expansion against $p_{\text {ex }}=0$, and (iii) an adiabatic reversible expansion.

3A.11(a) The enthalpy of vaporization of chloroform $\left(\mathrm{CHCl}_{3}\right)$ is $29.4 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at its normal boiling point of 334.88 K . Calculate (i) the entropy of vaporization of chloroform at this temperature and (ii) the entropy change of the surroundings.
3A.11(b) The enthalpy of vaporization of methanol is $35.27 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at its normal boiling point of $64.1^{\circ} \mathrm{C}$. Calculate (i) the entropy of vaporization of methanol at this temperature and (ii) the entropy change of the surroundings.

3A.12(a) Calculate the change in entropy of the system when 10.0 g of ice at $-10.0^{\circ} \mathrm{C}$ is converted into water vapour at $115.0^{\circ} \mathrm{C}$ and at a constant pressure of 1 bar. The constant-pressure molar heat capacity of $\mathrm{H}_{2} \mathrm{O}(\mathrm{s})$ and $\mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ is $75.291 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ and that of $\mathrm{H}_{2} \mathrm{O}(\mathrm{g})$ is $33.58 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$.
3A.12(b) Calculate the change in entropy of the system when 15.0 g of ice at $-12.0^{\circ} \mathrm{C}$ is converted to water vapour at $105.0^{\circ} \mathrm{C}$ at a constant pressure of 1 bar. For data, see the preceding exercise.

## Problems

3A. 1 Represent the Carnot cycle on a temperature-entropy diagram and show that the area enclosed by the cycle is equal to the work done.

3A. 2 The cycle involved in the operation of an internal combustion engine is called the Otto cycle. Air can be considered to be the working substance and can be assumed to be a perfect gas. The cycle consists of the following steps: (1) Reversible adiabatic compression from A to B, (2) reversible constant-volume pressure increase from B to C due to the combustion of a small amount of fuel, (3) reversible adiabatic expansion from C to D , and (4) reversible and constant-volume pressure decrease back to state A . Determine the change in entropy (of the system and of the surroundings) for each step of the cycle and determine an expression for the efficiency of the cycle, assuming that the heat is supplied in Step 2. Evaluate the efficiency for a compression ratio of $10: 1$. Assume that in state $\mathrm{A}, V=4.00 \mathrm{dm}^{3}, p=1.00 \mathrm{~atm}$, and $T=300 \mathrm{~K}$, that $V_{\mathrm{A}}=10 V_{\mathrm{B}}, p_{\mathrm{C}} / p_{\mathrm{B}}=5$, and that $C_{p, \mathrm{~m}}=\frac{7}{2} R$.
3A. 3 Prove that two reversible adiabatic paths can never cross. Assume that the energy of the system under consideration is a function of temperature only.
(Hint: Suppose that two such paths can intersect, and complete a cycle with the two paths plus one isothermal path. Consider the changes accompanying each stage of the cycle and show that they conflict with the Kelvin statement of the Second Law.)

3A.4 To calculate the work required to lower the temperature of an object, we need to consider how the coefficient of performance $c$ (see Impact I3.1) changes with the temperature of the object. (a) Find an expression for the work of cooling an object from $T_{\mathrm{i}}$ to $T_{\mathrm{f}}$ when the refrigerator is in a room at a temperature $T_{\mathrm{h}}$. Hint: Write $\mathrm{d} w=\mathrm{d} q / c(T)$, relate $\mathrm{d} q$ to $\mathrm{d} T$ through the heat capacity $C_{p}$, and integrate the resulting expression. Assume that the heat capacity is independent of temperature in the range of interest. (b) Use the result in part (a) to calculate the work needed to freeze 250 g of water in a refrigerator at 293 K . How long will it take when the refrigerator operates at 100 W ?

3A. 5 The expressions that apply to the treatment of refrigerators (Problem 3A.4) also describe the behaviour of heat pumps, where warmth is obtained from the back of a refrigerator while its front is being used to cool the outside world. Heat pumps are popular home heating devices because they are very efficient. Compare heating of a room at 295 K by each of two methods:
(a) direct conversion of 1.00 kJ of electrical energy in an electrical heater, and (b) use of 1.00 kJ of electrical energy to run a reversible heat pump with the outside at 260 K . Discuss the origin of the difference in the energy delivered to the interior of the house by the two methods.

3A. 6 Calculate the difference in molar entropy (a) between liquid water and ice at $-5^{\circ} \mathrm{C}$, (b) between liquid water and its vapour at $95^{\circ} \mathrm{C}$ and 1.00 atm . The differences in heat capacities on melting and on vaporization are $37.3 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ and $-41.9 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$, respectively. Distinguish between the entropy changes of the sample, the surroundings, and the total system, and discuss the spontaneity of the transitions at the two temperatures.

3A. 7 The molar heat capacity of chloroform (trichloromethane, $\mathrm{CHCl}_{3}$ ) in the range 240 K to 330 K is given by $C_{p, \mathrm{~m}} /\left(\mathrm{J} \mathrm{K}^{-1} \mathrm{~mol}^{-1}\right)=91.47+7.5 \times 10^{-2}(T / \mathrm{K})$.

In a particular experiment, $1.00 \mathrm{~mol} \mathrm{CHCl}_{3}$ is heated from 273 K to 300 K . Calculate the change in molar entropy of the sample.

3A.8 A block of copper of mass 2.00 kg ( $C_{p, \mathrm{~m}}=24.44 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ ) and temperature $0^{\circ} \mathrm{C}$ is introduced into an insulated container in which there is $1.00 \mathrm{~mol} \mathrm{H}_{2} \mathrm{O}(\mathrm{g})$ at $100^{\circ} \mathrm{C}$ and 1.00 atm . (a) Assuming all the steam is condensed to water, what will be the final temperature of the system, the heat transferred from water to copper, and the entropy change of the water, copper, and the total system? (b) In fact, some water vapour is present at equilibrium. From the vapour pressure of water at the temperature calculated in (a), and assuming that the heat capacities of both gaseous and liquid water are constant and given by their values at that temperature, obtain an improved value of the final temperature, the heat transferred, and the various entropies. (Hint: You will need to make plausible approximations.)

3A. 9 A sample consisting of 1.00 mol of perfect gas molecules at $27^{\circ} \mathrm{C}$ is expanded isothermally from an initial pressure of 3.00 atm to a final pressure of 1.00 atm in two ways: (a) reversibly, and (b) against a constant external pressure of 1.00 atm . Determine the values of $q, w, \Delta U, \Delta H, \Delta S, \Delta S_{\text {surr }}$, and $\Delta S_{\text {tot }}$ for each path.

3A. 10 A block of copper of mass 500 g and initially at 293 K is in thermal contact with an electric heater of resistance $1.00 \mathrm{k} \Omega$ and negligible mass. A current of 1.00 A is passed for 15.0 s . Calculate the change in entropy of the copper, taking $C_{p, \mathrm{~m}}=24.4 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. The experiment is then repeated with the copper immersed in a stream of water that maintains its temperature at 293 K . Calculate the change in entropy of the copper and the water in this case.

3A. 11 Find an expression for the change in entropy when two blocks of the same substance and of equal mass, one at the temperature $T_{\mathrm{h}}$ and the other at $T_{\mathrm{c}}$, are brought into thermal contact and allowed to reach equilibrium. Evaluate the change for two blocks of copper, each of mass 500 g , with $C_{p, \mathrm{~m}}=24.4 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$, taking $T_{\mathrm{h}}=500 \mathrm{~K}$ and $T_{\mathrm{c}}=250 \mathrm{~K}$.

3A. 12 According to Newton's law of cooling, the rate of change of temperature is proportional to the temperature difference between the system and its surroundings. Given that $S(T)-S\left(T_{\mathrm{i}}\right)=C \ln \left(T / T_{\mathrm{i}}\right)$, where $T_{\mathrm{i}}$ is the initial temperature and $C$ the heat capacity, deduce an expression for the rate of change of entropy of the system as it cools.

3A. 13 The protein lysozyme unfolds at a transition temperature of $75.5^{\circ} \mathrm{C}$ and the standard enthalpy of transition is $509 \mathrm{~kJ} \mathrm{~mol}^{-1}$. Calculate the entropy of unfolding of lysozyme at $25.0^{\circ} \mathrm{C}$, given that the difference in the constantpressure heat capacities upon unfolding is $6.28 \mathrm{~kJ} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ and can be assumed to be independent of temperature. Hint: Imagine that the transition at $25.0^{\circ} \mathrm{C}$ occurs in three steps: (i) heating of the folded protein from $25.0^{\circ} \mathrm{C}$ to the transition temperature, (ii) unfolding at the transition temperature, and (iii) cooling of the unfolded protein to $25.0^{\circ} \mathrm{C}$. Because the entropy is a state function, the entropy change at $25.0^{\circ} \mathrm{C}$ is equal to the sum of the entropy changes of the steps.

## TOPIC 3B The measurement of entropy

## Discussion question

3B. 1 Discuss why the standard entropies of ions in solution may be positive, negative, or zero.

## Exercises

3B.1(a) Calculate the residual molar entropy of a solid in which the molecules can adopt (i) three, (ii) five, (iii) six orientations of equal energy at $T=0$.
3B.1(b) Suppose that the hexagonal molecule $\mathrm{C}_{6} \mathrm{H}_{n} \mathrm{~F}_{6-n}$ has a residual entropy on account of the similarity of the H and F atoms. Calculate the residual for each value of $n$.

3B.2(a) Calculate the standard reaction entropy at 298 K of
(i) $2 \mathrm{CH}_{3} \mathrm{CHO}(\mathrm{g})+\mathrm{O}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{CH}_{3} \mathrm{COOH}(\mathrm{l})$

## Problems

3B. 1 The standard molar entropy of $\mathrm{NH}_{3}(\mathrm{~g})$ is $192.45 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$ at 298 K , and its heat capacity is given by eqn 2B. 8 with the coefficients given in Table 2B.1. Calculate the standard molar entropy at (a) $100^{\circ} \mathrm{C}$ and (b) $500^{\circ} \mathrm{C}$.

3B. 2 The molar heat capacity of lead varies with temperature as follows:

| $T / \mathrm{K}$ | 10 | 15 | 20 | 25 | 30 | 50 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $C_{p, \mathrm{~m}} /\left(\mathrm{J} \mathrm{K}^{-1} \mathrm{~mol}^{-1}\right)$ | 2.8 | 7.0 | 10.8 | 14.1 | 16.5 | 21.4 |
| $T / \mathrm{K}$ | 70 | 100 | 150 | 200 | 250 | 298 |
| $C_{p, \mathrm{~m}} /\left(\mathrm{J} \mathrm{K}^{-1} \mathrm{~mol}^{-1}\right)$ | 23.3 | 24.5 | 25.3 | 25.8 | 26.2 | 26.6 |

Calculate the standard Third-Law entropy of lead at (a) $0^{\circ} \mathrm{C}$ and (b) $25^{\circ} \mathrm{C}$.
3B. 3 From standard enthalpies of formation, standard entropies, and standard heat capacities available from tables in the Resource section, calculate:
(a) the standard enthalpies and entropies at 298 K and 398 K for the reaction $\mathrm{CO}_{2}(\mathrm{~g})+\mathrm{H}_{2}(\mathrm{~g}) \rightarrow \mathrm{CO}(\mathrm{g})+\mathrm{H}_{2} \mathrm{O}(\mathrm{g})$. Assume that the heat capacities are constant over the temperature range involved.

3B. 4 The molar heat capacity of anhydrous potassium hexacyanoferrate(II) varies with temperature as follows:

| T/K | 10 | 20 | 30 | 40 | 50 | 60 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $C_{p, \mathrm{~m}} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$ | 2.09 | 14.43 | 36.44 | 62.55 | 87.03 | 111.0 |
| T/K | 70 | 80 | 90 | 100 | 110 | 150 |
| $C_{p, \mathrm{~m}} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$ | 131.4 | 149.4 | 165.3 | 179.6 | 192.8 | 237.6 |
| T/K | 160 | 170 | 180 | 190 | 200 |  |
| $C_{p, \mathrm{~m}} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$ | 247.3 | 256.5 | 265.1 | 273.0 | 280.3 |  |

Calculate the molar enthalpy relative to its value at $T=0$ and the Third-Law entropy at each of these temperatures.

3B. 5 The compound 1,3,5-trichloro-2,4,6-trifluorobenzene is an intermediate in the conversion of hexachlorobenzene to hexafluorobenzene, and its thermodynamic properties have been examined by measuring its heat capacity over a wide temperature range (R.L. Andon and J.F. Martin, J. Chem. Soc. Faraday Trans. I, 871 (1973)). Some of the data are as follows:
(ii) $2 \mathrm{AgCl}(\mathrm{s})+\mathrm{Br}_{2}(\mathrm{l}) \rightarrow 2 \mathrm{AgBr}(\mathrm{s})+\mathrm{Cl}_{2}(\mathrm{~g})$
(iii) $\mathrm{Hg}(\mathrm{l})+\mathrm{Cl}_{2}(\mathrm{~g}) \rightarrow \mathrm{HgCl}_{2}(\mathrm{~s})$

3B.2(b) Calculate the standard reaction entropy at 298 K of
(i) $\mathrm{Zn}(\mathrm{s})+\mathrm{Cu}^{2+}(\mathrm{aq}) \rightarrow \mathrm{Zn}^{2+}(\mathrm{aq})+\mathrm{Cu}(\mathrm{s})$
(ii) $\mathrm{C}_{12} \mathrm{H}_{22} \mathrm{O}_{11}(\mathrm{~s})+12 \mathrm{O}_{2}(\mathrm{~g}) \rightarrow 12 \mathrm{CO}_{2}(\mathrm{~g})+11 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$

| T/K | 14.14 | 16.33 | 20.03 | 31.15 | 44.08 | 64.81 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $C_{p, \mathrm{~m}} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$ | 9.492 | 12.70 | 18.18 | 32.54 | 46.86 | 66.36 |
| T/K | 100.90 | 140.86 | 183.59 | 225.10 | 262.99 | 298.06 |
| $C_{p, \mathrm{~m}} /\left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right)$ | 95.05 | 121.3 | 144.4 | 163.7 | 180.2 | 196.4 |
| Calculate the molar enthalpy relative to its value at $T=0$ and the Third-Law molar entropy of the compound at these temperatures. |  |  |  |  |  |  |
| 3B. $6^{\ddagger}$ Given that $S_{\mathrm{m}}^{\ominus}=29.79 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$ for bismuth at 100 K and the following tabulated heat capacity data (D.G. Archer, J. Chem. Eng. Data 40, 1015 (1995)), compute the standard molar entropy of bismuth at 200 K . |  |  |  |  |  |  |
| T/K | 100 | 120 | 140 | 160 | 180 | 200 |
| $\begin{aligned} & C_{p, \mathrm{~m}} / \\ & \left(\mathrm{JK}^{-1} \mathrm{~mol}^{-1}\right) \end{aligned}$ | 23.00 | 23.74 | 24.25 | 24.44 | 24.89 | 25.11 |

Compare the value to the value that would be obtained by taking the heat capacity to be constant at $24.44 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$ over this range.
3B. 7 Derive an expression for the molar entropy of a monatomic solid on the basis of the Einstein and Debye models and plot the molar entropy against the temperature (use $T / \theta$ in each case, with $\theta$ the Einstein or Debye temperature). Use the following expressions for the temperature-dependence of the heat capacities:

$$
\begin{aligned}
\text { Einstein: } C_{V, \mathrm{~m}}(T) & =3 R f^{\mathrm{E}}(T) \quad f^{\mathrm{E}}(T)=\left(\frac{\theta^{\mathrm{E}}}{T}\right)^{2}\left(\frac{\mathrm{e}^{\theta^{\mathrm{E}} / 2 T}}{\mathrm{e}^{\theta^{\mathrm{E}} / T}-1}\right)^{2} \\
\text { Debye: } C_{V, \mathrm{~m}}(T) & =3 R f^{\mathrm{D}}(T) \quad f^{\mathrm{D}}(T)=3\left(\frac{T}{\theta^{\mathrm{D}}}\right)^{2} \int_{0}^{\theta^{\mathrm{D}} / T} \frac{x^{4} \mathrm{e}^{x}}{\left(\mathrm{e}^{x}-1\right)^{2}} \mathrm{~d} x
\end{aligned}
$$

Use mathematical software to evaluate the appropriate expressions.
3B. 8 An average human DNA molecule has $5 \times 10^{8}$ binucleotides (rungs on the DNA ladder) of four different kinds. If each rung were a random choice of one of these four possibilities, what would be the residual entropy associated with this typical DNA molecule?

## TOPIC 3C Concentrating on the system

## Discussion questions

3C. 1 The following expressions have been used to establish criteria for spontaneous change: $\mathrm{d} A_{T, V}<0$ and $\mathrm{dG}_{T, p}<0$. Discuss the origin, significance, and applicability of each criterion.

3C. 2 Under what circumstances, and why, can the spontaneity of a process be discussed in terms of the properties of the system alone?

[^12]
## Exercises

3C.1(a) Combine the reaction entropies calculated in Exercise 3B.2(a) with the reaction enthalpies, and calculate the standard reaction Gibbs energies at 298 K .
3C.1(b) Combine the reaction entropies calculated in Exercise 3B.2(b) with the reaction enthalpies, and calculate the standard reaction Gibbs energies at 298 K .

3C.2(a) Calculate the standard Gibbs energy of the reaction $4 \mathrm{HI}(\mathrm{g})+\mathrm{O}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{I}_{2}(\mathrm{~s})+2 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$ at 298 K , from the standard entropies and enthalpies of formation given in the Resource section.
3C.2(b) Calculate the standard Gibbs energy of the reaction $\mathrm{CO}(\mathrm{g})+ \mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{OH}(\mathrm{l}) \rightarrow \mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{COOH}(\mathrm{l})$ at 298 K , from the standard entropies and enthalpies of formation given in the Resource section.

3C.3(a) Calculate the maximum non-expansion work per mole that may be obtained from a fuel cell in which the chemical reaction is the combustion of methane at 298 K .
3C.3(b) Calculate the maximum non-expansion work per mole that may be obtained from a fuel cell in which the chemical reaction is the combustion of propane at 298 K .

## Problems

3C. 1 Consider a perfect gas contained in a cylinder and separated by a frictionless adiabatic piston into two sections A and B . All changes in B are isothermal; that is, a thermostat surrounds $B$ to keep its temperature constant. There is 2.00 mol of the gas molecules in each section. Initially $T_{\mathrm{A}}=T_{\mathrm{B}}=300 \mathrm{~K}, V_{\mathrm{A}}=V_{\mathrm{B}}=2.00 \mathrm{dm}^{3}$. Energy is supplied as heat to Section A and the piston moves to the right reversibly until the final volume of Section B is $1.00 \mathrm{dm}^{3}$. Calculate (a) $\Delta S_{\mathrm{A}}$ and $\Delta S_{\mathrm{B}}$, (b) $\Delta A_{\mathrm{A}}$ and $\Delta A_{\mathrm{B}}$, (c) $\Delta G_{\mathrm{A}}$ and $\Delta G_{\mathrm{B}}$, (d) $\Delta S$ of the total system and its surroundings. If numerical values cannot be obtained, indicate whether the values should be positive, negative, or zero or are indeterminate from the information given. (Assume $C_{V, \mathrm{~m}}=20 \mathrm{JK}^{-1} \mathrm{~mol}^{-1}$.)

3C. 2 Calculate the molar internal energy, molar entropy, and molar Helmholtz energy of a collection of harmonic oscillators and plot your expressions as a function of $T / \theta^{\mathrm{V}}$, where $\theta^{\mathrm{V}}=h \nu / k$.

3C. 3 In biological cells, the energy released by the oxidation of foods is stored in adenosine triphosphate (ATP or ATP ${ }^{4-}$ ). The essence of ATP's action is its ability to lose its terminal phosphate group by hydrolysis and to form adenosine diphosphate (ADP or ADP ${ }^{3-}$ ):

$$
\mathrm{ATP}^{4-}(\mathrm{aq})+\mathrm{H}_{2} \mathrm{O}(\mathrm{l}) \rightarrow \mathrm{ADP}^{3-}(\mathrm{aq})+\mathrm{HPO}_{4}^{2-}(\mathrm{aq})+\mathrm{H}_{3} \mathrm{O}^{+}(\mathrm{aq})
$$

3C.4(a) Use standard Gibbs energies of formation to calculate the standard reaction Gibbs energies at 298 K of the reactions
(i) $2 \mathrm{CH}_{3} \mathrm{CHO}(\mathrm{g})+\mathrm{O}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{CH}_{3} \mathrm{COOH}(\mathrm{l})$
(ii) $2 \mathrm{AgCl}(\mathrm{s})+\mathrm{Br}_{2}(\mathrm{l}) \rightarrow 2 \mathrm{AgBr}(\mathrm{s})+\mathrm{Cl}_{2}(\mathrm{~g})$
(iii) $\mathrm{Hg}(\mathrm{l})+\mathrm{Cl}_{2}(\mathrm{~g}) \rightarrow \mathrm{HgCl}_{2}(\mathrm{~s})$

3C.4(b) Use standard Gibbs energies of formation to calculate the standard reaction Gibbs energies at 298 K of the reactions
(i) $\mathrm{Zn}(\mathrm{s})+\mathrm{Cu}^{2+}(\mathrm{aq}) \rightarrow \mathrm{Zn}^{2+}(\mathrm{aq})+\mathrm{Cu}(\mathrm{s})$
(ii) $\mathrm{C}_{12} \mathrm{H}_{22} \mathrm{O}_{11}(\mathrm{~s})+12 \mathrm{O}_{2}(\mathrm{~g}) \rightarrow 12 \mathrm{CO}_{2}(\mathrm{~g})+11 \mathrm{H}_{2} \mathrm{O}(\mathrm{l})$

3C.5(a) The standard enthalpy of combustion of ethyl acetate $\left(\mathrm{CH}_{3} \mathrm{COOC}_{2} \mathrm{H}_{5}\right)$ is $-2231 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K and its standard molar entropy is $259.4 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. Calculate the standard Gibbs energy of formation of the compound at 298 K . 3C.5(b) The standard enthalpy of combustion of the amino acid glycine $\left(\mathrm{NH}_{2} \mathrm{CH}_{2} \mathrm{COOH}\right)$ is $-969 \mathrm{~kJ} \mathrm{~mol}^{-1}$ at 298 K and its standard molar entropy is $103.5 \mathrm{~J} \mathrm{~K}^{-1} \mathrm{~mol}^{-1}$. Calculate the standard Gibbs energy of formation of glycine at 298 K .

At $\mathrm{pH}=7.0$ and $37^{\circ} \mathrm{C}(310 \mathrm{~K}$, blood temperature $)$ the enthalpy and Gibbs energy of hydrolysis are $\Delta_{\mathrm{r}} H=-20 \mathrm{~kJ} \mathrm{~mol}^{-1}$ and $\Delta_{\mathrm{r}} G=-31 \mathrm{~kJ} \mathrm{~mol}^{-1}$, respectively. Under these conditions, the hydrolysis of $1 \mathrm{~mol} \mathrm{ATP}^{4-}(\mathrm{aq})$ results in the extraction of up to 31 kJ of energy that can be used to do nonexpansion work, such as the synthesis of proteins from amino acids, muscular contraction, and the activation of neuronal circuits in our brains. (a) Calculate and account for the sign of the entropy of hydrolysis of ATP at $\mathrm{pH}=7.0$ and 310 K . (b) Suppose that the radius of a typical biological cell is $10 \mu \mathrm{~m}$ and that inside it $1 \times 10^{6}$ ATP molecules are hydrolysed each second. What is the power density of the cell in watts per cubic metre $\left.(1 \mathrm{~W}=1 \mathrm{~J} \mathrm{~s})^{-1}\right)$ ? A computer battery delivers about 15 W and has a volume of $100 \mathrm{~cm}^{3}$. Which has the greater power density, the cell or the battery? (c) The formation of glutamine from glutamate and ammonium ions requires $14.2 \mathrm{~kJ} \mathrm{~mol}^{-1}$ of energy input. It is driven by the hydrolysis of ATP to ADP mediated by the enzyme glutamine synthetase. How many moles of ATP must be hydrolysed to form 1 mol glutamine?

## TOPIC 3D Combining the First and Second Laws

## Discussion questions

3D. 1 Suggest a physical interpretation of the dependence of the Gibbs energy on the temperature.

## Exercises

3D.1(a) Suppose that $2.5 \mathrm{mmol} \mathrm{N}_{2}(\mathrm{~g})$ occupies $42 \mathrm{~cm}^{3}$ at 300 K and expands isothermally to $600 \mathrm{~cm}^{3}$. Calculate $\Delta G$ for the process.
3D.1(b) Suppose that $6.0 \mathrm{mmol} \mathrm{Ar}(\mathrm{g})$ occupies $52 \mathrm{~cm}^{3}$ at 298 K and expands isothermally to $122 \mathrm{~cm}^{3}$. Calculate $\Delta G$ for the process.

3D. 2 Suggest a physical interpretation of the dependence of the Gibbs energy on the pressure.

3D.2(a) The change in the Gibbs energy of a certain constant-pressure process was found to fit the expression $\Delta G / \mathrm{J}=-85.40+36.5(T / \mathrm{K})$. Calculate the value of $\Delta S$ for the process.

3D.2(b) The change in the Gibbs energy of a certain constant-pressure process was found to fit the expression $\Delta G / \mathrm{J}=-73.1+42.8(T / \mathrm{K})$. Calculate the value of $\Delta S$ for the process.

3D.3(a) Estimate the change in the Gibbs energy and molar Gibbs energy of $1.0 \mathrm{dm}^{3}$ of octane when the pressure acting on it is increased from 1.0 atm to 100 atm . The mass density of octane is $0.703 \mathrm{~g} \mathrm{~cm}^{-3}$.

## Problems

3D. 1 Calculate $\Delta_{\mathrm{r}} G^{\ominus}(375 \mathrm{~K})$ for the reaction $2 \mathrm{CO}(\mathrm{g})+\mathrm{O}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{CO}_{2}(\mathrm{~g})$ from the value of $\Delta_{\mathrm{r}} G^{\ominus}(298 \mathrm{~K}), \Delta_{\mathrm{r}} H^{\ominus}(298 \mathrm{~K})$, and the Gibbs-Helmholtz equation.

3D. 2 Estimate the standard reaction Gibbs energy of $\mathrm{N}_{2}(\mathrm{~g})+3 \mathrm{H}_{2}(\mathrm{~g}) \rightarrow 2 \mathrm{NH}_{3}(\mathrm{~g})$ at (a) 500 K , (b) 1000 K from their values at 298 K .

3D. 3 At 298 K the standard enthalpy of combustion of sucrose is -5797 $\mathrm{kJ} \mathrm{mol}^{-1}$ and the standard Gibbs energy of the reaction is $-6333 \mathrm{~kJ} \mathrm{~mol}^{-1}$. Estimate the additional non-expansion work that may be obtained by raising the temperature to blood temperature, $37^{\circ} \mathrm{C}$.

3D. 4 Two empirical equations of state of a real gas are as follows:

$$
\begin{aligned}
\text { van der Waals: } p & =\frac{R T}{V_{\mathrm{m}}-b}-\frac{a}{V_{\mathrm{m}}^{2}} \\
\text { Dieterici: } p & =\frac{R T \mathrm{e}^{-a / R T V_{\mathrm{m}}}}{V_{\mathrm{m}}-b}
\end{aligned}
$$

Evaluate $(\partial S / \partial V)_{T}$ for each gas. For an isothermal expansion, for which kind of gas (also consider a perfect gas) will $\Delta S$ be greatest? Explain your conclusion.

3D. 5 Two of the four Maxwell relations were derived in the text, but two were not. Complete their derivation by showing that $(\partial S / \partial V)_{T}=(\partial p / \partial T)_{V}$ and $(\partial T / \partial p)_{S}=(\partial V / \partial S)_{p}$.
3D. 6 (a) Use the Maxwell relations to express the derivatives $(\partial S / \partial V)_{T}$, $(\partial V / \partial S)_{p},(\partial p / \partial S)_{V}$, and $(\partial V / \partial S)_{p}$ in terms of the heat capacities, the expansion coefficient $\alpha=(1 / V)(\partial V / \partial T)_{p}$, and the isothermal compressibility, $\kappa_{T}=-(1 / V) (\partial V / \partial p)_{T}$. (b) The Joule coefficient, $\mu_{\mathrm{J}}$, is defined as $\mu_{\mathrm{J}}=(\partial T / \partial V)_{U^{U}}$. Show that $\mu_{\mathrm{J}} C_{V}=p-\alpha T / \kappa_{T}$.

3D. 7 Suppose that $S$ is regarded as a function of $p$ and $T$. Show that $T \mathrm{~d} S=C_{p} \mathrm{~d} T- \alpha T V \mathrm{~d} p$. Hence, show that the energy transferred as heat when the pressure

3D.3(b) Estimate the change in the Gibbs energy and molar Gibbs energy of $100 \mathrm{~cm}^{3}$ of water when the pressure acting on it is increased from 100 kPa to 500 kPa . The mass density of water is $0.997 \mathrm{~g} \mathrm{~cm}^{-3}$.

3D.4(a) Calculate the change in the molar Gibbs energy of hydrogen gas when its pressure is increased isothermally from 1.0 atm to 100.0 atm at 298 K . 3D.4(b) Calculate the change in the molar Gibbs energy of oxygen when its pressure is increased isothermally from 50.0 kPa to 100.0 kPa at 500 K .
on an incompressible liquid or solid is increased by $\Delta p$ is equal to $-\alpha T V \Delta p$, where $\alpha=(1 / V)(\partial V / \partial T)_{p}$. Evaluate $q$ when the pressure acting on $100 \mathrm{~cm}^{3}$ of mercury at $0^{\circ} \mathrm{C}$ is increased by 1.0 kbar . ( $\alpha=1.82 \times 10^{-4} \mathrm{~K}^{-1}$.)

3D. 8 Equation 3D. $6\left(\pi_{T}=T(\partial p / \partial T)_{V}-p\right)$ expresses the internal pressure $\pi_{T}$ in terms of the pressure and its derivative with respect to temperature. Express $\pi_{T}$ in terms of the molecular partition function.

3D. 9 Explore the consequences of replacing the equation of state of a perfect gas by the van der Waals equation of state for the pressure-dependence of the molar Gibbs energy. Proceed in three steps. First, consider the case when $a=0$ and only repulsions are significant. Then consider the case when $b=0$ and only attractions are significant. For the latter, you should consider making the approximation that the attractions are weak. Finally, explore the full expression by using mathematical software. In each case plot your results graphically and account physically for the deviations from the perfect gas expression.

3D. $10^{\ddagger}$ Nitric acid hydrates have received much attention as possible catalysts for heterogeneous reactions which bring about the Antarctic ozone hole. Worsnop et al. (Science 259, 71 (1993)) investigated the thermodynamic stability of these hydrates under conditions typical of the polar winter stratosphere. They report thermodynamic data for the sublimation of mono-, di-, and trihydrates to nitric acid and water vapour, $\mathrm{HNO}_{3} \cdot n \mathrm{H}_{2} \mathrm{O}(\mathrm{s}) \rightarrow \mathrm{HNO}_{3}(\mathrm{~g})+n \mathrm{H}_{2} \mathrm{O}(\mathrm{g})$, for $n=1,2$, and 3. Given $\Delta_{\mathrm{r}} G^{\ominus}$ and $\Delta_{\mathrm{r}} H^{\ominus}$ for these reactions at 220 K , use the Gibbs-Helmholtz equation to compute $\Delta_{\mathrm{r}} G^{\ominus}$ at 190 K .

| $n$ | 1 | 2 | 3 |
| :--- | :--- | :--- | :--- |
| $\Delta_{\mathrm{r}} G^{\ominus} /\left(\mathrm{kJ} \mathrm{mol}^{-1}\right)$ | 46.2 | 69.4 | 93.2 |
| $\Delta_{\mathrm{r}} H^{\ominus} /\left(\mathrm{kJ} \mathrm{mol}^{-1}\right)$ | 127 | 188 | 237 |

## Integrated activities

3.1 A gaseous sample consisting of 1.00 mol molecules is described by the equation of state $p V_{\mathrm{m}}=R T(1+B p)$. Initially at 373 K , it undergoes Joule-Thomson expansion from 100 atm to 1.00 atm . Given that $C_{p, \mathrm{~m}}=\frac{5}{2} R, \mu=0.21 \mathrm{~K} \mathrm{~atm}^{-1}, B=-0.525(\mathrm{~K} / T) \mathrm{atm}^{-1}$ and that these are constant over the temperature range involved, calculate $\Delta T$ and $\Delta S$ for the gas.
3.2 Discuss the relationship between the thermodynamic and statistical definitions of entropy.
3.3 Use mathematical software, a spreadsheet, or the Living graphs on the web site for this book to:
(a) Evaluate the change in entropy of $1.00 \mathrm{~mol} \mathrm{CO}_{2}(\mathrm{~g})$ on expansion from $0.001 \mathrm{~m}^{3}$ to $0.010 \mathrm{~m}^{3}$ at 298 K , treated as a van der Waals gas.
(b) Allow for the temperature dependence of the heat capacity by writing $C=a+b T+c / T^{2}$, and plot the change in entropy for different values of the three coefficients (including negative values of $c$ ).
(c) Show how the first derivative of $G,(\partial G / \partial p)_{T}$, varies with pressure, and plot the resulting expression over a pressure range. What is the physical significance of $(\partial G / \partial p)_{T}$ ?
(d) Evaluate the fugacity coefficient as a function of the reduced volume of a van der Waals gas and plot the outcome for a selection of reduced temperatures over the range $0.8 \leq V_{\mathrm{r}} \leq 3$.


[^0]:    ${ }^{1}$ Concerted motion, but on a much smaller scale, is observed as Brownian motion, the jittering motion of small particles suspended in a liquid or gas.

[^1]:    ${ }^{2}$ Alternatively, the surroundings can be regarded as being at constant pressure, in which case we could equate $\mathrm{d} q_{\text {sur }}$ to $\mathrm{d} H_{\text {sur }}$.

[^2]:    ${ }^{3}$ Discussions are in progress to replace this definition by another that is independent of the specification of a particular substance.

[^3]:    ${ }^{4}$ According to Topic 2C, $\Delta_{\text {trs }} H$ is an enthalpy change per mole of substance; so $\Delta_{\text {trs }} S$ is also a molar quantity.

[^4]:    * More values are given in the Resource section.

[^5]:    ${ }^{1}$ In terms of the language introduced in Topic 5A, the entropies of ions in solution are actually partial molar entropies, for their values include the consequences of their presence on the organization of the solvent molecules around them.

[^6]:    Answer: With $\mathrm{d} H<0$, it is common for $\mathrm{d} G<0$ unless $T \mathrm{~d} S$ is strongly negative.

[^7]:    ${ }^{1}$ Arbeit is the German word for work; hence the symbol $A$.

[^8]:    * More values are given in the Resource section.

[^9]:    ${ }^{2}$ The reference state of an element is defined in Topic 2C.

[^10]:    *'etc.' indicates that the conditions are as expressed by the subscripts.

[^11]:    ${ }^{1}$ The name 'fugacity' comes from the Latin for 'fleetness' in the sense of 'escaping tendency'; fugacity has the same dimensions as pressure.

[^12]:    ${ }^{\ddagger}$ These problems were provided by Charles Trapp and Carmen Giunta.

