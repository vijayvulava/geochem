
# Equilibrium Thermodynamics

## Introduction 

Thermodynamics is a fundamental scientific discipline that is applicable in a wide range of fields and systems, both natural and man-made. It is used to describe and predict the behavior of systems that exchange energy, work, and heat with their surroundings. The systems studied using this approach can be from a microscopic- to planetary-scales.  Some examples of natural and human systems that can be studied using a thermodynamic approach are outlined below.

In this example on the impact of climate change - scientists use principles of thermodynamics to predict how various parts of the Earth system respond to the changing climate.  

<div class="container">
<iframe src="https://www.youtube.com/embed/AVu-vplvCZE" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Economists can also explain supply chains and manufacturing processes using thermodynamic principles.

<div class="container">
<iframe src="https://www.youtube.com/embed/h6Clz8DQvIk" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Earth's interior including the mantle and the plate tectonic theory can be quantified using the principles of thermodynamics. The Earth can be studied from a classic systems perspective that makes the application of thermodynamics very helpful.

<div class="container">
<iframe src="https://www.youtube.com/embed/ECBbAjoEHWI" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

The world's scientists and governments are banking on "green" solutions as an answer to solving the climate crisis.  However, thermodynamic principles can help us better identify which types of solutions are more feasible than others. 

<div class="container">
<iframe src="https://www.youtube.com/embed/Chp9VlSs25c" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


<!---
<div class="container">
<iframe src="https://www.youtube.com/embed/Cco0T7cj-B4" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>
--->


Equilibrium thermodynamics focuses on prediction of concentrations of all species and phases present at the end of a reaction at equilibrium. Kinetics focuses on the rate at which reactions occur. In this section we focus on fundamental ideas of thermodynamics and also on their applications in the field of environmental geochemistry.

This chapter provides a basic understanding of chemical thermodynamics, which is the basis for all of chemical equilibria. We describe the basic concepts, principal functions of state, and laws of thermodynamics and show how these concepts are used to define the equilibrium conditions for chemical processes. The effects of temperature and pressure on thermodynamic functions of state and on chemical equilibria also are developed, and examples are provided throughout the chapter to illustrate applications of important thermodynamic principles and equations.


```{admonition} Learning Goals

The main goals for this chapter are to:
1. learn the basic terminology of thermodynamics - including, work, energy, systems, and state variables,
2. identify how energy is transferred between systems and their surroundings, and 
3. define and apply the laws of thermodynamics and the fundamental thermodynamic properties, including enthalpy, entropy, and Gibbs free energy.
```


## Energy and Thermochemistry

### What is work?

Mass (e.g., coffee, gasoline) contained in a closed system (e.g., a Thermos flask, gas tank in a car) is a conserved quantity, but if the system is not closed, the amount of mass that goes in or out of the system can be measured. Likewise, we often have a system that is not closed, and would like to know how much energy comes in or out. 

Energy is not a physical substance like water or coffee, so energy transfer cannot be measured with a meter or an instrument. So, how can we tell how much useful energy can a car "put out" on one tank of gas?

The ***law of conservation of energy*** guarantees that all the chemical energy in the gasoline will reappear in some form, but not necessarily in a form that is useful for doing farm work. Tractors, like cars, are extremely inefficient, and typically $\pu{90 \%}$ of the energy they consume is converted directly into heat, which is carried away by the exhaust and the air flowing over the radiator. We wish to distinguish the energy that comes out directly as heat from the energy that serves to accelerate a trailer or to plow a field, so we define a technical meaning of the ordinary word "work" to express the distinction:

```{math}
:label: work

\text{Work} = \text{force} \times \text{distance}
```


### What is energy?

Energy is the capacity to do work. It can be in many forms: thermal energy (associated with random motion of atoms and molecules), chemical energy (associated with bonds in chemical substances), potential energy (associated with position of an object), kinetic energy (associated with motion), etc. Each of these forms of energy can be converted to another form (e.g., dropping an object converts potential energy to kinetic energy), but cannot be created or destroyed. This principle is called ***law of conservation of energy***. SI unit of energy is joule or $\pu{J}$.

```{dropdown} Example: Kinetic Energy
The amount of kinetic energy possessed by $\pu{2 kg}$ mass moving at a speed of $\pu{1 m s−1}$, calculated as:

>$$
E_k = \frac{1}{2}m\nu^2 = \frac{1}{2}(\pu{ 2 kg})(\pu{1 m s-2})  = \pu{ 1 J}
$$
```

Matter can undergo physical and chemical changes. For example, freezing of water does not involve breaking down of water molecules and only involves changing the state of matter, i.e., physical change. This can be represented as follows: $\ce{H2O(l)  -> H2O(g)} $

Chemical change involves making or breaking chemical bonds. Formation of water from constituent elements is an example of chemical change: $\ce{2 H2(g) + O2(g) -> 2 H2O(l)} $. In each case there was a specific type of energy involved in the change. This energy must be released or supplied for changes (reactions) to occur.


<div class="container">
<iframe src="https://www.youtube.com/embed/2S6e11NBwiw" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


Energy changes associated with physical processes and chemical reactions must be discussed in the context of a ***system*** and its ***surroundings***. A system is a specific part of the universe that interests us and the surroundings are rest of the universe. Practically speaking, surroundings are immediately close to the system. In the above examples, ice or water is a system and all other parts beyond this system (container, etc) are the surroundings.

*Heat* and *thermal energy* are not to be used interchangeably. Heat is the transfer of thermal energy between two bodies that are at different temperatures. Matter does not contain heat - it contains thermal energy. ***Thermochemistry*** is the study of heat (transfer of thermal energy) associated with chemical reactions.

