# Quadratic_Normal_Model

This research project delves into a closed-form approximation of the quadratic normal model, wherein the volatility is linked quadratically to the spatial dimension. 
In the context of the WTI market, the quadratic normal model offers two distinct advantages when compared to the conventional Black (1976) model. 
Firstly, it accommodates the possibility of negative WTI futures prices, a scenario that the conventional model fails to capture. 
Secondly, it acknowledges the non-constant nature of volatility in the WTI market.

It's worth noting that the associated partial differential equation (PDE) lacks a closed-form analytical solution, which poses challenges for calibration in practical applications. 
To overcome this hurdle, the technique of linearization proves valuable. 
This technique treats the space-dependent volatility as a perturbation to a constant benchmark, enabling the derivation of a closed-form approximation. 
Notably, the method of linearization extends its applicability to all space-dependent volatility in polynomial forms.

Our research validates the efficacy of this closed-form approximation in fitting WTI option data. 
A critical insight emerges from our findings: the choice of volatility expression holds significant influence. 
This choice essentially defines the benchmark, thereby influencing the accuracy of the approximation.
