# Horizon–Response Cosmology (micro ↔ macro)

## Friedmann (explicit DM and GW; “reservoir” excluded from FRW background)

Let $\rho_r^{\rm std}$ be photons + standard neutrinos (excluding $\rho_{\rm GW}$). Then

$$
H^2 \;=\; \frac{8\pi G}{3}\,\big(\rho_b+\rho_{\rm DM}+\rho_r^{\rm std}+\rho_{\rm GW}+\rho_\Lambda\big)\,.
$$

---

## Continuity system
<em>Densities in</em> $\mathrm{GeV}^4$; <em>comoving volume</em> $V_c$ has units $\mathrm{GeV}^{-3}$; <em>sources</em> have units $\mathrm{GeV}^5$.


$$
\begin{aligned}
\dot\rho_\Lambda &= \frac{\alpha_h}{V_c}\,\dot S_{\rm hor},\\
\dot\rho_{\rm DM}+3H\rho_{\rm DM} &= p_{\rm DM}\,\frac{\varepsilon_h}{V_c}\,\dot S_{\rm hor},\\
\dot\rho_{\rm GW}+4H\rho_{\rm GW} &= p_{\rm GW}\,\frac{\varepsilon_h}{V_c}\,\dot S_{\rm hor},\\
\dot\rho_{\rm hor}+3H(1+w_{\rm hor})\,\rho_{\rm hor} &= -\,\frac{\varepsilon_h}{V_c}\,\dot S_{\rm hor}\,.
\end{aligned}
$$

with $w_\Lambda=-1$, $w_{\rm DM}=0$, $w_{\rm GW}=1/3$, and $w_{\rm hor}$ user-chosen.

---

## Partition closure and conservation

$$
p_\Lambda+p_{\rm DM}+p_{\rm GW}=1, \qquad \alpha_h=p_\Lambda\,\varepsilon_h \, .
$$

Define source terms

$$
\begin{aligned}
Q_\Lambda &= \frac{\alpha_h}{V_c}\,\dot S_{\rm hor}, &
Q_{\rm DM} &= p_{\rm DM}\,\frac{\varepsilon_h}{V_c}\,\dot S_{\rm hor},\\
Q_{\rm GW} &= p_{\rm GW}\,\frac{\varepsilon_h}{V_c}\,\dot S_{\rm hor}, &
Q_{\rm hor} &= -\,\frac{\varepsilon_h}{V_c}\,\dot S_{\rm hor}\,.
\end{aligned}
$$

Then total covariant conservation is

$$
\sum_{i\in\{\Lambda,{\rm DM},{\rm GW},{\rm hor}\}}
\left(\dot\rho_i+3H(1+w_i)\rho_i\right)=0\,.
$$

---

## Vacuum channel (integrated form)

$$
\rho_\Lambda(t)=\rho_{\Lambda0}+\frac{1}{V_c}\int_{t_0}^{t}\!\alpha_h(t')\,\dot S_{\rm hor}(t')\,dt'
=\rho_{\Lambda0}+\frac{1}{V_c}\int_{S_{\rm hor}(t_0)}^{S_{\rm hor}(t)}\!\alpha_h(S)\,dS \, .
$$

**Constant $\alpha_h$ special case (explicit):**

$$
\rho_\Lambda(t)=\rho_{\Lambda0}+\frac{\alpha_h}{V_c}\,\Delta S_{\rm hor}(t)\,.
$$

---

## Horizon–entropy production
Extensive in $V_c$; $\dot S_{\rm hor}$ has units $\mathrm{GeV}$.

$\dot S_{\rm hor}(t)=\int dM\,N(M,t)\,\dot S_{\rm BH}(M,t)+\iint dM_1\,dM_2\,R_{\rm merg}(M_1,M_2,t)\,\Delta S_{\rm merg}$,

where $N(M,t)$ is the differential count per unit mass with units $\mathrm{GeV}^{-1}$ (so that $dM\,N$ is dimensionless), $\dot S_{\rm BH}$ and $R_{\rm merg}$ are rates $[\mathrm{GeV}]$, and $\Delta S_{\rm merg}$ is dimensionless.

---

## Micro-informed coefficients
<em>Both coefficients are in</em> $\mathrm{GeV}$.

