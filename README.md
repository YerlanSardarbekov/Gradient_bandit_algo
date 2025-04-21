# Gradient_bandit_algo
Here I impelemented the generalized gradient bandit algorithm when Ψ(x) = ReLU(x) and update rule was changed to $H_{t+1}(a) = H_t(a) + α (R_t - \bar{R}_t)\frac{Ψ'(H_t(a))}{Ψ(H_t(a))}([A_t = a] - π_t(a))$
