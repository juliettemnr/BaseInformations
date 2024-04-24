

conflict : one sensor strongly supports one target and the other strongly supports another target, and both targets are different (Liu, 2006 and Liu et al., 2011)

==conflict measure==

 **Shafer's weight of conflict
$$ Conf(m_i,m_j)=-Log_2(1-K) $$

**K**: conflict between mi and mj : global conflict of combination 
$$K=m_\oplus(ø)=\sum_{B\cap C = ø} m_{i(B)}* m_j(C)$$

**ma** : average BPA of all BOE except i : can be used as an estimation of the majority opinion

$$ m_a=\sum_{j=1,j≠i}^{n}m_j/n-1 $$
**conflict measure** : Conf(i)
$$ Conf(i)=Conf(m_i,m_a) $$

==Dissimilarity measure==
Jousselme et al. 2001

$$ Diss(i,j)=d_j(m_i,mj)=\sqrt{\frac{1}{2}(\vec{m_i}-\vec{m_{j})^T}D(\vec{m_i}-\vec{m_{j})}} $$
where D matrix 2^Θx2^Θ 

$$ d_{hl}= \left\{ \begin{array}{rl} 1 \hspace{1cm} if A_{h}=A_l=ø \\ \frac{|A_{h}\cap A_l|}{|A_{h}\cup A_{l}} \hspace{0.5cm} \forall A_{h,}A_{l}\in 2^{\Theta} \end{array} \right. $$

to compare A BOE with all other BOE 

$$ Diss(i)=\sum_{j=1, j≠i}^{n} Diss(i,j)/n-1 $$

==Disparity measure==
Tessem 1993

Distance between betting commitment (TBM distance) : DifBetP
=> based on the difference between two pignistic probabilities associated to two BOEs for judging whether the latter are disparate or not

$$ Disp(i,j)= DifBetP(i,j)=Max_{A \subseteq \Theta}(|BetP_i(A)-BetP_j(A)|) $$
$$ Disp(i)=\sum_{j=1, j≠i}^{n} Disp(i,j)/n-1 $$

