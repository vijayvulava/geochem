# 8.2 Organic Chemicals in the Environment

## Aqueous Solubility

This fundamental property refers to the saturated solubility of the organic compound in water and is shown as $C_w^{sat}$, and typical units are $\pu{mol L-1}$ and $\pu{\mu g L-1}$. For typical organic pollutants, $C_w^{sat}$ is usually very low. For example, a relatively high value might be for benzene ($\pu{2.2e-2 mol L-1}$), and a relatively low value might be for decachlorobiphenyl ($\pu{e-10 mol L-1}$). $C_w^{sat}$ changes with temperature but not as much as vapor pressure. There are several thermodynamics-based methods to predict the water solubility of organic compounds.

The aqueous solubility of organic chemicals is generally higher for smaller molecules or molecules that are more polar and, hence, can form an attraction with the polar water molecules. Many, but not all, ionic compounds (salts) are very water-soluble, as their ions can interact strongly with water molecules, whose negative, oxygen-containing ends orient toward cations and whose positive, hydrogen-containing ends orient toward anions. The attraction between water molecules and ions in a solution promotes the movement of ions into the solution.

```{table} Aqueous solubility values of selected organic chemicals at $\pu{25 ^\circ C}$. "Miscible" indicates very high solubility.
:name: aq-sol-org
| Name        | $C_w^{sat}\, (\pu{mol L-1})$ |
|-------------|------------------------------:|
| Acetone     | Miscible                   |
| Methane     | $\pu{1.4e-3}$                       |
| Butane      | $\pu{1.0e-3}$                       |
| Benzene     | $\pu{2.2e-2}$                       |
| Naphthalene | $\pu{2.5e-4}$                       |
| Anthracene  | $\pu{2.5e-7}$                       |
```


## Vapor Pressure

Vapor pressure, another chemical-specific property, is the partial pressure of a chemical in a gas phase that is in equilibrium with the pure liquid or solid chemical. Vapor pressure is essentially the solubility of a compound in air. Permanent gases, such as methane, have high vapor pressures; in fact, they have a vapor pressure of $\pu{1 atm}$ or $\pu{760 Torr}$. Some pesticides have medium vapor pressures; for example, hexachlorobenzene has a vapor pressure of about  $\pu{e-7 atm}$. Some compounds, such as decachlorobiphenyl, have vapor pressures so low that they are essentially nonvolatile ( $\pu{e-10 atm}$). For our purposes, the relevant range is  $\pu{e-4 - e-8 atm}$.

```{dropdown} Example: Vapor Pressure
At $\pu{20 ^\circ C}$ a bottle contains both air and pure liquid TCE (trichloroethylene, a common industrial solvent), the partial pressure of TCE vapor in the air-filled neck of the bottle (the headspace) will be approximately $\pu{0.08 atm}$. 

>The ideal gas law is used to convert the vapor pressure into the corresponding concentration (expressed in moles of vapor per volume), 
>
$$
\frac{n}{V}=\frac{P}{\text{R}T}
$$
>
>where $n$ is the number of moles of the chemical, $V$ is the volume, $P$ is the vapor pressure, $R$ is the gas constant ($\pu{0.0821 L atm mol−1 K-1}$), and $T$ is the absolute temperature. Thus, a partial pressure of $\pu{0.08 atm}$ of TCE corresponds to a concentration of approximately $\pu{0.003 mg L−1}$.

```

The term volatility is often used to qualitatively describe a chemical's vapor pressure. Although there are no universally agreed-upon cutoffs, chemicals described as volatile typically have vapor pressures exceeding $\pu{1 atm}$ at the boiling point of water ($\pu{100 ^\circ C}$). Examples of volatile chemicals include solvents, such as TCE, and hydrocarbons present in gasoline, such as benzene. Semivolatile chemicals typically have vapor pressures lower than $\pu{1 atm}$ at $\pu{100 ^\circ C}$ but can volatilize significantly at environmental temperatures. Examples include naphthalene (found in mothballs) and other polycyclic aromatic hydrocarbons (PAHs). Chemicals with negligible vapor pressures are often nonvolatile; examples include most salts. Vapor pressure is temperature-dependent.

