# Sum and product of solutions

## 1. Sum

### 1.1 $ax^2 + c = 0$

#### Example 1.1.1

$$x^2 = 16$$

$$x = \pm 4$$

$$x_1 = -4, x_2 = 4$$

$$x_1 + x_2 = 0$$

#### Example 1.1.2

$$5x^2 = 125$$

$$x^2 = 25$$

$$x = \pm 5$$

$$x_1 = -5, x_2 = 5$$

$$x_1 + x_2 = 0$$

#### Generalizing

$$ax^2 = c$$

$$x^2 = \frac{c}{a}$$

$$x = \pm \sqrt{\frac{c}{a}}$$

$$x_1 = -\sqrt{\frac{c}{a}}, x_2 = \sqrt{\frac{c}{a}}$$

$$x_1 + x_2 = 0$$

$$ax^2 + c = 0$$

$$ax^2 = -c$$

$$x^2 = -\frac{c}{a}$$

$$x = \pm \sqrt{\frac{-c}{a}}$$

$$x_1 = -\sqrt{\frac{-c}{a}}, x_2 = \sqrt{\frac{-c}{a}}$$

$$x_1 + x_2 = 0$$

### 1.2 $a(x-h)^2 + k = 0$

#### Example 1.2.1

$$(x-1)^2 = 9$$

$$x - 1 = \pm 3$$

$$x = 1 \pm 3$$

$$x_1 = 1 - 3$$

$$x_2 = 1 + 3$$

$$x_1 + x_2 = 1 - 3 + 1 + 3$$

$$x_1 + x_2 = 2$$

#### Example 1.2.2

$$5(x-13)^2 = 125$$

$$(x-13)^2 = 25$$

$$x - 13 = \pm 5$$

$$x = 13 \pm 5$$

$$x_1 = 13 - 5, x_2 = 13 + 5$$

$$x_1 + x_2 = 13 - 5 + 13 + 5$$

$$x_1 + x_2 = 26$$

#### Generalizing

$$a(x-h)^2 + k = 0$$

$$a(x-h)^2 = -k$$

$$(x-h)^2 = -\frac{k}{a}$$

$$x - h = \pm \sqrt{-\frac{k}{a}}$$

$$x = h \pm \sqrt{-\frac{k}{a}}$$

$$x_1 = h - \sqrt{-\frac{k}{a}}, x_2 = h + \sqrt{-\frac{k}{a}}$$

$$x_1 + x_2 = 2h$$

### 1.3 $ax^2 + bx + c = 0$

#### Example 1.3.1

$$x^2 + 8x + 15 = 0$$

$$(x + 3)(x + 5) = 0$$

$$x_1 = -3, x_2 = -5$$

$$x_1 + x_2 = -8$$

#### Example 1.3.2

$$x^2 - 7x - 30 = 0$$

$$(x - 10)(x + 3) = 0$$

$$x_1 = -3, x_2 = 10$$

$$x_1 + x_2 = 7$$

#### Generalizing

##### Proof 1

$$a(x-p)(x-q) = 0$$

$$a(x^2 - px - qx + pq) = 0$$

$$a(x^2 - (p+q)x + pq) = 0$$

$$ax^2 - a(p+q)x + apq = 0$$

$$ax^2 + bx + c = 0$$

$$-a(p+q) = b$$

$$p + q = -\frac{b}{a}$$

##### Proof 2

$$ax^2 + bx + c = 0$$

$$x = \frac{-b}{2a} \pm \frac{\sqrt{b^2 - 4ac}}{2a}$$

$$x_1 = \frac{-b}{2a} - \frac{\sqrt{b^2 - 4ac}}{2a}$$

$$x_2 = \frac{-b}{2a} + \frac{\sqrt{b^2 - 4ac}}{2a}$$

$$x_1 + x_2 = -\frac{b}{a}$$

And if you're not used to seeing the quadratic formula like this, that's because the educational system has failed you. For the tiny price of repeating the $2a$, this otherwise mysterious beast of a formula suddenly opens itself up to us.

For this:

$$-\frac{b}{2a}$$

is the axis of symmetry, and this:

$$\pm \frac{\sqrt{b^2 - 4ac}}{2a}$$

is the number of steps we walk to get to the solutions:

$$+\frac{\sqrt{b^2 - 4ac}}{2a}$$

steps to the right and

$$-\frac{\sqrt{b^2 - 4ac}}{2a}$$

steps to the left from the axis of symmetry:

$$-\frac{b}{2a}$$

And we know that if we double the axis of symmetry, we get the sum of the solutions:

$$2 \cdot \left( -\frac{b}{2a} \right) = -\frac{b}{a}$$

## 2. Products

### 2.1 $ax^2 + c = 0$

#### Example 1.1

$$x^2 = 16$$

$$x = \pm 4$$

