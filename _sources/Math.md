# Review of Basic Mathematics

In this appendix, I will include basic algebra and calculus that are often useful in environmental geosciences.

<div class="container">
<iframe src="https://www.youtube.com/embed/3icoSeGqQtY" 
frameborder="0" allowfullscreen class="video"></iframe>
</div>

## Numbers

### Scientific notation

In geosciences, you will work with numbers that are extremely large to numbers that are minuscule. As the numbers get bigger or smaller, the digits required to describe those numbers increase. For example, the number of people on Earth is approximately $\pu{8 billion}$, or $\pu{8 000 000 000}$. Nanoparticles refer to particles that have a size of the order of $\pu{0.000 000 0001 m}$, or a billionth of a meter. Manipulating extremely large and small numbers is unwieldy and errors creep in if we forget a digit (i.e. a factor of $10$).

To overcome this problem, scientists have developed a scientific shorthand notation for numbers which uses exponents. The general form is

$$C \times B^E \quad \text{or} \quad C \cdot B^E $$
where $C$ is the coefficient, $B$ is the base number and $E$ is the exponent. Both "$\times$" and "$\cdot$" can be used to signify multiplication of the $C$ and $B$. In this textbook, "$\cdot$" is used for scientific notation.

For example, in $\pu{1.234e2}$, $1.234$ is the coefficient, $10$ is the base number, and $2$ is the exponent.

Generally speaking, if $E<0$ and $C<10$ then the number being described is $<1$, for example, $\pu{8e-6 m}$. Moving between normal and scientific notation is straightforward. Each $0$ to the left of the period ‘$.$’ is a factor of $10$; for example, $1000$ has three zeros to the left of the period. Scientific notation is essentially about collecting the factors of $10$ together in a compact form.

```{admonition} Examples of commonly-used prefixes in SI units

List of commonly used prefixes used in the **International System of Units** (SI units).

| Prefix | Symbol | Base $10$ | Decimal          |
| ------ | ------- | ------- | ----------------- |
| peta   | P       | $\pu{e15}$   | $\pu{1000000000000000}$  |
| tera   | T       | $\pu{e12}$   | $\pu{1000000000000}$     |
| giga   | G       | $\pu{e9}$    | $\pu{1000000000}$        |
| mega   | M       | $\pu{e6}$    | $\pu{1000000}$           |
| kilo   | k       | $\pu{e3}$    | $\pu{1000}$              |
| hecto  | h       | $\pu{e2}$    | $\pu{100}$               |
| deca   | da      | $\pu{e1}$    | $\pu{10}$                |
|     |        | $\pu{e0}$       |     $\pu{1}$              |
| deci   | d       | $\pu{e-1}$    | $\pu{0.1}$               |
| centi  | c       | $\pu{e-2}$   | $\pu{0.01}$              |
| milli  | m       | $\pu{e-3}$   | $\pu{0.001}$             |
| micro  | μ       | $\pu{e-6}$   | $\pu{0.000001}$          |
| nano   | n       | $\pu{e-9}$   | $\pu{0.000000001}$       |
| pico   | p       | $\pu{e-12}$   | $\pu{0.000000000001}$    |
| femto  | f       | $\pu{e-15}$  | $\pu{0.000000000000001}$ |
```

```{admonition} Examples of scientific notation
Some examples of significant numbers using scientific notation:
1. On 1/6/23, world's human population was $\pu{7.943e9 persons}$
2. On 1/6/23, US population was $\pu{3.343e8 persons}$
3. Avogadro's number: $\pu{6.022e23}$
4. Approximate diameter of a human hair is $\pu{75 \mu m}$ or $\pu{7.5e-5 m}$
```


### Significant Figures and Rounding Numbers

The numbers of digits shown for a measurement implies the level of measurement certainty. The number of significant figures is the number of digits provided. As the number of significant figures increases, the more certain the measurement becomes.