## Partitioning into Phases

The environmental distribution of organic compounds can be studied by looking at their equilibrium partitioning between environmental phases, which include air, water, soil, and biota. Taking these phases pairwise, we can define the various physical and chemical properties that control the partition coefficients between these phases:

1. Air-water: vapor pressure and water solubility
2. Water-soil: adsorption and water solubility
3. Soil-air: adsorption and vapor pressure
4. All phases - biota: fat solubility or "lipophilicity"

Partitioning between the air and water depends on a compound's vapor pressure and solubility. A highly soluble compound with low vapor pressure, such as sodium chloride, would not move across the air-water interface and would stay almost completely in the water phase; a very volatile compound, such as methane, would quickly move out of the water phase and over time its concentration in the water would approach zero.

Partitioning between air and soil or sediment depends on a compound's tendency to absorb particles and vapor pressure. For example, DDT has a low vapor pressure and a high tendency to adsorb to particles; therefore, it is only slowly released from soils and sediments to the air.

Lastly, the partitioning and accumulating pollutants into biota depend on all these factors, especially vapor pressure and water solubility. Still, it mainly depends on the compound's solubility in the organism's fat. The latter has a special name: ***lipophilicity***, which means *fat loving*. It might also be called ***hydrophobicity*** (*water fearing*), but the most common term for this property is lipophilicity - note the spelling of this word.

Let's consider a system in which two bulk phases, 1 and 2 (e.g., air and water), are in contact with each other at a given temperature and pressure. We assume that the two phases are in equilibrium due to the amounts of all chemical species present in each. We now introduce a very small amount of a given organic compound $i$ into *Phase 1* (i.e., the properties of both bulk phases are not significantly influenced by the introduction of the compound). After a short time, some molecules of the compound, *i*, will have been transferred from *Phase 1* (reactant) to *Phase 2* (product). This partitioning can be represented in a reaction form as follows:

$$
\ce{$i$ in Phase 1 <=> $i$ in Phase 2}
$$

The equilibrium situation can thus be described by an equilibrium partition constant, $K_p$, which we define as:

```{math}
:label: parti
K_p = \frac{C_{i,2}}{C_{i,1}}
```
Because we have chosen $i$ in Phase 2 as the "product," the abundance of $i$ in Phase 2 is in the numerator of Eq. {eq}`parti`. We define a constant as a ratio of concentrations rather than activities for practical purposes. Finally, we consider only situations in which the compound is present as a solute, that is, at low concentrations, such that it does not significantly affect the properties of the bulk phase.

### Air-Water Partitioning

The Henry's law constant represents partitioning between air and water ($K_H$ or $H$). $K_H$ is the ratio of a compound's water solubility ($C_w^{sat}$) to its partial pressure above that water sample. 

```{math}
:label: khorg
K_H = \frac{C_\text{Air}}{C_{\ce{H2O}}}
```
When the concentration of the compound is expressed in partial pressures (atm) and $C_w^{sat}$ is expressed in $\pu{mol L-1}$, then $K_H$ units reflect these concentration units. When both $C_{Air}$ and $C_w^{sat}$ have same units, $K_H$ becomes dimensionless.


