# IR_calibration

In this notebook, we will calibrate **Intreset Rate Models** using **QuantLib-Python**.
We will calibrate 3 intreset rate models :
- Hull-White 1 Factor Model
$$ dr_t = (\theta_t - a r_t) \, dt + \sigma \, dW_t $$

Where:
- $a$ \: is the mean reversion constant ;
- $\sigma$ \: is the volatility parameter ;
- $\theta_t$ \: is chosen to fit the input term structure of interest rates.
- Black Karasinski Model
- G2 ++ Model