$$x_1 \cdot x_2 = -4 \cdot 4 = -16$$

#### Example 1.2

$$7x^2 = 63$$

$$x^2 = 9$$

$$x = \pm 3$$

$$x_1 = -3, x_2 = 3$$

$$x_1 \cdot x_2 = -9$$

$$ax^2 = c$$

$$x^2 = \frac{c}{a}$$

$$x = \pm \sqrt{\frac{c}{a}}$$

$$x_1 \cdot x_2 = -\sqrt{\frac{c}{a}} \cdot \sqrt{\frac{c}{a}}$$

$$x_1 \cdot x_2 = -\frac{c}{a}$$

---

### 2.2 $$a(x-h)^2 + k = 0$$

#### Example 2.2.1

$$(x-5)^2 = 16$$

$$x - 5 = \pm 4$$

$$x = 5 \pm 4$$

$$x_1 = 5 + 4$$

$$x_2 = 5 - 4$$

$$x_1 \cdot x_2 = (5 + 4)(5 - 4) = 5^2 - 4^2$$

$$x_1 \cdot x_2 = 25 - 16 = 9$$

#### Example 2.2.2

$$(x - 2)^2 = 7$$

$$x - 2 = \pm \sqrt{7}$$

$$x = 2 \pm \sqrt{7}$$

$$x_1 \cdot x_2 = (2 - \sqrt{7})(2 + \sqrt{7}) = 2^2 - 7$$

$$x_1 \cdot x_2 = h^2 + k$$

## 2.3 $ax^2 + bx + c = 0$

### Generalizing

#### Proof 1

$$x = \frac{-b}{2a} \pm \frac{\sqrt{b^2 - 4ac}}{2a}$$

$$x_1 \cdot x_2 = \left( -\frac{b}{2a} - \frac{\sqrt{b^2 - 4ac}}{2a} \right) \left( -\frac{b}{2a} + \frac{\sqrt{b^2 - 4ac}}{2a} \right)$$

$$x_1 \cdot x_2 = \left( -\frac{b}{2a} \right)^2 - \left( \frac{\sqrt{b^2 - 4ac}}{2a} \right)^2$$

$$x_1 \cdot x_2 = \frac{b^2}{(2a)^2} - \frac{b^2 - 4ac}{(2a)^2}$$

$$x_1 \cdot x_2 = \frac{b^2 - (b^2 - 4ac)}{4a^2}$$

$$x_1 \cdot x_2 = \frac{4ac}{4a^2}$$

$$x_1 \cdot x_2 = \frac{c}{a}$$

#### Proof 2

Here's another way of proving this. Let's work backwards:

$$a(x - p)(x - q) = 0$$

$$a(x^2 - px - qx + pq) = 0$$

$$ax^2 - a(p + q)x + apq = 0$$

$$ax^2 + bx + c = 0$$

$$b = -a(p + q)$$

$$c = apq$$

This is the one we're interested in:

$$pq = \frac{c}{a}$$

---

## Summary

The sum and product of the solutions follow the relationships:

- Sum: $x_1 + x_2 = -\frac{b}{a}$
- Product: $x_1 \cdot x_2 = \frac{c}{a}$

The steps for solving quadratic equations using these relationships demonstrate the usefulness of factoring and symmetry in solving for roots.

---

## Level 1

### Question 1.1

$$3x^2 + 6x + 7 = 0$$

What’s the sum of the solutions to the equation above?

$$x_1 + x_2 = -\frac{b}{a}$$

$$x_1 + x_2 = -\frac{6}{3} = -2$$

---

### Question 1.2

$$(x - 7)^2 + 9 = 0$$

What’s the sum of the solutions to the equation above?

$$x_1 + x_2 = 2 \cdot x_{\text{vertex}}$$

$$2 \cdot 7 = 14$$

---

### Question 1.3

$$5x^2 + 9x + 17 = 0$$

What’s the product of the solutions to the equation above?

$$x_1 \cdot x_2 = \frac{c}{a}$$

$$x_1 \cdot x_2 = \frac{17}{5}$$

---

### Question 1.4

$$2(x - 7)^2 - 32 = 0$$

What’s the product of the solutions to the equation above?

$$x_1 \cdot x_2 = h^2 + \frac{k}{a}$$

$$x_1 \cdot x_2 = 7^2 + \frac{-32}{2}$$

$$x_1 \cdot x_2 = 49 - 16$$

$$x_1 \cdot x_2 = 33$$

---

## Level 2

### Question 2.1

$$5x^2 + 20x - 5k = 0$$

In the given equation, $k$ is a positive constant. The sum of the solutions to the equation is $7k$. What is the value of $k$?

$$x_1 + x_2 = -\frac{b}{a}$$

$$x_1 + x_2 = -\frac{20}{5} = -4$$

