<h1 align="center">An Introduction to Model-based Machine Learning – Homework</a></h1>
<h5 align="center">Submitted as part of BMI 500 Coursework at Emory University</h5>
<h5 align="center">Submitted by Swati Rajwal</h5>
<h5 align="center">

# 🎯Introduction
- Name & Contact: Swati Rajwal (swati.rajwal@emory.edu)
- The question number you select to answer: 1
- Report submitted on Canvas ([PDF](https://github.com/swati-rajwal/BMI500_week11/blob/main/Rajwal_BMI500_HW11.pdf))

# 📈Key Insights
- The SIR and SEIR models effectively simulate pandemic dynamics and shows epidemic curves with initial peaks and subsequent declines in infection rates.
- The basic reproduction number ($R_0$), transmission ($\beta$) and recovery ($\gamma$) rates are critical in shaping infection curves.
- Lower $\beta$ values (one option: through social distancing) and higher $\gamma$ values (one option: through medical intervention) can significantly reduce both peak and total infections.
<p align="center">
  <img src="figures/6.png" width="500" alt="Experimental Task Design">
</p>
<p align="center"><b>Figure 1:  Peak infection over a year for each β and γ combination.</b></p>

# 👩‍💻Comparative Model Performance
- Compared to SIR, the SEIR model provides a more realistic simulation by incorporating an "Exposed" compartment, introducing a delay in infection spread. It also accounts for birth and death rates, allowing for long-term cyclical dynamics.
- During the sensitivity analysis, it was found that analysis of $\beta$ and $\gamma$ combinations highlights that lower transmission and higher recovery rates are optimal for minimizing infection spread and impact on healthcare systems.

# 📌Relevance to Model-based Machine Learning
- These epidemic models demonstrate the effectiveness of mathematical frameworks in simulating real-world disease dynamics, providing valuable insights for data-driven decision-making in public health.
- Sensitivity analyses offer a structured approach to assess the impact of varying parameters, aligning with model-based machine learning principles to enhance model robustness and applicability.

# 💭Suggestions for future modeling improvements
- **Incorporate Variability**: Introduce stochastic elements to capture random fluctuations in infection spread.
- **Advanced Compartments**: Consider additional compartments (e.g., vaccinated individuals) to simulate different intervention strategies.
- **Real-Time Data Integration**: Combine model-based approaches with real-world data for adaptive, real-time pandemic forecasting and intervention assessment.

# 📚References
1. R. Sameni, "Model-Based Prediction and Optimal Control of Pandemics by Non-Pharmaceutical Interventions," in IEEE Journal of Selected Topics in Signal Processing, vol. 16, no. 2, pp. 307-317, Feb. 2022, doi: 10.1109/JSTSP.2021.3129118.
2. Sameni, R. (2020). Mathematical Modeling of Epidemic Diseases; A Case Study of the COVID-19 Coronavirus. ArXiv. https://arxiv.org/abs/2003.11371
3. Sameni, R., & Alphanumerics Lab. EpidemicModeling [Computer software]. GitHub. https://github.com/alphanumericslab/EpidemicModeling
4. https://en.wikipedia.org/wiki/Basic_reproduction_number

# ⚠️Disclaimer
Perplexity.ai was used to complete HW #1.C to understand the concept of the basic reproductive number