```{dropdown} Example: Air-Water Partitioning 

Benzene (a BTEX hydrocarbon) is released during an industrial accident and enters the groundwater system. The average concentration of benzene in the water is $\pu{1000 mg L−1}$ (same as ppm). If the water is in contact with air, calculate the benzene concentration in the air in $\pu{mol L-1}$. $K_H$ for benzene is $0.22849$.

>First convert $\pu{1000 mg L−1}$ to $\pu{mol L-1}$. Assume that $\pu{1 kg}$ of water equals a volume of $\pu{1 L}$. The molecular weight of benzene ($\ce{C6H6}$) is 78.
>
>$$\frac{\pu{1000 mg L-1} \times \pu{e-3 mg g-1}}{\pu{78g mol-1}} = \pu{1.28e-2 mol L-1}$$
>
>Substitute this concentration in Eq. {eq}`khorg`, and we get
>
>$$\begin{aligned}
K_H &= \frac{C_{Air}}{C_{\ce{H2O}}}\\
0.22849 &= \frac{C_{Air}}{\pu{1.28e-2 mol L-1}}\\
\therefore C_{Air} &= \pu{2.92e-3 mol L-1}
\end{aligned}$$
```


### Water-Organics Partitioning

We use partition constants or coefficients to quantify the distribution of organic chemicals in different phases (see Eq. {eq}`parti`). They are defined as the ratio of the concentration of an organic compound in two phases that are in equilibrium with each other. 

```{math}
:label: korg-h2o
K = \frac{C_\text{Organics}}{C_{\ce{H2O}}}
```

The denominator concentration will be less than $C_w^{sat}$. A high value of $K$ suggests that the compound is not water-soluble but more soluble in organic solvents. In this case, the compound is said to be *lipophilic* (or fat-soluble).

To simulate lipids (fats) in biota, pharmacologists long ago selected a model compound: n-octanol. Thus, the partition coefficient that best describes lipophilicity is the octanol-water partition coefficient, usually given the symbol $K_{ow}$. The interesting values of $K_{ow}$ are usually in the $\pu{e2 - e7}$ range; hence, it is convenient to use the logarithm of $K_{ow}$. Clearly $K_{ow}$ is related to $C_w^{sat}$; high water solubility implies a low $K_{ow}$. An empirical relationship between these two parameters:

```{math}
:label: logkow
\log K_{ow} = - 0.86 \log C_w^{sat} + 0.32
```
Note that $C_w^{sat}$ is in $\pu{mol L-1}$. High $\log K_{ow}$ values imply that the organic compound is *lipophilic*. If one knows the $\log K_{ow}$ value of a given compound, it is possible to calculate the $\log K_{ow}$ value of related compounds.

### Water-Solid Partitioning

Adsorption refers to the collection of organic compounds on the surfaces of particles, such as soil, suspended sediment, and aerosols. Most of these particles are covered with a layer of organic material; thus, the adsorption results from the attraction of two organic materials. Adsorption is measured by the solid-water distribution coefficient ($K_d$), which is the ratio of the concentration of the compound on the solid to its concentration in the water surrounding the solid: 

```{math}
:label: kd
K_d = \frac{C_\text{Solid}}{C_{\ce{H2O}}}
```

The concentration on the solid has units of $\pu{mol kg−1}$, and the concentration in the water is $\pu{mol L-1}$; hence, $K_d$ has units of $\pu{L kg−1}$. These units are often ignored if we assume a solid density of $\pu{1 kg L-1}$. $K_d$ will often depend on how much of the total mass of the particle is organic material; thus, $K_d$ can be corrected by the fraction of organic material ($f_{om}$) in the particles to give the following expression.

```{math}
:label: kom
K_{om} = \frac{K_d}{f_{om}}
```
Note that $f_{om}$ is a fraction and is always less than $1$ and often less than $0.1$. Because the partitioning is from the water to the organic material on the particle, it should come as no surprise that $K_{om}$ is empirically related to $K_{ow}$ and the water solubility: 

```{math}
:label: kom-csat

\begin{aligned}
    \log K_{om} &= 0.82 \log K_{ow} + 0.14\\
    &= -0.75 \log C_w^{sat} + 0.44 
\end{aligned}
```

