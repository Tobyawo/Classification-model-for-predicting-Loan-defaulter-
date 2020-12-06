  # <h1> Loan defaulter algorithm</h1>
 <p>This is a Data Science Nigeria AI 2019 pre-bootcamp competition to build an algorithm that can predict staff that are likely to be promoted based on defined personal and performance parameters</p>
 
 # <h2> Description </h2>
Kowope Mart is a Nigerian-based retail company with a vision to provide quality goods, education and automobile services to its customers at affordable price and reduce if not eradicate charges on card payments and increase customer satisfaction with credit rewards that can be used within the Mall. To achieve this, the company has partnered with DSBank on co-branded credit card with additional functionality such that customers can request for loan, pay for goods even with zero-balance and then pay back within an agreed period of time. This innovative strategy has increased sales for the company. However, there has been recent cases of credit defaults and Kowope Mart will like to have a system that profiles customers who are worthy of the card with minimum if not zero risk of defaulting.

You have been employed as a Data Scientist to leverage Machine learning to predict customers who are likely to default or not.

The dataset contains these variables as explained below:</p>
* EmployeeNo : System-generated unique staff ID

• Division: Operational department where each employee works

• Qualification: Highest qualification received by the staff

• Gender: Male or Female

• ChannelofRecruitment: How the staff was recruited – this is via internal process, use of an agent or special referral

• Trainings_Attended : Unique paid and unpaid trainings attended by each staff in the previous business cycle

• Yearofbirth: Year that the employee was born

• LastPerformanceScore Previous year overall performance HR score and rated on a scale of 0-14

• Yearofrecruitment : The year that each staff was recruited into the company

• Targets_met: A measure of employees who meet the annual set target. If met, the staff scores 1 but if not, it is a 0.

• Previous_Award : An indicator of previous award won. If yes, it is a 1 and if No it is a 0.

• Trainingscoreaverage: Feedback score on training attended based on evaluation

• StateOfOrigin: The state that the employee claims

• Foreign_schooled: An indicator of staff who had any of their post-secondary education outside the country. Responses are in Yes or No

• Marital_Status: Marriage status of employees and recorded as Yes or No

• PastDisciplinaryAction : An indicator if a staff has been summoned to a disciplinary panel in the past. This is indicated as Yes or No

• PreviousIntraDepartmentalMovement : This is an indicator to identify staff who have moved between departments in the past. Yes and No are the responses.

• Noofprevious_employers : A list of the number of companies that an employee worked with before joining the organisation. This is recorded as counts

# <h3> Evaluation </h3>
The error metric is Area Under the Curve

# <h3> dataset </h3>
dataset used for training and testing this model can be downloadeded on kaggle through this [link](https://www.kaggle.com/c/intercampusai2019/data) or using the kaggle api **kaggle competitions download -c intercampusai2019**
