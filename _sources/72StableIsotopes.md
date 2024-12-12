# 7.2 Stable Isotopes

## What are Stable Isotopes?

Stable isotopes do not spontaneously break down to form other isotopes. Because of relative differences in masses of isotopes of an element, changes to isotopic ratios can be observed during various biogeochemical processes. The study of stable isotopes is useful in gaining a better understanding of environmental and geological studies.

Stable isotopes are especially useful in elements whose isotopes have large relative mass differences. Therefore, most elements used for stable isotope studies have a low atomic number and atomic mass ({numref}`stable-isotopes`). For isotopes with an atomic mass of greater than $40$, the relative mass differences are too small for any measurable isotopic fractionation. Most elements used in radiometric dating have high atomic mass, and mass fractionation is insignificant.

```{table} Distribution of stable isotopes of most commonly-used elements.
:name: stable-isotopes
| Element | Isotope         | %   |
|---------|-----------------|--------|
| H       | $\ce{^1 H}$  | $99.985$ |
| H       | $\ce{^2 H}$  | $0.015$  |
| C       | $\ce{^{12} C}$ | $98.9$   |
| C       | $\ce{^{13} C}$ | $1.1$    |
| N       | $\ce{^{14} N}$ | $99.63$  |
| N       | $\ce{^{15} N}$ | $0.37$   |
| O       | $\ce{^{16} O}$ | $99.762$ |
| O       | $\ce{^{18} O}$ | $0.2$    |

```


## Stable Isotope Fractionation

Isotopic fractionation is the partitioning of isotopes during physical (evaporation, condensation, melting, crystallization, absorption, desorption, diffusion, etc.), chemical (weathering, precipitation, etc.), or biological (assimilation, incorporation, etc.) processes. This partitioning is proportional to the difference in the masses of the isotopes. The processes can either be equilibrium reactions, in which forward and backward reaction rates are equal for each isotope, or kinetic reactions, which are unidirectional reactions in which reaction rates depend on the masses of the isotopes and their vibrational energies.

```{dropdown} Example: Stable isotope fractionation of $\ce{H2O}$

During evaporation of $\ce{H2O}$ in a closed system, six isotope combinations of $\ce{H2O}$ are possible: $\ce{^1H2^{16}O}, \ce{^1H^2H^{16}O}, \ce{^2H2^{16}O}, \ce{^1H2^{18}O}, \ce{^1H^2H^{18}O}, \ce{^2H2^{18}O}$.

As a result of these different stable isotope combinations, the molecular masses are $18$, $19$, $20$, $20$, $21$, and $22$ respectively. See the conceptualizations in the figure below.

![# Water Isotopes Diagram - USGS](https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/Fig%201.Isotopes.web_.jpg)

```

Why do stable isotopes fractionate? Isotopically lighter isotopes have higher velocities than heavier isotopes. From basic physics, the kinetic energy of a particle can be calculated using the following formula:

```{math}
:label: kineticenergy
\text{Kinetic Energy} = \frac{1}{2} mv^2
```

Per Eqn. {eq}`kineticenergy`, isotopically lighter molecules with higher velocities and, therefore, higher kinetic energy. Consider the above water example. Since the lighter molecules have greater velocities, they preferentially escape into the vapor phase, enriching the lighter isotopes ($\ce{^1H}$ and $\ce{^{16}O}$) relative to the liquid phase of water. In addition, atoms with higher mass form slightly stronger bonds, and the heavier isotope is generally enriched in the more condensed phase or larger molecule.

```{dropdown} Example: Fractionation of water between phases 

Consider the equilibrium exchange of water between different phases:

$$\ce{
H2O(s) <=> H2O(l) <=> H2O(g)
}$$

As we know, the molecules of water are held together by weak hydrogen bonds.  These intermolecular bonds are strongest in the solid phase and weakest in the vapor phase.  In addition, there is slightly greater hydrogen bond strength for $\ce{H2^{18}O-H2O}$ versus $\ce{H2^{16}O-H2O}$ bonds, the $\ce{^{16}O}$ bonds will be more easily broken during evaporation. Therefore, a lower concentration of $\ce{H2^{18}O}$ is present in the water vapor than in the liquid water, so water is isotopically enriched over its vapor. Similarly, $\ce{^{18}O}$ is more enriched in ice than water. 

```


