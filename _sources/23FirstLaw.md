# 2.3  The First Law

The first law states that ***energy is conserved***, in other words, energy can be converted from one form to another and can neither be created nor destroyed. Any change in the heat of the system or work done by the system must be accounted for in the internal energy of the system. 

```{math}
:label: FirstLaw

\Delta_{sys}E^\circ = q + w
```

In Eq {eq}`FirstLaw`, $\Delta_{sys}E^\circ$ is the differential change in the internal energy of the system, $q$ is the heat added or removed from the system, and $w$ is the work done on or by the system. By convention, $q$ is positive for an endothermic process and negative for an exothermic process, and $w$ is positive for work done on the system by the surroundings and negative for work done by the system on the surroundings.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/68b9d7102438342c6cf948437ecbe44f09267984
---
name: exo-endo
figclass: margin-caption
---
In a calorimetric determination, either (a) an exothermic process occurs and heat, $q<0$, indicating that thermal energy is transferred from the system to its surroundings, or (b) an endothermic process occurs and heat, $q>0$, indicating that thermal energy is transferred from the surroundings to the system. Image source: [9.2 Calorimetry - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/9-2-calorimetry)
```

If a chemical reaction occurred in a sealed container (e.g., a combustion reaction) and the product of the reaction were creation of a new products, this would increase the volume and the pressure. Instead of a sealed container, if this reaction occurred in a container that had a movable piston that allowed the volume to adjust ($\Delta V$), the pressure would remain constant. Therefore, the chemical reaction is causing mechanical work to occur in that system. Specifically, this type of work is called pressure-volume ($PV$) work. The amount of work done by such a process is given by 

```{math}
:label: PV

w = -P\Delta V
```

In Eq {eq}`PV`  $P$ is the external, opposing pressure and $\Delta V$ is the change in the volume of the container as the result of the piston being pushed upward. The negative sign in Eq {eq}`PV`  accounts for an increase in volume resulting in a negative value for $w$. At constant $V$, ($\Delta V = 0$), $q_V = _{sys}{E}$. 

This condition is not practical as volume is not constant. Rather, in near-Earth's surface systems, we can assume $P$ to be constant resulting in $q_P$. We can now combine Eqs {eq}`FirstLaw` and {eq}`PV` as follows:

```{math}
:label: EnergyWork

\Delta_{sys}{E} = q_P- P\Delta V
```


## Enthalpy

Enthalpy is state function derived from rearranging Eq {eq}`EnergyWork` as follows:

```{math}
:label: Enthalpy

q_P= \Delta_{sys}{E} + P\Delta V
```

The variable $q_P$ in Eq {eq}`Enthalpy` is called enthalpy ($\Delta H^\circ$) and is equal to the heat flow when processes occur at constant $P$ and the only work done is pressure-volume work. The assumption of constant $P$ is acceptable for Earth's near surface environments, where most systems can be considered to be open. $\Delta H^\circ$ is a state function and accounts for both the internal energy ($\Delta _{sys}E^\circ$) and work ($w$) done on or by the system. It quantifies the heat flow into or out of the system at constant pressure ($P$). Enthalpy has the unit of $\pu{kJ}$, while molar enthalpy has the units of $\pu{ kJ mol−1}$. In a chemical reaction, ($\Delta _{rxn}H^\circ$) accounts for $\Delta _{prod}H^\circ$ (products in a reaction) and $\Delta _{reac}H^\circ$ (reactants in a reaction) as shown below:

```{math}
:label: H_rxn

\Delta_{rxn}H^\circ = \Sigma \Delta_{prod}H^\circ - \Sigma \Delta_{reac}H^\circ
```

$\Delta _{rxn}H^\circ$ can be used to determine if the system ($sys$) gains or loses heat. This value can be positive or negative (units: $\pu{kJ mol-1}$) and needs to be applied to chemical reaction that represents the system.

When $\Delta_{rxn}H^\circ <0$, ($\Delta_{prod}H^\circ < \Delta_{reac}H^\circ$), this implies there is more internal energy bound within the reactants and that portion of this energy is now contained within the products while the rest is released into the surroundings. That is, the excess energy is release into the surroundings ($surr$). Such systems are called ***exothermic*** systems.

```{dropdown} Example: Exothermic reactions 

Virtually any combustion reaction is an exothermic reaction as heat is released into the surroundings. Hydrogen gas explosively reacts with oxygen to form water molecules as shown in:

$$
\ce{2 H2(g) + O2(g) -> 2 H2O(l) + \text{heat}}
$$

Heat released into the surroundings is "product" of this reactions can be quantified if we know exactly how much internal energy makes up each of the chemical species.
```

In the scenarios where $\Delta_{rxn}H^\circ >0$, ($\Delta_{prod}H^\circ > \Delta_{reac}H^\circ$),  there is more internal energy in the products than in the reactants. The system has to adjust for the imbalance in the energy by absorbing energy from the surroundings. Such systems are called ***endothermic*** systems.

```{dropdown} Example: Endothermic reactions 

