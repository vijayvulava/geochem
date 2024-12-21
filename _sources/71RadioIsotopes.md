# 7.1 Radioisotopes

## What are isotopes?

Atoms that have the same atomic number ($Z$) but a different atomic mass ($M$), i.e., isotopes of an element have the same number of protons ($\ce{p+}$) but a different number of neutrons ($\ce{n^0}$). For example, the element hydrogen has three isotopes: $\ce{_1^{1}H}$ (protium), $\ce{_1^{2}H}$(deuterium), and $\ce{_1^{3}H}$ (tritium). By convention, the atomic number is shown on the lower left side of the element symbol, while the atomic mass is on the upper left side. Since isotopes of the same element have the same atomic number, the atomic number is often not shown. The common way to show the hydrogen isotopes would be $\ce{^{1}H}$, $\ce{^{2}H}$, and $\ce{^{3}H}$. You may also come across other naming conventions in literature such as $\ce{C-14}$ or $\ce{U-238}$.

In the calculation of the atomic mass of an element, relative abundances of all isotopes and their respective masses are used to calculate a weighted average.

```{dropdown} Example: Calculation of atomic mass 

Naturally occurring hydrogen is found to consist of three isotopes:

1. $\pu{99.9885 \%}$ whose isotopic weight is $1.007825$
2. $\pu{0.0115 \%}$ whose isotopic weight is $2.01410178$
3. $\pu{0 \%}$ whose isotopic weight is $3.016049277$

Calculate the atomic weight of an average naturally occurring sample of a hydrogen atom. 

>The atomic weight is the weighted average of the masses of all isotopes of the element and can be calculated as follows: 
>
>$$\begin{align}
    \text{Atomic Weight} &= \frac{99.9885}{100}\times 1.007825 \\
    &+ \frac{0.0115}{100}\times 2.01410178 \\
    &+ \frac{0}{100}\times 3.016049277 \\
    &= \pu{1.00794 amu}
\end{align}$$

```


## What are Radioisotopes?

The number of neutrons in the nucleus of an element can be variable, giving rise to isotopes. Many isotopes are unstable, and some will spontaneously transform from one form to another. This process is termed radioactive decay, and an isotope that undergoes radioactive decay is termed a radioisotope.

In the example of $\ce{H}$ isotopes is a radioisotope. Similarly, $\ce{^{14}C}$ is a radioisotope of $\ce{C}$ that is employed in many geological and environmental applications. Within the periodic table, the majority of the elements have stable radioisotopes. All elements with $Z>83$ are radioisotopes. The elements $\ce{Tc}$ ($Z=43$) and $\ce{Pm}$ ($Z=61$) have no stable isotopes.

## Decay Mechanisms

Why are radioisotopes unstable? The nucleus of a radioisotope is unstable because the total energy content of its nucleus is greater than that of a neighboring stable nucleus. There are several processes by which a radioisotope can become stable. When radioisotopes decay, they release various forms of subatomic particles and energy. For example, {numref}`u238-decay` shows how decays into more stable isotopes.


```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/6/65/Decay_chain%284n%2B2%2C_Uranium_series%29.svg/800px-Decay_chain%284n%2B2%2C_Uranium_series%29.svg.png
---
name: u238-decay
figclass: margin-caption
---
Decay sequence of naturally occurring $\ce{^{238}U}$ into daughter products and the release of various types of subatomic particles. Image source: [Decay chain - Wikipedia](https://en.wikipedia.org/wiki/Decay_chain)
```

This decay process can be shown as a chemical reaction:

$$
\begin{align*}
\ce{Parent -> Daughter + subatomic  particle + energy
}
\end{align*}
$$

Radioisotopes of low mass numbers generally attempt to become stable by ***beta ($\beta$) decay***. There are two forms of $\beta$ decay. In beta- ($\beta^-$) decay a neutron ($\ce{n^0}$) converts into a proton ($\ce{p+}$) and an electron ($\ce{e-}$) as shown below.

$$
\begin{align*}
\ce{n^0 -> p+ + e-}
\end{align*}
$$