```{dropdown} Example: Fractionation of $\ce{CaCO3}$ during dissolution 

Consider the chemical weathering of limestone ($\ce{CaCO3}$):

$$\ce{
CaCO3 ->[Acid] CaO + CO2
}$$

In this reaction, $\ce{CO2}$ escapes and thus does not equilibrate with the solid phase. During a chemical reaction, the lighter isotope is more reactive and concentrated in the products. The relative loss of the lighter isotope from the reactants leads to an enrichment of the reactants in the heavier isotope. In this example, the gas phase (product) is enriched in the lighter isotopes of C and O, and the enrichment is significantly greater than that which would occur during an equilibrium reaction.

```

The partitioning of stable isotopes between two substances, $A$ and $B$, is described by the isotopic fractionation factor, $\alpha$. The fractionation factor is written as 

```{math}
:label: alpha
\alpha = \frac{R_A}{R_B}
```

Where $R$ is the ratio of heavy to light isotope abundance (e.g., $\ce{^2 H}$/$\ce{^1 H}$, $\ce{^{18}O}$/$\ce{^{16}O}$ ). Generally, the isotope abundance ratio does not significantly vary in the environment, so the fractionation factor, $\alpha$, generally has a value close to 1. However, this value can be precisely measured and expressed with a precision of 4-5 decimal places. The fractionation factor depends on the temperature and can be determined experimentally or from spectroscopic data.

```{dropdown} Example: Isotope fractionation factor 

Consider the evaporation of water. We can set the fractionation ratio and factor as follows:

$$R = \frac{\ce{^{18}O}}{\ce{^{16}O}}
$$ 
We can calculate $\alpha$ as

$$\alpha = \frac{\ce{^{18}O}/\ce{^{16}O}_{\text{(liquid)}}}{\ce{^{18}O}/\ce{^{16}O}_{\text{(vapor)}}}
$$

Since $\ce{^{16}O}$ is enriched in the vapor phase relative to the liquid,

$$
[\ce{^{18}O}]_{\text{vapor}} > [\ce{^{16}O}]_{\text{liquid}}
$$

Conversely, $\ce{^{18}O}$ is enriched in the liquid relative to the vapor,

$$
[\ce{^{18}O}]_{\text{liquid}} > [\ce{^{18}O}]_{\text{vapor}}$$

Therefore, the fractionation factor is greater than 1. With increasing temperature, the fractionation factor decreases and becomes 1 at infinite temperature.

```

In {numref}`oxygen-fractionation`, isotope fractionation of $\ce{O}$ as a function of temperature during evaporation of $\ce{H2O}$ is shown. Paleoclimatologists use $\ce{O}$ ratios ($\ce{^{18}O}$/$\ce{^{16}O}$) from $\ce{H2O}$ trapped in glaciers as well as the $\ce{O}$ absorbed in the shells of marine plants and animals to measure past temperatures and rainfall. In polar ice cores, the measurement is relatively simple: less $\ce{^{18}O}$ in the frozen water means that temperatures were cooler.  In shells, the measurement is far more complicated because the biological and chemical processes that form the shells skew the $\ce{O}$ ratio in different ways depending on temperature.

```{figure} https://earthobservatory.nasa.gov/ContentFeature/Paleoclimatology_OxygenBalance/images/oxygen_schematic.jpg
---
name: oxygen-fractionation
figclass: margin-caption
---
Water vapor gradually loses $\ce{^{18}O}$ as it travels from the equator to the poles. Because water molecules with heavy $\ce{^{18}O}$ isotopes in them condense more quickly than normal water molecules, the air becomes progressively depleted in $\ce{^{18}O}$ as it travels to high latitudes and becomes colder and drier. The snow that forms most glacial ice is also depleted in $\ce{^{18}O}$. Image source: [Paleoclimatology: The Oxygen Balance (nasa.gov)](https://earthobservatory.nasa.gov/features/Paleoclimatology_OxygenBalance)
```

The isotopic fractionation factor is related to the equilibrium constant ($K$) of a reaction as follows: 

```{math}
:label: alphak
\alpha = K^\frac{1}{n}
```
 Where $K$ is the equilibrium constant and $n$ is the number of atoms exchanged.

