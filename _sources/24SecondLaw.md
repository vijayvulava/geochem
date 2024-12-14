# 2.4 The Second Law

The first law of thermodynamics addresses energy exchange between a system and its surroundings. But, it does not address *if* a reaction or process will occur under a given set of conditions ($P$, $T$, concentration, etc.) That is, it does not address if the chemical process is *spontaneous*. The second law introduces a state function called entropy ($S$) to address spontaneity.

## Spontaneous processes

Spontaneous processes are defined as processes that occur under a specific set of conditions. Unlike in common parlance, spontaneous processes do not indicate "fast" or suddenly occurring reactions. Reaction rates are not addressed in thermodynamics, where all state functions are compared to systems assumed to already be at equilibrium under a given set of conditions.

```{dropdown} Example: Spontaneous processes

1. Water flows downhill
2. A lump of sugar dissolves in hot coffee
3. At $\pu{1 atm}$, $\ce{H2O(l)}$ freezes below $\pu{0 ^\circ C}$
4. $\ce{Fe}$ exposed to $\ce{O2}$ and $\ce{H2O}$ at $\pu{1 atm}$ forms $\ce{Fe2O3}$ (rust)

```

Processes that result in a decrease in the energy of a system often are spontaneous -- i.e., these processes reach a most stable lower energy level. In such reactions, heat is given off to the surroundings (exothermic processes). However, endothermic processes can also be spontaneous.

```{dropdown} Example: Spontaneous chemical processes 

All reactions below occur spontaneously at $\pu{25 ^\circ C}$. 

>| Reaction | $\Delta_{rxn}H^\circ$,  $\pu{kJ mol-1}$ |
>| --- | ---: |
>| $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$  | $-890.4$ |
>| $\ce{H+ (aq) + OH- (aq) <=> H2O(l) }$ | $-56.2$ |
>| $\ce{H2O(s) -> H2O(l)}$ | $6.01$ |
>| $\ce{NH4NO3(s) ->[H2O] NH4+ (aq) + NO3- (aq)}$ | $25.0$ |
>
>It is also evident that the first two reactions are exothermic, while the last two are endothermic.
```

Because $\Delta_{rxn}H^\circ$ is not adequate to predict the spontaneity of the process, we have to define new terms such as entropy and Gibbs free energy.

## Entropy

Imagine two well-insulated bottles somewhere in the universe ({numref}`spontaneous`) one side of the bottle was filled with a gas, and the other side contained a vacuum, separated by a valve. If this valve were to be removed, you would intuitively know that gas would enter the side under vacuum spontaneously. We have neither added energy to nor taken energy from the system; hence, the first law says nothing about this process. Nor did opening the valve *cause* the reaction. It is apparent from the observation that if we reclose the valve, the gas will not return to the original side. This phenomenon suggests there is something very fundamental and universal about this. This process is addressed in the second law of thermodynamics.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/9eafa2a59a63c98a307979ec929c1e6ae7d47898
---
name: spontaneous
figclass: margin-caption
---
An isolated system consists of an ideal gas in one flask connected by a valve to a second flask containing a vacuum. Once the valve is opened, the gas spontaneously becomes evenly distributed between the flasks. Image source: [12.1 Spontaneity - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/12-1-spontaneity)
```

A system's entropy ($S$) measures how spread or dispersed the system's energy is. The simplest interpretation of this is how spread out a system's energy is in space. Because the gas molecules initially confined to one side of the container are moving, they possess motional energy. When the barrier is removed, the motional energy of molecules will cause the molecules to spread out and occupy a larger volume. This dispersal of the system's motional energy causes an increase in the system's entropy. Just as an exothermic process favors spontaneity, spontaneity is also favored by an increase in the system's entropy. Whether it is the enthalpy change, the entropy change, or both, something must favor spontaneity for a process to be spontaneous.

[What is entropy? - Jeff Phillips | TED-Ed](https://ed.ted.com/lessons/what-is-entropy-jeff-phillips)

<div class="container">
<iframe src="https://www.youtube.com/embed/YM-uykVfq_E" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Entropy is an extensive property (see {numref}`state-properties`) and has the units $\pu{J K−1}$. Molar entropy is entropy normalized to the amount (moles) of a substance ($\pu{J K-1 mol−1}$) and is, therefore, an intensive property. Mathematically, $S$ is the heat absorbed ($q$) in a reversible reaction in a closed system divided by absolute temperature ($T$, an intensive property). 

```{math}
:label: entropy

