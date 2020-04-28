# Survival Estimates of lymphoma patients
> Using Python to build some of the statistical models to analyze surivival estimates for a dataset of lymphoma patients. This is Survival estimates that vary with time.

Lymphoma is cancer that begins in infection-fighting cells of the immune system, called lymphocytes. These cells are in the lymph nodes, spleen, thymus, bone marrow, and other parts of the body. When you have lymphoma, lymphocytes change and grow out of control.

In this project I use lifelines which is an open-source library for data analysis.

Can import KaplanMeierFitter from lifelines which is used for fitting the Kaplan-Meier estimate for the survival function.

I have used dataset from lifelines.datasets where it contains load_lymphoma

Column Time in dataset states how long the patient lived before they died or were censored.
The column Event says whether a death was observed or not. Event is 1 if the event is observed (i.e. the patient died) and 0 if data was censored.
