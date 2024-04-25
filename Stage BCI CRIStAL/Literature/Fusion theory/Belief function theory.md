Initially introduced by Dempster (1967), formalized by Shafer (1976) and justified by Smets and Kennest (1994)

==Definition== : general framework for modeling uncertainty and imprecision where the available information is imperfect (Frikha et Moalla, 2015)
information fusion => [[./Combination rules (BFT)|Combination rules (BFT)]]
decision making => decision rules

Another methods are described here : [[./Multiple Criteria Reliability|Multiple Criteria Reliability]]

Base

Belief function model : 
==frame of discernment==  = finite and exhaustive set Θ of the problem under consideration
==power se==t = all subsets of Θ, denoted by 2^Θ

==Basic Probability Assignment function== (BPA) : mapping m:2^Θ => [0,1] : to every subset A⊆Θ, it assigns m(A) : ==the mass== = degree of belief attributed exacted to A
two conditions : m(ø) = 0 (monde fermé), Σ{m(A)/A⊆Θ}=1

==focal element== of m : m(A)>0, set of focal element : ζ
==body of evidence ==: (ζ, m)

==belief function== : 2^Θ => [0,1] = total belief completely committed to A⊆Θ  

$$ Bel(A)=\sum_{B⊆A}m(B) \forall A \subseteq \Theta$$

==plausibility function== : 2^Θ => [0,1] = the maximum amount of belief that could be potentially given to A
$$ Pl(A)=\sum_{ B∩A ≠ ø}m(B) \forall A \subseteq \Theta$$
$$ Pl(A)=1-Bel(\bar A)$$
==total uncertainty== : m(Θ)=1 and m(A)=0 for all A≠Θ
vacuous belief function : Bel(Θ)=1 and Bel(A)=0 for all A≠Θ

==total certainty== : m({Θ1})=1 for one particular event and m(A)=0 for the rest


Website to implement it : https://bennycheung.github.io/dempster-shafer-theory-for-classification