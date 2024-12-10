# Isomorphism

Prove that if two graphs $A$ and $B$ are isomorphic they do *not* have to
be completely connected. I have started with the formal definition of
isomorphism below. Add your answer to this markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$G_1=(V_1 , E_1)$ is isomorphic to $G_2 = (V_2, E_2)$ if there exists a
one-to-one and onto function (bijection) $f: V_1 \rightarrow V_2$ such that $(u,v)
\in E_1$ iff $(f(u),f(v)) \in E_2$.


Isomorphism between two graphs implies that there's a one-to-one relationship between their nodes and edges. This means that every node and edge in the first graph can be mapped to a unique node and edge in the second graph and vice versa but a graph can be edgeless. Consider two separate graphs, G1 and G2, each with three vertices and no edges. In this case, isomorphism depends solely on the vertices. Since both graphs have no edges, their edge sets are empty and thus bijectively related. Therefore, if the vertices of the two graphs can be paired in a one-to-one manner the graphs are isomorphic. If G1 contains vertices A, B, and C. G2 contains vertices 1, 2, and 3 then the two graphs are isomorphic as long as there's a bijective mapping between their vertices like:

A matches with 1 

B matches with 2

C matches with 3

This senerio or any other with a bijective relationship G1 and G2 are isomorphic even tho they're not connected.

I used my previous repo
https://github.com/COSC3020/isomorphism-connectivity-Hrics12


I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."
