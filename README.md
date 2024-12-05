### Visa-Applicants-EasyVisa
I analyzed the data of Visa applicants and built a predictive model to streamline the visa approval process. Based on the key factors that significantly influence visa status, I recommended suitable profiles for applicants who should be certified or denied a visa.


#### Context:

Business communities in the United States are facing high demand for human resources, but one of the constant challenges is identifying and attracting the right talent, which is perhaps the most important element in remaining competitive. Companies in the United States look for hard-working, talented, and qualified individuals both locally as well as abroad.

The Immigration and Nationality Act (INA) of the US permits foreign workers to come to the United States to work on either a temporary or permanent basis. The act also protects US workers against adverse impacts on their wages or working conditions by ensuring US employers' compliance with statutory requirements when they hire foreign workers to fill workforce shortages. The immigration programs are administered by the Office of Foreign Labor Certification (OFLC).

OFLC processes job certification applications for employers seeking to bring foreign workers into the United States and grants certifications in those cases where employers can demonstrate that there are not sufficient US workers available to perform the work at wages that meet or exceed the wage paid for the occupation in the area of intended employment.

#### Objective:

In FY 2016, the OFLC processed 775,979 employer applications for 1,699,957 positions for temporary and permanent labor certifications. This was a nine percent increase in the overall number of processed applications from the previous year. The process of reviewing every case is becoming a tedious task as the number of applicants is increasing every year.

The increasing number of applicants every year calls for a Machine Learning based solution that can help in shortlisting the candidates having higher chances of VISA approval. OFLC has hired your firm EasyVisa for data-driven solutions. You as a data scientist have to analyze the data provided and, with the help of a classification model:

* Facilitate the process of visa approvals.
* Recommend a suitable profile for the applicants for whom the visa should be certified or denied based on the drivers that significantly influence the case status.


#### Data Description

The data contains the different attributes of the employee and the employer. The detailed data dictionary is given below.

* case_id: ID of each visa application
* continent: Information of continent the employee
* education_of_employee: Information of education of the employee
* has_job_experience: Does the employee has any job experience? Y= Yes; N = No
* requires_job_training: Does the employee require any job training? Y = Yes; N = No
* no_of_employees: Number of employees in the employer's company
* yr_of_estab: Year in which the employer's company was established
* region_of_employment: Information of foreign worker's intended region of employment in the US.
* prevailing_wage:  Average wage paid to similarly employed workers in a specific occupation in the area of intended employment. The purpose of the prevailing wage is to ensure that the foreign worker is not underpaid compared to other workers offering the same or similar service in the same area of employment.
* unit_of_wage: Unit of prevailing wage. Values include Hourly, Weekly, Monthly, and Yearly.
* full_time_position: Is the position of work full-time? Y = Full Time Position; N = Part Time Position
* case_status:  Flag indicating if the Visa was certified or denied



#### Skills & Tools Covered:
* EDA
* Data Preprocessin
* Customer Profiling
* Bagging Classifiers (Bagging and Random Forest)
* Boosting Classifier (AdaBoost, Gradient Boosting, XGBoost)
* Stacking Classifier
* Hyperparameter Tuning using GridSearchCV
* Business insights


##### Installing the libraries with the specified version.
!pip install numpy==1.25.2 pandas==1.5.3 scikit-learn==1.2.2 matplotlib==3.7.1 seaborn==0.13.1 xgboost==2.0.3



### Actionable Insights and Recommendations

#### Based on our analysis, several key insights have emerged regarding visa certification for applicants:
* Applicants with higher levels of education are more likely to have their visas certified.
* Candidates with job experience have a greater likelihood of visa certification.
*  Applicants who receive wage offers in hourly units are less likely to have their visa certified compared to those with annual, monthly, or weekly wage offers.
* Employees from Europe have the highest chances of visa certification, while those from South America have the lowest.
* The median wage of employees is approximately $70,000.
* About 67% of employees are from Asia.
* Approximately 66.8% of applicants have their visas certified.
* Employees with working regions in the South or Midwest have higher chances of obtaining visa.

#### Recommendations
* Companies should prioritize candidates with higher educational qualifications when sourcing international talent, as this is positively correlated with visa certification success.
* Organizations should look for candidates with relevant job experience, as this significantly improves the likelihood of visa certification.
* Companies should consider offering salaries in annual, monthly, or weekly formats rather than hourly, to enhance the chances of visa approval for their candidates.
* Given the higher certification rates among European applicants, companies might focus their recruitment efforts in this region to optimize visa certification outcomes.
* With a significant portion of the workforce from Asia, companies should continue to engage with this demographic, while ensuring their application processes are efficient.
*  Organizations hiring employees in the South or Midwest should be aware of the higher chances of visa certification in these regions and plan their recruitment strategies accordingly.
