Grady Clopton
Chem 524
Homework #1




> [!Question] 1 (1.1)
> Consider each of the following electrode/solution interfaces. Write the equations for the electrode reactions that occur when the potential is moved progressively (1) negatively and (2) positively from the open-circuit potential, until the background limit is reached. Next to each reaction write the approximate potential for the reaction in V vs. SCE (assuming the reaction is reversible). Sketch the entire $i-E$ curve for the system.
> a) $\mathrm{Pt} / \mathrm{Cu}^{2+}(0.01 \mathrm{M}), \mathrm{Cd}^{2+}(0.01 \mathrm{M}), \mathrm{H}_{2} \mathrm{SO}_{4}(1 \mathrm{M})$
> b) $\mathrm{Pt} / \mathrm{Sn}^{2+}(0.01 \mathrm{M}), \mathrm{Sn}^{4+}(0.01 \mathrm{M}), \mathrm{HCl}(1 \mathrm{M})$
> c) $\mathrm{Hg} / \mathrm{Cd}^{2+}(0.01 \mathrm{M}), \mathrm{Zn}^{2+}(0.01 \mathrm{M}), \mathrm{HCl}(1 \mathrm{M})$



Reductions appear first in order of most positive $E$, and oxidations appear first in order of least positive $E$. I use
$$
E(\text{vs SCE})=E(\text{vs NHE})-0.244\ \text{V}
$$
and, for $M^{2+}+2e^- \rightleftharpoons M$ at $[M^{2+}]=0.01\ \text{M}$,
$$
E=E^\circ+\frac{0.059}{2}\log(0.01)=E^\circ-0.059\ \text{V}.
$$

## Part A

On a negative scan from open circuit, copper is reduced first:
$$
\mathrm{Cu}^{2+}+2e^- \rightarrow \mathrm{Cu}, \qquad E \approx +0.03\ \text{V vs SCE}.
$$
At more negative potential the cathodic background limit is hydrogen evolution:
$$
2\mathrm{H}^+ +2e^- \rightarrow \mathrm{H}_2, \qquad E \approx -0.24\ \text{V vs SCE}.
$$
The cadmium couple is more negative,
$$
\mathrm{Cd}^{2+}+2e^- \rightarrow \mathrm{Cd}, \qquad E \approx -0.71\ \text{V vs SCE},
$$
so it is reached only after hydrogen background has already become dominant at Pt. On a positive scan from open circuit, the first major process is positive background (oxygen evolution):
$$
2\mathrm{H_2O} \rightarrow \mathrm{O_2}+4\mathrm{H}^+ +4e^-, \qquad E \approx +0.99\ \text{V vs SCE}.
$$




![[Homework 1 Problem 1 Part A Sketch.png|500]]




## Part B

Both redox forms are present, so open circuit is near the $\mathrm{Sn}^{4+}/\mathrm{Sn}^{2+}$ couple:
$$
\mathrm{Sn}^{4+}+2e^- \rightleftharpoons \mathrm{Sn}^{2+}, \qquad E \approx -0.09\ \text{V vs SCE}\ (\text{for }[\mathrm{Sn}^{4+}]=[\mathrm{Sn}^{2+}]).
$$
On the negative side, the cathodic branch of this couple appears first:
$$
\mathrm{Sn}^{4+}+2e^- \rightarrow \mathrm{Sn}^{2+}, \qquad E \approx -0.09\ \text{V vs SCE},
$$
then hydrogen background begins near
$$
2\mathrm{H}^+ +2e^- \rightarrow \mathrm{H}_2, \qquad E \approx -0.24\ \text{V vs SCE}.
$$
Tin metal deposition is more negative,
$$
\mathrm{Sn}^{2+}+2e^- \rightarrow \mathrm{Sn}, \qquad E \approx -0.44\ \text{V vs SCE},
$$
so it is typically obscured by hydrogen background at Pt. On the positive side, the anodic branch of the same couple appears first:
$$
\mathrm{Sn}^{2+} \rightarrow \mathrm{Sn}^{4+}+2e^-, \qquad E \approx -0.09\ \text{V vs SCE},
$$
followed by positive background (approximately oxygen evolution in acidic aqueous solution):
$$
2\mathrm{H_2O} \rightarrow \mathrm{O_2}+4\mathrm{H}^+ +4e^-, \qquad E \approx +0.99\ \text{V vs SCE}.
$$


![[Homework 1 Problem 1 Part B Sketch.png|500]]

## Part C