Heating of liquid water from an external heat source (stove) causes water to evaporate or turn into vapor phase water. This can be represented as:

$$
\ce{H2O(l) + \text{heat} -> H2O(g)}
$$

Heat energy is a "reactant" and is required to make this reaction possible.
```

Absolute enthalpies of chemical entities are difficult to measure. These values depend on the chemical composition of the chemical entity, types of bonds involved and system conditions (functions such as $V$, $P$, $T$, etc.). Hence, $\Delta$ term is used before $H$ is used to denote that enthalpies of a chemical entity as measured relative to a standard state. The reference point for all enthalpy expressions is called the standard enthalpy of formation ($\Delta_f H^\circ$), which is defined as the heat change that results when $\pu{1 mol}$ of a compound is formed from its constituent elements in their standard states. ***Standard states*** refer to the most stable form of an element under standard conditions, meaning at ordinary atmospheric pressure. E.g., oxygen can exist as as the most stable form at ordinary atmospheric pressure. Although the standard state does not specify a temperature, we will always use ($\Delta_f H^\circ$) values measured at $\pu{25 ^\circ C}$. 

````{margin}
The CRC Handbook of Physics and Chemistry is a good reference obtaining $\Delta_f H^\circ$ for most chemicals. The online version is available at [Standard Thermodynamic Properties of Chemical Substances (chemnetbase.com)](https://hbcp.chemnetbase.com/faces/documents/05_02/05_02_0001.xhtml)
````

```{dropdown} Example: Determining enthalpy of a reaction

Let's determine if the following reaction gain heat from or lose heat to the surroundings.

$$
\begin{align*}
\ce{
2 H2(g) + O2(g) &-> 2 H2O(g)\\
H2O(l) &-> H2O(g)
}
\end{align*}
$$

First, we need to lookup $\Delta_f H^\circ$ for all chemical species in thermodynamic data tables

| Chemical | $\Delta_f H^\circ$,  $\pu{kJ mol-1}$ | Chemical | $\Delta_f H^\circ$,  $\pu{kJ mol-1}$ |
| --- | ---: | --- | ---: |
| $\ce{O2 (g)}$  | $0$ | $\ce{H2O (g)}$ | $-241.8$ |
| $\ce{H2 (g)}$ | $0$ | $\ce{H2O (l)}$ | $-285.8$ |
|  |  | $\ce{H2O (s)}$ | $-291.8$|


Next we need to calculate $\Delta_{rxn} H^\circ$ for each reaction. 

