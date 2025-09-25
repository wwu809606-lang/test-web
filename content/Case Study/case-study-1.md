---
title: "Case Study 1"
weight: 1
---
## Overview

To bridge the gap between abstract algebraic theory and its practical application, we will explore 10 distinct case studies. Each case translates a familiar, real-world scenario—from calculating the cost of a phone plan to understanding the vastness of the QR code universe—into a mathematical model. This approach is designed to make core concepts such as linear functions, polynomial operations, inequalities, and exponential growth more intuitive and tangible. Throughout these examples, we will leverage visualization tools like GeoGebra to see these mathematical relationships in action, turning static formulas into dynamic, interactive models. The following table provides a complete overview of the journey ahead, outlining each case and the key concepts we will master along the way.

| No. | Case Name | Key Concepts Covered |
|:--- |:--- |:--- |
| 1 | The Picture Frame | Polynomial expansion; Distributive law & FOIL method; Geometric meaning of algebraic terms |
| 2 | The Phone Plan | Linear functions ($y = mx + b$); Slope and y-intercept; Rate of change; Units |
| 3 | The Thermostat | Compound inequalities; Interval notation; Number line representation |
| 4 | The Break-Even Point | Systems of linear equations; Intersection of lines; Real-world meaning of a solution |
| 5 | The Projectile's Flight | Quadratic equations; Factoring to find roots; Physical meaning of roots (solutions) |
| 6 | Can the Rocket Reach? | The discriminant of a quadratic equation; Relating the discriminant to the number of real solutions; Feasibility analysis |
| 7 | Average Production Cost | Rational expressions; Domain of a function; Long-run behavior and horizontal asymptotes |
| 8 | The Profitable Window | Quadratic inequalities; Solving for roots with the quadratic formula; Sign diagrams to determine intervals |
| 9 | Budgeting Time and Money | Systems of linear inequalities; Graphing inequalities in two variables; Feasible region |
| 10 | The QR Code Universe | Exponential growth (Exponents); Orders of magnitude and large numbers; Using logarithms for estimation |


## Case 1: The Picture Frame

### Key concepts covered
- Polynomial expansion
- Distributive law & FOIL method
- Geometric meaning of algebraic terms

### Scenario
An everyday object, a picture frame, provides a perfect visual for understanding polynomial multiplication. Imagine a 15 cm × 10 cm photograph that is to be placed in a wooden frame of uniform width. Let the width of the frame be $x$ cm on all sides. How does the total area of the photo plus the frame change as we vary $x$? This scenario directly translates "composing shapes" into "multiplying binomials," showing why quadratic and linear terms naturally arise from a simple geometric arrangement.

### From scenario to model
The original photo has a fixed area of $15 \times 10 = 150$ cm². When the frame of width $x$ is added, it increases the dimensions on all four sides. The new total length becomes the original 15 cm plus $x$ for the left side and $x$ for the right side, totaling $15 + 2x$. Similarly, the new total width becomes $10 + 2x$.

The total area, $A(x)$, can be written as the product of these new dimensions:
$$A(x) = (15 + 2x)(10 + 2x)$$
This compact expression perfectly models the geometry. To understand the individual contributions of the photo and the different parts of the frame, we need to expand this product.

### Quick review: Binomial Products
We rely on the distributive law, often remembered by the acronym FOIL (First, Outer, Inner, Last) for multiplying two binomials:
$$(A + B)(C + D) = AC + AD + BC + BD$$
In our case, $A = 15$, $B = 2x$, $C = 10$, and $D = 2x$.

### Expansion and Geometric Correspondence
Let's expand the expression for the area:
$$A(x) = (15)(10) + (15)(2x) + (2x)(10) + (2x)(2x)$$
$$A(x) = 150 + 30x + 20x + 4x^2$$
Combining the like terms gives the final polynomial:
$$A(x) = 4x^2 + 50x + 150$$

Each term in this expanded form corresponds to a distinct geometric part of the framed picture:
-   **150**: This is the constant term, representing the unchanged area of the original photo ($15 \times 10$).
-   **50x**: This linear term is the sum of the areas of the rectangular frame strips. It can be broken down further:
    -   **30x**: Area of the top and bottom strips (two rectangles, each $15 \times x$).
    -   **20x**: Area of the left and right strips (two rectangles, each $10 \times x$).
