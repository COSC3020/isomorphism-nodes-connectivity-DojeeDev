# Isomorphism

Prove that if two graphs $A$ and $B$ have the same number of nodes and are
completely connected, they must be isomorphic. I have started with the formal
definition of isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.

If a graph G is completely connected that is to say $\forall u, v \in V, (u,v) \in E$ For them to be isomorphic we need to find a bijection function that maps V of A to V of B so that they will have matching edges. 

Since every node has the same edges, if we count the edge that loops to itself, we can map the V of A to any V in B, as long as we map each node to a different node in B. This would satisfy the definition of isomorphism for any two fully connected graphs with the same number of nodes. 




I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice.

