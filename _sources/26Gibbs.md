# 2.6 Gibbs Free Energy

According to the second law, $\Delta _{universe} S^\circ  > 0$, which was expressed in another form in Eq. {eq}`secondlaw`.

$$\Delta _{universe} S^\circ  = \Delta _{sys} S^\circ  - \frac{\Delta _{sys} H^\circ  }{T} >0$$
Multiply both sides of above equation by $T$,

$$T\Delta _{universe} S^\circ  = T \Delta _{sys} S^\circ  - \Delta _{sys} H^\circ   >0$$
Now reverse signs on both sides of above equation,

```{math}
:label: gibbs-deriv

-T \Delta _{universe} S^\circ  = \Delta _{sys} H^\circ -T \Delta _{sys} S^\circ    <0
```

According to Eq. {eq}`gibbs-deriv`, processes that occur at constant $P$ and $T$ are spontaneous if $\Delta _{sys} H^\circ$ and $\Delta _{sys} S^\circ$ are such that $\Delta _{sys} H^\circ   -T \Delta _{sys} S^\circ    <0$. To simplify this expression, we introduce a new thermodynamic function called Gibbs free energy ($G$) or free energy. Gibbs free energy, , is the energy available to do work.

```{math}
:label: gibbs

\Delta _{sys} G^\circ = \Delta _{sys} H^\circ -T \Delta _{sys} S^\circ 
```

Free energy is a state function and, as the name implies, has same units as and $T \Delta _{sys} S^\circ$ ($\pu{kJ}$ or $\pu{kJ mol−1}$)  If a reaction is accompanied by release of usable energy ($\Delta _{sys} G^\circ  <0$), reaction is guaranteed to be spontaneous.

```{table} $\Delta _{sys} G^\circ$ and spontaneity of reactions.
:name: g-spont
| $\Delta _{sys} G^\circ$ condition | Reaction condition |
| :---: | --- |
| $\Delta _{sys} G^\circ  <0$ | Reaction is spontaneous in forward direction  |
| $\Delta _{sys} G^\circ  =0$ | Reaction is at equilibrium |
| $\Delta _{sys} G^\circ  >0$ | Reaction is nonspontaneous as written |
```


## Standard Gibbs free energy, $\Delta _{f} G^\circ$

The standard free energy of reaction is the free-energy change for a reaction when it occurs under standard-state conditions - i.e., when reactants in their standard states are converted to products in their standard states.