```{dropdown} Example: Isotope fractionation factor and $K$ 

Consider the exchange of $\ce{O}$ isotopes between carbonate ($\ce{CaCO3}$) and water. This particular reaction is interesting because it is used as a "paleothermometer" in marine systems. The fractionation factor can help determine the water temperature at the time of carbonate deposition.

Let's write the reaction in terms of a single oxygen, so $n = 1$ in Eq. {eq}`alphak`,

$$
\ce{
1/3 CaC^{16}O3 + H2^{18}O <=> 1/3 CaC^{18}O3 + H2^{16}O
}$$

Writing this equation in terms of the equilibrium constant, $K$,

$$K = \frac{([\ce{CaC^{18}O3}]^{1/3} [\ce{H2^{16}O}])}{([\ce{CaC^{16}O3}]^{1/3} [\ce{H2^{18}O}])}$$

Rearranging this equation with $\ce{CaCO3}$ separated from $\ce{H2O}$,

$$K = \frac{([\ce{CaC^{18}O3}]/[\ce{CaC^{16}O3}])^{1/3}}{[\ce{H2^{18}O}]/ [\ce{H2^{16}O}]}$$

Therefore,

$$K = \alpha = \frac{R_\text{Carbonate}}{R_\ce{H2O}} = \frac{\ce{^{18}O}/\ce{^{18}O}\, \text{of}\, \ce{CaCO3}}{\ce{^{18}O}/\ce{^{18}O}\, \text{of}\, \ce{H2O}}$$

Because the isotopic fractionation factor varies as a function of temperature, the measured fractionation factor can be compared to empirical values to determine the equilibrium temperature for the calcium carbonate-water reaction.
```


## The $\delta$ notation

$R$ values for environmental samples have to be compared with a fixed value (or a standard) to know if that sample is enriched or depleted compared to the standard.

Since isotopic variations between samples are very small, we express isotopic ratios using delta ($\delta$) notation. This value is determined by comparing the isotopic ratio ($R$) of a sample with that of a standard and calculated as follows:

```{math}
:label: delta
\delta = \left(\frac{R_\text{Sample}}{R_\text{Standard}} - 1\right) \times 1000
```

Where the isotopic ratio, $R$, has been defined in the previous section. Note that the ratio is multiplied by a thousand and is expressed in "parts per thousand" or permille or permil or the symbol, $\pu{‰}$. As seen in Eqn. {eq}`delta`, $R_\text{Standard}$ is required for the element of interest. Standards for most common elements of interest have been adopted worldwide for research purposes and shown in {numref}`isotopestandards`. Typically, V-SMOW (Vienna standard mean ocean water) and PDB (Pee Dee Belemnite) are most commonly used for $\ce{H}$, $\ce{O}$, and $\ce{C}$ ratios.

```{table} Isotope ratios and standards for most commonly-used elements in environmental geosciences.
:name: isotopestandards
| Isotope Ratio   | Standard | $R \times \pu{e-5}$ |
|--------------|----------|----------: |
| $\ce{^2 H}$/$\ce{^1 H}$   | V-SMOW   | $15.575$ |
| $\ce{^{13} C}$/$\ce{^{12} C}$ | PDB      | $1123.75$   |
| $\ce{^{18} O}$/$\ce{^{16} O}$ | V-SMOW   | $200.52$    |
| $\ce{^{18} O}$/$\ce{^{16} O}$ | PDB      | $206.72$   |
| $\ce{^{15} N}$/$\ce{^{14} N}$ | NBS-14   | $367.6 $   |
| $\ce{^{34} S}$/$\ce{^{32} S}$ | CDT      | $4499.4$   |
```

When $\delta$ values are negative, $R_\text{Sample} < R_\text{Standard}$ in Eqn. {eq}`delta`, therefore, the sample is considered depleted compared with the standard. Similarly, when $\delta$ values are positive, $R_\text{Sample} > R_\text{Standard}$, therefore, the sample is considered to be enriched compared to the standard.

Since the $\delta$ values and the isotope fractionation factors ($\alpha$) are derived from isotopic ratios, they are correlated. Once again, let's look at the fractionation between water (liquid) and vapor and express the fractionation factor, $\alpha$, in terms of the $\delta \ce{^{18}O}$ values of the water and vapor by combining Eqn. {eq}`alpha` and Eqn. {eq}`delta`.

