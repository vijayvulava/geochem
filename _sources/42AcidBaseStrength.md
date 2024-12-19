# 4.2 Strength of Acids and Bases

## How strong are acids and bases?

The strength of acids and bases is measured by their tendency to ionize. Consider a hypothetical strong acid $\ce{HX}$ that readily ionizes in water.

$$\ce{
HX ->[H2O] H+ + X-
}$$

In the above case, weak $\ce{H-X}$ bonds within the molecular structure can result in strong ionization and vice versa. This bond strength is referred to as bond enthalpy. Another factor that impacts the strength of acids is polarity in the $\ce{H-X}$ bond or the difference in electronegativity in the main bond. When the above $\ce{H-X}$ is highly polarized, $\ce{HX}$ tends to break up into $\ce{H+}$ and $\ce{X-}$. Therefore, high polarity results in stronger acids (or bases).

[The strengths and weaknesses of acids and bases - TED-Ed](https://ed.ted.com/lessons/the-strengths-and-weaknesses-of-acids-and-bases-george-zaidan-and-charles-morton)

<div class="container">
<iframe src="https://www.youtube.com/embed/DupXDD87oHc" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Generally, hydrohalic acids (acids with halide conjugate base) are strong except $\ce{HF}$. The strength of these acids are as follows: 

$$\ce{HF} \ll \ce{HCl} < \ce{HBr} < \ce{HI}$$

The strength of oxoacids (acids that contain $\ce{H}$, $\ce{O}$, and a central, nonmetal atom) increases with the electronegativity of a central nonmetal atom. For example, since $\ce{Cl}$ is more electronegative than $\ce{Br}$, therefore the strength of these acids are:

$$\ce{HClO3} > \ce{HBrO3}$$
When oxoacids have the same central atom but a different number of $\ce{O}$ atoms, the strength of the acid is directly proportional to the number of $\ce{O}$ atoms present (or directly proportional to the oxidation state of a central atom). For example,

$$\ce{HClO4} > \ce{HClO3} > \ce{HClO2} > \ce{HClO}$$

There are only a few strong acids and include: $\ce{HCl}$, $\ce{HBr}$, $\ce{HI}$, $\ce{HNO3}$, $\ce{HClO3}$ (chloric acid), $\ce{HClO4}$ (perchloric acid), and $\ce{H2SO4}$. Because the ionization of these strong acids in water is $\pu{100 \%}$ complete, $\{\ce{H3O+}\}$ is the same as the initial concentration of the acid.

```{dropdown} Example: $p\ce{H}$ of strong acids 

Calculate the $p\ce{H}$ of $\pu{0.035 M}$ $\ce{HI}$ at $\pu{25 ^\circ C}$. 

>Because $\ce{HI}$ is a strong acid, it reacts as follows:
>
>$$\ce{
HI + H2O -> H3O+ + I-
}$$
>Therefore, according to the reaction stoichiometry, $\pu{0.035 M}$ $\ce{HI}$ produces $\pu{0.035 M}$ of $\ce{H3O+}$. Therefore, 
>
>$$p\ce{H}= -\log_{10}(\ce{H3O+}) = -\log_{10}(0.035) = 1.46$$
```

Hydroxides of alkali metals (Group 1 - e.g., $\ce{LiOH}$, $\ce{NaOH}$, $\ce{KOH}$, $\ce{RbOH}$, $\ce{CsOH}$) and alkaline earth metals (Group 2 - e.g., $\ce{Ca(OH)2}$, $\ce{Mg(OH)2}$, and $\ce{Ba(OH)2}$) are strong bases.

```{dropdown} Example: $p\ce{H}$ of strong bases
 
Calculate $p\ce{H}$ of $\pu{0.018 M}$  NaOH at $\pu{25 ^\circ C}$. 

>Because $\ce{NaOH}$ is a strong base, it produces $\pu{0.018 M}$ of $\ce{OH-}$. There are two ways we can calculate $p\ce{H}$.
>
>Approach 1. Substitute $\{\ce{OH-}\}$ in Eq. {eq}`kw2`:
>
>$$\begin{aligned}
\{\ce{H3O+}\}\{\ce{OH-}\} &=  \pu{1.0e-14}\\
\{\ce{H3O+}\} &= \frac{\pu{1.0e-14}}{\{\ce{OH-}\}} \\
&= \frac{\pu{1.0e-14}}{(0.018)} = \pu{5.56e-13}\\
p\ce{H} &= -\log(\pu{5.56e-13}) =12.25
\end{aligned}$$

>Approach 2: Calculate $p\ce{OH}$ from $\{\ce{OH-}\}$ and substitute this value in Eq. {eq}`phpoh`: 
>
>$$\begin{aligned}
p\ce{OH} &= -\log(0.018) = 1.75\\
p\ce{H} &= 14.0 - p\ce{OH} = 14.0-1.75 = 12.25
\end{aligned}$$
```


## Acid ionization constants

Most acids are weak and only partially ionize in water. At equilibrium, an aqueous solution of a weak acid contains a mixture of aqueous acid molecules, the corresponding conjugate base, and $\ce{H3O+}$. The degree to which a weak acid ionizes depends on the acid concentration and the equilibrium constant for the ionization.

Consider a weak monoprotic acid $\ce{HA}$, whose ionization in water can be represented as

$$\ce{
HA <=>[H2O] H+ + A-
}$$

The equilibrium expression for this reaction can be written as:

```{math}
:label: ka

K_a = \frac{\{\ce{H+}\}\{\ce{A-}\}}{\{\ce{HA}\}}
```

In Eq {eq}`ka` $K_a$  is a special equilibrium constant called the ***acid ionization constant***. The magnitude of $K_a$ indicates the strength of an acid. A large $K_a$ value indicates a stronger acid, whereas a small $K_a$ value indicates a weaker acid.

Weak acids do not completely dissociate. Hence, we must use the *ICE method* setup introduced in the previous chapter to solve equilibrium problems.


```{dropdown} Example: Equilibrium $p\ce{H}$  of weak acid solutions 

Calculate  at equilibrium of $\pu{0.5 M}$ $\ce{HF}$ solution at $\pu{25 ^\circ C}$. 

>This equilibrium reaction is 
>
>$$\ce{
HF + H2O <=> H3O+ + F- \qquad $K_a = \pu{7.1e-4}$
}$$
>
>Let's set the ICE table for this problem
>
>|   | $\ce{HF(aq)}$ | $+$ | $\ce{H2O (l)}$ | $\rightleftharpoons$ | $\ce{H3O+ (aq)}$ | $+$ | $\ce{F- (aq)}$ |
>|---|------------|-----|------|--------|---------------|-----|------|
>| [I] | $0.5$      |     |      |       | $0$    |     | $0$         |
>| [C] | $-x$       |     |   |     | $+x$          |     | $+x$        |
>| [E] | $(0.5-x)$  |     |   |    | $(+x)$        |     | $(+x)$      |
>
>We can now substitute these into Eq. {eq}`ka` 
>
>$$K_a = \frac{\{\ce{H3O+}\}\{\ce{F-}\}}{\{\ce{HF}\}} = \frac{(+x)(+x)}{(0.5-x)} = \pu{7.1e-4}$$
>
>The above expression can be simplified into a quadratic expression and be solved for $x$. In this case, $x = \pu{1.9e-2}$ or from the above table $\{\ce{H3O+}\} = x = \pu{1.9e-2}$ or $p\ce{H} = 1.72$. 
```

```{dropdown} Example: Relative abundance of weak acids 

We can calculate the relative abundance of the conjugate base of a weak acid by examining the equilibrium expression. In the $\ce{HF}$ ionization reaction shown in the previous example, the expression can be rearranged as 

>$$
 \begin{align*}
    K_a &= \frac{\{\ce{H3O+}\}\{\ce{F-}\}}{\{\ce{HF}\}}\\
    \frac{\{\ce{F-}\}}{\{\ce{HF}\}} &= \frac{K_a}{\{\ce{H3O+}\}} 
\end{align*}
$$
>
>For any given $\{\ce{H3O+}\}$ (or $p\ce{H}$), we can calculate the relative abundance of weak acids. We can express this ratio in $\%$ by multiplying by $100$.
>
>Percent ionization is calculated as follows:
>
>$$\frac{\{\ce{F-}\}}{\{\ce{HF}\}} \times \pu{100 \%}$$
```

````{margin}
For more information, see [14.3 Relative Strengths of Acids and Bases - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/14-3-relative-strengths-of-acids-and-bases) and [14.4 Hydrolysis of Salt Solutions - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/14-4-hydrolysis-of-salt-solutions).
````


## Carbonic acid system

Carbonic acid ($\ce{H2CO3}$) is the most abundant acid in natural waters and is also a weak acid. Along with its salt, $\ce{CaCO3}$, it forms a buffer that plays an important role in regulating the natural waters. Hence, understanding the carbonic acid system is essential to understanding the $p\ce{H}$ of natural waters.

$\ce{CO2(g)}$ dissolves in water in the sequence as shown below.  Closely note the states of matter and the arrows between reactants and products.

```{math}
:label: co2-dissol
\begin{align*}
\ce{
CO2(g) &<=> CO2(aq) \\
CO2(aq) &<<=> H2CO3(aq) 
}
\end{align*}
```

The above two reactions cannot be separated, and it is often difficult to distinguish between $\ce{CO2(aq)}$ and $\ce{H2CO3(aq)}$. Often, scientists use the term $\ce{H2CO3^*}$ to denote the sum of $[\ce{CO2(aq)}]$ and $[\ce{H2CO3(aq)}]$. At $\pu{25 ^\circ C}$, $[\ce{CO2(aq)}]$  makes up $\pu{99.85 \%}$ of this sum and may be more acceptable to the use of $\ce{H2CO3^*}$. In this text, we will use $\ce{H2CO3^*}$ to represent carbonic acid.

The equilibrium relationship of reaction {eq}`co2-dissol` can be expressed as

$$K_H = \frac{[\ce{CO2 (aq)}]}{P_{\ce{CO2 (g)}}} = \pu{10^{-1.47} mol L-1 atm-1}$$

The $K_H$ is a special equilibrium constant called the ***Henry's Law constant*** and is used for equilibrium reactions involving gas dissolution in water. Using the $K_H$, $[\ce{H2CO3^*}]$ can be calculated for different atmospheric concentrations.

```{dropdown} Example: Application of $K_H$

If we assume that $[\ce{CO2(g)}]$ is $\pu{400 ppm}$ (= $\pu{400e-6 atm}$),

>$$\begin{aligned}
[\ce{CO2 (aq)}] &= K_H P_{\ce{CO2 (g)}} \\
&= \pu{10^{-1.47} mol L-1 atm-1} \times \pu{400e-6 atm} \\
&= \pu{10^{-4.87} mol L-1}
\end{aligned}
$$

```

At $\pu{25 ^\circ C}$, the $\ce{H2CO3^*}$ dissociates in water as follows,

```{math}
:label: h2co3-ka1ka2
\begin{align}
\ce{
H2CO3(aq) &<=> H+ (aq) + HCO3- (aq) \qquad $K_{a1} = \pu{4.47e-7}$\\
HCO3- (aq) &<=> H+ (aq) + CO3^2- (aq) \qquad $K_{a2} = \pu{4.68e-10}$
}
\end{align}
```

The relative abundance of $\ce{H2CO3^* (aq)}$, $\ce{HCO3- (aq)}$, and $\ce{CO3^2- (aq)}$ at any $p\ce{H}$ can be calculated by applying the Law of Mass Action expression to reactions {eq}`h2co3-ka1ka2`. These expressions can be rearranged and expressed as: 

```{math}
:label: co3-ka1-ka2-exp
\begin{align}
\frac{[\ce{H2CO3^* (aq)}]}{[\ce{HCO3- (aq)}]} &= \frac{[\ce{H3O+ (aq)}]}{K_{a1}}  \\
\frac{[\ce{HCO3- (aq)}]}{[\ce{CO3^2- (aq)}]} &= \frac{[\ce{H3O+ (aq)}]}{K_{a2}} 
\end{align}
```

The total carbonate concentration ($\ce{C}_T$) present in an aqueous system can be considered constant. If we assume that all carbonate is only present in this aqueous system in the forms of $\ce{H2CO3^* (aq)}$, $\ce{HCO3- (aq)}$, and $\ce{CO3^2- (aq)}$, we can use mass balance concepts to determine absolute abundance as follows:

```{math}
:label: ct-exp
\ce{C}_T = [\ce{H2CO3^* (aq)}] + [\ce{HCO3- (aq)}] + [\ce{CO3^2- (aq)}] 
```

Equilibrium expressions  {eq}`co3-ka1-ka2-exp` can be combined with equation {eq}`ct-exp` and simplified as:

```{math}
:label: ct-expanded
\ce{C}_T = [\ce{H2CO3^* (aq)}]\left(1 + \frac{K_{a1}}{[\ce{H3O+}]} + \frac{K_{a1} K_{a2}}{[\ce{H3O+}]^2}\right) 
```

We now have an expression that relates total carbonate to the amount of. This is a very useful expression. To simplify subsequent equations, we will define a variable, $\alpha_\text{H}$, that encompasses all of the terms inside the parentheses in equation {eq}`ct-expanded`. Note that this portion of the equation deals with $p\ce{H}$  of the aqueous system.

```{math}
:label: alpha-h
\alpha_\ce{H} = \left(1 + \frac{K_{a1}}{[\ce{H3O+}]} + \frac{K_{a1} K_{a2}}{[\ce{H3O+}]^2}\right)
```

We can now determine $[\ce{H2CO3^* (aq)}]$, $[\ce{HCO3- (aq)}]$, and $[\ce{CO3^2- (aq)}]$, by combining equations eq {eq}`co3-ka1-ka2-exp` and {eq}`ct-expanded` as follows: 

```{math}
:label: ct-alpha
\begin{align}
[\ce{H2CO3^* (aq)}] &= \frac{\text{C}_T}{\alpha_\text{H}}\\
[\ce{HCO3^- (aq)}] &= \frac{\text{C}_T K_{a1}}{[\ce{H3O+}] \alpha_\text{H}}\\
[\ce{CO3^2- (aq)}] &= \frac{\text{C}_T K_{a1} K_{a2}}{[\ce{H3O+}]^2 \alpha_\text{H}}
\end{align}
```
 
All carbonate species concentrations can be determined if $\ce{C}_T$ and $p\ce{H}$ are known in any given system.

## Silicic acid system

Silicic acid ($\ce{H4SiO4}$) is a common byproduct of silicate mineral weathering and weak acid. This is a "tetraprotic acid," meaning it can release four $\ce{H+}$ in four dissociation steps. Only the first two dissociation steps are environmentally relevant. At $\pu{25 ^\circ C}$, dissociates in water as follows,

```{math}
:label: silicate
\begin{align}
\ce{
H4SiO4 + H2O &<=> H3SiO4- + H3O+ \qquad  $K_{a1} = \pu{10^{-9.83}}$\\
H3SiO4- + H2O &<=> H2SiO4^2- + H3O+ \qquad  $K_{a2} = \pu{10^{-13.17}}$
}
\end{align}
```

## Weak bases and base ionization constants

Just like acids, most bases only partially ionize in water. At equilibrium, an aqueous solution of a weak base contains a mixture of aqueous base molecules, $\ce{OH-}$, and the corresponding conjugate acid. The ionization can be treated very similar to that of a weak acid.

Consider a weak base $\ce{B}$ (and the conjugate acid, $\ce{HB+}$), whose ionization in water can be represented as

$$\ce{
B + H2O <=> HB+ + OH-
}$$

The equilibrium expression for this reaction can be written as:

```{math}
:label: kb

K_b = \frac{\{\ce{HB+}\}\{\ce{OH-}\}}{\{\ce{B}\}}
```

$K_b$  is special equilibrium constant called the ***base ionization constant***.

$K_a$ and $K_b$ are related to $K_w$ by following relationship.

```{math}
:label: kakb

K_a \times K_b = K_w
```


## Amphoteric Compounds and Hydrated Metal Ions

Unlike the group 1 and 2 metal ions ($\ce{Na+}$, $\ce{Ca^2+}$, etc.), some metal ions function as acids in aqueous solutions. These ions are covalently bonded to a fixed number of water molecules to yield a complex ion. 


```{figure} https://openstax.org/apps/archive/20230220.155442/resources/68a314671bf83af3515776c96ec37c9d7555f061
---
name: trans-elem-coord
figclass: margin-caption
---
(a) Covalent bonds involve the sharing of electrons, and ionic bonds involve transferring electrons associated with each bonding atom, as indicated by the colored electrons. (b) Coordinate covalent bonds involve electrons from a Lewis base being donated to a metal center. The lone pairs from six water molecules form bonds to the scandium ion to form an octahedral complex.   Image source: [19.2 Coordination Chemistry of Transition Metals - Chemistry 2e | OpenStax](https://openstax.org/books/chemistry-2e/pages/19-2-coordination-chemistry-of-transition-metals)
```

For example, the dissolution of aluminum nitrate in water is typically represented as

$$
\ce{Al(NO3)3 (s) <=> Al^3+ (aq) + 3 NO3- (aq) }
$$

However, the $\ce{Al^3+ (aq)}$ reacts with six $\ce{H2O}$ molecules to form a stable complex ion, and so the more explicit representation of the dissolution process is shown below:

$$
\ce{Al(NO3)3 (s) 6 H2O (l) <=> Al(H2O)6^3+ (aq) + 3 NO3- (aq) }
$$

As shown in {numref}`al-solvation`, the $\ce{Al(H2O)6^3+}$ involve bonds between a central $\ce{Al}$ atom and the $\ce{O}$ atoms of the six water molecules. Consequently, the bonded water molecules' $\ce{O–H}$ bonds are more polar than in nonbonded water molecules, making the bonded molecules more prone to donation of a $\ce{H+}$ as shown below:

$$
\ce{
Al(H2O)6^3+ (aq) + H2O (l) <=> H3O+ (aq) + Al(H2O)5(OH)^2+ (aq) \qquad $K_a = \pu{1.4e-5}$
}
$$

```{figure} https://openstax.org/apps/archive/20230220.155442/resources/c32762e9e5627c8a1683e4944a50bfd1619ba4f9
---
name: al-solvation
figclass: margin-caption
---
When an aluminum ion reacts with water, the hydrated aluminum ion becomes a weak acid.  Image source: [14.4 Hydrolysis of Salts - Chemistry 2e | OpenStax](https://openstax.org/books/chemistry-2e/pages/14-4-hydrolysis-of-salts)
```

The conjugate base produced by the above process contains five other bonded water molecules capable of acting as acids.

```{math}
:label: aluminum-dissoc
\begin{align}
\ce{
Al(H2O)6^3+ (aq) + H2O (l) <=> H3O+ (aq) + Al(H2O)5(OH)^2+ (aq)\\
Al(H2O)5(OH)^2+ (aq) + H2O (l) <=> H3O+ (aq) + Al(H2O)4(OH)2^+ (aq)\\
Al(H2O)4(OH)2^+ (aq) + H2O (l) <=> H3O+ (aq) + Al(H2O)3(OH)3 (aq)
}
\end{align}
```

Most metal ions (transition metals) will undergo acid ionization to some extent when dissolved in water. The acid strength of these complex ions typically increases with the metal ions' increasing charge and decreasing size. Many natural metal oxides (e.g., $\ce{Al2O3}$, $\ce{Fe2O3}$, both of which are common components of natural soils) and hydroxides (E.g., $\ce{Al(OH)3}$, $\ce{Fe(OH)3}$ - both are components of natural soils) can act as both acids and bases as they respond to change in the bulk solution conditions.

```{dropdown} Example: Amphoteric acids and bases

Aluminum oxide ($\ce{Al2O3}$) is amphoteric. It can behave as an acidic or a basic oxide depending on the reaction conditions. 

>For example, $\ce{Al2O3}$ acts as a base with hydrochloric acid ($\ce{HCl}$) to produce a salt ($\ce{AlCl3}$) and $\ce{H2O}$,
>
>$$\ce{
Al2O3 + 6 HCl -> 2 AlCl3 + 3 H2O
}$$
>and acts as an acid with sodium hydroxide ($\ce{NaOH}$),
>
>$$\ce{
Al2O3 + 2 NaOH + 3 H2O -> 2 NaAl(OH)4
}$$
>
>Aluminum hydroxide reacts with both acids and bases similarly:
>
>$$
\begin{align}
\ce{
Al(OH)3 + 3 H+ &-> Al^3+ + 3 H2O\\
Al(OH)3 + OH- &-> Al(OH)4^-
}
\end{align}$$
```

The amphoteric nature of metal oxides and hydroxides is often exploited in water and wastewater treatment and the treatment of metal-contaminated soils and groundwater. By adding acids or bases to solutions, metal contaminants in solid form could be "mobilized" into aqueous solutions.


## Common Ions and Buffering

A buffer solution resists changes when acids or bases are added. This is possible in solutions that contain a weak acid and its conjugate base (or a weak base and its conjugate acid). To understand this, let's explore the ***common ion effect***, which is easily observable in the acetic acid-acetate system.

```{dropdown} Example: Common ion effect 

Calculate $p\ce{H}$ of a $\pu{0.1 M}$ $\ce{CH3COOH}$ (acetic acid) solution. The $K_a$ for $\ce{CH3COOH}$ is $\pu{1.8e-5}$ at $\pu{25 ^\circ C}$.

$$\ce{
CH3COOH <=> H+ + CH3COO- 
}$$

>Let's calculate the concentrations of all components at equilibrium using the ICE method.
>
>|   | $\ce{CH3COOH (aq)}$ | $\ce{H+ (aq)}$ | $\ce{CH3COO- (aq)}$ |
>|---|------------------|-------------|------------------|
>| [I] | $0.1$            | $0$         | $0$              |
>| [C] | $-x$             | $+x$        | $+x$             |
>| [E] | $0.1-x$          | $+x$        | $+x$             |
>
>The solution to this problem yields: $[\ce{CH3COOH (aq)}] = \pu{0.099 M}$, $[\ce{CH3COO- (aq)}] = [\ce{H+ (aq)}] = \pu{1.34e-3 M}$ or $p\ce{H} = 2.87$.
>
>Now, let's add $\pu{0.05 M}$ of $\ce{CH3COONa}$ (the $\ce{Na}$ salt of acetic acid) to the above $\ce{CH3COOH (aq)}$ solution.  $\ce{CH3COONa}$ dissociates strongly into ionic form as follows:
>
>$$\ce{
CH3COONa (aq) -> CH3COO- (aq) + Na+ (aq)
}$$
>
>Adding the above two reactions increases the concentration of $\ce{CH3COO- (aq)}$ in the original reaction.  Le Châtelier's principle tells us that increasing product concentration will drive the reaction to the left.
>
>$$ \ce{
CH3COOH (aq)) <<=>  H+ (aq) +  CH3COO- (aq)
} $$
>
>This shift of equilibrium to the left consumes not only some of the $\ce{CH3COO- (aq)}$, but also some of the $\ce{H+ (aq)}$ (a strong acid) to form $\ce{CH3COOH (aq)}$, a weak acid.  Therefore, the $p\ce{H}$ of the solution increases.  Let's calculate the new equilibrium concentrations using the ICE method as above, but with different initial concentrations.
>
>|   | $\ce{CH3COOH (aq)}$ | $\ce{H+ (aq)}$ | $\ce{CH3COO- (aq)}$|
>|---|------------------|-------------------|--------------------|
>| [I] | $0.099$      | $\pu{1.34e-3}$     | $\pu{5.134e-2}$     |
>| [C] | $+y$             | $-y$              | $-y$               |
>| [E] | $0.099+y$        | $\pu{1.34e-3} -y$ | $\pu{5.134e-2} -y$ |
>
>The solution to this problem yields: [$\ce{H+ (aq)}$] = $\pu{3.6e-5 M}$ or $p\ce{H} = 4.44$, or as expected $p\ce{H}$ increased.
```

In the above solution, a soluble salt that contained a common ion shifted the equilibrium to the left, thereby suppressing the ionization of the weak electrolyte. Generally, when a compound containing an ion in common with a dissolved substance is added to a solution at equilibrium, the equilibrium shifts to the left. This phenomenon is known as the *common ion effect*. The common ion can also be $\ce{H+}$ or $\ce{OH-}$. Adding a strong acid to a weak acid's solution suppresses the weak acid's ionization. Similarly, adding a strong base to a solution of a weak base suppresses the ionization of the weak base.

```{dropdown} Example: Common ion effect due to addition of $\ce{H+}$ or $\ce{OH-}$

What happens when you add $\ce{H+}$ or $\ce{OH-}$ to the previous acetate system?

>Adding $\ce{H+}$ to the acetate system:
>
>$$\ce{
H+ + CH3COO- -> CH3COOH
}$$
>
>Or, a strong acid ($\ce{H+}$) turns into a weak acid ($\ce{CH3COOH}$)!
>
>Adding $\ce{OH-}$ to the acetate system:
>
>$$\ce{
CH3COOH + OH- -> CH3COO- + H2O
}$$
>
>Or, a strong base ($\ce{OH-}$) turns into a weak base ($\ce{CH3COO-}$)!

```

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/1c77469757bdebda940b86afc5133f1a34578d22
---
name: acetate-buffer
figclass: margin-caption
---
This figure summarizes the buffering action of an $\ce{CH3COOH-CH3COO-}$ system.
```


```{dropdown} Example: Acetate buffer system 

Consider a solution that is $\pu{1.0 M}$ in $\ce{CH3COOH}$ and $\pu{1.0 M}$ $\ce{CH3COONa}$. Let's calculate $p\ce{H}$ of this system using the acetic acid reaction.

$$\ce{
CH3COOH <=> H+ + CH3COO- \qquad $K_{a} = \pu{1.8e-5}$
}$$

>Let's calculate the concentrations of all components at equilibrium using the ICE method.
>
>|   | $\ce{CH3COOH <=>}$ | $\ce{H+ +}$  | $\ce{CH3COO-}$ |
>|---|-----------------------------------|-----------|--------------|
>| [I] | $1.0$                             | $0$       | $1.0$        |
>| [C] | $-x$                              | $+x$      | $+x$         |
>| [E] | $1.0-x$                           | $+x$      | $1.0+x$      |
>
>The solution to this problem yields a $p\ce{H} = 4.74$.
>
>Now, let's add $\pu{0.1 M}$ of $\ce{HCl}$ to this system (assume that the addition of $\ce{HCl}$ doesn't change volume).  As the previous example shows, all added $\ce{H+}$ is converted to $\ce{CH3COOH}$.	
>
>$$\ce{
H+ + CH3COO- -> CH3COOH
}$$
>
>|       | $\ce{H+ +}$ | $\ce{CH3COO- ->}$ | $\ce{CH3COOH}$ |
>|---------------|-----------|-------------|--------------|
>| On addition of $\ce{H+}$    | $0.1$     | $1.0$    | $1.0$        |
>| On consumption of $\ce{H+}$ | $0$       | $0.9$    | $1.1$        |
>
>Let's use the ICE approach to determine this solution's final $p\ce{H}$ after adding $\ce{HCl}$.
>
>|   | $\ce{CH3COOH <=>}$ | $\ce{H+ +}$  | $\ce{CH3COO-}$ |
>|---|-----------------------------------|-----------|--------------|
>| [I] | $1.1$                             | $0$       | $0.9$        |
>| [C] | $-x$                              | $+x$      | $+x$         |
>| [E] | $1.1-x$                           | $+x$      | $0.9+x$      |
>
>The solution to this problem yields a $p\ce{H} = 4.66$. In other words, a drop of $0.08$ $p\ce{H}$ unit after adding the strong acid. In contrast, if there were no acetate present in the solution, $p\ce{H}$ of pure water in the presence of $\pu{0.1 M}$ HCl would have been $1.0$ ($-\log[\ce{H+}] = -\log(0.1) = 1.0$)!
```

The final $p\ce{H}$ of a buffer solution can be determined using the ***Henderson-Hasselbalch equation***, which can be derived from the equilibrium expression of dissociation of a weak acid. The final equation is given as:

```{math}
:label: henderson

