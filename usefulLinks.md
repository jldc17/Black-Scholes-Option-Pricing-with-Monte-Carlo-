# Links that provide access to models and answer questions we have had about Monte Carlo Options Pricing

## Models

* [Monte Carlo Blog Post 1](https://www.codearmo.com/blog/)
    * Great explanation for where they got the equation. Don't have to understand all of the math to understand all of the implementation
* [Monte Carlo Blog Post 2](https://towardsdatascience.com/monte-carlo-pricing-in-python-eafc29e3b6c9)
* [Monte Carlo Blog Post 3](https://python.plainenglish.io/monte-carlo-options-pricing-in-two-lines-of-python-cf3a39407010)
    * This has a quote about risk free rate in the US, which says it is interest rate on treasury bills
## Explanations to Key Concepts

* [Macroption.com](https://www.macroption.com/why-is-volatility-proportional-to-square-root-of-time/)
    * While I was trying to figure out the code, I kept wondering why we were dividing by the $\sqrt{T}$ or $\sqrt{dT}$. This explains why, because basically volatility is proportional to the square root of time, it's just a thing. I think you can read the math on it. 