-   **4x²**: This quadratic term represents the area of the four small squares at the corners of the frame, each with dimensions $x \times x$.

### Interpretation and Sanity Checks
-   The model correctly shows that the total area is the sum of the photo's area, the side strips' areas, and the corner squares' areas.
-   **Sanity Check 1 (No Frame)**: If $x = 0$, the frame has no width.
    $A(0) = 4(0)^2 + 50(0) + 150 = 150$. This is the area of the photo alone, which is correct.
-   **Sanity Check 2 (1 cm Frame)**: If $x = 1$, the total dimensions are $15 + 2(1) = 17$ cm and $10 + 2(1) = 12$ cm.
    The total area is $17 \times 12 = 204$ cm².
    Using our polynomial: $A(1) = 4(1)^2 + 50(1) + 150 = 4 + 50 + 150 = 204$. The model works perfectly.

### Common confusions to avoid
A frequent mistake is to model the new dimensions as $(15 + x)$ and $(10 + x)$, forgetting that the frame adds width to **both** sides (left/right and top/bottom). This would incorrectly miss half the frame's area.

### Self-study suggestions (visualization tools)
-   Use GeoGebra or Desmos. Draw the central $15 \times 10$ rectangle.
-   Create a slider for $x$ (from 0 to 5, for instance).
-   Draw the four corner squares ($x \times x$) and the four rectangular strips. Color-code each of the four components (photo, top/bottom strips, left/right strips, corners).
-   Display the values of $4x^2$, $50x$, and $150$ as $x$ changes, and show that their sum always equals the total area calculated from $(15+2x)(10+2x)$.

***

## Case 2: The Phone Plan

### Key concepts covered
- Linear functions ($y = mx + b$)
- Slope and y-intercept
- Rate of change
- Units

### Scenario
Many real-world costs are not a single flat fee but a combination of a fixed starting charge and a variable rate that depends on usage. A mobile phone bill is a perfect example of this. By creating a simple algebraic model for this cost, we can see precisely how the abstract mathematical concepts of "slope" and "y-intercept" represent concrete, everyday financial terms that appear on a bill.

### From scenario to model
Let's define our variables. Let $g$ be the amount of data used in a month, measured in gigabytes (GB). Let $C(g)$ be the total monthly cost in dollars. The plan has two components: a fixed base fee of $20, and a variable charge of $5 for every GB of data used.

Combining these, we can write the total cost as a function of data usage:
$$C(g) = 5g + 20$$
This is a linear function, which is one of the most fundamental models in mathematics and science.

### Quick review: Linear Functions
A linear function has the general form $y = mx + b$. It's crucial to remember what each part represents:
-   **$b$ is the y-intercept**: This is the starting value of $y$ when $x$ is zero.
-   **$m$ is the slope**: This is the rate of change. It tells us how much $y$ increases for every one-unit increase in $x$.

### Interpretation of the Model's Components
By comparing our cost function $C(g) = 5g + 20$ to the general form $y = mx + b$, we can assign a clear meaning to each number:
-   **The y-intercept is $b = 20$**: In this context, it represents the fixed monthly fee. It's the cost you must pay even if you use zero data ($g=0$). Graphically, this is where the cost line crosses the vertical axis.
-   **The slope is $m = 5$**: This represents the rate, or the variable cost. The units are crucial here: the slope is **$5 per GB**. It tells us that for each additional gigabyte of data you use, your monthly bill will increase by exactly $5.

### Sanity checks
Let's test the model with some simple values to confirm our understanding:
-   **No data usage ($g = 0$):**
    $C(0) = 5 \times 0 + 20 = 20$. The cost is $20, which matches the base fee as expected.
-   **10 GB of data usage ($g = 10$):**
    $C(10) = 5 \times 10 + 20 = 50 + 20 = 70$. The cost is $70, comprising $50 for the data and $20 for the base fee.

### Common confusions to avoid
-   **Mixing up slope and intercept**: The intercept is a fixed starting amount, while the slope is a rate that scales with usage.
-   **Forgetting units**: The slope is not just "5," it's "$5 per GB." Units give the numbers their real-world meaning.
-   **Misinterpreting the base fee**: The $20 is a fee for having the service, not a payment that covers the "first few" gigabytes.