$$
\alpha_h=C_\alpha\!\left(\frac{\kappa}{K_s}\right)\!\left(|\Omega|\,R_\ast\right),
\qquad
\varepsilon_h=C_\varepsilon\!\left(\frac{\kappa}{K_s}\right)\!\left(|\Omega|\,R_\ast\right),
$$

with $C_\alpha,C_\varepsilon=\mathcal O(1)$, $K_s[\mathrm{GeV}]$, $\kappa[\mathrm{GeV}^2]$, $|\Omega|[\mathrm{GeV}]$ (convert the rate), $R_\ast[\mathrm{GeV}^{-1}]$. Hence $(|\Omega|R_\ast)$ is dimensionless and $(\kappa/K_s)$ carries $\mathrm{GeV}$.

---

## Micro → macro ties (locked SU(2) Skyrme inputs)

$$
R_\ast=\frac{c_R}{eK_s},\qquad X\equiv eK_s,\qquad m=\frac{c_m K_s}{e}\, .
$$

**Present calibration**

$$
K_s=0.04784537~\mathrm{GeV},\quad e=1.11063189,\quad
X=eK_s=0.05313859~\mathrm{GeV},\quad
R_\ast=27.2466~\mathrm{GeV}^{-1}=5.3765\times10^{-13}~\mathrm{cm}\, .
$$

---

## Units and conversions  *(work in GeV after one conversion)*

**Dimensions.** $[\dot S_{\rm hor}] = \mathrm{GeV}$, $[V_c] = \mathrm{GeV}^{-3}$, $[\alpha_h]=[\varepsilon_h]=\mathrm{GeV}$.  
Thus $(\alpha_h/V_c)\,\dot S_{\rm hor}$ and $(\varepsilon_h/V_c)\,\dot S_{\rm hor}$ carry $\mathrm{GeV}^5$, matching $[\dot\rho]=\mathrm{GeV}^5$.

**Conversion factors.**

$$
1~\mathrm{km}^{-1}=1.973269804\times10^{-19}~\mathrm{GeV}\,,
$$

$$
1~\mathrm{cm}=5.06773065\times10^{13}~\mathrm{GeV}^{-1}\,,
$$

$$
1~\mathrm{Mpc}=1.563738286\times10^{38}~\mathrm{GeV}^{-1}\,,
\qquad
1~\mathrm{Mpc}^3=3.823774\times10^{114}~\mathrm{GeV}^{-3}\,.
$$

---

## ΛCDM limit (sanity)

If $\dot S_{\rm hor}\!\to\!0$ or $\varepsilon_h\!\to\!0$, then

$$
\dot\rho_\Lambda\to 0,\qquad
\dot\rho_{\rm DM}+3H\rho_{\rm DM}\to 0,\qquad
\dot\rho_{\rm GW}+4H\rho_{\rm GW}\to 0,
$$

recovering constant $\rho_{\Lambda0}$.  
Enforce $0\le p_\Lambda,p_{\rm DM},p_{\rm GW}\le 1$ and $p_\Lambda+p_{\rm DM}+p_{\rm GW}=1$.  
If both $\alpha_h$ and $\varepsilon_h$ are supplied, set $p_\Lambda=\alpha_h/\varepsilon_h$ and verify $p_\Lambda\in[0,1]$.  
Confirm $(|\Omega|R_\ast)$ is dimensionless after converting $|\Omega|$ to $\mathrm{GeV}$.

---

## How to use (sequence)

1. **Inputs:** $(K_s,e,c_R)$, $(C_\alpha,C_\varepsilon)$, $(p_\Lambda,p_{\rm DM},p_{\rm GW})$, and fixed comoving $V_c$.
2. **Convert units:** express $|\Omega|$ and $V_c$ in GeV units.
3. **Compute micro scales:** $R_\ast=c_R/(eK_s)$.
4. **Set coefficients:**  
   - Either $\alpha_h=C_\alpha(\kappa/K_s)(|\Omega|R_\ast)$ and $\varepsilon_h=C_\varepsilon(\kappa/K_s)(|\Omega|R_\ast)$,  
   - Or provide $\varepsilon_h$ and set $\alpha_h=p_\Lambda\,\varepsilon_h$.
5. **Evolve:** integrate the continuity system above (use the integral form for $\rho_\Lambda$ unless $\alpha_h$ is constant).
6. **Checks:** verify the conservation identity and all unit conversions before interpreting results.
