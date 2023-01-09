---
title: Lecture 3
---

# Basic Theory of Interest
- Simple interest
- Compound interest: interest in one period is re-invested
- Continuous compounding: limit of compounding principle. Exponential function in limit

- Two different methods to evaluate investments:
    - Rate of return
    - Net present value (*NPV*)
- Important details:
    - Taxes and depreciation
    - Inflation
    - Both of these, if known ahead of time, can be counted in effective rate of return

# Well-Known Details
- Future estimated cash flows at time $n$ : $x_0 (1 + r)^{n} + x_1 (1 + r)^{n - 1} + \ldots + x_n$
- We need to know rate of return for this, and we have assumed it to be constant throughout
- Present value of stream: $x_0 + x_1 / (1 + r) + \ldots + x_n / (1 + r)^{n}$
- Internal rate of return (IRR) is an $r$ for which the above expression is equal to zero. Two projects with different cash flows may have different IRRs, and can be compared
- $r$ here is computed and doesn't depend on current or future interest rates
- Money in hand today is worth more than money possibly received tomorrow. Thus, the interest rate has to be positive
- Usual situation - $x_0$ is negative (initial investment), then stream of positive cash flows after 1 or more years. This gives a unique IRR which can be used as basis for comparison
- Most other realistic situations give single positive (and meaningful) solution to IRR equation 
- Appraisals using IRR can be different from those using NPV
- Repetitive investment - IRR probably OK to use as 'internal' measure

# Inflation
- Let inflation rate be $f$
- 'Real' rate of return: $1 + r_0 = (1 + r) / (1 + f) \implies r_0 = \frac{r - f} / {1 + f}$. This can be used for NPV and other calculations
- Financial regulatory systems: try to keep inflation rate small

# Fixed Income Securities
- Financial instruments that may/may not be tradeable, but which has a fixed return (precisely specified) to the investor
- Product - 1) face value 2) rate 3) promised duration
- Market for future cash
- Perpetual returns, fixed return term schemes at committed times
- Annuities

# Securities and Trading
- Most bonds can be traded and can vary in their price depending on when they are traded and the percevied value of the promised fixed return
- Thus, although they are fixed return instruments, they can also be treated as variable return instruments
- In most markets, there would be one risk-free asset.
- There are some assets which cannot be traded, and are hence less liquid. However, one can often borrow against them, and provided collateral and liquidity
- Assets which are traded have a price, and hence there is a continuous assessment of their value
