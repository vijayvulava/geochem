# Chemical Kinetics

## Introduction

“Diamonds are forever,” says a famous advertising campaign. Are they? A look at the table of enthalpy and entropy values tells us the thermodynamically stable form of carbon is actually graphite, not diamond. Further, thermodynamics calculations shows us that the conversion of diamond into graphite is a spontaneous process ($\Delta _{rxn}G^\circ <0$). So why do we not see diamond spontaneously forming graphite? Thus far we have focused on processes that are at equilibrium. However, most chemical processes occur at different rates before achieving equilibrium. While the conversion of diamond into graphite is a spontaneous process, it occurs so slowly that we do not observe the conversion taking place in human  life scale.

In this chapter we focus on how to quantify reaction rates.  Chemical kinetics is the description of the rate of chemical reactions. This is the rate at which the reactants are transformed into products. This may take place by abiotic or by biological systems, such as microbial metabolism. Since a rate is a change in quantity that occurs with time, the change we are most concerned with is the change in the concentration of reactants into new chemical compounds.

<div class="container">
<iframe src="https://www.youtube.com/embed/OttRV5ykP7A" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Below are some examples of the application of chemical kinetics in environmental geosciences.

### Radioisotope Decay

Radioisotopes (unstable isotopes of elements - covered in the next chapter) are ubiquitous on the Earth.  Radioisotopes are important for understanding the Earth in a number of ways. One way is through the use of radioisotope dating, which allows us to determine the age of rocks that make up the Earth. This is possible because some (or all) isotopes of elements, such as C, K, and U, are radioactive and will decay into other elements over time. By measuring the amount of the parent element and the amount of the daughter element, geologists can calculate the age of the rock or mineral. However, the decay rates of these radioisotopes vary with element and range from seconds to billions of years.

For example, $\ce{^{14}C}$ (radioisotope of C) has a half-life ($t_{1/2}$ or the time required to decay half of the original mass of the isotope) of $\pu{5.7e3 y}$ and is very useful for dating fossils. $\ce{^{238}U}$ (radioisotope of U) has a half-life of $\pu{4.5e9 y}$ (4.5 billion years!) and can be used to study very old rocks.  In contrast, $\ce{^{99}Tc}$ has a very short half-life ($\pu{6 h}$) and is commonly used as a tracer in medical diagnostic purposes. So in each case decay rates are variable.

### Chemical Weathering

Chemical weathering is a spontaneous process, but proceeds at different rates depending on the parent rocks and the conditions.  Rocks containing carbonate minerals are more likely to weather rapidly compared to rocks containing silicate minerals.  Likewise, humid environments are more likely to accelerate weathering rates compared to arid climates.  Atmospheric contaminants such as $\ce{SO2}$ from fossil fuel combustion can also increase weathering rates.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/cac9008a5ab38f1a093cf966f25f49c4d76b443a
---
name: marble-statue
figclass: margin-caption
---
Statues made from carbonate compounds such as limestone and marble typically weather slowly over time due to the actions of water, and thermal expansion and contraction. However, pollutants like sulfur dioxide can accelerate weathering. As the concentration of air pollutants increases, deterioration of limestone occurs more rapidly. Image source: [17.2 Factors Affecting Reaction Rates - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/17-2-factors-affecting-reaction-rates)
```

### Redox Processes
 
 Redox reactions involve transfer of $\ce{e-}$ from one element to another (as covered in the previous chapter) as shown in the reaction below.
 $$\ce{
    FeS2 + 14 Fe^3+ + 8 H2O -> 16 H+ + 15 Fe^2+ + 2 SO4^2-
}$$
Such reactions are rate-limited and can be influenced by many factors including: (a) the nature of the reactants - for example, highly reactive substances tend to react more quickly than less reactive substances, (b) the concentration of the reactants - generally, the higher the concentration of reactants, the faster the reactions, (c) the presence of catalysts (substances that can increase the rate of a chemical reaction without being consumed in the process) - they provide an alternative pathway for the reaction that has a lower activation energy, (d) the temperature - generally, an increase in temperature leads to an increase in the rate of the reaction, and (e) the pressure -  for gases, an increase in pressure can lead to an increase in the rate of the reaction.


```{admonition} Learning Goals