### Self-study suggestions (visualization tools)
-   Use GeoGebra or Desmos to plot the function $y = 5x + 20$. Notice where it intersects the y-axis. Use the slope tool or draw a "slope triangle" to see that for every 1 unit you move right, you move 5 units up.
-   Create sliders for the slope `m` (the rate) and the y-intercept `b` (the base fee).
    -   Change the `b` slider and watch the entire line shift up or down. This is like the phone company changing its monthly base fee.
    -   Change the `m` slider and watch the line become steeper or flatter. This is like the company changing its price per gigabyte.

***

## Case 3: The Thermostat

### Key concepts covered
- Compound inequalities
- Interval notation
- Number line representation

### Scenario
For comfort and energy efficiency, a building's management system is programmed to keep the indoor temperature $T$ "at least 18°C and at most 25°C." This simple instruction is a real-world example of a mathematical constraint that defines an acceptable range of values. How do we translate this verbal rule into a precise mathematical statement and visualize it?

### From scenario to model
The phrase "at least 18°C" means the temperature $T$ can be 18°C or higher, which we write as:
$$T \ge 18$$
The phrase "at most 25°C" means the temperature $T$ can be 25°C or lower, which we write as:
$$T \le 25$$
Since both conditions must be true simultaneously, we combine them into a single **compound inequality**:
$$18 \le T \le 25$$

### Quick review: Inequalities and Interval Notation
-   **Inequality symbols**: $<$ (less than), $>$ (greater than), $\le$ (less than or equal to), $\ge$ (greater than or equal to). "Or equal to" corresponds to inclusive bounds.
-   **Interval notation**: A compact way to represent a range. It uses parentheses `()` for exclusive endpoints (value is not included) and square brackets `[]` for inclusive endpoints (value is included).
-   **Number line**: A visual graph of the solution set. A filled-in or closed circle (●) is used for an inclusive endpoint, while an open circle (○) is used for an exclusive endpoint.

### Interpretation and Representation
-   **Compound Inequality**: $18 \le T \le 25$ is the most direct mathematical translation.
-   **Interval Notation**: Since both 18 and 25 are included in the allowed range, we use square brackets. The interval is written as:
    $[18, 25]$
-   **Number Line Graph**: We draw a number line, place closed circles at 18 and 25, and shade the line segment between them. This visually represents all possible valid temperatures.

### Sanity checks
-   Is 17°C allowed? No, $17 < 18$.
-   Is 20°C allowed? Yes, $18 \le 20 \le 25$.
-   Is 25°C allowed? Yes, the boundary is inclusive.
-   Is 26°C allowed? No, $26 > 25$.

### Common confusions to avoid
-   **Mixing up inclusive and exclusive**: Using $<$ instead of $\le$ would incorrectly exclude the boundary temperatures of 18°C and 25°C. This translates to using $(18, 25)$ instead of $[18, 25]$.
-   **Confusing "and" with "or"**: An "and" inequality (like this case) represents an intersection of two conditions—a single segment. An "or" inequality (e.g., $T < 10$ or $T > 30$) represents a union—two separate rays pointing outwards.

### Self-study suggestions (visualization tools)
-   On a number line (digital or on paper), graph and compare the following:
    1.  The thermostat range: $[18, 25]$
    2.  A temperature that is strictly *between* 18°C and 25°C: $(18, 25)$
    3.  A fever temperature, defined as being strictly above 37.5°C: $(37.5, \infty)$
-   Use GeoGebra to plot the inequalities $x \ge 18$ and $x \le 25$. Observe how the software shades the number line and that the solution is the overlapping region.

***

## Case 4: The Break-Even Point

### Key concepts covered
- Systems of linear equations
- Intersection of lines
- Real-world meaning of a solution

### Scenario
A small business is launching a new product. The specialized machine to produce it costs $300 (a **fixed cost**). Each item produced costs an additional $5 in materials and labor (a **variable cost**). The business plans to sell each item for $20. How many items must be sold to cover all costs? This critical point, where the company is neither making a profit nor a loss, is the **break-even point**.

### From scenario to model
Let $x$ be the number of items produced and sold. We need to model two things: the total cost and the total revenue.

1.  **Total Cost Function, C(x):** This is the sum of the fixed cost and the total variable cost.
    $$C(x) = 5x + 300$$
