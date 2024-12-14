# 3.3  Application of $K$

## Predicting Direction of a Reaction

$K$ values can be used to predict the direction in which any reaction proceeds spontaneously. First, we must recall how a reaction's reaction quotient ($Q_c$, Eq. {eq}`qc`) is calculated. If $Q_c \ne K_c$, this information can be used to predict the direction the reaction proceeds to reach equilibrium. There are three possibilities (summarized in {numref}`qckc-relation`):

```{table} Relationship between $Q_c$ and $K_c$ and how this information helps predict the flow of a reaction.
:name: qckc-relation
| $Q_c\, \text{vs.}\, K_c$ | $\dfrac{\{\text{Products}\}}{\{\text{Reactants}\}}\, \text{Ratio}$ | For Equilibrium | System Proceeds |
| --- | --- | --- | --- |
| $Q_c < K_c$ | Low | Reactants must create products | Towards products |
| $Q_c = K_c$ |  | Concentrations do not change | At equilibrium |
| $Q_c > K_c$ | High | Products must create reactants | Towards reactants |

```

The example below demonstrates the application of this information.

```{dropdown} Example: $Q_c$ and $K_c$ 
The formation of $\ce{HI(g)}$ from $\ce{H2(g)}$ and $\ce{I2(g)}$ is depicted in the reaction below:

$$\ce{H2(g) + I2(g) <=> 2 HI(g) \qquad $K_c =54.3$ at $\pu{430 ^\circ C}$ 
}$$

If we were to conduct an experiment starting with an initial mixture of $\pu{0.243 M}$ of $\ce{H2(g)}$, $\pu{0.146 M}$  of $\ce{I2(g)}$, and $\pu{1.98 M}$ of $\ce{HI(g)}$ at $\pu{430 ^\circ C}$, is this reaction in equilibrium?

>First, calculate $Q_c$ as follows and compare with $K_c$. 
>
>$$\begin{aligned}
        Q_c &= \frac{[\ce{HI}]^2}{[\ce{H2}][\ce{I2}]}\\
        &= \frac{(1.98)^2}{(0.243)\times (0.146)}\\
        &= 110.5\\
        & \ne K_c
    \end{aligned}
>$$
>
>In the above example, $Q_c>K_c$, the reaction proceeds to the left to reach equilibrium.
```


## Le Châtelier's Principle

As implied in the discussion above, $Q_c$ and $K_c$ in a system could be different, causing the system to be disequilibrium. Likewise, a system can be disturbed from the equilibrium by a change in reaction conditions. In nature, most systems are in such a state and are working towards achieving this equilibrium. Humans intentionally or unintentionally disturb an equilibrium condition towards a goal. An example is the industrial level of production of ammonia ($\ce{NH3}$) by reacting $\ce{N2}$ with $\ce{H2}$ at high $T$ as shown in the following reaction.

$$\ce{N2(g) + 3 H2(g) <=> 2 NH3(g)
}$$

The above reaction is called the Haber-Bosch reaction, which is widely credited with providing humans with crop production that is critical for matching population growth in the twentieth century. In this reaction, the production is often manipulated by increasing one or more reactants or removing the product, causing the reaction to be out of equilibrium. The system then responds by increasing $\ce{NH3(g)}$ production. This is ultimately the goal of this process at an industrial scale - large production of $\ce{NH3(g)}$.

