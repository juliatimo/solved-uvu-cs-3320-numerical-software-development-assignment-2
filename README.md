Download Link: https://assignmentchef.com/product/solved-uvu-cs-3320-numerical-software-development-assignment-2
<br>
SECTION 1.1Exercise 5) Consider the equation x <sup>4 </sup>= x <sup>3 </sup>+ 10.

a) Find an interval [a, b] of length one inside which the equation has a solution

b) Starting with [a, b], how many steps of the Bisection Method are required to calculate the solutionwithin 10 <sup>-10</sup>? Answer with an integer.

Computer Problem 2) Use the Bisection Method to find the root to eight correct decimal places.● MATLAB Code for Bisection Method (code from textbook):

function xc = bisect(f, a, b, tol)if sign(f(a)) * sign(f(b)) &gt;= 0error(‘f(a)f(b) &lt; 0 not satisfied!’) % Ceases executionend

a) x<sup> 5</sup> + x = 1

b) sin(x) = 6x + 5

c) ln(x) + x <sup>2</sup> = 3

SECTION 1.2Exercise 1) Find all fixed points of the following g(x).a) x/3

b) x <sup>2 </sup>– 2x + 2

c) x <sup>2</sup> – 4x + 2

Exercise 7) Use Theorem 1.6 to determine whether Fixed-Point Iteration of g(x) is locally convergent tothe given fixed point r.Theorem 1.6 : Assume that g is continuously differentiable, that g(r) = r, and that s = | g’(r) | &lt; 1.Then Fixed-Point Iteration converges linearly with rate S to the fixed point r for initial guesssufficiently close to r .a)g(x) = (2x – 1) <sup>1/3</sup>, r = 1

b) g(x) =x<sup>3</sup> +1 /2 , r=1

c) g(x) = sin(x) + x, r = 0

Computer Problem 1) Apply Fixed-Point Iteration to find the solution of each equation to eight correctdecimal places.

a) x <sup>3</sup> = 2x + 2

b) e <sup>x </sup>+ x = 7

c) e <sup>x</sup> + sin(x) = 4