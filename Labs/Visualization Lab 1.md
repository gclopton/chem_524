

Visualization Lab #1
CHEM 524 - Electrochemical Methods
Grady Clopton

Due: Friday, Feb 13th, 2026, before the end of the day at 11:59 PM
Instructions: The total points are 100. Answer the questions below and show all the work / detailed steps necessary to arrive at an answer; identify the right equations to use. Include your name on your answer page. Please clearly label the question number in your answer. Please upload the lab to Canvas as a PDF or image file (please do not upload ".HEIC")

Learning Objectives
1. Observe the main components of electrochemical experiments.
2. Learn how to carry out electrochemical experiments with three electrode configurations and make connections.
3. a) Collect data on charging current.
b) Carry out a scan rate-dependent study.
c) Learn how to calculate Cd .
4. a) Collect data on the reduction of reduction of Ferricyanide, $\left[\mathrm{Fe}(\mathrm{CN})_6\right]^{3-}$.
b) Learn how to calculate the half wave potential, $\mathrm{E}_{1 / 2}$, and use it to make predictions about the standard potential, $\mathrm{E}^{\ominus}$.


> [!questio] Question 1
> Activities (Objectives 1 and 2)
> 1. What are the three main components necessary for an electrochemical experiment?
> 2. Our experiment will be making use of a Glassy Carbon Electrode (GCE) or Platinum Ultramicroelectrode ( $10 \mu \mathrm{~m}$ diameter) as the working electrode, a commercial $\mathrm{Ag} / \mathrm{AgCl} / \mathrm{KCl}(1 \mathrm{M})$ reference electrode, and a Carbon Rod as the counter electrode. What are the main characteristics that each of these electrodes need to exhibit for our experiment to be successful?
>3. Our background solution for this experiment will be an aqueous 1 M KCl solution. What role does the KCl play in the experiment? Why is the concentration 1 M ? Should the solution be stirred in the case of attempting to consider diffusion as the dominant mode of mass transport?
>4. We will be using a CHI1205b Electrochemical Analyzer. What role does this instrument play and which electrode should be connected to which color lead?



1.) The three essential components are the working electrode (where the chemistry of interest occurs), the reference electrode (which defines the potential scale), and the counter electrode (which carries the current to complete the circuit).


2.) **Working electrode (GCE or Pt UME):** stable and reproducible surface/area so currents reflect the intended processes; clean/renewable surface, sufficiently wide potential window in water. (For a $10~\mu\mathrm{m}$ UME, the small area helps keep currents small and reduces $iR$ and capacitive artifacts). 
**Reference electrode ($\mathrm{Ag}/\mathrm{AgCl}/\mathrm{KCl}(1~\mathrm{M})$):** a stable, well-poised potential with minimal drift and reliable ionic contact to solution. 
**Counter electrode (carbon rod):** inert and large-area so it can pass the required current without becoming rate-limiting or generating interfering products near the working electrode.

3.) The $1~\mathrm{M}$ KCl is a supporting electrolyte. It increases conductivity (minimizes $iR_{\mathrm{u}}$) and suppresses migration so mass transport is closer to diffusion-controlled. If you want diffusion to be the dominant mode of mass transport, do not stir during the measurement.

4.) The CHI1205b is a potentiostat/galvanostat. It controls $E$ (working vs. reference) and measures $i$ (between working and counter) while drawing negligible current through the reference. Connect to the terminals labeled WE/RE/CE; on CH Instruments systems the common lead colors are green $\rightarrow$ WE, white $\rightarrow$ RE, red $\rightarrow$ CE, and black is a sense lead used only if a 4-electrode mode is explicitly being used (otherwise leave it unconnected).






> [!questio] Question 2
> Activities (Objective 3)
> 1. Create a table for the values of charging current collected at varying scan rates.
> 2. What is the equation for charging current during a voltage ramp?
> 3. Create a plot of charging current versus scan rate and use it to calculate $\mathbf{C}_{\mathbf{d}}$.


![[Visualization Lab 1 Data Scan Rate.png|500]]

1.) From the CVs in $1~\mathrm{M}$ KCl (scan window $0.40 \rightarrow 0.20~\mathrm{V}$), I took the charging current magnitude at $E=0.30~\mathrm{V}$ (a region intended to be non-faradaic), using the anodic branch as $i_c$:

| Scan rate, $\nu$ (V/s) | Charging current, $i_c$ ($\mu$A) |
| --- | --- |
| 0.10 | 0.47 |
| 0.30 | 0.99 |
| 0.50 | 1.57 |
| 0.75 | 2.25 |
| 1.00 | 3.00 |