The above chemical reaction (formation of water) results in release of energy and can be written as follows: 

$$
\ce{2 H2(g) + O2(g) -> 2 H2O(l) + \text{Energy}}
$$

In this case, the system contains a mixture of all reactants and products. Because, energy cannot be created or destroyed, the energy is transferred between the system and the surroundings. In the above chemical reaction, energy is created in the system and is transferred to its surroundings. This is an example of an ***exothermic reaction***.

Consider the decomposition of mercury(II) oxide ($\ce{HgO}$) at high temperatures: 

$$
\ce{\text{Energy} + 2 HgO(s) -> 2 Hg(l) + O2 (g)}
$$

For this reaction to occur, energy has to be supplied to the system from the surroundings. This is an example of an ***endothermic reaction***. 

<div class="container">
<iframe src="https://player.vimeo.com/video/73325384?h=6aab1f5431" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


The above video shows how energy is consumed or produced during forming or breaking chemical bonds.  In an exothermic reaction, the energy of the products in a reaction is lower than the energy of the reactants causing the excess energy to be released from the system to the surroundings. In an endothermic reaction, the energy of the products is higher than that of the reactants.

```{figure} https://www.fda.gov/files/nutrition-facts-label-download-image2.jpg
---
width: 200px
name: fda-label
figclass: margin
---
An example of a US Food and Drug Administration (FDA)'s nutritional facts label. Note that the Calories amount on this label are actually kilocalories. Image source: [Food Labeling & Nutrition | FDA](https://www.fda.gov/food/food-labeling-nutrition)
```

SI unit for energy is joule ($\pu{J}$), another common unit of energy is calorie ($\pu{cal}$). A calorie is the amount of energy required to raise the temperature of $\pu{1 g}$ of water by $\pu{1 ^\circ C}$. $\pu{1 cal} = \pu{4.184 J}$. Calories listed on nutrition labels (see figure ) are not "calories" but "kilocalories." To make the distinction, the first letter in Calories is capitalized. 

$$\pu{1 Cal} = \pu{1000 cal} = \pu{1 kcal} = \pu{4184 J}$$

```{figure} https://esha.com/wp-content/uploads/2015/02/eu_label_1-01.jpg
---
width: 200px
name: eu-label
figclass: margin
---
An example of an European Union's nutritional facts label. Image source: [EU Nutrition Facts Templates - Ingredients List Label | ESHA Research](https://esha.com/products/genesis-rd-food-labeling-software/labels-and-labeling/european-union-nutrition-facts-label/)
```


## Introduction to Thermodynamics

Thermodynamics is a scientific study that deals with different relative energy levels and transfers of energy between systems and between different states of matter. Chemical thermodynamics specifically deals with energy transfers as related to chemical reactions and is primarily of our interest in geochemistry. We will also focus on the concept of equilibrium and its theoretical underpinnings in thermodynamics. The laws of thermodynamics provide useful guidelines for understanding the exchange of energy between systems and also direction of chemical processes.

### Thermodynamic Systems

It is very important to clearly define the ***system*** in equilibrium thermodynamics. This system can be in the scale of the entire universe (for an astronomer), an aquifer (for a hydrogeologist), or a petri dish (for a microbiologist) The choice depends on the kind of problem of interest. For example, in a shore environment there are different processes occurring and defining the bounds of the system become very important. See {numref}`earth-systems` for an example of how various processes on Earth can be studied using a systems approach.

```{figure} https://mynasadata.larc.nasa.gov/sites/default/files/2019-04/earth_system_diagram_print.jpg
---
width: 400px
name: earth-systems
figclass: margin-caption
---
Systems can be considered at many scales. In this picture we can see how energy and matter (elements, water, etc) is cycled across the entire Earth system at many scales.  Image source: [Earth System: Matter and Energy Cycles | MyNASAData](https://mynasadata.larc.nasa.gov/basic-page/earth-system-matter-and-energy-cycles)
```

A system is any portion of the universe that can be isolated from the rest of the universe for the purpose of observing and measuring changes. By saying that a system is any portion of the universe, we mean that the system can be whatever the observer defines it to be. In {numref}`earth-systems` we can see different parts of Earth can be subdivided into subsystems and studied separately for convenience.  A system is conceptual be design and needs to be defined more clearly by the observer.  It can be large or small, simple or complex. It can be in form of a  laboratory experiment in a beaker, or a lake, a small sample of rock, an ocean, a volcano, a mountain range, a continent, or an entire planet. A leaf is a system; it is part of a larger system (a tree), which in turn is part of an even larger system (a forest) and so on. 

The fact that a system is isolated from the rest of the universe means that it must have a boundary that sets it apart from its surroundings. The nature of the boundary is one of the most important defining features of a system, allowing us to establish three basic kinds of systems—open, closed, and isolated—with different types of boundaries.

```{admonition} Types of systems

There are three types of systems: 
1. Open systems - can exchange mass and energy with surroundings
2. Closed systems - can exchange energy with surroundings
3. Isolated systems - no exchange of mass or energy with surroundings

In {numref}`earth-systems` the Earth system is an open system internally with free exchange of mass and energy.  Since there is negligible exchange of mass with Earth and it's surroundings in the solar system, it is a closed system for mass. However, Earth gains and loses energy from within the solar system and is an open system for energy.
```

Since matter and energy is shared between systems and surroundings, it would be useful to quantify the flow of mass and energy.  The amount of matter (or energy) that is transferred across the boundary of a system, and the rate at which it is transferred, is called a ***flux***. It is quantified in units of *mass or volume per time*.

