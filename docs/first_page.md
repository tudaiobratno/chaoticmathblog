#About the finite abelian groups

This page is dedicated to the results of my project on exploring propertirs of finite abelian groups.

Let's construct the set S, which will include at the i-th position the number of elements whose order is equal to i. For example, for symmetric group $S_3$ the S is determined as S = $[1, 3, 2]$. For the direct product $Z_2 \oplus Z_2$, it is $[1, 3]$.

It's known that some groups may have the same set S (see https://math.stackexchange.com/questions/729611/is-a-finite-group-uniquely-determined-by-the-orders-of-its-elements). However, if we are talking about finite abelian groups the following statement is true:

!!! note ""

    Each set S determine unique finite abelian group
    
How can we prove it? First, let's recall one of the Sylow theorems with the help of Wikipedia:


!!! note ""

    Let p be a prime factor with multiplicity n of the order of a finite group G, 
    so that the order of G can be written as $p^nm$, where $n > 0$ and p does not divide m. Let $n_p$
    be the number of Sylow p-subgroups of G. Then the following hold:

    - $n_p$ divides m, which is the index of the Sylow p-subgroup in G.
    - $n_p \equiv 1 \:(mod \: p)$
    - $n_p = |G:N_G(P)|$, where P is any Sylow p-subgroup of G and $N_G$ 
    
    
Actually, we will use the fact that for any $p||G|$, there exists at least one Sylow p-group, and the group G can be represented as a direct sum of its Sylow p-groups uniquely.