2.  **Total Revenue Function, R(x):** This is the income from selling $x$ items.
    $$R(x) = 20x$$

The break-even point occurs when total cost equals total revenue. We find it by setting the two functions equal to each other:
$$C(x) = R(x)$$
$$5x + 300 = 20x$$

### Solving and Interpretation
This is a simple linear equation. To solve for $x$, we gather the $x$ terms on one side:
$$300 = 20x - 5x$$
$$300 = 15x$$
$$x = \frac{300}{15} = 20$$

**Interpretation**: The business must sell **20 items** to break even.
-   At $x = 20$, the total cost is $C(20) = 5(20) + 300 = 100 + 300 = \$400$.
-   At $x = 20$, the total revenue is $R(20) = 20(20) = \$400$.
The costs and revenue are equal, confirming our result. Graphically, this point $(20, 400)$ is where the cost line and the revenue line intersect. For any $x > 20$, the revenue line will be above the cost line, indicating a profit. For any $x < 20$, the business will be at a loss.

### Common confusions to avoid
-   **Forgetting the fixed cost**: A common error is to only consider variable costs, which would drastically miscalculate the break-even point.
-   **Misinterpreting the intersection**: Students should understand that the intersection point gives both the number of items ($x$-coordinate) and the dollar amount ($y$-coordinate) for the break-even moment.

### Self-study suggestions (visualization tools)
-   Use Desmos or GeoGebra to plot the two linear functions: $y = 5x + 300$ and $y = 20x$.
-   Click on the intersection point to verify that it is $(20, 400)$.
-   Create sliders for the fixed cost, variable cost per item, and selling price.
    -   Increase the fixed cost and watch the break-even point move to the right (more items needed).
    -   Increase the selling price and watch the break-even point move to the left (fewer items needed). This provides a powerful visual for business sensitivity analysis.

***

## Case 5: The Projectile's Flight

### Key concepts covered
- Quadratic equations
- Factoring to find roots
- Physical meaning of roots (solutions)

### Scenario
An object is launched upwards from a platform 25 meters high. Its height $h$ (in meters) above the ground after $t$ seconds is given by the quadratic function $h(t) = -5t^2 + 20t + 25$. When does the object hit the ground? This question is equivalent to finding the time $t$ for which the height $h(t)$ is zero.

### From scenario to model
To find when the object hits the ground, we need to solve the equation $h(t) = 0$:
$$-5t^2 + 20t + 25 = 0$$
This is a quadratic equation. While the quadratic formula always works, factoring is often faster and more insightful when possible.

### Factoring and Solving
**Step 1: Factor out the Greatest Common Factor (GCF).**
The coefficients -5, 20, and 25 are all divisible by -5. Factoring out -5 simplifies the equation:
$$-5(t^2 - 4t - 5) = 0$$
We can now divide both sides by -5 to get:
$$t^2 - 4t - 5 = 0$$

**Step 2: Factor the trinomial.**
We need two numbers that multiply to -5 and add to -4. These numbers are -5 and +1. So, the factored form is:
$$(t - 5)(t + 1) = 0$$

**Step 3: Solve for the roots.**
For the product of two factors to be zero, at least one of them must be zero:
$$t - 5 = 0 \quad \text{or} \quad t + 1 = 0$$
$$t = 5 \quad \text{or} \quad t = -1$$

### Interpretation
We have two mathematical solutions: $t = 5$ and $t = -1$.
-   **$t = 5$**: This is a physically meaningful solution. The object hits the ground 5 seconds after being launched.
-   **$t = -1$**: This is a physically extraneous solution. Time in this model starts at $t=0$. The negative root represents the time when the object *would have* been at ground level *if* its parabolic flight path had started from the ground before $t=0$. In the context of our problem, we discard it.

The answer is **5 seconds**.

### Common confusions to avoid
-   **Sign errors during factoring**: Be careful with signs, especially after factoring out a negative GCF.
-   **Forgetting to interpret the roots**: It's crucial to evaluate whether both mathematical solutions make sense in the physical context of the problem. Time cannot be negative here.

