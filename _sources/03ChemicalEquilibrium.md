
# Chemical Equilibrium

## Introduction 

The influence of chemical equilibrium and kinetics on the progress of chemical reactions often determines the abundance, distribution, and fate of substances in the environment. An understanding of the basic concepts of chemical equilibrium and chemical kinetics, therefore, may help us to explain and predict the environmental concentrations of inorganic and organic species in aqueous systems, whether these species are present naturally or have been introduced by humans.

Equilibrium principles can be used to explain how Earth came to be and how humans are changing the entire planet dramatically. Watch the video below as narrated by the famous environmental scientist David Attenborough.

<div class="container">
<iframe src="https://www.youtube.com/embed/2Jq23mSDh9U" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

In the previous chapter, we learned about the foundation principles of thermodynamics, including the laws of thermodynamics. These foundational principles explain why reactions happen. In this chapter, we will focus on the terminology of chemical reactions and the predictive power of thermodynamics in various environmental systems.

```{admonition} Learning Goals

The main goals for this chapter are to:
1. 
```



## Chemical Equilibrium

While studying chemical reactions, we need to know when they start and when they end. To do this, we define the state of equilibrium, when reactions are not proceeding. In thermodynamics, systems are at perfect rest, with absolutely no gradients or inhomogeneities of any kind. Under equilibrium conditions, systems have two attributes:

1. None of the properties change with time - regardless of the time observed
2. The system will return to equilibrium if any of its attributes are disturbed.

A state in which there are no observable changes as a function of time. This state is achieved when (i) the rates of forward and reverse reaction rates are equal and (ii) concentrations of reactants and products remain constant. There are two types of equilibrium: (i) ***physical equilibrium*** involves a change in the states of matter, but not a change in the chemical composition. (ii) ***chemical equilibrium*** involves a change in chemical composition.


```{dropdown} Example: Types of equilibrium

1. Physical equilibrium: e.g., $\ce{H2O(l) <=> H2O(g)}$
2. Chemical equilibrium: e.g., $\ce{N2O4(g) <=> 2 NO2(g)} $
```


<div class="container">
<iframe src="https://www.youtube.com/embed/dUMmoPdwBy4" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


## Law of Mass Action and the Equilibrium Constant

To quantify chemical equilibrium, we need to define the term, *reaction quotient* ($Q_c$). In any balanced chemical reaction, this term refers to the ratio of product concentrations in the numerator and reactant concentrations in the denominator -- with each concentration raised to a power equal to the corresponding stoichiometric coefficient.

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

Extensive studies and observations have determined that $Q_c$ had the same value at equilibrium at constant temperature, regardless of the initial concentrations. Therefore, for a system at equilibrium, $Q_c$ becomes the equilibrium constant, $K_c$.

```{math}
:label: lawmassaction

Q_c = \frac{[C]^c[D]^d}{[A]^a[B]^b} = K_c
```

Equation {eq}`lawmassaction` is known as the ***law of mass action***. This expression can be simplified as follows:

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

Note, we did not show any units for $K_c$. It is a dimensionless quantity as described in a subsequent section.

```


### Gas phase concentrations

Gas concentrations can be expressed in $P$. But in reality, gas concentrations are often expressed in partial pressures or as percent of the composition of Earth's atmosphere. Therefore, concentrations of gases are commonly expressed in units of atmosphere or $\pu{atm}$. We can also convert gas concentrations from $\pu{mol L-1}$ to $\pu{atm}$ using the ideal gas law equation. 

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

1. In the first reaction all chemical components are gases and is an example of homogeneous equilibrium reactions i.e., the states of matter are the same in the entire reaction. The second reaction contains more than one phase of matter and is an example of heterogeneous equilibrium.
2. In the first reaction, $K_p$ and $K_c$ can be written since all components are gases, while in the second reaction only $K_c$ can be written as $P$ is not applicable for aqueous/liquid concentrations.

```


### $K$ and $\Delta_{rxn}G$

As seen in Eq. {eq}`equi_exp`, $K$ indicates a ratio of product concentrations over reactant concentrations at equilibrium. This magnitude of this ratio ($K$) can be interpreted mathematically to deduce relative concentrations of reactants or the products at equilibrium in a chemical reaction. When $K$ is very large, we can expect the numerator (product concentrations) to be very large relative to the denominator (reactant concentrations), and vice versa. In other words, we can interpret a high $K$ value to indicate the products in a reaction to be more favored and that the reaction proceeds spontaneously as written (to right). Likewise, a low $K$ can be interpreted as meaning that the reaction is spontaneous to the left. As a rule of thumb, a $K$ value of  $\ge 10^2$ is considered high and a value of  $\le 10^{−2}$ is considered low.

