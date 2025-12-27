### Signature approach for pricing and hedging path-dependent options with frictions

This repository reproduces the results of  [Abi Jaber, Hainaud and Motte (2025)](https://www.arxiv.org/pdf/2511.23295).  

We implement:
- a full numerical resolution of the infinite-dimensional Riccati equation arising in signature-based hedging with temporary and permanent market impact, 
- sanity checks in settings admitting semi-explicit formulas, including quadratic European, Asian options (see `signature-payoffs.ipynb`),
- a numerical solver for the non-linear HJB equation of Almgren–Li–type market impact models, used as a benchmark for European options (see `non-signature-path-dependent-payoffs.ipynb`),
- a regression of non-signature payoffs against truncated time-augmented signatures to approximate the corresponding signature coefficients.

### Examples of illustrations 

![multiple_nu](assets/multiple_nu.png)

![R_T_asian](assets/R_T_asian.png)

![inventory_fractionless](assets/inventory_frictionless.png)

![inventory_hjb](assets/inventory_hjb.png)

### Disclaimer 
Source code is available upon request. Please contact me directly. 