### Self-study suggestions (visualization tools)
-   Plot the function $h(t) = -5t^2 + 20t + 25$ in GeoGebra or Desmos (use $x$ for $t$ and $y$ for $h$).
-   Observe the parabolic shape (opening downwards because of the -5 coefficient).
-   Identify the y-intercept at $(0, 25)$, which is the initial launch height.
-   Identify the x-intercepts (the roots) at $(-1, 0)$ and $(5, 0)$. This visually confirms our algebraic solution and shows why one root is discarded.
-   Find the vertex of the parabola. What does its y-coordinate represent? (The maximum height reached by the object).

***

## Case 6: Can the Rocket Reach?

### Key concepts covered
- The discriminant of a quadratic equation ($ \Delta = b^2 - 4ac $)
- Relating the discriminant to the number of real solutions
- Feasibility analysis without full solving

### Scenario
A model rocket is launched, and its height $h$ in meters after $t$ seconds is given by $h(t) = -5t^2 + 50t$. The design team has two target altitudes they are curious about: 125 meters and 130 meters. Without necessarily finding the exact time(s), can we determine if the rocket can reach each of these heights?

### From scenario to model
To check if the rocket can reach a certain height, we set its height function equal to that target height. This creates a quadratic equation.

**Target 1: 125 meters**
Is there a time $t$ such that $h(t) = 125$?
$$-5t^2 + 50t = 125$$
Rearranging into standard form ($ax^2 + bx + c = 0$):
$$5t^2 - 50t + 125 = 0$$
Dividing by 5 to simplify:
$$t^2 - 10t + 25 = 0$$

**Target 2: 130 meters**
Is there a time $t$ such that $h(t) = 130$?
$$-5t^2 + 50t = 130$$
Rearranging and simplifying:
$$5t^2 - 50t + 130 = 0$$
$$t^2 - 10t + 26 = 0$$

### Quick review: The Discriminant
For a quadratic equation $ax^2 + bx + c = 0$, the discriminant is $\Delta = b^2 - 4ac$. It tells us about the nature of the roots without having to calculate them:
-   If $\Delta > 0$, there are **two distinct real solutions**. (The parabola intersects the horizontal line twice).
-   If $\Delta = 0$, there is **exactly one real solution**. (The line is tangent to the parabola at its vertex).
-   If $\Delta < 0$, there are **no real solutions**. (The parabola and the line never intersect).

### Analysis using the Discriminant
**For the 125 m target ($t^2 - 10t + 25 = 0$):**
Here, $a=1, b=-10, c=25$.
$$\Delta = (-10)^2 - 4(1)(25) = 100 - 100 = 0$$
Since $\Delta = 0$, there is exactly one real solution for $t$.

**For the 130 m target ($t^2 - 10t + 26 = 0$):**
Here, $a=1, b=-10, c=26$.
$$\Delta = (-10)^2 - 4(1)(26) = 100 - 104 = -4$$
Since $\Delta < 0$, there are no real solutions for $t$.

### Interpretation
-   **125 meters is reachable**. Because there is only one solution, this event happens at exactly one moment in time. This means 125 meters is the rocket's maximum height (the vertex of its parabolic path).
-   **130 meters is unreachable**. There is no real time $t$ at which the rocket's height is 130 meters. It's beyond the rocket's maximum altitude.

The discriminant allows us to answer "is it possible?" efficiently, without completing the quadratic formula.

### Self-study suggestions (visualization tools)
-   In GeoGebra or Desmos, plot the height function $y = -5x^2 + 50x$.
-   Plot the two horizontal target lines: $y = 125$ and $y = 130$.
-   Visually confirm the results:
    -   The line $y = 125$ touches the parabola at its peak (tangent).
    -   The line $y = 130$ is entirely above the parabola and never intersects it.
-   Create a slider for a target height `H`. Plot the line `y = H` and observe how the number of intersection points changes as you move the slider up and down. Relate this to the discriminant of $-5x^2 + 50x - H = 0$ being positive, zero, or negative.

***

## Case 7: Average Production Cost

### Key concepts covered
- Rational expressions
- Domain of a function
- Long-run behavior and horizontal asymptotes

### Scenario
A factory has a fixed monthly operating cost of $1000 (rent, machinery maintenance, etc.). In addition, each unit it produces has a variable cost of $2 (materials, direct labor). We want to understand how the *average cost per unit* behaves as the factory's production volume changes.