The main goals for this chapter are to:
1. 
```


## Chemical Kinetics

Chemical equilibrium is a thermodynamics concept. Thermodynamics is able to predict what reactions as possible, however, it does not tell us how fast reactions happen. For example, consider the following reaction that occurs naturally in nature:

$$\ce{
C6H12O6 + 6 O2 -> 6 CO2 + 6 H2O 
}$$

Per thermodynamics, the above reaction involving glucose ($\ce{C6H12O6}$ or sugar) proceeds spontaneously under standard conditions and glucose is expected to combust in the presence of $\ce{O2}$. In reality, when do we observe spontaneous combustion of glucose? We don't, because the above reaction proceeds very slowly.

In thermodynamics, we explained that reactions occur spontaneously (this term is unrelated to rates of reactions) and reach equilibrium by minimizing $\Delta_{rxn}G^\circ$ . In all spontaneous reactions, products have free energies less than that of the reactants. In some cases, it take little or no energy to start the process of creation of the products ({numref}`activation-energy`).

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/e/e3/Activation2_updated.svg/1280px-Activation2_updated.svg.png
---
width: 400px
name: activation-energy
figclass: margin-caption
---
Energy used in the course of the glucose reaction with and without external support (catalyst). In either casem the activation energy must be exceeded for the reaction to proceed. Image source: [Activation energy - Wikipedia](https://en.wikipedia.org/wiki/Activation_energy)
```

In other cases, external factors such as catalysts can lower the activation energy to overcome an energy barrier ({numref}`activation-energy`). This requirement adds time for a reaction to reach equilibrium.

<div class="container">
<iframe src="https://www.youtube.com/embed/D0ZyjpAin_Y" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


Consider the dissolution of the mineral gypsum in water:

$$\ce{
CaSO4.2 H2O ->[H2O] Ca^2+ + SO4^2- + 2 H2O
}$$

This reaction is thermodynamically favorable, i.e., $\Delta_{rxn}G^\circ<0$. In order for this reaction to proceed, energy must be spent break chemical bonds within the crystalline structure, followed by diffusion of and away from the crystalline surface. The dissolution will continue until there is a dissolved ion gradient between the crystalline surface and the bulk aqueous solution. Thermodynamics does not explicitly account for these intermediate time-limiting steps.

***Chemical kinetics*** is the study of how rapidly reactions take place. Chemical kinetics provide important information for the elucidation of chemical mechanisms.

Consider a chemical reaction expressed in the following general form:

$$\ce{
Reactants -> Products
}$$
Over the course of this reaction, concentrations of the *Reactants* decrease while concentrations of the *Products* increase. The rates at which the changes in concentrations occur depend on the chemical system in question.

The ***Collision Theory*** of chemical kinetics, the reaction rate is directly proportional to the number of collision at any given time.

```{math}
:label: collisions-rate
\text{Rate} \propto \frac{\text{Number of Collisions}}{\text{Time}}
```
Not every collision between molecules results in a reaction, however, the collision theory gives simple basis to explaining chemical reaction mechanisms. For example, a molecule in motion possesses kinetic energy and when molecules collide, part of this kinetic energy is converted to vibrational energy, which can cause some chemical bonds in molecules and crystalline structures to break. A minimum amount of energy, the activation energy ($\Delta G^\ddagger$), required to initiate a chemical reaction (see {numref}`activation-energy`). Without this minimum amount of energy at impact, a collision will be ineffective or the reaction will occur at a slow rate.

## Reaction Rates

Since kinetics is concerned with the change of chemical concentrations over time, or the ***rates*** of chemical reactions become important. 

Consider the following hypothetical reaction: 

$$\ce{A -> B}$$ 
We can follow the progress of a reaction by monitoring either the decrease in concentration of the reactants or the increase in the concentrations of the products ({numref}`rxn-ab`). 

```{figure} https://saylordotorg.github.io/text_general-chemistry-principles-patterns-and-applications-v1.0/section_18/e5dd3f15f478af1b02121333c365af99.jpg
---
width: 500px
name: rxn-ab
figclass: margin-caption
---
The reaction mixture initially contains only A molecules (purple). With increasing time, the number of A molecules decreases and more B molecules (green) are formed (top). The graph shows the change in the number of A and B molecules in the reaction as a function of time (bottom). Image source: [Reaction Rates and Rate Laws (saylordotorg.github.io)](https://saylordotorg.github.io/text_general-chemistry-principles-patterns-and-applications-v1.0/s18-02-reaction-rates-and-rate-laws.html)
```

We can express the change in chemical concentration of each chemical species as a function of time using the "$\Delta$" notation.

```{math}
:label: reaction-rate
\text{Rate} = -\frac{\Delta [A]}{\Delta t} \quad \text{or} \quad \text{Rate} =  \frac{\Delta [B]}{\Delta t}
```

Here "\[\]" represents concentration of a chemical specie, while the "--" (minus) sign represents decrease in concentration. Rate is always a positive quantity, so when it is expressed as $\Delta [A]/\Delta t$, a minus sign is needed in the rate expression to make the rate positive. When the rate is expressed in terms of the change in a product concentration, no negative sign is needed to make the rate positive because the product concentration increases with time. Rates calculated in this way are average rates over the time period $\Delta t$.


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

