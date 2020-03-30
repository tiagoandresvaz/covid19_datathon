# covid_19
to analise covid19 hospitalization data

this is our code ...

Dataset description from: https://www.kaggle.com/einsteindata4u/covid19

Background
The World Health Organization (WHO) characterized the COVID-19, caused by the SARS-CoV-2, as a pandemic on March 11, while the exponential increase in the number of cases was risking to overwhelm health systems around the world with a demand for ICU beds far above the existing capacity, with regions of Italy being prominent examples.

Brazil recorded the first case of SARS-CoV-2 on February 26, and the virus transmission evolved from imported cases only, to local and finally community transmission very rapidly, with the federal government declaring nationwide community transmission on March 20.

Until March 27, the state of São Paulo had recorded 1,223 confirmed cases of COVID-19, with 68 related deaths, while the county of São Paulo, with a population of approximately 12 million people and where Hospital Israelita Albert Einstein is located, had 477 confirmed cases and 30 associated death, as of March 23. Both the state and the county of São Paulo decided to establish quarantine and social distancing measures, that will be enforced at least until early April, in an effort to slow the virus spread.

One of the motivations for this challenge is the fact that in the context of an overwhelmed health system with the possible limitation to perform tests for the detection of SARS-CoV-2, testing every case would be impractical and tests results could be delayed even if only a target subpopulation would be tested.

Dataset
This dataset contains anonymized data from patients seen at the Hospital Israelita Albert Einstein, at São Paulo, Brazil, and who had samples collected to perform the SARS-CoV-2 RT-PCR and additional laboratory tests during a visit to the hospital.

All data were anonymized following the best international practices and recommendations. All clinical data were standardized to have a mean of zero and a unit standard deviation.

Task Details
TASK 1
• Predict confirmed COVID-19 cases among suspected cases.
Based on the results of laboratory tests commonly collected for a suspected COVID-19 case during a visit to the emergency room, would it be possible to predict the test result for SARS-Cov-2 (positive/negative)?

TASK 2
• Predict admission to general ward, semi-intensive unit or intensive care unit among confirmed COVID-19 cases.
Based on the results of laboratory tests commonly collected among confirmed COVID-19 cases during a visit to the emergency room, would it be possible to predict which patients will need to be admitted to a general ward, semi-intensive unit or intensive care unit?

Expected Submission
Submit a notebook that implements the full lifecycle of data preparation, model creation and evaluation. Feel free to use this dataset plus any other data you have available. Since this is not a formal competition, you're not submitting a single submission file, but rather your whole approach to building a model.

Evaluation
This is not a formal competition, so we won't measure the results strictly against a given validation set using a strict metric. Rather, what we'd like to see is a well-defined process to build a model that can deliver decent results (evaluated by yourself).

Our team will be looking at:

Model Performance - How well does the model perform on the real data? Can it be generalized over time? Can it be applied to other scenarios? Was it overfit?
Data Preparation - How well was the data analysed prior to feeding it into the model? Are there any useful visualisations? Does the reader learn any new techniques through this submission? A great entry will be informative, thought provoking, and fresh all at the same time.
Documentation - Are your code, and notebook, and additional data sources well documented so a reader can understand what you did? Are your sources clearly cited? A high quality analysis should be concise and clear at each step so the rationale is easy to follow and the process is reproducible.
Questions and More Info
Additional questions and clarifications can be obtained at data4u@einstein.br