$$
\begin{align*}
\Delta_{rxn} H^\circ &= [2(-241.8)] - [(2(0) + (0)] = \pu{-483.6 kJ mol-1}\\
\Delta_{rxn} H^\circ &= [(-241.8)] - [(-285.8)] = \pu{+44.0 kJ mol-1}
\end{align*}
$$

Since $\Delta_{rxn}H^\circ <0$, the first reaction is exothermic and $\Delta_{rxn}H^\circ >0$, the second reaction is endothermic.
```

Since we are working with thermochemical systems, where heat is released or captured during a reaction, the following guidelines will be helpful in interpreting, writing, and manipulating thermochemical reactions.

```{admonition} Rules for working with thermochemical data

1. All calculations have to be performed on balanced chemical reactions.
2. Always specify physical states of matter of all reactants and products.
3. $\Delta_{rxn}H^\circ$ means that this is the enthalpy change per mole of the reaction (or process) as it is written and does not refer to individual chemical species or the number of moles involved in each reaction.
4. If both sides of a reaction are multiplied by $n$, then $\Delta_{rxn}H^\circ$ must be multiplied by $n$.
5. If reaction is reversed, $\Delta_{rxn}H^\circ$ magnitude remains same, but sign changes.
```


```{dropdown} Example: Application of thermochemical rules 

Let's calculate the $\Delta_{rxn}H^\circ$ for the following chemical reactions:

$$
\begin{align}
\ce{
4 H2(g) + 2 O2(g) &-> 4 H2O(g) \\
H2O(g) &-> H2O(l)
}
\end{align}
$$

If we used $\Delta_{f}H^\circ$ from the table in the previous example, we can calculate $\Delta_{rxn}H^\circ$ as $\pu{−967.2 kJ mol-1}$ and  $\pu{−44.0 kJ mol-1}$, respectively in these reactions.
```

```{dropdown} Example: Application of thermochemistry and mass balance 

Let's calculate the heat evolved when $\pu{75 g}$ of $\ce{SO2(g)}$ is oxidized to $\ce{SO3 (g)}$ as shown:

$$
\ce{SO2(g) + 1/2 O2(g) -> SO3(g)}
$$

$\Delta_{rxn}H^\circ = \pu{-99.1 kJ mol-1}$

According to this reaction, $\pu{1 mole}$ of $\ce{SO2(g)}$ is oxidized to $\pu{1 mole}$ of $\ce{SO3(g)}$ resulting in $\Delta_{rxn}H^\circ = \pu{-99.1 kJ mol-1}$ (release of energy into surroundings) 

The molar mass of $\ce{SO2(g)}$ is $\pu{64 g}$ ($\pu{1 mol} = \pu{64 g}$) or, in other words, $\pu{64 g}$ of $\ce{SO2(g)}$ results in $\Delta_{rxn}H^\circ = \pu{-99.1 kJ mol-1}$. 

Therefore, $\pu{75 g}$ of $\ce{SO2(g)}$ results in:

$$
\pu{75 g}\, \ce{SO2} \times \dfrac{\pu{1 mol}\, \ce{SO2}}{\pu{64 g}\, \ce{SO2}} = \pu{1.2 mol}\, \ce{SO2}
$$

$\therefore \Delta_\ce{SO2} H^\circ = \pu{1.2 mol}\times (\pu{-99.1 kJ mol-1}) = \pu{116 kJ}$.
```

## Hess's Law

Because $\Delta_{rxn}H^\circ$ is a state function, the change in enthalpy that occurs when reactants are converted to products in a reaction is the same whether the reaction takes place in one step or in a series of steps. This observation is called ***Hess's law***. This is an application of the concept that in thermodynamics, the system *does not care* how many steps (individual reactions) were required to reach equilibrium -- just the final reaction.

Another practical concern is that many compounds cannot be synthesized from their elements directly. In some cases, the reaction proceeds too slowly, or side reactions produce substances other than the desired compound. In these cases, $\Delta_f H^\circ$ can be determined by an indirect approach, using Hess's law.

```{dropdown} Example: Hess's law 
**Example 1**

Combustion of graphite ($\ce{C}$) to can occur as follows:

$$ \ce{
C(s) + 1/2 O2(g) -> CO(g)}
$$

This reaction can be created by combining two separate reactions shown below:

| Reaction | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
| --- | ---: |
| $\ce{CO2(g) -> CO(g) + 1/2 O2(g)}$ | $-283.0$ |
| $\ce{C(s) + O2(g)  -> CO2(g)}$ | $-393.5$ |


We can add balanced chemical equations just as we can add algebraic equalities, canceling identical items on opposite sides of the equation arrow. In order to combine the above two reactions, we need to reverse the first reaction as follows to get common terms on opposite sides. Also, remember to change sign of $\Delta_{rxn}H^\circ$ when reversing reactions.

| Reaction | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
| --- | ---: |
| $\ce{CO2(g) -> CO(g) + 1/2 O2(g) }$  | $-283.0$ |
| $\ce{C(s) + O2(g)  -> CO2(g)}$ | $-393.5$ |
| --- | --- |
| $\ce{C(s) + 1/2 O2(g)  -> CO(g)}$ | $-110.5$ |


Therefore, $\Delta_{rxn}H^\circ = \pu{-110.5 kJ mol-1}$ for the final reaction.

**Example 2**

Let's determine $\Delta_{rxn}H^\circ$ for the reaction below using $\Delta_{rxn}H^\circ$ data for the following reactions:

$$ \ce{
C(s) + 2 H2(g) + 1/2 O2(g) -> CH3OH(l)
}$$

| Reaction | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
| --- | ---: |
| $\ce{CH3OH(l) + 3/2 O2(g) -> CO2(g) + 2 H2O(l)}$  | $-726.4$ |
| $\ce{C(s) + O2(g)  -> CO2(g)}$ | $-393.5$ |
| $\ce{H2(g) + 1/2 O2(g) -> H2O(l)}$ | $-285.8$ |

The following changes were made to each of the above reactions to get common reactants and products to match our required reaction:

1. Rxn 1: Reversed, sign of $\Delta_{rxn}H^\circ$ changed
2. Rxn 2: No change
3. Rxn 3: Multiplied by 2, including $\Delta_{rxn}H^\circ$ value


| Reaction | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
| --- | ---: |
| $\ce{CO2(g) + 2 H2O(l) -> CH3OH(l) + 3/2 O2(g) }$ | $726.4$ |
| $\ce{C(s) + O2(g)  -> CO2(g)}$ | $-393.5$ |
| $\ce{2 H2(g) + O2(g) -> 2 H2O(l)}$ | $-571.6$ |
| --- | --- |
| $\ce{C(s) + 2 H2 (g) + 1/2 O2(g) -> CH3OH(l)}$ | $-238.7$ |


Therefore, $\Delta_{rxn}H^\circ = \pu{-238.7 kJ mol-1}$ for the final reaction.

```