p\ce{H} = pK_a + \log \frac{[\text{Conjugate Base}]}{[\text{Acid}]}
```

Equation {eq}`henderson` can be used to determine ideal concentrations and appropriate combinations of weak acids/conjugate bases that make effective buffer solutions.

```{dropdown} Example: Henderson-Hasselbalch Equation 

Let's use this equation to solve for the final $p\ce{H}$ when $\pu{0.1 M}$ of HCl was added to the solution containing $\pu{1.0 M}$ each of $\ce{CH3COOH}$ and $\ce{CH3COONa}$. From the previous example, we have [$\ce{CH3COOH}$] and [$\ce{CH3COO-}$] as $\pu{0.9 M}$ and $\pu{1.1 M}$, respectively. 

>Substitute these values in Eq. {eq}`henderson`.
>
>$$\begin{aligned}
    p\ce{H} &= pK_a + \log \frac{[\ce{CH3COO-}]}{[\ce{CH3COOH}]} \\
    &= 4.74 + \log \frac{\pu{0.9 M}}{\pu{1.1 M}}\\
    &= 4.65
\end{aligned}$$ 
>This $p\ce{H}$ value is similar to that obtained using the ICE approach.

```

````{margin}
For more information, see [14.6 Buffers - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/14-6-buffers).
````


## Soil Organic Matter

Soil carbon can act as a chemical buffer by regulating the soil's $p\ce{H}$. This is because soil carbon can help stabilize the concentration of $\ce{H+}$ in the soil, affecting the $p\ce{H}$. Soil carbon can also help to buffer against changes in the concentration of other ions, such as $\ce{CO3^2-}$, $\ce{NH4+}$, $\ce{NO3-}$, and $\ce{PO4^3-}$, which can also influence the $p\ce{H}$ of the soil. In this way, soil carbon can help maintain a relatively stable $p\ce{H}$ in the soil, which can benefit plant growth and other soil processes.

<div class="container">
<iframe src="https://www.youtube.com/embed/Ymy0IO7nizw" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

<div class="container">
<iframe src="https://www.youtube.com/embed/U0VyuddRq88" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

## Acidity and Alkalinity

Minerals in rocks undergo chemical weathering and release different types of ions into natural water systems, some of which can resist fluctuation in $p\ce{H}$ as shown in the preceding section.  This ability to resist change to $p\ce{H}$ due to adding acids and bases is called the ***buffering capacity*** of water. Volcanic and human activities release reactive gases such as $\ce{CO2}$, $\ce{SO2}$, and $\ce{NO_x}$, which interact with water creating acids and bases that affect natural water systems. However, the presence of ions such as $\ce{HCO3-}$ and $\ce{PO4^3-}$ in natural water can counteract the addition of $\ce{H+}$ and $\ce{OH-}$. Water samples would need to be titrated with a strong acid or base to determine the ability of water to buffer the addition of acids or bases.

The carbonic acid is the dominant weak acid system in most natural waters. In this system, the main weak acids are $\ce{HCO3–}$ and $\ce{H2CO3^*}$ and the main weak bases are $\ce{HCO3–}$ and $\ce{CO3^2–}$. To neutralize these acids, base ions have to be added. This is called the ***acid neutralizing capacity*** (ANC) or ***alkalinity*** of water. Based on our understanding of the $\ce{CO2}$ system in a previous section, this value is determined as follows:

```{math}
:label: anc

\ce{
ANC = [HCO3-] + 2[CO3^2-] + [OH-] - [H+]
}
```

Acid ions must be added to neutralize the bases in natural waters. This is called the ***base neutralizing capacity*** (BNC) or ***acidity*** of water. This value is determined as follows:

```{math}
:label: bnc

\ce{
BNC = 2[H2CO3^*] + [HCO3-] + [H+] - [OH-]
}
```

Alkalinity is the strong acid required to make water equivalent to an $\ce{H2CO3^*}$ solution, and acidity is the strong base required to make water equivalent to a $\ce{Na2CO3}$ solution. This means alkalinity and acidity are intimately tied to the $\ce{H2CO3^*}$ titration curve. It also means titration with a strong acid is an excellent way to measure alkalinity. Similarly, titration with a strong base is used to measure acidity.
