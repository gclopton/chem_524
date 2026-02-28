If $a$ is the base $10 \log$ arithm of $n(a=\log n)$, then $n=10^{a}$. On a calculator, you find the logarithm of a number by pressing the "log" button. If you know $a=\log n$ and you wish to find $n$, use the "antilog" button or raise 10 to the power $a$ :

$$
a=\log n
$$

$$
10^{a}=10^{\log n}=n(\Rightarrow n=\operatorname{antilog} a)
$$

Natural logarithms (ln) are based on the number e (= 2.718 281...) instead of 10:

$$
b=\ln n
$$

$$
\mathrm{e}^{b}=\mathrm{e}^{\ln n}=n
$$

On a calculator, you find the $\ln$ of $n$ with the "ln" button. To find $n$ when you know $b=\ln n$, use the $\mathrm{e}^{x}$ key.

Here are some useful properties to know:
$\log (a \cdot b)=\log a+\log b \quad \log 10^{a}=a$
$\log \left(\frac{a}{b}\right)=\log a-\log b \quad a^{b} \cdot a^{c}=a^{(b+c)}$
$\log \left(a^{b}\right)=b \log a \quad \frac{a^{b}}{a^{c}}=a^{(b-c)}$

## Problems

Test yourself by simplifying each expression as much as possible:
(a) $\mathrm{e}^{\ln a}$
(b) $10^{\log a}$
(c) $\log 10^{a}$
(d) $10^{-\log a}$
(e) $\mathrm{e}^{-\ln a^{3}}$
(f) $\mathrm{e}^{\ln a^{-3}}$
(g) $\log \left(10^{1 / a^{3}}\right)$
(h) $\log \left(10^{-a^{2}}\right)$
(i) $\quad \log \left(10^{a^{2}-b}\right)$
(j) $\quad \log \left(2 a^{3} 10^{b^{2}}\right)$
(k) $\mathrm{e}^{(a+\ln b)}$
(l) $10^{[(\log 3)-(4 \log 2)]}$

Solving a logarithmic equation: In working with the Nernst and Henderson-Hasselbalch equations, we will need to solve equations such as

$$
a=b-c \log \frac{d}{g x}
$$

for the variable, $x$. First isolate the log term:

$$
\log \frac{d}{g x}=\frac{(b-a)}{c}
$$

Then raise 10 to the value of each side of the equation:

$$
10^{\log (d / g x)}=10^{(b-a) / c}
$$

But $10^{\log (d / g x)}$ is just $d / g x$, so

$$
\frac{d}{g x}=10^{(b-a) / c} \Rightarrow x=\frac{d}{g 10^{(b-a) / c}}
$$

Converting between $\ln x$ and $\log x$ : The relation between them is derived by writing $x=10^{\log x}$ and taking $\ln$ of both sides:

$$
\ln x=\ln \left(10^{\log x}\right)=(\log x)(\ln 10)
$$

because $\ln a^{b}=b \ln a$.

## Answers

(a) $a$
(b) $a$
(c) $a$
(d) $1 / a$
(e) $1 / a^{3}$
(f) $1 / a^{3}$
(g) $1 / a^{3}$
(h) $-a^{2}$
(i) $a^{2}-b$
(j) $b^{2}+\log \left(2 a^{3}\right)$
(k) $b \mathrm{e}^{a}$
(l) $3 / 16$

The general form of the equation of a straight line is

$$
y=m x+b
$$

$$
\text { where } \begin{aligned}
m & =\text { slope }=\frac{\Delta y}{\Delta x}=\frac{y_{2}-y_{1}}{x_{2}-x_{1}} \\
b & =\text { intercept on } y \text {-axis }
\end{aligned}
$$

The meanings of slope and intercept are illustrated in Figure B-1.

![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-02.jpg?height=352&width=509&top_left_y=640&top_left_x=304)
FIGURE B-1 Parameters of a straight line.

If you know two points $\left[\left(x_{1}, y_{1}\right)\right.$ and $\left.\left(x_{2}, y_{2}\right)\right]$ that lie on the line, you can generate the equation of the line by noting that the slope is the same for every pair of points on the line. Calling some general point on the line $(x, y)$, we can write

$$
\frac{y-y_{1}}{x-x_{1}}=\frac{y_{2}-y_{1}}{x_{2}-x_{1}}=m
$$

which can be rearranged to the form

$$
\begin{aligned}
y-y_{1} & =\left(\frac{y_{2}-y_{1}}{x_{2}-x_{1}}\right)\left(x-x_{1}\right) \\
y & =\underbrace{\left(\frac{y_{2}-y_{1}}{x_{2}-x_{1}}\right)}_{m} x+\underbrace{y_{1}-\left(\frac{y_{2}-y_{1}}{x_{2}-x_{1}}\right) x_{1}}_{b}
\end{aligned}
$$

When you have a series of experimental points that should lie on a line, the best line is generally obtained by the method of least squares, described in Chapter 4. This method gives the slope and the intercept directly. If, instead, you wish to draw the "best" line by eye, you can derive the equation of the line by selecting two points that lie on the line and applying Equation B-1.

![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-02.jpg?height=736&width=486&top_left_y=268&top_left_x=1293)
FIGURE B-2 A linear graph in which one axis is a logarithmic function.

Sometimes you are presented with a linear plot in which $x$ or $y$ or both are nonlinear functions. An example is shown in Figure B-2, in which the potential of an electrode is expressed as a function of the activity of analyte. Given that the slope is 29.6 mV and the line passes through the point $\left(\mathcal{A}=10^{-4}, E=-10.2\right)$, find the equation of the line. To do this, first note that the $y$-axis is linear but the $x$-axis is logarithmic. That is, the function $E$ versus $\mathcal{A}$ is not linear, but $E$ versus $\log \mathcal{A}$ is linear. The form of the straight line should therefore be

$$
\underset{\uparrow}{E}=(29.6) \underbrace{\log \mathcal{A}}_{\substack{\uparrow \\ y}}+b
$$

To find $b$, we can use the coordinates of the one known point in Equation B-1:

$$
\frac{y-y_{1}}{x-x_{1}}=\frac{E-E_{1}}{\log \mathcal{A}-\log \mathcal{A}_{1}}=\frac{E-(-10.2)}{\log \mathcal{A}-\log \left(10^{-4}\right)}=m=29.6
$$

or

$$
\begin{gathered}
E+10.2=29.6 \log \mathcal{A}+(29.6)(4) \\
E(\mathrm{mV})=29.6(\mathrm{mV}) \log \mathcal{A}+108.2(\mathrm{mV})
\end{gathered}
$$

The rules for propagation of uncertainty in Table 3-1 are special cases of a general formula. Suppose you wish to calculate the function, $F$, of several experimental quantities, $x, y, z, \ldots$. If the errors $\left(e_{x}, e_{y}, e_{z}, \ldots\right)$ in $x, y, z, \ldots$ are small, random, and independent of one another, then the uncertainty, $e_{F}$, in the function $F$ is approximately:*

$$
e_{F}=\sqrt{\left(\frac{\partial F}{\partial x}\right)^{2} e_{x}^{2}+\left(\frac{\partial F}{\partial y}\right)^{2} e_{y}^{2}+\left(\frac{\partial F}{\partial z}\right)^{2} e_{z}^{2}+\ldots}
$$

The quantities in parentheses are partial derivatives, which are calculated in the same manner as ordinary derivatives, except that all but one variable are treated as constants. For example, if $F=3 x y^{2}$, then $\partial F / \partial x=3 y^{2}$ and $\partial F / \partial y=(3 x)(2 y)=6 x y$.

As an example of using Equation C-1, let's find the uncertainty in the function

$$
F=x^{y}=(2.00 \pm 0.02)^{3.00 \pm 0.09}
$$

The partial derivatives are

$$
\frac{\partial F}{\partial x}=y x^{y-1} \quad \frac{\partial F}{\partial y}=x^{y} \ln x
$$

Putting these quantities into Equation C-1 gives

$$
\begin{aligned}
e_{F} & =\sqrt{\left(y x^{y-1}\right)^{2} e_{x}^{2}+\left(x^{y} \ln x\right)^{2} e_{y}^{2}} \\
& =\sqrt{y^{2} x^{2 y-2} e_{x}^{2}+x^{2 y}(\ln x)^{2} e_{y}^{2}} \\
& =\sqrt{y^{2} x^{2 y}\left(\frac{e_{x}}{x}\right)^{2}+x^{2 y}(\ln x)^{2} e_{y}^{2}}
\end{aligned}
$$

Multiplying and dividing the second term by $y^{2}$ allows us to rearrange to a more pleasant form:

$$
e_{F}=\sqrt{y^{2} x^{2 y}\left(\frac{e_{x}}{x}\right)^{2}+y^{2} x^{2 y}(\ln x)^{2}\left(\frac{e_{y}}{y}\right)^{2}}
$$

Removing $\sqrt{y^{2} x^{2 y}}=y F$ from both terms gives

$$
e_{F}=y F \sqrt{\left(\frac{e_{x}}{x}\right)^{2}+(\ln x)^{2}\left(\frac{e_{y}}{y}\right)^{2}}
$$

Now for the number crunching. Disregarding uncertainties for a moment, we know that $F=2.00^{3.00}=8.00 \pm$ ? The uncertainty is obtained from the equation above:

$$
e_{F}=3.00 \cdot 8.00 \sqrt{\left(\frac{0.02}{2.00}\right)^{2}+(\ln 2.00)^{2}\left(\frac{0.09}{3.00}\right)^{2}}=0.55
$$

Reasonable answers are $F=8.0_{0} \pm 0.5_{5}$ or $8.0 \pm 0.6$.

[^0]
## Exercises

C-1. Verify the following calculations.
(a) $2.36^{4.39 \pm 0.08}=43.4 \pm 3.0$
(b) $(2.36 \pm 0.06)^{4.39 \pm 0.08}=43.4 \pm 5.7$

C-2. For $F=\sin (2 \pi x y)$, show that

$$
e_{F}=2 \pi x y \cos (2 \pi x y) \sqrt{\left(\frac{e_{x}}{x}\right)^{2}+\left(\frac{e_{y}}{y}\right)^{2}}
$$

## Covariance in Propagation of Uncertainty

Equation C-1 presumes that errors in $x, y$, and $z$ are independent of one another. A common case in which this is not true is when we use the leastsquares slope and intercept to compute a new quantity, such as the value of $x$ from an observed value of $y$. In general, uncertainties in the slope and intercept are correlated, so they are not independent errors.

Let's restrict our attention to a function, $F$, of the two experimental parameters, $m$ and $b$, whose uncertainties are $s_{m}$ and $s_{b}$. If the uncertainties are correlated, the equation for propagation of uncertainty is ${ }^{\dagger}$

$$
e_{F}=\sqrt{\underbrace{\left(\frac{\partial F}{\partial m}\right)^{2} s_{m}^{2}+\left(\frac{\partial F}{\partial b}\right)^{2} s_{b}^{2}}_{\begin{array}{c}
\text { Variance terms from } \\
\text { Equation C-1 }
\end{array}}+\underbrace{2\left(\frac{\partial F}{\partial m}\right)\left(\frac{\partial F}{\partial b}\right) s_{m b}}_{\begin{array}{c}
\text { Covariance accounts for } \\
\text { correlation of } m \text { and } b
\end{array}}}
$$

The last term in Equation C-2 reflects the fact that uncertainties in $m$ and $b$ are not independent of each other. The quantity $s_{m b}$ is called the covariance and it can be positive or negative.

In linear least-squares analysis, the variance and covariance are ${ }^{\ddagger}$
Variance:

$$
s_{m}^{2}=\frac{s_{y}^{2} n}{D} \quad s_{b}^{2}=\frac{s_{y}^{2} \sum\left(x_{i}^{2}\right)}{D}
$$

(Equations 4-21 and 4-22)

## Covariance:

$$
s_{m b}=\frac{-s_{y}^{2} \sum\left(x_{i}\right)}{D}
$$

where $s_{y}^{2}$ is the square of Equation 4-20, $D$ is given by Equation 4-18, and $n$ is the number of data points.

[^1](Continued)

## EXAMPLE Finding the $\boldsymbol{x}$-Intercept

For the line $y=m x+b$, the $x$-intercept occurs when $y=0$, or $x=-b / m$. Let's designate the $x$-intercept as the function $F=-b / m$. Find the $x$-intercept and its uncertainty for the least-squares line in Figure 4-11.

Solution The following quantities are computed in Section 4-7:

$$
\begin{array}{llll}
m=0.61538 & s_{m}^{2}=0.0029586 & s_{y}^{2}=0.038462 & \sum\left(x_{i}\right)=14 \\
b=1.34615 & s_{b}^{2}=0.045859 & D=52 &
\end{array}
$$

The covariance in Equation C-3 is therefore

$$
s_{m b}=\frac{-s_{y}^{2} \sum\left(x_{i}\right)}{D}=\frac{-(0.038462)(14)}{52}=-0.010355
$$

The $x$-intercept is just $F=-b / m=-(1.34615) /(0.61538)=-2.1875$.
To find the uncertainty in $F$, we use Equation C -2. The derivatives in C-2 are

$$
\begin{aligned}
& \frac{\partial F}{\partial m}=\frac{\partial(-b / m)}{\partial m}=\frac{b}{m^{2}}=\frac{1.34615}{0.61538^{2}}=3.5547 \\
& \frac{\partial F}{\partial b}=\frac{\partial(-b / m)}{\partial b}=\frac{-1}{m}=\frac{-1}{0.61538}=-1.6250
\end{aligned}
$$

Now we can evaluate the uncertainty with Equation C-2:

$$
\begin{aligned}
e_{F} & =\sqrt{\left(\frac{\partial F}{\partial m}\right)^{2} s_{m}^{2}+\left(\frac{\partial F}{\partial b}\right)^{2} s_{b}^{2}+2\left(\frac{\partial F}{\partial m}\right)\left(\frac{\partial F}{\partial b}\right) s_{m b}} \\
& =\sqrt{\left(\begin{array}{l}
(3.5547)^{2}(0.0029586)+ \\
(-1.6250)^{2}(0.045859)+ \\
2(3.5547)(-1.6250)(-0.010355)
\end{array}\right.} \\
& =0.52736
\end{aligned}
$$

The final answer can now be written with a reasonable number of digits:

$$
F=-2.1875 \pm 0.52736=-2.1_{9} \pm 0.5_{3}
$$

If we had used Equation C-1 and ignored the covariance term in Equation C -2, we would have computed an uncertainty of $\pm 0.4_{0}$.

To learn how to compute variance and covariance and to see how to include weighting factors in least-squares curve fitting, see J. Tellinghuisen, "Understanding Least Squares Through Monte Carlo Calculations," J. Chem. Ed. 2005, 82, 157.

The oxidation number, or oxidation state, is a bookkeeping device used to keep track of the number of electrons formally associated with a particular element. The oxidation number is meant to tell how many electrons have been lost or gained by a neutral atom when it forms a compound. Because oxidation numbers have no real physical meaning, they are somewhat arbitrary, and not all chemists will assign the same oxidation number to a given element in an unusual compound. However, there are some ground rules that provide a useful start.

1. The oxidation number of an element by itself-e.g., $\mathrm{Cu}(s)$ or $\mathrm{Cl}_{2}(g)$-is 0 .
2. The oxidation number of H is almost always +1 , except in metal hydrides-e.g., NaH -in which H is -1 .
3. The oxidation number of oxygen is almost always -2 . The only common exceptions are peroxides, in which two oxygen atoms are connected and each has an oxidation number of -1 . Two examples are hydrogen peroxide ( $\mathrm{H}-\mathrm{O}-\mathrm{O}-\mathrm{H}$ ) and its anion ( $\mathrm{H}-\mathrm{O}-\mathrm{O}^{-}$). The oxidation number of oxygen in gaseous $\mathrm{O}_{2}$ is, of course, 0 .
4. The alkali metals (Li, Na, K, Rb, Cs, Fr) almost always have an oxidation number of +1 . The alkaline earth metals ( $\mathrm{Be}, \mathrm{Mg}, \mathrm{Ca}, \mathrm{Sr}$, $\mathrm{Ba}, \mathrm{Ra}$ ) are almost always in the +2 oxidation state.
5. The halogens $(\mathrm{F}, \mathrm{Cl}, \mathrm{Br}, \mathrm{I})$ are usually in the -1 oxidation state. Exceptions occur when two different halogens are bound to each other or when a halogen is bound to more than one atom. When different halogens are bound to each other, we assign the oxidation number -1 to the more electronegative halogen.

The sum of the oxidation numbers of each atom in a molecule must equal the charge of the molecule. In $\mathrm{H}_{2} \mathrm{O}$, for example, we have

$$
\begin{array}{ll}
2 \text { hydrogen }=2(+1) & =+2 \\
\text { oxygen } & =\frac{-2}{0} \\
\text { net charge } &
\end{array}
$$

In $\mathrm{SO}_{4}^{2-}$, sulfur must have an oxidation number of +6 so that the sum of the oxidation numbers will be -2 :

$$
\begin{array}{ll}
\text { oxygen }=4(-2) & =-8 \\
\text { sulfur } & =\frac{+6}{-2} \\
\text { net charge } &
\end{array}
$$

In benzene $\left(\mathrm{C}_{6} \mathrm{H}_{6}\right)$, the oxidation number of each carbon must be -1 if hydrogen is assigned the number +1 . In cyclohexane $\left(\mathrm{C}_{6} \mathrm{H}_{12}\right)$, the oxidation number of each carbon must be -2 , for the same reason. The carbons in benzene are in a higher oxidation state than those in cyclohexane.

The oxidation number of iodine in $\mathrm{ICl}_{2}^{-}$is +1 . This is unusual, because halogens are usually -1 . However, because chlorine is more electronegative than iodine, we assign Cl as -1 , thereby forcing I to be +1 .

The oxidation number of As in $\mathrm{As}_{2} \mathrm{~S}_{3}$ is +3 , and the value for S is -2 . This is arbitrary but reasonable. Because S is more electronegative than As, we make S negative and As positive; and, because S is in the same family as oxygen, which is usually -2 , we assign S as -2 , thus leaving As as +3.

The oxidation number of S in $\mathrm{S}_{4} \mathrm{O}_{6}^{2-}$ (tetrathionate) is +2.5 . The fractional oxidation state comes about because six O atoms contribute -12 . Because the charge is -2 , the four S atoms must contribute +10 . The average oxidation number of S must be $+\frac{10}{4}=2.5$.

The oxidation number of Fe in $\mathrm{K}_{3} \mathrm{Fe}(\mathrm{CN})_{6}$ is +3 . To make this assignment, we first recognize cyanide ( $\mathrm{CN}^{-}$) as a common ion that carries a charge of -1 . Six cyanide ions give -6 , and three potassium ions $\left(\mathrm{K}^{+}\right)$ give +3 . Therefore, Fe should have an oxidation number of +3 for the whole formula to be neutral. In this approach, it is not necessary to assign
(a) $\mathbf{A g B r}$
(b) $\mathrm{S}_{2} \mathrm{O}_{3}^{2-}$
(c) $\mathrm{SeF}_{6}$
(d) $\mathrm{HS}_{2} \mathrm{O}_{3}^{-}$
(e) $\mathrm{HO}_{2}$
(f) NO
(g) $\mathbf{C r}^{3+}$
(h) $\mathrm{MnO}_{2}$
(i) $\quad \mathrm{Pb}(\mathrm{OH})_{3}^{-}$
(j) $\mathrm{Fe}(\mathrm{OH})_{3}$
(k) $\mathrm{ClO}^{-}$
(l) $\mathrm{K}_{4} \mathrm{Fe}(\mathrm{CN})_{6}$
(m) $\mathrm{ClO}_{2}$
(n) $\mathrm{ClO}_{2}^{-}$
(o) $\mathbf{M n}(\mathrm{CN})_{6}^{4-}$
(p) $\mathrm{N}_{2}$
(q) $\mathrm{NH}_{4}^{+}$
(r) $\mathrm{N}_{2} \mathrm{H}_{5}^{+}$
(s) $\mathrm{HAsO}_{3}^{2-}$
(t) $\mathrm{Co}_{2}(\mathrm{CO})_{8}(\mathrm{CO}$ group is neutral)
(u) $\left(\mathrm{CH}_{3}\right)_{4} \mathrm{Li}_{4}$
(v) $\mathrm{P}_{4} \mathrm{O}_{10}$
(w) $\mathrm{C}_{2} \mathrm{H}_{6} \mathrm{O}$ (ethanol, $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{OH}$ )
(x) $\mathrm{VO}\left(\mathrm{SO}_{4}\right)$
(y) $\mathrm{Fe}_{3} \mathrm{O}_{4}$
(z) $\mathrm{C}_{3} \mathrm{H}_{3}^{+}$

Structure:
<img class="imgSvg" id = "mm3x3s5k08ycfht6lpz" src="data:image/svg+xml;base64,PHN2ZyBpZD0ic21pbGVzLW1tM3gzczVrMDh5Y2ZodDZscHoiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDEyOSA4Ni41NDc3MjcyMTQ3NTEzOCIgc3R5bGU9IndpZHRoOiAxMjguNTQ3NzI3MjE0NzUxMzhweDsgaGVpZ2h0OiA4Ni41NDc3MjcyMTQ3NTEzOHB4OyBvdmVyZmxvdzogdmlzaWJsZTsiPjxkZWZzPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZS1tbTN4M3M1azA4eWNmaHQ2bHB6LTEiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iNjIuNDkxOTU4MTE3NTU2NTEiIHkxPSIyNy4yMzY2ODE0MTAyMDE3NiIgeDI9IjgwLjMxMTA0NTAwNDgyMjc2IiB5Mj0iNDUuMDU1Nzc2Mjk0NzM2NjIiPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIyMCUiPjwvc3RvcD48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMTAwJSI+PC9zdG9wPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lLW1tM3gzczVrMDh5Y2ZodDZscHotMyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSI2NC4yNzM4Njg2MDU2Njg1OCIgeTE9IjIxIiB4Mj0iODYuNTQ3NzI3MjE0NzUxMzkiIHkyPSI0My4yNzM4Njg2MDU2Njg1NyI+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjIwJSI+PC9zdG9wPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmUtbW0zeDNzNWswOHljZmh0Nmxwei01IiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjQyIiB5MT0iNDMuMjczODU4NjA5MDgyODEiIHgyPSI2NC4yNzM4Njg2MDU2Njg1OCIgeTI9IjIxIj48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMjAlIj48L3N0b3A+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjEwMCUiPjwvc3RvcD48L2xpbmVhckdyYWRpZW50PjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZS1tbTN4M3M1azA4eWNmaHQ2bHB6LTciIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iNjQuMjczODU4NjA5MDgyODIiIHkxPSI2NS41NDc3MjcyMTQ3NTEzOCIgeDI9Ijg2LjU0NzcyNzIxNDc1MTM5IiB5Mj0iNDMuMjczODY4NjA1NjY4NTciPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIyMCUiPjwvc3RvcD48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMTAwJSI+PC9zdG9wPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lLW1tM3gzczVrMDh5Y2ZodDZscHotOSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSI0OC4yMzY2ODIyMDk5Mjg2MjQiIHkxPSI0MS40OTE5NTA5MjAwMTQ3NiIgeDI9IjY2LjA1NTc2OTA5NzE5NDg4IiB5Mj0iNTkuMzExMDQ1ODA0NTQ5NjIiPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIyMCUiPjwvc3RvcD48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMTAwJSI+PC9zdG9wPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lLW1tM3gzczVrMDh5Y2ZodDZscHotMTEiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iNDIiIHkxPSI0My4yNzM4NTg2MDkwODI4MSIgeDI9IjY0LjI3Mzg1ODYwOTA4MjgyIiB5Mj0iNjUuNTQ3NzI3MjE0NzUxMzgiPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIyMCUiPjwvc3RvcD48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMTAwJSI+PC9zdG9wPjwvbGluZWFyR3JhZGllbnQ+PC9kZWZzPjxtYXNrIGlkPSJ0ZXh0LW1hc2stbW0zeDNzNWswOHljZmh0NmxweiI+PHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgZmlsbD0id2hpdGUiPjwvcmVjdD48L21hc2s+PHN0eWxlPgogICAgICAgICAgICAgICAgLmVsZW1lbnQtbW0zeDNzNWswOHljZmh0NmxweiB7CiAgICAgICAgICAgICAgICAgICAgZm9udDogMTRweCBIZWx2ZXRpY2EsIEFyaWFsLCBzYW5zLXNlcmlmOwogICAgICAgICAgICAgICAgICAgIGFsaWdubWVudC1iYXNlbGluZTogJ21pZGRsZSc7CiAgICAgICAgICAgICAgICB9CiAgICAgICAgICAgICAgICAuc3ViLW1tM3gzczVrMDh5Y2ZodDZscHogewogICAgICAgICAgICAgICAgICAgIGZvbnQ6IDguNHB4IEhlbHZldGljYSwgQXJpYWwsIHNhbnMtc2VyaWY7CiAgICAgICAgICAgICAgICB9CiAgICAgICAgICAgIDwvc3R5bGU+PGcgbWFzaz0idXJsKCN0ZXh0LW1hc2stbW0zeDNzNWswOHljZmh0NmxweikiPjxsaW5lIHgxPSI2Mi40OTE5NTgxMTc1NTY1MSIgeTE9IjI3LjIzNjY4MTQxMDIwMTc2IiB4Mj0iODAuMzExMDQ1MDA0ODIyNzYiIHkyPSI0NS4wNTU3NzYyOTQ3MzY2MiIgc3R5bGU9InN0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1kYXNoYXJyYXk6bm9uZTtzdHJva2Utd2lkdGg6MS4yNiIgc3Ryb2tlPSJ1cmwoJyNsaW5lLW1tM3gzczVrMDh5Y2ZodDZscHotMScpIj48L2xpbmU+PGxpbmUgeDE9IjY0LjI3Mzg2ODYwNTY2ODU4IiB5MT0iMjEiIHgyPSI4Ni41NDc3MjcyMTQ3NTEzOSIgeTI9IjQzLjI3Mzg2ODYwNTY2ODU3IiBzdHlsZT0ic3Ryb2tlLWxpbmVjYXA6cm91bmQ7c3Ryb2tlLWRhc2hhcnJheTpub25lO3N0cm9rZS13aWR0aDoxLjI2IiBzdHJva2U9InVybCgnI2xpbmUtbW0zeDNzNWswOHljZmh0Nmxwei0zJykiPjwvbGluZT48bGluZSB4MT0iNDIiIHkxPSI0My4yNzM4NTg2MDkwODI4MSIgeDI9IjY0LjI3Mzg2ODYwNTY2ODU4IiB5Mj0iMjEiIHN0eWxlPSJzdHJva2UtbGluZWNhcDpyb3VuZDtzdHJva2UtZGFzaGFycmF5Om5vbmU7c3Ryb2tlLXdpZHRoOjEuMjYiIHN0cm9rZT0idXJsKCcjbGluZS1tbTN4M3M1azA4eWNmaHQ2bHB6LTUnKSI+PC9saW5lPjxsaW5lIHgxPSI2NC4yNzM4NTg2MDkwODI4MiIgeTE9IjY1LjU0NzcyNzIxNDc1MTM4IiB4Mj0iODYuNTQ3NzI3MjE0NzUxMzkiIHkyPSI0My4yNzM4Njg2MDU2Njg1NyIgc3R5bGU9InN0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1kYXNoYXJyYXk6bm9uZTtzdHJva2Utd2lkdGg6MS4yNiIgc3Ryb2tlPSJ1cmwoJyNsaW5lLW1tM3gzczVrMDh5Y2ZodDZscHotNycpIj48L2xpbmU+PGxpbmUgeDE9IjQ4LjIzNjY4MjIwOTkyODYyNCIgeTE9IjQxLjQ5MTk1MDkyMDAxNDc2IiB4Mj0iNjYuMDU1NzY5MDk3MTk0ODgiIHkyPSI1OS4zMTEwNDU4MDQ1NDk2MiIgc3R5bGU9InN0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1kYXNoYXJyYXk6bm9uZTtzdHJva2Utd2lkdGg6MS4yNiIgc3Ryb2tlPSJ1cmwoJyNsaW5lLW1tM3gzczVrMDh5Y2ZodDZscHotOScpIj48L2xpbmU+PGxpbmUgeDE9IjQyIiB5MT0iNDMuMjczODU4NjA5MDgyODEiIHgyPSI2NC4yNzM4NTg2MDkwODI4MiIgeTI9IjY1LjU0NzcyNzIxNDc1MTM4IiBzdHlsZT0ic3Ryb2tlLWxpbmVjYXA6cm91bmQ7c3Ryb2tlLWRhc2hhcnJheTpub25lO3N0cm9rZS13aWR0aDoxLjI2IiBzdHJva2U9InVybCgnI2xpbmUtbW0zeDNzNWswOHljZmh0Nmxwei0xMScpIj48L2xpbmU+PC9nPjxnPjx0ZXh0IHg9IjY0LjI3Mzg2ODYwNTY2ODU4IiB5PSIyMSIgY2xhc3M9ImRlYnVnIiBmaWxsPSIjZmYwMDAwIiBzdHlsZT0iCiAgICAgICAgICAgICAgICBmb250OiA1cHggRHJvaWQgU2Fucywgc2Fucy1zZXJpZjsKICAgICAgICAgICAgIj48L3RleHQ+PHRleHQgeD0iODYuNTQ3NzI3MjE0NzUxMzkiIHk9IjQzLjI3Mzg2ODYwNTY2ODU3IiBjbGFzcz0iZGVidWciIGZpbGw9IiNmZjAwMDAiIHN0eWxlPSIKICAgICAgICAgICAgICAgIGZvbnQ6IDVweCBEcm9pZCBTYW5zLCBzYW5zLXNlcmlmOwogICAgICAgICAgICAiPjwvdGV4dD48dGV4dCB4PSI2NC4yNzM4NTg2MDkwODI4MiIgeT0iNjUuNTQ3NzI3MjE0NzUxMzgiIGNsYXNzPSJkZWJ1ZyIgZmlsbD0iI2ZmMDAwMCIgc3R5bGU9IgogICAgICAgICAgICAgICAgZm9udDogNXB4IERyb2lkIFNhbnMsIHNhbnMtc2VyaWY7CiAgICAgICAgICAgICI+PC90ZXh0Pjx0ZXh0IHg9IjQyIiB5PSI0My4yNzM4NTg2MDkwODI4MSIgY2xhc3M9ImRlYnVnIiBmaWxsPSIjZmYwMDAwIiBzdHlsZT0iCiAgICAgICAgICAgICAgICBmb250OiA1cHggRHJvaWQgU2Fucywgc2Fucy1zZXJpZjsKICAgICAgICAgICAgIj48L3RleHQ+PC9nPjwvc3ZnPg=="/>
individual oxidation numbers to carbon and nitrogen, as long as we recognize that the charge of CN is -1 .

## Problems

Answers are given at the end of this appendix.
D-1. Write the oxidation state of the boldface atom in each of the following species.

D-2. Identify the oxidizing agent and the reducing agent on the left side of each of the following reactions.
(a) $\mathrm{Cr}_{2} \mathrm{O}_{7}^{2-}+3 \mathrm{Sn}^{2+}+14 \mathrm{H}^{+} \rightarrow 2 \mathrm{Cr}^{3+}+3 \mathrm{Sn}^{4+}+7 \mathrm{H}_{2} \mathrm{O}$
(b) $4 \mathrm{I}^{-}+\mathrm{O}_{2}+4 \mathrm{H}^{+} \rightarrow 2 \mathrm{I}_{2}+2 \mathrm{H}_{2} \mathrm{O}$
(c)
![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-05.jpg?height=117&width=789&top_left_y=1297&top_left_x=1293)
(d)
![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-05.jpg?height=116&width=862&top_left_y=1415&top_left_x=1287)
(e)
![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-05.jpg?height=85&width=616&top_left_y=1520&top_left_x=1289)
(f)

$$
\mathrm{I}_{2}+\mathrm{OH}^{-} \underset{\text { Hypoiodous }}{\mathrm{HOI}+\mathrm{I}^{-}}
$$

acid

## Balancing Redox Reactions

To balance a reaction involving oxidation and reduction, we must first identify which element is oxidized and which is reduced. We then break the net reaction into two imaginary half-reactions, one of which involves only oxidation and the other only reduction. Although free electrons never appear in a balanced net reaction, they do appear in balanced half-reactions. If we are dealing with aqueous solutions, we proceed to balance each half-reaction, using $\mathrm{H}_{2} \mathrm{O}$ and either $\mathrm{H}^{+}$or $\mathrm{OH}^{-}$, as necessary. A reaction is balanced when the number of atoms of each element is the same on both sides and the net charge is the same on both sides.*

[^2]
## Acidic Solutions

Here are the steps we will follow:

1. Assign oxidation numbers to the elements that are oxidized or reduced.
2. Break the reaction into two half-reactions, one involving oxidation and the other reduction.
3. For each half-reaction, balance the number of atoms that are oxidized or reduced.
4. Balance the electrons to account for the change in oxidation number by adding electrons to one side of each half-reaction.
5. Balance oxygen atoms by adding $\mathrm{H}_{2} \mathrm{O}$ to one side of each halfreaction.
6. Balance the H atoms by adding $\mathrm{H}^{+}$to one side of each half-reaction.
7. Multiply each half-reaction by the number of electrons in the other half-reaction so that the number of electrons on each side of the total reaction will cancel. Then add the two half-reactions and simplify to the smallest integral coefficients.

## EXAMPLE Balancing a Redox Equation

Balance the following equation using $\mathrm{H}^{+}$, but not $\mathrm{OH}^{-}$:

$$
\underset{\text { Permanganate }}{\mathrm{Fe}^{2+}}+\underset{+2}{\mathrm{MnO}_{4}^{-}} \underset{+3}{\mathrm{Fe}^{3+}}+\underset{+2}{\mathrm{Mn}^{2+}}
$$

## Solution

1. Assign oxidation numbers. They are assigned for Fe and Mn in each species in the above reaction.
2. Break the reaction into two half-reactions.
$\begin{array}{lc}\text { Oxidation half-reaction: } & \mathrm{Fe}^{2+} \rightleftharpoons \mathrm{Fe}^{3+} \\ +2 & +3\end{array}$
3. Balance the atoms that are oxidized or reduced. Because there is only one Fe or Mn in each species on each side of the equation, the atoms of Fe and Mn are already balanced.
4. Balance electrons. Electrons are added to account for the change in each oxidation state.

$$
\begin{aligned}
\mathrm{Fe}^{2+} & \rightleftharpoons \mathrm{Fe}^{3+}+\mathrm{e}^{-} \\
\mathrm{MnO}_{4}^{-}+5 \mathrm{e}^{-} & \rightleftharpoons \mathrm{Mn}^{2+}
\end{aligned}
$$

In the second case, we need $5 \mathrm{e}^{-}$on the left side to take Mn from +7 to +2 .
5. Balance oxygen atoms. There are no oxygen atoms in the Fe half-reaction. There are four oxygen atoms on the left side of the Mn reaction, so we add four molecules of $\mathrm{H}_{2} \mathrm{O}$ to the right side:

$$
\mathrm{MnO}_{4}^{-}+5 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O}
$$

