We started from the market prices of the options and obtained the implied volatilities by inverting the Black–Scholes formula. Then, we implemented a Monte Carlo simulation to model the underlying asset prices at maturity, assuming a Geometric Brownian Motion (GBM) process.

Using these simulated prices, we computed several risk metrics and exposure profiles—namely Expected Exposure (EE), Expected Positive Exposure (EPE), Effective Expected Exposure (EEE), and Effective Expected Positive Exposure (EEPE). From these, we derived the Exposure at Default (EAD) and the Potential Future Exposure (PFE).

Finally, we used these results to calculate the Risk-Weighted Assets (RWA) both at the trade level and at the portfolio level, considering cases with and without netting. The portfolio analyzed included a mix of European and Asian call and put options.
