To prove that \( (n+1)^3 \) is \( O(n^3) \), we need to find constants \( c \) and \( n_0 \) 
such that for all \( n \geq n_0 \), the inequality \( (n+1)^3 \leq c \times n^3 \) is true.

Expand \( (n+1)^3 \):

\[ (n+1)^3 = n^3 + 3n^2 + 3n + 1 \]

We need to show there exists a constant \( c \) for which:

\[ n^3 + 3n^2 + 3n + 1 \leq c \times n^3 \]

Consider \( n \geq 1 \). Which inturn:

\[ 3n^2 \leq 3n^3, \]
\[ 3n \leq 3n^3, \]
\[ 1 \leq n^3, \]

because \( n^3 \) grows faster than \( n^2 \), \( n \), and 1.

Summing these inequalities we get:

\[ 3n^3 + 3n^3 + n^3 \geq 3n^2 + 3n + 1 \]

Timplifies to:

\[ 7n^3 \geq n^3 + 3n^2 + 3n + 1 \]

We can choose \( c = 7 \) and \( n_0 = 1 \) to satisfy the definition. Hence for all \( n \geq n_0 \):

\[ (n+1)^3 \leq 7n^3 \]

This shows that \( (n+1)^3 \) is \( O(n^3) \), completing the proof.
