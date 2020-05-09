# COVID19-Prediction
## Currently have several approaches to modeling
* Logistic Curve (Ill Posed, but some fits work)
* SIR/SIRD model with transitional variables (death, recovery, infection rates) modelled as high degree polynomial functions
 * Some fits work, but with unbounded functions come difficulties
* Third, using the same approach but with Chebyshev Interpolants instead of polynomial fits
  
## Currently working on...
* Prediction Range by setting transitional variables as the median of given experimental constants plus or minus the median absolute deviation of the given constants
 * Essentially, this prediction is going to be a shaded region
  
## Implications
* App for adjustable 'what if' markers to result in a prediction
* Potential PDE model for the virus spread..?
