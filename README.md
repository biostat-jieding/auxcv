# *auxcv R package*: Auxiliary Information Transfer via Control Variates

It focuses on enhancing **Surv**ival analysis in target domains by transferring aggregate auxiliary information extracted from external source domains (using **C**ontrol **V**ariate). 
- allow for low and high dimensional covariates;
- based on the Cox proportional hazards model;
- key underlying technique is the control variate;
- extension to include a cured fraction
- *The most updated version can be found in:  https://github.com/biostat-jieding/SurvCV*.

## Package Description and Main Functions

Briefly speaking, this package can implement the following cases:
- **Low-dimensional** Cox proportional hazards model:
  - with **subgroup survival probabilities at multiple time points** as auxiliary information (SP-Low)
- **High-dimensional** Cox proportional hazards model:
  - with **subgroup group survival probabilities at multiple time points** as auxiliary information (SP-High)

Survival data analysis from various perspectives is also of interest: 
- **Estimation**: Estimation of relative risk - prognostic effects for interested risk factors
- **Inference**: Condcut statistical inference



We will add more details in the near future. Thank you for your attention!

## References and Typos

Here are some papers that can help you understand the underlying method:
- (1). Ding, J., Li, J., & Wang, X. (2024). **Efficient auxiliary information synthesis for cure rate model**. *Journal of the Royal Statistical Society Series C: Applied Statistics*, 73(2), 497-521.
- (2). Ding, J., Li, J., Zhang, M., & Wang, X. (2024). **CureAuxSP: An R package for estimating mixture cure models with auxiliary survival probabilities**. *Computer Methods and Programs in Biomedicine*, 251, 108212.
- (3). Ding, J., Li, J., Xie, P., & Wang, X. (2024+). **Efficient risk assessment of time-to-event targets with adaptive information transfer**. *Statistics in Medicine*, Accepted (In Press).

We remark here that in part of these papers, there are actually several typos. For readers' convenient, we list them here:
- In the simulation section of (1), ...

Sorry for these typos and we hope that these revisions can help you!

Note: *This R package was contributed together by **Jie Ding** (DUT), **Xiaoguang Wang** (DUT), **Jialiang Li (NUS)**, **Ping Xie** (DUT) and **Mengxiu Zhang** (DUT & SHZU).*