````{margin}
The CRC Handbook of Physics and Chemistry is a good reference obtaining $\Delta_f G^\circ$ for most chemicals. The online version is available at [Standard Thermodynamic Properties of Chemical Substances (chemnetbase.com)](https://hbcp.chemnetbase.com/faces/documents/05_02/05_02_0001.xhtml)
````

$\Delta_{rxn}G^\circ$ is calculated as follows:

```{math}
:label: gibbs-rxn

\Delta _{rxn} G^\circ = \sum \Delta _{products} G^\circ - \sum \Delta _{reactants} G^\circ
```

$\Delta _{rxn} G^\circ$ can be calculated by looking up standard free energy of formation ($\Delta _{f} G^\circ$) from thermodynamic data tables.

```{dropdown} Example: Calculating $\Delta_{rxn}G^\circ$ 

**Example 1**

Let's calculate $\Delta_{rxn}G^\circ$ for the following reaction at
$\pu{25 ^\circ C}$:

$$ \ce{
C (s) + O2 (g) -> CO2 (g)
}$$

$\Delta_f G^\circ _\ce{C(s)} = \pu{0 kJ mol-1}$, $\Delta_f G^\circ _\ce{O2(g)} = \pu{0 kJ mol-1}$, and $\Delta_f G^\circ _\ce{CO2(g)} = \pu{-394.4 kJ mol-1}$ at $\pu{25 ^\circ C}$. 

$$\begin{aligned}
\Delta _{rxn} G^\circ  &= [\Delta _f G^\circ _\ce{CO2 (g)}] - [\Delta _f G^\circ _\ce{C (s)} + \Delta _f G_\ce{O2 (g)}]\\
&= [(\pu{-394.4 kJ mol-1})] - [(\pu{0 kJ mol-1}) + (\pu{0 kJ mol-1})]\\
&= \pu{-394.4 kJ mol-1}
\end{aligned}$$

**Example 2**

Let's calculate $\Delta_{rxn}G^\circ$ for the following reaction at $\pu{25 ^\circ C}$:

$$
\ce{
CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)
}
$$

$\Delta_f G^\circ _\ce{CH4(g)} = \pu{-50.8 kJ mol-1}$, $\Delta_f G^\circ _\ce{CO2(g)} = \pu{-394.4 kJ mol-1}$, $\Delta_f G^\circ _\ce{O2(g)} = \pu{0 kJ mol-1}$, and $\Delta_f G^\circ _\ce{H2O(l)} = \pu{-237.2 kJ mol-1}$.

$$
\begin{aligned}
\Delta _{rxn} G^\circ  &= [\Delta_f G^\circ _\ce{CO2 (g)} + 2 \cdot\Delta_f G^\circ _\ce{H2O (l)}] - [\Delta_f G^\circ _\ce{CH4 (g)} + 2\cdot \Delta_f G^\circ _\ce{O2 (g)}]\\
&= [(\pu{-394.4 kJ mol-1}) + 2(\pu{-237.2 kJ mol-1})]  - [(\pu{-50.8 kJ mol-1}) + 2(\pu{0 kJ mol-1})]\\
&= \pu{-818.0 kJ mol-1}
\end{aligned}
$$
```


## Predicting sign of $\Delta_{rxn}G^\circ$

$\Delta_{rxn}G^\circ$ is a function of $T$ as can be seen in Eq. {eq}`gibbs-rxn`. Also, $\Delta _{rxn} G^\circ  = 0$ at equilibrium (see {numref}`g-spont`). Eq. {eq}`gibbs-rxn` can be rearranged to determine exact $T$ where equilibrium is reached.

```{math}

\Delta _{rxn} G^\circ  = \Delta _{sys} H^\circ -T \Delta _{sys} S^\circ  = 0\\
```

Rearranging the above expression, we get

```{math}
:label: gibbs_t

T = \frac{\Delta _{sys} H^\circ}{\Delta _{sys} S^\circ }
```

Equations {eq}`gibbs`  and {eq}`gibbs_t` can be used to predict sign of $\Delta _{sys} G^\circ$ as shown in {numref}`gibbs-predict`.

```{table} Predicting sign of $\Delta _{sys} G^\circ$ using signs of $\Delta _{sys}S^\circ$ and $\Delta _{sys} H^\circ$.
:name: gibbs-predict

| When $\Delta _{sys} H^\circ$ is | and $\Delta _{sys}S^\circ$ is | then $\Delta _{sys} G^\circ$ will be  |  and the process is | 
| :---: | :---: | :---: | --- |
| $-$ | $+$  | $-$ | Spontaneous |
|	$+$ | $-$  | $+$ | Nonspontaneous | 
|	$-$ | $-$  | $-$ when $T{\Delta _{sys}S^\circ} < {\Delta _{sys} H^\circ}$ | Spontaneous at low $T$ | 
|	| | $+$ when $T {\Delta _{sys} S^\circ} > {\Delta _{sys} H^\circ}$ | Nonspontaneous at high $T$ |
|	$+$ | $+$  | $-$ when $T{\Delta _{sys}S^\circ} > {\Delta _{sys} H^\circ}$ | Spontaneous at high $T$ | 
|	| | $+$ when $T{\Delta _{sys}S^\circ} < {\Delta _{sys} H^\circ}$ | Nonspontaneous at low $T$ |
```

## Calculating $T$ at equilibrium

In earlier example, we saw how $\Delta _{rxn} G^\circ$ was calculated at $\pu{25 ^\circ C}$ using Eq. {eq}`gibbs-rxn` - however, $\Delta _{rxn} G^\circ$ is a function of $T$. How do we calculate ($\Delta _{rxn} G^\circ$ at other $T$? In such cases, $\Delta _{rxn} S^\circ$ and $\Delta _{rxn} H^\circ$ are determined separately and applied directly in Eq. {eq}`gibbs_t` at the specified $T$.

Using Eq. {eq}`gibbs_t`, exact $T$ where a system reaches equilibrium could be calculated. At any $T$ above or below this value the system will not longer be in equilibrium. The exact definition of equilibrium will be explored in the next chapter.

```{dropdown} Example: Calculating $\Delta _{rxn} G^\circ$ at a specified $T$ 

Let's calculate $\Delta _{rxn} G^\circ$ for decomposition of limestone to quick lime and $\ce{CO2(g)}$ as per the following reaction at $\pu{835 ^\circ C}$:

$$
\ce{CaCO3(s) -> CaO(s) + CO2(g)}
$$


Thermodynamic data for these substances at $\pu{25 ^\circ C}$ are as follows:

| Chemical | $\Delta_f H^\circ$, \, $\pu{kJ mol-1}$ | $S^\circ$, \, $\pu{J K-1 mol−1}$ |
| --- | ---: | ---: |
| $\ce{CaCO3(s)}$ | $-1206.9$ | $92.9$ |
| $\ce{CaO(s)}$ | $-635.6$ | $39.8$ |
| $\ce{CO2(g)}$ | $-393.5$ | $213.6$ |


From these data we can determine $\Delta_{rxn}H^\circ = \pu{177.8 kJ mol-1}$ and $\Delta_{rxn}S^\circ = \pu{160.5 J K-1 mol-1}$. From these data, let's calculate $\Delta _{rxn} G^\circ$ at $\pu{835 ^\circ C}$ (= $\pu{1108 K}$). 

$$
\begin{aligned}
\Delta _{rxn} G^\circ  &= \Delta_{rxn}H^\circ -T \Delta_{rxn}S^\circ\\
   &=\pu{177.8 kJ mol-1} - (\pu{1108 K})(\pu{160.5 J K-1 mol-1}) \left(\frac{\pu{1 kJ}}{\pu{e3 J}}\right)\\
   & =\pu{0  kJ mol-1}
\end{aligned}
$$
 
In this particular example, the system reached equilibrium at $\pu{835 ^\circ C}$!
```

