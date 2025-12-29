# Mean Reversion Properties — Half-Life of Spread Reversion

To quantify how quickly the Futures–Spot spread corrects back to equilibrium following a deviation, we estimate the half-life of mean reversion. The half-life represents the expected number of trading days required for a deviation in the spread to decay to half of its magnitude. In other words, it measures the strength and speed of the mean-reverting force in the spread process.

Methodology

Since the Engle–Granger test confirmed that the Futures and Spot series are cointegrated and the Augmented Dickey–Fuller (ADF) test confirmed the stationarity of the spread, it is appropriate to model the spread as a mean-reverting process. Following standard academic and industry convention, we approximate the spread dynamics using an AR(1) representation:

                                        St​=a+ϕSt−1​+ϵt​
where 𝑆𝑡 is the spread at time t, and 𝜙 represents the persistence of deviations.
The half-life of mean reversion is then computed as:
                                HL=−ln(ϕ)ln(2)​
If the spread is strongly mean-reverting, 
𝜙 will be significantly below 1, resulting in a shorter half-life. Conversely, values of 
𝜙 close to 1 imply weak mean reversion and a much slower convergence.

