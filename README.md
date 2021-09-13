# A-scalar-field-in-p-adic-string-theory
A demonstration of how to solve an infinite order differential equation by numerically solving its non-linear integral form

p-adic string theory is a specific kind of string theory where the worldsheet coordinates are p-adic valued. The effective lagrangian of the scalar field that reproduces the tree level non-Archimedean string amplitudes is non-local because of the presence of an infinite series of derivatives. Therefore, the equation of motion of this scalar field also contains an infinite number of derivatives acting on the field. Finding a solution to this equation seems daunting, but it can be done quite easily by first transforming the differential equation into its non-linear integral form, and then using the fixed-point iteration method generalized for functions. One then converges to a kink solution within a few iterations!

References:

1) https://www.sciencedirect.com/science/article/abs/pii/0550321388902076
2) https://iopscience.iop.org/article/10.1088/1126-6708/2002/10/034
