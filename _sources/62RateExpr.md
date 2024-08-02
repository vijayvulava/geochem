# 6.2  Common Rate Expressions

As seen in Eqs. {eq}`rate-ab` and {eq}`ratelaw-ab`, rate laws are in differential forms. They also show how reaction rates are impacted by reactant concentrations. In many chemical reactions reactants follow different trends on how they are consumed. Below we focus on two most common forms of rate expressions encountered in environmental geosciences.

Note that the rate laws are represented in differential forms to generally describe what is occurring on a molecular level during a reaction. The integrated forms of the rate laws are used for determining the reaction order and the value of the rate constant from experimental measurements.

## Zero-order kinetics

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


## First-order kinetics

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
