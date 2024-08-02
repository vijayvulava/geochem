# 1.1 Atoms and Subatomic Particles

## What are atoms?

Atoms (from the Greek word *atomos*, which means "uncuttable") are extraordinarily small building blocks of matter. Specifically, an atom is the smallest quantity of matter that still retains the properties of matter. Elements are substances that cannot be broken down into simpler substances and are made up of atoms.  Atoms are composed of three fundamental subatomic particles, two of which are contained in a dense nucleus.  The nucleus is composed of electrically neutral neutrons and positively charged protons and is surrounded by a cloud of negatively charged electrons.  The important properties of these subatomic particles are shown in {numref}`subatomic`. 

```{table} Mass and charge of subatomic particles. Note: formal unit of charge is coulumb ($\pu{C}$).
:name: subatomic

|  Particle |  Mass        |  Mass       | Charge        | Charge   |
| ---------- | -------------: | ------------: | ---------------: | ----------: |
|          | $\pu{g}$           | $\pu{amu}$        | Absolute, $\pu{C}$ | Relative |
| Electron | $\pu{9.109e-28}$ | $\pu{5.486e-4}$ | $\pu{-1.6022e-19}$ |       $-1$ |
| Proton   | $\pu{1.673e-24}$ | $1.007$      | $\pu{1.6022e-19}$  |       $+1$ |
| Neutron  | $\pu{1.675e-24}$ | $1.009$      | $0$             |        $0$ |

```

Mass of individual atoms are very low and are expressed in *atomic mass units* or $\pu{amu}$. The $\pu{amu}$ is equal to one-twelfth the mass of a carbon-12 atom.

$$
\pu{1 amu} = \pu{1.661e-24 g} = \pu{1.661e-27 kg}
$$

Atoms are identified by the number of protons and neutrons they contain. The **atomic number** ($Z$) is the number of protons in the nucleus of each atom of an element. It also indicates the number of electrons in the atom - because for an atom to be neutral, it must contain the same number of protons and electrons. $Z$, $A$, and number of neutrons are all positive integers (whole numbers). 
````{margin}
```{note}
With exception of the most common form of $\ce{H}$, which has one proton and no neutrons, all atomic nuclei contain both protons and neutrons.
````

The **mass number** ($A$) is the total number of neutrons and protons in an atom and is estimated as follows:

```{math}
:label: massnumber