6. Balance hydrogen atoms. The Fe equation is already balanced. The Mn equation needs $8 \mathrm{H}^{+}$on the left.

$$
\mathrm{MnO}_{4}^{-}+5 \mathrm{e}^{-}+8 \mathrm{H}^{+} \rightarrow \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O}
$$

At this point, each half-reaction must be completely balanced (the same number of atoms and charge on each side) or you have made a mistake.
7. Multiply and add the reactions. We multiply the Fe equation by 5 and the Mn equation by 1 and add:

$$
\begin{aligned}
5 \mathrm{Fe}^{2+} & \rightleftharpoons 5 \mathrm{Fe}^{3+}+5 \mathrm{e}^{-} \\
\mathrm{MnO}_{4}^{-}+5 \mathrm{e}^{-}+8 \mathrm{H}^{+} & \rightleftharpoons \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O} \\
\hline 5 \mathrm{Fe}^{2+}+\mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+} & \rightleftharpoons 5 \mathrm{Fe}^{3+}+\mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O}
\end{aligned}
$$

The total charge on each side is +17 , and we find the same number of atoms of each element on each side. The equation is balanced.

## EXAMPLE A Reverse Disproportionation

Now try the next reaction, which represents the reverse of a disproportionation. (In a disproportionation, an element in one oxidation state reacts to give the same element in higher and lower oxidation states.)

$$
\begin{array}{ccccc}
\mathrm{I}_{2}+ & \mathrm{IO}_{3}^{-} & \mathrm{Cl}^{-} & \rightleftharpoons & \mathrm{ICl}_{2}^{-} \\
0 & +5 & & -1 & \\
\text { Iodine } & \text { Iodate } & & &
\end{array}
$$

## Solution

1. The oxidation numbers are assigned above. Note that chlorine has an oxidation number of -1 on both sides of the equation. Only iodine is involved in electron transfer.
2. Oxidation half-reaction: $\quad \mathrm{I}_{2} \rightleftharpoons \mathrm{ICl}_{2}^{-}$
$\begin{array}{lll} & 0 & +1 \\ \text { Reduction half-reaction: } & \mathrm{IO}_{3}^{-} & \rightleftharpoons \mathrm{ICl}_{2}^{-} \\ & +5 & +1\end{array}$
3. We need to balance I atoms in the first reaction and add Cl ${ }^{-}$to each reaction to balance Cl .

$$
\begin{gathered}
\mathrm{I}_{2}+4 \mathrm{Cl}^{-} \rightleftharpoons 2 \mathrm{ICl}_{2}^{-} \\
\mathrm{IO}_{3}^{-}+2 \mathrm{Cl}^{-} \rightleftharpoons \mathrm{ICl}_{2}^{-}
\end{gathered}
$$

4. Now add electrons to each.

$$
\begin{gathered}
\mathrm{I}_{2}+4 \mathrm{Cl}^{-} \rightleftharpoons 2 \mathrm{ICl}_{2}^{-}+2 \mathrm{e}^{-} \\
\mathrm{IO}_{3}^{-}+2 \mathrm{Cl}^{-}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{ICl}_{2}^{-}
\end{gathered}
$$

The first reaction needs $2 \mathrm{e}^{-}$because there are two I atoms, each of which changes from 0 to +1 .
5. The second reaction needs $3 \mathrm{H}_{2} \mathrm{O}$ on the right side to balance oxygen atoms.

$$
\mathrm{IO}_{3}^{-}+2 \mathrm{Cl}^{-}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{ICl}_{2}^{-}+3 \mathrm{H}_{2} \mathrm{O}
$$

6. The first reaction is balanced, but the second needs $6 \mathrm{H}^{+}$on the left.

$$
\mathrm{IO}_{3}^{-}+2 \mathrm{Cl}^{-}+4 \mathrm{e}^{-}+6 \mathrm{H}^{+} \rightleftharpoons \mathrm{ICl}_{2}^{-}+3 \mathrm{H}_{2} \mathrm{O}
$$

As a check, the charge on each side of this half-reaction is -1 , and all atoms are balanced.
7. Multiply and add.

$$
\begin{aligned}
2\left(\mathrm{I}_{2}+4 \mathrm{Cl}^{-}\right. & \left.\rightleftharpoons 2 \mathrm{ICl}_{2}^{-}+2 \mathrm{e}^{-}\right) \\
\mathrm{IO}_{3}^{-}+2 \mathrm{Cl}^{-}+4 \mathrm{e}^{-}+6 \mathrm{H}^{+} & \rightleftharpoons \mathrm{ICl}_{2}^{-}+3 \mathrm{H}_{2} \mathrm{O} \\
\hline 2 \mathrm{I}_{2}+\mathrm{IO}_{3}^{-}+10 \mathrm{Cl}^{-}+6 \mathrm{H}^{+} & \rightleftharpoons 5 \mathrm{ICl}_{2}^{-}+3 \mathrm{H}_{2} \mathrm{O}
\end{aligned}
$$

We multiplied the first reaction by 2 so that there would be the same number of electrons in each half-reaction. You could have multiplied the first reaction by 4 and the second by 2 , but then all coefficients would simply be doubled. We customarily write the smallest coefficients.

## Basic Solutions

The method many people prefer for basic solutions is to balance the equation first with $\mathrm{H}^{+}$. The answer can then be converted into one in which $\mathrm{OH}^{-}$is used instead. This is done by adding to each side of the equation a number of hydroxide ions equal to the number of $\mathrm{H}^{+}$ions appearing in the equation. For example, to balance Equation D-1 with $\mathrm{OH}^{-}$instead of $\mathrm{H}^{+}$, proceed as follows:

$$
\begin{gathered}
\frac{2 \mathrm{I}_{2}+\mathrm{IO}_{3}^{-}+10 \mathrm{Cl}^{-}}{}+6 \mathrm{H}^{+} \rightleftharpoons 5 \mathrm{ICl}_{2}+3 \mathrm{H}_{2} \mathrm{O} \\
+6 \mathrm{OH}^{-} \\
\frac{+6 \mathrm{OH}^{-}}{\mathrm{I}_{2}+\mathrm{IO}_{3}^{-}+10 \mathrm{Cl}^{-}} \underbrace{+6 \mathrm{H}^{+}+6 \mathrm{OH}^{-}}_{6 \mathrm{H}_{2} \mathrm{O}} \rightleftharpoons 5 \mathrm{ICl}_{2}+3 \mathrm{H}_{2} \mathrm{O}+6 \mathrm{OH}^{-} \\
\Downarrow \\
3 \mathrm{H}_{2} \mathrm{O}
\end{gathered}
$$

Realizing that $6 \mathrm{H}^{+}+6 \mathrm{OH}^{-}=6 \mathrm{H}_{2} \mathrm{O}$, and canceling $3 \mathrm{H}_{2} \mathrm{O}$ on each side, gives the final result:

$$
2 \mathrm{I}_{2}+\mathrm{IO}_{3}^{-}+10 \mathrm{Cl}^{-}+3 \mathrm{H}_{2} \mathrm{O} \rightleftharpoons 5 \mathrm{ICl}_{2}+6 \mathrm{OH}^{-}
$$

## Problems

D-3. Balance the following reactions by using $\mathrm{H}^{+}$but not $\mathrm{OH}^{-}$.
(a) $\mathrm{Fe}^{3+}+\mathrm{Hg}_{2}^{2+} \rightleftharpoons \mathrm{Fe}^{2+}+\mathrm{Hg}^{2+}$
(b) $\mathrm{Ag}+\mathrm{NO}_{3}^{-} \rightleftharpoons \mathrm{Ag}^{+}+\mathrm{NO}$
(c) $\mathrm{VO}^{2+}+\mathrm{Sn}^{2+} \rightleftharpoons \mathrm{V}^{3+}+\mathrm{Sn}^{4+}$
(d) $\mathrm{SeO}_{4}^{2-}+\mathrm{Hg}+\mathrm{Cl}^{-} \rightleftharpoons \mathrm{SeO}_{3}^{2-}+\mathrm{Hg}_{2} \mathrm{Cl}_{2}$
(e) $\mathrm{CuS}+\mathrm{NO}_{3}^{-} \rightleftharpoons \mathrm{Cu}^{2+}+\mathrm{SO}_{4}^{2-}+\mathrm{NO}$
(f) $\mathrm{S}_{2} \mathrm{O}_{3}^{2-}+\mathrm{I}_{2} \rightleftharpoons \mathrm{I}^{-}+\mathrm{S}_{4} \mathrm{O}_{6}^{2-}$
(g) $\mathrm{ClO}_{3}^{-}+\mathrm{As}_{2} \mathrm{~S}_{3} \rightleftharpoons \mathrm{Cl}^{-}+\mathrm{H}_{2} \mathrm{AsO}_{4}^{-}+\mathrm{SO}_{4}^{2-}$
(h)
![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-07.jpg?height=112&width=526&top_left_y=491&top_left_x=308)
(i) $\mathrm{MnO}_{4}^{2-} \rightleftharpoons \mathrm{MnO}_{2}+\mathrm{MnO}_{4}^{-}$
(j) $\mathrm{Hg}_{2} \mathrm{SO}_{4}+\mathrm{Ca}^{2+}+\mathrm{S}_{8} \rightleftharpoons \mathrm{Hg}_{2}^{2+}+\mathrm{CaS}_{2} \mathrm{O}_{3}$
(k) $\mathrm{ClO}_{3}^{-} \rightleftharpoons \mathrm{Cl}_{2}+\mathrm{O}_{2}$

D-4. Balance the following equations by using $\mathrm{OH}^{-}$but not $\mathrm{H}^{+}$.
(a) $\mathrm{PbO}_{2}+\mathrm{Cl}^{-} \rightleftharpoons \mathrm{ClO}^{-}+\mathrm{Pb}(\mathrm{OH})_{3}^{-}$
(b) $\mathrm{HNO}_{2}+\mathrm{SbO}^{+} \rightleftharpoons \mathrm{NO}+\mathrm{Sb}_{2} \mathrm{O}_{5}$
(c) $\mathrm{Ag}_{2} \mathrm{~S}+\mathrm{CN}^{-}+\mathrm{O}_{2} \rightleftharpoons \mathrm{~S}+\mathrm{Ag}(\mathrm{CN})_{2}^{-}+\mathrm{OH}^{-}$
(d) $\mathrm{HO}_{2}^{-}+\mathrm{Cr}(\mathrm{OH})_{3}^{-} \rightleftharpoons \mathrm{CrO}_{4}^{2-}+\mathrm{OH}^{-}$
(e) $\mathrm{ClO}_{2}+\mathrm{OH}^{-} \rightleftharpoons \mathrm{ClO}_{2}^{-}+\mathrm{ClO}_{3}^{-}$
(f) $\mathrm{WO}_{3}^{-}+\mathrm{O}_{2} \rightleftharpoons \mathrm{HW}_{6} \mathrm{O}_{21}^{5-}+\mathrm{OH}^{-}$
(g) $\mathrm{Mn}_{2} \mathrm{O}_{3}+\mathrm{CN}^{-} \rightleftharpoons \mathrm{Mn}(\mathrm{CN})_{6}^{4-}+(\mathrm{CN})_{2}$
(h) $\mathrm{Cu}^{2+}+\mathrm{H}_{2} \rightleftharpoons \mathrm{Cu}+\mathrm{H}_{2} \mathrm{O}$
(i) $\mathrm{BH}_{4}^{-}+\mathrm{H}_{2} \mathrm{O} \rightleftharpoons \mathrm{H}_{3} \mathrm{BO}_{3}+\mathrm{H}_{2}$
(j) $\mathrm{Mn}_{2} \mathrm{O}_{3}+\mathrm{Hg}+\mathrm{CN}^{-} \rightleftharpoons \mathrm{Mn}(\mathrm{CN})_{6}^{4-}+\mathrm{Hg}(\mathrm{CN})_{2}$
(k)
<img class="imgSvg" id = "mm3x3s5no7fhdugsatb" src="data:image/svg+xml;base64,PHN2ZyBpZD0ic21pbGVzLW1tM3gzczVubzdmaGR1Z3NhdGIiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgdmlld0JveD0iMCAwIDI0OCA4OS4yNTAwNTUwOTQ2OTE1IiBzdHlsZT0id2lkdGg6IDI0Ny42Nzg4MDEzMTUyMjE4NXB4OyBoZWlnaHQ6IDg5LjI1MDA1NTA5NDY5MTVweDsgb3ZlcmZsb3c6IHZpc2libGU7Ij48ZGVmcz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi0xIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjE3OC4zOTkwMTE2OTg5OTg2IiB5MT0iNTIuNTAwMDM2NzI5Nzk0MzQ2IiB4Mj0iMjA1LjY3ODgwMTMxNTIyMTg1IiB5Mj0iNjguMjUwMDU1MDk0NjkxNSI+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjIwJSI+PC9zdG9wPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi0zIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjE1MS4xMTkyMDA4NzY4MTQ1NSIgeTE9IjY4LjI1MDAxODM2NDg5MDAyIiB4Mj0iMTc4LjM5OTAxMTY5ODk5ODYiIHkyPSI1Mi41MDAwMzY3Mjk3OTQzNDYiPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIyMCUiPjwvc3RvcD48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMTAwJSI+PC9zdG9wPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lLW1tM3gzczVubzdmaGR1Z3NhdGItNSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSIxMjMuODM5NDExMjYwNTkxMjkiIHkxPSI1Mi40OTk5OTk5OTk5OTI4NjYiIHgyPSIxNTEuMTE5MjAwODc2ODE0NTUiIHkyPSI2OC4yNTAwMTgzNjQ4OTAwMiI+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjIwJSI+PC9zdG9wPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi03IiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjEyNi42NzQ0MTEyNjA1OTA2NSIgeTE9IjUyLjUwMDAwMTkwODUyOTMzIiB4Mj0iMTI2LjY3NDQzMjQ2NjU1MTQxIiB5Mj0iMjEuMDAwMDAxOTA4NTM2NDc2Ij48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMjAlIj48L3N0b3A+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjEwMCUiPjwvc3RvcD48L2xpbmVhckdyYWRpZW50PjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZS1tbTN4M3M1bm83ZmhkdWdzYXRiLTkiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iMTIxLjAwNDQxMTI2MDU5MTk0IiB5MT0iNTIuNDk5OTk4MDkxNDU2NDA1IiB4Mj0iMTIxLjAwNDQzMjQ2NjU1MjciIHkyPSIyMC45OTk5OTgwOTE0NjM1MjQiPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIyMCUiPjwvc3RvcD48c3RvcCBzdG9wLWNvbG9yPSJjdXJyZW50Q29sb3IiIG9mZnNldD0iMTAwJSI+PC9zdG9wPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lLW1tM3gzczVubzdmaGR1Z3NhdGItMTEiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIiB4MT0iOTYuNTU5NjAwNDM4NDA3MjciIHkxPSI2OC4yNDk5ODE2MzUwODg1NSIgeDI9IjEyMy44Mzk0MTEyNjA1OTEyOSIgeTI9IjUyLjQ5OTk5OTk5OTk5Mjg2NiI+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjIwJSI+PC9zdG9wPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi0xMyIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSI2OS4yNzk4MTA4MjIxODQwMiIgeTE9IjUyLjQ5OTk2MzI3MDE5MTM5IiB4Mj0iOTYuNTU5NjAwNDM4NDA3MjciIHkyPSI2OC4yNDk5ODE2MzUwODg1NSI+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjIwJSI+PC9zdG9wPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi0xNSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiIHgxPSI0MiIgeTE9IjY4LjI0OTk0NDkwNTI4NzA3IiB4Mj0iNjkuMjc5ODEwODIyMTg0MDIiIHkyPSI1Mi40OTk5NjMyNzAxOTEzOSI+PHN0b3Agc3RvcC1jb2xvcj0iY3VycmVudENvbG9yIiBvZmZzZXQ9IjIwJSI+PC9zdG9wPjxzdG9wIHN0b3AtY29sb3I9ImN1cnJlbnRDb2xvciIgb2Zmc2V0PSIxMDAlIj48L3N0b3A+PC9saW5lYXJHcmFkaWVudD48L2RlZnM+PG1hc2sgaWQ9InRleHQtbWFzay1tbTN4M3M1bm83ZmhkdWdzYXRiIj48cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSJ3aGl0ZSI+PC9yZWN0PjxjaXJjbGUgY3g9IjE3OC4zOTkwMTE2OTg5OTg2IiBjeT0iNTIuNTAwMDM2NzI5Nzk0MzQ2IiByPSI3Ljg3NSIgZmlsbD0iYmxhY2siPjwvY2lyY2xlPjxjaXJjbGUgY3g9IjEyMy44Mzk0MzI0NjY1NTIwNSIgY3k9IjIxIiByPSI3Ljg3NSIgZmlsbD0iYmxhY2siPjwvY2lyY2xlPjxjaXJjbGUgY3g9IjQyIiBjeT0iNjguMjQ5OTQ0OTA1Mjg3MDciIHI9IjcuODc1IiBmaWxsPSJibGFjayI+PC9jaXJjbGU+PC9tYXNrPjxzdHlsZT4KICAgICAgICAgICAgICAgIC5lbGVtZW50LW1tM3gzczVubzdmaGR1Z3NhdGIgewogICAgICAgICAgICAgICAgICAgIGZvbnQ6IDE0cHggSGVsdmV0aWNhLCBBcmlhbCwgc2Fucy1zZXJpZjsKICAgICAgICAgICAgICAgICAgICBhbGlnbm1lbnQtYmFzZWxpbmU6ICdtaWRkbGUnOwogICAgICAgICAgICAgICAgfQogICAgICAgICAgICAgICAgLnN1Yi1tbTN4M3M1bm83ZmhkdWdzYXRiIHsKICAgICAgICAgICAgICAgICAgICBmb250OiA4LjRweCBIZWx2ZXRpY2EsIEFyaWFsLCBzYW5zLXNlcmlmOwogICAgICAgICAgICAgICAgfQogICAgICAgICAgICA8L3N0eWxlPjxnIG1hc2s9InVybCgjdGV4dC1tYXNrLW1tM3gzczVubzdmaGR1Z3NhdGIpIj48bGluZSB4MT0iMTc4LjM5OTAxMTY5ODk5ODYiIHkxPSI1Mi41MDAwMzY3Mjk3OTQzNDYiIHgyPSIyMDUuNjc4ODAxMzE1MjIxODUiIHkyPSI2OC4yNTAwNTUwOTQ2OTE1IiBzdHlsZT0ic3Ryb2tlLWxpbmVjYXA6cm91bmQ7c3Ryb2tlLWRhc2hhcnJheTpub25lO3N0cm9rZS13aWR0aDoxLjI2IiBzdHJva2U9InVybCgnI2xpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi0xJykiPjwvbGluZT48bGluZSB4MT0iMTUxLjExOTIwMDg3NjgxNDU1IiB5MT0iNjguMjUwMDE4MzY0ODkwMDIiIHgyPSIxNzguMzk5MDExNjk4OTk4NiIgeTI9IjUyLjUwMDAzNjcyOTc5NDM0NiIgc3R5bGU9InN0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1kYXNoYXJyYXk6bm9uZTtzdHJva2Utd2lkdGg6MS4yNiIgc3Ryb2tlPSJ1cmwoJyNsaW5lLW1tM3gzczVubzdmaGR1Z3NhdGItMycpIj48L2xpbmU+PGxpbmUgeDE9IjEyMy44Mzk0MTEyNjA1OTEyOSIgeTE9IjUyLjQ5OTk5OTk5OTk5Mjg2NiIgeDI9IjE1MS4xMTkyMDA4NzY4MTQ1NSIgeTI9IjY4LjI1MDAxODM2NDg5MDAyIiBzdHlsZT0ic3Ryb2tlLWxpbmVjYXA6cm91bmQ7c3Ryb2tlLWRhc2hhcnJheTpub25lO3N0cm9rZS13aWR0aDoxLjI2IiBzdHJva2U9InVybCgnI2xpbmUtbW0zeDNzNW5vN2ZoZHVnc2F0Yi01JykiPjwvbGluZT48bGluZSB4MT0iMTI2LjY3NDQxMTI2MDU5MDY1IiB5MT0iNTIuNTAwMDAxOTA4NTI5MzMiIHgyPSIxMjYuNjc0NDMyNDY2NTUxNDEiIHkyPSIyMS4wMDAwMDE5MDg1MzY0NzYiIHN0eWxlPSJzdHJva2UtbGluZWNhcDpyb3VuZDtzdHJva2UtZGFzaGFycmF5Om5vbmU7c3Ryb2tlLXdpZHRoOjEuMjYiIHN0cm9rZT0idXJsKCcjbGluZS1tbTN4M3M1bm83ZmhkdWdzYXRiLTcnKSI+PC9saW5lPjxsaW5lIHgxPSIxMjEuMDA0NDExMjYwNTkxOTQiIHkxPSI1Mi40OTk5OTgwOTE0NTY0MDUiIHgyPSIxMjEuMDA0NDMyNDY2NTUyNyIgeTI9IjIwLjk5OTk5ODA5MTQ2MzUyNCIgc3R5bGU9InN0cm9rZS1saW5lY2FwOnJvdW5kO3N0cm9rZS1kYXNoYXJyYXk6bm9uZTtzdHJva2Utd2lkdGg6MS4yNiIgc3Ryb2tlPSJ1cmwoJyNsaW5lLW1tM3gzczVubzdmaGR1Z3NhdGItOScpIj48L2xpbmU+PGxpbmUgeDE9Ijk2LjU1OTYwMDQzODQwNzI3IiB5MT0iNjguMjQ5OTgxNjM1MDg4NTUiIHgyPSIxMjMuODM5NDExMjYwNTkxMjkiIHkyPSI1Mi40OTk5OTk5OTk5OTI4NjYiIHN0eWxlPSJzdHJva2UtbGluZWNhcDpyb3VuZDtzdHJva2UtZGFzaGFycmF5Om5vbmU7c3Ryb2tlLXdpZHRoOjEuMjYiIHN0cm9rZT0idXJsKCcjbGluZS1tbTN4M3M1bm83ZmhkdWdzYXRiLTExJykiPjwvbGluZT48bGluZSB4MT0iNjkuMjc5ODEwODIyMTg0MDIiIHkxPSI1Mi40OTk5NjMyNzAxOTEzOSIgeDI9Ijk2LjU1OTYwMDQzODQwNzI3IiB5Mj0iNjguMjQ5OTgxNjM1MDg4NTUiIHN0eWxlPSJzdHJva2UtbGluZWNhcDpyb3VuZDtzdHJva2UtZGFzaGFycmF5Om5vbmU7c3Ryb2tlLXdpZHRoOjEuMjYiIHN0cm9rZT0idXJsKCcjbGluZS1tbTN4M3M1bm83ZmhkdWdzYXRiLTEzJykiPjwvbGluZT48bGluZSB4MT0iNDIiIHkxPSI2OC4yNDk5NDQ5MDUyODcwNyIgeDI9IjY5LjI3OTgxMDgyMjE4NDAyIiB5Mj0iNTIuNDk5OTYzMjcwMTkxMzkiIHN0eWxlPSJzdHJva2UtbGluZWNhcDpyb3VuZDtzdHJva2UtZGFzaGFycmF5Om5vbmU7c3Ryb2tlLXdpZHRoOjEuMjYiIHN0cm9rZT0idXJsKCcjbGluZS1tbTN4M3M1bm83ZmhkdWdzYXRiLTE1JykiPjwvbGluZT48L2c+PGc+PHRleHQgeD0iMjA1LjY3ODgwMTMxNTIyMTg1IiB5PSI2OC4yNTAwNTUwOTQ2OTE1IiBjbGFzcz0iZGVidWciIGZpbGw9IiNmZjAwMDAiIHN0eWxlPSIKICAgICAgICAgICAgICAgIGZvbnQ6IDVweCBEcm9pZCBTYW5zLCBzYW5zLXNlcmlmOwogICAgICAgICAgICAiPjwvdGV4dD48dGV4dCB4PSIxNzguMzk5MDExNjk4OTk4NiIgeT0iNjAuMzc1MDM2NzI5Nzk0MzQ2IiBjbGFzcz0iZWxlbWVudC1tbTN4M3M1bm83ZmhkdWdzYXRiIiBmaWxsPSJjdXJyZW50Q29sb3IiIHN0eWxlPSJ0ZXh0LWFuY2hvcjogc3RhcnQ7IGdseXBoLW9yaWVudGF0aW9uLXZlcnRpY2FsOiAwOyB3cml0aW5nLW1vZGU6IHZlcnRpY2FsLXJsOyB0ZXh0LW9yaWVudGF0aW9uOiB1cHJpZ2h0OyBsZXR0ZXItc3BhY2luZzogLTFweDsgZGlyZWN0aW9uOiBydGw7IHVuaWNvZGUtYmlkaTogYmlkaS1vdmVycmlkZTsiPjx0c3Bhbj5PPC90c3Bhbj48L3RleHQ+PHRleHQgeD0iMTc4LjM5OTAxMTY5ODk5ODYiIHk9IjUyLjUwMDAzNjcyOTc5NDM0NiIgY2xhc3M9ImRlYnVnIiBmaWxsPSIjZmYwMDAwIiBzdHlsZT0iCiAgICAgICAgICAgICAgICBmb250OiA1cHggRHJvaWQgU2Fucywgc2Fucy1zZXJpZjsKICAgICAgICAgICAgIj48L3RleHQ+PHRleHQgeD0iMTUxLjExOTIwMDg3NjgxNDU1IiB5PSI2OC4yNTAwMTgzNjQ4OTAwMiIgY2xhc3M9ImRlYnVnIiBmaWxsPSIjZmYwMDAwIiBzdHlsZT0iCiAgICAgICAgICAgICAgICBmb250OiA1cHggRHJvaWQgU2Fucywgc2Fucy1zZXJpZjsKICAgICAgICAgICAgIj48L3RleHQ+PHRleHQgeD0iMTIzLjgzOTQxMTI2MDU5MTI5IiB5PSI1Mi40OTk5OTk5OTk5OTI4NjYiIGNsYXNzPSJkZWJ1ZyIgZmlsbD0iI2ZmMDAwMCIgc3R5bGU9IgogICAgICAgICAgICAgICAgZm9udDogNXB4IERyb2lkIFNhbnMsIHNhbnMtc2VyaWY7CiAgICAgICAgICAgICI+PC90ZXh0Pjx0ZXh0IHg9IjExOC41ODk0MzI0NjY1NTIwNSIgeT0iMjYuMjUiIGNsYXNzPSJlbGVtZW50LW1tM3gzczVubzdmaGR1Z3NhdGIiIGZpbGw9ImN1cnJlbnRDb2xvciIgc3R5bGU9InRleHQtYW5jaG9yOiBzdGFydDsgd3JpdGluZy1tb2RlOiBob3Jpem9udGFsLXRiOyB0ZXh0LW9yaWVudGF0aW9uOiBtaXhlZDsgbGV0dGVyLXNwYWNpbmc6IG5vcm1hbDsgZGlyZWN0aW9uOiBsdHI7Ij48dHNwYW4+TzwvdHNwYW4+PC90ZXh0Pjx0ZXh0IHg9IjEyMy44Mzk0MzI0NjY1NTIwNSIgeT0iMjEiIGNsYXNzPSJkZWJ1ZyIgZmlsbD0iI2ZmMDAwMCIgc3R5bGU9IgogICAgICAgICAgICAgICAgZm9udDogNXB4IERyb2lkIFNhbnMsIHNhbnMtc2VyaWY7CiAgICAgICAgICAgICI+PC90ZXh0Pjx0ZXh0IHg9Ijk2LjU1OTYwMDQzODQwNzI3IiB5PSI2OC4yNDk5ODE2MzUwODg1NSIgY2xhc3M9ImRlYnVnIiBmaWxsPSIjZmYwMDAwIiBzdHlsZT0iCiAgICAgICAgICAgICAgICBmb250OiA1cHggRHJvaWQgU2Fucywgc2Fucy1zZXJpZjsKICAgICAgICAgICAgIj48L3RleHQ+PHRleHQgeD0iNjkuMjc5ODEwODIyMTg0MDIiIHk9IjUyLjQ5OTk2MzI3MDE5MTM5IiBjbGFzcz0iZGVidWciIGZpbGw9IiNmZjAwMDAiIHN0eWxlPSIKICAgICAgICAgICAgICAgIGZvbnQ6IDVweCBEcm9pZCBTYW5zLCBzYW5zLXNlcmlmOwogICAgICAgICAgICAiPjwvdGV4dD48dGV4dCB4PSI0Ny4yNSIgeT0iNzMuNDk5OTQ0OTA1Mjg3MDciIGNsYXNzPSJlbGVtZW50LW1tM3gzczVubzdmaGR1Z3NhdGIiIGZpbGw9ImN1cnJlbnRDb2xvciIgc3R5bGU9InRleHQtYW5jaG9yOiBzdGFydDsgd3JpdGluZy1tb2RlOiBob3Jpem9udGFsLXRiOyB0ZXh0LW9yaWVudGF0aW9uOiBtaXhlZDsgbGV0dGVyLXNwYWNpbmc6IG5vcm1hbDsgZGlyZWN0aW9uOiBydGw7IHVuaWNvZGUtYmlkaTogYmlkaS1vdmVycmlkZTsiPjx0c3Bhbj5PPC90c3Bhbj48dHNwYW4gc3R5bGU9InVuaWNvZGUtYmlkaTogcGxhaW50ZXh0OyI+SDwvdHNwYW4+PC90ZXh0Pjx0ZXh0IHg9IjQyIiB5PSI2OC4yNDk5NDQ5MDUyODcwNyIgY2xhc3M9ImRlYnVnIiBmaWxsPSIjZmYwMDAwIiBzdHlsZT0iCiAgICAgICAgICAgICAgICBmb250OiA1cHggRHJvaWQgU2Fucywgc2Fucy1zZXJpZjsKICAgICAgICAgICAgIj48L3RleHQ+PC9nPjwvc3ZnPg=="/>
(l) $\mathrm{K}_{3} \mathrm{~V}_{5} \mathrm{O}_{14}+\mathrm{HOCH}_{2} \mathrm{CHOHCH}_{2} \mathrm{OH} \rightleftharpoons \mathrm{VO}(\mathrm{OH})_{2}+\mathrm{HCO}_{2}^{-}+\mathrm{K}^{+}$

