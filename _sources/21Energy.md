# 2.1 Energy and Thermochemistry

## What is energy?

Energy is the capacity to do work. It can be in many forms: thermal energy (associated with the random motion of atoms and molecules), chemical energy (associated with bonds in chemical substances), potential energy (associated with the position of an object), kinetic energy (associated with motion), etc. Each of these forms of energy can be converted to another form (e.g., dropping an object converts potential energy to kinetic energy) but cannot be created or destroyed. This principle is called the ***law of conservation of energy***. SI unit of energy is joule or $\pu{J}$.

```{dropdown} Example: Kinetic Energy
The amount of kinetic energy possessed by $\pu{2 kg}$ mass moving at a speed of $\pu{1 m s−1}$, calculated as follows:

>$$
E_k = \frac{1}{2}m\nu^2 = \frac{1}{2}(\pu{ 2 kg})(\pu{1 m s-2})  = \pu{ 1 J}
$$
```

Matter can undergo physical and chemical changes. For example, freezing water does not involve breaking down water molecules and only involves changing the state of matter, i.e., physical change. This can be represented as follows: 

$$
\ce{H2O(l)  -> H2O(g)} 
$$

Chemical change involves making or breaking chemical bonds. Formation of water from constituent elements is an example of chemical change: 

$$\ce{2 H2(g) + O2(g) -> 2 H2O(l)} $$ 
In each case, a specific type of energy was involved in the change. This energy must be released or supplied for changes (reactions) to occur.


<div class="container">
<iframe src="https://www.youtube.com/embed/2S6e11NBwiw" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


Energy changes associated with physical processes and chemical reactions must be discussed in the context of a ***system*** and its ***surroundings***. A system is a specific part of the universe that interests us; the surroundings are the rest of the universe. Practically speaking, surroundings are immediately close to the system. In the above examples, ice or water is a system, and all other parts beyond this system (container, etc.) are the surroundings.


## How is energy transferred?

Physical and chemical changes within systems can exchange energy from within the system to the surroundings or vice versa.

Mass (e.g., coffee, gasoline) contained in a closed system (e.g., a Thermos flask or gas tank in a car) is a conserved quantity, but if the system is not closed, the amount of mass that goes in or out of the system can be measured. Likewise, we often have a system that is not closed, and we would like to know how much energy comes in or out. 

Energy is not a physical substance like water or coffee, so energy transfer cannot be measured with a meter or an instrument. So, how can we tell how much useful energy a car can "put out" on one gas tank?

The ***law of conservation of energy*** guarantees that all the chemical energy in the gasoline will reappear in some form, but not necessarily in a form useful for doing farm work. Tractors, like cars, are highly inefficient, and typically, $\pu{90 \%}$ of the energy they consume is converted directly into heat, which is carried away by the exhaust and the air flowing over the radiator. We distinguish the energy that comes out directly as heat from the energy that accelerates a trailer or plows a field, so we define a technical meaning of the ordinary word "work" to express the distinction.  

### What is work?

**Work** ($w$) is the energy that crosses a system boundary in response to a force moving through a distance (e.g., when a system changes volume) and is expressed mathematically as follows:

```{math}
:label: work

\text{Work} = \text{force} \times \text{distance}
```

### What is heat?

Heat represents a type of energy transfer and reflects the part of energy transfer that is not accounted for by mechanical work.

**Heat** ($q$) is the energy that crosses a system boundary in response to a temperature gradient.

### A Pond Analogy

Heat and work are forms of energy that are transferred in different ways. Suppose we consider the water in a deep pond. The water in the pond is quite large but finite and could be measured; it corresponds to a system's *internal energy*, $U$.

```{figure} /assets/PondAnalogy.png
---
name: PondAnalogyin
figclass: margin-caption
---
A pond analogy to relate the concepts of work and heat to the concept of energy.
```


Water may be added and subtracted from the pond in stream water (heat, $q$) by precipitation or evaporation (work, $w$). All the inflows and outflows of the lake can be monitored using appropriate instruments. If the only gains and losses of water are as follows: stream inflow and outflow are $q_i$ and $q_o$, respectively, the precipitation is $w_r$, and the evaporation is $w_e$, then the change in pond volume, $\Delta U$, can be calculated as:

$$
\Delta U = (q_i-q_o)+(w_r-w_e) = q + w
$$

Once water enters the pond, it becomes a stream or rainwater. The pond contains no identifiable stream or rainwater; it is simply water. Similarly, systems do not contain so much heat or work; they contain energy. The water level in the pond can be raised either by stream water alone *or* by rainwater alone; the temperature rise in the water bath can be caused either by heating (transferring energy due to a temperature difference) or by thrashing a paddle wheel about in it (transferring energy by doing work on the system).

Another implication or assumption in our pond analogy is that water is conserved; it cannot simply appear or disappear. The same proposition regarding energy is known as the first law of thermodynamics (explored in the following sections). For example, the energy expended in lifting a book off the floor to the table was not lost but transferred to the book.

## What is thermochemistry?

*Heat* and *thermal energy* are not to be used interchangeably. Heat is the transfer of thermal energy between two bodies at different temperatures. Matter does not contain heat - it contains thermal energy. ***Thermochemistry*** is the study of heat (transfer of thermal energy) associated with chemical reactions.

The above chemical reaction (formation of water) results in release of energy and can be written as follows: 

$$
\ce{2 H2(g) + O2(g) -> 2 H2O(l) + \text{Energy}}
$$

In this case, the system contains a mixture of all reactants and products. Because energy cannot be created or destroyed, it is transferred between the system and the surroundings. In the above chemical reaction, energy is created in the system and is transferred to its surroundings. This is an example of an ***exothermic reaction***.

Consider the decomposition of mercury(II) oxide ($\ce{HgO}$) at high temperatures: 

$$
\ce{\text{Energy} + 2 HgO(s) -> 2 Hg(l) + O2 (g)}
$$

For this reaction to occur, energy has to be supplied to the system from the surroundings. This is an example of an ***endothermic reaction***. 

<div class="container">
<iframe src="https://player.vimeo.com/video/73325384?h=6aab1f5431" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>


The above video shows how energy is consumed or produced during the forming or breaking of chemical bonds.  In an exothermic reaction, the energy contained in the products of a reaction is lower than the energy contained in the reactants, causing the excess energy to be released from the system to the surroundings. In an endothermic reaction, the products' energy is higher than the energy of the reactants.

```{figure} https://www.fda.gov/files/nutrition-facts-label-download-image2.jpg
---
name: fda-label
figclass: margin
---
An example of a US Food and Drug Administration (FDA)'s nutritional facts label. Note that the ``Calories'' on this label are kilocalories. Image source: [Food Labeling & Nutrition | FDA](https://www.fda.gov/food/food-labeling-nutrition)
```

SI unit for energy is joule ($\pu{J}$), another common unit of energy is calorie ($\pu{cal}$). A calorie is the energy required to raise the temperature of $\pu{1 g}$ of water by $\pu{1 ^\circ C}$. $\pu{1 cal} = \pu{4.184 J}$. Calories listed on nutrition labels (see figure ) are not "calories" but "kilocalories." To make the distinction, the first letter in Calories is capitalized. 

$$\pu{1 Cal} = \pu{1000 cal} = \pu{1 kcal} = \pu{4184 J}$$

```{figure} https://esha.com/wp-content/uploads/2015/02/eu_label_1-01.jpg
---
name: eu-label
figclass: margin
---
An example of a European Union's nutritional facts label. Image source: [EU Nutrition Facts Templates - Ingredients List Label | ESHA Research](https://esha.com/products/genesis-rd-food-labeling-software/labels-and-labeling/european-union-nutrition-facts-label/)
```


## What is Thermodynamics?

Thermodynamics is a scientific study that deals with different relative energy levels and energy transfers between systems and different states of matter. Chemical thermodynamics specifically deals with energy transfers related to chemical reactions and is primarily of interest in geochemistry. We will also focus on the concept of equilibrium and its theoretical underpinnings in thermodynamics. The laws of thermodynamics provide useful guidelines for understanding the exchange of energy between systems and the direction of chemical processes.

### Thermodynamic Systems

