# 5.2 Balancing Redox Reactions

Balancing redox reactions is similar to balancing any chemical reactions.  However, the charge and mass of the elements need to be considered during that process.

For balancing redox reactions, we balance the elements on each side of the reaction and the electrons.

```{admonition} Balancing redox reactions 

Follow the steps below in sequence to balance redox reactions.
1. Identify the OS of all major elements
2. Place $\ce{e-}$  where appropriate in skeletal reaction
3. Place $\ce{e-}$  where appropriate in actual reaction
4. Adjust the stoichiometry of the main element only
5. Add $\ce{H2O}$ on appropriate side of reaction to balance $\ce{O}$ 
6. Add $\ce{H+}$ on appropriate side to balance $\ce{H}$ 
7. Verify charge balance on both sides of the reaction
8. Combine half-reactions such that all $\ce{e-}$  are consumed - factor half-reactions as required
9. Verify the stoichiometry and charge balance of the final reaction
```

```{dropdown} Example: Balancing redox reactions 

Let's balance the following redox reaction:

$$\ce{
SO4^2- + FeO -> H2S + FeOOH
}$$

>This reaction involves two redox "couples":
>
>Step 1: Identify the OS of all major elements
>
>| Chemical    | OS | Chemical | OS |
>|-------------|------: |----------|------: |
>| $\ce{SO4^2-}$ | $+6$   | $\ce{H2S}$ | $-2$   |
>| $\ce{FeOOH}$  | $+3$   | $\ce{FeO}$ | $+2$   |
>
>Step 2: Place $\ce{e-}$ where appropriate in skeletal reaction
>
>$$ \begin{align*} 
\ce{
S(VI) + 8 e- &-> S(-II)\\
Fe(III) + e- &-> Fe(II)
} \end{align*} $$
>
>Step 3: Place $\ce{e-}$ where appropriate in actual reaction
>
>$$ \begin{align*} 
\ce{
SO4^2- + 8 e- &-> H2S\\
FeOOH + e- &-> FeO
} \end{align*} $$
>
>Step 4: Adjust the stoichiometry of the main elements (in the example below, they are already balanced)
>
>$$ \begin{align*} 
\ce{
SO4^2- + 8 e- &-> H2S\\
FeOOH + e- &-> FeO
} \end{align*} $$
>
>Step 5: Add $\ce{H2O}$ to balance $\ce{O}$
>
>$$ \begin{align*} 
\ce{
SO4^2- + 8 e- &-> H2S + 4 H2O\\
FeOOH + e- &-> FeO + H2O
} \end{align*} $$
>
>Step 6: Add $\ce{H+}$ to balance $\ce{O}$
>
>$$ \begin{align*} 
\ce{
SO4^2- + 8 e- + 10 H+ &-> H2S + 4 H2O\\
FeOOH + e- + H+ &-> FeO + H2O
} \end{align*} $$
>
>Step 7: Verify charge balance on both sides of the reactions
>
>Step 8a: Combine half-reaction such that all $\ce{e-}$ are consumed.  In this case, multiply the $\ce{Fe}$ half-reaction by a factor $8$ to have the same number of $\ce{e-}$.  
>
>$$ \begin{align*} 
\ce{
SO4^2- + 8 e- + 10 H+ &-> H2S + 4 H2O\\
8FeOOH + 8e- + 8H+ &-> 8FeO + 8H2O
} \end{align*} $$
>
>Step 8b: Combine half-reaction such that all $\ce{e-}$ are consumed.  Reverse the 2nd reaction so that the $\ce{e-}$ are on the opposite sides of the reactions. Now, all $\ce{e-}$ can be cancelled.
>
>$$ \begin{align*} 
\ce{
SO4^2- + 8 e- + 10 H+ &-> H2S + 4 H2O\\
8 FeO + 8 H2O &-> 8 FeOOH + 8 e- + 8 H+
} \end{align*} $$
>
>Step 9: Add both half-reactions and check stoichiometry and charge balance on the final reaction
>
>$$ \ce{
SO4^2- + 8 FeO + 2 H+ + 4 H2O -> H2S + 8 FeOOH
}$$
>
>$\ce{FeO}$ is oxidized by $\ce{SO4^2-}$!
```


