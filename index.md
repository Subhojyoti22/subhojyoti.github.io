<header>
Things to Do
</header>

# About Me

I am an M.S (Research) scholar at the Computer Science and Engineering (CSE) Department in IIT Madras. I am advised by Dr. Balaraman Ravindran (CSE) and Dr. Nandan Sudarsanam (Department of Management Studies). I am interested in working in the broad area of Machine Learning and Reinforcement Learning. Currently I am working in the area of stochastic and non-stocahstic Multi Armed Bandit settings. 

# Publications
1. *"Thresholding Bandits with Augmented UCB"*, Subhojyoti Mukherjee, K. P. Naveen, Nandan Sudarsanam, Balaraman Ravindran, **Proceedings of the Twenty-Sixth International Joint Conference on Artificial Intelligence (IJCAI-17)**.
* ### Abstract ###
    In this paper we propose the Augmented-UCB (AugUCB) algorithm for a fixed-budget version of the thresholding bandit problem (TBP), where the objective is to identify a set of arms whose quality is above a threshold. A key feature of AugUCB is that it uses both mean and variance estimates to eliminate arms that have been sufficiently explored; to the best of our knowledge this is the first algorithm to employ such an approach for the considered TBP. Theoretically, we obtain an upper bound on the loss (probability of mis-classification) incurred by AugUCB. Although UCBEV in literature provides a better guarantee, it is important to emphasize that UCBEV has access to problem complexity (whose computation requires arms’ mean and variances), and hence is not realistic in practice; this is in contrast to AugUCB whose implementation does not require any such complexity inputs. We conduct extensive simulation experiments to validate the performance of AugUCB. Through our simulation work, we establish that AugUCB, owing to its utilization of variance estimates, performs signifi-cantly better than the state-of-the-art APT, CSAR and other non variance-based algorithms.
* ### Full Paper ###
    [**PDF**](http://static.ijcai.org/proceedings-2017/0350.pdf)


# Ongoing Work

1. *"Efficient UCBV: An Almost Optimal Algorithm using Variance Estimates"*, Subhojyoti Mukherjee, K.P. Naveen, Nandan Sudarsanam, and Balaraman Ravindran, under review in AAAI 2018.
* ### Abstract ###
  We propose a novel variant of the UCB algorithm (referred to as Efficient-UCB-Variance (EUCBV)) for minimizing cumulative regret in the stochastic multi-armed bandit (MAB) setting. EUCBV incorporates the arm elimination strategy proposed in UCB-Improved, while taking into account the variance estimates to compute the arms' confidence bounds, similar to UCBV. Through a theoretical analysis we establish the *gap-dependent* regret bound of EUCBV after T trials and this bound is an improvement over that of existing state-of-the-art UCB algorithms (such as UCB1, UCB-Improved, UCBV,  MOSS). Further, EUCBV incurs an order optimal *gap-independent* regret bound of which is an improvement over that of UCB1, UCBV and UCB-Improved, while being comparable with that of MOSS and OCUCB. Through an extensive numerical study we show that EUCBV significantly outperforms the popular UCB variants (like MOSS, OCUCB, etc.) as well as Thompson sampling and Bayes-UCB algorithms. 


2. *Aggregation of Experts*, Subhojyoti Mukherjee, Odalric-Ambrym Maillard (INRIA, Sequel Lab, Lille, France)
* ### Abstract ###
  We study a variant of multi-armed bandits where arms are non-stationary but predictable. The basic idea is to combine change-point detection algorithm with aggregation of expert strategies in order to define efficient pulling strategies in context of bandits with change of distributions. We focus on the guarantees of prediction error for each arm derived from theory, and on the problem of learning adaptively a representation of signal from a practical point of view. 

# Research Internship
1. Research internship under Dr. Odalric-Ambrym Maillard in the INRIA, Sequel Lab, Lille, France from 1st September, 2017 to 28th November, 2017 for a period of 3 months.

# Collaborators

1. Dr. Balaraman Ravindran, Computer Science and Engineering Department, IIT Madras
2. Dr. Nandan Sudarsanam, Department of Management Science, IIT Madras
3. Dr. K.P. Naveen, Deprtment of Electrical Engineering, IIT Tiruapti
4. Dr. Odalric-Ambrym Maillard, INRIA, SequeL Lab, Lille, France

# Resume

You can find my full resume here. [Resume](https://github.com/Subhojyoti/CV/blob/master/subho_cv.pdf)