\delta S = \frac{\delta q}{T}
```

 Note that $\delta$ indicates *a small change*. As seen in the above example, most reactions that occur in nature are irreversible. The above equation is rewritten as
 
```{math}
:label: entropy-t

\delta S > \frac{\delta q}{T}
```

## Standard entropy, $S^\circ$ 

It is the absolute entropy of a substance at $\pu{1 atm}$ (they are a function of temperature, but standard values are expressed at $\pu{25 ^\circ C}$. The units of entropy are $\pu{J K-1 mol−1}$. The $S^\circ$ of substances (elements and compounds) are always positive (i.e., $S^\circ > 0$), even for elements in their standard states.

````{margin}
The CRC Handbook of Physics and Chemistry is a good reference for obtaining $S^\circ$ for most chemicals. The online version is available at [Standard Thermodynamic Properties of Chemical Substances (chemnetbase.com)](https://hbcp.chemnetbase.com/faces/documents/05_02/05_02_0001.xhtml) 
````

```{admonition} General trends in entropy ($S^\circ$) 

The Entropy ($S^\circ$) of selected substances is shown below. Observe the trends in the table.

| Substance | $S,\ \pu{J K-1 mol−1}$ | 
| --- | ---: |
| $\ce{H2O(l)}$ | $69.9$ | 
| $\ce{H2O(g)}$ | $188.7$ |
| $\ce{Na(s)}$ | $51.05$ |
| $\ce{Na(l)}$ | $57.56$ |
| $\ce{Na(g)}$ | $153.7$ |
| $\ce{He(g)}$ | $126.1$ |
| $\ce{Ne(g)}$ | $146.2$ |
| $\ce{C}$ (diamond) | $2.4$ |
| $\ce{C}$ (graphite) | $5.69$ |
| $\ce{O2(g)}$ | $205.0$ |
| $\ce{O3(g)}$ | $237.6$ |
| $\ce{F2(g)}$ | $203.34$ |
| $\ce{Au(s)}$ | $47.7$ |
| $\ce{Hg(l)}$ | $77.4$ |
     
The table of data shown above highlights the following trends:
1. For a given substance, it increases in the following order: $S_\text{gas} \gg S_\text{liquid}> S_\text{solid}$. This can be explained by greater molecular motion in gases and liquids than in solids (see {numref}`entropy-substance-fig`).
2. For two monatomic species, the one with the larger molar mass has the greater $S^\circ$. E.g., compare $\ce{He}$ vs. $\ce{Ne}$.
3. For two substances in the same phase and with similar molar masses, the substance with the more complex molecular structure has the greater $S^\circ$. The more complex a molecular structure, the more different types of motion the molecule can exhibit. E.g., $\ce{O2(g)}$ vs. $\ce{O3(g)}$.
4. When an element exists in two or more allotropic forms (e.g., graphite vs. diamond), the form where the atoms are more mobile has greater entropy. In diamonds, the carbon atoms occupy fixed positions in a three-dimensional array. In graphite, although the carbon atoms occupy fixed positions within the two-dimensional sheets, the sheets are free to move relative to one another, which increases the mobility and, therefore, the total number of possible arrangements of atoms within the solid.
```

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/f3f96b7f897d7cd062c326b3e451634f6c3d5a20
---
name: entropy-substance-fig
figclass: margin-caption
---
The entropy of a substance increases ($S^\circ > 0$) as it transforms from a relatively ordered solid to a less-ordered liquid and then to a still less-ordered gas. The entropy decreases ($S^\circ < 0$) as the substance transforms from a gas to a liquid to a solid. Image source: [12.2 Entropy - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/12-2-entropy)
```

The entropy of a system ($\Delta _{sys} S^\circ$) can be calculated similarly to the mathematical procedure for calculating $\Delta _{sys} H^\circ$.

