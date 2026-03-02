

> [!Equation] R-C Time Constant
$$\tau=R_{\mathrm{s}}C_{\mathrm{d}}.$$


Verbally, the time constant $\tau=R_{\mathrm{s}} C_{\mathrm{d}}$ is the characteristic time scale for the interface to "mostly finish" charging after you change the input.



The general solution is:



> [!equation] General Solution of a Linear ODE
 $$y(t)=\frac{1}{\mu(t)}\left[\int \mu(t) Q(t) d t+C\right]$$


---



Now plug in $\mu(t)=e^{t /\left(R_{\mathrm{s}} C_{\mathrm{d}}\right)}$ and $Q(t)=\Delta E / R_{\mathrm{s}}$ (for a voltage step, $\Delta E$ is a constant):

$$
q(t)=e^{-t /\left(R_{\mathrm{s}} C_{\mathrm{d}}\right)}\left[\int e^{t /\left(R_{\mathrm{s}} C_{\mathrm{d}}\right)}\left(\frac{\Delta E}{R_{\mathrm{s}}}\right) d t+C\right]
$$


$$
\int e^{t /\left(R_{\mathrm{s}} C_{\mathrm{d}}\right)}\left(\frac{\Delta E}{R_{\mathrm{s}}}\right) d t=\frac{\Delta E}{R_{\mathrm{s}}} \int e^{t / \tau} d t=\frac{\Delta E}{R_{\mathrm{s}}}\left(\tau e^{t / \tau}\right)+C_1,
$$

with $\tau=R_{\mathrm{s}} C_{\mathrm{d}}$. Absorb $C_1$ into the overall constant (rename the constant back to $C$ ):

$$
q(t)=e^{-t / \tau}\left[\frac{\Delta E}{R_{\mathrm{s}}} \tau e^{t / \tau}+C\right]=\frac{\Delta E}{R_{\mathrm{s}}} \tau+C e^{-t / \tau} .
$$


Since $\tau / R_{\mathrm{s}}=C_{\mathrm{d}}$, this is

$$
q(t)=\Delta E C_{\mathrm{d}}+C e^{-t / \tau} .
$$


Apply $q(0)=0$ :

$$
0=\Delta E C_{\mathrm{d}}+C \Rightarrow C=-\Delta E C_{\mathrm{d}} .
$$



> [!equation] Voltage-step stored charge (non-faradaic, $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model)
> $$
> q(t)=\Delta E\,C_{\mathrm{d}}\!\left(1-e^{-t/(R_{\mathrm{s}}C_{\mathrm{d}})}\right)
> $$

Stored charge approaches its long-time limit at


$$q(\infty)=\lim _{t \rightarrow \infty} \Delta E C_{\mathrm{d}}\left(1-e^{-t / \tau}\right)=\Delta E C_{\mathrm{d}}$$


and so 

$$q(\tau)=\Delta E C_{\mathrm{d}}\left(1-e^{-1}\right) \approx 0.63 q(\infty)$$

 
This means that the time it takes the capacitor charge $q(t)$ (and the double-layer voltage) to reach $1-e^{-1} \approx 63 \%$ of its final value $q(\infty)=\Delta E C_{\mathrm{d}}$.



Differentiate to obtain the current:
$$
i(t)=\frac{dq}{dt}=\frac{\Delta E}{R_{\mathrm{s}}}\,e^{-t/(R_{\mathrm{s}}C_{\mathrm{d}})}.
$$


> [!equation] Voltage-step charging current (non-faradaic, $R_{\mathrm{s}}$–$C_{\mathrm{d}}$ model)
> $$
> i(t)=\frac{\Delta E}{R_{\mathrm{s}}}\,e^{-t/(R_{\mathrm{s}}C_{\mathrm{d}})}
> $$

The initial value of the current is:

$$
\begin{aligned}
i(t) & =\frac{\Delta E}{R_{\mathrm{s}}} e^{-t /\left(R_{\mathrm{s}} C_{\mathrm{d}}\right)} \\
i\left(0^{+}\right) & =\frac{\Delta E}{R_{\mathrm{s}}} e^{-0^{+} /\left(R_{\mathrm{s}} C_{\mathrm{d}}\right)} \\
& =\frac{\Delta E}{R_{\mathrm{s}}} e^{-\left(0^{+}\right)} \\
& =\frac{\Delta E}{R_{\mathrm{s}}} e^0 \\
& =\frac{\Delta E}{R_{\mathrm{s}}}(1) \\
& =\frac{\Delta E}{R_{\mathrm{s}}} .
\end{aligned}
$$

