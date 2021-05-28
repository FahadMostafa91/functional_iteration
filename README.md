# functional_iteration
#MATLAB script to perform functional iteration to estimate the positive root to
within an absolute error τ = 10−10. We use the a posteriori bound to decide
when to stop. We use the following example
Consider the function g (x) ≡ x − 2 tan−1 (x).
This function has three roots: a trivial root at zero, and two others. Because of the odd symmetry of g, the two nonzero roots differ only by a sign;
call them ±x*We will consider functional iteration: x(n+1)= f (xn)
with f (x) ≡ 2 tan−1(x) as a method to solve the equation g (x) = 0.
