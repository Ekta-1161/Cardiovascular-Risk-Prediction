## Cardiovascular-Risk-Prediction
📖Introduction

A small clinic in Framingham, Massachusetts has seen a decided spike in cases of cardiovascular disease in their patients. Rather than sit back and wait for illness to strike, the lead cardiologist has decided to be proactive. They’ve reached out to us to review their clinical data and develop a model to predict their patient’s risk of developing cardiovascular disease in the next 10 years. The physician has two goals in mind: help identify those at risk and start acting before things get worse, and determine which patients are statistically more likely to develop problems and provide them with educational material before things become a problem. The model developed from their patient dataset will be used to do exactly that. A statistical model will be used to develop a patient education program, targeted at specific potential risk patients, and to help bring awareness surrounding cardiovascular disease before it becomes a problem. A machine learning model will also be used to target identified “at risk” patients and help them combat more severe cardiovascular disease by targeting treatment and making recommended life-style changes for those patients who are identified as being at risk.


📖Problem Statements

Cardiovascular Heart Disease (CHD) is the leading cause of death annually worldwide. Cardiovascular Diseases can, however, be managed if caught early and simple lifestyle changes are made. This project would explore a set of data for patients measuring known factors for heart disease to develop a machine learning model to predict risk of developing heart disease within the next ten years.

📖 Dataset information:
* Sex: male or female("M" or "F")
* Age: Age of the patient;(Continuous - Although the recorded ages have been truncated to whole numbers, the concept of age is continuous) Behavioral
* is_smoking: whether or not the patient is a current smoker ("YES" or "NO")
* Cigs Per Day: the number of cigarettes that the person smoked on average in one day.(can be considered continuous as one can have any number of cigarettes, even half a cigarette.) Medical( history)
* BP Meds: whether or not the patient was on blood pressure medication (Nominal)
* Prevalent Stroke: whether or not the patient had previously had a stroke (Nominal)
* Prevalent Hyp: whether or not the patient was hypertensive (Nominal)
* Diabetes: whether or not the patient had diabetes (Nominal) Medical(current)
* Tot Chol: total cholesterol level (Continuous)
* Sys BP: systolic blood pressure (Continuous)
* Dia BP: diastolic blood pressure (Continuous)
* BMI: Body Mass Index (Continuous)
* Heart Rate: heart rate (Continuous - In medical research, variables such as heart rate though in fact discrete, yet are considered continuous because of large number of possible values.)
* Glucose: glucose level (Continuous) Predict variable (desired target)
* 10 year risk of coronary heart disease CHD(binary: “1”, means “Yes”, “0” means “No”)

The project has been broken into two sections, and the code for each section can be found at the following:

1. Data Wrangling, Storytelling, and Statistical Analysis Downloading data, extracting features, creating features, data clean up. Analyzing graphically and statistically the impact of each feature on the risk of developing CHD in the next 10 years. Analysing the statistical correlation between features of the dataset and the risk of developing CHD in the next 10 years.

2.In-Depth Analysis Application of machine learning techniques to predict Cardiovascular Risk.

📖Conclusion:

From the above exploratory data analysis this are the following conclusions that can be incurred:
* People over 45 of age are more exposed to cardiovascular disease.
* As Systolic pressure(sysBP) value increses more than 110 and Normal diastolic blood(diaBP) value increses more than 70, the the risk of cardiovascular disease increse.
* Man have higher risk of CHD than the Woman. Also the person who smokes, who was on blood pressure medication, who was hypertensive, who has diabetes, who has obesity or overweight, who has high cholesterol, and who has high glucose level have higher chance of getting cardiovascular disease.
* The variable such as totcol, age, Cigsperday, is_smoking, sysBP, diaBP, glucose is more affecting the target variable.