```{table} Magnitude of $K$ and significance in reactions.
:name: k-relative
| $K$ value | Reaction Direction | Spontaneity | 
| --- | --- | --- | 
| $K \gg 1$ |  Products are favored | Spontaneous to right |
| $K \ll 1$ |  Reactants are favored | Spontaneous to left |
```


#### Influence of $K$ on the direction of reactions.

Since magnitude of $K$ is related to spontaneity of the reaction, it follows that $K$ is directly related to $\Delta_{rxn}G^\circ$. When $K \gg 1$, $\Delta_{rxn}G^\circ$ is negative and when $K \ll 1$, $\Delta_{rxn}G^\circ$ is positive. Therefore, we can also use $\Delta_{rxn}G^\circ$ to determine $K$. In the hypothetical reaction,

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

#### Activities

In chemical thermodynamics, concentrations are dimensionless (unitless). These dimensionless or idealized concentrations are called activities. Activity of a chemical constituent is an important concept and is used to address the influence of physical and chemical conditions in the bulk solution. Chemical species in solution interact in many ways with nearby chemical species, including chemical bonding, van der Waals (dipole) interactions, to long-range electrostatic interactions. Sometimes, when concentrations of solutes are very high, they crowd each other. The intensity of all these interactions depends on the distance between the molecules and their concentrations. The activities inherently account for all these factors and are hence referred to as "thermodynamic concentrations." Because, these values are dimensionless, $K_c$ of any aqueous phase chemical reaction is dimensionless.

Activities are derived from the same fundamental thermodynamic principles covered thus far. We use "$\{\, \}$" (curly brackets or braces) around chemical species names to indicate activity. An activity coefficient ($\gamma_i$) is used to convert concentrations to activities as follows: 

```{math}
:label: activity
\{A\} = \gamma_A [A]
```
 where $\{A\}$ is activity, $[A]$ is concentration, and $\gamma_A$ is the activity coefficient. By convention, $\gamma_A = 1$ for ideal solutes and dilute solutions (e.g., rain water and freshwater systems) and is $< 1$ all other cases. Also, by convention, $\{A\} = 1$ for pure solids (e.g., mineral phases, precipitates, etc) and pure liquids (e.g., water).

Activity coefficients are usually determined using ionic strength ($I$) of a solution. Ionic strength is a measure of combined concentration of all ions present in an aqueous solution and is calculated as follows:

```{math}
:label: ionicstrength
I = \frac{1}{2} \sum_{i=1}^{n} c_i z_i^2
```
where,  $c_i$ is concentration of each ion in $\pu{mol L-1 }$ and $z_i$ is charge of each ion in  $\pu{eq mol-1}$. The activity coefficient, $\gamma_i$ for each ion using one of the following equations:

```{math}
:label: activitycoeff
\begin{aligned}
-\log \gamma_i &= A z_i^2 \sqrt{I}\, && \text{for}\, I<0.005 \\
-\log \gamma_i &= \dfrac{A z_i^2 \sqrt{I}}{1+Ba_i\sqrt{I}}\, && \text{for}\, 0.005<I<0.1\\
-\log \gamma_i &= A z_i^2 \sqrt{I} \left( \dfrac{\sqrt{I}}{1+\sqrt{I}} -0.2I\right)\, && \text{for}\, 0.1<I<0.5 
\end{aligned}
```

where, $A$ and $B$ are called Debye-Hückel constants and vary with temperature. At $\pu{25 ^\circ C}$, $A=\pu{0.511}$ and $B=\pu{0.329e8}$. $a_i$ is ion size parameter and is provided in {numref}`ionsize`.

```{table} Ion size parameters ($a_i$) of major ions
:name: ionsize

| $a_i, \, \pu{cm}$ |   Ion |
| --- | --- |
| $\pu{3e-8}$ | $\text{All ions (exceptions below)}$ |
| $\pu{4e-8}$ | $\ce{Na+}$, $\ce{SO4^2-}$, $\ce{PO4^3-}$ |
| $\pu{6e-8}$ | $\ce{Ca^2+}$ |
| $\pu{8e-8}$ | $\ce{Mg^2+}$ |

```