```{dropdown} Example: $\beta^-$ decay 

The isotope $\ce{^{14}C}$ decays in this manner.

$$
\ce{_6^{14}C -> _7^{14}N + e-}
$$

>Because the neutron converts to a proton, the isotope's mass number does not change, but the atomic number increases by 1.
```


In beta+ ($\beta^+$or positron) decay, a proton ($\ce{p+}$) can decay into a neutron ($\ce{n^0}$) and a positron (a positively charged electron, $\ce{e+}$). Again, the mass number does not change, but the atomic number decreases by $1$ as there is one less proton in the nucleus, as shown below.

$$
\begin{align*}
\ce{p+ -> n^0 + e+}
\end{align*}
$$

```{dropdown} Example: $\beta^+$ decay 

The isotope $\ce{^{18}F}$ decays in this manner.

$$
\ce{_9^{18}F -> _8^{18}O + e+}
$$

>The mass number did not change, but the atomic number decreased by $1$ as there is one less proton in the nucleus.
```

A proton can also convert into a neutron by capturing an orbiting electron, emitting X-ray radiation, as shown in the reaction below. This process is called ***electron capture***.

$$
\begin{align*}
\ce{p+ + e-  -> n^0 + X-rays}
\end{align*}
$$


```{dropdown} Example: Electron capture 

The isotope $\ce{^{18}F}$ can capture an $\ce{e-}$ and emit X-rays as shown below. 

$$
\ce{_9^{18}F + e- -> _8^{18}O + X-rays}
$$

>The mass number did not change, but the atomic number decreased by $1$ as there is one less proton in the nucleus.

```

Neutron-rich radioisotopes tend to decay by the $\beta^-$ decay process, whereas neutron-poor radioisotopes undergo $\beta^+$ decay or electron capture. Many radioisotopes require repeated $\beta$ decays to become stable.  For example, radioactive $\ce{_{54}^{140}Xe}$, which undergoes four successive $\beta-$ decays to form stable $\ce{_{58}^{140}Ce}$.

$$
\begin{align*}
\ce{
_{54}^{140}Xe -> _{55}^{140}Cs ->_{56}^{140}Ba  -> _{57}^{140}La -> _{58}^{140}Ce
}
\end{align*}
$$

The number of beta decay reactions would be numerous for the heavier radioisotopes, so they undergo a different kind of radioactive decay process. This is known as ***alpha ($\alpha$) decay*** and involves the ejection of an $\alpha$ particle (i.e., $\ce{_2^{4}\alpha}$ or $\ce{_2^{4}He}$) from the nucleus.

```{dropdown} Example: Alpha ($\alpha$) decay 

The isotope $\ce{_{94}^{239}Pu}$ decays to $\ce{_{92}^{235}U}$ by this process.

$$
\ce{_{94}^{239}Pu -> _{92}^{235}U + _{2}^{4}He}
$$

>The loss of an $\alpha$ particle means that the mass number decreases by 4, whereas the atomic number decreases by 2.

```

The $\alpha$ particle is ejected at speed and, due to its mass, is the most ionizing but the least penetrating form of radiation. A sheet of paper can block this form of radiation.

Another form of radioactive decay is that of spontaneous fission. A heavy radioisotope will split into two medium-weight nuclei called fission products in this process. These are commonly radioactive themselves.

```{dropdown} Example: Spontaneous fission 

An example is the fission of $\ce{_{98}^{252}Cf}$, which splits with the emission of two neutrons.

$$
\ce{_{98}^{252}Cf -> _{48}^{120}Cd + _{50}^{130}Sn + 2 n^0}
$$

>The atomic numbers of cadmium (48) and tin (50) add up to the atomic number of californium (98) because there is no change in the total number of protons. The total mass of the products, including the two neutrons, adds up to 252, the mass number of $\ce{_{98}^{252}Cf}$.

```

The last form of radioactive decay is ***gamma ($\gamma$) decay***. Here, the radioisotopes are in an excited (i.e., high-energy) state. Most alpha and beta decays result in excited-state daughter nuclei, which lose energy to go to their ground (i.e., low-energy) state by emitting gamma ($\gamma$) radiation. This gamma radiation is very short-wavelength electromagnetic radiation similar to X-rays.