## Answers

D-1. (a) +1
(j) +3
(s) +3
(b) +2
(k) +1
(t) 0
(c) +6
(l) +2
(u) -4
(d) +2
(m) +4
(v) +5
(e) $-\frac{1}{2}$
(n) +3
(w) -2
(f) $\quad+2$
(o) +2
(x) +4
(g) +3
(p) 0
(y) $+8 / 3$
(h) +4
(q) -3
(z) $-2 / 3$
(i) $\quad+2$
(r) -2

D-2.

|  | Oxidizing agent | Reducing agent |
| :--- | :--- | :--- |
| (a) | $\mathrm{Cr}_{2} \mathrm{O}_{7}^{2-}$ | $\mathrm{Sn}^{2+}$ |
| (b) | $\mathrm{O}_{2}$ | $\mathrm{I}^{-}$ |
| (c) | $\mathrm{MnO}_{4}^{-}$ | $\mathrm{CH}_{3} \mathrm{CHO}$ |
| (d) | $\mathrm{IO}_{4}^{-}$ | Glycerol |
| (e) | $\mathrm{C}_{8} \mathrm{H}_{8}$ | Na |
| (f) | $\mathrm{I}_{2}$ | $\mathrm{I}_{2}$ |

Reaction (f) is called a disproportionation, because an element in one oxidation state is transformed into two different oxidation states-one higher and one lower than the original oxidation state.

D-3. (a) $2 \mathrm{Fe}^{3+}+\mathrm{Hg}_{2}^{2+} \rightleftharpoons 2 \mathrm{Fe}^{2+}+2 \mathrm{Hg}^{2+}$
(b) $3 \mathrm{Ag}+\mathrm{NO}_{3}^{-}+4 \mathrm{H}^{+} \rightleftharpoons 3 \mathrm{Ag}^{+}+\mathrm{NO}+2 \mathrm{H}_{2} \mathrm{O}$
(c) $4 \mathrm{H}^{+}+2 \mathrm{VO}^{2+}+\mathrm{Sn}^{2+} \rightleftharpoons 2 \mathrm{~V}^{3+}+\mathrm{Sn}^{4+}+2 \mathrm{H}_{2} \mathrm{O}$
(d) $2 \mathrm{Hg}+2 \mathrm{Cl}^{-}+\mathrm{SeO}_{4}^{2-}+2 \mathrm{H}^{+} \rightleftharpoons \mathrm{Hg}_{2} \mathrm{Cl}_{2}+\mathrm{SeO}_{3}^{2-}+\mathrm{H}_{2} \mathrm{O}$
(e) $3 \mathrm{CuS}+8 \mathrm{NO}_{3}^{-}+8 \mathrm{H}^{+} \rightleftharpoons 3 \mathrm{Cu}^{2+}+3 \mathrm{SO}_{4}^{2-}+8 \mathrm{NO}+4 \mathrm{H}_{2} \mathrm{O}$
(f) $2 \mathrm{~S}_{2} \mathrm{O}_{3}^{2-}+\mathrm{I}_{2} \rightleftharpoons \mathrm{~S}_{4} \mathrm{O}_{6}^{2-}+2 \mathrm{I}^{-}$
(g) $14 \mathrm{ClO}_{3}^{-}+3 \mathrm{As}_{2} \mathrm{~S}_{3}+18 \mathrm{H}_{2} \mathrm{O} \rightleftharpoons$

$$
14 \mathrm{Cl}^{-}+6 \mathrm{H}_{2} \mathrm{AsO}_{4}^{-}+9 \mathrm{SO}_{4}^{2-}+24 \mathrm{H}^{+}
$$

(h) $\mathrm{Cr}_{2} \mathrm{O}_{7}^{2-}+3 \mathrm{CH}_{3} \mathrm{CHO}+8 \mathrm{H}^{+} \rightleftharpoons 2 \mathrm{Cr}^{3+}+3 \mathrm{CH}_{3} \mathrm{CO}_{2} \mathrm{H}+4 \mathrm{H}_{2} \mathrm{O}$
(i) $4 \mathrm{H}^{+}+3 \mathrm{MnO}_{4}^{2-} \rightleftharpoons \mathrm{MnO}_{2}+2 \mathrm{MnO}_{4}^{-}+2 \mathrm{H}_{2} \mathrm{O}$
(j) $2 \mathrm{Hg}_{2} \mathrm{SO}_{4}+3 \mathrm{Ca}^{2+}+\frac{1}{2} \mathrm{~S}_{8}+\mathrm{H}_{2} \mathrm{O} \rightleftharpoons 2 \mathrm{Hg}_{2}^{2+}+3 \mathrm{CaS}_{2} \mathrm{O}_{3}+2 \mathrm{H}^{+}$
(k) $2 \mathrm{H}^{+}+2 \mathrm{ClO}_{3}^{-} \rightleftharpoons \mathrm{Cl}_{2}+\frac{5}{2} \mathrm{O}_{2}+\mathrm{H}_{2} \mathrm{O}$

The balanced half-reaction for $\mathrm{As}_{2} \mathrm{~S}_{3}$ in (g) is

$$
\underset{+3-2}{\mathrm{As}_{2} \mathrm{~S}_{3}}+\underset{+5}{20 \mathrm{H}_{2} \mathrm{O}} \underset{+6}{2 \mathrm{H}_{2} \mathrm{AsO}_{4}^{-}}+\underset{+5}{3 \mathrm{SO}_{4}^{2-}}+28 \mathrm{e}^{-}+36 \mathrm{H}^{+}
$$

Because $\mathrm{As}_{2} \mathrm{~S}_{3}$ is a single compound, we must consider the $\mathrm{As}_{2} \mathrm{~S}_{3} \rightarrow \mathrm{H}_{2} \mathrm{AsO}_{4}^{-}$and $\mathrm{As}_{2} \mathrm{~S}_{3} \rightarrow \mathrm{SO}_{4}^{2-}$ reactions together. The net change in oxidation number for the two As atoms is $2(5-3)=+4$. The net change in oxidation number for the three S atoms is $3[6-(-2)]=+24$. Therefore, $24+4= 28 \mathrm{e}^{-}$are involved in the half-reaction.

D-4. (a) $\mathrm{H}_{2} \mathrm{O}+\mathrm{OH}^{-}+\mathrm{PbO}_{2}+\mathrm{Cl}^{-} \rightleftharpoons \mathrm{Pb}(\mathrm{OH})_{3}^{-}+\mathrm{ClO}^{-}$
(b) $4 \mathrm{HNO}_{2}+2 \mathrm{SbO}^{-}+2 \mathrm{OH}^{-} \rightleftharpoons 4 \mathrm{NO}+\mathrm{Sb}_{2} \mathrm{O}_{5}+3 \mathrm{H}_{2} \mathrm{O}$
(c) $\mathrm{Ag}_{2} \mathrm{~S}+4 \mathrm{CN}^{-}+\frac{1}{2} \mathrm{O}_{2}+\mathrm{H}_{2} \mathrm{O} \rightleftharpoons \mathrm{S}+2 \mathrm{Ag}(\mathrm{CN})_{2}^{-}+2 \mathrm{OH}^{-}$
(d) $2 \mathrm{HO}_{2}^{-}+\mathrm{Cr}(\mathrm{OH})_{3}^{-} \rightleftharpoons \mathrm{CrO}_{4}^{2-}+\mathrm{OH}^{-}+2 \mathrm{H}_{2} \mathrm{O}$
(e) $2 \mathrm{ClO}_{2}+2 \mathrm{OH}^{-} \rightleftharpoons \mathrm{ClO}_{2}^{-}+\mathrm{ClO}_{3}^{-}+\mathrm{H}_{2} \mathrm{O}$
(f) $12 \mathrm{WO}_{3}^{-}+3 \mathrm{O}_{2}+2 \mathrm{H}_{2} \mathrm{O} \rightleftharpoons 2 \mathrm{HW}_{6} \mathrm{O}_{21}^{5-}+2 \mathrm{OH}^{-}$
(g) $\mathrm{Mn}_{2} \mathrm{O}_{3}+14 \mathrm{CN}^{-}+3 \mathrm{H}_{2} \mathrm{O} \rightleftharpoons 2 \mathrm{Mn}(\mathrm{CN})_{6}^{4-}+(\mathrm{CN})_{2}+6 \mathrm{OH}^{-}$
(h) $\mathrm{Cu}^{2+}+\mathrm{H}_{2}+2 \mathrm{OH}^{-} \rightleftharpoons \mathrm{Cu}+2 \mathrm{H}_{2} \mathrm{O}$
(i) $\mathrm{BH}_{4}^{-}+4 \mathrm{H}_{2} \mathrm{O} \rightleftharpoons \mathrm{H}_{3} \mathrm{BO}_{3}+4 \mathrm{H}_{2}+\mathrm{OH}^{-}$
(j) $3 \mathrm{H}_{2} \mathrm{O}+\mathrm{Mn}_{2} \mathrm{O}_{3}+\mathrm{Hg}+14 \mathrm{CN}^{-} \rightleftharpoons$

$$
2 \mathrm{Mn}(\mathrm{CN})_{6}^{4-}+\mathrm{Hg}(\mathrm{CN})_{2}+6 \mathrm{OH}^{-}
$$

(k) $2 \mathrm{MnO}_{4}^{-}+\mathrm{HCCH}_{2} \mathrm{CH}_{2} \mathrm{OH} \rightleftharpoons 2 \mathrm{MnO}_{2}+2 \mathrm{H}_{2} \mathrm{O}+\mathrm{CH}_{2}\left(\mathrm{CO}_{2}^{-}\right)_{2}$

For (k), the organic half-reaction is $8 \mathrm{OH}^{-}+\mathrm{C}_{3} \mathrm{H}_{6} \mathrm{O}_{2} \rightleftharpoons$

$$
\mathrm{C}_{3} \mathrm{H}_{2} \mathrm{O}_{4}^{2-}+6 \mathrm{e}^{-}+6 \mathrm{H}_{2} \mathrm{O} .
$$

(l) $32 \mathrm{H}_{2} \mathrm{O}+8 \mathrm{~K}_{3} \mathrm{~V}_{5} \mathrm{O}_{14}+5 \mathrm{HOCH}_{2} \mathrm{CHOHCH}_{2} \mathrm{OH} \rightleftharpoons 40 \mathrm{VO}(\mathrm{OH})_{2}+15 \mathrm{HCO}_{2}^{-}+9 \mathrm{OH}^{-}+24 \mathrm{~K}^{+}$
For (I), the two half-reactions are $\mathrm{K}_{3} \mathrm{~V}_{5} \mathrm{O}_{14}+9 \mathrm{H}_{2} \mathrm{O}+5 \mathrm{e}^{-} \rightleftharpoons 5 \mathrm{VO}(\mathrm{OH})_{2}+8 \mathrm{OH}^{-}+3 \mathrm{~K}^{+} \quad$ and $\quad \mathrm{C}_{3} \mathrm{H}_{8} \mathrm{O}_{3}+11 \mathrm{OH}^{-} \rightleftharpoons 3 \mathrm{HCO}_{2}^{-}+ 8 \mathrm{e}^{-}+8 \mathrm{H}_{2} \mathrm{O}$.

The normality, N , of a redox reagent is $n$ times the molarity, where $n$ is the number of electrons donated or accepted by that species in a chemical reaction.

$$
\mathrm{N}=n \mathrm{M}
$$

For example, in the half-reaction

$$
\mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O}
$$

the normality of permanganate ion is five times its molarity, because each $\mathrm{MnO}_{4}^{-}$accepts $5 \mathrm{e}^{-}$. If the molarity of permanganate is 0.1 M , the normality for the reaction

$$
\mathrm{MnO}_{4}^{-}+5 \mathrm{Fe}^{2+}+8 \mathrm{H}^{+} \rightleftharpoons \mathrm{Mn}^{2+}+5 \mathrm{Fe}^{3+}+4 \mathrm{H}_{2} \mathrm{O}
$$

is $5 \times 0.1=0.5 \mathrm{~N}$ (read " 0.5 normal"). In this reaction, each $\mathrm{Fe}^{2+}$ ion donates one electron. The normality of ferrous ion equals the molarity of ferrous ion, even though it takes five ferrous ions to balance the reaction.

In the half-reaction

$$
\mathrm{MnO}_{4}^{-}+4 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{MnO}_{2}+2 \mathrm{H}_{2} \mathrm{O}
$$

each $\mathrm{MnO}_{4}^{-}$in accepts only three electrons. The normality of permanganate for this reaction is equal to three times the molarity of permanganate. A 0.06 N permanganate solution for this reaction contains $0.02 \mathrm{M} \mathrm{MnO}_{4}^{-}$.

The normality of a solution is a statement of the moles of "reacting units" per liter. One mole of reacting units is called one equivalent. Therefore, the units of normality are equivalents per liter (equiv/L). For redox reagents, one equivalent is the amount of substance that can donate or accept one mole of electrons. It is possible to speak of equivalents only with respect to a particular half-reaction. For example, in Reaction E-2, there are five equivalents per mole of $\mathrm{MnO}_{4}^{-}$; but, in Reaction E-4, there are only three equivalents per mole of $\mathrm{MnO}_{4}^{-}$. The mass of substance containing one equivalent is called the equivalent mass. The formula mass of $\mathrm{KMnO}_{4}$ is 158.033 9. The equivalent mass of $\mathrm{KMnO}_{4}$ for Reaction E-2 is $158.0339 / 5=31.6068 \mathrm{~g} /$ equiv . The equivalent mass of $\mathrm{KMnO}_{4}$ for Reaction E-4 is $158.033 \frac{9}{3}=52.6780$ g/equiv.

## EXAMPLE Finding Normality

Find the normality of a solution containing 6.34 g of ascorbic acid in 250.0 mL if the relevant half-reaction is
![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-08.jpg?height=217&width=809&top_left_y=1661&top_left_x=168)

Ascorbic acid (vitamin C) Dehydroascorbic acid
Solution The formula mass of ascorbic acid $\left(\mathrm{C}_{6} \mathrm{H}_{8} \mathrm{O}_{6}\right)$ is 176.124. In 6.34 g , there are $(6.34 \mathrm{~g}) /(176.124 \mathrm{~g} / \mathrm{mol})=3.60 \times 10^{-2} \mathrm{~mol}$. Because each mole contains 2 equivalents in this example, $6.34 \mathrm{~g}=(2$ equiv $/ \mathrm{mot}) \left(3.60 \times 10^{-2} \mathrm{mot}\right)=7.20 \times 10^{-2}$ equivalent. The normality is $\left(7.20 \times 10^{-2}\right.$ equiv $) /(0.2500 \mathrm{~L})=0.288 \mathrm{~N}$.

## EXAMPLE Using Normality

How many grams of potassium oxalate should be dissolved in 500.0 mL to make a 0.100 N solution for titration of $\mathrm{MnO}_{4}^{-}$?

$$
5 \mathrm{H}_{2} \mathrm{C}_{2} \mathrm{O}_{4}+2 \mathrm{MnO}_{4}^{-}+6 \mathrm{H}^{+} \rightleftharpoons 2 \mathrm{Mn}^{2+}+10 \mathrm{CO}_{2}+8 \mathrm{H}_{2} \mathrm{O}
$$

Solution It is first necessary to write the oxalic acid half-reaction:

$$
\mathrm{H}_{2} \mathrm{C}_{2} \mathrm{O}_{4} \rightleftharpoons 2 \mathrm{CO}_{2}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-}
$$

It is apparent that there are two equivalents per mole of oxalic acid. Hence, a 0.100 N solution will be 0.0500 M :

$$
\frac{0.100 \text { equiv } / \mathrm{L}}{2 \text { equiv } / \mathrm{mol}}=0.0500 \mathrm{~mol} / \mathrm{L}=0.0500 \mathrm{M}
$$

Therefore, we must dissolve $(0.0500 \mathrm{~mol} / \mathrm{K})(0.5000 \mathrm{~L})=0.0250 \mathrm{~mol}$ in 500.0 mL . Because the formula mass of $\mathrm{K}_{2} \mathrm{C}_{2} \mathrm{O}_{4}$ is 166.216, we should use $(0.0250 \mathrm{~mol}) \times(166.216 \mathrm{~g} / \mathrm{mol})=4.15 \mathrm{~g}$ of potassium oxalate.

The utility of normality in volumetric analysis lies in the equation

$$
\mathrm{N}_{1} V_{1}=\mathrm{N}_{2} V_{2}
$$

where $\mathrm{N}_{1}$ is the normality of reagent $1, V_{1}$ is the volume of reagent $1, \mathrm{~N}_{2}$ is the normality of reagent 2 , and $V_{2}$ is the volume of reagent 2 . $V_{1}$ and $V_{2}$ may be expressed in any units, as long as the same units are used for both.

## EXAMPLE Finding Normality

A solution containing 25.0 mL of oxalic acid required 13.78 mL of $0.04162 \mathrm{~N} \mathrm{KMnO}_{4}$ for titration, according to Reaction E-5. Find the normality and molarity of the oxalic acid.

Solution Setting up Equation E-6, we write

$$
\begin{aligned}
\mathrm{N}_{1}(25.0 \mathrm{~mL}) & =(0.04162 \mathrm{~N})(13.78 \mathrm{~mL}) \\
\mathrm{N}_{1} & =0.02294 \text { equiv } / \mathrm{L}
\end{aligned}
$$

Because there are two equivalents per mole of oxalic acid in Reaction E-5,

$$
\mathrm{M}=\frac{\mathrm{N}}{n}=\frac{0.02294}{2}=0.01147 \mathrm{M}
$$

Normality is sometimes used in acid-base or ion-exchange chemistry. With respect to acids and bases, the equivalent mass of a reagent is the amount that can donate or accept 1 mole of $\mathrm{H}^{+}$. With respect to ion exchange, the equivalent mass is the mass of reagent containing 1 mole of charge.

