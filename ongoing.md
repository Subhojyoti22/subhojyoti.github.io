---
layout: page
title: Ongoing Projects
---
    
1. *Latent Ranked Bandits*, Subhojyoti Mukherjee, Branislav Kveton, Anup Rao, Zheng Wen

   * ### Abstract ###
   
      <details>
        <summary>
          Show details
        </summary>
          <p> We study the problem of learning personalized ranked lists of diverse items for multiple users, from sequential observations of user preferences. The user-item preference matrix is non-negative and low-rank. Existing methods for solving similar problems are based on reconstructing the preference matrix from its noisy observations using matrix factorization techniques, and typically require strong assumptions on the reconstructed matrix. We depart from this standard approach and consider a family of low-rank matrices, where the set of most preferred items of all users is small and can be learned efficiently. Then we learn to present this set to each user in a personalized manner, in the order of the descending preferences of the user. We propose a computationally efficient algorithm that implements this procedure, and prove a sublinear bound on its n-step regret. We evaluate the algorithm empirically on several synthetic and real-world datasets. In all experiments, we outperform existing state-of-the-art algorithms. </p>
       </details>
    
    
       [Download Report](/pdf/paper.pdf)

2. *Structured Bandits*, Subhojyoti Mukherjee, Gauri Joshi, Samarth Gupta

 <details>
        <summary>
          Show details
        </summary>
          <p> We study a new variant of stochastic multi-armed bandit problem where the expected return of
one arm may depend on the returns of other arms. We propose a new Thompson Sampling algorithm 
for this general class of problems that can take help of this corrleations. We show that under certain circumstances it
is possible to achieve finite expected cumulative regret. 
    </p>
       </details>
    
 
      
