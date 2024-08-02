# 1.4 Chemical Reactions

## What are chemical reactions? 

Understanding how chemical reactions work is very fundamental in geology and environmental sciences.  It is particularly useful for determining how minerals and rocks form from basic elements, how chemical weathering reactions breakdown minerals and rocks, how water dissolves salts and minerals, how contaminants move in aqueous environments, how ocean acidification is impacting corals, nuclear reactions occur, and so on.  

The main principles that underlie chemical equations is the conservation of mass and transformation of chemical entities or species. These chemical equations can contain significant amount of information regarding the chemical system depicted by the chemical equations.  In all chemical equations, chemical species are separated by an arrow and indicates the phrase *to produce*} or in other contexts the direction of reaction.  This arrow can point in one direction or in both directions (e.g., $\ce{->, <-, <=>}$).  Chemical species that appeared to the left of the arrow are called reactants and species to the right side of the arrow are products.  The "+" sign indicates the word *and* whether it appears to the left or right side of the arrow.  The states of the matter are also important in the chemical equations and need to be explicitly shown to deal with ambiguous situations where it is not clear if the chemical in the equation is solid, liquid, or a gas. The common symbols used are $s$, $l$, $g$, and $aq$ for solid, liquid, gas, and aqueous (dissolved in water).

```{dropdown} Example: Dissolution of _ $\ce{CO2}$ _ in _ $\ce{H2O}$

Consider how liquid water is acidified by atmospheric $\ce{CO2 (g)}$.

$$
\begin{align*}
\ce{		
CO2 (g) &<=>[H2O]  CO2 (aq)\\
CO2 (aq) + H2O (l) &<=> H2CO3 (aq)
}
\end{align*}
$$

The first equation is a representation of the chemical reaction where gaseous $\ce{CO2}$ (or $\ce{CO2 (g)}$) dissolves in water to form aqueous $\ce{CO2}$ (or $\ce{CO2 (aq)}$). Because $\ce{CO2 (aq)}$ does not explicitly form a chemical bond with water, $\ce{H2O}$ is shown on top of the arrow to indicate it's implicit involvement in the reaction.  The $\ce{<=>}$ arrow indicates that the reaction  is reversible.  The second equation represents a chemical reaction where $\ce{CO2 (aq)}$ explicitly reacts with $\ce{H2O (l)}$ to produce $\ce{H2CO3 (aq)}$ (carbonic acid.)  

```

There are different types of chemical reactions that will be explored over the rest of the course and they include precipitation, dissolution, acid-base, redox, and nuclear reactions.


## Balancing Chemical Reactions

Consider the following chemical reaction where $\ce{H2(g)}$ reacts explosively with $\ce{O2(g)}$ to form $\ce{H2O(l)}$.

$$\ce{H2(g) + O2(g) -> H2O(l)}$$

According to this reaction, two atoms of $\ce{H}$ and two atoms of $\ce{O}$ react to form two atoms of $\ce{H}$ and one atom of $\ce{O}$.  This is a violation of the conservation of mass. 

```{admonition} The three hypotheses that make up Dalton's atomic theory

1. Matter is composed of tiny, indivisible particles called atoms; and all atoms of a given element are identical.
2. Compounds are made up of specific combinations of atoms of two or more different elements.
3. Chemical reactions cause the rearrangement of atoms, but do not cause either the creation or the destruction of atoms.
```


This equation must be balanced so that the same number of atoms appear on both sides of the reaction arrow.  We do this by writing appropriate stoichiometric coefficients (or just *coefficients*) to the left of each chemical specie until there are same number of atoms on both sides or the equation is *balanced*.  In this particular case, let's tackle $\ce{O}$ first.  Let's add a coefficient of 2 before $\ce{H2O}$ to balance $\ce{O}$. Now, there are 4 $\ce{H}$ atoms on the right.  If we add a coefficient of 2 before $\ce{H2}$, there are same number of $\ce{H}$ atoms on both sides.  The balanced reaction can be shown as:

$$
\ce{2 H2 (g) + O2 (g) -> 2 H2O (l)}
$$
Balancing a chemical reaction requires a trial-and-error approach.  Sometimes, you have to try several iterations of the coefficients of a reactant or product until conservation of mass is achieved.  Below are a couple of approaches that a commonly applied.

```{admonition} Rules for balancing chemical reactions

1. Change the coefficients of compounds (e.g., $\ce{CO2}$) before changing the coefficients of elements (e.g., $\ce{O2}$).
2. Treat polyatomic ions that appear on both sides of the equation (e.g., $\ce{CO_3^2-}$, $\ce{OH-}$, $\ce{SO_4^2-}$) as units, rather than counting their constituent atoms individually.
3. Count atoms and/or polyatomic ions carefully, and track their numbers each time you change a coefficient.
```


```{dropdown} Example: Balancing chemical reactions - Approach 1

Let's balance the equation that represents combustion of butane ($\ce{C4H10 (g)}$):

$$
\ce{C4H10(g) + O2(g) ->	CO2(g) + H2O(l)	}
$$

Let's do an inventory of all atoms on both sides of the arrow.

> | 4 	| C 	| 1 	|
> | --- | --- | --- |
> | 10 	| H 	| 2 	|
> | 2 	| O 	| 3 	|

Now, let's fix $\ce{C}$ atoms first by changing coefficient of $\ce{CO2 (g)}$.

$$
\ce{C4H10(g) + O2(g) -> 4 CO2(g) + H2O(l)	}
$$

> | 4 	| C 	| $\cancel{1}$ 4 	|
> | --- | --- | --- |
> | 10 	| H 	| 2 	|
> | 2 	| O 	| $\cancel{3}$ 9 	|

Now, let's fix $\ce{H}$ atoms by changing coefficient of $\ce{H2O (l)}$.

$$
\ce{C4H10(g) + O2(g) -> 4 CO2(g) + 5 H2O(l)	}
$$	

> | 4 	| C 	| 4 	|
> | --- | --- | --- |
> | 10 	| H 	| $\cancel{2}$ 10 	|
> | 2 	| O 	| $\cancel{9}$  13	|

Lastly, let's fix $\ce{O}$ atoms by changing coefficient of $\ce{O2 (g)}$.

$$
\ce{C4H10(g) + 13/2 O2(g) -> 4 CO2(g) + 5 H2O(l)	}
$$	

> | 4 	| C 	| 4 	|
> | --- | --- | --- |
> | 10 	| H 	| 10 	|
> | $\cancel{2}$ 13 	| O 	| 13 	|

> Multiply above equation by 2 to get whole number coefficients.

$$
\ce{2 C4H10(g) + 13 O2(g) -> 8 CO2(g) + 10 H2O(l)	}
$$

The equation is still balanced!
```

 
```{dropdown} Example: Balancing chemical reactions - Approach 2

Here's another approach to balancing chemical equations. Kaolinite ($\ce{Al2Si2O5(OH)4}$), a major component of soils, is chemically weathered (by $\ce{H+}$) into $\ce{Al^3+}$, silicic acid ($\ce{H4SiO4}$), and $\ce{H2O}$. The basic chemical reaction that represents this chemical process is shown below:

 1. Write all reactants and products in correct locations of the chemical equation:

$$
	\ce{Al2Si2O5(OH)4 + H+ -> Al^3+ + H4SiO4 + H2O}
$$

2.  Balance main elements ($\ce{Al}$ and $\ce{Si}$) first

$$
	\ce{Al2Si2O5(OH)4 + H+ -> 2 Al^3+ + 2 H4SiO4 + H2O}
$$

3. Balance $\ce{O}$ next and adjust $\ce{H2O}$

$$
	\ce{Al2Si2O5(OH)4 + H+ -> 2 Al^3+ + 2 H4SiO4 + H2O}
$$

4. Balance single elements and ions ($\ce{H+}$) last

$$
	\ce{Al2Si2O5(OH)4 + 6 H+ -> 2 Al^3+ + 2 H4SiO4 + H2O}
$$

5.  Check to see if there is mass balance for all elements.
```
