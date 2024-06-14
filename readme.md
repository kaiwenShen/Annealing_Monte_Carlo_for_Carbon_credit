# MMF 1927H Workshop in Mathematical Finance
##### Author: Kaiwen Shen

Workshop Project about planting trees.
Suppose a company wants to plant trees to earn carbon credit in CA, where should they plant their trees and in what
amount?

This problem can be solved using a close to portfolio optimization fashion, except that in portfolio optimization, 
variance covariance matrix needs to be invertible, whereas unlike financial instrument, we can only objectively estimate
correlation. We run the risk of non-invertible. Here we use Annealer method to do a monte-carlo style optimization. 

This simple exercise can also be expanded to other hard-to-solve optimization problem, pros are it yields guaranteed 
answer within defined step, cons are due to stochastic nature, the result may not be extremely accurate like traditional 
optimization method, but good enough, with small tol. 