The storage and movement of material and energy in a group of interacting systems is often represented as a ***box model***. A box model can be used to show the following essential features of a system: 
1. The processes by which matter (or energy) enters and leaves the system, and the rates at which they do so.
2. The processes by which matter (or energy) moves among the various parts of the system internally, and the rates at which this happens.
3. The amount of matter (or energy) in the system at a given time and its distribution within the system.

As shown in {numref}`hydro-box-model`, the “boxes” in a box model represent the places where water (or energy, or whatever might be the material of interest) is stored for a period of time within the system. These storage places are called ***reservoirs***.  When the flux of matter into a reservoir matches the flux out of that reservoir, we say that the reservoir is at ***steady state***. The average length of time water spends in any of these reservoirs is called its ***residence time***. The residence time of any material in any particular reservoir is deter- mined by the interaction of many factors, including the physical, chemical, and biologic properties of the material itself, the properties of the reservoir, and any external forces or processes acting on either the material or the reservoir.


```{figure} assets/water-cycle-science.jpeg
---
width: 500px
name: hydro-box-model
figclass: margin-caption
---
The global hydrological cycle is shown as a box model in this figure. Fluxes ($\pu{e3 km3 yr-1}$) and reservoirs ($\pu{e3 km3}$) with natural and anthropogenic cycles are included. Big vertical arrows show total annual precipitation and evapotranspiration over land and ocean ($\pu{e3 km3 yr-1}$), which include annual precipitation and evapotranspiration in major landscapes ($\pu{e3 km3 yr-1}$) presented by small vertical arrows; parentheses indicate area ($\pu{e6 km2}$). The direct groundwater discharge, which is estimated to be about $\pu{10 \%}$ of total river discharge globally, is included in river discharge.  Image source: [Global Hydrological Cycles and World Water Resources | Science](https://www.science.org/doi/10.1126/science.1128845)
```

Under steady state conditions, the residence time can be calculated as shown in eq {eq}`residence-time`.

```{math}
:label: residence-time
\text{Residence time} = \dfrac{\text{Reservoir Amount}}{\text{Rate of addition/removal}}
```


### States and State Variables

In thermodynamics, it is important to explicitly define the properties (e.g., composition, energy, temperature, pressure, and volume) of a system -- these properties help us understand changes in the ***state of system*** during a chemical process. When state of the system changes, these properties change. ***State variables*** (or ***state functions***) are properties that are determined by the state of the system, regardless of how they were achieved. That is, when the state of the system changes, the magnitude of the change is only dependent on the initial and final states of the system and not on how the change is accomplished. Energy, pressure, temperature, and volume are examples of state variables. Several important state variables are not measurable in the absolute sense in a particular equilibrium state, though they do have fixed, finite values in these states. However, the changes between the equilibrium states can be measured. Changes in system variables can be denoted as shown below. The $\Delta$ is a standard mathematical symbol for change and refers to the *final* minus *initial* values as shown below.

$$
	\begin{eqnarray*}
		\Delta E &=& E_{final}-E_{initial}\\
		\Delta P &=& P_{final}-P_{initial}\\
		\Delta V &=& V_{final}-V_{initial}\\
		\Delta T &=& T_{final}-T_{initial}
	\end{eqnarray*}
$$

Thermodynamic properties can be extensive properties or intensive properties. ***Extensive properties*** are dependent on the amount of the material in the system (e.g., mass, volume.) ***Intensive properties*** are independent on the amount of material. They are the same for any subset of the material in the system (e.g., concentration, temperature, pressure). {numref}`state-properties` lists a summary of the most commonly-used state variables.

```{table} Commonly-used state extensive and intensive properties and their standard SI units. Note: Molar properties are normalized by moles of material while specific properties are normalized by mass.
:name: state-properties

|  **Type** |     **Extensive Property** |       **Intensive Property** |
| --------- | ----------- | ------------------ |
| Mass    |  mass ($\pu{ g}$ or $\pu{ mol}$)        |   concentration ($\pu{ g L-1}$ or $\pu{ mol L-1}$) |
|            |                        |    density ($\pu{ kg L-1}$) |
| Volume   | volume ($\pu{ L}$)               | specific volume ($\pu{ L kg-1}$) |
|           |  |                        molar volume ($\pu{ L mol-1}$) |
| Thermal   | heat capacity ($\pu{ J K-1}$)  | specific heat ($\pu{ J K g-1}$) |
|          | energy ($\pu{ kJ}$)              | molar energy ($\pu{ kJ mol-1}$) |
|          | enthalpy ($\pu{ kJ}$)             | molar enthalpy ($\pu{ kJ mol-1}$) |
|          | entropy ($\pu{ J K-1}$)     |    molar entropy ($\pu{ J K mol-1}$) |
|          | free energy ($\pu{ kJ}$)       |   molar free energy ($\pu{ kJ mol-1}$) |
| Other     | |                          pressure ($\pu{ atm}$) |
|            | |                         temperature ($\pu{ K}$) |
```

Some thermodynamic properties are additive even after systems are transformed or when two systems are combined. These properties are *conserved*. Intensive properties are not conserved as they are not additive even within the same system. Only extensive properties are conserved.