It is very important to clearly define the ***system*** in equilibrium thermodynamics. This system can be on the scale of the entire universe (for an astronomer), an aquifer (for a hydrogeologist), or a petri dish (for a microbiologist). The choice depends on the kind of problem of interest. For example, in a shore environment, different processes occur, and defining the bounds of the system becomes very important. See {numref}`earth-systems` for an example of how various processes on Earth can be studied using a systems approach.

```{figure} https://mynasadata.larc.nasa.gov/sites/default/files/2019-04/earth_system_diagram_print.jpg
---
name: earth-systems
figclass: margin-caption
---
Systems can be considered at many scales. This picture shows how energy and matter (elements, water, etc) are cycled across the entire Earth system at many scales.  Image source: [Earth System: Matter and Energy Cycles | MyNASAData](https://mynasadata.larc.nasa.gov/basic-page/earth-system-matter-and-energy-cycles)
```

A system is any portion of the universe that can be isolated from the rest of the universe for the purpose of observing and measuring changes. By saying that a system is any portion of the universe, we mean that the system can be whatever the observer defines it to be. In {numref}`earth-systems`, we can see different parts of Earth can be subdivided into subsystems and studied separately for convenience.  A system is conceptual in design and needs to be defined more clearly by the observer.  It can be large or small, simple or complex. It can be a laboratory experiment in a beaker or a lake, a small sample of rock, an ocean, a volcano, a mountain range, a continent, or an entire planet. A leaf is a system; it is part of a larger system (a tree), part of an even larger system (a forest), and so on. 

An isolated system from the rest of the universe means it must have a boundary that sets it apart from its surroundings. The nature of the boundary is one of the most important defining features of a system, allowing us to establish three basic kinds of systems—open, closed, and isolated—with different types of boundaries.

```{admonition} Types of systems

There are three types of systems: 
1. Open systems - can exchange mass and energy with surroundings
2. Closed systems - can exchange energy with surroundings
3. Isolated systems - no exchange of mass or energy with surroundings

In {numref}`earth-systems`, the Earth system is an open system internally with the free exchange of mass and energy.  Since there is negligible mass exchange with Earth and its surroundings in the solar system, it is a closed system for mass. However, Earth gains and loses energy from within the solar system, an open energy system.
```

Since matter and energy are shared between systems and surroundings, it would be useful to quantify the flow of mass and energy.  The amount of matter (or energy) transferred across a system's boundary and the rate at which it is transferred is called a ***flux***. It is quantified in units of *mass or volume per time*.

The storage and movement of material and energy in a group of interacting systems is often represented as a ***box model***. A box model can be used to show the following essential features of a system: 
1. The processes by which matter (or energy) enters and leaves the system and the rates at which they do so.
2. The processes by which matter (or energy) moves among the various parts of the system internally and the rates at which this happens.
3. The amount of matter (or energy) in the system at a given time and its distribution.

As shown in {numref}`hydro-box-model`, the “boxes” in a box model represent the places where water (or energy, or whatever might be the material of interest) is stored for some time within the system. These storage places are called ***reservoirs***.  When the flux of matter into a reservoir matches the flux out of that reservoir, we say that the reservoir is at ***steady state***. The average time water spends in these reservoirs is called its ***residence time***. The residence time of any material in any particular reservoir is determined by the interaction of many factors, including the physical, chemical, and biological properties of the material itself, the properties of the reservoir, and any external forces or processes acting on either the material or the reservoir.


```{figure} assets/water-cycle-science.jpeg
---
name: hydro-box-model
figclass: margin-caption
---
The global hydrological cycle is shown as a box model in this figure. Fluxes ($\pu{e3 km3 yr-1}$) and reservoirs ($\pu{e3 km3}$) with natural and anthropogenic cycles are included. Big vertical arrows show total annual precipitation and evapotranspiration over land and ocean ($\pu{e3 km3 yr-1}$), which include annual precipitation and evapotranspiration in major landscapes ($\pu{e3 km3 yr-1}$) presented by small vertical arrows; parentheses indicate area ($\pu{e6 km2}$). The direct groundwater discharge, estimated to be about $\pu{10 \%}$ of total river discharge globally, is included in river discharge.  Image source: [Global Hydrological Cycles and World Water Resources | Science](https://www.science.org/doi/10.1126/science.1128845)
```