| Formula | $\mathbf{p} \boldsymbol{K}_{\mathbf{s p}}$ | $\boldsymbol{K}_{\mathbf{s p}}$ | Formula | $\mathbf{p} \boldsymbol{K}_{\mathbf{s p}}$ | $\boldsymbol{K}_{\mathbf{s p}}$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Azides: $\mathrm{L}=\mathrm{N}_{3}^{-}$ |  |  | Chromates: $\mathrm{L}=\mathrm{CrO}_{4}^{2-}$ |  |  |
| CuL | 8.31 | $4.9 \times 10^{-9}$ | BaL | 9.67 | $2.1 \times 10^{-10}$ |
| AgL | 8.56 | $2.8 \times 10^{-9}$ | CuL | 5.44 | $3.6 \times 10^{-6}$ |
| $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 9.15 | $7.1 \times 10^{-10}$ | $\mathrm{Ag}_{2} \mathrm{~L}$ | 11.92 | $1.2 \times 10^{-12}$ |
| TIL | 3.66 | $2.2 \times 10^{-4}$ | $\mathrm{Hg}_{2} \mathrm{~L}$ | 8.70 | $2.0 \times 10^{-9}$ |
| $\mathrm{PdL}_{2}(\alpha)$ | 8.57 | $2.7 \times 10^{-9}$ | $\mathrm{Tl}_{2} \mathrm{~L}$ | 12.01 | $9.8 \times 10^{-13}$ |
| Bromates: $\mathrm{L}=\mathrm{BrO}_{3}^{-}$ |  |  | Cobalticyanides: $\mathrm{L}=\mathrm{Co}(\mathrm{CN})_{6}^{3-}$ |  |  |
| $\mathrm{BaL} \cdot \mathrm{H}_{2} \mathrm{O}$ (f) | 5.11 | $7.8 \times 10^{-6}$ | $\mathrm{Ag}_{3} \mathrm{~L}$ | 25.41 | $3.9 \times 10^{-26}$ |
| AgL | 4.26 | $5.5 \times 10^{-5}$ | $\left(\mathrm{Hg}_{2}\right)_{3} \mathrm{~L}_{2}$ | 36.72 | $1.9 \times 10^{-37}$ |
| TIL | 3.78 | $1.7 \times 10^{-4}$ |  |  |  |
| $\mathrm{PbL}_{2}$ | 5.10 | $7.9 \times 10^{-6}$ | Cyanides: $\mathrm{L}=\mathrm{CN}^{-}$ |  |  |
|  |  |  | AgL | 15.66 | $2.2 \times 10^{-16}$ |
| Bromides: $\mathrm{L}=\mathrm{Br}^{-}$ |  |  | $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 39.3 | $5 \times 10^{-40}$ |
| CuL | 8.3 | $5 \times 10^{-9}$ | $\mathrm{ZnL}_{2}$ (h) | 15.5 | $3 \times 10^{-16}$ |
| AgL | 12.30 | $5.0 \times 10^{-13}$ | Ferrocyanides: $\mathrm{L}=\mathrm{Fe}(\mathrm{CN})_{6}^{4-}$ |  |  |
| $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 22.25 | $5.6 \times 10^{-23}$ |  |  |  |
| TIL | 5.44 | $3.6 \times 10^{-6}$ | $\mathrm{Ag}_{4} \mathrm{~L}$ | 44.07 | $8.5 \times 10^{-45}$ |
| $\mathrm{HgL}_{2}$ (f) | 18.9 | $1.3 \times 10^{-19}$ | $\mathrm{Zn}_{2} \mathrm{~L}$ | 15.68 | $2.1 \times 10^{-16}$ |
| $\mathrm{PbL}_{2}$ | 5.68 | $2.1 \times 10^{-6}$ | $\mathrm{Cd}_{2} \mathrm{~L}$ | 17.38 | $4.2 \times 10^{-18}$ |
| Carbonates: $\mathrm{L}=\mathrm{CO}_{3}^{2-}$ |  |  | $\mathrm{Pb}_{2} \mathrm{~L}$ | 18.02 | $9.5 \times 10^{-19}$ |
| MgL | 7.46 | $3.5 \times 10^{-8}$ | Fluorides: $\mathrm{L}=\mathrm{F}^{-}$ |  |  |
| CaL (calcite) | 8.35 | $4.5 \times 10^{-9}$ | LiL | 2.77 | $1.7 \times 10^{-3}$ |
| CaL (aragonite) | 8.22 | $6.0 \times 10^{-9}$ | $\mathrm{MgL}_{2}$ | 8.13 | $7.4 \times 10^{-9}$ |
| SrL | 9.03 | $9.3 \times 10^{-10}$ | $\mathrm{CaL}_{2}$ | 10.50 | $3.2 \times 10^{-11}$ |
| BaL | 8.30 | $5.0 \times 10^{-9}$ | $\mathrm{SrL}_{2}$ | 8.58 | $2.6 \times 10^{-9}$ |
| $\mathrm{Y}_{2} \mathrm{~L}_{3}$ | 30.6 | $2.5 \times 10^{-31}$ | $\mathrm{BaL}_{2}$ | 5.82 | $1.5 \times 10^{-6}$ |
| $\mathrm{La}_{2} \mathrm{~L}_{3}$ | 33.4 | $4.0 \times 10^{-34}$ | $\mathrm{LaL}_{3}$ | 18.7 | $2 \times 10^{-19}$ |
| MnL | 9.30 | $5.0 \times 10^{-10}$ | $\mathrm{ThL}_{4}$ | 28.3 | $5 \times 10^{-29}$ |
| FeL | 10.68 | $2.1 \times 10^{-11}$ | $\mathrm{PbL}_{2}$ | 7.44 | $3.6 \times 10^{-8}$ |
| CoL | 9.98 | $1.0 \times 10^{-10}$ | Hydroxides: $\mathrm{L}=\mathrm{OH}^{-}$ |  |  |
| NiL | 6.87 | $1.3 \times 10^{-7}$ |  |  |  |
| CuL | 9.63 | $2.3 \times 10^{-10}$ | $\mathrm{MgL}_{2}$ (amorphous) | 9.2 | $6 \times 10^{-10}$ |
| $\mathrm{Ag}_{2} \mathrm{~L}$ | 11.09 | $8.1 \times 10^{-12}$ | $\mathrm{MgL}_{2}$ (brucite crystal) | 11.15 | $7.1 \times 10^{-12}$ |
| $\mathrm{Hg}_{2} \mathrm{~L}$ | 16.05 | $8.9 \times 10^{-17}$ | $\mathrm{CaL}_{2}$ | 5.19 | $6.5 \times 10^{-6}$ |
| ZnL | 10.00 | $1.0 \times 10^{-10}$ | $\mathrm{BaL}_{2} \cdot 8 \mathrm{H}_{2} \mathrm{O}$ | 3.6 | $3 \times 10^{-4}$ |
| CdL | 13.74 | $1.8 \times 10^{-14}$ | $\mathrm{YL}_{3}$ | 23.2 | $6 \times 10^{-24}$ |
| PbL | 13.13 | $7.4 \times 10^{-14}$ | $\mathrm{LaL}_{3}$ | 20.7 | $2 \times 10^{-21}$ |
|  |  |  | $\mathrm{CeL}_{3}$ | 21.2 | $6 \times 10^{-22}$ |
| Chlorides: $\mathrm{L}=\mathrm{Cl}^{-}$ |  |  | $\mathrm{UO}_{2}\left(\rightleftharpoons \mathrm{U}^{4+}+4 \mathrm{OH}^{-}\right)$ | 56.2 | $6 \times 10^{-57}$ |
| CuL | 6.73 | $1.9 \times 10^{-7}$ | $\mathrm{UO}_{2} \mathrm{~L}_{2}\left(\rightleftharpoons \mathrm{UO}_{2}^{2+}+2 \mathrm{OH}^{-}\right)$ | 22.4 | $4 \times 10^{-23}$ |
| AgL | 9.74 | $1.8 \times 10^{-10}$ | $\mathrm{MnL}_{2}$ | 12.8 | $1.6 \times 10^{-13}$ |
| $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 17.91 | $1.2 \times 10^{-18}$ | $\mathrm{FeL}_{2}$ | 15.1 | $7.9 \times 10^{-16}$ |
| TIL | 3.74 | $1.8 \times 10^{-4}$ | $\mathrm{CoL}_{2}$ | 14.9 | $1.3 \times 10^{-15}$ |
| $\mathrm{PbL}_{2}$ | 4.78 | $1.7 \times 10^{-5}$ | $\mathrm{NiL}_{2}$ | 15.2 | $6 \times 10^{-16}$ |

*The designations $\alpha, \beta$, or $\gamma$ after some formulas refer to particular crystalline forms (which are customarily identified by Greek letters). Data for salts except oxalates are taken mainly from A. E. Martell and R. M. Smith, Critical Stability Constants, Vol. 4 (New York: Plenum Press, 1976). Data for oxalates are from L. G. Sillén and A. E. Martell, Stability Constants of Metal-Ion Complexes, Supplement No. 1 (London: The Chemical Society, Special Publication No. 25, 1971). Another source: R. M. H. Verbeeck et al., Inorg. Chem. 1984, 23, 1922.

Conditions are $25^{\circ} \mathrm{C}$ and zero ionic strength unless otherwise indicated: (a) $19^{\circ} \mathrm{C}$; (b) $20^{\circ} \mathrm{C}$; (c) $38^{\circ} \mathrm{C}$; (d) 0.1 M ; (e) 0.2 M ; (f) 0.5 M ; (g) $1 M$; (h) $3 M$; (i) $4 M$; (j) $5 M$.
(Continued)

| Formula | $\mathbf{p} \boldsymbol{K}_{\mathbf{s p}}$ | $\boldsymbol{K}_{\mathbf{s p}}$ | Formula | $\mathbf{p} \boldsymbol{K}_{\mathbf{s p}}$ | $\boldsymbol{K}_{\mathbf{s p}}$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| $\mathrm{CuL}_{2}$ | 19.32 | $4.8 \times 10^{-20}$ | Phosphates: $\mathrm{L}=\mathrm{PO}_{4}^{3-}$ |  |  |
| $\mathrm{VL}_{3}$ | 34.4 | $4.0 \times 10^{-35}$ | $\mathrm{MgHL} \cdot 3 \mathrm{H}_{2} \mathrm{O}\left(\rightleftharpoons \mathrm{Mg}^{2+}+\mathrm{HL}^{2-}\right)$ | 5.78 | $1.7 \times 10^{-6}$ |
| $\mathrm{CrL}_{3}$ (d) | 29.8 | $1.6 \times 10^{-30}$ | $\mathrm{CaHL} \cdot 2 \mathrm{H}_{2} \mathrm{O}\left(\rightleftharpoons \mathrm{Ca}^{2+}+\mathrm{HL}^{2-}\right)$ | 6.58 | $2.6 \times 10^{-7}$ |
| $\mathrm{FeL}_{3}$ | 38.8 | $1.6 \times 10^{-39}$ | SrHL ( $\rightleftharpoons \mathrm{Sr}^{2+}+\mathrm{HL}^{2-}$ ) (b) | 6.92 | $1.2 \times 10^{-7}$ |
| $\mathrm{CoL}_{3}$ (a) | 44.5 | $3 \times 10^{-45}$ | BaHL ( $\rightleftharpoons \mathrm{Ba}^{2+}+\mathrm{HL}^{2-}$ ) (b) | 7.40 | $4.0 \times 10^{-8}$ |
| $\mathrm{VOL}_{2}\left(\rightleftharpoons \mathrm{VO}^{2+}+2 \mathrm{OH}^{-}\right)$ | 23.5 | $3 \times 10^{-24}$ | LaL (f) | 22.43 | $3.7 \times 10^{-23}$ |
| $\mathrm{PdL}_{2}$ | 28.5 | $3 \times 10^{-29}$ | $\mathrm{Fe}_{3} \mathrm{~L}_{2} \cdot 8 \mathrm{H}_{2} \mathrm{O}$ | 36.0 | $1 \times 10^{-36}$ |
| $\mathrm{ZnL}_{2}$ (amorphous) | 15.52 | $3.0 \times 10^{-16}$ | $\mathrm{FeL} \cdot 2 \mathrm{H}_{2} \mathrm{O}$ | 26.4 | $4 \times 10^{-27}$ |
| $\mathrm{CdL}_{2}(\beta)$ | 14.35 | $4.5 \times 10^{-15}$ | $(\mathrm{VO})_{3} \mathrm{~L}_{2}\left(\rightleftharpoons 3 \mathrm{VO}^{2+}+2 \mathrm{~L}^{3-}\right)$ | 25.1 | $8 \times 10^{-26}$ |
| HgO (red) ( $\rightleftharpoons \mathrm{Hg}^{2+}+2 \mathrm{OH}^{-}$) | 25.44 | $3.6 \times 10^{-26}$ | $\mathrm{Ag}_{3} \mathrm{~L}$ | 17.55 | $2.8 \times 10^{-18}$ |
| $\mathrm{Cu}_{2} \mathrm{O}\left(\rightleftharpoons 2 \mathrm{Cu}^{+}+2 \mathrm{OH}^{-}\right)$ | 29.4 | $4 \times 10^{-30}$ | $\mathrm{Hg}_{2} \mathrm{HL}\left(\rightleftharpoons \mathrm{Hg}_{2}^{2+}+\mathrm{HL}^{2-}\right)$ | 12.40 | $4.0 \times 10^{-13}$ |
| $\mathrm{Ag}_{2} \mathrm{O}\left(\rightleftharpoons 2 \mathrm{Ag}^{+}+2 \mathrm{OH}^{-}\right)$ | 15.42 | $3.8 \times 10^{-16}$ | $\mathrm{Zn}_{3} \mathrm{~L}_{2} \cdot 4 \mathrm{H}_{2} \mathrm{O}$ | 35.3 | $5 \times 10^{-36}$ |
| $\mathrm{AuL}_{3}$ | 5.5 | $3 \times 10^{-6}$ | $\mathrm{Pb}_{3} \mathrm{~L}_{2}$ (c) | 43.53 | $3.0 \times 10^{-44}$ |
| $\mathrm{AlL}_{3}(\alpha)$ | 33.5 | $3 \times 10^{-34}$ | GaL (g) | 21.0 | $1 \times 10^{-21}$ |
| $\mathrm{GaL}_{3}$ (amorphous) | 37 | $10^{-37}$ | InL (g) | 21.63 | $2.3 \times 10^{-22}$ |
| $\mathrm{InL}_{3}$ | 36.9 | $1.3 \times 10^{-37}$ | Sulfates: $\mathrm{L}=\mathrm{SO}_{4}^{2-}$ |  |  |
| $\mathrm{SnO}\left(\rightleftharpoons \mathrm{Sn}^{2+}+2 \mathrm{OH}^{-}\right)$ | 26.2 | $6 \times 10^{-27}$ | CaL | 4.62 | $2.4 \times 10^{-5}$ |
| PbO (yellow) ( $\rightleftharpoons \mathrm{Pb}^{2+}+2 \mathrm{OH}^{-}$) | 15.1 | $8 \times 10^{-16}$ | SrL | 6.50 | $3.2 \times 10^{-7}$ |
| $\mathrm{PbO}($ red $)\left(\rightleftharpoons \mathrm{Pb}^{2+}+2 \mathrm{OH}^{-}\right)$ | 15.3 | $5 \times 10^{-16}$ | BaL | 9.96 | $1.1 \times 10^{-10}$ |
| Iodates: $\mathrm{L}=\mathrm{IO}_{3}^{-}$ |  |  | RaL (b) | 10.37 | $4.3 \times 10^{-11}$ |
| $\mathrm{CaL}_{2}$ | 6.15 | $7.1 \times 10^{-7}$ | $\mathrm{Ag}_{2} \mathrm{~L}$ | 4.83 | $1.5 \times 10^{-5}$ |
| $\mathrm{SrL}_{2}$ | 6.48 | $3.3 \times 10^{-7}$ | $\mathrm{Hg}_{2} \mathrm{~L}$ | 6.13 | $7.4 \times 10^{-7}$ |
| $\mathrm{BaL}_{2}$ | 8.81 | $1.5 \times 10^{-9}$ | PbL | 6.20 | $6.3 \times 10^{-7}$ |
| $\mathrm{YL}_{3}$ | 10.15 | $7.1 \times 10^{-11}$ | Sulfides: $\mathrm{L}=\mathrm{S}^{2-}$ |  |  |
| $\mathrm{LaL}_{3}$ | 10.99 | $1.0 \times 10^{-11}$ |  |  |  |
| $\mathrm{CeL}_{3}$ | 10.86 | $1.4 \times 10^{-11}$ | MnL (pink) | 10.5 | $3 \times 10^{-11}$ |
| $\mathrm{ThL}_{4}$ (f) | 14.62 | $2.4 \times 10^{-15}$ | MnL (green) | 13.5 | $3 \times 10^{-14}$ |
| $\mathrm{UO}_{2} \mathrm{~L}_{2}\left(\rightleftharpoons \mathrm{UO}_{2}^{2+}+2 \mathrm{IO}_{3}^{-}\right)(\mathrm{e})$ | 7.01 | $9.8 \times 10^{-8}$ | FeL | 18.1 | $8 \times 10^{-19}$ |
| $\mathrm{CrL}_{3}$ (f) | 5.3 | $5 \times 10^{-6}$ | CoL ( $\alpha$ ) | 21.3 | $5 \times 10^{-22}$ |
| AgL | 7.51 | $3.1 \times 10^{-8}$ | CoL ( $\beta$ ) | 25.6 | $3 \times 10^{-26}$ |
| $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 17.89 | $1.3 \times 10^{-18}$ | NiL ( $\alpha$ ) | 19.4 | $4 \times 10^{-20}$ |
| TIL | 5.51 | $3.1 \times 10^{-6}$ | NiL ( $\beta$ ) | 24.9 | $1.3 \times 10^{-25}$ |
| $\mathrm{ZnL}_{2}$ | 5.41 | $3.9 \times 10^{-6}$ | $\operatorname{NiL}(\gamma)$ | 26.6 | $3 \times 10^{-27}$ |
| $\mathrm{CdL}_{2}$ | 7.64 | $2.3 \times 10^{-8}$ | CuL | 36.1 | $8 \times 10^{-37}$ |
| $\mathrm{PbL}_{2}$ | 12.61 | $2.5 \times 10^{-13}$ | $\mathrm{Cu}_{2} \mathrm{~L}$ | 48.5 | $3 \times 10^{-49}$ |
|  |  |  | $\mathrm{Ag}_{2} \mathrm{~L}$ | 50.1 | $8 \times 10^{-51}$ |
| Iodides: $\mathrm{L}=\mathrm{I}^{-}$ |  |  | $\mathrm{Tl}_{2} \mathrm{~L}$ | 21.2 | $6 \times 10^{-22}$ |
| CuL | 12.0 | $1 \times 10^{-12}$ | $\mathrm{ZnL}(\alpha)$ | 24.7 | $2 \times 10^{-25}$ |
| AgL | 16.08 | $8.3 \times 10^{-17}$ | ZnL ( $\beta$ ) | 22.5 | $3 \times 10^{-23}$ |
| $\mathrm{CH}_{3} \mathrm{HgL}\left(\rightleftharpoons \mathrm{CH}_{3} \mathrm{Hg}^{+}+\mathrm{I}^{-}\right)(\mathrm{b}, \mathrm{g})$ | 11.46 | $3.5 \times 10^{-12}$ | CdL | 27.0 | $1 \times 10^{-27}$ |
| $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{HgL}\left(\rightleftharpoons \mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{Hg}^{+}+\mathrm{I}^{-}\right)$ | 4.11 | $7.8 \times 10^{-5}$ | HgL (black) | 52.7 | $2 \times 10^{-53}$ |
| TIL | 7.23 | $5.9 \times 10^{-8}$ | HgL (red) | 53.3 | $5 \times 10^{-54}$ |
| $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 28.34 | $4.6 \times 10^{-29}$ | SnL | 25.9 | $1.3 \times 10^{-26}$ |
| $\mathrm{SnL}_{2}$ (i) | 5.08 | $8.3 \times 10^{-6}$ | PbL | 27.5 | $3 \times 10^{-28}$ |
| $\mathrm{PbL}_{2}$ | 8.10 | $7.9 \times 10^{-9}$ | $\mathrm{In}_{2} \mathrm{~L}_{3}$ | 69.4 | $4 \times 10^{-70}$ |
| Oxalates: $\mathrm{L}=\mathrm{C}_{2} \mathrm{O}_{4}^{2-}$ |  |  | Thiocyanates: $\mathrm{L}=\mathrm{SCN}^{-}$ |  |  |
| CaL (b, d) | 7.9 | $1.3 \times 10^{-8}$ | CuL (j) | 13.40 | $4.0 \times 10^{-14}$ |
| SrL (b, d) | 6.4 | $4 \times 10^{-7}$ | AgL | 11.97 | $1.1 \times 10^{-12}$ |
| BaL (b, d) | 6.0 | $1 \times 10^{-6}$ | $\mathrm{Hg}_{2} \mathrm{~L}_{2}$ | 19.52 | $3.0 \times 10^{-20}$ |
| $\mathrm{La}_{2} \mathrm{~L}_{3}$ (b, d) | 25.0 | $1 \times 10^{-25}$ | TIL | 3.79 | $1.6 \times 10^{-4}$ |
| $\mathrm{ThL}_{2}(\mathrm{~g})$ | 21.38 | $4.2 \times 10^{-22}$ | $\mathrm{HgL}_{2}$ | 19.56 | $2.8 \times 10^{-20}$ |
| $\mathrm{UO}_{2} \mathrm{~L}\left(\rightleftharpoons \mathrm{UO}_{2}^{2+}+\mathrm{C}_{2} \mathrm{O}_{4}^{2-}\right)(\mathrm{b}, \mathrm{d})$ | 8.66 | $2.2 \times 10^{-9}$ |  |  |  |

## APPENDIX G Acid Dissociation Constants

| Name | Structure* | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1} \mathbf{M}^{\text {§ }}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}{ }^{\dagger}$ | $\boldsymbol{K}_{\mathbf{a}}{ }^{\ddagger}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}{ }^{\boldsymbol{+}}$ |
| Acetic acid (ethanoic acid) | $\mathrm{CH}_{3} \mathrm{CO}_{2} \mathrm{H}$ | 4.756 | $1.75 \times 10^{-5}$ | 4.56 |
| Alanine | <smiles>CC([NH3+])C(=O)O</smiles> | $9.868\left(\mathrm{NH}_{3}\right)$ | $4.53 \times 10^{-3}$ | 2.33 |
| Aminobenzene (aniline) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-11.jpg?height=69&width=171&top_left_y=659&top_left_x=733) | 4.601 | $2.51 \times 10^{-5}$ | 4.64 |
| 4-Aminobenzenesulfonic acid (sulfanilic acid) | <smiles>[NH3+]c1ccc([18O])cc1</smiles> | 3.232 | $5.86 \times 10^{-4}$ | 3.01 |
| 2-Aminobenzoic acid (anthranilic acid) | <smiles>[NH3+]c1ccccc1C(=O)O</smiles> | $2.08\left(\mathrm{CO}_{2} \mathrm{H}\right)$ <br> $4.96\left(\mathrm{NH}_{3}\right)$ | $8.3 \times 10^{-3}$ <br> $1.10 \times 10^{-5}$ | 2.01 <br> 4.78 |
| 2-Aminoethanethiol (2-mercaptoethylamine) | $\mathrm{HSCH}_{2} \mathrm{CH}_{2} \mathrm{NH}_{3}^{+}$ | $\_\_\_\_$ <br> - |  | 8.21 (SH) <br> $10.73\left(\mathrm{NH}_{3}\right)$ |
| 2-Aminoethanol (ethanolamine) | $\mathrm{HOCH}_{2} \mathrm{CH}_{2} \mathrm{NH}_{3}^{+}$ | 9.498 | $3.18 \times 10^{-10}$ | 9.52 |
| 2-Aminophenol | <smiles>[NH3+]c1ccccc1O</smiles> | $4.70\left(\mathrm{NH}_{3}\right)\left(20^{\circ}\right)$ <br> $9.97(\mathrm{OH})\left(20^{\circ}\right)$ | $2.0 \times 10^{-5}$ <br> $1.05 \times 10^{-10}$ | 4.74 <br> 9.87 |
| Ammonia | $\mathrm{NH}_{4}^{+}$ | 9.245 | $5.69 \times 10^{-10}$ | 9.26 |
| Arginine | <smiles>[NH3+]=C(N)CCCNC(C(=O)O)C([NH3+])[NH3+]</smiles> | $1.823\left(\mathrm{CO}_{2} \mathrm{H}\right)$ <br> $8.991\left(\mathrm{NH}_{3}\right)$ <br> $-\left(\mathrm{NH}_{2}\right)$ | $1.50 \times 10^{-2}$ <br> $1.02 \times 10^{-9}$ $\_\_\_\_$ | 2.03 <br> 9.00 <br> (12.1) |
| Arsenic acid (hydrogen arsenate) | <smiles>[O]=[V]([OH])([OH])[OH]</smiles> | 2.24 <br> 6.96 <br> (11.50) | $5.8 \times 10^{-3}$ <br> $1.10 \times 10^{-7}$ <br> $3.2 \times 10^{-12}$ | 2.15 <br> 6.65 <br> (11.18) |
| Arsenious acid (hydrogen arsenite) | $\mathrm{As}(\mathrm{OH})_{3}$ | 9.29 | $5.1 \times 10^{-10}$ | 9.14 |
| Asparagine | <smiles>NC(=O)CC([NH3+])C(=O)O</smiles> | $\_\_\_\_$ | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-11.jpg?height=43&width=67&top_left_y=2120&top_left_x=1627) | $2.16\left(\mathrm{CO}_{2} \mathrm{H}\right)$ <br> $8.73\left(\mathrm{NH}_{3}\right)$ |

[^3](Continued)

| Name | Structure | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathbf{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Aspartic acid | <smiles>[NH3+]C(CCC(=O)O)C(=O)O</smiles> | $1.990\left(\alpha-\mathrm{CO}_{2} \mathrm{H}\right) 3.900\left(\beta-\mathrm{CO}_{2} \mathrm{H}\right) 10.002\left(\mathrm{NH}_{3}\right)$ | $1.02 \times 10^{-2}$ | 1.95 |
|  |  |  | $1.26 \times 10^{-4}$ | 3.71 |
|  |  |  | $9.95 \times 10^{-11}$ | 9.96 |
| Aziridine (dimethyleneimine) | <smiles>C1C[NH2+]1</smiles> | 8.04 | $9.1 \times 10^{-9}$ | - |
| Benzene-1,2,3-tricarboxylic acid (hemimellitic acid) |  | 2.86 | $1.38 \times 10^{-3}$ | 2.67 |
|  |  | 4.30 | $5.0 \times 10^{-5}$ | 3.91 |
|  |  | 6.28 | $5.2 \times 10^{-7}$ | 5.50 |
| Benzoic acid | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-12.jpg?height=71&width=194&top_left_y=786&top_left_x=571) | 4.202 | $6.28 \times 10^{-5}$ | 4.01 |
| Benzylamine | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-12.jpg?height=71&width=219&top_left_y=913&top_left_x=576) | 9.35 | $4.5 \times 10^{-10}$ | 9.40 |
| 2,2'-Bipyridine | <smiles>c1ccc2n(c1)[In]C1=CC=CC=[N+]21</smiles> <br> - $\underset{\mathrm{H}^{+}+\frac{\mathrm{N}}{\mathrm{H}}}{\text { - }}$ | $\_\_\_\_$ |  | (1.3) |
|  |  | 4.34 | $4.6 \times 10^{-5}$ | 4.41 |
|  | $\mathrm{B}(\mathrm{OH})_{3}$ | 9.237 | $5.79 \times 10^{-10}$ | 8.98 |
| Boric acid (hydrogen borate) |  | (12.74) $\left(20^{\circ}\right)$ (13.80) ( $20^{\circ}$ ) | $1.82 \times 10^{-13}$ | - |
|  |  |  | $1.58 \times 10^{-14}$ | - |
| Bromoacetic acid | $\mathrm{BrCH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 2.902 | $1.25 \times 10^{-3}$ | 2.71 |
| Butane-2,3-dione dioxime (dimethylglyoxime) | <smiles>CC(C)(N=O)NO</smiles> | 10.66 (12.0) | $2.2 \times 10^{-11} 1 \times 10^{-12}$ | 10.45 (11.9) |
| Butanoic acid | $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.818 | $1.52 \times 10^{-5}$ | 4.62 |
| cis-Butenedioic acid (maleic acid) |  |  |  |  |
|  |  | 1.92 | $1.20 \times 10^{-2}$ | 1.75 |
|  |  | 6.27 | $5.37 \times 10^{-7}$ | 5.84 |
| trans-Butenedioic acid (fumaric acid) |  | 3.02 | $9.5 \times 10^{-4}$ | 2.84 |
|  |  | 4.48 | $3.3 \times 10^{-5}$ | 4.09 |
| Butylamine | $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{NH}_{3}^{+}$ | 10.640 | $2.29 \times 10^{-11}$ | 10.66 |
| Carbonic acid* (hydrogen carbonate) |  | 6.351 | $4.46 \times 10^{-7}$ | 6.13 |
|  |  | 10.329 | $4.69 \times 10^{-11}$ | 9.91 |
| Chloroacetic acid | $\mathrm{ClCH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 2.865 | $1.36 \times 10^{-3}$ | 2.69 |
| 3-Chloropropanoic acid | $\mathrm{ClCH}_{2} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.11 | $7.8 \times 10^{-5}$ | 3.92 |
| Chlorous acid (hydrogen chlorite) | $\mathrm{HOCl}=\mathrm{O}$ | 1.96 | $1.10 \times 10^{-2}$ | - |

[^4]| Name | Structure | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathrm{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Chromic acid (hydrogen chromate) | <smiles>[O]=[Cr](=[O])([OH])[OH]</smiles> | (-0.2) $\left(20^{\circ}\right)$ 6.51 | 1.6 $3.1 \times 10^{-7}$ | $(-0.6)\left(20^{\circ} \mathrm{C}\right)$ 6.05 |
| Citric acid (2-hydroxypropane-1,2,3tricarboxylic acid) | <smiles>O=C(O)CC(O)(C(=O)O)C(=O)O</smiles> | 3.128 4.761 6.396 | $7.44 \times 10^{-4} 1.73 \times 10^{-5} 4.02 \times 10^{-7}$ | 2.90 4.35 5.70 |
| Cyanoacetic acid | $\mathrm{NCCH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 2.472 | $3.37 \times 10^{-3}$ | - |
| Cyclohexylamine | <smiles>[NH3+]C1CCCCC1</smiles> | 10.567 | $2.71 \times 10^{-11}$ | 10.62 |
| Cysteine | <smiles>[NH3+]C(CS)C(=O)O</smiles> | (1.7) $\left(\mathrm{CO}_{2} \mathrm{H}\right) 8.36(\mathrm{SH}) 10.74\left(\mathrm{NH}_{3}\right)$ | $2 \times 10^{-2} 4.4 \times 10^{-9} 1.82 \times 10^{-11}$ | (1.90) 8.18 10.30 |
| Dichloroacetic acid | $\mathrm{Cl}_{2} \mathrm{CHCO}_{2} \mathrm{H}$ | (1.1) | $8 \times 10^{-2}$ | (0.9) |
| Diethylamine | $\left(\mathrm{CH}_{3} \mathrm{CH}_{2}\right)_{2} \mathrm{NH}_{2}^{+}$ | 11.00 | $1.0 \times 10^{-11}$ | 11.04 |
| 1,2-Dihydroxybenzene (catechol) | <smiles>Oc1ccccc1O</smiles> | $\_\_\_\_$ | $3.5 \times 10^{-10}$ $\_\_\_\_$ $\_\_\_\_$ | 9.26 (13.3) |
| 1,3-Dihydroxybenzene (resorcinol) | <smiles>Oc1cccc(O)c1</smiles> | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-13.jpg?height=23&width=68&top_left_y=1452&top_left_x=1219) | $\_\_\_\_$ | 11.06 |
| D-2,3-Dihydroxybutanedioic acid (D-tartaric acid) | <smiles>O=C(O)C(O)C(O)C(=O)O</smiles> | 3.036 4.366 | $9.20 \times 10^{-4} 4.31 \times 10^{-5}$ | 2.82 3.97 |
| 2,3-Dimercaptopropanol | <smiles>OCC(S)CS</smiles> | $\_\_\_\_$ $\_\_\_\_$ | $\_\_\_\_$ | 10.65 |
| Dimethylamine | $\left(\mathrm{CH}_{3}\right)_{2} \mathrm{NH}_{2}^{+}$ | 10.774 | $1.68 \times 10^{-11}$ | 10.81 |
| 2,4-Dinitrophenol | <smiles>O=[N+]([O-])c1ccc(O)c([N+](=O)[O-])c1</smiles> | 4.114 | $7.69 \times 10^{-5}$ | 3.92 |
| Ethane-1,2-dithiol | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-13.jpg?height=38&width=192&top_left_y=2193&top_left_x=729) | $\_\_\_\_$ $\_\_\_\_$ | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-13.jpg?height=23&width=68&top_left_y=2202&top_left_x=1650) |  |
|  |  |  |  |  |
|  |  |  |  |  |

(Continued)

| Name | Structure | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathbf{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Ethylenedinitrilotetraacetic acid (EDTA) | $\left(\mathrm{HO}_{2} \mathrm{CCH}_{2}\right)_{2} \stackrel{+}{\mathrm{N}} \mathrm{HCH}_{2} \mathrm{CH}_{2} \stackrel{+}{\mathrm{N}} \mathrm{H}\left(\mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}\right)_{2}$ | $-\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | - | (0.0) $\left(\mathrm{CO}_{2} \mathrm{H}\right)(\mu=1 \mathrm{M})$ |
|  |  | $-\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | - | (1.5) $\left(\mathrm{CO}_{2} \mathrm{H}\right)$ |
|  |  | $-\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | - | $2.00\left(\mathrm{CO}_{2} \mathrm{H}\right)$ |
|  |  | $-\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | - | $2.69\left(\mathrm{CO}_{2} \mathrm{H}\right)$ |
|  |  | 6.273 (NH) | $5.3 \times 10^{-7}$ | $6.13(\mathrm{NH})$ |
|  |  | 10.948 (NH) | $1.13 \times 10^{-11}$ | 10.37 (NH) |
| ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-14.jpg?height=31&width=151&top_left_y=464&top_left_x=106) | $\mathrm{HCO}_{2} \mathrm{H}$ | 3.744 | $1.80 \times 10^{-4}$ | 3.57 |
| Glutamic acid |  | $2.160\left(\alpha-\mathrm{CO}_{2} \mathrm{H}\right)$ | $6.92 \times 10^{-3}$ | 2.16 |
|  |  | $4.30\left(\gamma-\mathrm{CO}_{2} \mathrm{H}\right)$ | $5.0 \times 10^{-5}$ | 4.15 |
|  | <smiles>[NH3+]C(CCC(=O)O)C(=O)O</smiles> | $9.96\left(\mathrm{NH}_{3}\right)$ <br> $1.10 \times 10^{-10}$ <br> $9.96\left(\mathrm{NH}_{3}\right) \quad 1.10 \times 10^{-10}$ |  |  |
| Glutamine | <smiles>NC(=O)CCC([NH3+])C(=O)O</smiles> | $\_\_\_\_$ $\_\_\_\_$ | $\_\_\_\_$ <br> - | $2.19\left(\mathrm{CO}_{2} \mathrm{H}\right)$ <br> $2.19\left(\mathrm{CO}_{2} \mathrm{H}\right) 9.00\left(\mathrm{NH}_{3}\right) 9.00\left(\mathrm{NH}_{3}\right)$ |
|  |  |  |  |  |
| Glycine (aminoacetic acid) |  | $2.350\left(\mathrm{CO}_{2} \mathrm{H}\right) 9.778\left(\mathrm{NH}_{3}\right)$ | 2.33 <br> $4.47 \times 10^{-3}$ <br> $1.67 \times 10^{-10}$ |  |
|  |  |  |  |  |  |
|  |  |  |  |  |  |
| Guanidine | <smiles>NC(N)=[NH2+]</smiles> | - |  |  |
| 1,6-Hexanedioic acid (adipic acid) | $\mathrm{HO}_{2} \mathrm{CCH}_{2} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.424 5.420 | $3.77 \times 10^{-5}$ <br> $3.80 \times 10^{-6}$ |  |
|  |  |  |  |  |
| Hexane-2,4-dione | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-14.jpg?height=99&width=253&top_left_y=1372&top_left_x=491) | 9.38 | $4.2 \times 10^{-10}$ |  |
|  |  |  | $3 \times 10^{-2}$ | (1.7) <br> 6.05 <br> 9.10 |
|  |  |  |  |  |
|  |  |  |  |  |
| Hydrazine | $\mathrm{H}_{3} \stackrel{+}{\mathrm{N}}-\stackrel{+}{\mathrm{N}} \mathrm{H}_{3}$ | -0.99 $7.98$ |  | $\stackrel{(-0.21)}{8.07}(\mu=0.5 \mathrm{M})$ <br> ( -0.21 ) ( $\mu=0.5 \mathrm{M}$ ) <br> 21) ( $\mu=0.5 \mathrm{M}$ ) <br> 07 8.07 |
|  |  |  | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-14.jpg?height=75&width=158&top_left_y=1730&top_left_x=1424) |  |
| Hydrazoic acid (hydrogen azide) | $\mathrm{HN}=\stackrel{+}{\mathrm{N}}=\overline{\mathrm{N}}$ | 4.65 | $2.2 \times 10^{-5}$ | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-14.jpg?height=97&width=73&top_left_y=1810&top_left_x=1873) |
|  |  |  |  |  |
| Hydrogen cyanate | $\mathrm{HOC} \equiv \mathrm{N}$ | 3.48 | $3.3 \times 10^{-4}$ | - |
| Hydrogen cyanide | $\mathrm{HC} \equiv \mathrm{N}$ | 9.21 | $6.2 \times 10^{-10}$ | 9.04 |
| Hydrogen fluoride | HF | 3.17 | $6.8 \times 10^{-4}$ | 2.94 |
| Hydrogen peroxide | HOOH | 11.65 | $2.2 \times 10^{-12}$ | - |
| Hydrogen sulfide | $\mathrm{H}_{2} \mathrm{~S}$ | 7.02 <br> 14.0* |  |  |
|  |  |  |  |  |
|  |  |  |  |  |
|  |  |  |  |  |

