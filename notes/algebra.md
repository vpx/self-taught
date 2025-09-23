# Algebra

## Table of Contents

 - [Expressions](./expressions.md)
 - [Monomials](./monomials.md)
 - [Polynomials](./polynomials.md)
 - [Equations](./equations.md)
 - [Systems](./systems.md)

# Expressions

In mathematics, expressions are a combination of numbers containing operations.

Examples: 

$$3+2-4$$

$$\frac{5+3}{3}$$

$$\frac{9 \cdot 6}{9}$$

## Variables

A variable is a placeholder that is used to rappresent something.

For example, we can say that we have a variable $a$ (our placeholder) that is equal to $365$. And when we will use the variable $a$ is the same as writing 365:

$$5 + a$$

Is the same as writing:

$$5 + 365$$

They can be used to simplify things up or when you don't know what a value is.

## Monomials

Monomials are expressions containing one or more variables, and when no further operations are possible it's formed only by multiplications.

For example:

$$10xyz$$

We call the variables of a monomial the literal part. The number by which a variable is multiplied the coefficient. The sum of the exponents of the literal part the degree of the monomial.

For example in $3xy$, the $3$ is the coefficient, $xy$ is the literal part and $2$ is the degree of the monomial.

Let's look at some examples:

1 Define:

$$3xy + 6xz$$

Reduced to the normal form it become:

$$9xy$$

Here the $9$ is the coefficient, $xy$ the literal part and $2$ the degree.

2 Define:

$$9yz^3 - 6yz^3$$

Reduced to the normal form it become:

$$3yz^3$$

Here $3$ is the coefficient, $yz$ the literal part and $4$ is the degree.

3 Define:

$$3x + 3y$$

Not a monomial there since is an addition and no further operations are possible.

### Types

1. Similar: Two monomials reduced to normal form that have the same literal part.
2. Equal: Two monomials having both equal literal parts and coefficients.
3. Opposite: Two monomials with the same literal part but opposite coefficients.

## Polynomials

A polynomial can either be a single monomial or a sum/difference of two or more monomials. We can represent polynomials using a capital letter followed by the literal parts of the monomials without exponents; A polynomial is said to be in standard form if no further operations can be performed on it.

For example, let's define:

$$P(xyz) = 3x+5x^2y+2z$$

The degree of a polynomial is the monomial with the highest degree.
Here $P$ is a polynomial that have $xyz$ as literal parts, since the monomial with the highest degree has a degree of $3$ the degree of the polynomial is also $3$. 

### Types

1. Null: Polynomial composed of a null monomial
2. Opposite: Polynomials having coefficients opposite to one another 
3. Equal: Polynomial reduced to standard form having the same monomials

### Product of Polynomials

To find the product between two polynomials, we multiply each element of the first for each element of the second.

Let's calculate the product of the polynomials $P(x) = x^2 + 2x + 3$ and $D(x) = 2x - 1$:

$$P(x) \cdot D(x)$$

$$(x^2 + 2x + 3) \cdot (2x - 1)$$

$$(x^2 \cdot 2x) + (x^2 \cdot -1) + (2x \cdot 2x) + (2x \cdot -1) + (3 \cdot 2x) + (3 \cdot -1)$$

$$(2x^3)+(-x^2)+(4x^2)+(-2x)+(6x)+(-3)$$

$$2x^3 - x^2 + 4x^2 - 2x + 6x - 3$$

$$2x^3 + 3x^2 + 4x - 3$$

Let's compute the product of the monomial $P(x) = 2x$ with the polynomial $D(x) = 3x^2 + 4x - 1$:

$$P(x) \cdot D(x)$$

$$2x \cdot (3x^2 + 4x - 1)$$

$$(2x \cdot 3x^2) + (2x \cdot 4x) + (2x \cdot -1)$$

$$(6x^3)+(8x^2)+(-2x)$$

$$6x^3+8x^2-2x$$

### Division of Polynomials

### Rest Theorem

### Ruffinis's Rule

### Total Factoring

### Partial Factoring
# Equations

