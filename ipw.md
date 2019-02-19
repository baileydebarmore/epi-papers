# Inverse Probability Weights 

Resources for using IPW in your analyses 

[Link to original tweet](https://twitter.com/BaileyDeBarmore/status/1097247963318022144) 

### General

Muñoz, I., & Van der Laan, M. (2012). [Population Intervention Causal Effects Based on Stochastic Interventions](https://www.jstor.org/stable/23270456?seq=1#metadata_info_tab_contents)
 Biometrics, 68(2), 541-549. Retrieved from http://www.jstor.org/stable/23270456

+ Try this stochastic method before deciding to categorize a continuous exposure (binned or binary)



Toh S, Hernández-Díaz S, Logan R, Robins JM, Hernán MA. 
[Estimating absolute risks in the presence of nonadherence: an application to a follow-up study with baseline randomization.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3315056/)
Epidemiology. 2010;21(4):528-39.

+ Continuous exposure with large amount of zeros; uses 2-stage approach for modeling weights

### Binary Exposures
Cole and Hernan 2008 walks through using IPW for measured confounding and selection bias and the 4 assumptions of "consistency, exchangeability, positivity, and no misspecification of the model used to estimate weights"

Table 3 walks through how to construct the correct model specification for weighted model and compares the mean weight value (should be around 1.0)

Also walks through the multiple models to construct for marginal structural models with HIV/HAART example

Cole SR and Hernan MA. [Constructing inverse probability weights for marginal structural models](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2732954/pdf/kwn164.pdf) Am J Epidemiology 2008; 168(6):656-664.


### Continuous exposures 

Naimi AI, Moodie EEM, Auger N, and Kaufman JS. [Constructing inverse probability weights for continuous exposures: a comparison of methods](https://pdfs.semanticscholar.org/7aec/34adfc512120cf4d92671cd7d26e183f01f3.pdf)
Epidemiology 2014;25:292-299. 
+ R code from Ashley Naimi for continuous and multinomial exposures: [IPW_continuous_example](https://github.com/ainaimi/ipw_continuous_example/blob/master/ipw_continuous.R)


Kennedy EH, Ma Z, McHugh MD, and Small DS. 
[Non-parametric methods for doubly robust estimation of continuous treatment effects.](https://rss.onlinelibrary.wiley.com/doi/abs/10.1111/rssb.12212)
Journal of the Royal Statistical Society: Series B (Statistical Methodology). 2016, 79(4). 

+ package [npcausal](http://www.ehkennedy.com/code.html) from E Kennedy



## Causal Inference Notebook

R code for part 2 of [Causal Inference](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/) by Hernan and Robins.

[Chapter 12](https://causalinferencebookr.netlify.com/chapter-12.html#program-12.4)

Citation: Hernán MA, Robins JM (2019). Causal Inference. Boca Raton: Chapman & Hall/CRC, forthcoming.



---
Contact me at bailey[dot]debarmore[at]gmail[dot]com