```{dropdown} Example: Gamma decay 

An example is the decay of $\ce{_{55}^{137}Cs}$ by $\ce{_{-1}^{0}\beta}$ decay to $\ce{_{56}^{137}Ba}$, which then emits $\gamma$ radiation to lose energy

$$
\ce{
_{55}^{137}Cs -> _{56}^{137}Ba (exited state) -> _{56}^{137}Ba + \gamma
}
$$

```

```{table} Summary of different types of subatomic particles and their common symbols.
:name: subatomic-particles
| Name              |     Symbols      |                |           |
|-------------------|-----------|----------------|-----------|
| Proton            | $\ce{p^+}$      | $\ce{H+} $       |           |
| Neutron           | $\ce{n^0}$      |                |           |
| Beta-            | $\beta^-$ | $_{-1}^0\beta$        | $\ce{e-}$      |
| Beta+             | $\beta^+$ | $_{+1}^0\beta$ | $\ce{e+}$ |
| Alpha particle | $_2^4\alpha$   | $\ce{_{2}^{4}He}$   |           |
| Gamma particle |  $\gamma$         |                |           |
```


## Quantifying Decay

Radioactive decay is a random process, and it is impossible to predict when any particular atom will decay. The rate at which a particular radioisotope decay obeys first-order kinetics. If the number of isotope atoms is represented as $N$, the rate of decay can be expressed as follows: 

```{math}
:label: radio-decay
\frac{dN}{dt} = -\lambda N
```
where $\lambda$ is the radioactive decay constant (similar to the rate constant, $\kappa$ described in the previous chapter.) We can integrate the above equation and derive the following solution:

```{math}
:label: radio-decay-equation
\begin{aligned}
\ln \frac{N_t}{N_0} &= -\lambda t \\
\text{or,}\,
N &= N_0 e^{-\lambda t} 
\end{aligned}
```

where, $N_0$ is the number of unchanged atoms at $t=0$, and $N_t$ is the number of atoms available at time, $t$.

Since the radioisotope is unstable and decaying according to first-order kinetics, the time required for an isotope to reach half its original mass or concentration is called half-life. At half-life, $N_t = \dfrac{N_0}{2}$. If we make appropriate substitutions to Eq. {eq}`radio-decay-equation`, 

```{math}
:label: 
\begin{aligned}
\frac{1}{2} &= e^{-\lambda t_{1/2}} \\
\text{or,}\,
t_{1/2} &= \frac{0.693}{\lambda}
\end{aligned}
```

Consider the radioactive decay of $\ce{^{238}U}$ to $\ce{^{234}Th}$. $\ce{^{238}U}$ is the radioactive parent and $\ce{^{234}Th}$ is the radiogenic daughter. For any closed system at time $t$, the number of daughter atoms produced plus the number of parent atoms remaining must equal the total number of parent atoms at the start. If we substitute $D$ for the number of daughter atoms produced in Eq. {eq}`parent-daughter`, we get 

```{math}
:label: parent-daughter
N = (N+D) e^{-\lambda t}
```

Suppose we assume that the $D$ is not a radioisotope. In that case, we can simplify Eq. {eq}`radio-decay-equation` to determine the number of daughter atoms formed as the parent atoms decay as follows:

```{math}
:label: 
D = N_0(1-e^{-\lambda t})
```

The relationship between a radioisotope's decay and its daughter's growth can be seen in {numref}`parent-daughter-fig`.

```{figure} https://d32ogoqmya1dw8.cloudfront.net/images/NAGTWorkshops/time/radioactive_decay_456.jpg
---
name: parent-daughter-fig
figclass: margin-caption
---
Graphical representation of decay of a radioisotope ($N$) and the growth of a radiogenic daughter ($D$). Image source: [Geochronology (carleton.edu)](https://serc.carleton.edu/NAGTWorkshops/time/geochronology.html)
```