Mercury changes the sequence because hydrogen evolution is very slow on Hg (**large overpotential**), so metal-ion reductions are observed first. On a negative scan:
$$
\mathrm{Cd}^{2+}+2e^- \rightarrow \mathrm{Cd(Hg)}, \qquad E \approx -0.71\ \text{V vs SCE},
$$
then
$$
\mathrm{Zn}^{2+}+2e^- \rightarrow \mathrm{Zn(Hg)}, \qquad E \approx -1.07\ \text{V vs SCE}.
$$
The cathodic background limit is then hydrogen evolution at much more negative potential on Hg (experimentally far negative of $-0.24\ \text{V vs SCE}$). On the positive scan, the anodic background limit is oxidation of mercury in chloride medium:
$$
2\mathrm{Hg}+2\mathrm{Cl}^- \rightarrow \mathrm{Hg_2Cl_2}+2e^-, \qquad E \approx +0.03\ \text{V vs SCE}.
$$





![[Homework 1 Problem 1 Part C Sketch.png|500]]



> [!Question] 2 (1.5)
> A $0.1-\mathrm{cm}^{2}$ electrode with $C_{\mathrm{d}}=20 \mu \mathrm{~F} / \mathrm{cm}^{2}$ is subjected to a potential step under conditions where $R_{\mathrm{u}}$ is 1,10 , or $100 \Omega$. In each case, what is the cell time constant, and what is the time required for the double-layer charging to be $95 \%$ complete?

For a potential step in the Chapter 1 RC model, the cell time constant is
$$
\tau = R_u C_d.
$$
The total double-layer capacitance is
$$
C_d=(20\ \mu\mathrm{F}/\mathrm{cm}^2)(0.1\ \mathrm{cm}^2)=2\ \mu\mathrm{F}=2\times10^{-6}\ \mathrm{F}.
$$
For $95\%$ charging,
$$
q(t)=q_\infty\left(1-e^{-t/\tau}\right),\qquad 0.95=1-e^{-t/\tau}
$$
so
$$
e^{-t/\tau}=0.05,\qquad t_{95\%}=-\tau\ln(0.05)=\tau\ln(20)\approx2.996\,\tau.
$$

For $R_u=1\ \Omega$:
$$
\tau=(1)(2\times10^{-6})=2\times10^{-6}\ \mathrm{s}=2\ \mu\mathrm{s},
$$
$$
t_{95\%}=2.996(2\ \mu\mathrm{s})\approx5.99\ \mu\mathrm{s}\approx6.0\ \mu\mathrm{s}.
$$

For $R_u=10\ \Omega$:
$$
\tau=(10)(2\times10^{-6})=2\times10^{-5}\ \mathrm{s}=20\ \mu\mathrm{s},
$$
$$
t_{95\%}=2.996(20\ \mu\mathrm{s})\approx59.9\ \mu\mathrm{s}\approx60\ \mu\mathrm{s}.
$$

For $R_u=100\ \Omega$:
$$
\tau=(100)(2\times10^{-6})=2\times10^{-4}\ \mathrm{s}=200\ \mu\mathrm{s},
$$
$$
t_{95\%}=2.996(200\ \mu\mathrm{s})\approx599\ \mu\mathrm{s}\approx0.599\ \mathrm{ms}\approx0.60\ \mathrm{ms}.
$$





> [!Question] 3 (1.7)
> For the electrode in Problem 1.5, what nonfaradaic current will flow (neglecting any transients) when the electrode is subjected to linear sweeps at $0.02,1,20 \mathrm{~V} / \mathrm{s}$ ?

From Chapter 1 (Section 1.6.4, potential sweep), the charging current is
$$
i=\pm v C_d\left(1-e^{-t/(R_uC_d)}\right).
$$
Neglecting transients gives the steady value
$$
i_{nf}=\pm vC_d.
$$
From Problem 1.5,
$$
C_d=(20\ \mu\mathrm{F}/\mathrm{cm}^2)(0.1\ \mathrm{cm}^2)=2\ \mu\mathrm{F}=2\times10^{-6}\ \mathrm{F}.
$$
Therefore,
$$
|i_{nf}|=v(2\times10^{-6}\ \mathrm{F}).
$$
At $v=0.02\ \mathrm{V/s}$:
$$
|i_{nf}|=(0.02)(2\times10^{-6})=4.0\times10^{-8}\ \mathrm{A}=40\ \mathrm{nA}.
$$
At $v=1\ \mathrm{V/s}$:
$$
|i_{nf}|=(1)(2\times10^{-6})=2.0\times10^{-6}\ \mathrm{A}=2.0\ \mu\mathrm{A}.
$$
At $v=20\ \mathrm{V/s}$:
$$
|i_{nf}|=(20)(2\times10^{-6})=4.0\times10^{-5}\ \mathrm{A}=40\ \mu\mathrm{A}.
$$
The sign depends on scan direction: positive for a negative-going scan and negative for a positive-going scan.






