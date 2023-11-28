Explain why (n+1)<sup>3</sup> is O(n<sup>3</sup>). Use the following
definition: f(n) is O(g(n)) if there exists positive constants c and
n<sub>0</sub> such that f(n) &le; c &times; g(n) for all n &ge; n<sub>0</sub>.

To prove that  n+1<sup>3</sup>  is  On<sup>3</sup> , we need to find constants  c  and  n<sub>0</sub>  
such that for all  n &ge; n<sub>0</sub> , the inequality  n+1<sup>3</sup> &le; c times n<sup>3</sup>  is true.

Expand n+1<sup>3</sup>:

 n+1<sup>3</sup> = n<sup>3</sup> + 3n<sup>2</sup> + 3n + 1 

We need to show there exists a constant  c  for which:

 n<sup>3</sup> + 3n<sup>2</sup> + 3n + 1 &le; c times n<sup>3</sup> 

Consider  n &ge; 1 . Which inturn:

 3n<sup>2</sup> &le; 3n<sup>3</sup>, 
 3n &le; 3n<sup>3</sup>, 
 1 &le; n<sup>3</sup>, 

because  n<sup>3</sup>  grows faster than  n<sup>2</sup> ,  n , and 1.

Summing these inequalities we get:

 3n<sup>3</sup> + 3n<sup>3</sup> + n<sup>3</sup> &ge; 3n<sup>2</sup> + 3n + 1 

Simplifies to:

 7n<sup>3</sup> &ge; n<sup>3</sup> + 3n<sup>2</sup> + 3n + 1 

We can choose  c = 7  and  n<sub>0</sub> = 1  to satisfy the definition. Hence for all  n &ge; n<sub>0</sub> :

 n+1<sup>3</sup> &le; 7n<sup>3</sup> 

This shows that  n+1<sup>3</sup>  is  On<sup>3</sup> , completing the proof.
