# Heston-Stochastic-Volatility-Model
A python function that prices vanilla calls/puts via the heston stochastic volatility model. The parameters of this model are then calibrated based on the implied volatility of TSLA options data. 
Where the best choice of Heston model parameters are chosen such that the squared error of the Black/Scholes implied volatilities from the Heston model prices is minimised. 

Note that the relevant inputs defining the stochastic dynamics of the underlying asset under the risk-neutral measure are (in the notation used in the slides) the initial asset price  𝑆(0), the initial level of (squared) volatility  𝑣(0) , the "volatility of volatility parameter"  𝜂, the continuously compounded interest rate  𝑟(which we assume to be constant), the speed of mean reversion (of volatility)  𝑘, the long-run mean volatility  𝜃, and the instantaneous correlation  𝜌 between the driving Wiener processes  𝑍1 and 𝑍2.