```{math}
:label: s_sys

\Delta _{sys} S^\circ  = \sum \Delta_{prod}S - \sum \Delta_{reac}S
```


```{dropdown} Example: Calculating $\Delta _{sys} S^\circ$ of a system 

Calculate the $\Delta _{sys} S^\circ$ of the following reaction at $\pu{25 ^\circ C}$

$$
\ce{CaCO3(s) -> CaO(s) + CO2(g)}
$$

>$S^\circ$ of these substances can be looked up in the CRC Thermodynamic Data Tables: 
>$S_{\ce{CaCO3 (s)}} = \pu{92.9 J K-1 mol-1}$, $S_{\ce{CaO (s)}} = \pu{39.8 J K-1 mol-1}$, and $S_{\ce{CO2 (g)}} = \pu{213.6 J K-1 mol-1}$. 
>
>$$
\begin{align*}
\Delta _{sys} S^\circ  &= [S_{\ce{CaO (s)}} + S_{\ce{CO2 (g)}}] - [S_{\ce{CaCO3 (s)}}]\\
&= [\pu{39.8 J K-1 mol-1} + \pu{213.6 J K-1 mol-1}] - [\pu{92.9 J K-1 mol-1}]\\
&= \pu{160.5 J K-1 mol-1}
\end{align*}
>$$
```


## Qualitative prediction of $\Delta _{sys}S^\circ$

Equation {eq}`s_sys` helps us calculate $\Delta _{sys}S^\circ$ for any process where $S^\circ$ of all reactants and products are known. But, we can qualitatively predict the sign of $\Delta _{sys}S^\circ$ by evaluating the chemical process.

```{admonition} Processes that lead to an increase in $S^\circ$ of a system

1. Melting - when solids melt, molecules have higher energy and are more mobile. They go from being in fixed positions in the solid to being free to move about in the liquid.
2. Vaporization or sublimation - a dramatic increase in energy/mobility and the number of possible arrangements of a system's molecules when the molecules go from a condensed phase to the gas phase.
3. Temperature increase - the energy of the system's molecules increases due to increased average kinetic energy.
4. Reactions that lead to the formation of gases increase entropy, as the entropy of a substance in the gaseous state is always much higher than in the liquid or solid states. Therefore, a reaction that produces more gas molecules contributes to a rise in the system's entropy.
5. Dissolving a substance leads to the spreading of molecules (and thus, the system's energy) over a larger volume and increased entropy. However, this principle does not hold for multiply charged ions in water, as these ions draw water molecules (hydration) to their surfaces, which results in decreased entropy.
```

```{dropdown} Example: Predicting the sign of $\Delta _{sys}S^\circ$ a system 

Let's predict sign of $\Delta _{sys}S^\circ$ for the following systems using the rules outlined above:

1. Decomposition of $\ce{CaCO3(s)}$ to $\ce{CaO(s)}$ and $\ce{CO2(g)}$: 

>$+$ or $\Delta _{sys}S^\circ >0$

2. Heating bromine vapor from $\pu{45 ^\circ C}$ to $\pu{80 ^\circ C}$: 

>$+$ or $\Delta _{sys}S^\circ >0$

3. Condensation of water vapor on a cold surface: 

>$-$ or $\Delta _{sys}S^\circ <0$

4. Reaction of $\ce{NH3(g)}$ and $\ce{HCl(g)}$ to give $\ce{NH4Cl(s)}$: 

>$-$ or $\Delta _{sys}S^\circ <0$

5. Dissolution of sugar in water: 

>$+$ or $\Delta _{sys}S^\circ >0$
```


## $S^\circ$ changes in the universe

Every system we study is part of the universe. We call the environment that exists outside the system the surroundings. Together, the system and its surroundings make up the universe. The transfer of energy from the system to its surroundings was addressed in the first law. We can also describe entropy changes in the surroundings based on our understanding of entropy. To correctly predict if a system is spontaneous, we must address entropy change in the surroundings.