Since, activities are dimensionless, it follows that $K$ values are also dimensionless. However, if a chemical reaction involves heterogeneous phases of reactants and products (usually a mixture of gases and liquids), it is not uncommon to see $K$ values with units.


## Application of $K$

### Predict Direction of a Reaction

$K$ values can be used to predict the direction in which any reaction proceeds spontaneously. First, we have to recall how reaction quotient ($Q_c$, Eq. {eq}`qc`) is calculated for a reaction. See example below.

```{dropdown} Example: Calculate $Q_c$ 

The formation of $\ce{HI(g)}$ from $\ce{H2(g)}$ and $\ce{I2(g)}$ is depicted int the reaction below:

$$\ce{H2(g) + I2(g) <=> 2 HI(g) \qquad $K_c =54.3$ at $\pu{430 ^\circ C}$ 
}$$

If we were to conduct an experiment starting with an initial mixture of $\pu{0.243 M}$ of $\ce{H2(g)}$, $\pu{0.146 M}$  of $\ce{I2(g)}$, and $\pu{1.98 M}$ of $\ce{HI(g)}$ at $\pu{430 ^\circ C}$, we can calculate $Q_c$ as follows: 

$$\begin{aligned}
        Q_c &= \frac{[\ce{HI}]^2}{[\ce{H2}][\ce{I2}]}\\
        &= \frac{(1.98)^2}{(0.243)\times (0.146)}\\
        &= 110.5\\
        & \ne K_c
    \end{aligned}
$$
```

As seen in the example above, $Q_c\ne K_c$. This information can be used to predict the direction in which the reaction proceeds to reach equilibrium. There are three possibilities (summarized in {numref}`qckc-relation`):

```{table} Relationship between $Q_c$ and $K_c$ and how this information helps predict the flow of a reaction.
:name: qckc-relation
| $Q_c\, \text{vs.}\, K_c$ | $\dfrac{\{\text{Products}\}}{\{\text{Reactants}\}}\, \text{Ratio}$ | For Equilbrium | System Proceeds |
| --- | --- | --- | --- |
| $Q_c < K_c$ | Low | Reactants must create products | Towards products |
| $Q_c = K_c$ |  | Concentrations do not change | At equilibrium |
| $Q_c > K_c$ | High | Products must create reactants | Towards reactants |

```

```{dropdown} Example: Comparing $Q_c$ and $K_c$ 

In the above example, $Q_c>K_c$, therefore, the reaction proceeds to the left to reach equilibrium.
```


### Le Châtelier's Principle

As implied in the discussion above, $Q_c$ and $K_c$ in a system could be different, causing the system to be in disequilibrium. Likewise, a system can be disturbed from the equilibrium by a change in reaction conditions. In nature, most systems are in such a state and are working towards achieving this equilibrium. Humans intentionally, or unintentionally, disturb an equilibrium condition towards a goal. An example is the industrial level of production of ammonia ($\ce{NH3}$) by reacting $\ce{N2}$ with $\ce{H2}$ at high $T$ as shown in the following reaction.

$$\ce{N2(g) + 3 H2(g) <=> 2 NH3(g)
}$$

The above reaction is called the Haber-Bosch reaction, widely credited to having providing humans with enhancing crop production critical for matching the population growth in the twentieth century. In this reaction, the production is often manipulated by increasing one or more of the reactants or removing the product, causing the reaction to be out of equilibrium. The system then responds by increasing production of $\ce{NH3(g)}$. This is ultimately the goal of this process at an industrial scale - large production of $\ce{NH3(g)}$.

