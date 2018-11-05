---
layout: page
title: Ongoing Projects
---

1. *Improved Changepoint Detection in Piecewise i.i.d Bandits*, Subhojyoti Mukherjee, Odalric-Ambrym Maillard (INRIA, Sequel Lab, Lille, France)

   * ### Abstract ###
   
      <details>
        <summary>
          Show details
        </summary>
          <p> We consider the setup of stochastic multi-armed bandits in the case when reward distributions are piecewise i.i.d. with unknown changepoints. Out of generality, we assume the reward distributions to be bounded and thus do not restrict to specific parametric exponential families. Due to the regret minimization objective, we study the change of mean, in the context when not only the change times are unknown, but also the mean before and after any change. We focus on the case when changes happen simultaneously on all arms, and in stark contrast with the existing literature, we target gap-dependent (as opposed to only gap-independent) regret bounds involving the magnitude of changes and optimality-gaps. We introduce two simple adaptations of UCB-strategies that employ scan-statistics in order to actively detect the changepoints, without knowing in advance the number of changepoints G. We also derive gap-independent regret bounds. The first strategy UCB-CPD does not know the time horizon T and achieve a O(√(GT)log T) regret bound, while the second strategy ImpCPD makes use of the knowledge of T to remove the log T dependency thereby closing an important gap with respect to the lower bound. Empirically, ImpCPD outperforms most of the passive and adaptive algorithms except the oracle-based algorithms that have access to the exact changepoints in all the considered environments.</p>
      </details>
    
2. *Latent Ranked Bandits*, Subhojyoti Mukherjee, Branislav Kveton, Anup Rao, Zheng Wen

   * ### Abstract ###
   
      <details>
        <summary>
          Show details
        </summary>
          <p> We study the problem of learning personalized ranked lists of diverse items for multiple users, from sequential observations of user preferences. The user-item preference matrix is non-negative and low-rank. Existing methods for solving similar problems are based on reconstructing the preference matrix from its noisy observations using matrix factorization techniques, and typically require strong assumptions on the reconstructed matrix. We depart from this standard approach and consider a family of low-rank matrices, where the set of most preferred items of all users is small and can be learned efficiently. Then we learn to present this set to each user in a personalized manner, in the order of the descending preferences of the user. We propose a computationally efficient algorithm that implements this procedure, and prove a sublinear bound on its n-step regret. We evaluate the algorithm empirically on several synthetic and real-world datasets. In all experiments, we outperform existing state-of-the-art algorithms. </p>
       </details>