Consider melting an ice cube at room temperature (endothermic process). Because we can expect an ice cube to melt spontaneously, we would expect $\Delta _{sys} S^\circ  >0$ (melting of a solid). Consequent to this melting of ice, the air in the room becomes cooler, causing a decrease in entropy of the surrounding ($\Delta _{surr}S^\circ <0$). Now consider the opposite process of a cup of boiling water placed at room temperature (exothermic process). Because the water in the cup is cooling, $\Delta _{sys} S^\circ  >0$ and since the surroundings are warmer than before, $\Delta _{surr}S^\circ >0$.

Now, let's examine the combustion of graphite ($\ce{C}$) in the same room as above. This process would result in the formation of $\ce{CO2(g)}$ and heat (exothermic process). Though this reaction is producing a gas ($\Delta _{sys} S^\circ  >0$), it is an exothermic reaction resulting in $\Delta _{surr}S^\circ >0$.

Therefore, in exothermic processes, heat transferred from the system to the surroundings increases the temperature of the molecules in the surroundings, causing the entropy of the surroundings. Conversely, in endothermic processes, heat is transferred from the surroundings to the system, decreasing the entropy of the surroundings. There is a clear correlation between $\Delta _{sys} H^\circ$, $\Delta _{surr}S^\circ$, and $T$ in the system (see Eq. {eq}`entropy`): 

```{math}
:label: s-t

\begin{aligned}
   \Delta _{surr}S^\circ &\propto \Delta _{sys} H^\circ  \\
    \Delta _{surr}S^\circ &\propto \frac{1}{T}
\end{aligned}
```


The negative sign refers to an exothermic process. In endothermic processes, the signs would be reversed. Combining the above two expressions, we have

```{math}
:label: s_surr

\Delta _{surr}S^\circ = - \frac{\Delta _{sys} H^\circ}{T}
```


## Second Law - Definition

It was clear from the above discussion that both systems and surroundings can change entropy during a chemical or physical process. These changes can be summarized as:

```{math}
:label: secondlaw

\Delta _{universe} S^\circ  = \Delta _{sys} S^\circ  + \Delta _{surr}S^\circ
```

The second law of thermodynamics defines that *increases spontaneously and remains unchanged at equilibrium.* This law is summarized in {numref}`s-univ` 

```{table} $\Delta _{univ} S^\circ$ and spontaneity of processes in systems.
:name: s-univ
| $\Delta _{univ} S^\circ$ condition | Reaction condition |
| :---: | --- |
| $\Delta _{univ} S^\circ  >0$ | Reaction is spontaneous   |
| $\Delta _{univ} S^\circ  =0$ | Reaction is at equilibrium |
| $\Delta _{univ} S^\circ  <0$ | Reaction is nonspontaneous  |
```

Equations {eq}`s_surr` and {eq}`secondlaw` can be combined to focus on the system properties as follows:

```{math}
:label: secondlaw-sys

\Delta _{universe} S^\circ = \Delta _{sys} S^\circ - \frac{\Delta _{sys} H^\circ}{T}
```

We can now use Eq. {eq}`secondlaw-sys` to determine if a chemical process occurs spontaneously.

```{dropdown} Example: Determining spontaneity of system 

Consider the synthesis of ammonia ($\ce{NH3(g)}$) at $\pu{25 ^\circ C}$ ($=\pu{298 K}$):

$$
\ce{N2(g) + 3 H2(g) -> 2 NH3(g)}
$$

Using thermodynamic data, we can determine that $\Delta _{sys} H^\circ = \pu{-96.2 kJ mol-1}$ and $\Delta _{sys} S^\circ = \pu{-199 J mol-1 K-1}$. 

>Let's see if the synthesis of $\ce{NH3(g)}$ is spontaneous. Substitute given data into Eq. {eq}`secondlaw-sys` and adjust units for consistency.
>
>$$
\begin{aligned}
\Delta _{universe} S^\circ  &= \pu{-199 J K-1 mol-1} - \frac{\pu{-96.2 J K-1 mol-1} \times \pu{1000 J K-1 mol-1}}{\pu{298 K}}\\
&= \pu{-199 J K-1 mol-1} + \pu{323 J K-1 mol-1}\\
&= \pu{124 J K-1 mol-1}
\end{aligned}
>$$ 
>
>Since $\Delta _{universe} S^\circ >0$, this process is spontaneous.
```