$$x_1 + x_2 = 7k$$

$$-4 = 7k$$

$$k = -\frac{4}{7}$$

---

### Question 2.2

$$27x^2 + (27s + r)x + rs = 0$$

In the given equation, $r$ and $s$ are positive constants. The product of the solutions to the given equation is $krs$, where $k$ is a constant. What is the value of $k$?

$$x_1 \cdot x_2 = \frac{c}{a}$$

$$x_1 \cdot x_2 = \frac{rs}{27}$$

$$x_1 \cdot x_2 = krs$$

$$\frac{rs}{27} = krs$$

$$k = \frac{1}{27}$$

---

### Question 2.3

$$(k + 1)x^2 + 10x - (k - 2) = 0$$

In the given equation, $k$ is a positive constant. The product of the solutions to the equation is $\frac{k}{2}$. What is the value of $k$?

$$x_1 \cdot x_2 = \frac{c}{a}$$

$$x_1 \cdot x_2 = \frac{-(k-2)}{k+1}$$

$$x_1 \cdot x_2 = \frac{k}{2}$$

$$\frac{-(k-2)}{k+1} = \frac{k}{2}$$

Solving:

$$-2(k-2) = k(k+1)$$

$$-2k + 4 = k^2 + k$$

$$0 = k^2 + 3k - 4$$

$$0 = (k + 4)(k - 1)$$

$$k = 1 \text{ (since } k > 0)$$

## Level 3

### Question 3.1

$$(4x + q)(6x^2 - 54)(2x^2 - 16x + 8q) = 0$$

In the given equation, $q$ is a positive constant. The sum of the solutions to the equation is $\frac{18}{4}$. What is the value of $q$?

#### Factor 1:

$$4x_1 + q = 0$$

$$4x_1 = -q$$

$$x_1 = -\frac{q}{4}$$

#### Factor 2:

$$6x^2 - 54 = 0$$

In the $ax^2 + bx = 0$ form, the sum of the solutions is zero.

#### Factor 3:

$$2x^2 - 16x + 8q = 0$$

$$x_2 + x_3 = -\frac{b}{a}$$

$$x_2 + x_3 = -\frac{-16}{2} = 8$$

#### Putting it together:

$$x_1 + x_2 + x_3 = -\frac{q}{4} + 8$$

$$x_1 + x_2 + x_3 = \frac{18}{4}$$

Solving:

$$-\frac{q}{4} + 8 = \frac{18}{4}$$

$$8 = \frac{18 + q}{4}$$

$$32 = 18 + q$$

$$q = 14$$

### Question 3.2

$$(3x + r)(5x^2 - 45)(4x^2 - 20x + 2r) = 0$$

In the given equation, $r$ is a positive constant. The product of the solutions to the equation is $6$. What is the value of $r$?

#### Factor 1:

$$3x + r = 0$$

$$r = -3x$$

$$x_1 = -\frac{r}{3}$$

#### Factor 2:

$$5x^2 - 45 = 0$$

$$x_2 \cdot x_3 = -\frac{45}{5} = -9$$

#### Factor 3:

$$x_4 \cdot x_5 = \frac{r}{2}$$

#### Putting it together:

$$x_1 \cdot x_2 \cdot x_3 \cdot x_4 \cdot x_5 = -\frac{r}{3} \cdot -9 \cdot \frac{r}{2} = 6$$

$$r^2 = \frac{12}{3}$$

$$r^2 = 4$$

$$r = \pm 2$$

Since $r > 0$, we have:

$$r = 2$$

### Question 3.3

$$(5x^2 + rx - 45)(4rx^2 - 5x + 2r) = 0$$

In the given equation, $r$ is a positive constant. The sum of the solutions to the equation is $3r$. What is the value of $r$?

#### Factor 1:

$$x_1 + x_2 = -\frac{b}{a}$$

$$x_1 + x_2 = -\frac{r}{5}$$

#### Factor 2:

$$x_3 + x_4 = -\frac{b}{a}$$

$$x_3 + x_4 = -\frac{-5}{4r}$$

$$x_3 + x_4 = \frac{5}{4r}$$

#### Putting it together:

$$x_1 + x_2 + x_3 + x_4 = -\frac{r}{5} + \frac{5}{4r}$$

$$x_1 + x_2 + x_3 + x_4 = 3r$$

Solving the equation:

$$-\frac{r}{5} + \frac{5}{4r} = 3r$$

Multiplying both sides by $20r$ to eliminate the denominators:

$$-4r^2 + 25 = 60r^2$$

Bringing all terms to one side:

$$64r^2 = 25$$

Solving for $r$:

$$r^2 = \frac{25}{64}$$

$$r = \pm \frac{5}{8}$$

Since $r > 0$, we have:

$$r = \frac{5}{8}$$
