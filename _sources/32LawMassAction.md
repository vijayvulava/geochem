# 3.2  Law of Mass Action

## Reaction quotient

To quantify chemical equilibrium, we must define the term ***reaction quotient*** ($Q_c$). In any balanced chemical reaction, this term refers to the ratio of product concentrations in the numerator and reactant concentrations in the denominator -- with each concentration raised to a power equal to the corresponding stoichiometric coefficient.

$$
\ce{aA + bB <=> cC +dD}
$$

```{math}
:label: qc

Q_c = \frac{[C]^c[D]^d}{[A]^a[B]^b}
```


In the above equation, square brackets "$[ \, ]$" are used to indicate molar concentrations ($\pu{mol L-1}$ or $\pu{M}$) of a chemical constituent.

```{dropdown} Example: Reaction quotient 

Let's write $Q_c$ for the following reactions:

$$
\begin{align*}
\ce{
N2(g) + 3 H2(g) &<=> 2 NH3(g) \\
Cd^2+(aq) + 4 Br-(aq) &<=> CdBr4^2-(aq)
}
\end{align*}
$$

$$
\begin{aligned}
        Q_c &= \frac{[\ce{NH3(g)}]^2}{[\ce{N2(g)}][\ce{H2 (g)}]^3}\\
         &=\frac{[\ce{CdBr4^{2-} (aq)}]}{[\ce{Cd^{2+} (aq)}][\ce{Br^- (aq)}]^4}
\end{aligned}
$$
```

## The Law of Mass Action and $K$

Extensive studies and observations have determined that $Q_c$ had the same value at equilibrium at constant temperature, regardless of the initial concentrations. Therefore, $Q_c$ becomes the equilibrium constant for a system at equilibrium, $K_c$.

```{math}
:label: lawmassaction

Q_c = \frac{[C]^c[D]^d}{[A]^a[B]^b} = K_c
```

Equation {eq}`lawmassaction` is the ***law of mass action***. This expression can be simplified as follows:

```{math}
:label: equi_exp

K_c = \frac{[C]^c[D]^d}{[A]^a[B]^b}
```

This expression is called the ***equilibrium expression***. If the equilibrium concentrations of all reactants and products are known in a given chemical reaction, we can calculate $K_c$.

```{dropdown} Example: Calculating equilibrium constants 

In an analysis of the following reaction at $\pu{100 ^\circ C}$,

$$\ce{
Br2(g) + Cl2(g) <=> 2 BrCl(g)
}$$

the equilibrium concentrations were found to be $[\ce{Br2 (g)}] = \pu{2.3e-3 mol L-1}$, $[\ce{Cl2 (g)}] = \pu{1.2e-2 mol L-1}$, and $[\ce{BrCl (g)}] = \pu{1.4e-2 mol L-1}$.
 
Let's write the equilibrium expression and substitute the given equilibrium concentrations to calculate $K_c$ 

$$\begin{aligned}
    K_c &= \frac{[\ce{BrCl(g){}}]^2}{[\ce{Br2(g)}][\ce{Cl2(g)}]}\\
        &= \frac{(\pu{1.4e-2 mol L-1})^2}{(\pu{2.3e-3 mol L-1})(\pu{1.2e-2 mol L-1})}\\
        &= 7.1
\end{aligned}
$$ 

Note that we did not show any units for $K_c$. It is a dimensionless quantity, as described in a subsequent section.

```


## Gas phase concentrations

Gas concentrations can be expressed in $P$. But in reality, gas concentrations are often expressed in partial pressures or as percent of the composition of Earth's atmosphere. Therefore, concentrations of gases are commonly expressed in units of atmosphere or $\pu{atm}$. Using the ideal gas law equation, we can also convert gas concentrations from $\pu{mol L-1}$ to $\pu{atm}$. 

```{math}
:label: gaslaw

PV = n R T
```
where, $P$ is pressure in $\pu{atm}$, $V$ is volume in $\pu{L}$, $n$ is number of moles, $T$ is temperature in $\pu{K}$, and $R$ is gas law constant and has the value of $\pu{0.0821 L atm mol-1 K-1}$ or $\pu{8.314 J mol-1 K}$ at STP. Note that the ideal gas law is derived from a combination of Boyle's, Charles', and Avogadro's laws. To convert gas concentrations from $\pu{mol L-1}$ to $\pu{atm}$, rearrange Eq. {eq}`gaslaw` as follows:

```{math}
:label: mol-atm-convert
\frac{n\ (\pu{mol})}{V\ (\pu{L})} = \frac{P\ (\pu{atm}) }{R\ (\pu{atm L mol-1 K-1}) \times T\ (\pu{K})}
```


[The ABC's of gas: Avogadro, Boyle, Charles - TED-Ed](https://ed.ted.com/lessons/1207-1-a-bennet-brianh264)

<div class="container">
<iframe src="https://www.youtube.com/embed/BY9VGS2eXas" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


```{dropdown} Example: Converting gas phase concentrations 

$P_{\ce{O2}}$ in Earth's atmosphere is $0.21$ (or $21\%$ of Earth's atmosphere is composed of $\ce{O2 (g)}$) We can convert $P_{\ce{O2}}$ to $[\ce{O2}]$  at $\pu{25 ^\circ C}$ as follows: 

$$
\begin{aligned}
    \frac{n\ (\pu{mole})}{V\ (\pu{L})} &= \frac{P\ (\pu{atm}) }{R\ (\pu{atm L mol-1 K-1}) \times T\ (\pu{K})}\\
    &= \frac{\pu{0.21 atm}}{(\pu{0.0821atm L mol-1 K-1})\times (\pu{298 K})}\\
    &= \pu{8.58e-3 mol L-1}
    \end{aligned}
$$
```

The equilibrium expression can be rewritten for reactions that involve gases only as 

```{math}
:label: gas-equi
K_p = \frac{{P_C}^c {P_D}^d}{{P_A}^a {P_B}^b}
```

The subscript, $p$, in $K_p$ refers to gas concentrations expressed in $\pu{atm}$, while the subscript, $c$, in $K_c$ refers to gas concentrations expressed in $\pu{mol L-1}$. Because gas concentrations are interchangeable in units, it follows that $K_p$ and $K_c$ are correlated as follows: 

```{math}
:label: kp-kc-convert
K_p = K_c (RT)^{\Delta n}
```

where, $\Delta n = \sum \text{Total}\, n\, \text{of products} - \sum \text{Total}\, n\, \text{of reactants}$.

```{dropdown} Example: Writing equilibrium expressions 
Let's write the equilibrium expression in $K_p$ for the following reaction:

$$\ce{
Br2 (g) + Cl2 (g) <=> 2 BrCl (g)}
$$

$$K_p = \frac{{P_{\ce{BrCl (g)}}}^2}{P_{\ce{Br2 (g)}} P_{\ce{Cl2 (g)}}}$$

```

```{dropdown} Example: Converting equilibrium expressions 

We calculated $K_c=7.1$ for the reaction below

$$\ce{
Br2 (g) + Cl2 (g) <=> 2 BrCl (g)}
$$

Let's convert $K_c$ to $K_p$ using Eq. {eq}`kp-kc-convert`. 

$\Delta n = (2)-(1+1) = 0$. 

$$
\begin{aligned}
K_p &= K_c (RT)^{\Delta n}\\
    &= 7.1 \times (\pu{0.0821 atm L mol-1 K-1} \times \pu{373 K})^0\\
    &= 7.1
    \end{aligned}
$$
```


```{dropdown} Example: $K$'s and reaction types 

Consider the following two reactions:

$$
\begin{align*}
\ce{
N2O4 (g) &<=> 2 NO2 (g) \\
CO2 (g) + H2O (l) &<=> H2CO3 (aq)
}
\end{align*}
$$

1. In the first reaction, all chemical components are gases and is an example of a homogeneous equilibrium reaction, i.e., the states of matter are the same in the entire reaction. The second reaction contains more than one phase of matter and is an example of heterogeneous equilibrium.
2. In the first reaction, $K_p$ and $K_c$ can be written since all components are gases, while in the second reaction, only $K_c$ can be written as $P$ is not applicable for aqueous/liquid concentrations.

```


## $K$ and $\Delta_{rxn}G$

As seen in Eq. {eq}`equi_exp`, $K$ indicates a ratio of product concentrations over reactant concentrations at equilibrium. The magnitude of this ratio ($K$) can be interpreted mathematically to deduce relative concentrations of reactants or the products at equilibrium in a chemical reaction. When $K$ is very large, we can expect the numerator (product concentrations) to be very large relative to the denominator (reactant concentrations) and vice versa. In other words, we can interpret a high $K$ value to indicate the products in a reaction to being more favored and that the reaction proceeds spontaneously as written (to the right). Likewise, a low $K$ can mean a spontaneous reaction to the left. As a rule of thumb, a $K$ value of  $\ge 10^2$ is considered high, and a value of  $\le 10^{−2}$ is considered low.

```{table} Magnitude of $K$ and significance in reactions.
:name: k-relative
| $K$ value | Reaction Direction | Spontaneity | 
| --- | --- | --- | 
| $K \gg 1$ |  Products are favored | Spontaneous to right |
| $K \ll 1$ |  Reactants are favored | Spontaneous to left |
```


## Influence of $K$ on the direction of reactions.

Since the magnitude of $K$ is related to the reaction's spontaneity, $K$ is directly related to $\Delta_{rxn}G^\circ$. When $K \gg 1$, $\Delta_{rxn}G^\circ$ is negative and when $K \ll 1$, $\Delta_{rxn}G^\circ$ is positive. Therefore, we can also use $\Delta_{rxn}G^\circ$ to determine $K$. In the hypothetical reaction,

$$\ce{aA + bB <=> cC + dD}
$$

$Q_C$ can be written as shown in Eq. {eq}`qc`. Using thermodynamic data, $\Delta_{rxn}G^\circ$ can be determined. In nonstandard conditions, it can shown from thermodynamic principles that

$$\Delta_{rxn}G^\circ = \Delta_{rxn}G^\circ{} + \mathrm{R}T\ln Q_c$$
Under equilibrium conditions, $\Delta_{rxn}G^\circ{}=0$ and $Q_c=K_c$, therefore the above equation can be simplified as follows: 

```{math}
:label: kc-gibbs-ln
\begin{align}
0 &= \Delta_{rxn}G^\circ{} + \mathrm{R}T\ln K_c \\
\Delta_{rxn}G^\circ{} &= -\mathrm{R}T\ln K_c
\end{align}
```
The above equation can be simplified into a non-logarithmic form as follows:

```{math}
:label: kc-gibbs

K_c = e^{-\left({\dfrac{\Delta_{rxn}G^\circ{}}{\mathrm{R}T}}\right)}
```

## Chemical Activities

In chemical thermodynamics, concentrations are dimensionless (unitless). These dimensionless or idealized concentrations are called activities. The activity of a chemical constituent is an important concept and is used to address the influence of physical and chemical conditions in the bulk solution. Chemical species in solution interact with nearby chemical species, including chemical bonding, van der Waals (dipole), and long-range electrostatic interactions. Sometimes, when concentrations of solutes are very high, they crowd each other. The intensity of all these interactions depends on the distance between the molecules and their concentrations. The activities inherently account for all these factors and are called "thermodynamic concentrations." Because these values are dimensionless, $K_c$ of any aqueous phase chemical reaction is dimensionless.

Activities are derived from the same fundamental thermodynamic principles covered thus far. We use "$\{\, \}$" (curly brackets or braces) around chemical species names to indicate activity. An activity coefficient ($\gamma_i$) is used to convert concentrations to activities as follows: 

```{math}
:label: activity
\{A\} = \gamma_A [A]
```
 where $\{A\}$ is activity, $[A]$ is concentration, and $\gamma_A$ is the activity coefficient. By convention, $\gamma_A = 1$ for ideal solutes and dilute solutions (e.g., rainwater and freshwater systems) and is $< 1$ in all other cases. Also, by convention, $\{A\} = 1$ for pure solids (e.g., mineral phases, precipitates, etc.) and pure liquids (e.g., water).

Activity coefficients are usually determined using a solution's ionic strength ($I$). Ionic strength is a measure of the combined concentration of all ions present in an aqueous solution and is calculated as follows:

```{math}
:label: ionicstrength
I = \frac{1}{2} \sum_{i=1}^{n} c_i z_i^2
```
where,  $c_i$ is concentration of each ion in $\pu{mol L-1 }$ and $z_i$ is charge of each ion in  $\pu{eq mol-1}$. The activity coefficient, $\gamma_i$, for each ion using one of the following equations:

```{math}
:label: activitycoeff
\begin{aligned}
-\log \gamma_i &= A z_i^2 \sqrt{I}\, && \text{for}\, I<0.005 \\
-\log \gamma_i &= \dfrac{A z_i^2 \sqrt{I}}{1+Ba_i\sqrt{I}}\, && \text{for}\, 0.005<I<0.1\\
-\log \gamma_i &= A z_i^2 \sqrt{I} \left( \dfrac{\sqrt{I}}{1+\sqrt{I}} -0.2I\right)\, && \text{for}\, 0.1<I<0.5 
\end{aligned}
```

where $A$ and $B$ are called Debye-Hückel constants and vary with temperature. At $\pu{25 ^\circ C}$, $A=\pu{0.511}$ and $B=\pu{0.329e8}$. $a_i$ is ion size parameter and is provided in {numref}`ionsize`.

````{margin}
```{table} Ion size parameters ($a_i$) of major ions
:name: ionsize

| $a_i, \, \pu{cm}$ |   Ion |
| --- | --- |
| $\pu{3e-8}$ | $\text{All ions (exceptions below)}$ |
| $\pu{4e-8}$ | $\ce{Na+}$, $\ce{SO4^2-}$, $\ce{PO4^3-}$ |
| $\pu{6e-8}$ | $\ce{Ca^2+}$ |
| $\pu{8e-8}$ | $\ce{Mg^2+}$ |

```
````

## Units of $K$

As seen in the previous section, the **activity**, or the effective concentration, of ions is less than that indicated by the actual concentration. Ions become more widely separated as solutions become more dilute, and the residual interionic interactions become less significant. Thus, in extremely dilute solutions, the effective concentrations of the ions (their activities) are equal to the actual concentrations. *In freshwater environmental systems, aqueous ions are present in very small concentrations; therefore, activities and concentrations are similar*.

 Below is a summary of the main conventions of activities and effective concentrations:
- Activities are dimensionless (unitless) quantities and are essentially “adjusted” concentrations.
- A substance's activity and molar concentration are roughly equal for relatively dilute solutions.
- Activities for pure condensed phases (solids and liquids) are equal to 1.

Due to this last consideration, $Q_c$ and $K_c$ expressions do not contain terms for solids or liquids (being numerically equal to 1, these terms do not affect the expression's value). 

For **homogeneous equilibrium** (the reactants and products are present in a single solution), evaluation of reaction quotients ($Q_c$), and equilibrium constants ($K_c$), it is a common convention to omit units of concentrations (as they are equivalent to activities) of reactants and products, resulting in **$K$ values are also dimensionless**. 

```{dropdown} Example: Homogeneous reactions

Consider the following reactions:

$$
\begin{align*}
\ce{
H2CO3 (aq) &<=> H+ (aq) + HCO3- (aq) && $K_c$ = \frac{[H+ (aq)][HCO3- (aq)]}{[H2CO3 (aq)]}\\
NH3 (aq) + H2O (l) &<=> NH4+ (aq) + OH- (aq) && $K_c$ = \frac{[NH4+ (aq)][OH− (aq)]}{[NH3 (aq)]}\\
N2 (g) + 3 H2 (g) &⇌ 2 NH3 (g) && $K_c$ = \frac{[NH3 (g)]^2}{[N2 (g)][H2 (g)]^3}
}
\end{align*}
$$

1. In the first two reactions, all chemical components are in the aqueous phase and/or include $\ce{H2O (l)}$. A $K_c$ expression can be written for these reactions, and the concentration $H2O (l)$ does not appear by convention in the $K_c$ expression.
2. In the third reaction, all components are in the gas phase, and $K_p$ and $K_c$ expressions can be written.

```

A **heterogeneous equilibrium** is a system in which reactants and products are found in two or more phases. The phases may combine solid, liquid, or gas phases and solutions. When dealing with these equilibria, remember that solids and pure liquids do not appear in equilibrium constant expressions (the activities of pure solids, pure liquids, and solvents are 1).  If a chemical reaction involves heterogeneous phases of reactants and products (usually a mixture of gases and liquids), it is not uncommon to see $K$ values with units.

```{dropdown} Example: Heterogeneous reactions

Consider the following reactions:

$$
\begin{align*}
\ce{
PbCl2 (s) + H2O (l)  &⇌ Pb^2+ (aq) + 2 Cl− (aq) && $K_c$ = [Pb^2+ (aq)][Cl− (aq)]^2 \\
CaO (s) + CO2 (g) &⇌ CaCO3 (s) && $K_c$ = \frac{1}{[CO2 (g)]} \\
H2O (l) &⇌ H2O (g) && $K_c$ = [H2O (g)] 
}
\end{align*}
$$

1. A  solid dissolves in $\ce{H2O (l)}$ to form ions in the first reaction. 
2. In the second reaction, a solid reacts with a gas to form another solid. $K_p$ and $K_c$ expressions can be written.
3. In the third reaction, a phase change is occurring. $K_p$ and $K_c$ expressions can be written.

When writing out the $K_c$ expressions in such reactions, the activities of solids, liquids, and solvents are 1. 

```