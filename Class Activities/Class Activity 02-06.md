

Grady Clopton
Chem 524
Class Activity 02-06




For a one-electron couple $O+e^{-} \rightleftharpoons R$, the Nernst equation relates the electrode potential to the ratio of the surface concentrations at $x=0$. In these three cases we use the Nernst relation and the surface mass balance $C_O(x=0)+C_R(x=0)=C^*$ with $C^*=1 \mathrm{mM}$. 


# Part A $E=E^{\circ}$


> [!question] Surface Equilibrium at $E^{\circ}$
> What are the surface concentrations $C_O(x=0)$ and $C_R(x=0)$ when the electrode potential equals the formal potential, given the Nernst relation and total concentration $C_O(x=0)+C_R(x=0)= C^*=1 \mathrm{mM}$ ?



At $E=E^{\circ}$, we evaluate the Nernst equation at the surface and use the result to determine the ratio $C_R / C_O$.


$$
E=E^{\circ}-\frac{0.059}{n} \log _{10}\left(\frac{C_R(x=0)}{C_O(x=0)}\right)
$$


Substitute the condition $E=E^{\circ}$ and $n=1$ :

$$
\begin{aligned}
E^{\circ}=E^{\circ} & -0.059 \log _{10}\left(\frac{C_R(x=0)}{C_O(x=0)}\right) \\
E^{\circ}=E^{\circ}-0.059 \log _{10}\left(\frac{C_R}{C_O}\right) & \Rightarrow E^{\circ}-E^{\circ}=\left(E^{\circ}-0.059 \log _{10}\left(\frac{C_R}{C_O}\right)\right)-E^{\circ} \\
& \Rightarrow 0=-0.059 \log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow \frac{0}{-0.059}=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow 0=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow 10^0=\frac{C_R}{C_O} \\
& \Rightarrow 1=\frac{C_R}{C_O} \\
& \Rightarrow C_R=C_O
\end{aligned}
$$




Use the surface mass balance $C_O(x=0)+C_R(x=0)=C^*$


$$
\begin{aligned}
C_O+C_R=C^* & \Rightarrow C_O+C_O=C^* \\
& \Rightarrow 2 C_O=C^* \\
& \Rightarrow C_O=\frac{C^*}{2}
\end{aligned}
$$


Plug in $C^*=1 \mathrm{mM}$ :

$$
C_O=\frac{1 \mathrm{mM}}{2} \Rightarrow C_O=0.5 \mathrm{mM}
$$


Finally, since $C_R=C_O$ :

$$
C_R=0.5 \mathrm{mM}
$$


So when $E=E^{\circ}$, the Nernst relation gives $C_R / C_O=1$, so the surface concentrations split evenly:

$$
C_O(x=0)=C_R(x=0)=0.5 \mathrm{mM}
$$





# Part B $E=E^{\circ}-0.12 \mathrm{~V}$


> [!Question] Cathodic Polarization
> What are the surface concentrations $C_O(x=0)$ and $C_R(x=0)$ when the electrode potential is 0.12 V below the formal potential, given the Nernst relation and total concentration $C_O(x=0)+C_R(x= 0)=C^*=1 \mathrm{mM}$ ?


A cathodic shift ( $E<E^{\circ}$ ) makes the logarithm term positive, so the surface ratio $C_R / C_O$ becomes greater than 1. We compute that ratio and apply the mass balance.


$$
E=E^{\circ}-0.059 \log _{10}\left(\frac{C_R(x=0)}{C_O(x=0)}\right)
$$


Substitute $E=E^{\circ}-0.12 \mathrm{~V}$ (and $n=1$):

$$
\begin{aligned}
E^{\circ}-0.12= & E^{\circ}-0.059 \log _{10}\left(\frac{C_R(x=0)}{C_O(x=0)}\right) \\
E^{\circ}-0.12=E^{\circ}-0.059 \log _{10}\left(\frac{C_R}{C_O}\right) & \Rightarrow\left(E^{\circ}-0.12\right)-E^{\circ}=\left(E^{\circ}-0.059 \log _{10}\left(\frac{C_R}{C_O}\right)\right)-E^{\circ} \\
& \Rightarrow-0.12=-0.059 \log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow \frac{-0.12}{-0.059}=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow \frac{0.12 \times 1000}{0.059 \times 1000}=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow \frac{120}{59}=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow 10^{120 / 59}=\frac{C_R}{C_O} \\
& \Rightarrow C_R=10^{120 / 59} C_O
\end{aligned}
$$


$$
\begin{aligned}
10^{120 / 59} & \approx 10^{2.03} \approx 1.08 \times 10^2 \approx 108 \\
& \Rightarrow \frac{C_R(x=0)}{C_O(x=0)} \approx 108 \\
& \Rightarrow C_R(x=0) \approx 108 C_O(x=0)
\end{aligned}
$$