In mathematics, an equation is a mathematical formula that expresses the equality betwen two numbers.

$$a=b$$

In order to have a true equation, both the left hand side and the right hand side must be equal.
So solving an equation means finding the value that substituted to a variable give you a true equality, for example, consider:

$$a=5$$

Which number that substituted to $a$ will be equal to $5$ ?

If $a$ is equal to $5$:

$$5=5$$

In an equation we can subtract or add the same quantity to both side and the equation will remain true:

$$5=5$$

$$5 + 2 = 5 + 2$$

$$7 = 7$$

$$7 - 7 = 7 - 7$$

$$0 = 0$$

An example with multiplications and divisions:

$$5x + 3 = 6x + 1$$

$$-6x + 5x + 3 = 6x + 1 - 6x$$

$$-x + 3 = 1$$

$$-3 - x + 3 = 1 - 3$$

$$-x = 1 - 3$$

$$-1 \cdot -x = -2 \cdot -1$$

$$x = 2$$

### Solving Linear Equations (Degree 1)

Linear equations are of the form $ax+b=0$, where $a$ and $b$ are constants.
To solve a linear equation, isolate the variable $x$ by applying inverse operations (e.g., subtracting $b$ and then dividing by $a$).
The solution to a linear equation is a single value for $x$.

Example:

$$2x = 3$$

$${2x \over 2} = {3 \over 2}$$

$$x = {3 \over 2}$$

So the solution for $x$ to be true is $3\over2$.

### Solving Quadratic Equations (Degree 2)

The quadratic formula allows us to easily obtain the roots of any quadratic equation (Equations with a degree of 2) $ax^2+bx+c=0$. There is a very nice proof of this formula that uses geometry to give an intuitive understanding of this result. We show this proof below alongside the typical purely algebraic proof.

Theorem 1 (The Quadratic Formula): Let $a$, $b$, and $c$ be real numbers with $a\neq0$. Then the solutions to the quadratic equation $ax^2+bx+c=0$ are:

$$x={-b \pm \sqrt{b^2-4ac}\over2a}$$

We require that $a\neq0$ to ensure that $ax^2+bx+c=0$ is indeed a quadratic equation. If $a=0$, then $ax^2+bx+c=0$ is the same as $bx+c=0$, which is a linear equation.

### Geometric proof

Consider the quadratic equation $ax^2+bx+c=0$ with $a$, $b$, and $c$ as real numbers with $a\neq0$. Then:

$$ax^2+bx+c=0$$

$$ax^2+bx=-c$$

$$x^2 + \frac{b}{a}x = - \frac{c}{a}$$

We illustrate the equation above as follows:

- We denote $x^2$ to be the area of a square. Therefore, this square has side length $x$.
- We denote $\frac{b}{a}x$ to be the area of a rectangle whose side lengths are $x$ and $\frac{b}{a}$.
- Lastly, we denote $-\frac{c}{a}$ to denote the area of a rectangle whose side lengths are unimportant.

![Quadratic equation geometry proof](../media/quadratic_equations_one.png)

- Consider the rectangle $\frac{b}{a}x$. We separate this rectangle into two equal rectangles whose side lengths are $\frac{b}{2a}$ and $x$:

![Quadratic equation geometry proof step 2](../media/quadratic_equations_two.png)

We take the first of these rectangles and attach the side with side length $x$ to the top of the square $x^2$. We take the second of these rectangles and attach the side with side length $x$ to the right side of the square $x^2$. We add a smaller square with side length $\frac{b}{2a}$ (and area $\frac{b^2}{4a^2}$) to the lefthand side of the equation, and we add the same amount of area to the righthand side of the equation to balance the equality:

![Quadratic equation geometry proof step 3](../media/quadratic_equations_three.png)

From the above, we get the following equation:

$$(x+\frac{b}{2a})^2 = -\frac{c}{a} + \frac{b^2}{4a^2}$$

Therefore:

$$(x+\frac{b}{2a})^2 = \frac{-4ac+b^2}{4a^2}$$

$$x+\frac{b}{2a} = \sqrt{\frac{-4ac+b^2}{4a^2}}$$