```{dropdown} Example: Conservation of Mass
Conservation of mass Let's determine concentration in a solution ($S$) formed when one spoon ($\pu{5 mL}$) of seawater ($sw$) from Folly Beach ($=\pu{10.8 g L^{-1}}$) at $\pu{25 ^\circ C}$ is added to $\pu{1.0 L}$ of freshwater ($fw$) from Goose Creek reservoir ($=\pu{6 mg L^{-1}}$). Since, concentration is an intensive property and is not additive, it needs to be transformed to an extensive property. The extensive property equivalent of concentration is mass ($m = C\times V$, where $m$ is mass, $C$ is concentration and $V$ is volume). 

$$
\begin{aligned}
        m_s &= m_{sw} + m_{fw} = C_{sw}V_{sw} + C_{fw}V_{fw}\\
         &= (\pu{5e-5 L})(\pu{10.8 g L-1}) + (\pu{1 L})(\pu{6e-3 g L-1})\\
        &= \pu{6.54e-3 g}\\
        V_s &= V_{sw} + V_{fw} \\
        &= \pu{5e-5 L} + \pu{1 L}\\ 
        &= \pu{1.00005 L}\\
        &\text{Now, convert the mass back to concentration}\\
        C_s &= \frac{m_s}{V_s}\\ 
        &= \frac{\pu{6.54e-3 g}}{\pu{1.00005 L}} = \pu{6.5 mg L-1}
    \end{aligned}
$$
```


### Phases and Components

Thermodynamic properties are used to define the state of the system. But we need to know how many of these properties are required to actually define a system? You can intuitively guess that this would depend on the complexity of the system. The number of properties required is determined by the number of phases and components present in the system.

A ***phase*** is defined as a homogeneous body of matter that has distinct boundaries with adjacent phases, and hence can be mechanically separable. Shape, orientation, and position of a phase in relation to adjacent phases is irrelevant, so a single phase may occur in several locations within a system. Examples of single phases include, quartz in granite and a salt solution. There are three common phases -- solid, liquid, gas or vapor. A system having only a single phase is *homogeneous* and a system with multiple phases is *heterogeneous*.

