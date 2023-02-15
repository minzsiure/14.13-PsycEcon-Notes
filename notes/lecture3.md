# 14.13 Lecture 3 Time Preferences (Theory) (1)
###### tags: `14.13`
[toc]
## 1. Exponential discounting
### A) Choices over time
* Most non-trivial economic choices involve tradeoffs between costs and benefits that occur at different points in *time*.
    * ie. going to college, deactivating social media account
* How do we make decisions?
    1. Determine value (utility) of costs and benefits;
    2. Weigh these costs and benefits against each other somehow.
* Key question: how should we weight costs and benefits?

### B) Fisher (1930) Diagram
![](https://i.imgur.com/usJ1Meb.png)

### C) Samuelson (1937) discounted utility model
* Mathematical version of Fisher’s view of intertemporal choice: just like any other tradeoff in economics. 
* At time $t$, maximize **discouted utility**: $$U_t \equiv \sum_{\tau =t}^{\infty} \delta^{\tau - t}u_{\tau} = u_t + \delta u_{t+1} + \delta^2 u_{t+2} + \dots$$
* **Instantaneous utilities**: $u_t, u_{t+1}, u_{t+2}, \dots$
    * capture how the person feels at a specific moment (in period $\tau$)
    * function of consumption, leisure, etc. in period $\tau: u_{\tau} \equiv u(c_{\tau}, l_{\tau}, \dots).$
* **Discount factor**: $\delta$ (usually $\leq 1$)
    * measures how utility in later periods is discounted relative to earlier periods.
    * Instantaneous utility in period $t$ $(u_t)$ is always worth $\delta$ times instantaneous utility in the previous period $(u_{t−1})$.
    * $\delta$ replaces complex psycology of how people think about the future for mathematical convenience.

### D) Terminology: Discount functions and discount rates
* $U_t = \sum_{\tau =0}^{\infty} D(\tau) u_{t+\tau}$
* Discount function $D(\tau)$
    * $u$ utility in $\tau$ periods are psychologically worth $D(\tau) \cdot u$ utility today.
    * $D(\tau)$ specifies weights on utility derived in $\tau$ periods.
* Discount rate $\rho(\tau)$
    * Rate of decline in the discount function $\rho(\tau) \equiv -\frac{dD(\tau)/d\tau}{D(\tau)}$
    * $\rho(\tau)$ specifies the rate at which value of future utils declines with delay.
* Key feature of <u>**exponential discounting**</u>: discount rates do not change with horizon.
    * Discount function $D(\tau) = \delta^{\tau}$
    * Discount factor $\delta$
    * Discount rate $\rho(\tau) \equiv -\frac{dD(\tau)/d\tau}{D(\tau)} = -\frac{d(\delta^{\tau}/d\tau)}{\delta^{\tau}} = -\frac{\delta^{\tau}log(\delta)}{\delta^{\tau}} = -log(\delta) \simeq 1-\delta$

> see examples in lecture slides.

### E) How to measure/estimate unknown $\delta$?
* Thaler (1981): (hypothetical) monetary choices
    * Choices between amounts at different points in time: What $X$ makes you indifferent between $ $Y$ ($15 in Thaler’s case) today and $ $X$ in $\dots$
    * ![](https://i.imgur.com/TDA9HeR.png)


## 2. Evidence against exponential discounting
### A) Short-run impatience vs. long run patience
* Empirical evidence: impatience for choices involving immediate consumption.
    * Key implication of exponential discounting: ****same**** impatience for any delay of same length.
* Real world, people are quite patient in the long run.
* Federick et al. (2002): estimated $\delta$ increases by time horizon, same exercise as Thaler (1981).
![](https://i.imgur.com/RfgnGwX.png)

### B) Prefrence reversals (dynamic inconsistency)
* Exponential discounting implies dynamic consistency:
    * **Dynamic consistency:** The action a person thinks she should take in the future always **coincides** with the action that she actually prefers to take once the time comes.
    * **Consistent preferences** at different points in time - no "intra-personal conflicts".
    * State-contingent **plans do not change** over time (though plans may changed if unforeseen information arrives or circumstances change).
    * Closely related to the assumption of exponential discounting that a decision-maker **counts each period $\delta$ times as much as the previous one**.
* Real world, there are plenty of examples of intra-personal conflicts.


### C) Demand for commitment
* People who foresee their preference reversals might try to alter their future choices.
* They might even be willing to pay to restrict their future choice set.