```{dropdown} Example: Adsorption 

It was found that the adsorption of naphthalene onto sedimentary particles followed a linear relationship, with $ K_d = \pu{137 L kg−1}$. If the naphthalene concentration in the groundwater was $\pu{3.2 mg L−1}$, calculate the concentration of naphthalene adsorbed onto the sedimentary particles in the aquifer.

>Substitute given data in Eq. {eq}`kd` as follows:
>
>$$\begin{aligned}
K_d &= \frac{C_{Solid}}{C_{\ce{H2O}}}\\
\pu{137 L kg-1} &= \frac{C_{Solid}}{\pu{3.2 mg L-1}}\\
C_{Solid} &= \pu{438 mg kg-1}
\end{aligned}$$

```


## Bioaccumulation

Since many organic pollutants are *lipophilic* (fat- or tissue-loving), it is unsurprising that they are found in organisms and biota exposed to them. Most organic pollutants tend to accumulate in biota. The simplest case of an animal in equilibrium with its surroundings is a fish. In this case, we can define a partition coefficient for the concentration of some organic compound in the fish relative to the concentration of that compound in the water in which the fish lives: 

```{math}
:label: kbiol
K_B = \frac{C_\text{Fish}}{C_{\ce{H2O}}}
```
 where $C_{fish}$ is the concentration of some pollutant in the whole fish, usually in units of $\pu{\mu g g−1}$ of the wet weight of fish, and $C_{\ce{H2O}}$ is the concentration of the same pollutant in the surrounding water, usually in units of $\pu{\mu g cm−3}$ of water. The partition coefficient $K_B$ is sometimes called the bioaccumulation factor (BAF) and has no units. Because octanol was selected to simulate animal lipids, $K_B$ is related to $K_{ow}$ as shown in the empirical relationship below: 

```{math}
:label: kbkow
\log K_B = \log K_{ow} - 1.32
```

$K_B$ is higher for animals that feed on fish. For example, dolphins and other higher-level predators can have much greater $K_B$.

```{dropdown} Example: Bioaccumulation 

A covered soup bowl contains $\pu{1 L}$ of a very dilute, tepid soup (at $\pu{25 ^\circ C}$), $\pu{1 L}$ of air, and a floating blob of fat with a volume of $\pu{1 mL}$. The soup also contains $\pu{1 mg}$ of naphthalene. The $\log K_{ow}$ for naphthalene is $3.36$ and its unitless Henry's law constant $0.0174$.

Assuming everything is at equilibrium, estimate the amount of naphthalene you would ingest if you were to eat only the fat blob.

>First, set up the mass balance equation: 
>
>$$\begin{aligned}
M_{total} = \pu{1 mg} &= M_{\ce{H2O}} + M_{Air} + M_{Fat}  \\
&= C_{\ce{H2O}}V_{\ce{H2O}} + C_{Air}V_{Air} + C_{Fat}V_{Fat} \\
&= C_{\ce{H2O}}(\pu{1 L}) + C_{Air}(\pu{1 L}) + C_{Fat}(\pu{e-3 L})
\end{aligned}$$ 
>
>We need to make this into an equation with only one unknown to solve for $M_{Fat}$
>
>Now, let's rearrange the partitioning coefficients: 
>
>$$\begin{aligned}
K_{ow}  &= \frac{C_{Fat}}{C_{\ce{H2O}}} \\
\text{Or,} \quad    C_{\ce{H2O}} &= \frac{C_{Fat}}{K_{ow}} 
\end{aligned}$$
>
>$$\begin{aligned}
K_H &= \frac{C_{Air}}{C_{\ce{H2O}}}  \\
\text{Or,}\quad C_{Air} &= K_H (C_{\ce{H2O}}) 
\end{aligned}$$
>
>Combining the above two expressions, we get
>
>$$
C_{Air} = K_H \left(\frac{C_{Fat}}{K_{ow}} \right) 
$$
>
>Substitute $C_{\ce{H2O}}$ and $C_{Air}$ expressions into the $M_{total}$ expression
>
>$$\begin{aligned}
M_{total}   &= \left(\frac{C_{Fat}}{K_{ow}}\right) (\pu{1 L}) + K_H \left(\frac{C_{Fat}}{K_{ow}} \right)(\pu{1 L}) + C_{Fat}(\pu{e-3 L})  \\
&= (C_{Fat})\left( \frac{1}{K_{ow}} + \frac{K_H}{K_{ow}} + \pu{e-3}\right)\\
&= (C_{Fat}) \left( \frac{1}{10^{3.36}} + \frac{0.0174}{10^{3.36}} + \pu{e-3}\right)\\
&=  (C_{Fat})(\pu{0.00144 L})
\end{aligned}$$
>
>Simplify and calculate $C_{Fat}$ and $M_{Fat}$ 
>
>$$\begin{aligned}
M_{total}   &=  (C_{Fat})(\pu{0.00144 L})\\
C_{Fat} &= \frac{M_{total}}{\pu{0.00144 L}} = \frac{\pu{1 mg}}{\pu{0.00144 L}}\\
& = \pu{693 mg L-1}\\
M_{Fat} &= C_{Fat}\times V_{Fat} = \pu{693 mg L-1}\times \pu{e-3 L}\\
&= \pu{0.693 mg} 
\end{aligned}$$
```


