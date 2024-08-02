# Basic Math for Geoscientists

In this appendix, I will include basic algebra and calculus that are often useful in environmental geosciences.

## Numbers

### Scientific notation

In geosciences, you will work with numbers that are extremely large to numbers that are minuscule. As the numbers get bigger or smaller, the digits required to describe those numbers increase. For example, the number of people on Earth is approximately $\pu{8 billion}$, or $\pu{8 000 000 000}$. Nanoparticles refer to particles that have a size of the order of $\pu{0.000 000 0001 m}$, or a billionth of a meter. Manipulating extremely large and small numbers is unwieldy and errors creep in if we forget a digit (i.e. a factor of $10$).

To overcome this problem, scientists have developed a scientific shorthand notation for numbers which uses exponents. The general form is

$$C \times B^E \quad \text{or} \quad C \cdot B^E $$
where $C$ is the coefficient, $B$ is the base number and $E$ is the exponent. Both "$\times$" and "$\cdot$" can be used to signify multiplication of the $C$ and $B$. In this textbook, "$\cdot$" is used for scientific notation.

For example, in $\pu{1.234e2}$, $1.234$ is the coefficient, $10$ is the base number, and $2$ is the exponent.

Generally speaking, if $E<0$ and $C<10$ then the number being described is $<1$, for example, $\pu{8e-6 m}$. Moving between normal and scientific notation is straightforward. Each $0$ to the left of the period ‘$.$’ is a factor of $10$; for example, $1000$ has three zeros to the left of the period. Scientific notation is essentially about collecting the factors of $10$ together in a compact form.

```{table} List of commonly used prefixes used in the **International System of Units** (SI units).
:name: si-unit-prefixes
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

*Some examples of significant numbers using scientific notation:*
1. On 1/6/23, world's human population was $\pu{7.943e9 persons}$
2. On 1/6/23, US population was $\pu{3.343e8 persons}$
3. Avogadro's number: $\pu{6.022e23}$
4. Approximate diameter of a human hair is $\pu{75 \mu m}$ or $\pu{7.5e-5 m}$


### Significant Figures and Rounding Numbers

The numbers of digits shown for a measurement implies the level of measurement certainty. The number of significant figures is the number of digits provided. As the number of significant figures increases, the more certain the measurement becomes.

For example, the number $2000$ can be expressed as one significant figure $\pu{2e3}$, which lies between $\pu{1e3}$ ($1000$) and $\pu{3e3}$ ($3000$); two significant figures $\pu{2.0e3}$, which lies between $\pu{1.9e3}$ ($1900$) and $\pu{2.1e3}$ ($2100$); three significant figures $\pu{2.00e3}$, which lies between $\pu{1.99e3}$ ($1990$) and $\pu{2.01e3}$ ($2010$); etc.

Two rules apply with calculations involving significant figures:
1. In multiplication and division, round the final result to the least number of significant figures of any one term.
2. In addition and subtraction, round the final result to the least number of decimal places, regardless of the significant figures of any one term.

The number of decimal places is the number of digits after the ‘.’. 

For example, $\pi = \pu{3.141 592 65}$ is quoted to 9 significant figures and 8 decimal places. If we choose to quote $\pi = \pu{3.14}$ (3 sig. fig.), this is smaller than the longer number, so we have rounded down. If we choose $\pi = \pu{3.142}$ (4 sig. fig.), this is larger than the longer number, so we have rounded up. Generally, if the digit beyond the required significant figure is larger than or equal to 5 we round up, and if it is less than 5 we round down.


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

```{admonition} Common exponents
Exampes of common expressions with exponents.

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

1. $3x + 12$ or $3(x + 4)$
2. $17t + 34$ or $17(t + 2)$
3. $x + 2xy + 3xyz$ or $x(1 + 2y + 3yz)$
4. $\frac{1}{5a^2+35ab}$ or $\frac{1}{5a(a+7b)}$
5. $16abc − 8ab^2 + 24bc$ or $8b(2ac − ab + 3c)$
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

Recall that a quadratic equation is generally of the form $y = ax^2 + bx + c$ and must include a term to the power of 2 (the quadratic term), otherwise it is a linear equation ($a = 0$) or a constant ($a = b = 0$). Examples of quadratic equations include $5x^2 = 0$, $2x^2 + 3x + 2 = 0$, and $7x^2 − 2x = 0$.

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

For example, the average of the numbers 1 to 10 is calculated as follows:

$$
=\frac{1+2+3+4+5+6+7+8+9+10}{10}= 5.5
$$

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


## Calculus