2.) For a purely capacitive response during a linear potential ramp, the charging current is proportional to scan rate:

$$
i_c = C_d \frac{dE}{dt} = C_d \nu
$$

3.) Plotting $i_c$ vs. $\nu$ gives an approximately linear trend; the slope is $C_d$:

![[Visualization Lab 1 Charging Current vs Scan Rate.png]]

Using a fit constrained through the origin, $C_d \approx 3.0~\mu\mathrm{F}$ for this electrode under these conditions (since $\mu\mathrm{A}/(\mathrm{V}/\mathrm{s}) = \mu\mathrm{F}$).







> [!questio] Question 3
> Activities (Objective 4)
> 1. Consider the reduction of Ferricyanide. Identify the limiting current. At what potentials does the limiting current occur? Why is this the case? Write the charge transfer and Nernst equations for this system at the surface of the electrode.
> 2. Calculate the Half Wave Potential, $\mathrm{E}_{1 / 2}$. What predictions can you make about the Standard Potential, $\mathrm{E}^{\ominus}$, based on this value? What is the concentration of Ferricyanide and Ferrocyanide at the electrode surface when the potential is equal to this value? What assumption about the mass transfer coefficients of Ferricyanide and Ferrocyanide must be true for your predictions to be correct?


![[Visualization Lab 1 Data Ferricyanide.png|500]]

1.) From the LSV, the current rises from a small background near $E\approx 0.50~\mathrm{V}$ and reaches a clear plateau (diffusion-limited region) at about

$$
i_{\mathrm{lim}} \approx 1.47\times 10^{-9}~\mathrm{A}.
$$

The plateau occurs at the most cathodic potentials in the scan, roughly for $E\lesssim 0.08~\mathrm{V}$ down to $0~\mathrm{V}$ (as plotted). This happens because once the electron-transfer driving force is large enough, ferricyanide is consumed at the electrode surface as fast as it can be delivered from the bulk by mass transport; further changes in $E$ cannot increase the flux, so the current becomes limited by diffusion rather than kinetics.

The (1-electron) charge-transfer reaction is

$$
\left[\mathrm{Fe(CN)}_6\right]^{3-} + e^- \rightleftharpoons \left[\mathrm{Fe(CN)}_6\right]^{4-}.
$$

At the electrode surface, the Nernst equation is

$$
E = E^{\ominus\prime} + \frac{R T}{F}\ln\!\left(\frac{a_{\left[\mathrm{Fe(CN)}_6\right]^{3-},s}}{a_{\left[\mathrm{Fe(CN)}_6\right]^{4-},s}}\right)
\approx
E^{\ominus\prime} + \frac{R T}{F}\ln\!\left(\frac{C_{\left[\mathrm{Fe(CN)}_6\right]^{3-},s}}{C_{\left[\mathrm{Fe(CN)}_6\right]^{4-},s}}\right),
$$

where the subscript $s$ denotes the interfacial (surface) values.

2.) The half-wave potential is the potential where the current is halfway between the pre-wave baseline and the diffusion-limited plateau. Using the trace as plotted,

$$
E_{1/2} \approx 0.229~\mathrm{V}.
$$

For a reversible couple with equal mass-transfer coefficients for oxidized and reduced forms, $E_{1/2}$ is a good estimate of the formal (and, under appropriate standard-state conventions, standard) potential on the same reference scale:

$$
E^{\ominus\prime} \approx E_{1/2}.
$$

At $E=E_{1/2}$, the Nernst relation implies equal surface activities (and, to a good approximation in this context, equal surface concentrations):

$$
a_{\left[\mathrm{Fe(CN)}_6\right]^{3-},s} = a_{\left[\mathrm{Fe(CN)}_6\right]^{4-},s}.
$$

Because the bulk solution is $2~\mathrm{mM}$ ferricyanide with negligible ferrocyanide initially, the “halfway” current condition corresponds to approximately

$$
C_{\left[\mathrm{Fe(CN)}_6\right]^{3-},s} \approx 1~\mathrm{mM},
\qquad
C_{\left[\mathrm{Fe(CN)}_6\right]^{4-},s} \approx 1~\mathrm{mM}.
$$

The key assumption required for interpreting $E_{1/2}$ as $E^{\ominus\prime}$ is that ferricyanide and ferrocyanide have approximately the same mass-transfer coefficient to/from the electrode often approximated as $D_{\left[\mathrm{Fe(CN)}_6\right]^{3-}}\approx D_{\left[\mathrm{Fe(CN)}_6\right]^{4-}}$ under the same hydrodynamic conditions.