Consider a hypothetical chemical reaction, where two reactants *A* and *B* combine to form a product *AB*. 

$$\ce{A + B \rightarrow AB}$$ 

This reactants show a one-to-one stoichiometry. One mole of *A* reacts with one mole of *B* to form the product, $AB$. That is, the reaction rates of *A* and *B* are identical. It also follows that reaction rates are proportional ($\propto$) to concentrations of *A* ($[A]$) and *B* ($[B]$). If the reaction rates are proportional to concentrations of the reactants, it can be summarized that reaction rates for the reaction are proportional to the product of $[A]$ and $[B]$ or $[A]\times [B]$.

```{math}
:label: rate-ab
\text{Rate} \propto [A] \times [B]
```

The proportional sign in Eq. {eq}`rate-ab` can be converted into an "=" sign by incorporating a proportionality constant, $\kappa$. 

```{math}
:label: ratelaw-ab
\text{Rate} = \kappa [A]^1[B]^1
```

This expression where the reaction rate is equated to concentration of reactants are called *rate expressions* or *rate laws*. In this equation, $\kappa$ is called the *rate constant*. By convention, the rate laws are only written for the reactants and each reactant has its own rate constant. Note that the exponent 1 is shown in Eq. {eq}`ratelaw-ab` refers to the number of moles of each reactant in the original chemical reaction. In this case, the ***reaction order*** for *A* and *B* is 1 (both have one mole each in the reaction.) The reaction order refers to the molecularity or the number of molecules of a reactant that are participating in a reaction. The reaction order for the whole reaction is the sum of the reaction order for all reactants. In this case, the reaction order for the above reaction is 2. Equation {eq}`ratelaw-ab` also shows that the rate is dependent on the reactant concentrations.

## Common Rate Expressions

As seen in Eqs. {eq}`rate-ab` and {eq}`ratelaw-ab`, rate laws are in differential forms. They also show how reaction rates are impacted by reactant concentrations. In many chemical reactions reactants follow different trends on how they are consumed. Below we focus on two most common forms of rate expressions encountered in environmental geosciences.

Note that the rate laws are represented in differential forms to generally describe what is occurring on a molecular level during a reaction. The integrated forms of the rate laws are used for determining the reaction order and the value of the rate constant from experimental measurements.

### Zero-order kinetics

In some reactions, the rate of the reaction is independent of the reactant concentration. The rates of these zero-order reactions do not vary with increasing or decreasing reactants concentrations. Zero-order rate expression refers to the rate law where the exponents of all reactants are $0$. The basic expression is:

```{math}
:label: rate-ab-0
\text{Rate} = \kappa [A]^0[B]^0
```
The differential form of this expression can be show as:

```{math}
:label: ratelaw-ab-0
\text{Rate} = - \frac{\Delta [A]}{\Delta t} = \kappa
```

On integrating the above expression we obtain, 

```{math}
:label: ratelaw-a-0
[A]_t  = [A]_0 - \kappa t
```
 This equation is represented in {numref}`zero-order-rxn`.

```{figure} assets/ZeroOrder.png
---
width: 300px
name: zero-order-rxn
figclass: margin-caption
---
The graph of a zeroth-order reaction. The change in concentration of reactant and product with time produces a straight line. 
```

```{dropdown} Example: Zero-order kinetics

1.  Determine the rate constant ($\kappa$) of a zero-order reaction if the initial concentration of substance $A$ is $\pu{1.5 M}$ and after $\pu{120 s}$ the concentration of substance $A$ is $\pu{0.75 M}$.
    **Answer**: $\pu{0.00624 M s−1}$

2.  What is the half-life of substance $A$ if its original concentration     is $\pu{1.2 M}$?
    **Answer**: $\pu{96 s}$

3.  If the original concentration of substance $A$ is reduced to $\pu{1.0 M}$ in the previous problem, does the half-life decrease, increase, or stay the same? If the half-life changes what is the new half-life?     

**Answer**: The half-life decreases when the original concentration is reduced. New half-life is $\pu{80 s}$.
```


### First-order kinetics

A first-order reaction is a reaction that proceeds at a rate that is dependent on the concentration of the reactant. Exponents of all reactants are $1$ in expression below: 

```{math}
:label: rate-1
\text{Rate} = \kappa [A][B]
```

For $A$, 
```{math}
:label: reactant-rate-1
\text{Rate} = - \frac{\Delta [A]}{\Delta t} = \kappa_A [A]
```
On integrating,
```{math}
:label: ratelaw-a-1
[A]_t  = [A]_0 e^{- \kappa_A t}\quad \text{or} \quad \ln \frac{[A]_t}{[A]_0} = - \kappa_A t
```

 This equation is represented in {numref}`first-order-rxn`.