> [!Question] 4
> Harry works in a research lab. He noticed that an $\mathrm{Ag} / \mathrm{AgCl}$ reference electrode was stored in a container with 0.3 M KCl , and this 0.3 M KCl solution is drying out. Very conveniently, he found a bottle of 1 M KCl . (20pts)
> 
> $$
> \operatorname{AgCl}(s)+e^{-} \rightleftharpoons \operatorname{Ag}(s)+C l^{-} E^0=0.222 V
> $$
> 
> a. Should he add this 1 M KCl solution to the container where $\mathrm{Ag} / \mathrm{AgCl}$ reference electrode is stored and why?
> b. Do you expect the potential of the reference electrode in 0.3 M and 1 M KCl to be the same? Calculate the potential in each concentration.
> 
> 

For the half-reaction
$$
\mathrm{AgCl}(s)+e^- \rightleftharpoons \mathrm{Ag}(s)+\mathrm{Cl}^-,
$$
the Nernst equation at $25^\circ\mathrm{C}$ is
$$
E=E^0-\frac{0.059}{1}\log a_{\mathrm{Cl}^-}.
$$
Using the common approximation $a_{\mathrm{Cl}^-}\approx[\mathrm{Cl}^-]$:
$$
E\approx E^0-0.059\log[\mathrm{Cl}^-],\qquad E^0=0.222\ \mathrm{V}.
$$


## Part A
He should not add 1 M KCl if the electrode is meant to be maintained as a 0.3 M KCl reference environment, because changing $[\mathrm{Cl}^-]$ changes the reference potential. The better choice is to replenish with 0.3 M KCl so the reference composition and potential remain consistent.


## Part B
The potentials are not the same. At $[\mathrm{Cl}^-]=1.0\ \mathrm{M}$:
$$
E_{1.0\ \mathrm{M}}=0.222-0.059\log(1.0)=0.222\ \mathrm{V}.
$$
At $[\mathrm{Cl}^-]=0.30\ \mathrm{M}$:
$$
E_{0.30\ \mathrm{M}}=0.222-0.059\log(0.30)
$$
$$
=0.222-0.059(-0.5229)\approx0.222+0.0309\approx0.253\ \mathrm{V}.
$$
So the 0.30 M electrode is about $31\ \mathrm{mV}$ more positive than the 1.0 M case:
$$
\Delta E=E_{0.30\ \mathrm{M}}-E_{1.0\ \mathrm{M}}\approx+0.031\ \mathrm{V}.
$$






> [!Question] 5
> Write down the Nernst equation and calculate the half-cell potential of the following reaction in the conditions (20pts):
> 
> $$
> 2 H^{+}+2 e^{-} \rightleftharpoons H_2(a=1)
> $$
> 
> a. 1 M HCl
> b. $1 \mathrm{MNaCl}(\mathrm{pH}=7)$
> c. $1 \mathrm{M} \mathrm{NaOH}(\mathrm{pH}=14)$

For
$$
2\mathrm{H}^+ + 2e^- \rightleftharpoons \mathrm{H}_2(a=1),
$$
the Nernst equation at $25^\circ\mathrm{C}$ is
$$
E=E^0-\frac{0.059}{2}\log\left(\frac{a_{\mathrm{H}_2}}{a_{\mathrm{H}^+}^2}\right).
$$
With $a_{\mathrm{H}_2}=1$ and $E^0=0\ \mathrm{V}$ (vs NHE),
$$
E=\frac{0.059}{2}\log\left(a_{\mathrm{H}^+}^2\right)=0.059\log a_{\mathrm{H}^+}.
$$
Using $pH=-\log a_{\mathrm{H}^+}$:
$$
E=-0.059\,pH \quad (\mathrm{V\ vs\ NHE}).
$$

## Part A
$1\ \mathrm{M\ HCl}$, take $pH\approx0$:
$$
E=-0.059(0)=0.000\ \mathrm{V\ vs\ NHE}.
$$


## Part B
$1\ \mathrm{M\ NaCl}$ with $pH=7$:
$$
E=-0.059(7)=-0.413\ \mathrm{V\ vs\ NHE}\approx-0.414\ \mathrm{V\ vs\ NHE}.
$$

## Part C

$1\ \mathrm{M\ NaOH}$ with $pH=14$:
$$
E=-0.059(14)=-0.826\ \mathrm{V\ vs\ NHE}\approx-0.828\ \mathrm{V\ vs\ NHE}.
$$