```{dropdown} Example: Partitioning 

A stream is contaminated with 1,2,4-trichlorobenzene (1,2,4-TCB) and has 1,2,4-TCB concentration of $\pu{2.3 \mu g L-1}$. The molecular weight of this compound is $\pu{181.5 g mol−1}$, and its $\log K_{ow}$ (at $\pu{25 ^\circ C}$) is $4.04$. Estimate the maximum concentration of 1,2,4-TCB in rainbow trout swimming in water.

>First, let's calculate $K_B$ using $K_{ow}$ using Eq. {eq}`kbkow`.
>
>$$\begin{aligned}
\log K_B &= \log K_{ow} - 1.32\\
&= 4.04-1.32 = 2.72\\
K_B = 10^{2.72} = 524.8
\end{aligned}$$ 
>
>Now, apply this value to the $K_B$ expression in Eq. {eq}`kbiol`: 
>
>$$\begin{aligned}
K_B &= \frac{C_{fish}}{C_{\ce{H2O}}}\\
524.8 &= \frac{C_{fish}}{\pu{2.3 \mu g L-1}}\\
C_{fish} &= \pu{1207 \mu g L-1}
\end{aligned}$$
```


## Degradation

Because of the presence of C atoms in organic molecules, they are susceptible to degradation in most surface environments. The degradation can occur through various processes, including biodegradation, photodegradation, and chemical degradation.

In **biodegradation** the breakdown of organic chemicals by microorganisms, such as bacteria and fungi, into simpler, non-toxic substances. The microorganisms use the organic chemicals as energy and nutrients, breaking them down into carbon dioxide, water, and other organic compounds. Biodegradation occurs naturally in the environment but can also be enhanced by adding specific microorganisms or nutrients to contaminated areas.

In **photodegradation** process, organic chemicals are degraded by exposure to sunlight or ultraviolet radiation. The energy from the radiation can break down the chemical bonds in the molecules, causing them to break down into more straightforward, less toxic substances. This process is commonly used to treat contaminated water or soil by exposing it to sunlight or ultraviolet light.

During **chemical degradation**, some organic chemicals can be degraded through chemical reactions. For example, oxidation can occur when organic chemicals react with oxygen in the environment, causing them to break down into simpler substances. Chemical degradation can also occur through other chemical reactions, such as hydrolysis, where water breaks down the chemical bonds in the molecules.

The specific degradation mechanism for a particular organic chemical depends on its chemical structure, environmental conditions, and other chemicals or microorganisms in the environment.

For organic chemicals predominantly dissolved in water or adsorbed to soil and sediment, chemical or biochemical transformations may also be essential fate processes, each with their characteristic rate constant.

We can use the previously-covered chemical kinetics principles to study degradation rates.