[The Haber process | TED-Ed](https://ed.ted.com/lessons/the-chemical-reaction-that-feeds-the-world-daniel-d-dulek)

<div class="container">
<iframe src="https://www.youtube.com/embed/o1_D4FscMnU" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Le Châtelier's principle addresses the shift in equilibrium when external stress is applied to a system in equilibrium. *When stress is applied to a system at equilibrium, the system will respond by shifting in a direction that minimizes the effect of the stress.* *Stress* can be applied in a variety of ways, including:
1. addition of a reactant or product,
2. removal of a reactant or product,
3. change in volume of the system, resulting in a change in concentration or partial pressure of the reactants and products and
4. change in temperature.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/0402516bd1c563bf706ff9a267c6f19a642c591d
---
name: nh3-production
figclass: margin-caption
---
Commercial ammonia production requires heavy equipment to handle the high temperatures and pressures. This schematic outlines the design of an ammonia plant. Image source: [17.7 Catalysis - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/17-7-catalysis)
```

The system can respond to such change(s) by "shifting" the reaction in a forward or reverse direction, such that the effect of the stress is partially offset as the system reestablishes equilibrium. A shift to the right produces more products by the forward reaction. A shift to the left produces more reactants by the reverse reaction. Using Le Châtelier's principle, we can predict the direction in which an equilibrium will shift, given the applied stress.

```{dropdown} Example: Addition or removal of chemicals 

Consider the Haber-Bosch process at $\pu{700 ^\circ C}$ :

$$\ce{N2(g) + 3 H2(g) <=> 2 NH3(g)
}$$


If the concentrations are $[\ce{N2}] = \pu{2.05 M}$, $[\ce{H2}] = \pu{1.56 M}$, and $[\ce{NH3}] = \pu{1.52 M}$, let's $Q_c$ with $K_c$.

>$$\begin{aligned}
Q_c &= \frac{[\ce{NH3}]^2}{[\ce{N2}][\ce{H2}]^3} = \frac{(1.52)^2}{(2.05)\times(1.56)^3}\\
&= 0.297    = K_c
 \end{aligned}
>$$ 
> Therefore, the system is at equilibrium.
    
>If we "stress" this system by increasing $[\ce{N2}]$ from $\pu{2.05 M}$  to $\pu{3.51 M}$, let's recalculate $Q_c$ 
>
>$$\begin{aligned}
Q_c &= \frac{(1.52)^2}{(3.51)\times(1.56)^3}\\
&= 0.173 \ne K_c
\end{aligned}
>$$ 
>    
>Since $Q_c < K_c$, the reaction proceeds to the right side of the above reaction (see {numref}`qckc-relation`). We can easily predict reaction scenarios involving removing or adding reactants or products.

```


```{dropdown} Example: Changes to volume and pressure 

Consider the following system:

$$\ce{N2O4(g) <=> 2 NO2(g)
}$$

At $\pu{25 ^\circ C}$, $K_c = \pu{4.63e-3}$. If at equilibrium, the concentrations are $[\ce{N2O4}] = \pu{0.643 M}$ and $[\ce{NO2}] = \pu{0.0547 M}$ in a cylinder. If we use a piston to reduce the volume of this cylinder by half ("stress"), the resulting concentrations are doubled to $[\ce{N2O4}] = \pu{1.286 M}$ and $[\ce{NO2}] = \pu{0.1094 M}$. Evaluate this system.

> First, let's calculate $Q_c$. 
>
>$$\begin{aligned}
Q_c &= \frac{[\ce{NO2}]^2}{[\ce{N2O4}]} = \frac{(0.1094)^2}{(1.286)}\\
&= \pu{9.31e-3}    \ne K_c
\end{aligned}
$$ 
>
>Since $Q_c > K_c$, the reaction proceeds to the left side of the above reaction (see {numref}`qckc-relation`).
>
>Note: When there is no difference in the number of moles of gas, changing the volume of the reaction vessel will change the concentrations of the reactant(s) and product(s) in the same proportion - but the system will remain at equilibrium ($Q_c = K_c$).

```


```{dropdown} Example: Changes to temperature 

Changes to $T$ can alter the position of an equilibrium and the equilibrium constant. Consider the following reaction:

$$\ce{N2O4(g) <=> 2 NO2(g)
}$$

>This is an endothermic reaction ($\Delta_{sys}H^\circ{}>0$), so the above reaction can be expressed as:
>
>$$\ce{\text{heat} + N2O4(g) <=> 2 NO2(g)
}$$
>
>In this expression, "heat" is treated as a reactant. If we were to increase $T$ or add "heat", we can see that $Q_c < K_c$ or the reaction will proceed to the right as expected. A similar argument can be made for exothermic reactions.
>
>$T$ increase favors endothermic reactions, while $T$ decrease favors exothermic processes.

```

In cases where $T$ in a system is changed, the resulting new equilibrium constant can be calculated using the van't Hoff equation:

```{math}
:label: vanthoff
\ln \frac{K_2}{K_1} = \frac{\Delta_{rxn}H^\circ}{R} \left(\frac{1}{T_1} - \frac{1}{T_2}\right)
```


## Determining Concentrations of Reactants

If we know the $K$ of a reaction, we can calculate the concentrations in an equilibrium mixture from the initial reactant concentrations. We can set up "ICE" tables to make this calculation methodical.

```{admonition} Calculating concentrations of reactants and products at equilibrium
The following steps summarize the process involved:
1. Construct an equilibrium table and fill in the initial concentrations (including any that are zero).
2. Use initial concentrations to calculate the reaction quotient, $Q_c$, and compare $Q_c$ to $K_c$ to determine the direction in which the reaction will proceed.
3. Define $x$ as the amount of a particular species consumed, and use the reaction's stoichiometry to define (in terms of $x$) the amount of other species consumed or produced.
4. For each species in the equilibrium, add the change in concentration to the initial concentration to get the equilibrium concentration.
5. Use the equilibrium concentrations and the equilibrium expression to solve for $x$.
6. Using the calculated value of $x$, determine the concentrations of all species at equilibrium.
7. Check your work by substituting the calculated equilibrium concentrations into the equilibrium expression. The result should be very close to the $K$ stated in the problem.

>See the example below to see how this method is used in practice.
```

```{dropdown} Example: Calculating concentrations at equilibrium 

$K_c$ for the following reaction is $54.3$ at $\pu{430 ^\circ C}$

$$\ce{H2(g) + I2(g) <=> 2 HI(g)
}$$

Let's calculate concentrations of all components at equilibrium if we start with $\pu{0.24 M}$ of both $\ce{H2(g)}$ and $\ce{I2(g)}$.

>We cannot determine how $Q_c$ correlates with $K_c$ because no products have been created yet.  Since the reactants had just been added, the reaction proceeded to the right to create products.
>
>In the above system, let's insert the starting concentrations we know into the equilibrium table below. We define the change in concentration of one of the reactants as $x$. Because there is no product at the start of the reaction, the reactant concentration must decrease; this reaction must proceed in the forward direction to reach equilibrium. According to the stoichiometry of the chemical reaction, the reactant concentrations will decrease by the same amount ($x$), and the product concentration will increase by twice ($2x$). Combining the initial concentration and the change in concentration for each species, we get expressions (in terms of $x$) for the equilibrium concentrations:
>
>|    | $\ce{H2(g)}$ | $+$ | $\ce{I2(g)}$ | $\rightleftharpoons$ | $2\ce{HI(g)}$ |
>|--------|------|-----|----------|------------|---------|
>| **I**nitial, M  | $0.24$   |     | $0.24$   |   | $0$ |
>| **C**hange, M  | $-x$ |     | $-x$  |   | $+2x$  |
>| **E**quilibrium, M | $(0.24-x)$  |   | $(0.24-x)$ |   | $(0+2x)$  |
>
>The above equilibrium setup table is called the ***ICE Table***.
>
>From the ICE table, we can write $K_c$ expression and substitute equilibrium concentrations
>
>$$K_c = \frac{[\ce{HI}(g)]^2}{[\ce{H2(g)}][\ce{I2(g)}]} = \frac{(0+2x)^2}{(0.24-x)(0.24-x)} = 54.3$$
>
>The above expression can be rearranged into a linear quadratic form:
>
>$$50.3 x^2 - 26.1x + 3.13 = 0$$ 
>
>Solutions for a generic quadratic equation, $ax^2 + bx + c = 0$: 
>
>$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$ 
>
>To calculate $x$, substitute $a=50.3$, $b=-26.1$, and $c=3.13$ in above expression and we obtain $x_1 = 0.189$ and $x_2 = 0.329$. Which of these two $x$ values is correct? We can substitute each $x$ value into the equilibrium concentration expressions and determine the correct value.
>
>|         |   |           |   | $x_1$ | $x_2$ |
>|---------|:---:|-----------|:---:|---------: |---------: |
>| $\ce{H2}$ | = | $ 0.24-x$ | = | $0.051 $  | $-0.089$  |
>| $\ce{I2}$ | = | $ 0.24-x$ | = | $0.051$   | $-0.089$  |
>| $\ce{HI}$ | = | $ 2x$     | = | $0.378$   | $-0.658$  |
>
>Substituting $x_1$ in the above table resulted in all positive equilibrium concentrations, while substituting $x_2$ resulted in negative equilibrium concentrations. Since negative concentrations are not possible, the correct value for $x_1 = 0.189$.
>
>As a final check, let's re-substitute equilibrium concentrations in the $K$ expression.
>
>$$
K_c = \frac{[\ce{HI}(g)]^2}{[\ce{H2(g)}][\ce{I2(g)}]} = \frac{(0.378)^2}{(0.051)\times(0.051)} = 54.9 \approx 54.3
>$$
>
>The slight discrepancy in the final calculation can be attributed to rounding.
```