Under steady-state conditions, the residence time can be calculated as shown in eq {eq}`residence-time`.

```{math}
:label: residence-time
\text{Residence time} = \dfrac{\text{Reservoir Amount}}{\text{Rate of addition/removal}}
```


### States and State Variables

In thermodynamics, it is crucial to explicitly define a system's properties (e.g., composition, energy, temperature, pressure, and volume). These properties help us understand changes in the ***state of the system*** during a chemical process. When the state of the system changes, these properties change. ***State variables*** (or ***state functions***) are properties determined by the system's state, regardless of how they were achieved. That is, when the state of the system changes, the magnitude of the change only depends on the initial and final states of the system and not on how the change is accomplished. Energy, pressure, temperature, and volume are examples of state variables. Several important state variables are not measurable in the absolute sense in a particular equilibrium state, though they do have fixed, finite values in these states. However, the changes between the equilibrium states can be measured. Changes in system variables can be denoted below. The $\Delta$ is a standard mathematical symbol for change and refers to the *final* minus *initial* values, as shown below.

$$
	\begin{eqnarray*}
		\Delta E &=& E_{final}-E_{initial}\\
		\Delta P &=& P_{final}-P_{initial}\\
		\Delta V &=& V_{final}-V_{initial}\\
		\Delta T &=& T_{final}-T_{initial}
	\end{eqnarray*}
$$

Thermodynamic properties can be extensive properties or intensive properties. ***Extensive properties*** are dependent on the amount of the material in the system (e.g., mass, volume.) ***Intensive properties*** are independent of the amount of material. They are the same for any subset of the material in the system (e.g., concentration, temperature, pressure). {numref}`state-properties` lists a summary of the most commonly-used state variables.

```{table} Commonly-used state extensive and intensive properties and their standard SI units. Note: Molar properties are normalized by moles of material, while specific properties are normalized by mass.
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
Let's determine the concentration in a solution ($s$) formed when one spoon ($\pu{5 mL}$) of seawater ($sw$) from Folly Beach ($=\pu{10.8 g L-1}$) at $\pu{25 ^\circ C}$ is added to $\pu{1.0 L}$ of freshwater ($fw$) from the Goose Creek reservoir ($=\pu{6 mg L^{-1}}$). 

>Since concentration is an intensive and not additive property, it must be transformed into an extensive property. The extensive property equivalent of concentration is mass ($m = C\times V$, where $m$ is mass, $C$ is concentration, and $V$ is volume). 
>
>$$
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
>$$
```


### Phases and Components

Thermodynamic properties are used to define the state of the system. However, we need to know how many properties are required to define a system. You can intuitively guess that this would depend on the system's complexity. The number of properties required is determined by the number of phases and components in the system.

A ***phase*** is defined as a homogeneous body of matter with distinct boundaries with adjacent phases and hence can be mechanically separable. A phase's shape, orientation, and position relative to adjacent phases are irrelevant, so a single phase may occur in several locations within a system. Examples of single phases include quartz in granite and a salt solution. There are three common phases: solid, liquid, gas, and vapor. A system with only one phase is *homogeneous* and a system with multiple phases is *heterogeneous*.

***Components*** are used to describe the chemical composition of a system. They are defined as the smallest set of chemical formulas required to completely describe the composition of all the phases that make up a system. For example, in a $\ce{NaCl}$ solution (it doesn't matter if there is water vapor or calcite precipitate in the solution), the combination of $\ce{NaCl}$ describes the composition of all phases.

So, how many thermodynamic properties does one need in a system with $P$ phases and $C$ components? According to the ***Gibbs Phase Rule,***, $C-P+2$ properties are needed.

*Why do we need to know thermodynamic properties?* This will become clear as we study the laws of thermodynamics.

Unlike what you have learned about the definition of a law according to the scientific method, thermodynamics laws are concepts held to be true without derivation or proof. The basis of thermodynamics is built on three conservation statements: in any process, mass, energy, and momentum are conserved.

Initially, only three laws of thermodynamics were formulated.  However, when the fourth law was formulated, it was decided that this fourth law was even more fundamental than the original three laws. Instead of renumbering the original three laws, the fourth law was named the "Zeroth" law.
