
*Frikha et Moalla, 2015 : 

==Single criterion== to estimate reliability of sensors : 
- quality of information 
- non-specificity
- uncertainty
- conflict between sensors

Martin et al 2008 : 
estimation of BOE based on distance of evidence 

Liu et al 2011 : new dissimilarity measure to assess discounting factors 

Deng et al 2004 and Chen et al 2005 : similarity to determine weights 

=> not reliable : mono criteria is not enough to reflect reality 

==Multiple criteria== : 

**First class : imperfection of information provided by each sensor 

*Contradiction (strife)*
non-zero degrees of belief are allocated to disjoint subsets of a universal set 
=> element of interest cannot belong to only one or several disjoint subsets of the universal set 

$$ St(m)=-\sum_{A\in F}m(A)Log_{2}[\sum_{B\in F}m(B)(|A∩B|/|A|)] $$

- St(m)=0, if ζ contient m(A)=1 : no contradiction
- Max St(m)=Log2|Θ| : uniquely for uniformly distributed measure : BOE totally dissonant 
- Most conflicting BOE : distributing the masses of proba among the max number of disjoint subsets 

*Imprecision (non-specificity)*
degree of non-specificity 
the larger the subset is, the less specific the characterization is
$$ I(m)=\sum_{A\in F}m(A)* Log_2[|A|] $$
I(m)=0 if every singleton is a probability 
=> probability is the maximally precise statement 

*Uncertainty (ambiguity)*

$$ Au(m)= Max_{Bel}[-\sum_{\theta_{i}\in \Theta}p_{\theta_i}Log_{2}p_{\theta_i}] $$
Amount of uncertainty : P.4



**Second class : conflict between sensors BOE 

conflict : one sensor strongly supports one target and the other strongly supports another target, and both targets are different (Liu, 2006 and Liu et al., 2011)

*conflict measure*

 Shafer's weight of conflict
$$ Conf(m_i,m_j)=-Log_2(1-K) $$

K : conflict between mi and mj : global conflict of combination 
$$K=m_\oplus(ø)=\sum_{B\cap C = ø} m_{i(B)}* m_j(C)$$

ma : average BPA of all BOE except i : can be used as an estimation of the majority opinion

$$ m_a=\sum_{j=1,j≠i}^{n}m_j/n-1 $$
conflict measure : Conf(i)
$$ Conf(i)=Conf(m_i,m_a) $$

*Dissimilarity measure*








