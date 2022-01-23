Sometimes it's easier to write functions as a transformation of functions for easier calculation. For example, in the following question, it's easier to find the subarrays with at most K distinct g(x) elements than to find subarrays with exactly K distinct elements f(x).

![diagram](/inequality.drawio.png "function transformation technique")

Using this fact we can write the function f(x) as follows.

	f(x) = g(x) - g(x-1)


This technique can be applied in many of the problems to convert equality  
to a combination of inequalities.