### From scenario to model
Let $x$ be the number of units produced in a month.

1.  **Total Cost, C(x):** This is the sum of fixed and variable costs.
    $$C(x) = 2x + 1000$$
2.  **Average Cost, A(x):** This is the total cost divided by the number of units produced.
    $$A(x) = \frac{C(x)}{x} = \frac{2x + 1000}{x}$$

This is a **rational expression**. To better understand its behavior, we can split the fraction:
$$A(x) = \frac{2x}{x} + \frac{1000}{x} = 2 + \frac{1000}{x}$$

### Concepts and Interpretation
-   **Domain**: The number of units produced, $x$, must be a positive number. You cannot produce zero or a negative number of units, and mathematically, we cannot divide by zero. So, the domain is $x > 0$.

-   **Behavior for small $x$**: When production is low (e.g., $x=10$), the fixed cost dominates the average.
    $A(10) = 2 + \frac{1000}{10} = 2 + 100 = \$102$ per unit. The $1000 fixed cost is spread over very few units, making each one seem very expensive.

-   **Behavior for large $x$**: When production is high (e.g., $x=1000$), the fixed cost is "spread thin."
    $A(1000) = 2 + \frac{1000}{1000} = 2 + 1 = \$3$ per unit.

-   **Long-Run Behavior (Limit)**: As $x$ becomes extremely large ($x \to \infty$), the term $\frac{1000}{x}$ gets closer and closer to zero.
    $A(x) \to 2 + 0 = 2$.
    This means that for very high production volumes, the average cost per unit approaches the variable cost of $2. This is a key concept in economics and engineering called "economies of scale." The line $y = 2$ is a **horizontal asymptote** for the graph of A(x).

### Common confusions to avoid
-   **Confusing total cost with average cost**: Total cost $C(x)$ is a line that goes up forever. Average cost $A(x)$ is a curve that comes down and approaches a floor value.
-   **Assuming average cost can be $2**: The average cost *approaches* $2 but never quite reaches it, because there is always a tiny fraction of the fixed cost included in each unit's average.

### Self-study suggestions (visualization tools)
-   Use Desmos or GeoGebra to graph the average cost function $y = 2 + \frac{1000}{x}$.
-   Set the viewing window for x from 0 to about 2000.
-   Plot the horizontal line $y = 2$. Observe how the average cost curve gets closer and closer to this line as $x$ increases, but never touches it.
-   Also, observe the behavior as $x$ approaches 0 from the right. The curve shoots up towards infinity, which represents the **vertical asymptote** at $x=0$. This visually shows how ridiculously high the average cost would be for an extremely small number of units.

***

## Case 8: The Profitable Window

### Key concepts covered
- Quadratic inequalities
- Solving for roots with the quadratic formula
- Sign diagrams to determine intervals

### Scenario
A company's monthly profit $P$ (in thousands of dollars) from producing and selling $x$ thousand units of a product is modeled by the function $P(x) = -0.1x^2 + 20x - 300$. The company wants to know the range of production levels that will result in a profit (i.e., where $P(x) > 0$). This range is the "profitable window."

### From scenario to model
We need to solve the quadratic inequality:
$$-0.1x^2 + 20x - 300 > 0$$
Since the leading coefficient (-0.1) is negative, the graph of this profit function is a parabola opening downwards. This means the profit will be positive *between* its two roots (the break-even points).

**Step 1: Find the critical values (the roots).**
We solve the corresponding equation $P(x) = 0$ using the quadratic formula, $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.
Here, $a = -0.1$, $b = 20$, $c = -300$.

$$x = \frac{-20 \pm \sqrt{20^2 - 4(-0.1)(-300)}}{2(-0.1)}$$
$$x = \frac{-20 \pm \sqrt{400 - 120}}{-0.2}$$
$$x = \frac{-20 \pm \sqrt{280}}{-0.2}$$

Now, we approximate $\sqrt{280}$. Since $16^2=256$ and $17^2=289$, $\sqrt{280}$ is slightly less than 17. Let's use $\sqrt{280} \approx 16.73$.

$$x_1 \approx \frac{-20 + 16.73}{-0.2} = \frac{-3.27}{-0.2} \approx 16.35$$
$$x_2 \approx \frac{-20 - 16.73}{-0.2} = \frac{-36.73}{-0.2} \approx 183.65$$