[^5]| Name | Structure | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathrm{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Hydroxybenzene (phenol) | <smiles>Oc1ccccc1</smiles> | 9.997 | $1.01 \times 10^{-10}$ | 9.78 |
| 2-Hydroxybenzoic acid (salicylic acid) | <smiles>O=C(O)c1ccccc1O</smiles> | $2.972\left(\mathrm{CO}_{2} \mathrm{H}\right)$ (13.7) (OH) | $1.07 \times 10^{-3} 2 \times 10^{-14}$ | 2.80 (13.4) |
| l-Hydroxybutanedioic acid (malic acid) | <smiles>O=C(O)CC(O)C(=O)O</smiles> | 3.459 5.097 | $3.48 \times 10^{-4} 8.00 \times 10^{-6}$ | 3.24 4.68 |
| Hydroxylamine | $\mathrm{HO} \stackrel{+}{\mathrm{N}} \mathrm{H}_{3}$ | $5.96(\mathrm{NH})$ (13.74) (OH) | $1.10 \times 10^{-6} 1.8 \times 10^{-14}$ | 5.96 |
| 8-Hydroxyquinoline (oxine) | <smiles>Oc1cccc2ccc[nH+]c12</smiles> | 4.94 (NH) | $1.15 \times 10^{-5}$ | 4.97 |
| Hypobromous acid (hydrogen hypobromite) | HOBr | 8.63 | $2.3 \times 10^{-9}$ | - |
| Hypochlorous acid (hydrogen hypochlorite) | HOCl | 7.53 | $3.0 \times 10^{-8}$ | - |
| Hypoiodous acid (hydrogen hypoiodite) | HOI | 10.64 | $2.3 \times 10^{-11}$ | - |
| Hypophosphorous acid (hydrogen hypophosphite) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-15.jpg?height=97&width=99&top_left_y=1243&top_left_x=732) | (1.3) | $5 \times 10^{-2}$ | (1.1) |
| Imidazole (1,3-diazole) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-15.jpg?height=115&width=115&top_left_y=1378&top_left_x=732) | 6.993 (14.5) | $1.02 \times 10^{-7} 3 \times 10^{-15}$ | 7.00 |
| Iminodiacetic acid | $\mathrm{H}_{2} \stackrel{+}{\mathrm{N}}\left(\mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}\right)_{2}$ | (1.85) $\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $1.41 \times 10^{-2}$ | (1.77) |
|  |  | $2.84\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $1.45 \times 10^{-3}$ | 2.62 |
|  |  | $9.79\left(\mathrm{NH}_{2}\right)$ | $1.62 \times 10^{-10}$ | 9.34 |
| Iodic acid (hydrogen iodate) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-15.jpg?height=89&width=119&top_left_y=1688&top_left_x=732) | 0.77 | 0.17 | - |
| Iodoacetic acid | $\mathrm{ICH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 3.175 | $6.68 \times 10^{-4}$ | 2.98 |
| Isoleucine | <smiles>CCCC(C)C([NH3+])C(=O)O</smiles> | $2.318\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $4.81 \times 10^{-3}$ | 2.26 |
| Leucine | <smiles>CC(C)CC([NH3+])C(=O)O</smiles> | 2.328 ( $\mathrm{CO}_{2} \mathrm{H}$ ) | $4.70 \times 10^{-3}$ | 2.32 |
| Lysine | <smiles>[NH3+]CCCCC([NH3+])C(=O)O</smiles> | $10.82\left(\epsilon-\mathrm{NH}_{3}\right)$ | $1.51 \times 10^{-11}$ | 10.66 |

(Continued)

| Name | Structure | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathrm{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Malonic acid (propanedioic acid) | $\mathrm{HO}_{2} \mathrm{CCH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 2.847 | $1.42 \times 10^{-3}$ | 2.65 |
|  |  | 5.696 | $2.01 \times 10^{-6}$ | 5.27 |
| Mercaptoacetic acid (thioglycolic acid) | $\mathrm{HSCH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | $3.64\left(\mathrm{CO}_{2} \mathrm{H}\right)$ 10.61 (SH) | $2.3 \times 10^{-4}$ | 3.48 |
|  |  |  | $2.5 \times 10^{-11}$ | 10.11 |
| 2-Mercaptoethanol | $\mathrm{HSCH}_{2} \mathrm{CH}_{2} \mathrm{OH}$ | 9.72 $\_\_\_\_$ | $1.9 \times 10^{-10}$ | 9.40 |
| Methionine | <smiles>CCCC([NH3+])C(=O)O</smiles> |  | - | $2.18\left(\mathrm{CO}_{2} \mathrm{H}\right)$ |
| 2-Methoxyaniline (o-anisidine) | <smiles>COc1ccccc1N</smiles> | 4.526 | $2.98 \times 10^{-5}$ | _ |
| 4-Methoxyaniline ( $p$-anisidine) | <smiles>COc1ccc([NH3+])cc1</smiles> | 5.357 | $4.40 \times 10^{-6}$ | 5.33 |
| Methylamine | $\mathrm{CH}_{3} \stackrel{+}{\mathrm{N}} \mathrm{H}_{3}$ | 10.632 | $2.33 \times 10^{-11}$ | 10.65 |
| 2-Methylaniline (o-toluidine) | <smiles>Cc1ccccc1N</smiles> | 4.447 | $3.57 \times 10^{-5}$ | - |
| 4-Methylaniline ( $p$-toluidine) | <smiles>Cc1ccc([NH3+])cc1</smiles> | 5.080 | $8.32 \times 10^{-6}$ | 5.09 |
| 2-Methylphenol (o-cresol) | <smiles>Cc1ccccc1O</smiles> | 10.31 | $4.9 \times 10^{-11}$ | 10.09 |
| 4-Methylphenol ( $p$-cresol) | <smiles>Cc1ccc(O)cc1</smiles> | 10.269 | $5.5 \times 10^{-11}$ | 10.04 |
| Morpholine (perhydro-1,4-oxazine) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-16.jpg?height=71&width=138&top_left_y=1621&top_left_x=577) | 8.492 | $3.22 \times 10^{-9}$ | - |
| 1-Naphthoic acid | <smiles>O=C(O)c1cccc2ccccc12</smiles> | 3.67 | $2.1 \times 10^{-4}$ | - |
| 2-Naphthoic acid | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-16.jpg?height=97&width=229&top_left_y=1915&top_left_x=573) | 4.16 | $6.9 \times 10^{-5}$ | - |
| 1-Naphthol | <smiles>Oc1cccc2ccccc12</smiles> | 9.416 | $3.84 \times 10^{-10}$ | 9.14 |
| 2-Naphthol | <smiles>Oc1ccc2ccccc2c1</smiles> | 9.573 | $2.67 \times 10^{-10}$ | 9.31 |
| Nitrilotriacetic acid |  | $-\left(\mathrm{CO}_{2} \mathrm{H}\right)$ |  | (1.0) |
|  | $\stackrel{+}{\mathrm{H}}\left(\mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}\right)_{3}$ | $2.0\left(\mathrm{CO}_{2} \mathrm{H}\right)\left(25^{\circ}\right)$ | 0.010 | 1.81 |
|  |  | $2.940\left(\mathrm{CO}_{2} \mathrm{H}\right)\left(20^{\circ}\right)$ | $5 \times 10^{-3}$ | 2.52 |
|  |  | $10.334(\mathrm{NH})\left(20^{\circ}\right)$ | $4.63 \times 10^{-11}$ | 46 |

## AP16

| Name |  | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  | Structure | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathrm{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| 2-Nitrobenzoic acid | <smiles>O=C(O)c1ccccc1[N+](=O)[O-]</smiles> | 2.185 | $6.53 \times 10^{-3}$ | - |
| 3-Nitrobenzoic acid | <smiles>O=C(O)c1cccc([N+](=O)[O-])c1</smiles> | 3.449 | $3.56 \times 10^{-4}$ | 3.28 |
| 4-Nitrobenzoic acid | <smiles>O=C(O)c1ccc([N+](=O)[O-])cc1</smiles> | 3.442 | $3.61 \times 10^{-4}$ | 3.28 |
| Nitroethane | $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{NO}_{2}$ | 8.57 | $2.7 \times 10^{-9}$ | - |
| 2-Nitrophenol | <smiles>O=[N+]([O-])c1ccccc1O</smiles> | 7.230 | $5.89 \times 10^{-8}$ | 7.04 |
| 3-Nitrophenol | <smiles>O=[N+]([O-])c1cccc(O)c1</smiles> | 8.37 | $4.3 \times 10^{-9}$ | 8.16 |
| 4-Nitrophenol | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-17.jpg?height=69&width=239&top_left_y=1093&top_left_x=749) | 7.149 | $7.10 \times 10^{-8}$ | 6.96 |
| $N$-Nitrosophenylhydroxylamine (cupferron) | <smiles>ON(O)c1ccccc1</smiles> | - | - | 4.16 |
| Nitrous acid | $\mathrm{HON}=\mathrm{O}$ | 3.15 | $7.1 \times 10^{-4}$ | - |
| Oxalic acid (ethanedioic acid) | $\mathrm{HO}_{2} \mathrm{CCO}_{2} \mathrm{H}$ | 1.250 <br> 4.266 | $5.62 \times 10^{-2}$ <br> $5.42 \times 10^{-5}$ | (1.2) <br> 3.80 |
| Oxoacetic acid (glyoxylic acid) | <smiles>O=CC(=O)O</smiles> | 3.46 | $3.5 \times 10^{-4}$ | 3.05 |
| Oxobutanedioic acid (oxaloacetic acid) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-17.jpg?height=95&width=224&top_left_y=1628&top_left_x=749) | 2.56 <br> 4.37 | $2.8 \times 10^{-3}$ <br> $4.3 \times 10^{-5}$ | 2.26 <br> 3.90 |
| 2-Oxopentanedioic ( $\alpha$-ketoglutaric acid) | <smiles>O=C(O)CCC(=O)O</smiles> | - <br> - | $\_\_\_\_$ <br> - | (1.9) ( $\mu=0.5 \mathrm{M}$ ) <br> 4.44 ( $\mu=0.5 \mathrm{M}$ ) |
| 2-Oxopropanoic acid (pyruvic acid) | <smiles>CC(=O)O</smiles> | 2.48 | $3.3 \times 10^{-3}$ | 2.26 |
| 1,5-Pentanedioic acid (glutaric acid) | $\mathrm{HO}_{2} \mathrm{CCH}_{2} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.345 <br> 5.422 | $4.52 \times 10^{-5}$ <br> $3.78 \times 10^{-6}$ | 4.19 <br> 5.06 |
| Pentanoic acid (valeric acid) | $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.843 | $1.44 \times 10^{-5}$ | $4.63\left(18^{\circ} \mathrm{C}\right)$ |
| 1,10-Phenanthroline | <smiles>c1c[nH+]c2c(c1)ccc1cc[n-]c12</smiles> | 4.91 | $1.23 \times 10^{-5}$ | (1.8) |
| Phenylacetic acid | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-17.jpg?height=69&width=235&top_left_y=2378&top_left_x=749) | 4.310 | $4.90 \times 10^{-5}$ | 4.11 |


| Name | Structure | Ionic strength $\boldsymbol{(} \boldsymbol{\mu} \boldsymbol{)} \boldsymbol{=} \mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  |  | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathrm{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Phenylalanine | <smiles>[NH3+]C(Cc1ccccc1)C(=O)O</smiles> | $2.20\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $6.3 \times 10^{-3}$ | 2.18 |
| Phosphoric acid* (hydrogen phosphate) | <smiles>O=P(O)(O)O</smiles> | 2.148 | $7.11 \times 10^{-3}$ | 1.92 |
|  |  | 7.198 | $6.34 \times 10^{-8}$ | 6.71 |
|  |  | 12.375 | $4.22 \times 10^{-13}$ | 11.52 |
| Phosphorous acid (hydrogen phosphite) |  | (1.5) | $1.66 \times 10^{-7}$ | - |
| Phthalic acid (benzene-1,2-dicarboxylic acid) | <smiles>O=C(O)c1ccccc1C(=O)O</smiles> <br> $\bigcirc_{\mathrm{CO}_{2} \mathrm{H}}^{\mathrm{CO}_{2} \mathrm{H}}$ | 2.950 | $3.90 \times 10^{-6}$ | 2.76 |
| Piperazine (perhydro-1,4-diazine) | <smiles>C1CC[NH2+]C1</smiles> <br> $\stackrel{+}{\mathrm{H}} 2 \stackrel{N}{\mathrm{~N}} \stackrel{+}{\mathrm{H}} 2$ | 5.333 | $4.65 \times 10^{-6}$ | 5.64 |
|  |  | 9.731 | $1.86 \times 10^{-10}$ | 9.74 |
| Piperidine | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-18.jpg?height=76&width=121&top_left_y=1069&top_left_x=652) | 11.125 | $7.50 \times 10^{-12}$ | 11.08 |
| Proline | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-18.jpg?height=115&width=177&top_left_y=1184&top_left_x=652) | $1.952\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $1.12 \times 10^{-2}$ | 1.89 |
|  |  | $10.640\left(\mathrm{NH}_{2}\right)$ | $2.29 \times 10^{-11}$ | 10.46 |
| Propanoic acid | $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.874 | $1.34 \times 10^{-5}$ | 4.69 |
| Propenoic acid (acrylic acid) | $\mathrm{H}_{2} \mathrm{C}=\mathrm{CHCO}_{2} \mathrm{H}$ | 4.258 | $5.52 \times 10^{-5}$ | - |
| Propylamine | $\mathrm{CH}_{3} \mathrm{CH}_{2} \mathrm{CH}_{2} \mathrm{NH}_{3}^{+}$ | 10.566 | $2.72 \times 10^{-11}$ | 10.64 |
| Pyridine (azine) | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-18.jpg?height=71&width=126&top_left_y=1605&top_left_x=652) | 5.20 | $6.3 \times 10^{-6}$ | 5.24 |
| Pyridine-2-carboxylic acid (picolinic acid) |  | (1.01) $\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $9.8 \times 10^{-2}$ | (0.95) |
| Pyridine-3-carboxylic acid (nicotinic acid) |  | $2.03\left(\mathrm{CO}_{2} \mathrm{H}\right)$ | $1.51 \times 10^{-5}$ | 2.08 |
| Pyridoxal-5-phosphate | <smiles>Cc1[nH+]c(COP(=O)(O)O)c(C=O)c1O</smiles> | - | - | (1.4) $(\mathrm{POH})$ |
| Pyrophosphoric acid (hydrogen diphosphate) | O O $\left.\underset{(\mathrm{HO})_{2} \mathrm{POP}}{\\|} \mathrm{OH}\right)_{2}$ | (0.9) | 0.13 | (0.8) |
|  |  | 2.28 | $5.2 \times 10^{-3}$ | (1.9) |
|  |  | 6.70 | $2.0 \times 10^{-7}$ | 5.94 |
|  |  | 9.40 | $4.0 \times 10^{-10}$ | 8.25 |

[^6]| Name |  | Ionic strength $(\boldsymbol{\mu})=\mathbf{0}$ |  | $\boldsymbol{\mu}=\mathbf{0 . 1 ~ M}$ |
| :--- | :--- | :--- | :--- | :--- |
|  | Structure | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ | $\boldsymbol{K}_{\mathrm{a}}$ | $\mathbf{p} \boldsymbol{K}_{\mathbf{a}}$ |
| Pyrrolidine | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-19.jpg?height=72&width=117&top_left_y=215&top_left_x=807) | 11.305 | $4.95 \times 10^{-12}$ | 11.3 |
| Serine | <smiles>[NH3+]C(CO)C(=O)O</smiles> | 2.187 ( $\mathrm{CO}_{2} \mathrm{H}$ ) <br> $9.209\left(\mathrm{NH}_{3}\right)$ | $6.50 \times 10^{-3}$ <br> $6.18 \times 10^{-10}$ | 2.16 <br> 9.05 |
| Succinic acid (butanedioic acid) | $\mathrm{HO}_{2} \mathrm{CCH}_{2} \mathrm{CH}_{2} \mathrm{CO}_{2} \mathrm{H}$ | 4.207 <br> 5.636 | $6.21 \times 10^{-5}$ <br> $2.31 \times 10^{-6}$ | 3.99 <br> 5.24 |
| Sulfuric acid (hydrogen sulfate) | <smiles>O=S(=O)(O)O</smiles> | $1.987\left(\mathrm{p} K_{2}\right)$ | $1.03 \times 10^{-2}$ | 1.54 |
| Sulfurous acid (hydrogen sulfite) | O <br> HOSOH | 1.857 <br> 7.172 | $1.39 \times 10^{-2}$ <br> $6.73 \times 10^{-8}$ | 1.66 <br> 6.85 |
| Thiosulfuric acid (hydrogen thiosulfate) | <smiles>O=[SbH]([SH])=O</smiles> | (0.6) <br> (1.6) | 0.3 0.03 | (1.3) |
| Threonine | <smiles>CC(O)C([NH3+])C(=O)O</smiles> | 2.088 ( $\mathrm{CO}_{2} \mathrm{H}$ ) <br> $9.100\left(\mathrm{NH}_{3}\right)$ | $8.17 \times 10^{-3}$ <br> $7.94 \times 10^{-10}$ | 2.20 <br> 8.94 |
| Trichloroacetic acid | $\mathrm{Cl}_{3} \mathrm{CCO}_{2} \mathrm{H}$ | (-0.5) | 3 | - |
| Triethanolamine | $\left(\mathrm{HOCH}_{2} \mathrm{CH}_{2}\right)_{3} \mathrm{NH}^{+}$ | 7.762 | $1.73 \times 10^{-8}$ | 7.85 |
| Triethylamine | $\left(\mathrm{CH}_{3} \mathrm{CH}_{2}\right)_{3} \mathrm{NH}^{+}$ | 10.72 | $1.9 \times 10^{-11}$ | 10.76 |
| 1,2,3-Trihydroxybenzene (pyrogallol) | <smiles>Oc1cccc(O)c1O</smiles> | $\_\_\_\_$ <br> - | $\_\_\_\_$ |  |
| Trimethylamine | $\left(\mathrm{CH}_{3}\right)_{3} \mathrm{NH}^{+}$ | 9.799 | $1.59 \times 10^{-10}$ | 9.82 |
| Tris(hydroxymethyl)aminomethane (tris or tham) | $\left(\mathrm{HOCH}_{2}\right)_{3} \mathrm{CNH}_{3}^{+}$ | 8.072 | $8.47 \times 10^{-9}$ | 8.10 |
| Tryptophan | <smiles>[NH3+]C(Cc1c[nH]c2ccccc12)C(=O)O</smiles> | $\_\_\_\_$ | $\_\_\_\_$ | $2.37\left(\mathrm{CO}_{2} \mathrm{H}\right) 9.33\left(\mathrm{NH}_{3}\right)$ |
| Tyrosine | <smiles>[NH3+]C(Cc1ccc(O)cc1)C(=O)O</smiles> | ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-19.jpg?height=18&width=74&top_left_y=2053&top_left_x=1321) | $\_\_\_\_$ | $11.01(\mathrm{OH})$ |
| Valine | <smiles>CC(C)C([NH3+])C(=O)O</smiles> | 2.286 ( $\mathrm{CO}_{2} \mathrm{H}$ ) <br> $9.719\left(\mathrm{NH}_{3}\right)$ | $5.18 \times 10^{-3}$ <br> $1.91 \times 10^{-10}$ | 2.27 <br> 9.52 |
| Water* | $\mathrm{H}_{2} \mathrm{O}$ | 13.997 | $1.01 \times 10^{-14}$ | - |

[^7]| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| Aluminum |  |  |
| $\mathrm{Al}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Al}(s)$ | -1.677 | 0.533 |
| $\mathrm{AlCl}^{2+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Al}(s)+\mathrm{Cl}^{-}$ | -1.802 |  |
| $\mathrm{AlF}_{6}^{3-}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Al}(s)+6 \mathrm{~F}^{-}$ | -2.069 |  |
| $\mathrm{Al}(\mathrm{OH})_{4}^{-}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Al}(s)+4 \mathrm{OH}^{-}$ | -2.328 | -1.13 |
| Antimony |  |  |
| $\mathrm{SbO}^{+}+2 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sb}(s)+\mathrm{H}_{2} \mathrm{O}$ | 0.208 |  |
| $\mathrm{Sb}_{2} \mathrm{O}_{3}(s)+6 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Sb}(s)+3 \mathrm{H}_{2} \mathrm{O}$ | 0.147 | -0.369 |
| $\mathrm{Sb}(s)+3 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{SbH}_{3}(g)$ | -0.510 | -0.030 |
| Arsenic |  |  |
| $\mathrm{H}_{3} \mathrm{AsO}_{4}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{3} \mathrm{AsO}_{3}+\mathrm{H}_{2} \mathrm{O}$ | 0.575 | -0.257 |
| $\mathrm{H}_{3} \mathrm{AsO}_{3}+3 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{As}(s)+3 \mathrm{H}_{2} \mathrm{O}$ | 0.2475 | -0.505 |
| $\mathrm{As}(s)+3 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{AsH}_{3}(g)$ | -0.238 | -0.029 |
| Barium |  |  |
| $\mathrm{Ba}^{2+}+2 \mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Ba}($ in Hg$)$ | -1.717 |  |
| $\mathrm{Ba}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ba}(s)$ | -2.906 | -0.401 |
| Beryllium |  |  |
| $\mathrm{Be}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Be}(s)$ | -1.968 | 0.60 |
| Bismuth |  |  |
| $\mathrm{Bi}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \operatorname{Bi}(s)$ | 0.308 | 0.18 |
| $\mathrm{BiCl}_{4}^{-}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Bi}(s)+4 \mathrm{Cl}^{-}$ | 0.16 |  |
| $\operatorname{BiOCl}(s)+2 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Bi}(s)+\mathrm{H}_{2} \mathrm{O}+\mathrm{Cl}^{-}$ | 0.160 |  |
| Boron |  |  |
| $2 \mathrm{~B}(s)+6 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{B}_{2} \mathrm{H}_{6}(g)$ | -0.150 | -0.296 |
| $\mathrm{B}_{4} \mathrm{O}_{7}^{2-}+14 \mathrm{H}^{+}+12 \mathrm{e}^{-} \rightleftharpoons 4 \mathrm{~B}(s)+7 \mathrm{H}_{2} \mathrm{O}$ | -0.792 |  |
| $\mathrm{B}(\mathrm{OH})_{3}+3 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{B}(s)+3 \mathrm{H}_{2} \mathrm{O}$ | -0.889 | -0.492 |
| Bromine |  |  |
| $\mathrm{BrO}_{4}^{-}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{BrO}_{3}^{-}+\mathrm{H}_{2} \mathrm{O}$ | 1.745 | -0.511 |
| $\mathrm{HOBr}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{Br}_{2}(l)+\mathrm{H}_{2} \mathrm{O}$ | 1.584 | -0.75 |
| $\mathrm{BrO}_{3}^{-}+6 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{Br}_{2}(l)+3 \mathrm{H}_{2} \mathrm{O}$ | 1.513 | -0.419 |
| $\mathrm{Br}_{2}(a q)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Br}^{-}$ | 1.098 | -0.499 |
| $\mathrm{Br}_{2}(l)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Br}^{-}$ | 1.078 | -0.611 |
| $\mathrm{Br}_{3}^{-}+2 \mathrm{e}^{-} \rightleftharpoons 3 \mathrm{Br}^{-}$ | 1.062 | -0.512 |
| $\mathrm{BrO}^{-}+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Br}^{-}+2 \mathrm{OH}^{-}$ | 0.766 | -0.94 |
| $\mathrm{BrO}_{3}^{-}+3 \mathrm{H}_{2} \mathrm{O}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{Br}^{-}+6 \mathrm{OH}^{-}$ | 0.613 | -1.287 |
| Cadmium |  |  |
| $\mathrm{Cd}^{2+}+2 \mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Cd}($ in Hg$)$ | -0.380 |  |
| $\mathrm{Cd}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cd}(s)$ | -0.402 | -0.029 |
| $\mathrm{Cd}\left(\mathrm{C}_{2} \mathrm{O}_{4}\right)(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cd}(s)+\mathrm{C}_{2} \mathrm{O}_{4}^{2-}$ | -0.522 |  |
| $\mathrm{Cd}\left(\mathrm{C}_{2} \mathrm{O}_{4}\right)_{2}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cd}(s)+2 \mathrm{C}_{2} \mathrm{O}_{4}^{2-}$ | -0.572 |  |
| $\mathrm{Cd}\left(\mathrm{NH}_{3}\right)_{4}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cd}(s)+4 \mathrm{NH}_{3}$ | -0.613 |  |
| $\mathrm{CdS}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cd}(s)+\mathrm{S}^{2-}$ | -1.175 |  |
| Calcium |  |  |
| $\mathrm{Ca}(s)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{CaH}_{2}(s)$ | 0.776 |  |
| $\mathrm{Ca}^{2+}+2 \mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Ca}($ in Hg$)$ | -2.003 |  |
| $\mathrm{Ca}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ca}(s)$ | -2.868 | -0.186 |

