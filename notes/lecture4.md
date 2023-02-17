# 14.13 Lecture 4 Time Preferences (Theory) (2)
###### tags: `14.13`

[toc]

## 0. Recap: exponential discounting vs. empirical evidence
* Three **key features** of exponential discounting model
    * 1. Constant discount rate
    * 2. Time consistency
    * 3. No demand for commitment
* **Emperical evidence** show
    * 1. Short run impatience and long-run patience
    * 2. Preference reversals
    * 3. Demand for commitment 


## 1. Quasi-hyperbolic discounting (Laibson, 1997)
### A) Model
* Exponential Discounting: at time $t$, the person maximizes
    $$ u_t + \delta u_{t+1} + \delta^2 u_{t+2} + \delta^3 u_{t+3} + \dots$$ where $0 < \delta \leq 1$ is short-/long-term discount factor.
    
* **Quasi-Hyperbolic Discounting**: at time $t$, the person maximizes  $$ u_t + \beta\delta u_{t+1} + \beta\delta^2 u_{t+2} +\beta \delta^3 u_{t+3} + \dots$$ where $0 < \beta\leq 1$ is the **short-term discount factor**, $0 < \delta \leq 1$ is the **long-term discount factor**.
    * Typically assume $\beta < 1$ and $\delta \approx 1$.
    * Relative to current, all future periods are worth less (factor of $\beta$).
    * Most (all in this case) discounting is between the present and the future.
    * Little discounting between future periods.

![](https://i.imgur.com/n4F5gxa.png)

### B) Leisure goods: immediate rewards, delayed costs
**Example 1a: eating candy (quasi-hyperbolic discounting)**
* Immediate utility benefits $B_{pleasure} = 2$
* Delayed health costs $C_{health} = 3$
* Let $\beta = 1/2, \delta=1$
* Eating today? Yes.
    * $B_{pleasure} - \beta \delta \cdot C_{health} = 2 - \frac{1}{2} \cdot 3 > 0$
* Eating next week? No.
    * $\beta \delta \cdot (B_{pleasure} - \delta C_{health}) = \frac{1}{2} \cdot (2-3) < 0$
* <u>Over-consume leisure goods relative to long-run plans.</u>

**Example 1b: eating candy (exponential discounting)**
* Let $\beta = 1, \delta=1$, all else keep the same. (note it's the same result if long-term discounter term $\delta$ is 1/2 instead.)
* Eating today? No.
    * $B_{pleasure} - \beta \delta \cdot C_{health} = 2 - 3 > 0$
* Eating next week? No.
    * $\beta \delta \cdot (B_{pleasure} - \delta C_{health}) = 2-3 < 0$
* <u>An exponential discounter always follows through on her plans!</u>

### C) Investment goods: immediate costs, delayed benefits
* The examples are analogous to (B); refer to slides for details.
* <u>An quasi-hyperbolic discounter under-consume investment goods relative to long-run plans.</u>
* An exponential discounter <u>always</u> follows through on her plans!

### D) Investment good *with/without* commitment
> **Setup**
> * A student with $\beta = 1/2, \delta = 1$
> * Has to do problem set in exactly one of three periods, $t = 0, 1, 2$.
> * Instantaneous dis-utilities: $u_0 = −1, u_1 = −3/2$, and $u_2 = −5/2$.

**Case 1: Commitment avaliable**
* Suppose the student can commit at $t=0$ to doing the pset on any date (ie. she can decide when the pset is actually done.)
* From the perspective of period 0: if pset is done at $\dots$
    * $t=0$, the discounted disutility is $-1$.
    * $t=1$, the discounted disutility is $1/2 \cdot (-3/2) = -3/4$.
    * $t=2$, the discounted disutility is $1/2 \cdot (-5/2) = -5/4$.
* Hence, at $t=0$ she commits to doing the pset at $t=1$.

**Case 2: No commitment available**
* No commitment, would she do it in period 1?
* From the perspective of period 1: if pset is done at $\dots$
    * $t=1$, the discounted cost is $-3/2$.
    * $t=2$, the discounted disutility is $1/2 \cdot (-5/2) = -5/4$.
    * She now prefers to do it at $t=2$.
* <u>The student’s preferences are dynamically inconsistent!</u>

## 2. Sophistication vs naive
> Given this conflict, when does she actually do the problem set?
    > * Key question: is the student *aware* of her time inconsistency?
    > * Additional parameter $\tilde{\beta}$ measures beliefs about future $\beta$.

**Two extreme assumptions**
1. **Full naive**: $\tilde{\beta} = 1$
    * She doesn't realize she'll change mind.
    * She assumes future self will follow through her plan
    * Surprises about future present bias
    * False optimism about future patience.
2. **Sophistication**: $\tilde{\beta} = \beta$
    * She understands perfectly that she will change mind.
    * She does the best given future self's correctly anticipated behavior.
    * No surprises about future present bias.

### A) Investment good 
#### i) naive student's behavior
* Keep delaying for many periods, "naive procrastination".
* Naive procrastination can cause large welfrare costs.

#### ii) sophisticated student's behavior
* Recognizes if she delays, she'll delay more, so she reluctantly does the pset at $t=0$.
* Sophisticated procrastination (if occurs) does *not* cause large welfare costs.

### B) Leisure good
> Sophistication can hurt, see a concrete example on slides

* Sophisticated student's problem: her *realistic* pessimism about her future behavior.


### C) General lesson
*  If future misbehavior **raises the cost** of current misbehavior, then sophistication **helps** in overcoming short-run impatience.
    * This tends to be true for <u>investment goods</u> (with immediate costs).
* If future misbehavior **lowers the costs** of current misbehavior, sophistication **hurts** in overcoming short-run impatience.
    * This tends to be true for <u>leisure goods</u> (with immediate rewards).