# Portfolio Optimization using Varitional Quantum Eigensolvers

## Introduction

In the stock market, every investor wants to maximize their profit while also reducing the risk. For this purpose, every investor wishes to optimize their portfolio using the latest optimization techniques. One of such techniques is by running Variational Quantum EigenSolver using Quantum Computers.  The goal of portfolio optimization is to minimize risks (financial loss) and maximize returns (financial gain). But this process is not as simple as it may seem. Gaining high returns with little risk is indeed too good to be true. Risks and returns usually have a trade-off relationship which makes optimizing your portfolio a little more complicated. Portfolio optimization can be mathematically formulated as a combinatorial optimization problem subject to certain constraints. There exist a few classical methods (e.g. Minimum Eigen solver) to solve this type of problem. But these methods usually have exponential time complexity and suffer from the computational bottleneck when the problem size is very large. Unfortunately, portfolio optimization problems in the real world usually involve a large number of assets (e.g. 1000 assets) and we have to select an optimal combination of a certain number of assets from them. It would take a very long time (e.g. a few weeks, a few months) to solve these problems, which is impractical in real-world business.


The goal of this project is to find the efficient frontier for an inherent risk using a quantum approach. We will use Qiskit's Finance application modules to convert our portfolio optimization problem into a quadratic program so we can then use variational quantum algorithms such as VQE  to solve our optimization problem. 

## Required Libraries
- Qiskit
- Matplotlib
- Qiskit Finance
- Numpy
- Pandas