Now use the surface mass balance $C_O(x=0)+C_R(x=0)=C^*$ :

$$
\begin{aligned}
C_O+C_R=C^* & \Rightarrow C_O+108 C_O=C^* \\
& \Rightarrow 109 C_O=C^* \\
& \Rightarrow C_O=\frac{C^*}{109} \\
& \Rightarrow C_R=108 C_O=\frac{108 C^*}{109}
\end{aligned}
$$


With $C^*=1 \mathrm{mM}$, we have:

$$
\begin{aligned}
& C_O=\frac{1 \mathrm{mM}}{109} \approx 9.17 \times 10^{-3} \mathrm{mM} \\
& C_R=1 \mathrm{mM}-C_O \approx 1 \mathrm{mM}-0.00917 \mathrm{mM} \approx 0.991 \mathrm{mM}
\end{aligned}
$$


$$
9.17 \times 10^{-3} \mathrm{mM}=9.17 \mu \mathrm{M}
$$


Under cathodic polarization, $C_R / C_O \approx 108$, so the reduced form dominates at the surface:

$$
C_O(x=0) \approx 9.17 \mu \mathrm{M}, \quad C_R(x=0) \approx 0.991 \mathrm{mM} .
$$






# Part C $E=E^{\circ}+0.12 \mathrm{~V}$


> [!Question] Anodic Polarization
> What are the surface concentrations $C_O(x=0)$ and $C_R(x=0)$ when the electrode potential is 0.12 V above the formal potential, given the Nernst relation and total concentration $C_O(x=0)+C_R(x= 0)=C^*=1 \mathrm{mM}$ ?


An anodic shift $\left(E>E^{\circ}\right)$ reverses the ratio from Part B. The surface ratio $C_R / C_O$ becomes less than 1 by the same factor, and the mass balance then gives the individual concentrations.

$$
E=E^{\circ}-0.059 \log _{10}\left(\frac{C_R(x=0)}{C_O(x=0)}\right)
$$


Substitute the Part C condition $E=E^{\circ}+0.12 \mathrm{~V}$ :

$$
\begin{aligned}
E^{\circ}+0.12= & E^{\circ}-0.059 \log _{10}\left(\frac{C_R(x=0)}{C_O(x=0)}\right) \\
E^{\circ}+0.12=E^{\circ}-0.059 \log _{10}\left(\frac{C_R}{C_O}\right) & \Rightarrow\left(E^{\circ}+0.12\right)-E^{\circ}=\left(E^{\circ}-0.059 \log _{10}\left(\frac{C_R}{C_O}\right)\right)-E^{\circ} \\
& \Rightarrow 0.12=-0.059 \log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow \frac{0.12}{-0.059}=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow-\frac{120}{59}=\log _{10}\left(\frac{C_R}{C_O}\right) \\
& \Rightarrow 10^{-120 / 59}=\frac{C_R}{C_O} \\
& \Rightarrow \frac{C_R}{C_O}=\frac{1}{10^{120 / 59}}
\end{aligned}
$$


$$\begin{aligned} & 10^{120 / 59} \approx 108 \\ & \Rightarrow \quad \frac{C_R}{C_O}=\frac{1}{10^{120 / 59}} \approx \frac{1}{108} \\ & \Rightarrow \quad C_R \approx \frac{1}{108} C_O\end{aligned}$$


Use the surface mass balance $C_O(x=0)+C_R(x=0)=C^*$ :

$$
\begin{aligned}
C_O+C_R=C^* & \Rightarrow C_O+\frac{1}{108} C_O=C^* \\
& \Rightarrow\left(1+\frac{1}{108}\right) C_O=C^* \\
& \Rightarrow \frac{109}{108} C_O=C^* \\
& \Rightarrow C_O=\frac{108}{109} C^* \\
& \Rightarrow C_R=C^*-C_O
\end{aligned}
$$


Now plug in $C^*=1 \mathrm{mM}$ :

$$
\begin{aligned}
& C_O(x=0)=\frac{108}{109}(1 \mathrm{mM}) \approx 0.991 \mathrm{mM} \\
& C_R(x=0)=1 \mathrm{mM}-0.991 \mathrm{mM} \approx 9.17 \times 10^{-3} \mathrm{mM}
\end{aligned}
$$


Under anodic polarization, the oxidized form dominates at the surface:

$$
C_O(x=0) \approx 0.991 \mathrm{mM}, \quad C_R(x=0) \approx 9.17 \times 10^{-3} \mathrm{mM} \approx 9.17 \mu \mathrm{M}
$$