```{math}
:label: alphadelta
\alpha \ce{^{18}O}_{\text{water-liquid-vapor}} = \frac{\delta \ce{^{18}O}_{\text{liquid water}}+1000}{\delta \ce{^{18}O}_{\text{vapor water }}+1000}
```


```{dropdown} Example: $\delta$ notation 

A rainwater sample collected in Boston, Massachusetts, has an $\ce{^{18} O}$/$\ce{^{16} O}$ ratio of $0.0019750$. Calculate $\delta$ for this rainwater sample.

From {numref}`isotopestandards`, we can read the isotopic ratio of $\ce{^{18} O}$/$\ce{^{16} O}$ in V-SMOW to be $0.0020052$. Substitute values in Eqn. {eq}`delta` as follows: 

$$\begin{align}
\delta &=  \left(\frac{\ce{^{18}O}/\ce{^{16}O}_\text{Sample}}{\ce{^{18}O}/\ce{^{16}O}_\text{Standard}} - 1\right) \times 1000\\ &=\left(\frac{0.0019750}{0.0020052} - 1\right) \times 1000 = \pu{-15.1 ‰} 
\end{align}$$

Since this final value is negative, the sample isotopically lighter than the standard.
```


## Stable isotopes and the water cycle

Isotopes provide an excellent tool for distinguishing different water sources and recharge areas during water cycle analysis. Natural isotopes are an intrinsic component of the water molecule and so are ideal tracers. They are selectively partitioned at each step of the water cycle, from primary evaporation over the oceans through condensation and precipitation to groundwater recharge and runoff back to the seas.

The principal hydrological processes that affect the distribution of isotopes through the hydrological cycle include the following:

1. Evaporation and formation of atmospheric vapor
2. Condensation and rain out with decreasing temperature
3. Re-evaporation from soils and surface waters, which enriches the residual water in both isotopes
4. Mixing during recharge and groundwater flow

Based on experimental observations of water isotopes around the world at different latitudes, it has been observed that $\ce{^{18}O}$ and $\ce{^{2}H}$ in freshwater are enriched in warm regions and depleted in cold regions, with a range of $\delta \ce{^{18}O} > \pu{40 ‰}$ and $\delta \ce{^{2}H} > \pu{300 ‰}$. In addition, there is a strong linear correlation between $\delta \ce{^{18}O}$ and $\delta \ce{^{2}H}$ in meteoric waters, with a slope of $8$ and deuterium intercept of $\pu{10}$. This linear correlation is called the ***Global Meteoric Water Line (GMWL)***. It describes the global annual average relationship between $\delta \ce{^{18}O}$ and $\delta \ce{^{2}H}$ in natural [meteoric waters](https://en.wikipedia.org/wiki/Meteoric_water "Meteoric water").

```{math}
:label: gmwl
\delta \ce{^{2}H} = 8 \delta \ce{^{18}O} + 10
```

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Global_meteoric_water_line.tif/lossy-page1-1280px-Global_meteoric_water_line.tif.jpg
---
name: gmwl-fig
figclass: margin-caption
---
Global relationship between $\delta \ce{^{18}O}$ and $\delta \ce{^{2}H}$ ($\delta$D) in water samples. The line shown is called the global meteoric water line. Image source: [Global meteoric water line - Wikipedia](https://en.wikipedia.org/wiki/Global_meteoric_water_line)
```

The mean global meteoric water line (GMWL) is based on numerous analyses of meteoric waters collected at different latitudes and represents a global average. Local meteoric water lines are determined by measuring the isotopic composition of meteoric waters from a restricted geographic area.

The ***Local Meteoric Water Line*** (LMWL) can diverge from the GMWL depending on the climate of that region. The LMWL can differ from GMWL in slope and intercept - the deviation is mainly from climate factors that impact precipitation patterns.

```{figure} https://www.mdpi.com/water/water-10-00705/article_deploy/html/images/water-10-00705-g003.png
---
name: lmwl-fig
figclass: margin-caption
---
Local relationship (LMWL) between $\delta \ce{^{18}O}$ and $\delta \ce{^{2}H}$ ($\delta$D) in water samples from a study in China. Compare the equations with the GMWL shown in the previous figure Image source: [Oxygen and Hydrogen Isotopes of Precipitation in a Rocky Mountainous Area of Beijing to Distinguish and Estimate Spring Recharge (mdpi.com)](https://www.mdpi.com/2073-4441/10/6/705)
```