For example, the number $2000$ can be expressed as one significant figure $\pu{2e3}$, which lies between $\pu{1e3}$ ($1000$) and $\pu{3e3}$ ($3000$); two significant figures $\pu{2.0e3}$, which lies between $\pu{1.9e3}$ ($1900$) and $\pu{2.1e3}$ ($2100$); three significant figures $\pu{2.00e3}$, which lies between $\pu{1.99e3}$ ($1990$) and $\pu{2.01e3}$ ($2010$); etc.

Two rules apply with calculations involving significant figures:
1. In multiplication and division, round the final result to the least number of significant figures of any one term.
2. In addition and subtraction, round the final result to the least number of decimal places, regardless of the significant figures of any one term.

The number of decimal places is the number of digits after the ‘.’. 

```{admonition} Example of significant figures

For example, $\pi = \pu{3.141 592 65}$ is quoted to 9 significant figures and 8 decimal places. If we choose to quote $\pi = \pu{3.14}$ (3 sig. fig.), this is smaller than the longer number, so we have rounded down. If we choose $\pi = \pu{3.142}$ (4 sig. fig.), this is larger than the longer number, so we have rounded up. Generally, if the digit beyond the required significant figure is larger than or equal to 5 we round up, and if it is less than 5 we round down.
```


### Units and Dimensions

Everything we measure has a unit associated with it: meters, degrees Celsius (or kelvin), seconds, etc. Best practice is to state units for all answers. The dimension of a physical quantity indicates explicitly how the quantity is related, through its defining equation, to the basic quantities.

Basic quantities of interest in this book include length $[L]$, which is measured in meters; time $[T]$, which is measured in seconds; and mass $[M]$ which is measured in kilograms. Whenever a calculation is performed, it is important that the dimension of the equation remains consistent.