\text{mass number}\ (A) = \text{# of protons}\ (Z) + \text{# of neutrons}
```

The accepted way to express this information in geochemical settings is as follows for a hypothetical element, $X$ is $^A_Z X$.


```{dropdown} Example: Estimating subatomic particles
For the elemen fluorine ($\ce{F}$), $A=19$  and $Z=9$. Therefore using Eq. {eq}`massnumber`, we can determine that the number of neutrons in an atom of $\ce{F}$ is $19-9 = 10$. This information can be shown as $\ce{^19_9{F}}$.
```


Atoms of any given element are not all identical.  Instead, most elements have two or more **isotopes** That is, these elements have same $Z$, but different $A$. Because $Z$ does not change for isotopes of any element (if $Z$ changed, it would be a different element!), $Z$ can be dropped and only $A$} is often shown.

A small set of naturally occurring elements in the periodic table have only one stable isotope.

```{dropdown} Example: Isotope notation
For example, $\ce{H}$ has three isotopes: $\ce{^1_1H}$ (protium), $\ce{^2_1H}$ (deuterium), and $\ce{^3_1H}$ (tritium) and can be shown as $\ce{^1H}$, $\ce{^2H}$, and $\ce{^3H}$. Only $\ce{H}$ isotopes have specific names, isotopes of all other elements are denoted by their mass numbers or names as shown in the examples below:
1.  Carbon-14 or $\ce{C-14}$ or $\ce{^{14}C}$ 
2.  Oxygen-18 or $\ce{O-18}$ or $\ce{^{18}O}$
3.  Uranium-238 or $\ce{U-238}$ or $\ce{^{238}U}$
```


## What is mass?

### Atomic Mass

Atomic mass is the mass of an atom in *amu*. When you look up the atomic mass of most elements in a periodic table, those values are usually not whole numbers. The difference arises because most naturally occurring elements have more than one isotope. This means that generally, when we determine the atomic mass of an element, what we are actually measuring is the *average atomic mass* of the naturally occurring mixture of isotopes.  The average atomic mass of an element is a weighted, average mass of all the isotopes present in a naturally occurring sample of that element. This is equal to the sum of each individual isotope’s mass multiplied by its fractional abundance.

```{math}
:label: averagemass

\text{average mass} = ∑_i (\text{fractional abundance} \times \text{isotopic mass})_i
```

```{dropdown} Example: Calculating average atomic masses

Naturally occurring $\ce{C}$ has two major stable isotopes - $\ce{^{12} C}$ ($99\%$ of all stable $\ce{C}$) and $\ce{^{13} C}$ ($1\%$  of all stable $\ce{C}$). 

The atomic mass of $\ce{^{12} C}$ and $\ce{^{13} C}$ is $\pu{12 amu}$ and $\pu{13 amu}$, respectively. Using Eq. {eq}`averagemass` we can calculate the overall atomic mass of naturally occurring $\ce{C}$:  

>$$
= \frac{99}{100} \times \pu{12 amu} + \frac{1}{100}\times \pu{13 amu} = \pu{12.01 amu}
$$
```


### Mole

Atoms are so tiny that even the smallest quantity of matter contains an enormous number of atoms.  It is very useful to know exact number of atoms involved in a chemical reaction. For convenience, chemists use a unit of measurement called the **mole** to denote these large number of atoms.  A **mole** which is defined as the amount of a substance that contains as many elementary entities (e.g., atoms, ions, etc.) as there are atoms in exactly $\pu{0.012 kg}$ ($\pu{12 g}$) of carbon-12. The number of (experimentally determined) atoms in exactly $\pu{12 g}$ of carbon-12 is known as **Avogadro's Number** ($N_A$).
```{margin}
```{note}
After Italian scientist Amedeo Avogadro (1776-1856). See this link to read about Avogadro: (https://en.wikipedia.org/wiki/Amedeo_Avogadro}.
```

 The currently accepted value of Avogadro's number is $\pu{6.0221418e23}$, although we usually round this number to $\pu{6.022e23}$. 
 
 [How big is a mole? (Not the animal, the other one.) -  TED-Ed](https://ed.ted.com/lessons/daniel-dulek-how-big-is-a-mole-not-the-animal-the-other-one).
<div class="container">
<iframe src="https://www.youtube.com/embed/TEl4jeETVmg" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

### Molar Mass

We know the number of atoms present in a mole of any substance, but *how much does this mole weigh*? Literally, we need to know the weight of each atom of that substance and add all these masses. An easier way to deal with this is the molar mass concept. 

The molar mass of a substance is the mass in *grams* of one mole of a substance. Atomic mass has the units of *atomic mass units* or *amu*.

```{dropdown} Example: Calculating molar masses:
Carbon-12 or $\ce{^{12} C}$ (most abundant stable isotope of $\ce{C}$) is used the standard example -- mass of one mole of $\ce{^{12} C}$ is exactly $\pu{12 g}$, i.e., molar mass of $\ce{^{12} C}$ is equal to its atomic mass in grams.  The overall molar mass of naturally occurring $\ce{C}$ 

>$$
= \frac{99}{100} \times \pu{12 g} + \frac{1}{100}\times \pu{13 g} = \pu{12.01 g}
$$
```

So how do we convert from moles to molar masses to number of atoms?  Set up conversion factors such that units are explicitly shown and are consistent.

```{dropdown} Example: Conversion of moles to grams
Ca is the most abundant metal in the human body. A typical human body contains roughly $\pu{30 moles}$ of $\ce{Ca}$. 

$$	
30\ \cancel{\text{moles Ca}}\times \dfrac{\pu{6.022e23 atoms Ca}}{1\ \cancel{\text{mole Ca}}} = \pu{1.807e25 atoms Ca} 
$$	
and

$$	
30\ \cancel{\text{moles Ca}}\times \frac{\pu{40.078 g Ca}}{1\ \cancel{\text{mole Ca}}} = \pu{1202.3 g Ca}
$$

Therefore, there are $\pu{1202.3 g Ca}$ in an average human body.
```

```{dropdown} Example: Conversion of grams to atoms
Copper is commonly used to fabricate electrical wire. How many copper atoms are in $\pu{5.00 g}$ of copper wire?

**Answer:**

The number of $\ce{Cu}$ atoms in the wire may be conveniently derived from its mass by a two-step computation: first calculating the molar amount of $\ce{Cu}$, and then using Avogadro’s number ($N_A$) to convert this molar amount to number of $\ce{Cu}$ atoms:

![](https://openstax.org/apps/archive/20221109.213337/resources/4e96501f65cccee7575915387b18ab45e3340551)

$$
\pu{5.00 g}\ \ce{Cu} \dfrac{\text{mol Cu}}{\pu{63.55 g}} \dfrac{\pu{6.022e23 atoms}}{\text{mol}} = \pu{4.74e22 atoms Cu}
$$

```


##  Chemical Formulas

A chemical formula denotes composition of any chemical substance. In a **molecular formula**, exact number of atoms of each element in a molecule are shown.


### Molecular formulas

$\ce{H2}$ is the molecular formula for hydrogen, $\ce{O2}$ is that for oxygen, $\ce{CO2}$ is that for carbon dioxide, and $\ce{H2O}$ is that of water. The subscript number indicates the number of atoms of an element present in the molecule. There is no subscript for $\ce{O}$ in $\ce{H2O}$ because there is only one oxygen atom in a molecule of water and $1$ is never used as a subscript in a chemical formula. 


### Structural Formulas

**Structural formulas** not only show the elemental composition, they also show the general arrangement of the atoms within the molecule. See different representations in {numref}`type-formula` and {numref}`caffeine`.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/700be7a9676f6d5263fecd751061677c47d678d0
---
name: type-formula
figclass: margin-caption
---
A methane molecule can be represented as (a) a molecular formula, (b) a structural formula, (c) a ball-and-stick model, and (d) a space-filling model. Carbon and hydrogen atoms are represented by black and white spheres, respectively. Image source: [2.4 Chemical Formulas - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/2-4-chemical-formulas)
```

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/c/cc/Caffeine_molecule_ball_from_xtal_%281%29.png/1024px-Caffeine_molecule_ball_from_xtal_%281%29.png
---
width: 300 px
name: caffeine
figclass: margin-caption
---
Molecular structure of caffeine molecule. The structure is shown as a ball-and-stick model with color of each ball represents an atom of a specific element. Typically black ball are $\ce{C}$, blue balls are $\ce{N}$, white balls are $\ce{H}$, and the red balls are $\ce{O}$.  Source: [Caffeine - Wikipedia](https://en.wikipedia.org/wiki/Caffeine)
```

### Empirical Formulas

**Empirical** ("from experience" or "experimentally") formulas tell which elements are present in a molecule and in what whole-number ratio relative to each other.  This is usually determined experimentally.  It is the simplest chemical formula possible for any molecule.  Usually, it is written by reducing the subscripts of molecular formulas to the smallest possible whole number.  But, molecular formulas are *true formulas of molecules*.


```{dropdown} Example of empirical formulas
Below are some examples of molecular and empirical formulas.

| Compound | Molecular Formula | Empirical formula |  
| --- | :---: | :---: |
|Water | $\ce{H2O}$ | $\ce{H2O}$ | 
|Hydrogen Peroxide | $\ce{H2O2}$ | $\ce{HO}$ | 
|Propane | $\ce{C3H8}$ | $\ce{C3H8}$ |
|Benzene | $\ce{C6H6}$ |  $\ce{CH}$ |
```


In above example, water and propane already have the simplest formula possible with whole number subscripts. Therefore, both molecular and empirical formulas are same.


### Molecular and Formula Masses

Molecular mass is the sum of the atomic masses (in *amu*) of the atoms that make up the molecule. Often, molecular mass is referred to as *molecular weight*.


```{dropdown} Example: Molecular mass
Molecular mass of $\ce{H2O = 2(atomic mass of H) + atomic mass of O}$
= $2(\pu{1.008 amu}) + \pu{16.00 amu} = \pu{18.02 amu}$
```

Since ionic compounds are not whole molecules, their masses are based on their empirical formulas and are called *formula mass* or *formula weight*.

```{dropdown} Examples of molecular and formula masses

| Compound | Chemical Formula | Molecular Mass, $\pu{amu}$ | Empirical Mass, $\pu{amu}$ |
|--- | --- | ---: | ---: |
|Water | $\ce{H2O}$ | $18.02$ | $18.02$ |
|Hydrogen Peroxide | $\ce{H2O2}$ | $34.01$ | $17.01$ |
|Propane | $\ce{C3H8}$ | $44.10$ | $44.10$ |
|Benzene | $\ce{C6H6}$ | $78.11$ |  $13.02$ |
```


## Percent Composition

If we know the molecular or empirical formula of a compound, we can easily estimate the percent composition by mass of each element in that compound. Percent composition of each element is calculated as:

```{math}
:label: percent-comp

\text{% mass of an element} = \dfrac{n\times\text{atomic mass of element}}{\text{molecular/formula mass of compound}}\times 100
```

where $n$ is number of atoms of the element in the compound.  A list or table of the percent by mass of each element in a compound is known as the compound's *percent composition by mass*.

```{dropdown} Example: Calculating percent composition of _ $\ce{H2O}$

Atomic masses of $\ce{H}$ and $\ce{O}$ are $\pu{1.008 amu}$ and $\pu{16.00 amu}$ respectively, the molecular mass of $\ce{H2O}$ is $\pu{18.02 amu}$. Percent composition is as follows:

$$
\begin{align}
\ce{H} &= \dfrac{2\times \pu{1.008 amu}\, \ce{H}}{\pu{18.02 amu}\, \ce{H2O}} \times 100 = \pu{11.19 \%} \\
\ce{O} &= \dfrac{1\times \pu{16.00 amu}\, \ce{O}}{\pu{18.02 amu}\, \ce{H2O}} \times 100 = \pu{88.81 \%}
\end{align}
$$

The sum of the percentages add up to $\pu{100 \%}$.
```


## Determining Chemical Formulas

Percent composition is often determined experimentally and precisely using very sensitive analytical instrumentation.  This information can be used to determine the empirical formula of a substance of interest.

```{admonition} Rules for determining empirical formulas

1. Determine weight percent of each element in the compound
2. Determine weight in grams of each element per 100 g of compound
3. Divide weight of each element in grams by atomic weight to determine the number of moles
4. Using the element with the least number of moles, determine the relative number of moles of all other elements -- these integers represent the formula for the compound
```

It is best to set this up as a table.  See example below.

```{dropdown} Example: Determining chemical formulas
During a chemical reaction a precipitate forms.  The percent mass was determined experimentally as follows: $\ce{Ca} = \pu{39.74 \%}$, $\ce{P} = \pu{18.42 \%}$, $\ce{O} = \pu{38.07 \%}$, and $\ce{F} = \pu{3.77 \%}$.  Determine the chemical formula for this compound. 	

**Answer:**

First, let's set this information up as a table and calculate the moles of each element.

| Element | Wt., % |  Wt./100 g |  At. Wt. | Moles | Rel. Moles |
| --- | ---: |  ---: |  ---: |  ---: |  ---: | 
| $\ce{Ca}$ | $39.74$ | $39.74$ | $40.08$ | $0.992$ | $5$ | 
| $\ce{P}$ | $18.42$ | $18.42$ | $30.97$ | $0.595$ | $3$ |
| $\ce{O}$ | $38.07$ | $38.07$ | $16.00$ | $2.379$ | $12$ | 
| $\ce{F}$ | $3.77$ | $3.77$ | $19.00$ | $0.198$ | $1$ |

Based on this information, the formula of the compound is $\ce{Ca5P3O12F}$. If we re-arranged this formula, we get $\ce{Ca5(PO4)3F}$ (fluorapatite).
```

In the above example, since the percent mass was determined experimentally, the resulting formula is considered to be an empirical formula, or the simplest whole-number ratio of atoms that make up a compound.  If we know or determined the molecular weight of this compound by other means, we could compare the formula and molecular weights and then determine exact molecular formula.

```{dropdown} Example: Determining molecular formula

If the empirical formula of a compound is $\ce{CH3}$ and its molecular weight is $\pu{30 g}$, the molecular formula can be determined as follows. 

**Answer:**

First, calculate the formula weight of 

$$
\begin{align}
\ce{
CH3 &= \pu{12.01 g mol-1} C + 3(\pu{1.008 g mol-1} H) \\
&=  \pu{15.03 g mol-1} CH3
}
\end{align}
$$ 

Since the molecular weight is twice the formula weight, the molecular formula is $\ce{C2H6}$.

```

## Solutions and Concentrations

*Concentration* is a major factor that can influence reactions in aqueous solutions.  It is defined as the amount of solute dissolved in a given quantity of solvent or solution.

Molarity, or molar concentration, $\pu{M}$, is defined as the number of moles of solute per liter of solution and can also be written as $\pu{mol L-1}$.