[The Haber process | TED-Ed](https://ed.ted.com/lessons/the-chemical-reaction-that-feeds-the-world-daniel-d-dulek)

<div class="container">
<iframe src="https://www.youtube.com/embed/o1_D4FscMnU" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Le Châtelier's principle addresses the shift in equilibrium when external stress is applied to a system in equilibrium. *When a stress is applied to a system at equilibrium, the system will respond by shifting in the direction that minimizes the effect of the stress.* *Stress* can be applied in a variety of ways including:
1. addition of a reactant or product,
2. removal of a reactant or product,
3. change in volume of the system, resulting in a change in concentration or partial pressure of the reactants and products, and
4. change in temperature.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/0402516bd1c563bf706ff9a267c6f19a642c591d
---
width: 400px
name: nh3-production
figclass: margin-caption
---
Commercial production of ammonia requires heavy equipment to handle the high temperatures and pressures required. This schematic outlines the design of an ammonia plant. Image source: [17.7 Catalysis - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/17-7-catalysis)
```

The system can respond to such change(s) by "shifting" the reaction in forward or reverse direction, such that the effect of the stress is partially offset as the system reestablishes equilibrium. A shift to the right produces more products by the forward reaction. A shift to the left produces more reactants by the reverse reaction. Using Le Châtelier's principle, we can predict the direction in which an equilibrium will shift, given the specific stress that is applied.

```{dropdown} Example: Addition or removal of chemicals 

Consider the Haber-Bosch process at $\pu{700 ^\circ C}$ :

$$\ce{N2(g) + 3 H2(g) <=> 2 NH3(g)
}$$


If at equilibrium, the concentrations are $[\ce{N2}] = \pu{2.05 M}$, $[\ce{H2}] = \pu{1.56 M}$, and $[\ce{NH3}] = \pu{1.52 M}$, let's calculate the reaction quotient ($Q_c= K_c$ at equilibrium.)

$$\begin{aligned}
Q_c &= \frac{[\ce{NH3}]^2}{[\ce{N2}][\ce{H2}]^3} = \frac{(1.52)^2}{(2.05)\times(1.56)^3}\\
&= 0.297    = K_c
 \end{aligned}
$$ 
    
If we "stress" this system by increasing $[\ce{N2}]$ from $\pu{2.05 M}$  to $\pu{3.51 M}$, let's recalculate $Q_c$ 

$$\begin{aligned}
Q_c &= \frac{(1.52)^2}{(3.51)\times(1.56)^3}\\
&= 0.173 \ne K_c
\end{aligned}
$$ 
    
Since $Q_c < K_c$, the reaction proceeds to the right side of the above reaction (see {numref}`qckc-relation`). We can easily predict reaction scenarios that involve removal or addition of reactants or products.

```


```{dropdown} Example: Changes to volume and pressure 

Consider the following reaction:

$$\ce{N2O4(g) <=> 2 NO2(g)
}$$

At $\pu{25 ^\circ C}$, $K_c = \pu{4.63e-3}$. If at equilibrium, the concentrations are $[\ce{N2O4}] = \pu{0.643 M}$ and $[\ce{NO2}] = \pu{0.0547 M}$ in a cylinder. If we use a piston to reduce the volume of this cylinder by half ("stress"), the resulting concentrations are doubled to $[\ce{N2O4}] = \pu{1.286 M}$ and $[\ce{NO2}] = \pu{0.1094 M}$. Let's calculate $Q_c$. 

$$\begin{aligned}
Q_c &= \frac{[\ce{NO2}]^2}{[\ce{N2O4}]} = \frac{(0.1094)^2}{(1.286)}\\
&= \pu{9.31e-3}    \ne K_c
\end{aligned}
$$ 

Since $Q_c > K_c$, the reaction proceeds to the left side of the above reaction (see {numref}`qckc-relation`).

Note: When there is no difference in the number of moles of gas, changing the volume of the reaction vessel will change the concentrations of reactant(s) and product(s) in the same proportion - but the system will remain at equilibrium. ($Q_c = K_c$)

```


```{dropdown} Example: Changes to temperature 

Changes to $T$ can alter the position of an equilibrium and the equilibrium constant. Consider the following reaction:

$$\ce{N2O4(g) <=> 2 NO2(g)
}$$

This is an endothermic reaction ($\Delta_{sys}H^\circ{}>0$), so the above reaction can be expressed as:

$$\ce{\text{heat} + N2O4(g) <=> 2 NO2(g)
}$$

In this expression, "heat" is treated as a reactant. If we were to increase $T$ or add "heat", we can see that $Q_c < K_c$ or that the reaction will proceed to the right as expected. Similar argument can be made for exothermic reactions.

$T$ increase favors endothermic reactions, while $T$ decrease favors exothermic processes.

```

In cases where $T$ in a system is changed, the resulting new equilibrium constant can be calculated using the van't Hoff equation:

```{math}
:label: vanthoff
\ln \frac{K_2}{K_1} = \frac{\Delta_{rxn}H^\circ}{R} \left(\frac{1}{T_1} - \frac{1}{T_2}\right)
```


### Determine Concentrations of Reactants

If we know the $K$ of a reaction, we can calculate the concentrations in an equilibrium mixture from the initial reactant concentrations. We can set up "ICE" tables to make this calculation methodical.

```{admonition} Calculating concentrations of reactants and products at equilibrium
The following steps summarize the process involved:
1. Construct an equilibrium table, and fill in the initial concentrations (including any that are zero).
2. Use initial concentrations to calculate the reaction quotient, $Q_c$, and compare $Q_c$ to $K_c$ to determine the direction in which the reaction will proceed.
3. Define $x$ as the amount of a particular species consumed, and use the stoichiometry of the reaction to define (in terms of $x$) the amount of other species consumed or produced.
4. For each species in the equilibrium, add the change in concentration to the initial concentration to get the equilibrium concentration.
5. Use the equilibrium concentrations and the equilibrium expression to solve for $x$.
6. Using the calculated value of $x$, determine the concentrations of all species at equilibrium.
7. Check your work by substituting the calculated equilibrium concentrations into the equilibrium expression. The result should be very close to the $K$ stated in the problem.

See the example below to see this method in practice.
```

```{dropdown} Example: Calculating concentrations at equilibrium 

$K_c$ for the following reaction is $54.3$ at $\pu{430 ^\circ C}$

$$\ce{H2(g) + I2(g) <=> 2 HI(g)
}$$

Let's calculate concentrations of all components at equilibrium if we start with $\pu{0.24 M}$ of both $\ce{H2(g)}$ and $\ce{I2(g)}$.

Let's determine how $Q_c$ correlates with $K_c$. Because, there are no products to begin, the reaction proceeds to right to create products.

In the above system, let's insert the starting concentrations that we know into the equilibrium table below. We define the change in concentration of one of the reactants as $x$. Because there is no product at the start of the reaction, the reactant concentration must decrease; that is, this reaction must proceed in the forward direction to reach equilibrium. According to the stoichiometry of the chemical reaction, the reactant concentrations will both decrease by the same amount ($x$), and the product concentration will increase by twice that amount ($2x$). Combining the initial concentration and the change in concentration for each species, we get expressions (in terms of $x$) for the equilibrium concentrations:

|    | $\ce{H2(g)}$ | $+$ | $\ce{I2(g)}$ | $\rightleftharpoons$ | $2\ce{HI(g)}$ |
|--------|------|-----|----------|------------|---------|
| **I**nitial, M  | $0.24$   |     | $0.24$   |   | $0$ |
| **C**hange, M  | $-x$ |     | $-x$  |   | $+2x$  |
| **E**quilibrium, M | $(0.24-x)$  |   | $(0.24-x)$ |   | $(0+2x)$  |

The above equilibrium setup table is called the ***ICE Table***.

From the ICE table we can write $K_c$ expression and substitute equilibrium concentrations

$$K_c = \frac{[\ce{HI}(g)]^2}{[\ce{H2(g)}][\ce{I2(g)}]} = \frac{(0+2x)^2}{(0.24-x)(0.24-x)} = 54.3$$

The above expression can be rearranged into a linear quadratic form:

$$50.3 x^2 - 26.1x + 3.13 = 0$$ 

Solutions for a generic quadratic equation, $ax^2 + bx + c = 0$: 

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$ 

To calculate $x$, substitute $a=50.3$, $b=-26.1$, and $c=3.13$ in above expression and we obtain $x_1 = 0.189$ and $x_2 = 0.329$. Which of these two $x$ values is correct? We can substitute each $x$ value into the equilibrium concentration expressions and determine the correct value.

|         |   |           |   | $x_1$ | $x_2$ |
|---------|:---:|-----------|:---:|---------: |---------: |
| $\ce{H2}$ | = | $ 0.24-x$ | = | $0.051 $  | $-0.089$  |
| $\ce{I2}$ | = | $ 0.24-x$ | = | $0.051$   | $-0.089$  |
| $\ce{HI}$ | = | $ 2x$     | = | $0.378$   | $-0.658$  |

Substituting $x_1$ in the above table resulted in all positive equilibrium concentrations, while substitution of $x_2$ resulted in negative equilibrium concentrations. Since negative concentrations are not possible, the correct value for $x_1 = 0.189$.

As a final check, let's re-substitute equilibrium concentrations in $K$ expression.

$$
K_c = \frac{[\ce{HI}(g)]^2}{[\ce{H2(g)}][\ce{I2(g)}]} = \frac{(0.378)^2}{(0.051)\times(0.051)} = 54.9 \approx 54.3
$$

The small discrepancy in the final calculation can be attributed to rounding.
```


## Practice Problems

(1) Write $Q_c$ expressions for the following reactions:

$$
\begin{align*}
\ce{
2 N2O &<=> 2 N2 + O2 \\
2 NOBr &<=> 2 NO + Br2 \\
HF &<=> H+ + F- \\
CO + H2O &<=> CO2 + H2 \\
CH4 + 2 H2S &<=> CS2 + 4 H2 \\
H2C2O4 &<=> 2 H+ + C2O4^2-
}
\end{align*}
$$
(2) A reaction vessel contains $\ce{NH3 (g)}$, $\ce{N2 (g)}$, and $\ce{H2 (g)}$ at equilibrium at a certain temperature. The equilibrium concentrations are $[\ce{NH3}] = \pu{0.25 M}$, $[\ce{N2}] = \pu{0.11 M}$, and $[\ce{H2}] = \pu{1.91 M}$. Calculate the equilibrium constant $K_c$ for each of the two reactions representing synthesis of ammonia as

$$
\begin{align*}
\ce{N2 + 3 H2 & <=> 2 NH3\\
1/2 N2 + 3/2 H2 & <=> NH3
}
\end{align*}
$$
(3) Create a table of all gases present in Earth's atmosphere from the most abundant at top to less abundant (minimum of 6 gases). In adjacent columns, list concentrations in fraction ($\%$), partial pressure ($P,\, \pu{atm}$), and concentration ($C,\, \pu{mol L-1}$). See template below:
   
| Gas       | Fraction   |   $P$   |   $C$   |
|------  |-----: | ------: | --------: |
|     | $\%$      | $\pu{atm}$ | $\pu{mol L-1}$ |
| $\ce{N2}$ |       |        |         |
| $\ce{O2}$ | $21$    | $0.21$   | $\pu{8.58e-3}$    |
| $\vdots$  |     |     |       |

(4) Carbonyl chloride ($\ce{COCl2}$), also called phosgene, is a highly poisonous gas that was used on the battlefield in World War I. It is produced by the reaction of carbon monoxide with chlorine gas as follows
$$\ce{CO(g) + Cl2(g)  <=> COCl2(g)}$$

In an experiment conducted at $\pu{74 ^\circ C}$, the equilibrium concentrations of the species involved in the reaction were as follows: $[\ce{CO}] = \pu{1.2e-2 M}$, $[\ce{Cl2}]= \pu{0.054 M}$, and $[\ce{COCl2}] = \pu{0.14 M}$. 

>(a) Write the equilibrium expression. 
>
>(b) Determine $K_c$ and $K_p$ for this reaction at 74 °C.

(5). At equilibrium, the pressure of the reacting mixture (represented below) is $\pu{0.105 atm}$ at $\pu{350 ^\circ C}$. 

$$\ce{CaCO3(s) <=> CaO(s) + CO2(g)
}$$
>Determine $K_c$ and $K_p$ for this reaction.

(6) Below is a reaction depicting the composition of water molecules and the production of $\ce{H2(g)}$ at $\pu{25 ^\circ C}$. (In reality, this reaction occurs at a very high temperature.)

$$\ce{2 H2O(g) <=> 2 H2(g) + O2(g)
}$$
> Using thermodynamic data, calculate the equilibrium constant, $K_p$ for this reaction.


(7) The dissolution of silver chloride in water at $\pu{25 ^\circ C}$. 

$$\ce{AgCl(s) <=>[H2O] Ag+(aq) + Cl-(aq) \qquad $K_{sp} = \pu{1.6e-10}$
}$$
> Calculate $\Delta_{rxn}G^\circ$ for the process using only the data provided here.

(8) Consider the decomposition of calcium carbonate as shown in the reaction below. 

$$\ce{CaCO3 <=> CaO + CO2
}$$
>Assume that $\Delta_{rxn}H^\circ = \pu{177.8 kJ mol-1}$ and $\Delta_{rxn}S^\circ = \pu{160.5 J mol-1 K-1}$ for the temperature range.  Calculate the pressure in atm of in an equilibrium process at 
>
>(a) $\pu{25 ^\circ C}$ 
>
>(b) $\pu{800 ^\circ C}$. 

(9) At $\pu{25 ^\circ C}$, $\Delta_{rxn}G^\circ = \pu{8.6 kJ mol-1}$ for the process shown below. 

$$\ce{H2O(l) <=> H2O(g)
}$$
> Calculate the vapor pressure of water at this temperature.

(10) The reaction below shows the equilibrium between graphite and diamond.

$$\ce{C  (diamond) <=> C  (graphite)
}$$

> (a) Calculate $\Delta_{rxn}G^\circ$ for the process.
> 
> (b) Is the formation of graphite from diamond favored at $\pu{25 ^\circ C}$? If so, why is it that diamonds do not become graphite on standing?

(11) $\ce{CaCl2(s)}$ is a strong electrolyte when it is dissolved in water at $\pu{25 ^\circ C}$ to create $\ce{Ca^2+}$ and $\ce{Cl-}$. Calculate activity of $\{\ce{Ca^2+}\}$ and $\{\ce{Cl-}\}$ when the following concentrations of $\ce{CaCl2(s)}$ are dissolved: 

> (a) $\pu{0.001 mol L-1}$
> 
> (b) $\pu{0.09 mol L-1}$
> 
> (c) $\pu{0.4 mol L-1}$ 

(12) At the start of the following reaction, the concentrations of $\ce{N2}$, $\ce{H2}$, and $\ce{NH3}$ are $\pu{0.071 M}$, $\pu{9.2e-3 M}$, and $\pu{1.83e-4 M}$, respectively. 

$$\ce{N2 + 3 H2 <=> 2 NH3 \qquad $K_c =1.2$ at $\pu{375 ^\circ C}$
}$$
>Determine whether this system is at equilibrium, and if not, determine in which direction it must proceed to establish equilibrium.

(13) Hydrogen sulfide ($\ce{H2S(g)}$) is a commonly found in salt marsh environments. It is removed by reaction with oxygen to produce elemental sulfur.

$$\ce{2 H2S(g) + O2(g) <=> 2 S(s) + 2 H2O(g)
}$$

>For each of the following scenarios, determine whether the equilibrium will shift to the right, shift to the left, or neither: 
>
>(a) addition of $\ce{O2(g)}$
>
>(b) removal of $\ce{H2S(g)}$
>
>(c) removal of $\ce{H2O(g)}$
>
>(d) addition of $\ce{S(s)}$

(14) Repeat above problem with the following initial data.

$$\ce{H2(g) + I2(g) <=> 2 HI(g)
}$$

>Calculate concentrations of all components at equilibrium if we start with $\ce{H2(g)}$ = $\pu{0.00623 M}$, $\ce{H2(g)}$ = $\pu{0.00414 M}$, and $\ce{HI(g)}$ =  $\pu{0.0424 M}$. $K_c$ for the above reaction is $54.3$ at $\pu{430 ^\circ C}$. Hint: Compare $Q_c$ with $K_c$ to determine in which direction the reaction proceeds towards equilibrium.

(15) Large quantities of $\ce{H2 (g)}$ are needed to produce $\ce{NH3(g)}$. One preparation for $\ce{H2 (g)}$ is the following reaction, at $\pu{300 ^\circ C}$ in the presence of a Cu-Zn catalyst:

$$\ce{CO(g) + H2O(g) <=> CO2(g) + H2(g) \qquad $K_c=1.87$ and $\Delta _{rxn}H^\circ = \pu{-41 kJ mol-1}$
}$$
>(a) Initial concentrations of reactants $\ce{CO(g)}$ and $\ce{H2O(g)}$ were $\pu{3.2 M}$. The final concentration of $\ce{CO(g)}$ was monitored over time and determined to be $\pu{1.35 M}$ at equilibrium. What are the equilibrium concentrations of all gases? (Use ICE method) 
>
>(b) In another reactor, initial concentrations are: $[\ce{CO}] = \pu{0.50 M}$, $[\ce{H2O}] = \pu{0.045 M}$, $[\ce{CO2}] = \pu{0.050 M}$, $[\ce{H2}] = \pu{0.040 M}$. (i) Compare $Q$ to $K$ and determine in which direction the reaction will proceed. (ii) What are the equilibrium concentrations?
>
>(c) If $\pu{0.80 mole}$ of $\ce{CO(g)}$ and $\ce{H2O(g)}$ are added to a new $\pu{5 L}$ reactor, what are the equilibrium concentrations of all reactants and products?
>
>(d) If your objective is to increase $\ce{H2(g)}$ production, explain which of the following options work? (i) Remove reactant or product? (ii) Add reactant or product? (iii) Change $P$? (iv) Change $T$?