The two break-even points are at approximately 16,350 units and 183,650 units.

### Interpretation and Sign Diagram
The roots are approximately 16.35 and 183.65. These points divide the number line into three intervals:
1.  $x < 16.35$
2.  $16.35 < x < 183.65$
3.  $x > 183.65$

Since the parabola opens downwards, it will be above the x-axis (positive) only in the middle interval.

**Conclusion**: The company makes a profit when its production level $x$ is between 16.35 thousand units and 183.65 thousand units.
In interval notation, the profitable window is approximately $(16.35, 183.65)$. We use parentheses because the inequality is strict ($ > 0$); at the endpoints, the profit is exactly zero.

### Common confusions to avoid
-   **Stopping at the roots**: Finding the roots is only the first step. The final answer to an inequality problem is an interval or a set of intervals.
-   **Choosing the wrong interval**: For a downward-opening parabola, the positive region is *between* the roots. For an upward-opening one, it would be *outside* the roots. A quick sketch or sign test prevents this error.

### Self-study suggestions (visualization tools)
-   Graph the profit function $P(x) = -0.1x^2 + 20x - 300$ in Desmos or GeoGebra.
-   Visually identify the x-intercepts and confirm they match the roots we calculated.
-   Observe the region where the parabola is above the x-axis. Verify that this corresponds to the interval $(16.35, 183.65)$.
-   Create a sign diagram on paper. Pick test points in each of the three intervals (e.g., x=10, x=100, x=200), plug them into P(x), and check if the result is positive or negative. This confirms the graphical result.

***

## Case 9: Budgeting Time and Money

### Key concepts covered
- Systems of linear inequalities
- Graphing inequalities in two variables
- Feasible region

### Scenario
A project manager is allocating resources for a sprint. There are two main activities: Research (R) and Development (D). The team has the following constraints:
1.  **Time Constraint**: The team has a total of 30 person-hours available.
2.  **Budget Constraint**: The total budget is $500. Research hours cost $10/hour, while Development hours cost $25/hour.
3.  **Non-negativity**: The hours spent cannot be negative.

What are all the possible combinations of Research and Development hours that satisfy all these conditions simultaneously?

### From scenario to model
Let $R$ be the number of hours spent on Research and $D$ be the number of hours spent on Development. We translate each constraint into a linear inequality:

1.  **Time**: $R + D \le 30$
2.  **Budget**: $10R + 25D \le 500$
3.  **Non-negativity**: $R \ge 0$ and $D \ge 0$

This set of four inequalities forms a **system of linear inequalities**. The solution is not a single point but a whole region of points $(R, D)$ that are valid plans. This solution set is called the **feasible region**.

### Graphing and Interpretation
We graph this system on a 2D plane with $R$ as the horizontal axis and $D$ as the vertical axis.
-   The non-negativity constraints ($R \ge 0, D \ge 0$) restrict our solution to the first quadrant.
-   For $R + D \le 30$, we first draw the line $R + D = 30$. The intercepts are at $(30, 0)$ and $(0, 30)$. We shade the region below this line.
-   For $10R + 25D \le 500$, we first draw the line $10R + 25D = 500$. The intercepts are at $(50, 0)$ and $(0, 20)$. We shade the region below this line.

The **feasible region** is the overlapping shaded area in the first quadrant—a four-sided polygon (a quadrilateral). Any point $(R, D)$ within this polygon represents a valid allocation of time and money.

The vertices (corner points) of this region are particularly important. They are:
-   $(0, 0)$ - Do nothing.
-   $(30, 0)$ - Only do Research, using all the time. Budget used: $10 \times 30 = \$300$.
-   $(0, 20)$ - Only do Development, using all the budget. Time used: 20 hours.
-   The intersection of $R+D=30$ and $10R+25D=500$. Solving this system gives $(R, D) \approx (16.67, 13.33)$.

Any plan inside this shape is feasible. For example, $(R=10, D=10)$ is a valid plan. Total time = 20 hrs ($\le 30$), total cost = $10(10)+25(10) = \$350$ ($\le 500$).