````{margin}
The units used here are part of the International System of Units (SI).  For a nice summary, see [International System of Units - Wikipedia](https://en.wikipedia.org/wiki/International_System_of_Units).
````


## Algebra

### Subscripts and superscripts

In geosciences, the subscript is typically used to help clarify the meaning of a variable. For example, the density ($\rho$, rho) of a rock can be written as $\rho_\text{rock}$.

The superscript, often called the *exponent*, has a definite mathematical meaning: raise a number to the power of the exponent. For example, $x^2$ means raise $x$ to the power of $2$, (i.e. take the ‘square’ of $x$). Similarly, $x^3$ means raise $x$ to the power of $3$ (take the ‘cube’ of $x$). For the example $X^a _b$ we say that $a$ is the superscript of $X$ and $b$ is the subscript.

```{admonition} Rules for exponents
These are the basic rules for manipulating numbers that have exponents.

$$
\begin{align}
x^a x^b &= x^{a+b}\\
\frac{1}{x^a} &= x^{-a}\\
\frac{x^a}{x^b} &= x^{a-b}\\
(x^a)^b &= x^{ab}
\end{align}
$$

Below are some basic applications of exponents.

$$
\begin{align}
x^0  &= 1\\
x^1 &= x
\end{align}
$$

```

When numbers are encountered in the format such as $X^A$, it denotes some number $X$ to the *power of $A$*, where $A$ can be a whole or fractional number (e.g., 2 or 1/3). $A$ is called the exponent (or power or index) and $X$ is called the base. Here are some examples:

```{admonition} Examples of common expressions with exponents

$$
\begin{align}
x^2 &= x\times x \quad x \text{ squared}\\
x^3 &= x\times x \times x \quad x \text{ cubed}\\
x^0  &= 1\\
x^1 &= x \\
x^{1/2} &= \sqrt{x}\\
x^{-1} &= \frac{1}{x}\\
x^{-2} &= \frac{1}{x^2}\\
\end{align}
$$
```

### Factorization

Factorization is a fancy word for simplifying algebraic equations by identifying and grouping common factors in individual terms. This helps to solve equations.

```{admonition} Examples of factorization
In the expressions below, a common factor was identified an isolated.

$$
\begin{align*}
3x + 12 & = 3(x + 4)\\
17t + 34 & = 17(t + 2)\\
x + 2xy + 3xyz & = x(1 + 2y + 3yz)\\
\frac{1}{5a^2+35ab} & = \frac{1}{5a(a+7b)}\\
16abc − 8ab^2 + 24bc & = 8b(2ac − ab + 3c)
\end{align*}
$$
```

### Linear and quadratic equations

Generally, the type of equation is named after its highest exponent. Equations of the form $y = ax + b$, where $a$ and $b$ are constant values, are called ***linear equations***, where the $x$ variable has a power of $1$ ($x^1$). 

Equations of the form $y = ax^2 + bx + c$, where $a$, $b$, and $c$ are constant values, are called ***quadratic equations***, where the highest exponent is $2$. Note that this example of a quadratic equation includes linear and constant terms. In this textbook, you will mainly see linear and quadratic equations. 


### Transposing equations

‘Transpose’ means rearrange. The general rule is: *whatever you do to the left-hand side (LHS) of the equation you do to the right-hand side (RHS) of the equation so they remain equal*.

For example, the area $A$ of a circle is related to its radius $r$ as $A = \pi r^2$. Here, $A$ is the subject of the equation. If we want to know the radius that corresponds to a circle area of $\pu{10 m2}$ we have to rearrange the equation so that $r$ is the subject. 

First, we need to remove $\pi$ from the RHS by dividing both sides of the equation:

$$
\begin{align}
\frac{A}{\pi} &= \frac{\pi r^2}{\pi}\\
&=r^2
\end{align}
$$

To make $r$ the subject of the equation, we have to take the square root of $r^2$:


$$
\begin{align}
\sqrt\frac{A}{\pi} &= \sqrt{r^2}\\
r=&\pm \sqrt\frac{A}{\pi}
\end{align}
$$

When you take the square root of a number you have two possible answers (positive and negative) because, in the reverse, when you square the negative number you get the same answer as squaring the positive number. Typically, it is clear which root you should use in subsequent calculations, but in general you should report the positive and negative roots.

## Solving equations

### Linear equations

A linear equation is one of the form $ax + b = y$, where $a$ and $b$ are numbers and the unknown quantity is $x$. Some definitions:
1. $a$ is called the ***coefficient*** of $x$ and $b$ is a ***constant***.
2. $x$ is called the ***independent variable*** and $y$ is the ***dependent variable***; $y$ depends on $x$.
3. $a$ is often called the ***gradient*** or ***slope of the line***.
4. $b$ is called the ***intercept of the line*** because $y = b$ when $x = 0$.

Linear equations can be solved graphically by plotting on a linear $xy$ graph, as shown in {numref}`linear-eq-graph`.  A grid system is used in algebra to show a relationship between two variables in a rectangular coordinate system. The rectangular coordinate system is also called the $xy$-plane or the ***coordinate plane***.

The horizontal number line is called the ***x-axis***. The vertical number line is called the ***y-axis***. The _x_-axis and the _y_-axis together form the rectangular coordinate system. These axes divide a plane into four regions, called **quadrants**. For linear equations we only need two points on a line to define the equation.

```{figure} https://openstax.org/apps/archive/20221109.213337/resources/9222fa07edf6cea53550fe1c2c41646dd2062293
---
name: linear-eq-graph
figclass: margin-caption
---
An $xy$ graph of a linear equation. Image source: [4.2 Graph Linear Equations in Two Variables - Elementary Algebra 2e | OpenStax](https://openstax.org/books/elementary-algebra-2e/pages/4-2-graph-linear-equations-in-two-variables)
```

We solve linear equations by using algebra to simplify and transpose the expression (as shown in the previous section). Find the value of the unknown variable that satisfies each of the following equations.

### Quadratic equations

Recall that a quadratic equation is generally of the form $y = ax^2 + bx + c$ and must include a term to the power of 2 (the quadratic term), otherwise it is a linear equation ($a = 0$) or a constant ($a = b = 0$). 

```{admonition} Examples of quadratic equations
1. $5x^2 = 0$
2. $2x^2 + 3x + 2 = 0$
3. $7x^2 − 2x = 0$
```

We focus on three approaches to solving quadratic equations.

#### Factoring by Inspection

 If one is given a quadratic equation in the form $ax^2 + bx + c=0$, the sought factorization has the form $(x + q)(x + s)$, and one has to find two numbers $q$ and $s$ that add up to $b$ and whose product is $c$. As an example, $x^2 + 5x + 6$ factors as ($x + 3)(x + 2)$. The more general case where $a$ does not equal $1$ can require a considerable effort in trial and error guess-and-check, assuming that it can be factored at all by inspection.

Except for special cases such as where $b = 0$ or $c = 0$, factoring by inspection only works for quadratic equations that have rational roots. This means that the great majority of quadratic equations that arise in practical applications cannot be solved by factoring by inspection.

#### Completing the Square

The process of completing the square makes use of the algebraic identity

$$x^2+2hx+h^2=(x+h)^2$$

which represents a well-defined [algorithm](https://en.wikipedia.org/wiki/Algorithm "Algorithm") that can be used to solve any quadratic equation. Starting with a quadratic equation in standard form, $ax^2 + bx + c=0$

1.  Divide each side by $a$, the coefficient of the squared term.
2.  Subtract the constant term $\frac{c}{a}$ from both sides.
3.  Add the square of one-half of $\frac{b}{a}$, the coefficient of $x$, to both sides. This *completes the square*, converting the left side into a perfect square.
4.  Write the left side as a square and simplify the right side if necessary.
5.  Produce two linear equations by equating the square root of the left side with the positive and negative square roots of the right side.
6.  Solve each of the two linear equations.

```{admonition} Example of completing the square

We illustrate use of this algorithm by solving $2x^2 + 4x - 4 = 0$

$$
\begin{align*}
2x^2+4x-4 &=0\\
x^2+2x-2 &=0\\
x^2+2x &=2\\
x^2+2x+1 &=2+1\\
(x+1)^2 &= 3\\
x+1 &= \pm\sqrt{3}\\
x &= -1 \pm \sqrt{3}
\end{align*}
$$

The $\pm$ symbol indicates that both $x=-1+\sqrt{3}$ and $x=-1-\sqrt{3}$ are solutions of the quadratic equation.
```

A general formula for solving quadratic equation, $ax^2 + bx + c=0$ is shown below.

$$
x = \frac{-b \pm \sqrt{b^2-4ac}}{2a}
$$
When $b^2=4ac$ in the above equation, $x$ will have one distinctive root. When $b^2<4ac$, the solutions will produce roots with [Imaginary number](https://en.wikipedia.org/wiki/Imaginary_number).

> Note that in the above solution both roots have to be evaluated with the problem being considered. 

#### Graphical Solution

The solutions of the quadratic equation, $ax^2 + bx + c=0$ can be deduced from the graph of the graphical function $f(x) = ax^2 + bx + c$, which is a parabola.

If the parabola intersects the $x$-axis in two points, there are two real roots, which are the $x$-coordinates of these two points (also called $x$-intercept).

```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Polynomialdeg2.svg/600px-Polynomialdeg2.svg.png
---
width: 250px
name: fig-quadratic
figclass: margin-caption
---
For the quadratic function $y = x^2 − x − 2$, the points where the graph crosses the $x$-axis, $x = −1$ and $x = 2$, are the solutions. Image source: [Quadratic equation - Wikipedia](https://en.wikipedia.org/wiki/Quadratic_equation)
```

If the parabola is tangent to the $x$-axis, there is a double root, which is the $x$-coordinate of the contact point between the graph and parabola.

If the parabola does not intersect the x-axis, there are two complex conjugate roots with real and imaginary parts.

### Simultaneous equations

For the linear equations in the previous section we solved for one unknown, but we may have more than unknown (e.g. $5x + 2y = 0$). In general, we need n equations for n unknowns, so two equations are required to solve for two unknowns.

The general approach is as follows:
1. Simplify equations by collecting common terms.
2. Eliminate one of the unknowns by: (a) subtracting (adding) one equation from (to) the other; (b) or rearranging the equations so that each have the same subject (e.g. x = ?).
3. Solve for the remaining unknown using algebra.
4. Solve for the eliminated unknown by inserting the solved unknown into one of the original equations.
5. Verify your results by inserting your answers into the original equations.

You can also solve simultaneous equations graphically.

## Statistics

The most-commonly encountered statistical parameter includes the ***mean*** (or average). It is also commonly called the arithmetic mean. It is the sum of a set of $n$ numbers divided by $n$. 

```{admonition} Example of calculating an average

The average of the numbers 1 to 10 is calculated as follows:

$$
\text{Average} =\frac{1+2+3+4+5+6+7+8+9+10}{10}= 5.5
$$
```

A more general statement about the mean of $n$ measurements of a quantity $x$:

$$
\bar{x}= \frac{1}{n}\sum_{i=1} ^n x_i
$$

This may look a little daunting, so let us break it down into parts:
1. The subscript $i$ of $x$ denotes the $i$th value of the quantity $x$.
2. $\sum$ is shorthand for ‘summation’, so in this equation we are summing successive values of $x$.
3. The numbers on the bottom and top of $\sum$ are called the limits of the sum. In our present example, we are summing from $i = 1$ to $i = n$. For our numerical example that sums the first 10 numbers (excluding zero), $n = 10$.
4. The bar above $\bar{x}$ denotes the mean value of $x$.

An alternative method of describing data is to use the ***median*** value, which is described as the number separating the higher half of a dataset from the lower half. This is obtained by ranking the data in order of magnitude and taking the central value; take the mean of the middle two numbers if you have an even number of points. A big difference between the mean and median of a dataset quickly highlights this problem.

The ***variance*** of a dataset is a measure of the spread of possible values, averaging the squared distance of individual values from the mean value. This is opposed to the mean, which is a way to describe the location of a distribution. The following formula, using the notation outlined above, describes the sample variance, denoted by $\sigma^2$:

$$\sigma^2 = \frac{1}{n-1} \sum_{i=1} ^n (\bar{x}-x_i)^2
$$

In words, this is the mean square deviation about the mean. The ***standard deviation*** (often denoted by $\sigma$) of a dataset is found by taking the square root of the variance:


$$\sigma = \sqrt{\frac{1}{n-1} \sum_{i=1} ^n (\bar{x}-x_i)^2}
$$


```{figure} https://upload.wikimedia.org/wikipedia/commons/thumb/f/f9/Comparison_standard_deviations.svg/400px-Comparison_standard_deviations.svg.png
---
name: mean-sd
figclass: margin-caption
---
Example of samples from two populations with the same mean but different variances ($\sigma^2$). The red population has $\bar{x}=100$ and $\sigma^2=100$ ($\sigma=10$) while the blue population has $\bar{x}=100$ and $\sigma^2=2500$ ($\sigma=50$). Image source: [Variance - Wikipedia](https://en.wikipedia.org/wiki/Variance)
```

## Logarithms and Exponentials

### Exponentials

Exponential notation is used to express very large and very small numbers as a product of two numbers. The first number of the product, the _digit term_, is usually a number not less than 1 and not greater than 10. The second number of the product, the _exponential term_, is written as 10 with an exponent. 

An expression of the form $a^x$ is called an exponential expression. The number $a$ is the base and $x$ is the power or exponent or index. Exponential growth occurs when the growth becomes more rapid in proportion to the size of the quantity increasing; exponential decay can be treated as a negative growth rate.

```{admonition} Examples of exponential notation

$$
\begin{align*}
1000 &= \pu{1e3}\\
100 &= \pu{1e2}\\
10 &= \pu{1e1}\\
1 &= \pu{1e0}\\
0.1 &= \pu{1e-1}\\
0.01 &= \pu{1e-2}\\
0.001 &= \pu{1e-3}\\
1682 &= \pu{1.682 \times 10^3} =  \pu{1.682e3}\\
0.324 &= \pu{3.24 \times 0.1} = \pu{3.24e-1}
\end{align*}
$$

```

#### Adding and Subtracting

Convert all numbers to the same power of 10, add the digit terms of the numbers, and if appropriate, convert the digit term back to a number between 1 and 10 by adjusting the exponential term.

```{admonition} Example of adding exponential numbers

To add $\pu{5.00e-5}$ with $\pu{3.00e-3}$, convert one of numbers to the same exponential as the other:

$$
\begin{align*}
\pu{3.00e-3} &= \pu{300e-5}\\
(\pu{5.00e-5}) + (\pu{300e-5}) &= [(5.00) + (300)]\times \pu{e-5} = \pu{305e-5} = \pu{3.05e-3}
\end{align*}
$$

```

```{admonition} Example of subtracting exponential numbers

To subtract $\pu{4.0e-7}$ from $\pu{5.0e-6}$, convert one of numbers to the same exponential as the other:

$$
\begin{align*}
\pu{4.0e-7} &= \pu{0.40e-6}\\
(\pu{5.0e-6}) - (\pu{0.40e-6}) &= [(5.0)-(0.40)]\times\pu{e-6} = \pu{4.6e-6}
\end{align*}
$$

```


#### Multiplication and Division

For multiplication, multiply the digit terms in the usual way and add the exponents of the exponential terms.

```{admonition} Example of multiplying exponential numbers

To multiply $\pu{4.2e-8}$ by $\pu{4.0e3}$,

$$
\begin{align*}
(\pu{4.2e-8}) \times (\pu{4.0e3}) &= (4.2\times 4.0) \times 10^{(-8)+(+3)}\\
&=\pu{16.8e-5} = \pu{1.68e-4}
\end{align*}
$$

```

For divisions, divide the digit term of the numerator by the digit term of the denominator and subtract the exponents of the exponential terms.

```{admonition} Example of dividing exponential numbers

Divide $\pu{3.6e5}$ by $\pu{6.0e-4}$,

$$
\begin{align*}
\frac{\pu{4.2e-8}}{\pu{4.0e3}} &= \frac{4.2}{4.0} \times 10^{(-5)-(-4)}\\
&=\pu{0.60e-1} = \pu{6.0e-2}
\end{align*}
$$

```


#### Squares, Cubes, Square Roots

To square an exponential, square the digit term in the usual way and multiply the exponent of the exponential term by 2. 

```{admonition} Example of squaring an exponential number
Square the number $\pu{4.0e-6}$.

$$
\begin{align*}
(\pu{4.0e-6})^2 &= (4)^2 \times 10^{2\times(-6)}\\
&=16 \times \pu{e-12} = \pu{1.6e-11}
\end{align*}
$$
```

To cube an exponential, cube the digit term in the usual way and multiply the exponent of the exponential term by 3.

```{admonition} Example of cubing an exponential number
Cube the number $\pu{2.0e4}$.

$$
\begin{align*}
(\pu{3.0e4})^3 &= (3)^3 \times 10^{3\times(4)}\\
&=27 \times \pu{e12} = \pu{2.7e13}
\end{align*}
$$
```

For determining square roots  of exponential numbers, decrease or increase the exponential term so that the power of 10 is evenly divisible by 2. Extract the square root of the digit term and divide the exponential term by 2.

```{admonition} Example of square root of an exponential number
Find the square root of the number $\pu{1.6e-7}$.

$$
\begin{align*}
\pu{1.6e-7} &= \pu{16e-8}\\
\sqrt{\pu{16e-8}} &= \sqrt{16} \times \sqrt{\pu{e-8}} = \sqrt{16} \times 10^{-\frac{8}{2}} = \pu{4.0e-4}
\end{align*}
$$
```


### Logarithms

Logarithms provide a way to succinctly describe data with a wide range of values. Within geosciences, we work from the nano scale ($\pu{e-9 m}$) to the planetary scale ($\pu{e6 m}$), straddling more than 15 orders of magnitude. Essentially, logarithms provide a shortcut for exponents.

In general, if $y = a^x$ then $\log _a y = x$.

```{admonition} Example of a simple logarithm
For example, from $100 = 10^2$ we obtain that $\log_{10} 100 = 2$.
```


The most common bases are base $10$ and the base $e$. The mathematical constant $e$ has a value of $\pu{2.71828}$ and occurs in many natural phenomena, for example, radioactive decay. We will follow the convention that logs to the base 10 are denoted by $\log$ or $\log_{10}$ and logs to the base $e$ (referred to as natural logarithms) are denoted by $\ln$ or $\log_e$. Get familiar with the $\log$ and $\ln$ buttons on your calculator.

```{admonition} Three main logarithm laws
There are three main logarithm laws (applies to both $\log$ and $\ln$):

$$
\begin{align*}
\log (ab) &= \log a + \log b \\
\log \frac{a}{b} &= \log a - \log b \\
\log a^n &= n \log a
\end{align*}
$$

$$
\begin{align*}
\ln (ab) &= \ln a + \ln b \\
\ln \frac{a}{b} &= \ln a - \ln b \\
\ln a^n &= n \ln a
\end{align*}
$$
```



## Calculus

Calculus is the study of how things change and provides a framework for modelling phenomena (natural or otherwise) in which there is change, and a way to deduce the predictions of such models. Calculus is important for geologists because it helps them understand the behavior of natural systems, such as the movement of groundwater through aquifers, the deformation of rocks under stress, and the flow of heat through the Earth’s interior. Calculus is also used to model the behavior of natural systems, which can help geologists make predictions about future events.

Calculus provides an approach to construct relatively simple quantitative models of change, and to deduce their consequences. The Earth system is ever changing on a wide spectrum of temporal and spatial scales. Without calculus we are limiting our understanding of the natural world. Using calculus, we can better understand the effects of changing conditions on the phenomena under investigation.

In calculus we are dealing with small changes in quantities. These changes are typically denoted by $\Delta$ and $d$ so that $\Delta x = dx$ is a small change in the variable $x$.

Differential calculus is the branch of calculus that deals with the study of rates of change and slopes of curves. It is used to find the instantaneous rate of change of a function at a given point. The derivative of a function is the slope of the tangent line to the function at a given point.

Integral calculus is the branch of calculus that deals with the study of areas under and between curves. It is used to find the total change or accumulation of a function over an interval. The definite integral of a function is the area under the curve of the function between two points.

### Differential Calculus

The derivative of a function and their applications are usually the main concept . The derivative of a function at a chosen input value describes *the rate of change of the function near that input value*. The process of finding a derivative is called *differentiation*. Geometrically, the derivative at a point is the slope of the tangent line to the graph of the function at that point, provided that the derivative exists and is defined at that point. For a real-valued function of a single real variable, the derivative of a function at a point generally determines the best linear approximation to the function at that point.

#### Derivative

A derivative is a measure of how much a function changes as its input changes. This is, the derivative of a function $f$ at a point $x$ is the slope of the line tangent to the graph of $f$ at $x$. The derivative of the function $f(x)$ is denoted by $f'(x)$ or $dy/dx$, and is defined as the limit of the ratio of the change in y to the change in $x$ as the change in $x$ approaches zero. Mathematically, this can be expressed as:

$$
f'(x) = \lim_{\Delta x → 0} \frac{[f(x + \Delta x) - f(x)]}{\Delta x}
$$

where $\Delta x$ represents a small change in $x$ and $\lim_{\Delta x → 0}$ is shorthand for "at the limit of $\Delta x$ approaching 0".

Intuitively, this equation means that to find the derivative of a function at a given point, we look at how much the function changes as we make a small change in its input value, and then divide this change by the size of the input change. Taking the limit as the input change approaches zero gives us the instantaneous rate of change, or the slope of the tangent line, at that point.


### Integral Calculus

Integration is the opposite of differentiation. 