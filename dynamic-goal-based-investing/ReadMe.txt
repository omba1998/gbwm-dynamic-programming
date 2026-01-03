# goal-based-wealth-dp

This project implements a dynamic programming framework for
Goal-Based Wealth Management (GBWM), following the methodology
proposed by Das, Ostrov, Radhakrishnan, and Srivastav (2020).

The objective is to construct an optimal dynamic asset allocation
strategy that maximizes the probability of reaching a target wealth
level at a fixed investment horizon. The strategy depends jointly
on time and current wealth, and selects portfolios from a discrete
set along the efficient frontier.

Wealth is discretized on a fixed grid, and the optimal policy is
computed via backward dynamic programming using the Bellman
equation. Once the optimal policy is obtained, its performance is
evaluated both in-sample and out-of-sample through forward
simulation.

The project analyzes the impact of key numerical parameters,
including wealth-grid granularity and grid width, and illustrates
the resulting optimal strategies using policy heatmaps. Results
confirm the robustness of the GBWM approach and highlight the
trade-offs between numerical accuracy and computational cost.