### Common confusions to avoid
-   **Shading the wrong side of the line**: A simple way to check is to use a test point like $(0,0)$. For $R+D \le 30$, $0+0 \le 30$ is true, so you shade the side that includes the origin.
-   **Forgetting non-negativity**: Real-world quantities like time and money are almost always non-negative, which is a crucial but sometimes overlooked constraint.

### Self-study suggestions (visualization tools)
-   Use GeoGebra's inequality plotting feature. Enter each of the four inequalities. The software will automatically shade the correct half-planes.
-   Use the `Intersect` tool to find the coordinates of the vertices of the feasible region polygon.
-   **Extension**: Introduce an objective function to optimize, such as "Maximize Impact $I = 2R + 3D$." You can then evaluate this function at each vertex to find the optimal plan. Plotting the line $2R+3D=k$ and moving it with a slider `k` will visually show how the optimal point is always a vertex.

***

## Case 10: The QR Code Universe

### Key concepts covered
- Exponential growth (Exponents)
- Orders of magnitude and large numbers
- Using logarithms for estimation and solving

### Scenario
A standard QR code is made of a grid of black and white squares (pixels). Let's consider a simplified model: a $21 \times 21$ grid. Each pixel in this grid can be in one of two states: black or white. How many unique QR codes can be created with this grid? And if a supercomputer could generate and check one billion ($10^9$) unique codes per second, how long would it take to exhaust all possibilities?

### From scenario to model
**1. Counting the possibilities:**
-   The grid size is $21 \times 21$ pixels. Total number of pixels = 441.
-   Each pixel has 2 independent choices (black or white).
-   The total number of unique combinations is found by multiplying the number of choices for each pixel:
    $$\text{Total Codes} = 2 \times 2 \times \dots \times 2 \quad (441 \text{ times})$$
    $$\text{Total Codes} = 2^{441}$$

**2. Calculating the time:**
-   Rate of generation = $10^9$ codes/second.
-   Total time = (Total Codes) / (Rate of generation)
    $$\text{Time (in seconds)} = \frac{2^{441}}{10^9}$$

### Solving with Logarithms
The number $2^{441}$ is far too large for any standard calculator to display. We must use logarithms to understand its magnitude. We will use the common logarithm (base 10).

**Step 1: Find the order of magnitude of $2^{441}$.**
$$\log_{10}(2^{441}) = 441 \times \log_{10}(2)$$
Using the approximation $\log_{10}(2) \approx 0.30103$:
$$\log_{10}(2^{441}) \approx 441 \times 0.30103 \approx 132.75$$
This means:
$$2^{441} \approx 10^{132.75} = 10^{0.75} \times 10^{132} \approx 5.6 \times 10^{132}$$
So, there are roughly $5.6 \times 10^{132}$ possible unique codes.

**Step 2: Calculate the time.**
$$\text{Time} \approx \frac{5.6 \times 10^{132}}{10^9} = 5.6 \times 10^{123} \text{ seconds}$$

### Interpretation
The number $5.6 \times 10^{123}$ seconds is astronomically large. Let's put it in perspective by converting it to years.
-   There are about $3.15 \times 10^7$ seconds in a year.
-   Age of the universe is about $13.8 \times 10^9$ years, which is roughly $4.35 \times 10^{17}$ seconds.

Our required time of $5.6 \times 10^{123}$ seconds is unimaginably longer than the current age of the universe. It is, for all practical purposes, infinite. This demonstrates the power of **exponential growth**. Even with a simple binary choice, the number of possibilities grows so rapidly with the number of components (pixels) that it quickly becomes unmanageable to brute-force.

### Common confusions to avoid
-   **Adding instead of multiplying**: Thinking the total is $2 \times 441$ instead of $2^{441}$ is a fundamental error in counting combinations.
-   **Underestimating the scale**: Without logarithms, it's impossible to grasp the true size of $2^{441}$. It highlights why logarithms are essential for dealing with problems involving exponential relationships.

### Self-study suggestions
-   Use a calculator to explore how quickly $2^n$ grows. Calculate it for n=10, 20, 30, 40, 50, 60. You'll see it quickly exceeds billions and trillions.
-   If a password uses an alphabet of 62 characters (A-Z, a-z, 0-9), how many characters long must it be to have more combinations than our 21x21 QR code? (Solve $62^L > 2^{441}$ by taking the log of both sides: $L \times \log(62) > 441 \times \log(2)$).