[^8]| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| $\mathrm{Ca}(\text { acetate })^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ca}(s)+$ acetate $^{-}$ | -2.891 |  |
| $\mathrm{CaSO}_{4}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ca}(s)+\mathrm{SO}_{4}^{2-}$ | -2.936 |  |
| $\mathrm{Ca}($ malonate $)(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ca}(s)+$ malonate $^{2-}$ | -3.608 |  |
| Carbon |  |  |
| $\mathrm{C}_{2} \mathrm{H}_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{C}_{2} \mathrm{H}_{4}(g)$ | 0.731 |  |
| ![](https://cdn.mathpix.com/cropped/e3418fe6-7511-4241-880e-64fe2d6d92a2-21.jpg?height=71&width=672&top_left_y=351&top_left_x=294) | 0.700 |  |
| $\mathrm{CH}_{3} \mathrm{OH}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{CH}_{4}(\mathrm{~g})+\mathrm{H}_{2} \mathrm{O}$ | 0.583 | -0.039 |
| Dehydroascorbic acid $+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons$ ascorbic acid $+\mathrm{H}_{2} \mathrm{O}$ | 0.390 |  |
| $(\mathrm{CN})_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{HCN}(a q)$ | 0.373 |  |
| $\mathrm{H}_{2} \mathrm{CO}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{CH}_{3} \mathrm{OH}$ | 0.237 | -0.51 |
| $\mathrm{C}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{CH}_{4}(g)$ | 0.1315 | -0.209 2 |
| $\mathrm{HCO}_{2} \mathrm{H}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{CO}+\mathrm{H}_{2} \mathrm{O}$ | -0.029 | -0.63 |
| $\mathrm{CO}_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{CO}(g)+\mathrm{H}_{2} \mathrm{O}$ | -0.103 8 | -0.397 7 |
| $\mathrm{CO}_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{HCO}_{2} \mathrm{H}$ | -0.114 | -0.94 |
| $2 \mathrm{CO}_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{C}_{2} \mathrm{O}_{4}$ | -0.432 | -1.76 |
| Cerium |  |  |
| $\mathrm{Ce}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ce}^{3+}$ | $\begin{cases}1.72 & \\ 1.70 & 1 \mathrm{~F} \mathrm{HClO}_{4} \\ 1.44 & 1 \mathrm{~F} \mathrm{H}_{2} \mathrm{SO}_{4} \\ 1.61 & 1 \mathrm{~F} \mathrm{HNO}_{3} \\ 1.47 & 1 \mathrm{~F} \mathrm{HCl}\end{cases}$ | 1.54 |
|  | -2.336 | 0.280 |
| Cesium |  |  |
| $\mathrm{Cs}^{+}+\mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Cs}($ in Hg$)$ | -1.950 |  |
| $\mathrm{Cs}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cs}(s)$ | -3.026 | -1.172 |
| Chlorine |  |  |
| $\mathrm{HClO}_{2}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{HOCl}+\mathrm{H}_{2} \mathrm{O}$ | 1.674 | 0.55 |
| $\mathrm{HClO}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{Cl}_{2}(g)+\mathrm{H}_{2} \mathrm{O}$ | 1.630 | -0.27 |
| $\mathrm{ClO}_{3}^{-}+6 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{Cl}_{2}(g)+3 \mathrm{H}_{2} \mathrm{O}$ | 1.458 | -0.347 |
| $\mathrm{Cl}_{2}(a q)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Cl}^{-}$ | 1.396 | -0.72 |
| $\mathrm{Cl}_{2}(g)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Cl}^{-}$ | 1.3604 | -1.248 |
| $\mathrm{ClO}_{4}^{-}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{ClO}_{3}^{-}+\mathrm{H}_{2} \mathrm{O}$ | 1.226 | -0.416 |
| $\mathrm{ClO}_{3}^{-}+3 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{HClO}_{2}+\mathrm{H}_{2} \mathrm{O}$ | 1.157 | -0.180 |
| $\mathrm{ClO}_{3}^{-}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{ClO}_{2}+\mathrm{H}_{2} \mathrm{O}$ | 1.130 | 0.074 |
| $\mathrm{ClO}_{2}+\mathrm{e}^{-} \rightleftharpoons \mathrm{ClO}_{2}^{-}$ | 1.068 | -1.335 |
| Chromium |  |  |
| $\mathrm{Cr}_{2} \mathrm{O}_{7}^{2-}+14 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Cr}^{3+}+7 \mathrm{H}_{2} \mathrm{O}$ | 1.36 | -1.32 |
| $\mathrm{CrO}_{4}^{2-}+4 \mathrm{H}_{2} \mathrm{O}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cr}(\mathrm{OH})_{3}(s$, hydrated $)+5 \mathrm{OH}^{-}$ | -0.12 | -1.62 |
| $\mathrm{Cr}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cr}^{2+}$ | -0.42 | 1.4 |
| $\mathrm{Cr}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cr}(s)$ | -0.74 | 0.44 |
| $\mathrm{Cr}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cr}(s)$ | -0.89 | -0.04 |
| Cobalt |  |  |
| $\mathrm{Co}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Co}^{2+}$ | $\begin{cases}1.92 & \\ 1.817 & 8 \mathrm{~F} \mathrm{H}_{2} \mathrm{SO}_{4} \\ 1.850 & 4 \mathrm{~F} \mathrm{HNO}_{3}\end{cases}$ | 1.23 |
| $\mathrm{Co}\left(\mathrm{NH}_{3}\right)_{5}\left(\mathrm{H}_{2} \mathrm{O}\right)^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Co}\left(\mathrm{NH}_{3}\right)_{5}\left(\mathrm{H}_{2} \mathrm{O}\right)^{2+}$ | $0.37 \quad 1 \mathrm{~F} \mathrm{NH}_{4} \mathrm{NO}_{3}$ |  |
| $\mathrm{Co}\left(\mathrm{NH}_{3}\right)_{6}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Co}\left(\mathrm{NH}_{3}\right)_{6}^{2+}$ | 0.1 |  |
| $\mathrm{CoOH}^{+}+\mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Co}(s)+\mathrm{H}_{2} \mathrm{O}$ | 0.003 | -0.04 |
| $\mathrm{Co}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Co}(s)$ | -0.282 | 0.065 |
| $\mathrm{Co}(\mathrm{OH})_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Co}(s)+2 \mathrm{OH}^{-}$ | -0.746 | -1.02 |
| Copper |  |  |
| $\mathrm{Cu}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)$ | 0.518 | -0.754 |
| $\mathrm{Cu}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)$ | 0.339 | 0.011 |
| $\mathrm{Cu}^{2+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}^{+}$ | 0.161 | 0.776 |
| $\mathrm{CuCl}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+\mathrm{Cl}^{-}$ | 0.137 |  |
| $\mathrm{Cu}\left(\mathrm{IO}_{3}\right)_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+2 \mathrm{IO}_{3}^{-}$ | -0.079 |  |
| $\mathrm{Cu}(\text { ethylenediamine })_{2}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+2$ ethylenediamine | -0.119 |  |
| $\mathrm{CuI}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+\mathrm{I}^{-}$ | -0.185 |  |
| $\mathrm{Cu}(\mathrm{EDTA})^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+\mathrm{EDTA}^{4-}$ | -0.216 |  |
| $\mathrm{Cu}(\mathrm{OH})_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+2 \mathrm{OH}^{-}$ | -0.222 |  |
| $\mathrm{Cu}(\mathrm{CN})_{2}^{-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+2 \mathrm{CN}^{-}$ | -0.429 |  |
| $\mathrm{CuCN}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Cu}(s)+\mathrm{CN}^{-}$ | -0.639 |  |


| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| Dysprosium |  |  |
| $\mathrm{Dy}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Dy}(s)$ | -2.295 | 0.373 |
| Erbium |  |  |
| $\mathrm{Er}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Er}(s)$ | -2.331 | 0.388 |
| Europium |  |  |
| $\mathrm{Eu}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Eu}^{2+}$ | -0.35 | 1.53 |
| $\mathrm{Eu}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Eu}(s)$ | -1.991 | 0.338 |
| $\mathrm{Eu}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Eu}(s)$ | -2.812 | -0.26 |
| Fluorine |  |  |
| $\mathrm{F}_{2}(g)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{~F}^{-}$ | 2.890 | -1.870 |
| $\mathrm{F}_{2} \mathrm{O}(\mathrm{g})+2 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{~F}^{-}+\mathrm{H}_{2} \mathrm{O}$ | 2.168 | -1.208 |
| Gadolinium |  |  |
| $\mathrm{Gd}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Gd}(s)$ | -2.279 | 0.315 |
| Gallium |  |  |
| $\mathrm{Ga}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ga}(s)$ | -0.549 | 0.61 |
| $\operatorname{GaOOH}(s)+\mathrm{H}_{2} \mathrm{O}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ga}(s)+3 \mathrm{OH}^{-}$ | -1.320 | -1.08 |
| Germanium |  |  |
| $\mathrm{Ge}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ge}(s)$ | 0.1 |  |
| $\mathrm{H}_{4} \mathrm{GeO}_{4}+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ge}(s)+4 \mathrm{H}_{2} \mathrm{O}$ | -0.039 | -0.429 |
| Gold |  |  |
| $\mathrm{Au}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Au}(s)$ | 1.69 | -1.1 |
| $\mathrm{Au}^{3+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Au}^{+}$ | 1.41 |  |
| $\mathrm{AuCl}_{2}^{-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Au}(s)+2 \mathrm{Cl}^{-}$ | 1.154 |  |
| $\mathrm{AuCl}_{4}^{-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{AuCl}_{2}^{-}+2 \mathrm{Cl}^{-}$ | 0.926 |  |
| Hafnium |  |  |
| $\mathrm{Hf}^{4+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hf}(s)$ | -1.55 | 0.68 |
| $\mathrm{HfO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hf}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -1.591 | -0.355 |
| Holmium |  |  |
| $\mathrm{Ho}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ho}(\mathrm{s})$ | -2.33 | 0.371 |
| Hydrogen |  |  |
| $2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2}(\mathrm{~g})$ | 0.0000 | 0 |
| $\mathrm{H}_{2} \mathrm{O}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{H}_{2}(\mathrm{~g})+\mathrm{OH}^{-}$ | -0.828 0 | -0.8360 |
| Indium |  |  |
| $\mathrm{In}^{3+}+3 \mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{In}($ in Hg$)$ | -0.313 |  |
| $\mathrm{In}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{In}(s)$ | -0.338 | 0.42 |
| $\mathrm{In}^{3+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{In}^{+}$ | -0.444 |  |
| $\mathrm{In}(\mathrm{OH})_{3}(s)+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{In}(s)+3 \mathrm{OH}^{-}$ | -0.99 | -0.95 |
| Iodine |  |  |
| $\mathrm{IO}_{4}^{-}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{IO}_{3}^{-}+\mathrm{H}_{2} \mathrm{O}$ | 1.589 | -0.85 |
| $\mathrm{H}_{5} \mathrm{IO}_{6}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{HIO}_{3}+3 \mathrm{H}_{2} \mathrm{O}$ | 1.567 | -0.12 |
| $\mathrm{HOI}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{I}_{2}(s)+\mathrm{H}_{2} \mathrm{O}$ | 1.430 | -0.339 |
| $\mathrm{ICl}_{3}(s)+3 \mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{I}_{2}(s)+3 \mathrm{Cl}^{-}$ | 1.28 |  |
| $\mathrm{ICl}(s)+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{I}_{2}(s)+\mathrm{Cl}^{-}$ | 1.22 |  |
| $\mathrm{IO}_{3}^{-}+6 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{I}_{2}(s)+3 \mathrm{H}_{2} \mathrm{O}$ | 1.210 | -0.367 |
| $\mathrm{IO}_{3}^{-}+5 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{HOI}+2 \mathrm{H}_{2} \mathrm{O}$ | 1.154 | -0.374 |
| $\mathrm{I}_{2}(a q)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{I}^{-}$ | 0.620 | -0.234 |
| $\mathrm{I}_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{I}^{-}$ | 0.535 | -0.125 |
| $\mathrm{I}_{3}^{-}+2 \mathrm{e}^{-} \rightleftharpoons 3 \mathrm{I}^{-}$ | 0.535 | -0.186 |
| $\mathrm{IO}_{3}^{-}+3 \mathrm{H}_{2} \mathrm{O}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{I}^{-}+6 \mathrm{OH}^{-}$ | 0.269 | -1.163 |
| Iridium |  |  |
| $\mathrm{IrCl}_{6}^{2-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{IrCl}_{6}^{3-}$ | 1.0261 F HCl |  |
| $\mathrm{IrBr}_{6}^{2-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{IrBr}_{6}^{3-}$ | 0.9472 F NaBr |  |
| $\mathrm{IrCl}_{6}^{2-}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ir}(s)+6 \mathrm{Cl}^{-}$ | 0.835 |  |
| $\mathrm{IrO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ir}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | 0.73 | -0.36 |
| $\mathrm{IrI}_{6}^{2-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{IrI}_{6}^{3-}$ | 0.4851 F KI |  |
| Iron |  |  |
| $\mathrm{Fe}(\text { phenanthroline })_{3}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(\text { phenanthroline })_{3}^{2+}$ | 1.147 |  |
| $\mathrm{Fe}(\text { bipyridyl })_{3}{ }^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(\text { bipyridyl })_{3}{ }^{2+}$ | 1.120 |  |
| $\mathrm{FeOH}^{2+}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}^{2+}+\mathrm{H}_{2} \mathrm{O}$ | 0.900 | 0.096 |
| $\mathrm{FeO}_{4}^{2-}+3 \mathrm{H}_{2} \mathrm{O}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{FeOOH}(s)+5 \mathrm{OH}^{-}$ | 0.80 | -1.59 |
| $\mathrm{Fe}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}^{2+}$ | $\begin{cases}0.771 & \\ 0.732 & 1 \mathrm{~F} \mathrm{HCl} \\ 0.767 & 1 \mathrm{~F} \mathrm{HClO} \\ 0.746 & 1 \mathrm{~F} \mathrm{HNO}_{3} \\ 0.68 & 1 \mathrm{~F} \mathrm{H}_{2} \mathrm{SO}_{4}\end{cases}$ | 1.175 |


| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| $\mathrm{FeOOH}(s)+3 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}^{2+}+2 \mathrm{H}_{2} \mathrm{O}$ | 0.74 | -1.05 |
| Ferricinium ${ }^{+}+\mathrm{e}^{-} \rightleftharpoons$ ferrocene | 0.400 |  |
| $\mathrm{Fe}(\mathrm{CN})_{6}^{3-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(\mathrm{CN})_{6}^{4-}$ | 0.356 |  |
| $\mathrm{Fe}(\text { glutamate })^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(\text { glutamate })^{2+}$ | 0.240 |  |
| $\mathrm{FeOH}^{+}+\mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(s)+\mathrm{H}_{2} \mathrm{O}$ | -0.16 | 0.07 |
| $\mathrm{Fe}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(s)$ | -0.44 | 0.07 |
| $\mathrm{FeCO}_{3}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Fe}(s)+\mathrm{CO}_{3}^{2-}$ | -0.756 | -1.293 |
| Lanthanum |  |  |
| $\mathrm{La}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{La}(s)$ | -2.379 | 0.242 |
| $\mathrm{La}(\text { succinate })^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{La}(s)+$ succinate $^{2-}$ | -2.601 |  |
| Lead |  |  |
| $\mathrm{Pb}^{4+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pb}^{2+}$ | $1.69 \quad 1 \mathrm{~F} \mathrm{HNO}_{3}$ |  |
| $\mathrm{PbO}_{2}(s)+4 \mathrm{H}^{+}+\mathrm{SO}_{4}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{PbSO}_{4}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | 1.685 |  |
| $\mathrm{PbO}_{2}(s)+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pb}^{2+}+2 \mathrm{H}_{2} \mathrm{O}$ | 1.458 | -0.253 |
| $3 \mathrm{PbO}_{2}(s)+2 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pb}_{3} \mathrm{O}_{4}(s)+4 \mathrm{OH}^{-}$ | 0.269 | -1.136 |
| $\mathrm{Pb}_{3} \mathrm{O}_{4}(s)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons 3 \mathrm{PbO}(s$, red $)+2 \mathrm{OH}^{-}$ | 0.224 | -1.211 |
| $\mathrm{Pb}_{3} \mathrm{O}_{4}(s)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons 3 \mathrm{PbO}(s$, yellow $)+2 \mathrm{OH}^{-}$ | 0.207 | -1.177 |
| $\mathrm{Pb}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pb}(s)$ | -0.126 | -0.395 |
| $\mathrm{PbF}_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pb}(s)+2 \mathrm{~F}^{-}$ | -0.350 |  |
| $\mathrm{PbSO}_{4}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pb}(s)+\mathrm{SO}_{4}^{2-}$ | -0.355 |  |
| Lithium |  |  |
| $\mathrm{Li}^{+}+\mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Li}($ in Hg$)$ | -2.195 |  |
| $\mathrm{Li}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Li}(s)$ | -3.040 | -0.514 |
| Lutetium |  |  |
| $\mathrm{Lu}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Lu}(s)$ | -2.28 | 0.412 |
| Magnesium |  |  |
| $\mathrm{Mg}^{2+}+2 \mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Mg}($ in Hg$)$ | -1.980 |  |
| $\mathrm{Mg}(\mathrm{OH})^{+}+\mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mg}(s)+\mathrm{H}_{2} \mathrm{O}$ | -2.022 | 0.25 |
| $\mathrm{Mg}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mg}(s)$ | -2.360 | 0.199 |
| $\operatorname{Mg}\left(\mathrm{C}_{2} \mathrm{O}_{4}\right)(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mg}(s)+\mathrm{C}_{2} \mathrm{O}_{4}^{2-}$ | -2.493 |  |
| $\mathrm{Mg}(\mathrm{OH})_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mg}(s)+2 \mathrm{OH}^{-}$ | -2.690 | -0.946 |
| Manganese |  |  |
| $\mathrm{MnO}_{4}^{-}+4 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{MnO}_{2}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | 1.692 | -0.671 |
| $\mathrm{Mn}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}^{2+}$ | 1.56 | 1.8 |
| $\mathrm{MnO}_{4}^{-}+8 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}^{2+}+4 \mathrm{H}_{2} \mathrm{O}$ | 1.507 | -0.646 |
| $\mathrm{Mn}_{2} \mathrm{O}_{3}(s)+6 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Mn}^{2+}+3 \mathrm{H}_{2} \mathrm{O}$ | 1.485 | -0.926 |
| $\mathrm{MnO}_{2}(s)+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}^{2+}+2 \mathrm{H}_{2} \mathrm{O}$ | 1.230 | -0.609 |
| $\mathrm{Mn}(\text { EDTA })^{-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}(\text { EDTA })^{2-}$ | 0.825 | -1.10 |
| $\mathrm{MnO}_{4}^{-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{MnO}_{4}^{2-}$ | 0.56 | -2.05 |
| $3 \mathrm{Mn}_{2} \mathrm{O}_{3}(s)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Mn}_{3} \mathrm{O}_{4}(s)+2 \mathrm{OH}^{-}$ | 0.002 | -1.256 |
| $\mathrm{Mn}_{3} \mathrm{O}_{4}(s)+4 \mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons 3 \mathrm{Mn}(\mathrm{OH})_{2}(s)+2 \mathrm{OH}^{-}$ | -0.352 | -1.61 |
| $\mathrm{Mn}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}(s)$ | -1.182 | -1.129 |
| $\mathrm{Mn}(\mathrm{OH})_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mn}(s)+2 \mathrm{OH}^{-}$ | -1.565 | -1.10 |
| Mercury |  |  |
| $2 \mathrm{Hg}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hg}_{2}^{2+}$ | 0.908 | 0.095 |
| $\mathrm{Hg}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hg}(l)$ | 0.852 | -0.116 |
| $\mathrm{Hg}_{2}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Hg}(l)$ | 0.796 | -0.327 |
| $\mathrm{Hg}_{2} \mathrm{SO}_{4}(s)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Hg}(l)+\mathrm{SO}_{4}^{2-}$ | 0.614 |  |
| $\mathrm{Hg}_{2} \mathrm{Cl}_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Hg}(l)+2 \mathrm{Cl}^{-}$ | $\left\{\begin{array}{l}0.268 \\ 0.241 \text { (saturated calomel electrode) }\end{array}\right.$ |  |
| $\mathrm{Hg}(\mathrm{OH})_{3}^{-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hg}(l)+3 \mathrm{OH}^{-}$ | 0.231 |  |
| $\mathrm{Hg}(\mathrm{OH})_{2}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hg}(l)+2 \mathrm{OH}^{-}$ | 0.206 | -1.24 |
| $\mathrm{Hg}_{2} \mathrm{Br}_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Hg}(l)+2 \mathrm{Br}^{-}$ | 0.140 |  |
| $\mathrm{HgO}(s$, yellow $)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hg}(l)+2 \mathrm{OH}^{-}$ | 0.0983 | -1.125 |
| $\mathrm{HgO}(s$, red $)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Hg}(l)+2 \mathrm{OH}^{-}$ | 0.0977 | -1.120 6 |
| Molybdenum |  |  |
| $\mathrm{MoO}_{4}^{2-}+2 \mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{MoO}_{2}(s)+4 \mathrm{OH}^{-}$ | -0.818 | -1.69 |
| $\mathrm{MoO}_{4}^{2-}+4 \mathrm{H}_{2} \mathrm{O}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mo}(s)+8 \mathrm{OH}^{-}$ | -0.926 | -1.36 |
| $\mathrm{MoO}_{2}(s)+2 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Mo}(s)+4 \mathrm{OH}^{-}$ | -0.980 | -1.196 |
| Neodymium |  |  |
| $\mathrm{Nd}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Nd}(s)$ | -2.323 | 0.282 |
| Neptunium |  |  |
| $\mathrm{NpO}_{3}^{+}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{NpO}_{2}^{2+}+\mathrm{H}_{2} \mathrm{O}$ | 2.04 |  |
| $\mathrm{NpO}_{2}^{2+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{NpO}_{2}^{+}$ | 1.236 | 0.058 |


| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| $\mathrm{NpO}_{2}^{+}+4 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Np}^{4+}+2 \mathrm{H}_{2} \mathrm{O}$ | 0.567 | -3.30 |
| $\mathrm{Np}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Np}^{3+}$ | 0.157 | 1.53 |
| $\mathrm{Np}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Np}(s)$ | -1.768 | 0.18 |
| Nickel |  |  |
| $\mathrm{NiOOH}(s)+3 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ni}^{2+}+2 \mathrm{H}_{2} \mathrm{O}$ | 2.05 | -1.17 |
| $\mathrm{Ni}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ni}(s)$ | -0.236 | 0.146 |
| $\mathrm{Ni}(\mathrm{CN})_{4}^{2-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ni}(\mathrm{CN})_{3}^{2-}+\mathrm{CN}^{-}$ | -0.401 |  |
| $\mathrm{Ni}(\mathrm{OH})_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ni}(s)+2 \mathrm{OH}^{-}$ | -0.714 | -1.02 |
| Niobium |  |  |
| $\frac{1}{2} \mathrm{Nb}_{2} \mathrm{O}_{5}(s)+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{NbO}_{2}(s)+\frac{1}{2} \mathrm{H}_{2} \mathrm{O}$ | -0.248 | -0.460 |
| $\frac{1}{2} \mathrm{Nb}_{2} \mathrm{O}_{5}(s)+5 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \mathrm{Nb}(s)+\frac{5}{2} \mathrm{H}_{2} \mathrm{O}$ | -0.601 | -0.381 |
| $\mathrm{NbO}_{2}(s)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{NbO}(s)+\mathrm{H}_{2} \mathrm{O}$ | -0.646 | -0.347 |
| $\mathrm{NbO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Nb}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -0.690 | -0.361 |
| Nitrogen |  |  |
| $\mathrm{HN}_{3}+3 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{N}_{2}(g)+\mathrm{NH}_{4}^{+}$ | 2.079 | 0.147 |
| $\mathrm{N}_{2} \mathrm{O}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{N}_{2}(g)+\mathrm{H}_{2} \mathrm{O}$ | 1.769 | -0.461 |
| $2 \mathrm{NO}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{N}_{2} \mathrm{O}(g)+\mathrm{H}_{2} \mathrm{O}$ | 1.587 | -1.359 |
| $\mathrm{NO}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{NO}(\mathrm{g})$ | 1.46 |  |
| $2 \mathrm{NH}_{3} \mathrm{OH}^{+}+\mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{N}_{2} \mathrm{H}_{5}^{+}+2 \mathrm{H}_{2} \mathrm{O}$ | 1.40 | -0.60 |
| $\mathrm{NH}_{3} \mathrm{OH}^{+}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{NH}_{4}^{+}+\mathrm{H}_{2} \mathrm{O}$ | 1.33 | -0.44 |
| $\mathrm{N}_{2} \mathrm{H}_{5}^{+}+3 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{NH}_{4}^{+}$ | 1.250 | -0.28 |
| $\mathrm{HNO}_{2}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{NO}(\mathrm{g})+\mathrm{H}_{2} \mathrm{O}$ | 0.984 | 0.649 |
| $\mathrm{NO}_{3}^{-}+4 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{NO}(\mathrm{g})+2 \mathrm{H}_{2} \mathrm{O}$ | 0.955 | 0.028 |
| $\mathrm{NO}_{3}^{-}+3 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{HNO}_{2}+\mathrm{H}_{2} \mathrm{O}$ | 0.940 | -0.282 |
| $\mathrm{NO}_{3}^{-}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{~N}_{2} \mathrm{O}_{4}(g)+\mathrm{H}_{2} \mathrm{O}$ | 0.798 | 0.107 |
| $\mathrm{N}_{2}(g)+8 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{NH}_{4}^{+}$ | 0.274 | -0.616 |
| $\mathrm{N}_{2}(g)+5 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{N}_{2} \mathrm{H}_{5}^{+}$ | -0.214 | -0.78 |
| $\mathrm{N}_{2}(g)+2 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{NH}_{3} \mathrm{OH}^{+}$ | -1.83 | -0.96 |
| $\frac{3}{2} \mathrm{~N}_{2}(g)+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{HN}_{3}$ | -3.334 | -2.141 |
| Osmium |  |  |
| $\mathrm{OsO}_{4}(s)+8 \mathrm{H}^{+}+8 \mathrm{e}^{-} \rightleftharpoons \mathrm{Os}(s)+4 \mathrm{H}_{2} \mathrm{O}$ | 0.834 | -0.458 |
| $\mathrm{OsCl}_{6}^{2-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{OsCl}_{6}^{3-}$ | $0.85 \quad 1$ F HCl |  |
| Oxygen |  |  |
| $\mathrm{OH}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{O}$ | 2.56 | -1.0 |
| $\mathrm{O}(\mathrm{g})+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{O}$ | 2.4301 | -1.148 4 |
| $\mathrm{O}_{3}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{O}_{2}(g)+\mathrm{H}_{2} \mathrm{O}$ | 2.075 | -0.489 |
| $\mathrm{H}_{2} \mathrm{O}_{2}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{H}_{2} \mathrm{O}$ | 1.763 | -0.698 |
| $\mathrm{HO}_{2}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{O}_{2}$ | 1.44 | -0.7 |
| $\frac{1}{2} \mathrm{O}_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{O}$ | 1.2291 | -0.845 6 |
| $\mathrm{O}_{2}(g)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{O}_{2}$ | 0.695 | -0.993 |
| $\mathrm{O}_{2}(g)+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{HO}_{2}$ | -0.05 | -1.3 |
| Palladium |  |  |
| $\mathrm{Pd}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pd}(s)$ | 0.915 | 0.12 |
| $\mathrm{PdO}(s)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pd}(s)+\mathrm{H}_{2} \mathrm{O}$ | 0.79 | -0.33 |
| $\mathrm{PdCl}_{6}^{4-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pd}(s)+6 \mathrm{Cl}^{-}$ | 0.615 |  |
| $\mathrm{PdO}_{2}(s)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{PdO}(s)+2 \mathrm{OH}^{-}$ | 0.64 | -1.2 |
| Phosphorus |  |  |
| ${ }_{4}^{1} \mathrm{P}_{4}(s$, white $)+3 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{PH}_{3}(g)$ | -0.046 | -0.093 |
| ${ }_{4}^{1} \mathrm{P}_{4}(s$, red $)+3 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{PH}_{3}(g)$ | -0.088 | -0.030 |
| $\mathrm{H}_{3} \mathrm{PO}_{4}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{3} \mathrm{PO}_{3}+\mathrm{H}_{2} \mathrm{O}$ | -0.30 | -0.36 |
| $\mathrm{H}_{3} \mathrm{PO}_{4}+5 \mathrm{H}^{+}+5 \mathrm{e}^{-} \rightleftharpoons \frac{1}{4} \mathrm{P}_{4}(s$, white $)+4 \mathrm{H}_{2} \mathrm{O}$ | -0.402 | -0.340 |
| $\mathrm{H}_{3} \mathrm{PO}_{3}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{3} \mathrm{PO}_{2}+\mathrm{H}_{2} \mathrm{O}$ | -0.48 | -0.37 |
| $\mathrm{H}_{3} \mathrm{PO}_{2}+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{4} \mathrm{P}_{4}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -0.51 |  |
| Platinum |  |  |
| $\mathrm{Pt}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pt}(s)$ | 1.18 | -0.05 |
| $\mathrm{PtO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pt}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | 0.92 | -0.36 |
| $\mathrm{PtCl}_{4}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pt}(s)+4 \mathrm{Cl}^{-}$ | 0.755 |  |
| $\mathrm{PtCl}_{6}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{PtCl}_{4}^{2-}+2 \mathrm{Cl}^{-}$ | 0.68 |  |
| Plutonium |  |  |
| $\mathrm{PuO}_{2}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{PuO}_{2}(s)$ | 1.585 | 0.39 |
| $\mathrm{PuO}_{2}^{2+}+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pu}^{4+}+2 \mathrm{H}_{2} \mathrm{O}$ | 1.000 | -1.615 1 |
| $\mathrm{Pu}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Pu}^{3+}$ | 1.006 | 1.441 |
| $\mathrm{PuO}_{2}^{2+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{PuO}_{2}^{+}$ | 0.966 | 0.03 |
| $\mathrm{PuO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pu}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -1.369 | -0.38 |
| $\mathrm{Pu}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pu}(s)$ | -1.978 | 0.23 |


| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| Potassium |  |  |
| $\mathrm{K}^{+}+\mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{K}($ in Hg$)$ | -1.975 |  |
| $\mathrm{K}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{K}(s)$ | -2.936 | -1.074 |
| Praseodymium |  |  |
| $\mathrm{Pr}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Pr}^{3+}$ | 3.2 | 1.4 |
| $\mathrm{Pr}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pr}(s)$ | -2.353 | 0.291 |
| Promethium |  |  |
| $\mathrm{Pm}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Pm}(s)$ | -2.30 | 0.29 |
| Radium |  |  |
| $\mathrm{Ra}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ra}(s)$ | -2.80 | -0.44 |
| Rhenium |  |  |
| $\mathrm{ReO}_{4}^{-}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{ReO}_{3}(s)+\mathrm{H}_{2} \mathrm{O}$ | 0.72 | -1.17 |
| $\mathrm{ReO}_{4}^{-}+4 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{ReO}_{2}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | 0.510 | -0.70 |
| Rhodium |  |  |
| $\mathrm{Rh}^{6+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Rh}^{3+}$ | $1.48 \quad 1 \mathrm{~F} \mathrm{HClO}_{4}$ |  |
| $\mathrm{Rh}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Rh}^{3+}$ | $1.443 \mathrm{~F} \mathrm{H}_{2} \mathrm{SO}_{4}$ |  |
| $\mathrm{RhCl}_{6}^{2-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{RHCl}_{6}^{3-}$ | 1.2 |  |
| $\mathrm{Rh}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Rh}(s)$ | 0.76 | 0.4 |
| $2 \mathrm{Rh}^{3+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Rh}_{2}^{4+}$ | 0.7 |  |
| $\mathrm{RhCl}_{6}^{3-}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Rh}(s)+6 \mathrm{Cl}^{-}$ | 0.44 |  |
| Rubidium |  |  |
| $\mathrm{Rb}^{+}+\mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Rb}$ (in Hg ) | -1.970 |  |
| $\mathrm{Rb}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Rb}(s)$ | -2.943 | -1.140 |
| Ruthenium |  |  |
| $\mathrm{RuO}_{4}^{-}+6 \mathrm{H}^{+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}(\mathrm{OH})_{2}^{2+}+2 \mathrm{H}_{2} \mathrm{O}$ | 1.53 |  |
| $\mathrm{Ru}(\text { dipyridyl })_{3}{ }^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}(\text { dipyridyl })_{3}{ }^{2+}$ | 1.29 |  |
| $\mathrm{RuO}_{4}(s)+8 \mathrm{H}^{+}+8 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}(s)+4 \mathrm{H}_{2} \mathrm{O}$ | 1.032 | -0.467 |
| $\mathrm{Ru}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}(s)$ | 0.8 |  |
| $\mathrm{Ru}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}(s)$ | 0.60 |  |
| $\mathrm{Ru}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}^{2+}$ | 0.24 |  |
| $\mathrm{Ru}\left(\mathrm{NH}_{3}\right)_{6}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ru}\left(\mathrm{NH}_{3}\right)_{6}^{2+}$ | 0.214 |  |
| Samarium |  |  |
| $\mathrm{Sm}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sm}(s)$ | -2.304 | 0.279 |
| $\mathrm{Sm}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sm}(s)$ | -2.68 | -0.28 |
| Scandium |  |  |
| $\mathrm{Sc}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sc}(s)$ | -2.09 | 0.41 |
| Selenium |  |  |
| $\mathrm{SeO}_{4}^{2-}+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{SeO}_{3}+\mathrm{H}_{2} \mathrm{O}$ | 1.150 | 0.483 |
| $\mathrm{H}_{2} \mathrm{SeO}_{3}+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Se}(s)+3 \mathrm{H}_{2} \mathrm{O}$ | 0.739 | -0.562 |
| $\mathrm{Se}(s)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{Se}(g)$ | -0.082 | 0.238 |
| $\mathrm{Se}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Se}^{2-}$ | -0.67 | -1.2 |
| Silicon |  |  |
| $\mathrm{Si}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{SiH}_{4}(g)$ | -0.147 | -0.196 |
| $\mathrm{SiO}_{2}(s$, quartz $)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Si}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -0.990 | -0.374 |
| $\mathrm{SiF}_{6}^{2-}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Si}(s)+6 \mathrm{~F}^{-}$ | -1.24 |  |
| Silver |  |  |
| $\mathrm{Ag}^{2+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}^{+}$ | $\left\{\begin{array}{cc}2.000 & 4 \mathrm{~F} \mathrm{HClO}_{4} \\ 1.989 & \\ 1.929 & 4 \mathrm{~F} \mathrm{HNO}_{3}\end{array}\right.$ | 0.99 |
| $\mathrm{Ag}^{3+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}^{+}$ | 1.9 |  |
| $\mathrm{AgO}(s)+\mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \frac{1}{2} \mathrm{Ag}_{2} \mathrm{O}(s)+\frac{1}{2} \mathrm{H}_{2} \mathrm{O}$ | 1.40 |  |
| $\mathrm{Ag}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}(s)$ | 0.7993 | -0.989 |
| $\mathrm{Ag}_{2} \mathrm{C}_{2} \mathrm{O}_{4}(s)+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Ag}(s)+\mathrm{C}_{2} \mathrm{O}_{4}^{2-}$ | 0.465 |  |
| $\mathrm{AgN}_{3}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}(s)+\mathrm{N}_{3}^{-}$ | 0.293 |  |
| $\mathrm{AgCl}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}(s)+\mathrm{Cl}^{-}$ | $\left\{\begin{array}{l}0.222 \\ 0.197\end{array}\right.$ saturated KCl |  |
| $\operatorname{AgBr}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}(s)+\mathrm{Br}^{-}$ | 0.071 |  |
| $\mathrm{Ag}\left(\mathrm{S}_{2} \mathrm{O}_{3}\right)_{2}^{3-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ag}(s)+2 \mathrm{~S}_{2} \mathrm{O}_{3}^{2-}$ | 0.017 |  |
| $\operatorname{AgI}(s)+\mathrm{e}^{-} \rightleftharpoons \operatorname{Ag}(s)+\mathrm{I}^{-}$ | -0.152 |  |
| $\mathrm{Ag}_{2} \mathrm{~S}(s)+\mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Ag}(s)+\mathrm{SH}^{-}$ | -0.272 |  |
| Sodium |  |  |
| $\mathrm{Na}^{+}+\mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Na}($ in Hg$)$ | -1.959 |  |
| $\mathrm{Na}^{+}+\frac{1}{2} \mathrm{H}_{2}(g)+\mathrm{e}^{-} \rightleftharpoons \mathrm{NaH}(s)$ | -2.367 | -1.550 |
| $\mathrm{Na}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Na}(s)$ | -2.714 3 | -0.757 |


| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| Strontium |  |  |
| $\mathrm{Sr}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sr}(s)$ | -2.889 | -0.237 |
| Sulfur |  |  |
| $\mathrm{S}_{2} \mathrm{O}_{8}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{SO}_{4}^{2-}$ | 2.01 |  |
| $\mathrm{S}_{2} \mathrm{O}_{6}^{2-}+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{H}_{2} \mathrm{SO}_{3}$ | 0.57 |  |
| $4 \mathrm{SO}_{2}+4 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{4} \mathrm{O}_{6}^{2-}+2 \mathrm{H}_{2} \mathrm{O}$ | 0.539 | -1.11 |
| $\mathrm{SO}_{2}+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | 0.450 | -0.652 |
| $2 \mathrm{H}_{2} \mathrm{SO}_{3}+2 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{2} \mathrm{O}_{3}^{2-}+3 \mathrm{H}_{2} \mathrm{O}$ | 0.40 |  |
| $\mathrm{S}(s)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{~S}(g)$ | 0.174 | 0.224 |
| $\mathrm{S}(s)+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{H}_{2} \mathrm{~S}(a q)$ | 0.144 | -0.21 |
| $\mathrm{S}_{4} \mathrm{O}_{6}^{2-}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{HS}_{2} \mathrm{O}_{3}^{-}$ | 0.10 | -0.23 |
| $5 \mathrm{~S}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{5}^{2-}$ | -0.340 |  |
| $\mathrm{S}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}^{2-}$ | -0.476 | -0.925 |
| $2 \mathrm{~S}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{2}^{2-}$ | -0.50 | -1.16 |
| $2 \mathrm{SO}_{3}^{2-}+3 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{2} \mathrm{O}_{3}^{2-}+6 \mathrm{OH}^{-}$ | -0.566 | -1.06 |
| $\mathrm{SO}_{3}^{2-}+3 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}(s)+6 \mathrm{OH}^{-}$ | -0.659 | -1.23 |
| $\mathrm{SO}_{4}^{2-}+4 \mathrm{H}_{2} \mathrm{O}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}(s)+8 \mathrm{OH}^{-}$ | -0.751 | -1.288 |
| $\mathrm{SO}_{4}^{2-}+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{SO}_{3}^{2-}+2 \mathrm{OH}^{-}$ | -0.936 | -1.41 |
| $2 \mathrm{SO}_{3}^{2-}+2 \mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{2} \mathrm{O}_{4}^{2-}+4 \mathrm{OH}^{-}$ | -1.130 | -0.85 |
| $2 \mathrm{SO}_{4}^{2-}+2 \mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{S}_{2} \mathrm{O}_{6}^{2-}+4 \mathrm{OH}^{-}$ | -1.71 | -1.00 |
| Tantalum |  |  |
| $\mathrm{Ta}_{2} \mathrm{O}_{5}(s)+10 \mathrm{H}^{+}+10 \mathrm{e}^{-} \rightleftharpoons 2 \mathrm{Ta}(s)+5 \mathrm{H}_{2} \mathrm{O}$ | -0.752 | -0.377 |
| Technetium |  |  |
| $\mathrm{TcO}_{4}^{-}+2 \mathrm{H}_{2} \mathrm{O}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{TcO}_{2}(s)+4 \mathrm{OH}^{-}$ | -0.366 | -1.82 |
| $\mathrm{TcO}_{4}^{-}+4 \mathrm{H}_{2} \mathrm{O}+7 \mathrm{e}^{-} \rightleftharpoons \mathrm{Tc}(s)+8 \mathrm{OH}^{-}$ | -0.474 | -1.46 |
| Tellurium |  |  |
| $\mathrm{TeO}_{3}^{2-}+3 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Te}(s)+6 \mathrm{OH}^{-}$ | -0.47 | -1.39 |
| $2 \mathrm{Te}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Te}_{2}^{2-}$ | -0.84 |  |
| $\mathrm{Te}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Te}^{2-}$ | -0.90 | -1.0 |
| Terbium |  |  |
| $\mathrm{Tb}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Tb}^{3+}$ | 3.1 | 1.5 |
| $\mathrm{Tb}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Tb}(s)$ | -2.28 | 0.350 |
| Thallium |  |  |
| $\begin{cases}1.280 & \\ 0.77 & 1 \mathrm{~F} \mathrm{HCl} \\ 1.22 & 1 \mathrm{~F} \mathrm{H}_{2} \mathrm{SO}_{4} \\ 1.23 & 1 \mathrm{~F} \mathrm{HNO}_{3} \\ 1.26 & 1 \mathrm{~F} \mathrm{HClO}_{4}\end{cases}$ <br> 0.97 <br> $\mathrm{Tl}^{3+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Tl}^{+}$ <br> 1.26 -0.294 <br> $\mathrm{Tl}^{+}+\mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Tl}$ (in Hg ) |  |  |
|  |  |  |
| $\mathrm{Tl}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Tl}(s)$ | -0.336 | -1.312 |
| $\operatorname{TlCl}(s)+\mathrm{e}^{-} \rightleftharpoons \mathrm{Tl}(s)+\mathrm{Cl}^{-}$ | -0.557 |  |
| Thorium |  |  |
| $\mathrm{Th}^{4+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Th}(s)$ | -1.826 | 0.557 |
| Thulium |  |  |
| $\mathrm{Tm}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Tm}(s)$ | -2.319 | 0.394 |
| Tin |  |  |
| $\mathrm{Sn}(\mathrm{OH})_{3}^{+}+3 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sn}^{2+}+3 \mathrm{H}_{2} \mathrm{O}$ | 0.142 |  |
| $\mathrm{Sn}^{4+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sn}^{2+}$ | 0.139 |  |
| $\mathrm{SnO}_{2}(s)+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sn}^{2+}+2 \mathrm{H}_{2} \mathrm{O}$ | -0.094 | -0.31 |
| $\mathrm{Sn}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sn}(s)$ | -0.141 | -0.32 |
| $\mathrm{SnF}_{6}^{2-}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sn}(s)+6 \mathrm{~F}^{-}$ | -0.25 |  |
| $\mathrm{Sn}(\mathrm{OH})_{6}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Sn}(\mathrm{OH})_{3}^{-}+3 \mathrm{OH}^{-}$ | -0.93 |  |
| $\mathrm{Sn}(s)+4 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{SnH}_{4}(g)+4 \mathrm{OH}^{-}$ | -1.316 | -1.057 |
| $\mathrm{SnO}_{2}(s)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{SnO}(s)+2 \mathrm{OH}^{-}$ | -0.961 | -1.129 |
| Titanium |  |  |
| $\mathrm{TiO}^{2+}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ti}^{3+}+\mathrm{H}_{2} \mathrm{O}$ | 0.1 | -0.6 |
| $\mathrm{Ti}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{Ti}^{2+}$ | -0.9 | 1.5 |
| $\mathrm{TiO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ti}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -1.076 | 0.365 |
| $\mathrm{TiF}_{6}^{2-}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ti}(s)+6 \mathrm{~F}^{-}$ | -1.191 |  |
| $\mathrm{Ti}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Ti}(s)$ | -1.60 | -0.16 |
| Tungsten |  |  |
| $\mathrm{W}(\mathrm{CN})_{8}^{3-}+\mathrm{e}^{-} \rightleftharpoons \mathrm{W}(\mathrm{CN})_{8}^{4-}$ | 0.457 |  |
| $\mathrm{W}^{6+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{W}^{5+}$ | 0.2612 F HCl |  |
| $\mathrm{WO}_{3}(s)+6 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{W}(s)+3 \mathrm{H}_{2} \mathrm{O}$ | -0.091 | -0.389 |


| Reaction | $E^{\circ}$ (volts) | $d E^{\circ} / d T(\mathrm{mV} / \mathrm{K})$ |
| :--- | :--- | :--- |
| $\mathrm{W}^{5+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{W}^{4+}$ | $-0.3 \quad 12$ F HCl |  |
| $\mathrm{WO}_{2}(s)+2 \mathrm{H}_{2} \mathrm{O}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{W}(s)+4 \mathrm{OH}^{-}$ | -0.982 | -1.197 |
| $\mathrm{WO}_{4}^{2-}+4 \mathrm{H}_{2} \mathrm{O}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{W}(s)+8 \mathrm{OH}^{-}$ | -1.060 | -1.36 |
| Uranium |  |  |
| $\mathrm{UO}_{2}^{+}+4 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{U}^{4+}+2 \mathrm{H}_{2} \mathrm{O}$ | 0.39 | -3.4 |
| $\mathrm{UO}_{2}^{2+}+4 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{U}^{4+}+2 \mathrm{H}_{2} \mathrm{O}$ | 0.273 | -1.582 |
| $\mathrm{UO}_{2}^{2+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{UO}_{2}^{+}$ | 0.16 | 0.2 |
| $\mathrm{U}^{4+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{U}^{3+}$ | -0.577 | 1.61 |
| $\mathrm{U}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{U}(s)$ | -1.642 | 0.16 |
| Vanadium |  |  |
| $\mathrm{VO}_{2}^{+}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{VO}^{2+}+\mathrm{H}_{2} \mathrm{O}$ | 1.001 | -0.901 |
| $\mathrm{VO}^{2+}+2 \mathrm{H}^{+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{V}^{3+}+\mathrm{H}_{2} \mathrm{O}$ | 0.337 | -1.6 |
| $\mathrm{V}^{3+}+\mathrm{e}^{-} \rightleftharpoons \mathrm{V}^{2+}$ | -0.255 | 1.5 |
| $\mathrm{V}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{V}(s)$ | -1.125 | -0.11 |
| Xenon |  |  |
| $\mathrm{H}_{4} \mathrm{XeO}_{6}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{XeO}_{3}+3 \mathrm{H}_{2} \mathrm{O}$ | 2.38 | 0.0 |
| $\mathrm{XeF}_{2}+2 \mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Xe}(g)+2 \mathrm{HF}$ | 2.2 |  |
| $\mathrm{XeO}_{3}+6 \mathrm{H}^{+}+6 \mathrm{e}^{-} \rightleftharpoons \mathrm{Xe}(g)+3 \mathrm{H}_{2} \mathrm{O}$ | 2.1 | -0.34 |
| Ytterbium |  |  |
| $\mathrm{Yb}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Yb}(s)$ | -2.19 | 0.363 |
| $\mathrm{Yb}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Yb}(s)$ | -2.76 | -0.16 |
| Yttrium |  |  |
| $\mathrm{Y}^{3+}+3 \mathrm{e}^{-} \rightleftharpoons \mathrm{Y}(s)$ | -2.38 | 0.034 |
| Zinc |  |  |
| $\mathrm{ZnOH}^{+}+\mathrm{H}^{+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+\mathrm{H}_{2} \mathrm{O}$ | -0.497 | 0.03 |
| $\mathrm{Zn}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)$ | -0.762 | 0.119 |
| $\mathrm{Zn}^{2+}+2 \mathrm{e}^{-}+\mathrm{Hg} \rightleftharpoons \mathrm{Zn}$ (in Hg ) | -0.801 |  |
| $\mathrm{Zn}\left(\mathrm{NH}_{3}\right)_{4}^{2+}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+4 \mathrm{NH}_{3}$ | -1.04 |  |
| $\mathrm{ZnCO}_{3}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+\mathrm{CO}_{3}^{2-}$ | -1.06 |  |
| $\mathrm{Zn}(\mathrm{OH})_{3}^{-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+3 \mathrm{OH}^{-}$ | -1.183 |  |
| $\mathrm{Zn}(\mathrm{OH})_{4}^{2-}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+4 \mathrm{OH}^{-}$ | -1.199 |  |
| $\mathrm{Zn}(\mathrm{OH})_{2}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+2 \mathrm{OH}^{-}$ | -1.249 | -0.999 |
| $\mathrm{ZnO}(s)+\mathrm{H}_{2} \mathrm{O}+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+2 \mathrm{OH}^{-}$ | -1.260 | -1.160 |
| $\mathrm{ZnS}(s)+2 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zn}(s)+\mathrm{S}^{2-}$ | -1.405 |  |
| Zirconium |  |  |
| $\mathrm{Zr}^{4+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zr}(s)$ | -1.45 | 0.67 |
| $\mathrm{ZrO}_{2}(s)+4 \mathrm{H}^{+}+4 \mathrm{e}^{-} \rightleftharpoons \mathrm{Zr}(s)+2 \mathrm{H}_{2} \mathrm{O}$ | -1.473 | -0.344 |


| Reacting ions | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{1}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{2}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{3}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{4}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{5}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{6}}$ | Temperature $\left({ }^{\circ} \mathrm{C}\right)$ | Ionic strength ( $\mu$, M) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Acetate, $\mathrm{CH}_{3} \mathrm{CO}_{2}^{-}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ | 0.73 | 0.64 |  |  |  |  | 25 | 0 |
| $\mathrm{Ca}^{2+}$ | 1.24 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Cd}^{2+}$ | 1.93 | 3.15 |  |  |  |  | 25 | 0 |
| $\mathrm{Cu}^{2+}$ | 2.23 | 3.63 |  |  |  |  | 25 | 0 |
| $\mathrm{Fe}^{2+}$ | 1.82 |  |  |  |  |  | 25 | 0.5 |
| $\mathrm{Fe}^{3+}$ | 3.38 | 7.1 | 9.7 |  |  |  | 20 | 0.1 |
| $\mathrm{Mg}^{2+}$ | 1.25 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Mn}^{2+}$ | 1.40 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Na}^{+}$ | -0.18 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Ni}^{2+}$ | 1.43 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Zn}^{2+}$ | 1.28 | 2.09 |  |  |  |  | 20 | 0.1 |
| Ammonia, $\mathrm{NH}_{3}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ | 3.31 | 7.23 |  |  |  |  | 25 | 0 |
| $\mathrm{Cd}^{2+}$ | 2.51 | 4.47 | 5.77 | 6.56 |  |  | 30 | 0 |
| $\mathrm{Co}^{2+}$ | 1.99 | 3.50 | 4.43 | 5.07 | 5.13 | 4.39 | 30 | 0 |
| $\mathrm{Cu}^{2+}$ | 3.99 | 7.33 | 10.06 | 12.03 |  |  | 30 | 0 |
| $\mathrm{Hg}^{2+}$ | 8.8 | 17.5 | 18.50 | 19.28 |  |  | 22 | 2 |
| $\mathrm{Ni}^{2+}$ | 2.67 | 4.79 | 6.40 | 7.47 | 8.10 | 8.01 | 30 | 0 |
| $\mathrm{Zn}^{2+}$ | 2.18 | 4.43 | 6.74 | 8.70 |  |  | 30 | 0 |
| Cyanide, $\mathrm{CN}^{-}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ |  | 20 | 21 |  |  |  | 20 | 0 |
| $\mathrm{Cd}^{2+}$ | 5.18 | 9.60 | 13.92 | 17.11 |  |  | 25 | ? |
| $\mathrm{Cu}^{+}$ |  | 24 | 28.6 | 30.3 |  |  | 25 | 0 |
| $\mathrm{Ni}^{2+}$ |  |  |  | 30 |  |  | 25 | 0 |
| $\mathrm{Tl}^{3+}$ | 13.21 | 26.50 | 35.17 | 42.61 |  |  | 25 | 4 |
| $\mathrm{Zn}^{2+}$ |  | 11.07 | 16.05 | 19.62 |  |  | 25 | 0 |
| Ethylenediamine (1,2-diaminoethane), $\mathrm{H}_{2} \mathrm{NCH}_{2} \mathrm{CH}_{2} \mathrm{NH}_{2}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ | 4.70 | 7.70 | 9.7 |  |  |  | 20 | 0.1 |
| $\mathrm{Cd}^{2+}$ | 5.69 | 10.36 | 12.80 |  |  |  | 25 | 0.5 |
| $\mathrm{Cu}^{2+}$ | 10.66 | 19.99 |  |  |  |  | 20 | 0 |
| $\mathrm{Hg}^{2+}$ | 14.3 | 23.3 | 23.2 |  |  |  | 25 | 0.1 |
| $\mathrm{Ni}^{2+}$ | 7.52 | 13.84 | 18.33 |  |  |  | 20 | 0 |
| $\mathrm{Zn}^{2+}$ | 5.77 | 10.83 | 14.11 |  |  |  | 20 | 0 |
| Hydroxide, $\mathrm{OH}^{-}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ | 2.0 | 3.99 |  |  |  |  | 25 | 0 |
| Al ${ }^{3+}$ | 9.00 | 17.9 | 25.2 | 33.3 |  |  | 25 | 0 |
| $\log \beta_{22}=20.3 \quad \log \beta_{43}=42.1$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ba}^{2+}$ | 0.64 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Bi}^{3+}$ | 12.9 | 23.5 | 33.0 | 34.8 |  |  | 25 | 0 |
|  |  | $\log \beta_{126}=165.3(\mu=1)$ |  |  |  |  |  |  |
| $\mathrm{Be}^{2+}$ |  |  | 18.8 | 18.6 |  |  | 25 | 0 |
| $\log \beta_{33}=32.54(\mu=0.1)$ <br> $\log \beta_{65}=66.24(\mu=3)$ <br> $\log \beta_{86}=85(\mu=0)$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ca}^{2+}$ | 1.30 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Cd}^{2+}$ | 3.9 | 7.7 |  |  |  |  | 25 | 0 |
|  |  |  | 10.3 ( $\mu=3$ ) | 12.0 ( $\mu=3$ ) |  |  |  |  |
| $\log \beta_{12}=4.6 \quad \log \beta_{44}=23.2$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ce}^{3+}$ | 4.9 |  |  |  |  |  | 25 | 3 |
| $\log \beta_{22}=12.4 \quad \log \beta_{53}=35.1$ |  |  |  |  |  |  |  |  |
| $\mathrm{Co}^{2+}$ | 4.3 | 9.2 | 10.5 | 9.7 |  |  | 25 | 0 |
|  |  | $\log \beta_{12}=3 \quad \log \beta_{44}=25.5$ |  |  |  |  |  |  |
| $\mathrm{Co}^{3+}$ | 13.52 |  |  |  |  |  | 25 | 3 |