```{dropdown} Example: Balancing redox reactions -- Case Study 1 

Groundwater is an anoxic environment where dissolved iron exists as $\ce{Fe^2+}$. When this water is pumped to the surface, $\ce{O2(g)}$ in atmosphere oxidizes $\ce{Fe^2+}$, into an insoluble precipitate $\ce{Fe(OH)3 (s)}$ depending on $p\ce{H}$ conditions. 

>Let's write the half-reactions and the overall redox reaction.
>
>(1) The half-reactions
>
>$$ \begin{align} \ce{
    Fe^2+ + 3 H2O &<=> Fe(OH)3 + 3 H+ + e- \\
    O2 + 4 H+ + 4 e- &<=> 2 H2O
} \end{align} $$
>
>(2) The overall redox reaction
>
>$$\ce{
    4 Fe^2+ + O2 + 10 H2O <=> 4 Fe(OH)3 + 8 H+
}$$
```


```{dropdown} Example: Balancing redox reactions -- Case Study 2 

Ammonia (as $\ce{NH3}$) in fertilizers discharged into natural surface waters is often oxidized to $\ce{NO3-}$ by bacteria using dissolved oxygen. This process is called nitrification. 

>Let's write the half-reactions and the overall redox reaction.
>
>(1) The half-reactions
>
>$$\begin{align} \ce{
    NH4+ + 3 H2O &<=> NO3- + 10 H+ + 8 e- \\
    O2 + 4 H+ + 4 e- &<=> 2 H2O
} \end{align} $$
>
>(2) The overall redox reaction
>
>$$ \ce{
    NH4+ + 2 O2 <=> NO3- + 2 H+ + H2O
 }$$
```


```{dropdown} Example: Balancing redox reactions - Case Study 3 

$\ce{SO4^2-(aq)}$ in ocean water is often reduced to $\ce{H2S(g)}$ by abundant organic matter ($\ce{CH2O}$ in simplified form) present in saltmarsh environments. $\ce{CO2(g)}$ is a common by-product during this process. 

>Let's write the half-reactions and the overall redox reaction.
>
>(1) The half-reactions
>
>$$ \begin{align} \ce{
    SO4^2- + 10 H+ + 8 e- &<=> H2S + 4 H2O\\
    CH2O + H2O &<=> CO2 + 4 H+ + 4 e-
    } \end{align} $$
>
>(2) The overall redox reaction
>
>$$ \ce{
    SO4^2- + 2 CH2O + 2 H+ <=> H2S + 2 CO2 + 2 H2O
    } $$
```


```{dropdown} Example: Balancing redox reactions - Case Study 4 

Acid mine drainage is caused by the oxidation of pyrite ($\ce{FeS2(s)}$) when it comes in contact with water containing dissolved oxygen. The base reaction is:

$$\ce{
FeS2 + O2 -> Fe(OH)3 + SO4^2-
}$$

>In this reaction, three elements ($\ce{Fe}$, $\ce{S}$, and $\ce{O}$) participate in the overall redox reaction.
>
>(1) The half-reactions
> 
>$$ \begin{align} 
 \ce{
    Fe^2+ &-> Fe^3+ + e- \\
    2 S- + 8 H2O &-> 2 SO4^2- + 14 e- + 16 H+ \\
    O2 + 4 e- + 2 H+ &-> 2 OH-
    } \end{align} $$
>
>(2) The overall redox reaction
>
>$$ \begin{align} \ce{
    4 FeS2 + 15 O2 + 14 H2O -> 4 Fe(OH)3 + 8 SO4^2- + 16 H+
    } \end{align} $$
>
>In this case, both $\ce{Fe}$ and $\ce{S}$ are oxidized by $\ce{O2}$.
```