***Components*** are used to describe the chemical composition of a system. They are defined as the smallest set of chemical formula required to completely describe the composition of all the phases that make up a system. For example, in a $\ce{NaCl}$ solution (doesn't matter if there is water vapor or calcite precipitate in the solution), the combination of $\ce{NaCl}$ and describes the composition of all phases.

So, how many thermodynamic properties does one need in a system that $P$ phases and $C$ components? According to the ***Gibbs Phase Rule***, $C-P+2$ properties are needed.

Why do we need to know thermodynamic properties? This will become clear as we start discussing the laws of thermodynamics.

Unlike what you have learned about the definition of a law according to the scientific method, the thermodynamics laws are concepts held to be true without derivation or proof. The basis of thermodynamics is built on three conservation statements: in any process, mass, energy, and momentum are conserved.

Originally, there were only three laws of thermodynamics that were formulated.  However, when the fourth law was formulated, it was decided that this fourth law was even more fundamental than the original three laws. Instead of renumbering the original three laws, the fourth law was named the "Zeroth" law.

## Zeroth Law of Thermodynamics

The zeroth law states that if two thermodynamic systems are in thermal equilibrium with each other, and also separately in thermal equilibrium with a third system, then the three systems are in thermal equilibrium with each other. 

Two systems are said to be in thermal equilibrium if they are linked by a wall permeable only to heat, and they do not change over time. This property is applied in a basic thermometer.  When a thermometer is placed in a room or on a body, the temperature reading on the thermometer changes until thermal equilibrium is established between the thermometer and the surrounding system.

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/5/57/Mercury_Thermometer.jpg/220px-Mercury_Thermometer.jpg
---
name: thermometer
figclass: margin
---
Mercury thermometer (mercury-in-glass thermometer) for measurement of room temperature. Image source: [Thermometer - Wikipedia](https://en.wikipedia.org/wiki/Thermometer)
```

## First Law of Thermodynamics

The first law states that ***energy is conserved***, in other words, energy can be converted from one form to another and can neither be created nor destroyed. Any change in the heat of the system or work done by the system must be accounted for in the internal energy of the system. 

```{math}
:label: FirstLaw

\Delta_{sys}E^\circ = q + w
```

In Eq {eq}`FirstLaw`, $\Delta_{sys}E^\circ$ is the differential change in the internal energy of the system, $q$ is the heat added or removed from the system, and $w$ is the work done on or by the system. By convention, $q$ is positive for an endothermic process and negative for an exothermic process, and $w$ is positive for work done on the system by the surroundings and negative for work done by the system on the surroundings.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/68b9d7102438342c6cf948437ecbe44f09267984
---
width: 400px
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


### Enthalpy

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
The CRC Handbook of Physics and Chemistry is a good reference obtaining $\Delta_f H^\circ$ for most chemicals. The online version is available at [Handbook of Chemistry and Physics 103rd Edition (openathens.net)](https://hbcp-chemnetbase-com.eu1.proxy.openathens.net/faces/contents/ContentsSearch.xhtml) 
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

### Hess's Law

Because $\Delta_{rxn}H^\circ$ is a state function, the change in enthalpy that occurs when reactants are converted to products in a reaction is the same whether the reaction takes place in one step or in a series of steps. This observation is called ***Hess's law***. This is an application of the concept that in thermodynamics, the system *does not care* how many steps (individual reactions) were required to reach equilibrium -- just the final reaction.

Another practical concern is that many compounds cannot be synthesized from their elements directly. In some cases, the reaction proceeds too slowly, or side reactions produce substances other than the desired compound. In these cases, $\Delta_f H^\circ$ can be determined by an indirect approach, using Hess's law.

```{dropdown} Example: Hess's law 

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
```

```{dropdown} Example: Hess's law 

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


## Second Law of Thermodynamics

The first law of thermodynamics addresses energy exchange between a system and it's surroundings. But, it does not address *if* a reaction or process will occur under a given set of conditions ($P$, $T$, concentration, etc) That is, it does not address if the chemical process is *spontaneous*. The second law introduces a state function called entropy ($S$) to address spontaneity.

### Spontaneous processes

Spontaneous processes are defined as processes that does occur under a specific set of conditions. Unlike in common parlance, spontaneous processes do not indicate "fast" or suddenly occurring reactions. Reaction rates are not addressed in thermodynamics, where all state functions are compared is systems assumed to already be at equilibrium under given set of conditions.

```{dropdown} Example: Spontaneous processes

1. Water flows downhill
2. Lump of sugar dissolves in hot coffee
3. At $\pu{1 atm}$, $\ce{H2O(l)}$ freezes below $\pu{0 ^\circ C}$
4. $\ce{Fe}$ exposed to $\ce{O2}$ and $\ce{H2O}$ at $\pu{1 atm}$ forms $\ce{Fe2O3}$ (rust)

```

Processes that result in a decrease in the energy of a system often are spontaneous -- i.e., these processes reach a most stable lower energy level. In such reactions, heat is given off to the surroundings (exothermic processes) However, endothermic processes can also be spontaneous.

```{dropdown} Example: Spontaneous chemical processes 

All reactions shown below occur spontaneously at $\pu{25 ^\circ C}$. It is also evident that first two reactions are exothermic, while the last two reactions are endothermic.

| Reaction | $\Delta_{rxn}H^\circ$,  $\pu{kJ mol-1}$ |
| --- | ---: |
| $\ce{CH4(g) + 2 O2(g) -> CO2(g) + 2 H2O(l)}$  | $-890.4$ |
| $\ce{H+ (aq) + OH- (aq) <=> H2O(l) }$ | $-56.2$ |
| $\ce{H2O(s) -> H2O(l)}$ | $6.01$ |
| $\ce{NH4NO3(s) ->[H2O] NH4+ (aq) + NO3- (aq)}$ | $25.0$ |
```

Because $\Delta_{rxn}H^\circ$ is not adequate to predict spontaneity of the process, we have to define new terms such as entropy and Gibbs free energy.

### Entropy

Imagine two well-insulated bottles somewhere in the universe ({numref}`spontaneous`) and that within one side of bottle was filled with a gas and the other side of the bottle contains vacuum, separated by a valve. If this valve were to be removed, you would intuitively know that gas will enter the side under vacuum spontaneously. We have neither added energy to nor taken energy from the system, hence the first law says nothing about this process. Nor did opening the valve *cause* the reaction. This is apparent from the observation that if we reclose the valve, the gas will not return to the original side. This phenomenon suggests there is something very fundamental and universal about this. This process is addressed in the second law of thermodynamics.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/9eafa2a59a63c98a307979ec929c1e6ae7d47898
---
width: 300px
name: spontaneous
figclass: margin-caption
---
An isolated system consists of an ideal gas in one flask that is connected by a valve to a second flask containing a vacuum. Once the valve is opened, the gas spontaneously becomes evenly distributed between the flasks. Image source: [12.1 Spontaneity - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/12-1-spontaneity)
```

Entropy ($S$) of a system is a measure of how spread out or how dispersed the system's energy is. The simplest interpretation of this is how spread out a system's energy is in space. Because the gas molecules that were originally confined to one side of the container are moving, they possess motional energy. When the barrier is removed, the motional energy of molecules will cause the as molecules to spread out and occupy a larger volume. This dispersal of system's motional energy causes an increase in the system's entropy. Just as spontaneity is favored by a process being exothermic, spontaneity is also favored by an increase in the system's entropy. Whether it is the enthalpy change, the entropy change, or both, for a process to be spontaneous, something must favor spontaneity.

[What is entropy? - Jeff Phillips | TED-Ed](https://ed.ted.com/lessons/what-is-entropy-jeff-phillips)

<div class="container">
<iframe src="https://www.youtube.com/embed/YM-uykVfq_E" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

Entropy is an extensive property (see {numref}`state-properties`) and has the units $\pu{J K−1}$. Molar entropy is entropy normalized to amount (moles) of a substance ($\pu{J K-1 mol−1}$) and is, therefore, an intensive property. Mathematically, $S$ is described as the heat absorbed ($q$) in a reversible reaction that occurred in a closed system divided by absolute temperature ($T$, an intensive property). 

```{math}
:label: entropy

\delta S = \frac{\delta q}{T}
```

 Note that $\delta$ indicates *a small change*. As seen in the above example, most reactions that occur in nature are irreversible the above equation is rewritten as
 
```{math}
:label: entropy-t

\delta S > \frac{\delta q}{T}
```

### Standard entropy, $S^\circ$ 

It is the absolute entropy of a substance at $\pu{1 atm}$ (they are function of temperature, but standard values are expressed at $\pu{25 ^\circ C}$. The units of entropy are $\pu{J K-1 mol−1}$. The $S^\circ$ of substances (elements and compounds) are always positive (i.e., $S^\circ > 0$), even for elements in their standard states.

````{margin}
The CRC Handbook of Physics and Chemistry is a good reference obtaining $S^\circ$ for most chemicals. The online version is available at [Handbook of Chemistry and Physics 103rd Edition (openathens.net)](https://hbcp-chemnetbase-com.eu1.proxy.openathens.net/faces/contents/ContentsSearch.xhtml) 
````

```{table} Entropy ($S^\circ$) of selected substances. Observe the trends in the table.
:name: entropy-substances

| Substance | $S,\ \pu{J K-1 mol−1}$ | Substance | $S,\ \pu{J K-1 mol−1}$ | 
| --- | ---: | --- | ---: |
| $\ce{H2O(l)}$ | $69.9$ | $\ce{C}$ (diamond) | $2.4$ |
| $\ce{H2O(g)}$ | $188.7$ | $\ce{C}$ (graphite) | $5.69$ |
| $\ce{Na(s)}$ | $51.05$ | $\ce{O2(g)}$ | $205.0$ |
| $\ce{Na(l)}$ | $57.56$ | $\ce{O3(g)}$ | $237.6$ |
| $\ce{Na(g)}$ | $153.7$ | $\ce{F2(g)}$ | $203.34$ |
| $\ce{He(g)}$ | $126.1$ | $\ce{Au(s)}$ | $47.7$ |
| $\ce{Ne(g)}$ | $146.2$ | $\ce{Hg(l)}$ | $77.4$ |
```

```{admonition} General trends in entropy ($S^\circ$) of various chemical substances

The table of data shown above highlight the following trends:
1. For a given substance, is increases in the following order: $S_\text{gas} \gg S_\text{liquid}> S_\text{solid}$. This can be explained by greater molecular motion in gases compared with liquids, and in liquids compared with solids (see {numref}`entropy-substance-fig`).
2. For two monatomic species, the one with the larger molar mass has the greater $S^\circ$. E.g., compare $\ce{He}$ vs. $\ce{Ne}$.
3. For two substances in the same phase, and with similar molar masses, the substance with the more complex molecular structure has the greater $S^\circ$. The more complex a molecular structure, the more different types of motion the molecule can exhibit. E.g., $\ce{O2(g)}$ vs. $\ce{O3(g)}$.
4. When an element exists in two or more allotropic forms (e.g., graphite vs. diamond), the form in which the atoms are more mobile has the greater entropy. In diamond, the carbon atoms occupy fixed positions in a three-dimensional array. In graphite, although the carbon atoms occupy fixed positions within the two-dimensional sheets, the sheets are free to move with respect to one another, which increases the mobility and, therefore, total number of possible arrangements of atoms within the solid.
```

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/f3f96b7f897d7cd062c326b3e451634f6c3d5a20
---
name: entropy-substance-fig
figclass: margin-caption
---
The entropy of a substance increases ($S^\circ > 0$) as it transforms from a relatively ordered solid, to a less-ordered liquid, and then to a still less-ordered gas. The entropy decreases ($S^\circ < 0$) as the substance transforms from a gas to a liquid and then to a solid. Image source: [12.2 Entropy - Chemistry: Atoms First | OpenStax](https://openstax.org/books/chemistry-atoms-first/pages/12-2-entropy)
```

Entropy of a system ($\Delta _{sys} S^\circ$) can be calculated similar to mathematical procedure for calculating $\Delta _{sys} H^\circ$.

```{math}
:label: s_sys

\Delta _{sys} S^\circ  = \sum \Delta_{prod}S - \sum \Delta_{reac}S
```


```{dropdown} Example: Calculating $\Delta _{sys} S^\circ$ of a system 

Let's calculate $\Delta _{sys} S^\circ$ of the following reaction at $\pu{25 ^\circ C}$

$$
\ce{CaCO3(s) -> CaO(s) + CO2(g)}
$$

$S^\circ$ of these substances can be looked up the CRC Thermodynamic Data Tables: $S_{\ce{CaCO3 (s)}} = \pu{92.9 J K-1 mol-1}$, $S_{\ce{CaO (s)}} = \pu{39.8 J K-1 mol-1}$, and $S_{\ce{CO2 (g)}} = \pu{213.6 J K-1 mol-1}$. 

$$
\begin{align*}
\Delta _{sys} S^\circ  &= [S_{\ce{CaO (s)}} + S_{\ce{CO2 (g)}}] - [S_{\ce{CaCO3 (s)}}]\\
&= [\pu{39.8 J K-1 mol-1} + \pu{213.6 J K-1 mol-1}] - [\pu{92.9 J K-1 mol-1}]\\
&= \pu{160.5 J K-1 mol-1}
\end{align*}
$$
```


### Qualitative prediction of $\Delta _{sys}S^\circ$

Equation {eq}`s_sys` helps us calculate $\Delta _{sys}S^\circ$ for any process where $S^\circ$ of all reactants and products are known. But, we can qualitatively predict the sign of $\Delta _{sys}S^\circ$ by evaluating the chemical process.

```{admonition} Processes that lead to increase in $S^\circ$ of a system

1. Melting - when solids melt, molecules have greater energy and are more mobile. They go from being in fixed positions in the solid, to being free to move about in the liquid.
2. Vaporization or sublimation - a dramatic increase in energy/mobility, and in the number of possible arrangements of a system's molecules when the molecules go from a condensed phase to the gas phase.
3. Temperature increase - the energy of the system's molecules increases due to increase in their average kinetic energy.
4. Reaction resulting in a greater number of gas molecules -- since entropy of a substance in the gas phase is always significantly greater than its entropy in either the liquid or solid phase, a reaction that results in an increase in the number of gas molecules causes an increase in the system's entropy.
5. Dissolving a substance - dissolving causes dispersal of the molecules (and consequently, of the system's energy) into a larger volume and greater entropy. This rule breaks down for multiple-charged ions in water as these ions attract water molecules (hydration) around their surfaces resulting in lower entropy.
```

```{dropdown} Example: Predicting the sign of $\Delta _{sys}S^\circ$ a system 

Let's predict sign of $\Delta _{sys}S^\circ$ for the following systems using the rules outlined above:

1. Decomposition of $\ce{CaCO3(s)}$ to $\ce{CaO(s)}$ and $\ce{CO2(g)}$: $+$ or $\Delta _{sys}S^\circ >0$
2. Heating bromine vapor from $\pu{45 ^\circ C}$ to $\pu{80 ^\circ C}$: $+$ or $\Delta _{sys}S^\circ >0$
3. Condensation of water vapor on a cold surface: $-$ or $\Delta _{sys}S^\circ <0$
4. Reaction of $\ce{NH3(g)}$ and $\ce{HCl(g)}$ to give $\ce{NH4Cl(s)}$: $-$ or $\Delta _{sys}S^\circ <0$
5. Dissolution of sugar in water: $+$ or $\Delta _{sys}S^\circ >0$
```


### $S^\circ$ changes in the universe

Every system we study is part of the universe. We call the environment that exists outside the system as the surroundings. Together, the system and its surroundings make up the universe. The transfer of energy from the system to its surroundings was addressed in the first law. Based on our understanding of entropy, we can also describe entropy changes in the surroundings. To correctly predict if a system is spontaneous, we need to address entropy change in the surroundings as well.

Consider melting of an ice cube at room temperature (endothermic process). Because we can expect ice cube to melt spontaneously, we would expect $\Delta _{sys} S^\circ  >0$ (melting of a solid). Consequent to this melting of ice, the air in the room becomes cooler causing a decrease in entropy of the surrounding ($\Delta _{surr}S^\circ <0$). Now consider the opposite process of a cup of boiling water placed at room temperature (exothermic process). Because the water in the cup is cooling, $\Delta _{sys} S^\circ  >0$ and since the surroundings are warmer than before, $\Delta _{surr}S^\circ >0$.

Now, let's examine combustion of graphite ($\ce{C}$) in the same room as above. This process would result in formation of $\ce{CO2(g)}$ and heat (exothermic process). Though this reaction is producing a gas ($\Delta _{sys} S^\circ  >0$), it is an exothermic reaction resulting in $\Delta _{surr}S^\circ >0$.

Therefore, in exothermic processes, heat transferred from the system to the surroundings increases the temperature of the molecules in the surroundings causing entropy of the surroundings to increase. Conversely, in endothermic processes, heat is transferred from the surroundings to the system, decreasing the entropy of the surroundings. There is a clear correlation between $\Delta _{sys} H^\circ$, $\Delta _{surr}S^\circ$, and $T$ in the system (see Eq. {eq}`entropy`): 

```{math}
:label: s-t

\begin{aligned}
   \Delta _{surr}S^\circ &\propto \Delta _{sys} H^\circ  \\
    \Delta _{surr}S^\circ &\propto \frac{1}{T}
\end{aligned}
```


The negative sign refers to an exothermic process. In endothermic processes, the signs would be reversed. Combining, above two expressions, we have

```{math}
:label: s_surr

\Delta _{surr}S^\circ = - \frac{\Delta _{sys} H^\circ}{T}
```


### Second Law - Definition

It was clear from the above discussion that both systems and surroundings can undergo changes in entropy during a chemical or physical process. These changes can be summarized as:

```{math}
:label: secondlaw

\Delta _{universe} S^\circ  = \Delta _{sys} S^\circ  + \Delta _{surr}S^\circ
```

Second law of thermodynamics defines that *increases in a spontaneous process and remains unchanged at equilibrium.* This law is summarized in {numref}`s-univ` 

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

Using thermodynamic data, we can determine that $\Delta _{sys} H^\circ = \pu{-96.2 kJ mol-1}$ and $\Delta _{sys} S^\circ = \pu{-199 J mol-1 K-1}$. Let's see if synthesis of $\ce{NH3(g)}$ is spontaneous. Substitute given data into Eq. {eq}`secondlaw-sys` and adjust units for consistency.

$$
\begin{aligned}
\Delta _{universe} S^\circ  &= \pu{-199 J K-1 mol-1} - \frac{\pu{-96.2 J K-1 mol-1} \times \pu{1000 J K-1 mol-1}}{\pu{298 K}}\\
&= \pu{-199 J K-1 mol-1} + \pu{323 J K-1 mol-1}\\
&= \pu{124 J K-1 mol-1}
\end{aligned}$$ 

Since $\Delta _{universe} S^\circ >0$, this process is spontaneous.
```


## Third Law of Thermodynamics

This law is an application of the second law. It states that *the entropy of a perfect crystalline substance is zero at absolute zero* ($\pu{0 K}$). As $T$ increases, molecular motion increases causing an increase in entropy ({numref}`entropy-substance-fig`).

As can be observed from {numref}`entropy-substance-fig`, all entropy values of substances are absolute entropies at a given $T$ compared with their corresponding values ($=0$) at absolute zero. Absolute entropies are referred to as standard entropies ($S^\circ$) at $1$.


## Gibbs Free Energy

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


### Standard Gibbs free energy, $\Delta _{f} G^\circ$

The standard free energy of reaction is the free-energy change for a reaction when it occurs under standard-state conditions - i.e., when reactants in their standard states are converted to products in their standard states.

````{margin}
The CRC Handbook of Physics and Chemistry is a good reference obtaining $\Delta_f G^\circ$ for most chemicals. The online version is available at [Handbook of Chemistry and Physics 103rd Edition (openathens.net)](https://hbcp-chemnetbase-com.eu1.proxy.openathens.net/faces/contents/ContentsSearch.xhtml) 
````

$\Delta_{rxn}G^\circ$ is calculated as follows:

```{math}
:label: gibbs-rxn

\Delta _{rxn} G^\circ = \sum \Delta _{products} G^\circ - \sum \Delta _{reactants} G^\circ
```

$\Delta _{rxn} G^\circ$ can be calculated by looking up standard free energy of formation ($\Delta _{f} G^\circ$) from thermodynamic data tables.

```{dropdown} Example: Calculating $\Delta_{rxn}G^\circ$ 

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
```

```{dropdown} Example:  Calculating $\Delta_{rxn}G^\circ$ 

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


#### Predicting sign of $\Delta_{rxn}G^\circ$

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

#### Calculating $T$ at equilibrium

In earlier example, we saw how $\Delta _{rxn} G^\circ$ was calculated at $\pu{25 ^\circ C}$ using Eq. {eq}`gibbs-rxn` - however, $\Delta _{rxn} G^\circ$ is a function of $T$. How do we calculate ($\Delta _{rxn} G^\circ$ at other $T$? In such cases, $\Delta _{rxn} S^\circ$ and $\Delta _{rxn} H^\circ$ are determined separately and applied directly in Eq. {eq}`gibbs_t` at the specified $T$.

Using Eq. {eq}`gibbs_t`, exact $T$ where a system reaches equilibrium could be calculated. At any $T$ above or below this value the system will not longer be in equilibrium. The exact definition of equilibrium will be explored in the next chapter.

```{dropdown} Example: Calculating $\Delta _{rxn} G^\circ$ at specified $T$ 

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


## Practice Problems

(1) Calculate the kinetic energy of an oxygen atom moving at a speed of $\pu{100 m s−1}$. Hint: convert mass of an $\ce{O}$ atom from $\pu{amu}$ to $\pu{g}$.

(2) Calculate $\Delta_{rxn}H^\circ$ for the following reactions using thermodynamic data:

$$\begin{align*}
\ce{H2 + F2 &-> 2 HF\\
2 NO2 &-> N2O4
}
\end{align*}$$

(3) How is the system defined in this chemical reaction? Where does the energy go?

(4) According to a Clif Bar nutrition label, it contains $\pu{240 Cal}$ of energy. How much is this energy in $\pu{J}$?

(5) What would be good examples of open, closed, and isolated systems in nature?

(6) Of mass and concentration, which property is conserved in a system?

(7) Is a mixture of different gases a single phase?

(8) What component defines a pure $\ce{H2O}$ system?

(9) What component(s) defines an aqueous system composed of $\ce{CO2}$ and $\ce{CaCO3}$?

(10) How many properties are required to define a system of $\pu{1 L}$ pure $\ce{H2O}$?

(11) If $\Delta_{rxn}H^\circ = \pu{2803 kJ mol-1}$ for photosynthesis reaction shown below: 

$$\ce{6 H2O(l) + 6 CO2(g) ->[Sunlight] C6H12O6(s) + 6 O2(g)}$$

>Calculate the solar energy required to produce $\pu{75 g}$ of $\ce{C6H12O6}$.

(12) If $\Delta_{rxn}H^\circ = \pu{-72.4 kJ mol-1}$ for the reaction 

$$\ce{H2(g) + Br2(l) -> 2 HBr(g)}$$

> Calculate the amount of heat released when $\pu{1 kg}$ of $\ce{Br2}$ is consumed in this reaction.

(13) If $\Delta_{rxn}H^\circ = \pu{333.8 kJ mol-1}$ for the thermochemical equation, 

$$\ce{2 Cu2O -> 4 Cu + O2}$$

> Calculate the mass of copper produced when $\pu{1.47e4 kJ}$ is consumed in this reaction.

(14) Determine the enthalpy change for each reaction using the reaction data provided in the table below each reaction:

$$\ce{NO(g) + O(g) -> NO2(g)}$$

| Reaction      | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
|-------------------------|------:|
| $\ce{NO(g) + O3(g) -> NO2(g) + O2 (g)}$ | $-198.9$  |
| $\ce{O3(g)  -> 3/2 O2 (g)}$ | $-142.3$ |
| $\ce{O2(g) -> 2 O (g)}$  | $-571.6$ |

$$\ce{
3 H2 + O3 -> 3 H2O
}$$
| Reaction      | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
| ------------- | -------------: |
| $\ce{2 H2 (g) + O2(g) -> 2H2O (g)}$ | $-483.6$|
| $\ce{3 O2(g) -> 2 O3 (g)}$ | $284.6$ |

$$ \ce{
P4O6 + 2 O2 -> P4O10}
$$
| Reaction   | $\Delta_{rxn}H^\circ$, $\pu{kJ mol-1}$ |
|--------------|-----------------: |
| $\ce{P4 (s) + 3 O2(g) -> P4O6 (s)}$ | $-1640.1$ |
|  $\ce{P4(s) + 5O2(g) -> P4O10(s) }$ | $-2940.1$ |

(15) Calculate $\Delta_{rxn}S^\circ$of the following reactions at $\pu{25 ^\circ C}$:

$$
\begin{align*}
\ce{
N2 + 3 H2 &-> 2 NH3\\
H2 + Cl2 &-> 2 HCl\\
H2 + CuO &-> Cu + H2O\\
2 Al + 3 ZnO &-> Al2O3 + 3 Zn\\
CH4 + 2 O2 &-> CO2 + 2 H2O
}
\end{align*}
$$

(16) Determine sign of $\Delta_{sys}S$ for the following systems using the rules outlined in the section on entropy of substances:

> 1. Freezing ethanol
> 2. Evaporating water
> 3. Heating water
> 4. Condensing bromine vapor

(17) Calculate $\Delta_{rxn}G^\circ$ for the following reactions at $\pu{25 ^\circ C}$:

$$
\begin{align*}
\ce{
2 MgO &-> 2 Mg + O2\\
H2 + Br2 &-> 2 HBr\\
2 C2H6 + 7 O2 &-> 4 CO2 + 6 H2O
}
\end{align*}
$$

(18) Determine the $T$ at which the following reactions reach equilibrium:

$$
\begin{align*}
\ce{
2 MgO &-> 2 Mg + O2\\
H2 + Br2 &-> 2 HBr\\
2 C2H6 + 7 O2 &-> 4 CO2 + 6 H2O
}
\end{align*}
$$