$$x = -\frac{b}{2a} + \sqrt{\frac{-4ac+b^2}{4a^2}}$$

$$x = \frac{- b \pm \sqrt{-4ac+b^2}}{2a}$$

### Algebraic proof

Consider the quadratic equation $ax^2+bx+c=0$ with $a$, $b$, and $c$ as real numbers with $a \neq 0$. Then:

$$ax^2+bx+c=0$$

$$ax^2+bx=-c$$

$$x^2+\frac{b}{a}x = -\frac{c}{a}$$

$$x^2+\frac{b}{2a}x+\frac{b}{2a}x = -\frac{c}{a}$$

$$(x+\frac{b}{2a})^2=-\frac{c}{a} + \frac{b^2}{4a^2}$$

$$\sqrt{(x+\frac{b}{2a})^2} = \sqrt{\frac{-4ac + b^2}{4a^2}}$$

$$x+\frac{b}{2a} = \sqrt{\frac{-4ac + b^2}{4a^2}}$$

$$x = -\frac{b}{2a} + \sqrt{\frac{-4ac + b^2}{4a^2}}$$

$$x_1 = \frac{-b + \sqrt{b^2 - 4ac}}{2a}$$

$$x_2 = \frac{-b - \sqrt{b^2 - 4ac}}{2a}$$

### Solving cubic equations

The cubic formula, also known as Cardano's formula, provides a solution to cubic equations of the form $ax^3 + bx^2 + cx + d = 0$, where $a$, $b$, $c$, and $d$ are constants and $a \neq 0$. The formula is quite complex and involves multiple steps. It was discovered by the Italian mathematician Gerolamo Cardano in the 16th century. Here is the cubic formula:

Let $a$, $b$, $c$, and $d$ be the coefficients of the cubic equation $ax^3 + bx^2 + cx + d = 0$.

First, define $\Delta$ as:

$$\Delta = 18abcd - 4b^3d + b^2c^2 - 4ac^3 - 27a^2d^2$$

Then, compute:

$$C = \sqrt[3]{\frac{\Delta + \sqrt{\Delta^2 - 4b^3d^2 - 4a^3c^3 - 18abcd\Delta}}{2}}$$

Finally, the roots of the cubic equation are:

$$x_1 = \frac{-b - \frac{C}{\sqrt[3]{2}} - \frac{b^2 - 3ac}{3a}}{2}$$

$$x_2 = \frac{-b + \frac{C}{\sqrt[3]{2}} - \frac{b^2 - 3ac}{3a}}{2}$$

$$x_3 = \frac{-b - \frac{C}{\sqrt[3]{2}} + \frac{b^2 - 3ac}{3a}}{2}$$

Where $C$ can take either of the cubic roots (since there can be three distinct roots for a cubic equation). However, this formula is often not used directly in practice due to its complexity. Instead, numerical methods or approximation techniques are typically employed to find the roots of cubic equations.

### Quartic Formula

The quartic formula provides a solution to quartic equations of the form $ax^4 + bx^3 + cx^2 + dx + e = 0$, where $a$, $b$, $c$, $d$, and $e$ are constants and $a \neq 0$. The quartic formula is substantially more complicated than the quadratic and cubic formulas, and its derivation involves intricate algebraic manipulations. The quartic formula was first discovered by Lodovico Ferrari in the 16th century. Here is the quartic formula:

Let $a$, $b$, $c$, $d$, and $e$ be the coefficients of the quartic equation $ax^4 + bx^3 + cx^2 + dx + e = 0$.

First, define:

$$p = \frac{8ac - 3b^2}{8a^2}$$
$$q = \frac{b^3 - 4abc + 8a^2d}{8a^3}$$

Then, compute:

$$\Delta_0 = c^2 - 3bd + 12ae$$
$$\Delta_1 = 2c^3 - 9bcd + 27b^2e + 27ad^2 - 72ace$$
$$\Delta = \Delta_1^2 - 4\Delta_0^3$$

Next, define:

$$\alpha = \frac{-2\sqrt[3]{\Delta_1 + \sqrt{\Delta}}}{3}$$
$$\beta = \frac{-2\sqrt[3]{\Delta_1 - \sqrt{\Delta}}}{3}$$

Now, we have three cases:

1. If $\Delta > 0$, then there is only one real root and two complex roots.
2. If $\Delta = 0$, then there is a multiple root and one simple root.
3. If $\Delta < 0$, then there are four real roots.

Finally, the roots of the quartic equation are:

$$x_1 = \frac{-b - \sqrt{2p + \frac{\alpha + \beta}{2}} + \frac{q}{\sqrt{2p + \frac{\alpha + \beta}{2}}}}{4a}$$
$$x_2 = \frac{-b + \sqrt{2p + \frac{\alpha + \beta}{2}} - \frac{q}{\sqrt{2p + \frac{\alpha + \beta}{2}}}}{4a}$$
$$x_3 = \frac{-b - \sqrt{2p - \frac{\alpha + \beta}{2}} + \frac{q}{\sqrt{2p - \frac{\alpha + \beta}{2}}}}{4a}$$
$$x_4 = \frac{-b + \sqrt{2p - \frac{\alpha + \beta}{2}} - \frac{q}{\sqrt{2p - \frac{\alpha + \beta}{2}}}}{4a}$$

Similar to the cubic formula, the quartic formula is quite complex and not commonly used directly in practice due to its complexity. Instead, numerical methods or approximation techniques are typically employed to find the roots of quartic equations.

### Zero Product Property

If an equation equal to $0$ is formed only by multiplication we can say that whenever one of that multiplication is equal to $0$ then the equation will be true.

For example, define:

$$(x+3)\cdot(x-12)\cdot(x^5)=0$$

We that if $(x+3)$ or $(x-12)$ or $(x^5)$ is $0$ then the equation will be true since $0 \cdot 0$ is always $0$

### Factoring

Factoring an equation means finding the two factors that multiplied with each other gives the first equation as a result so you can then apply the zero product property on them:

$$x^2-3x-24=0$$

Can be made by these two factors:

$$(x+3)\cdot(x-8)=0$$

The rule is: You have to find the two number that multiplied together gives you $24$ and summed together gives you $3$.

### Factoring Cubic Equations

In a cubic equations if the coefficients of $b$ divided by $a$ is equal to $d$ divided to $c$ then the factoring by group is possible:

You make the total factorization between $a$ and $b$ and then between $c$ and $d$:

$$x^3+2x^2-5x-10=0$$

You see if $b$ divided by $a$ is equal to $d$ divided by $c$

$2\over{1}$ $=$ $-10\over{-5}$

Since its true you can make the total factorization:

$x^2(x+2)-5(x+2)$

$(x^2-5)(x+2)$

### Solving Third Degree Equations

Before solving third degree equations you have to see if $x=1$ is true and if $x=-1$ is true.

To find if $x=-1$ we can see if $a + c$ is equal to $b + d$ if so the solution is -1.

### Existence conditions

## Systems

In mathematics, a system is a relation between any abstract concept or entity that can be studied, analyzed, manipulated, and reasoned about within the framework of mathematics. These objects can take various forms, including numbers, shapes, functions, sets, vectors, matrices, groups, and more.

We can say that everything that is not composed only by itself has a system, from real-world objects to any mathematical concept.

Let's say you have an equation with two variables, and we want to substitute one variable with the solution of another equation; to represent the relation between them, we use a system, denoted by curly brackets `{}` encapsulating all equations that have a relation.

$$
\begin{cases}
y=1 \\
x-y=0 \\
\end{cases}
$$

Here we substitute $y$ with the solution of the other equation:

$$
\begin{cases}
y=1 \\
x-1=0 \\
\end{cases}
$$

Here we add the same value to both sides in order to get the final solution:

$$
\begin{cases}
y=1 \\
1+x-1=0+1 \\
\end{cases}
$$

Final solution:

$$
\begin{cases}
y=1 \\
x=1 \\
\end{cases}
$$

In equations, systems are particularly useful to represent the relation between our variables and the values that we want to substitute them with.
