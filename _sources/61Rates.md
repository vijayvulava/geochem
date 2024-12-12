# 6.1  Chemical Kinetics

Chemical equilibrium is a thermodynamics concept. Thermodynamics can predict what reactions are possible, however, it does not tell us how fast reactions happen. For example, consider the following reaction that occurs naturally in nature:

$$\ce{
C6H12O6 (s) + 6 O2 (g) -> 6 CO2 (g) + 6 H2O (l)
}$$

Per thermodynamics, the above reaction involving glucose ($\ce{C6H12O6}$ or sugar) proceeds spontaneously under standard conditions, and glucose is expected to combust in the presence of $\ce{O2}$. In reality, when do we observe spontaneous combustion of glucose? We don't because the above reaction proceeds very slowly.

In thermodynamics, we explained that reactions occur spontaneously (this term is unrelated to rates of reactions) and reach equilibrium by minimizing $\Delta_{rxn}G^\circ$. In all spontaneous reactions, products have less free energy than reactants. In some cases, it takes little or no energy to start the process of creation of the products ({numref}`activation-energy`).

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Activation2_updated.svg/1280px-Activation2_updated.svg.png
---
name: activation-energy
figclass: margin-caption
---
Energy is used during the glucose reaction with and without external support (catalyst). In either case, the activation energy must be exceeded for the reaction to proceed. Image source: [Activation energy - Wikipedia](https://en.wikipedia.org/wiki/Activation_energy)
```

In other cases, external factors such as catalysts can lower the activation energy to overcome an energy barrier ({numref}`activation-energy`). This requirement adds time for a reaction to reach equilibrium.

<div class="container">
<iframe src="https://www.youtube.com/embed/D0ZyjpAin_Y" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


Consider the dissolution of the mineral gypsum in water:

$$\ce{
CaSO4.2 H2O (s) ->[H2O] Ca^2+ (aq) + SO4^2- (aq) + 2 H2O (l)
}$$

This reaction is thermodynamically favorable, i.e., $\Delta_{rxn}G^\circ<0$. For this reaction to proceed, energy must be spent to break chemical bonds within the crystalline structure, followed by diffusion of and away from the crystalline surface. The dissolution will continue until there is a dissolved ion gradient between the crystalline surface and the bulk aqueous solution. Thermodynamics does not explicitly account for these intermediate time-limiting steps.

***Chemical kinetics*** is the study of how rapidly reactions take place. Chemical kinetics provide important information for the elucidation of chemical mechanisms.

Consider a chemical reaction expressed in the following general form:

$$\ce{
Reactants -> Products
}$$
Throughout this reaction, concentrations of the *Reactants* decrease while concentrations of the *Products* increase. The rates at which the changes in concentrations occur depend on the chemical system.

In the ***Collision Theory*** of chemical kinetics, the reaction rate is directly proportional to the number of collisions at any given time.

```{math}
:label: collisions-rate
\text{Rate} \propto \frac{\text{Number of Collisions}}{\text{Time}}
```
Not every collision between molecules results in a reaction. However, the collision theory gives a simple basis for explaining chemical reaction mechanisms. For example, a molecule in motion possesses kinetic energy. When molecules collide, part of this kinetic energy is converted to vibrational energy, which can cause some chemical bonds in molecules and crystalline structures to break. A minimum amount of energy, the activation energy ($\Delta G^\ddagger$), is required to initiate a chemical reaction (see {numref}`activation-energy`). Without this minimum energy at impact, a collision will be ineffective, or the reaction will occur slowly.

## Reaction Rates

Since kinetics is concerned with changing chemical concentrations over time, the ***rates*** of chemical reactions become important. 

Consider the following hypothetical reaction: 

$$\ce{A -> B}$$ 
We can follow the progress of a reaction by monitoring either the decrease in concentration of the reactants or the increase in the concentrations of the products ({numref}`rxn-ab`). 

```{figure} https://saylordotorg.github.io/text_general-chemistry-principles-patterns-and-applications-v1.0/section_18/e5dd3f15f478af1b02121333c365af99.jpg
---
name: rxn-ab
figclass: margin-caption
---
The reaction mixture initially contains only *A* molecules (purple). The number of *A* molecules decreases with increasing time, and more *B* molecules (green) are formed (top). The graph shows the change in the reaction's number of *A* and *B* molecules as a function of time (bottom). Image source: [Reaction Rates and Rate Laws (saylordotorg.github.io)](https://saylordotorg.github.io/text_general-chemistry-principles-patterns-and-applications-v1.0/s18-02-reaction-rates-and-rate-laws.html)
```

We can express the change in chemical concentration of each chemical species as a function of time using the "$\Delta$" notation.

```{math}
:label: reaction-rate
\text{Rate} = -\frac{\Delta [A]}{\Delta t} \quad \text{or} \quad \text{Rate} =  \frac{\Delta [B]}{\Delta t}
```

Here, "\[\]" represents the concentration of a chemical species, while the "$-$" (minus) sign represents a decrease in concentration. Rate is always a positive quantity, so when it is expressed as $\Delta [A]/\Delta t$, a minus sign is needed in the rate expression to make the rate positive. When the rate is expressed in terms of the change in a product concentration, no negative sign is needed to make the rate positive because the product concentration increases with time. Rates calculated this way are average rates over the period $\Delta t$.


```{dropdown} Example: Reaction Rates

Write reaction rates for the following reactions:

$$
\begin{align}
\ce{
a A + bB &-> cC + dD\\
CO2 + 2 H2O &-> CH4 + 2 O2\\
4 NH3 + 5 O2 &-> 4 NO + 6 H2O
}
\end{align}$$

**Answer:** 

$$\begin{aligned}
\text{Rate} &=  - \frac{1}{a} \frac{\Delta [A]}{\Delta t} = - \frac{1}{b} \frac{\Delta [B]}{\Delta t} = \frac{1}{c} \frac{\Delta [C]}{\Delta t} =  \frac{1}{d} \frac{\Delta [D]}{\Delta t}\\
&= -  \frac{\Delta [\ce{CO2}]}{\Delta t} = - \frac{1}{2} \frac{\Delta [\ce{H2O}]}{\Delta t} =   \frac{\Delta [\ce{CH4}]}{\Delta t} =  \frac{1}{2} \frac{\Delta [\ce{O2}]}{\Delta t}\\
&= -  \frac{1}{4}\frac{\Delta [\ce{NH3}]}{\Delta t} = - \frac{1}{5} \frac{\Delta [\ce{O2}]}{\Delta t} =   \frac{1}{4}\frac{\Delta [\ce{NO}]}{\Delta t} =  \frac{1}{6} \frac{\Delta [\ce{H2O}]}{\Delta t}
\end{aligned}$$


```


```{dropdown} Example: Reaction Rates 

Consider,

$$\ce{
4 NO2 + O2 -> 2 N2O5
}$$

At a particular time during the reaction, $\ce{NO2(g)}$ is being consumed at the rate of $\pu{1.3e-3 mol L-1 s-1}$. (a) At what rate is $\ce{O2(g)}$ being consumed? (b) At what rate is $\ce{N2O5(g)}$ being produced?

**Answer**:

$$\text{Rate} =  -  \frac{1}{4}\frac{\Delta [\ce{NO2}]}{\Delta t} = -  \frac{\Delta [\ce{O2}]}{\Delta t} =   \frac{1}{2}\frac{\Delta [\ce{N2O5}]}{\Delta t}
$$

$$\begin{aligned}
\frac{\Delta [\ce{NO2}]}{\Delta t} &= -\pu{1.3e-3 mol L-1 s-1}\\
\text{Rate} & = -  \frac{1}{4}\frac{\Delta [\ce{NO2}]}{\Delta t} = -  \frac{1}{4} \times (-\pu{1.3e-3 mol L-1 s-1})\\
&= \pu{3.25e-4 mol L-1 s-1}
\end{aligned}$$

```


## Stoichiometry & Reaction Rates

Consider a hypothetical chemical reaction where two reactants *A* and *B* combine to form a product *AB*. 

$$\ce{A + B \rightarrow AB}$$ 

These reactants show a one-to-one stoichiometry. One mole of *A* reacts with one mole of *B* to form the product, $AB$. The reaction rates of *A* and *B* are identical. It also follows that reaction rates are proportional ($\propto$) to concentrations of *A* ($[A]$) and *B* ($[B]$). If the reaction rates are proportional to concentrations of the reactants, it can be summarized that reaction rates for the reaction are proportional to the product of $[A]$ and $[B]$ or $[A]\times [B]$.

```{math}
:label: rate-ab
\text{Rate} \propto [A] \times [B]
```

The proportional sign in Eq. {eq}`rate-ab` can be converted into an "=" sign by incorporating a proportionality constant, $\kappa$. 

```{math}
:label: ratelaw-ab
\text{Rate} = \kappa [A]^1[B]^1
```

This expression where the reaction rate is equated to reactant concentration is called *rate expressions* or *rate laws*. In this equation, $\kappa$ is called the *rate constant*. By convention, the rate laws are only written for the reactants, and each reactant has its rate constant. Note that the exponent $1$ is shown in Eq. {eq}`ratelaw-ab`, which refers to the number of moles of each reactant in the original chemical reaction. In this case, the ***reaction order*** for *A* and *B* is $1$ (both have one mole each in the reaction.) The reaction order refers to the molecularity or the number of molecules of a reactant participating in a reaction. The reaction order for the whole reaction is the sum of the reaction order for all reactants. In this case, the reaction order for the above reaction is 2. Equation {eq}`ratelaw-ab` also shows that the rate depends on the reactant concentrations.
