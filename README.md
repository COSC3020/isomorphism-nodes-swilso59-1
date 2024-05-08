[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/AtNXzL3S)
# Isomorphism

Prove that if two graphs $A$ and $B$ do not have the same number of nodes, they
cannot be isomorphic. I have started with the formal definition of isomorphism
below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

- If we had two graph with a different number of nodes. In order for them to be isomorphic there would need to exist a bijection.
- If we had two graphs with different nodes would would not be able to create a one-to-one mapping.
- Since we would not be able to create a one-to-one mapping it implies there would not be a way to create a bijective mapping.
- since a abijective mapping cannot be created. The two graphs with different numbers of nodes cannot be isomorphic.  

// I reviewed material from:
// isomorphism-nodes-howardthegr8one-1
// https://courses.grainger.illinois.edu/cs173/sp2024/ALL-lectures/Lectures/graphs1.html#:~:text=The%20two%20most%20obvious%20invariant,if%20those%20don't%20match.