[^9]| Reacting ions | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{1}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{2}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{3}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{4}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{5}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{6}}$ | Temperature $\left({ }^{\circ} \mathrm{C}\right)$ | Ionic strength ( $\mu, \mathrm{M}$ ) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\mathrm{Cr}^{2+}$ | 8.5 |  |  |  |  |  | 25 | 1 |
| $\mathrm{Cr}^{3+}$ | 10.34 | 17.3 |  |  |  |  | 25 | 0 |
|  | ( $\mu=0.1$ ) |  |  |  |  |  |  |  |
| $\log \beta_{22}=24.0(\mu=1) \quad \log \beta_{43}=37.0(\mu=1) \quad \log \beta_{44}=50.7(\mu=2)$ |  |  |  |  |  |  |  |  |
| $\mathrm{Cu}^{2+}$ | 6.5 | 11.8 | 14.5 | 15.6 |  |  | 25 | 0 |
|  | $(\mu=1) \quad(\mu=1)$ |  |  |  |  |  |  |  |
|  | $\log \beta_{12}=8.2(\mu=3) \quad \log \beta_{22}=17.4 \quad \log \beta_{43}=35.2$ |  |  |  |  |  |  |  |  |
| $\mathrm{Fe}^{2+}$ | 4.6 | 7.5 | 13 | 10 |  |  | 25 | 0 |
| $\mathrm{Fe}^{3+}$ | 11.81 | 23.4 |  | 34.4 |  |  | 25 | 0 |
| $\log \beta_{22}=25.14 \quad \log \beta_{43}=49.7$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ga}^{3+}$ | 11.4 | 22.1 | 31.7 | 39.4 |  |  | 25 | 0 |
| $\mathrm{Gd}^{3+}$ | 4.9 |  |  |  |  |  | 25 | 3 |
| $\log \beta_{22}=14.14$ |  |  |  |  |  |  |  |  |
| $\mathrm{Hf}^{4+}$ | 13.7 |  |  |  | 52.8 |  | 25 | 0 |
| $\mathrm{Hg}_{2}^{2+}$ | 8.7 |  |  |  |  |  |  | 0.5 |
| $\log \beta_{12}=11.5(\mu=3) \quad \log \beta_{45}=48.24(\mu=3)$ |  |  |  |  |  |  |  |  |
| $\mathrm{Hg}^{2+}$ | 10.60 | 21.8 | 20.9 |  |  |  | 25 | 0 |
| $\log \beta_{12}=10.7 \quad \log \beta_{33}=35.6$ |  |  |  |  |  |  |  |  |
| $\mathrm{In}^{3+}$ | 10.1 | 20.2 | 29.5 | 33.8 |  |  | 25 | 0 |
| $\log \beta_{22}=23.2(\mu=3) \quad \log \beta_{44}=47.8(\mu=0.1) \quad \log \beta_{64}=43.1(\mu=0.1)$ |  |  |  |  |  |  |  |  |
| $\mathrm{La}^{3+}$ |  |  |  |  |  |  | 25 | 0 |
|  |  |  |  |  |  |  |  |  |
| $\mathrm{Li}^{+}$ | 0.36 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Mg}^{2+}$ | 2.6 | -0.3 |  |  |  |  | 25 | 0 |
| ( $\mu=3$ ) |  |  |  |  |  |  |  |  |
| $\log \beta_{44}=18.1(\mu=3)$ |  |  |  |  |  |  |  |  |
| $\mathrm{Mn}^{2+}$ | 3.4 |  |  | 7.7 |  |  | 25 | 0 |
| $\log \beta_{12}=6.8 \quad \log \beta_{32}=18.1$ |  |  |  |  |  |  |  |  |
| $\mathrm{Na}^{+}$ | 0.1 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Ni}^{2+}$ | 4.1 | 9 | 12 |  |  |  | 25 | 0 |
| $\log \beta_{12}=4.7(\mu=1) \quad \log \beta_{44}=28.3$ |  |  |  |  |  |  |  |  |
| $\mathrm{Pb}^{2+}$ | 6.4 | 10.9 | 13.9 |  |  |  | 25 | 0 |
| $\log \beta_{12}=7.6 \quad \log \beta_{43}=32.1 \quad \log \beta_{44}=36.0 \quad \log \beta_{86}=68.4$ |  |  |  |  |  |  |  |  |
| $\mathrm{Pd}^{2+}$ | 13.0 | 25.8 |  |  |  |  | 25 | 0 |
| $\mathrm{Rh}^{3+}$ | 10.67 |  |  |  |  |  | 25 | 2.5 |
| $\mathrm{Sc}^{3+}$ |  |  | 9.7 18.3 | 30 |  |  | 25 | 0 |
| $\log \beta_{22}=22.0 \quad \log \beta_{53}=53.8$ |  |  |  |  |  |  |  |  |
| $\mathrm{Sn}^{2+}$ | 10.6 | 20.9 | 25.4 |  |  |  | 25 | 0 |
| $\log \beta_{22}=23.2 \quad \log \beta_{43}=49.1$ |  |  |  |  |  |  |  |  |
| $\mathrm{Sr}^{2+}$ | 0.82 |  |  |  |  |  | 25 | 0 |
| $\mathrm{Th}^{4+}$ | 10.8 | 21.1 |  | 41.1 |  |  | 25 | 0 |
| ( $\mu=3$ ) |  |  |  |  |  |  |  |  |
| $\log \beta_{22}=23.6(\mu=3) \quad \log \beta_{32}=33.8(\mu=3) \quad \log \beta_{53}=53.7(\mu=3)$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ti}^{3+}$ |  |  |  |  |  |  | 25 | 0 |
|  |  |  |  |  |  |  |  |  |
| $\mathrm{Tl}^{+}$ | 0.79 | -0.8 |  |  |  |  | 25 | 0 |
|  |  | ( $\mu=3$ ) |  |  |  |  |  |  |
| $\mathrm{Tl}^{3+}$ | 13.4 | 26.6 | 38.7 | 41.0 |  |  | 25 | 0 |
| $\mathrm{U}^{4+}$ | 13.4 |  |  |  |  |  | 25 | 0 |
| $\mathrm{VO}^{2+}$ | 8.3 |  |  |  |  |  | 25 | 0 |
| $\log \beta_{22}=21.3$ |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |
| $\log \beta_{22}=13.8 \quad \log \beta_{53}=38.4$ |  |  |  |  |  |  |  |  |
| $\mathrm{Zn}^{2+}$ | 5.0 | 10.2 | 13.9 | 15.5 |  |  | 25 | 0 |
| $\log \beta_{12}=5.5(\mu=3) \quad \log \beta_{44}=27.9(\mu=3)$ |  |  |  |  |  |  |  |  |
| $\log \beta_{43}=55.4 \quad \log \beta_{84}=106.0$ |  |  |  |  |  |  |  |  |
| Nitrilotriacetate, $\mathrm{N}\left(\mathrm{CH}_{2} \mathrm{CO}_{2}^{-}\right)_{3}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ | 5.16 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Al}^{3+}$ | 9.5 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Ba}^{2+}$ | 4.83 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Ca}^{2+}$ | 6.46 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Cd}^{2+}$ | 10.0 | 14.6 |  |  |  |  | 20 | 0.1 |


| Reacting ions | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{1}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{2}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{3}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{4}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{\mathbf{5}}$ | $\boldsymbol{\operatorname { l o g }} \boldsymbol{\beta}_{6}$ | Temperature $\left({ }^{\circ} \mathrm{C}\right)$ | Ionic strength ( $\mu, \mathrm{M}$ ) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| $\mathrm{Co}^{2+}$ | 10.0 | 13.9 |  |  |  |  | 20 | 0.1 |
| $\mathrm{Cu}^{2+}$ | 11.5 | 14.8 |  |  |  |  | 20 | 0.1 |
| $\mathrm{Fe}^{3+}$ | 15.91 | 24.61 |  |  |  |  | 20 | 0.1 |
| $\mathrm{Ga}^{3+}$ | 13.6 | 21.8 |  |  |  |  | 20 | 0.1 |
| $\mathrm{In}^{3+}$ | 16.9 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Mg}^{2+}$ | 5.46 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Mn}^{2+}$ | 7.4 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Ni}^{2+}$ | 11.54 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Pb}^{2+}$ | 11.47 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Tl}^{+}$ | 4.75 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Zn}^{2+}$ | 10.44 |  |  |  |  |  | 20 | 0.1 |
| Oxalate, ${ }^{-} \mathrm{O}_{2} \mathrm{CCO}_{2}^{-}$ |  |  |  |  |  |  |  |  |
| $\mathrm{Al}^{3+}$ |  |  | 15.60 |  |  |  | 20 | 0.1 |
| $\mathrm{Ba}^{2+}$ | 2.31 |  |  |  |  |  | 18 | 0 |
| $\mathrm{Ca}^{2+}$ | 1.66 | 2.69 |  |  |  |  | 25 | 1 |
| $\mathrm{Cd}^{2+}$ | 3.71 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Co}^{2+}$ | 4.69 | 7.15 |  |  |  |  | 25 | 0 |
| $\mathrm{Cu}^{2+}$ | 6.23 | 10.27 |  |  |  |  | 25 | 0 |
| $\mathrm{Fe}^{3+}$ | 7.54 | 14.59 | 20.00 |  |  |  | ? | 0.5 |
| $\mathrm{Ni}^{2+}$ | 5.16 | 6.5 |  |  |  |  | 25 | 0 |
| $\mathrm{Zn}^{2+}$ | 4.85 | 7.6 |  |  |  |  | 25 | 0 |
| 1,10-Phenanthroline, <smiles>c1cnc2c(c1)ccc1cccnc12</smiles> |  |  |  |  |  |  |  |  |
| $\mathrm{Ag}^{+}$ | 5.02 | 12.07 |  |  |  |  | 25 | 0.1 |
| $\mathrm{Ca}^{2+}$ | 0.7 |  |  |  |  |  | 20 | 0.1 |
| $\mathrm{Cd}^{2+}$ | 5.17 | 10.00 | 14.25 |  |  |  | 25 | 0.1 |
| $\mathrm{Co}^{2+}$ | 7.02 | 13.72 | 20.10 |  |  |  | 25 | 0.1 |
| $\mathrm{Cu}^{2+}$ | 8.82 | 15.39 | 20.41 |  |  |  | 25 | 0.1 |
| $\mathrm{Fe}^{2+}$ | 5.86 | 11.11 | 21.14 |  |  |  | 25 | 0.1 |
| $\mathrm{Fe}^{3+}$ |  |  | 14.10 |  |  |  | 25 | 0.1 |
| $\mathrm{Hg}^{2+}$ |  | 19.65 | 23.4 |  |  |  | 20 | 0.1 |
| $\mathrm{Mn}^{2+}$ | 4.50 | 8.65 | 12.70 |  |  |  | 25 | 0.1 |
| $\mathrm{Ni}^{2+}$ | 8.0 | 16.0 | 23.9 |  |  |  | 25 | 0.1 |
| $\mathrm{Zn}^{2+}$ | 6.30 | 11.95 | 17.05 |  |  |  | 25 | 0.1 |

## Logarithm of the Formation Constant for the

APPENDIX J Reaction $\mathbf{M}(\boldsymbol{a q})+\mathbf{L}(\boldsymbol{a q}) \rightleftharpoons \mathbf{M L}(\boldsymbol{a q})^{\boldsymbol{*}}$

| M | L |  |  |  |  |  |  |  |  |  |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
|  | $\mathrm{F}^{-}$ | $\mathrm{Cl}^{-}$ | $\mathbf{B r}^{-}$ | $\mathbf{I}^{-}$ | $\mathrm{NO}_{3}^{-}$ | $\mathrm{ClO}_{4}^{-}$ | $\mathrm{IO}_{3}^{-}$ | $\mathrm{SCN}^{-}$ | $\mathrm{SO}_{4}^{2-}$ | $\mathrm{CO}_{3}^{2-}$ |
| $\mathrm{Li}^{+}$ | 0.23 | - | - | - | - | - | - | - | 0.64 | - |
| $\mathrm{Na}^{+}$ | -0.2 | -0.5 | - | - | -0.55 | -0.7 | -0.4 | - | 0.72 | 1.27 |
| $\mathrm{K}^{+}$ | $-1.2^{a}$ | -0.5 | - | -0.4 | -0.19 | -0.03 | -0.27 | - | 0.85 | - |
| $\mathrm{Rb}^{+}$ | - | -0.4 | - | 0.04 | -0.08 | 0.15 | -0.19 | - | 0.60 | - |
| $\mathrm{Cs}^{+}$ | - | -0.2 | 0.03 | -0.03 | -0.02 | 0.23 | -0.11 | - | 0.3 | - |
| $\mathrm{Ag}^{+}$ | 0.4 | 3.31 | 4.6 | 6.6 | -0.1 | -0.1 | 0.63 | 4.8 | 1.3 | - |
| $\left(\mathrm{CH}_{3}\right)_{4} \mathrm{~N}^{+}$ | - | 0.04 | 0.16 | 0.31 | - | 0.27 | - | - | - | - |
| $\mathrm{Mg}^{2+}$ | 2.05 | 0.6 | $-1.4{ }^{d}$ | - | - | - | 0.72 | $-0.9{ }^{d}$ | 2.23 | 2.92 |
| $\mathrm{Ca}^{2+}$ | 0.63 | $0.2{ }^{b}$ | - | - | 0.5 | - | 0.89 | - | 2.36 | 3.20 |
| $\mathrm{Sr}^{2+}$ | 0.14 | $-0.22{ }^{a}$ | - | - | 0.6 | - | 1.00 | - | 2.2 | 2.81 |
| $\mathrm{Ba}^{2+}$ | -0.20 | $-0.44^{a}$ | - | - | 0.7 | - | 1.10 | - | 2.2 | 2.71 |
| $\mathrm{Zn}^{2+}$ | 1.3 | 0.4 | -0.07 | $-1.5^{d}$ | 0.4 | - | - | 1.33 | 2.34 | 4.76 |
| $\mathrm{Cd}^{2+}$ | 1.2 | 1.98 | 2.15 | 2.28 | 0.5 | - | $0.51{ }^{a}$ | 1.98 | 2.46 | $3.49^{b}$ |
| $\mathrm{Hg}_{2}^{2+}$ | - | - | - | - | $0.08{ }^{\text {f }}$ | - | - | - | $1.30^{f}$ | - |
| $\mathrm{Hg}^{2+}$ | $1.03{ }^{\text {f }}$ | 7.30 | $9.07{ }^{\text {f }}$ | $12.87{ }^{f}$ | $0.11{ }^{d}$ | - | - | 9.64 | $1.34{ }^{f}$ | $11.0^{f}$ |
| $\mathrm{Sn}^{2+}$ | - | 1.64 | 1.16 | $0.70^{e}$ | $0.44{ }^{a}$ | - | - | $0.83{ }^{a}$ | - | - |
| $\mathrm{Y}^{3+}$ | 4.81 | $-0.1{ }^{a}$ | $-0.15^{a}$ | - | - | - | - | $-0.07{ }^{\text {f }}$ | 3.47 | 8.2 |
| $\mathrm{La}^{3+}$ | 3.60 | $-0.1{ }^{a}$ | - | - | $0.1^{a}$ | - | - | $0.12{ }^{a}$ | 3.64 | $5.6{ }^{d}$ |
| $\mathrm{In}^{3+}$ | 4.65 | $2.32{ }^{\text {c }}$ | $2.01{ }^{c}$ | $1.64{ }^{c}$ | 0.18 | - | - | 3.15 | $1.85^{a}$ | - |

*Unless otherwise indicated, conditions are $25^{\circ} \mathrm{C}$ and $\mu=0$.
a. $\mu=1$ M ; b. $\mu=0.1$ M ; c. $\mu=0.7$ M ; d. $\mu=3$ M; e. $\mu=4$ M; f. $\mu=0.5 M$.
source: A. E. Martell, R. M. Smith, and R. J. Motekaitis, NIST Critical Stability Constants of Metal Complexes Database 46 (Gaithersburg, MD: National Institute of Standards and Technology, 2001).

The table in this appendix recommends primary standards for many elements. An elemental assay standard must contain a known amount of the desired element. A matrix matching standard must contain extremely low concentrations of undesired impurities, such as the analyte. If you want to prepare 10 ppm Fe in $10 \%$ aqueous NaCl , the NaCl must not contain significant Fe impurity, because the impurity would then have a higher concentration than the deliberately added Fe.

Rather than using compounds in the table, many people purchase certified solutions whose concentrations are traceable to standards from the National Institute of Standards and Technology (NIST or other national institutes of standards). By NIST traceable, we mean that the solution has been prepared from a standard material certified by NIST or that it has been compared with an NIST standard by a reliable analytical procedure.

Manufacturers frequently indicate elemental purity by some number of 9s. This deceptive nomenclature is based on the measurement of certain impurities. For example, $99.999 \%$ (five 9s) pure Al is certified to contain $\leq 0.001 \%$ metallic impurities, based on the analysis of other metals present. However, $\mathrm{C}, \mathrm{H}, \mathrm{N}$, and O are not measured. The Al might contain $0.1 \% \mathrm{Al}_{2} \mathrm{O}_{3}$ and still be "five 9s pure." For the most accurate work, the dissolved gas content in solid elements may also be a source of error.

Carbonates, oxides, and other compounds may not possess the expected stoichiometry. For example, $\mathrm{TbO}_{2}$ will have a high Tb content if some $\mathrm{Tb}_{4} \mathrm{O}_{7}$ is present. Ignition in an $\mathrm{O}_{2}$ atmosphere may be helpful, but the final stoichiometry is never guaranteed. Carbonates may contain traces of bicarbonate, oxide, and hydroxide. Firing in a $\mathrm{CO}_{2}$ atmosphere may improve
the stoichiometry. Sulfates may contain some $\mathrm{HSO}_{4}^{-}$. Some chemical analysis may be required to ensure that you know what you are really working with.

Most metal standards dissolve in 6 M HCl or $\mathrm{HNO}_{3}$ or a mixture of the two, possibly with heating. Frothing accompanies dissolution of metals or carbonates in acid, so vessels should be loosely covered by a watchglass or Teflon lid to prevent loss of material. Concentrated $\mathrm{HNO}_{3}(16 \mathrm{M})$ may passivate some metals, forming an insoluble oxide coat that prevents dissolution. If you have a choice between using a bulk element or a powder as standards, the bulk form is preferred because it has a smaller surface area on which oxides can form and impurities can be adsorbed. After a pure metal to be used as a standard is cut, it should be etched ("pickled") in a dilute solution of the acid in which it will be dissolved to remove surface oxides and contamination from the cutter. The metal is then washed well with water and dried in a vacuum desiccator.

Dilute solutions of metals are best prepared in Teflon or plastic vessels, because glass is an ion exchanger that can replace analyte species. Specially cleaned glass vials are commercially available for trace organic analysis. Volumetric dilutions are rarely more accurate than $0.1 \%$, so gravimetric dilutions are required for greater accuracy. Of course, weights should be corrected for buoyancy with Equation 2-1. Evaporation of standard solutions is a source of error that is prevented if the mass of the reagent bottle is recorded after each use. If the mass changes between uses, the contents are evaporating.

## Calibration standards

| Element | Source ${ }^{a}$ | Purity | Comments ${ }^{b}$ |
| :--- | :--- | :--- | :--- |
| Li | SRM $924\left(\mathrm{Li}_{2} \mathrm{CO}_{3}\right)$ <br> $\mathrm{Li}_{2} \mathrm{CO}_{3}$ | $100.05 \pm 0.02 \%$ <br> five-six 9s | E ; dry at $200^{\circ} \mathrm{C}$ for 4 h . <br> M; purity calculated from impurities. Stoichiometry unknown. |
| Na | SRM 919 or 2201 ( NaCl ) <br> $\mathrm{Na}_{2} \mathrm{CO}_{3}$ | 99.9\% <br> three 9s | E ; dry for 24 h over $\mathrm{Mg}\left(\mathrm{ClO}_{4}\right)_{2}$. <br> M; purity based on metallic impurities. |
| K | SRM 918 (KCl) <br> SRM 999 (KCl) <br> $\mathrm{K}_{2} \mathrm{CO}_{3}$ | 99.9\% <br> $52.435 \pm 0.004 \% \mathrm{~K}$ <br> five-six 9 s | E ; dry for 24 h over $\mathrm{Mg}\left(\mathrm{ClO}_{4}\right)_{2}$. <br> E; ignite at $500^{\circ} \mathrm{C}$ for 4 h . <br> M; purity based on metallic impurities. |
| Rb | SRM 984 (RbCl) <br> $\mathrm{Rb}_{2} \mathrm{CO}_{3}$ | $99.90 \pm 0.02 \%$ | E ; hygroscopic. Dry for 24 h over $\mathrm{Mg}\left(\mathrm{ClO}_{4}\right)_{2}$. <br> M |
| Cs | $\mathrm{Cs}_{2} \mathrm{CO}_{3}$ |  |  |
| Be | metal | three 9s | E, M; purity based on metallic impurities. |
| Mg | SRM 929 | $100.1 \pm 0.4 \%$ <br> $5.403 \pm 0.022 \% \mathrm{Mg}$ | E; magnesium gluconate clinical standard. <br> Dry for 24 h over $\mathrm{Mg}\left(\mathrm{ClO}_{4}\right)_{2}$. |
| Ca | metal | five 9s | E ; use without drying. <br> $\mathrm{E}, \mathrm{M}$; dry at $200^{\circ} \mathrm{C}$ for 4 h in $\mathrm{CO}_{2}$. User must determine stoichiometry. |
| Sr | SRM $987\left(\mathrm{SrCO}_{3}\right)$ <br> $\mathrm{SrCO}_{3}$ | 99.8\% <br> five 9 s | E: ignite to establish stoichiometry. Dry at $110^{\circ} \mathrm{C}$ for 1 h . <br> M; up to $1 \%$ off stoichiometry. Ignite to establish stoichiometry. Dry at $200^{\circ} \mathrm{C}$ for 4 h . |
| Ba | $\mathrm{BaCO}_{3}$ | four-five 9s | M ; dry at $200^{\circ} \mathrm{C}$ for 4 h . |

Transition metals: Use pure metals (usually $\geq$ four 9s) for elemental and matrix standards. Assays are based on impurities and do not include dissolved gases.
Lanthanides: Use pure metals (usually $\geq$ four 9 s) for elemental standards and oxides as matrix standards. Oxides may be difficult to dry and stoichiometry is not certain.

[^10]Calibration standards (continued)
| Element | Source ${ }^{a}$ | Purity | Comments ${ }^{b}$ |
| :--- | :--- | :--- | :--- |
| B | SRM $951\left(\mathrm{H}_{3} \mathrm{BO}_{3}\right)$ | $100.00 \pm 0.01$ | E; expose to room humidity ( $\sim 35 \%$ ) for 30 min before use. |
| Al | metal | five 9s | E, M; SRM 1257 Al metal available. |
| Ga | metal | five 9s | E, M; SRM 994 Ga metal available. |
| In | metal | five 9s | E, M |
| Tl | metal | five 9s | E, M; SRM 997 Tl metal available. |
| C |  |  | No recommendation. |
| Si | metal | six 9s | E, M; SRM $990 \mathrm{SiO}_{2}$ available. |
| Ge | metal | five 9s | E, M |
| Sn | metal | six 9 s | E, M; SRM 741 Sn metal available. |
| Pb | metal | five 9s | E, M; several SRMs available. |
| N | $\mathrm{NH}_{4} \mathrm{Cl}$ | six 9s | E ; can be prepared from $\mathrm{HCl}+\mathrm{NH}_{3}$. |
|  | $\mathrm{N}_{2}$ | >three 9s | E |
|  | $\mathrm{HNO}_{3}$ | six 9s | M ; contaminated with $\mathrm{NO}_{x}$. Purity based on impurities. |
| P | SRM $194\left(\mathrm{NH}_{4} \mathrm{H}_{2} \mathrm{PO}_{4}\right)$ | three 9s | E |
|  | $\mathrm{P}_{2} \mathrm{O}_{5}$ | five 9s | E, M; difficult to keep dry. |
|  | $\mathrm{H}_{3} \mathrm{PO}_{4}$ | four 9s | E; must titrate 2 hydrogens to be certain of stoichiometry. |
| As | metal | five 9s | E, M |
|  | SRM 83d ( $\mathrm{As}_{2} \mathrm{O}_{3}$ ) | $99.9926 \pm 0.0030 \%$ | Redox standard. As assay not ensured. |
| Sb | metal | four 9s | E, M |
| Bi | metal | five 9s | E, M |
| O | $\mathrm{H}_{2} \mathrm{O}$ | eight 9s | E, M; contains dissolved gases. |
|  | $\mathrm{O}_{2}$ | >four 9s | E |
| S | element | six 9s | $\mathrm{E}, \mathrm{M}$; difficult to dry. Other sources are $\mathrm{H}_{2} \mathrm{SO}_{4}, \mathrm{Na}_{2} \mathrm{SO}_{4}$, and $\mathrm{K}_{2} \mathrm{SO}_{4}$. Stoichiometry must be proved (e.g., no $\mathrm{SO}_{3}^{2-}$ present). |
| Se | metal | five 9s | E, M; SRM 726 Se metal available. |
| Te | metal | five 9s | E, M |
| F | NaF | four 9s | E, M; no good directions for drying. |
| Cl | NaCl | four 9s | $\mathrm{E}, \mathrm{M}$; dry for 24 h over $\mathrm{Mg}\left(\mathrm{ClO}_{4}\right)_{2}$. Several SRMs ( NaCl and KCl ) available. |
| Br | KBr | four 9s | E, M; need to dry and demonstrate stoichiometry. |
|  | $\mathrm{Br}_{2}$ | four 9 s | E |
| I | sublimed $\mathrm{I}_{2}$ | six 9s | E |
|  | KI | three 9s | E, M |
|  | $\mathrm{KIO}_{3}$ | three 9s | Stoichiometry not ensured. |


This page intentionally left blank


[^0]:    *A numerical recipe for evaluating Equation C-1 with a spreadsheet is given by R. de Levie, J. Chem. Ed. 2000, 77, 534.

[^1]:    ${ }^{\dagger}$ E. F. Meyer, J. Chem. Ed. 1997, 74, 1339.
    ${ }^{\ddagger}$ C. Salter, J. Chem. Ed. 2000, 77, 1239.

[^2]:    *A completely different method for balancing complex redox equations by inspection has been described by D. Kolb, J. Chem. Ed. 1981, 58, 642. For some challenging problems in balancing redox equations, see R. Stout, J. Chem. Ed. 1995, 72, 1125.

[^3]:    *Each acid is written in its protonated form. The acidic protons are indicated in bold type.
    ${ }^{\dagger} p K_{a}$ values refer to $25^{\circ} \mathrm{C}$ unless otherwise indicated. Values in parentheses are considered to be less reliable. Data are from A. E. Martell, R. M. Smith, and R. J. Motekaitis, NIST Database 46 (Gaithersburg, MD: National Institute of Standards and Technology, 2001).
    ${ }^{\ddagger}$ The accurate way to calculate $K_{b}$ for the conjugate base is $p K_{b}=13.995-p K_{a}$ and $K_{b}=10^{-p K_{b}}$.
    ${ }^{§}$ See marginal note on page 166 for distinction between $p K_{a}$ at $\mu=0$ and at $\mu=0.1 \mathrm{M}$.

[^4]:    *The concentration of "carbonic acid" is considered to be the sum [ $\mathrm{H}_{2} \mathrm{CO}_{3}$ ] $+\left[\mathrm{CO}_{2}(\right.$ aq $\left.)\right]$. See Box 6-4.

[^5]:    *D. J. Phillips and S. L. Phillips. "High Temperature Dissociation Constants of $\mathrm{HS}^{-}$and the Standard Thermodynamic Values for $\mathrm{S}^{2-}$,, J. Chem. Eng. Data 2000, 45, 981.

[^6]:    ${ }^{*} p K_{3}$ from A. G. Miller and J. W. Macklin, Anal. Chem. 1983, 55, 684.

[^7]:    *The constant given for water is $K_{w}$.

[^8]:    *All species are aqueous unless otherwise indicated. The reference state for amalgams is an infinitely dilute solution of the element in $H g$. The temperature coefficient, $d E^{\circ} / d T$ allows us to calculate the standard potential, $E^{\circ}(T)$, at temperature $T$ : $E^{\circ}(T)=E^{\circ}+\left(d E^{\circ} / d T\right) \Delta T$, where $\Delta T$ is $T-298.15 K$. Note the units $m V / K$ for $d E^{\circ} / d T$. Once you know $E^{\circ}$ for a net cell reaction at temperature $T$, you can find the equilibrium constant, $K$, for the reaction from the formula $K=10^{n F E^{\circ} / R T \ln 10}$, where $n$ is the number of electrons in each half-reaction, $F$ is the Faraday constant, and $R$ is the gas constant.
    sources: The most authoritative source is S. G. Bratsch, J. Phys. Chem. Ref. Data 1989, 18, 1. Additional data come from L. G. Sillén and A. E. Martell, Stability Constants of Metal-Ion Complexes (London: The Chemical Society, Special Publications Nos. 17 and 25. 1964 and 1971); G. Milazzo and S. Caroli, Tables of Standard Electrode Potentials (New York: Wiley, 1978); T. Mussini, P. Longhi, and S. Rondinini, Pure Appl. Chem. 1985, 57, 169. Another good source is A. J. Bard, R. Parsons, and J. Jordan. Standard Potentials in Aqueous Solution (New York: Marcel Dekker, 1985). Reduction potentials for 1200 free radical reactions are given by P. Wardman, J. Phys. Chem. Ref. Data 1989, 18, 1637.

[^9]:    *The overall (cumulative) formation constant, $\beta_{n}$, is the equilibrium constant for the reaction $M+n L \rightleftharpoons M L_{n}: \beta_{n}=\left[M L_{n}\right] /\left([M][L]^{n}\right)$.
    $\beta_{n}$ is related to stepwise formation constants $\left(K_{i}\right)$ by $\beta_{n}=K_{1} K_{2} \ldots K_{n}$ (Box 6-2). $\beta_{n m}$ is the cumulative formation constant for the reaction $m M+n L \rightleftharpoons M_{m} L_{n}: \beta_{n m}=\left[M_{m} L_{n}\right] /\left([M]^{m}[L]^{n}\right)$. The subscript $n$ refers to the ligand and $m$ refers to the metal. Data from L. G. Sillén and A. E. Martell, Stability Constants of Metal-Ion Complexes (London: The Chemical Society. Special Publications No. 17 and 25, 1964 and 1971); and A. E. Martell, R. M. Smith, and R. J. Motekaitis, NIST Critical Stability Constants of Metal Complexes Database 46 (Gaithersburg, MD: National Institute of Standards and Technology, 2001).

[^10]:    a. SRM is the National Institute of Standards and Technology designation for a Standard Reference Material.
    b. E means elemental assay standard; $M$ means matrix matching standard.
    source: J. R. Moody, R. R. Greenberg, K. W. Pratt, and T. C. Rains, "Recommended Inorganic Chemicals for
    Calibration," Anal. Chem. 1988, 60, 1203A.

