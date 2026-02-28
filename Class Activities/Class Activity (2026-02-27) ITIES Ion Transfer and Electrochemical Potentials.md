

> [!exercise] Class Activity (2026-02-27): ITIES ion transfer and electrochemical potentials
> 1. The interface between two immiscible electrolyte solutions (ITIES) electrode is very powerful to detect non-redox active ionic species.
> 
> **(a)** Write down the overall electrochemical reaction of the transfer of $\mathrm{ACh}^+$ from water phase (W) to oil phase, nitrobenzene (NB), including phases. Is this a faradaic process?
> 
> **(b)** To derive the Nernst equation, what is the electrochemical potential correlation? Expand the electrochemical potential as a function of standard chemical potential, activity, and inner potential (only the first-step expansion is required).

## Solution

### (a) Interfacial “reaction” for ion transfer and faradaic vs. non-faradaic classification

At an ITIES, the experimentally driven interfacial event is **ion transfer** rather than electron transfer. Writing the transfer of $\mathrm{ACh}^+$ from the aqueous phase (W) to the nitrobenzene phase (NB) as an overall electrochemical reaction (including phases) gives
$$
\mathrm{ACh}^+(\mathrm{W}) \rightleftharpoons \mathrm{ACh}^+(\mathrm{NB}).
$$
If the problem statement intends the *direction* explicitly “from W to NB,” the same reaction can be written with a one-way arrow in that direction:
$$
\mathrm{ACh}^+(\mathrm{W}) \rightarrow \mathrm{ACh}^+(\mathrm{NB}).
$$

To classify the process, use the course distinction between **faradaic** (net charge-transfer across an interface tied to a chemical/stoichiometric event) and **non-faradaic** (no net interfacial transfer reaction; current is purely charging/structural rearrangement). Here, a charged species crosses the W|NB interface; the current corresponds to a net interfacial transfer event and is therefore a **faradaic (charge-transfer) process** in the sense that it is not merely capacitive charging.

At the same time, it is important to note what it is *not*: it is **not** a redox (electron-transfer) reaction, because no electrons appear in the interfacial reaction as written.

### (b) Electrochemical-potential correlation and first-step expansion (activity form)

The thermodynamic “correlation” used to start a Nernst-type derivation is an **equilibrium condition written in terms of electrochemical potentials**. For a single ionic species $j$ distributed between two phases $\alpha$ and $\beta$, equilibrium requires
$$
\bar{\mu}_j^\alpha=\bar{\mu}_j^\beta.
$$
For the ITIES transfer of $\mathrm{ACh}^+$ between the water phase (W) and the nitrobenzene phase (NB), the correlation is therefore
$$
\bar{\mu}_{\mathrm{ACh}^+}^{\mathrm{W}}=\bar{\mu}_{\mathrm{ACh}^+}^{\mathrm{NB}}.
$$

The first-step expansion used in the lecture notes is to write $\bar{\mu}$ as a chemical part plus an electrical (inner-potential) part, and then to write the chemical potential in activity form:
$$
\bar{\mu}_j^\alpha=\mu_j^\alpha+z_jF\phi^\alpha,
\qquad
\mu_j^\alpha=\mu_j^{\circ,\alpha}+RT\ln a_j^\alpha.
$$
Substituting the activity form of $\mu_j^\alpha$ into the electrochemical-potential definition gives the expanded electrochemical potential in phase $\alpha$:
$$
\bar{\mu}_j^\alpha
=
\mu_j^{\circ,\alpha}+RT\ln a_j^\alpha+z_jF\phi^\alpha.
$$

Applying this expansion to $\mathrm{ACh}^+$ in each phase gives
$$
\bar{\mu}_{\mathrm{ACh}^+}^{\mathrm{W}}
=
\mu_{\mathrm{ACh}^+}^{\circ,\mathrm{W}}
+RT\ln a_{\mathrm{ACh}^+}^{\mathrm{W}}
+z_{\mathrm{ACh}^+}F\phi^{\mathrm{W}},
$$
and
$$
\bar{\mu}_{\mathrm{ACh}^+}^{\mathrm{NB}}
=
\mu_{\mathrm{ACh}^+}^{\circ,\mathrm{NB}}
+RT\ln a_{\mathrm{ACh}^+}^{\mathrm{NB}}
+z_{\mathrm{ACh}^+}F\phi^{\mathrm{NB}}.
$$
Since $\mathrm{ACh}^+$ is monovalent, $z_{\mathrm{ACh}^+}=+1$.
