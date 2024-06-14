# Identify Unmet Pharmaceutical Needs in Hypertension Treatment Across 128 Countries

Here is your text with corrected grammar and refined for clarity:

---

In this summer fellowship, our project aims to identify unmet pharmaceutical needs in hypertension treatment across different countries. There are two datasets: I am responsible for analyzing the NCDRisC hypertension survey dataset, while my teammate Jared Dunn is responsible for analyzing the IQVIA pharmaceutical retail data. My goal is to build a statistical model to predict the proportion of people diagnosed with hypertension but untreated, spanning 30 years, 10 age groups, and 2 sexes.

I proposed three models: 1) Beta regression with random effects (country/region/superregion), 2) Beta regression with shuffled random effects and 3) Beta regression model with only fixed effects.

To ensure the testing data includes data from each country, we randomly selected two rows from each country without replacement. The rest of the data serves as the training data. We trained the models using the training data and evaluated the performance of these three models on the testing data. As the beta regression model with random effects demonstrated the best performance, I applied a bagging method to create ten versions of this model and averaged the predicted values across these ten models to estimate the proportion of diagnosed but untreated hypertension cases.

I obtained three output datasets: `output_new_overall.csv`, `output_new_2019.csv`, and `output_new_2019_oecd.csv`. To explore the relationship between drug prices and unmet treatment needs, my teammate and I aggregated the results together and obtained new output data and visualizations: `hypertension_meds_combined_2019.csv`, `Fischer_vs_prob_diag_untreated.png`, `Laspeyres_vs_prob_diag_untreated.png`, and `Paasche_vs_prob_diag_untreated.png`.

Regarding the hypothesis of why countries with low pharmaceutical retail prices might still experience high proportions of untreated hypertension, our hypothesis is that geographic or financial barriers, or lack of health awareness, can limit access to pharmacies or healthcare facilities. Particularly in underdeveloped countries, these factors may result in low pharmaceutical retail prices but still high proportions of untreated hypertension.

---

This version corrects grammar and punctuation and ensures clarity and coherence throughout the text.
