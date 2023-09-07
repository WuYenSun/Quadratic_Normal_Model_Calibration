# Quadratic_Normal_Model_Calibration

This research project delves into a closed-form approximation of the quadratic normal model, wherein the volatility is linked quadratically to the spatial dimension. 
In the context of the WTI market, the quadratic normal model offers two distinct advantages when compared to the conventional Black (1976) model. 
Firstly, it accommodates the possibility of negative WTI futures prices, a scenario that the conventional model fails to capture. 
Secondly, it acknowledges the non-constant nature of volatility in the WTI market.

It's worth noting that the associated partial differential equation (PDE) lacks a closed-form analytical solution, which poses challenges for calibration in practical applications. 
To overcome this hurdle, the technique of linearization proves valuable. 
This technique treats the space-dependent volatility as a perturbation to a constant benchmark, enabling the derivation of a closed-form approximation. 
Notably, the method of linearization extends its applicability to all space-dependent volatility in polynomial forms.

Our research validates the efficacy of this closed-form approximation in fitting WTI option data, as shown by the plots below.
A critical insight emerges from our findings: the choice of volatility expression holds a significant influence. 
This choice essentially defines the benchmark, thereby influencing the accuracy of the approximation.

![calibration_IBV](https://github.com/WuYenSun/Quadratic_Normal_Model/blob/main/calibration_IBV.png)
![calibration_price](https://github.com/WuYenSun/Quadratic_Normal_Model/blob/main/calibration_price.png)

The sensitivity analysis on benchmark implied volatility is presented below:
![sensitivity_sig_atm](https://github.com/WuYenSun/Quadratic_Normal_Model/blob/main/sensitivity_sig_atm.png)
![sensitivity_sig_atm_IBV](https://github.com/WuYenSun/Quadratic_Normal_Model/blob/main/sensitivity_sig_atm_IBV.png)