```{figure} assets/FirstOrder.png
---
width: 300px
name: first-order-rxn
figclass: margin-caption
---
Graphs of a first-order reaction. The expected shapes of the curves for plots of reactant concentration versus time (top) and the natural logarithm of reactant concentration versus time (bottom) for a first-order reaction. 
```

```{dropdown} Example: First-order kinetics 

If $\pu{3.0 g}$ of substance $B$ decomposes for $\pu{36 min}$ the mass of unreacted $B$ remaining is found to be $\pu{0.375 g}$. What is the half life of this reaction if it follows first-order kinetics? 

**Answer**: $\pu{12 min}$

```

```{dropdown} Example: First-order kinetics 

The rate of decomposition of diazomethane is shown in the data below.

| Time, $\pu{s}$ | Conc, $\pu{mm of Hg}$ |
|---------|----------------|
| 0       | 284            |
| 100     | 220            |
| 150     | 193            |
| 200     | 170            |
| 250     | 150            |
| 300     | 132            |

Determine (a) the reaction order and (b) the rate constant for this reaction.

**Answer**: On plotting these data in a $x-y$ graph resembling {numref}`first-order-rxn` and therefore, this is a first-order reaction. Plot the $\ln (\text{Conc}) $ vs. $\pu{Time}$ and the slope of this straight line is the rate constant.

```


## Practice Problems

(1) Consider the following reaction, 

$$\ce{4 NO2 + O2 -> 2 N2O5}$$
At a particular time during the reaction, is being consumed at the rate of $\pu{1.3e-3 mol L-1 s-1}$. (a)  At what rate is being consumed? (b) At what rate is being produced? 

**Answer**: (a) $\pu{-3.25e-4mol L-1 s-1}$, (b) $\pu{6.5e-4 mol L-1 s-1}$
 
(2) The solvent methylene chloride ($\ce{CH2Cl2}$) reacts with bisulfide ($\ce{HS-}$) to form dithiomethane ($\ce{CH2(SH)2}$) as shown in this reaction: 

$$\ce{CH2Cl2 + 2 HS- -> CH2(SH)2 + 2 Cl-}$$
This reaction is monitored by measuring the rate of production. If after $\pu{2 min}$, appears at a rate of $\pu{10 mmol L-1 min-1}$, what is the reaction rate at which is being consumed? 

**Answer**: $\pu{-5 mmol L-1 min-1}$

(3) Write the rate expressions and determine the reaction order in the following reactions.

$$
\begin{align}
\ce{
2 A &-> C\\
2 A + B &-> C
}
\end{align}$$
**Answer**: (1) 2, 2 (2) 2, 1, 3

(4) The decomposition of hydrogen peroxide is first order in $\ce{H2O2}$. 

$$\ce{
2 H2O2 -> 2 H2O + O2
}$$
The rate constant for this reaction at $\pu{20 ^\circ C}$ is $\pu{1.8e-5 s-1}$. The starting concentration of is $\pu{0.75 M}$. Determine (a) the concentration of remaining after $\pu{3 h}$.  **Answer**: $\pu{0.62 M}$ and (b) how long it will take for the concentration to drop to $\pu{0.10 M}$. **Answer**: $\pu{31 h}$.

(5) The decomposition of ethane ($\ce{C2H6}$) to methyl radicals ($\ce{.CH3}$) is a first-order reaction with a rate constant of $\pu{5.36e-1 s-1}$ at $\pu{700 ^\circ C}$. Calculate the half-life of this reaction in minutes. 

**Answer**: $\pu{21.5 min}$

(6) Auto-oxidation of $\ce{Fe^2+}$ occurs when exposed to the atmosphere due to the presence of $\ce{O2(g)}$. The table below shows the observed $\ce{Fe^2+}$ oxidation data. Determine (a) the reaction order, (b) the rate constant for this reaction, and (c) the half-life of $\ce{Fe^2+}$.

| Time, $\pu{min}$ | Conc, $\pu{\mu g L-1}$ |
|-----------|----------------------------------|
| 0         | 500                              |
| 10        | 320                              |
| 20        | 200                              |
| 30        | 130                              |
| 40        | 80                               |
| 60        | 35                               |

(7) A researcher has monitored the treatment of an organic pollutant using a naturally-occurring mineral compound. The table below shows the kinetics data. Determine (a) the reaction order, (b) the rate constant for this reaction, and (c) the half-life of pollutant.

| Time, $\pu{h}$ | Conc, $\pu{\mu mol L-1}$ |
|---------|-------------------------|
| 1.5     | 137                     |
| 18      | 98.6                    |
| 42.5    | 68                      |
| 71.5    | 38.4                    |
| 91.5    | 23.7                    |
| 115     | 12.2                    |
| 138.5   | 8.4                     |
