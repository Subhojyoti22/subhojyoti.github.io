
# About Me

<p> I am a Ph.D. scholar in the College of Information and Computer Sciences, University of Massachusetts Amherst. I am advised by Dr. Hong Yu and Dr. Phillip Thomas. Currently, I am working in applying Reinforcement Learning techniques in medical applications. I am asscociated with the [**Autonomous Learning Laboratory**](http://www-anw.cs.umass.edu/) and the [**Bio-NLP**](https://bio-nlp.org/) group. 
   
   Prevously, I was an M.S (Research) scholar in the Computer Science and Engineering (CSE) Department in IIT Madras. I was advised by Dr. Balaraman Ravindran (CSE Department, IIT Madras) and Dr. Nandan Sudarsanam (Department of Management Studies, IIT Madras). I worked in the area of stochastic and non-stocahstic Multi-Armed Bandit settings. </p>

# Publications in peer-reviewed Conferences 

1. *"Efficient UCBV: An Almost Optimal Algorithm using Variance Estimates"*, Subhojyoti Mukherjee, K.P. Naveen, Nandan Sudarsanam, and Balaraman Ravindran, **Proceedings of the Thirty-Second Association for the Advancement of Artificial Intelligence (AAAI-18)**.

   * ### Abstract ###
   
   <p>We propose a novel variant of the UCB algorithm (referred to as Efficient-UCB-Variance (EUCBV)) for minimizing cumulative regret in the stochastic multi-armed bandit (MAB) setting. EUCBV incorporates the arm elimination strategy proposed in UCB-Improved while taking into account the variance estimates to compute the arms' confidence bounds, similar to UCBV. Through a theoretical analysis, we establish the *gap-dependent* regret bound of EUCBV after T trials and this bound is an improvement over that of existing state-of-the-art UCB algorithms (such as UCB1, UCB-Improved, UCBV,  MOSS). Further, EUCBV incurs an order optimal *gap-independent* regret bound of which is an improvement over that of UCB1, UCBV, and UCB-Improved, while being comparable with that of MOSS and OCUCB. Through an extensive numerical study, we show that EUCBV significantly outperforms the popular UCB variants (like MOSS, OCUCB, etc.) as well as Thompson sampling and Bayes-UCB algorithms.</p>
   
   * ### Full Paper ###
   
      [**PDF**](https://arxiv.org/pdf/1711.03591.pdf)

2. *"Thresholding Bandits with Augmented UCB"*, Subhojyoti Mukherjee, K. P. Naveen, Nandan Sudarsanam, Balaraman Ravindran, **Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence (IJCAI-17)**.
   
   * ### Abstract ###
   
   <p>In this paper we propose the Augmented-UCB (AugUCB) algorithm for a fixed-budget version of the thresholding bandit problem  (TBP), where the objective is to identify a set of arms whose quality is above a threshold. A key feature of AugUCB is that it uses both  mean and variance estimates to eliminate arms that have been sufficiently explored; to the best of our knowledge, this is the first algorithm to employ such an approach for the considered TBP. Theoretically, we obtain an upper bound on the loss (probability of misclassification) incurred by AugUCB. Although UCBEV in literature provides a better guarantee, it is important to emphasize that UCBEV has access to problem complexity (whose computation requires arms’ mean and variances), and hence is not realistic in practice; this is in contrast to AugUCB whose implementation does not require any such complexity inputs. We conduct extensive simulation experiments to validate the performance of AugUCB. Through our simulation work, we establish that AugUCB, owing to its utilization of variance estimates, performs significantly better than the state-of-the-art APT, CSAR and other nonvariance-based algorithms.</p>
   
   * ### Full Paper ###  
   
      [**PDF**](http://static.ijcai.org/proceedings-2017/0350.pdf)



# Ongoing Work

1. *Improved Changepoint Detection in Piecewise i.i.d Bandits*, Subhojyoti Mukherjee, Odalric-Ambrym Maillard (INRIA, Sequel Lab, Lille, France)

   * ### Abstract ###
   <p>We proposed two UCB algorithms, UCB-CPD and ImpCPD for the piecewise stochastic environment. Both these algorithms are adaptive and try to locate the changepoints and restart, thereby performing better than the passive algorithms. Theoretically, ImpCPD achieves an order optimal regret bound, thereby closing an important gap with respect to the lower bound. Empirically, ImpCPD outperforms most of the passive and adaptive algorithms except the oracle-based algorithms in all the considered environments.</p>

2. *Online Stochastic Low-Rank Latent Bandits*, Subhojyoti Mukherjee, Branislav Kveton, Anup Rao, Zheng Wen

   * ### Abstract ###
   <p> We study the problem of recommending the best items to users who are coming sequentially. The learner has access to very less prior information about the users and it has to adapt quickly to the user preferences and suggest the best item to each user. Furthermore, we consider the setting where users are grouped into clusters and within each cluster the users have the same choice of the best item, even though their quality of preference may be different for the best item. These clusters along with the choice of the best item for each user are unknown to the learner.  Also, we assume that each user has a single best item preference. This complex problem can be conceptualized as a low rank stochastic bandit problem where the goal of the learner is to minimize the cumulative regret by quickly identifying the best item for each user. </p>


# Research Internship

**1. Adobe Research, San Jose:** Research internship under Dr. Branislav Kveton and Dr. Anup Rao in Adobe Research, San Jose, USA from 22nd January, 2018 to 20th April, 2018 for a period of 3 months.

**2. INRIA, SequeL Lab:** Research internship under Dr. Odalric Maillard in the INRIA Sequel Lab, Lille, France from 1st September 2017 to 28th November 2017 for a period of 3 months.

# Collaborators

1. Dr. Balaraman Ravindran, Associate Professor, Computer Science and Engineering Department, IIT Madras
2. Dr. Nandan Sudarsanam, Assistant Professor, Department of Management Science, IIT Madras
3. Dr. K.P. Naveen, Assistant Professor, Deprtment of Electrical Engineering, IIT Tiruapti
4. Dr. Odalric-Ambrym Maillard, CR1, INRIA, SequeL Lab, Lille, France
5. Dr. Branislav Kveton, Machine Learning Scientist, Adobe Research, San Jose, USA
6. Dr. Anup Rao, Machine Learning Scientist, Adobe Research, San Jose, USA

# Resume

You can find my full resume here ([Resume](https://github.com/Subhojyoti/CV/blob/master/subho_cv.pdf)).

# Contact 

subho [at] cse[dot]iitm[dot]ac[dot]in

