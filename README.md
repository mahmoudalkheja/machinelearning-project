# machinelearningprojects
A company wants to assess the quality of their online advertisement campaign. Online users are the main interest in this campaign. The users see a web banner during their browsing activity. For each user, they want to be able to predict whether they subscribe to the advertised product through the advertisement banner, based on the information they have about them. To subscribe, the user has to click on the banner and then subscribe to the service.The target variable name is subscription.
Data fields
Unique identifier
Id: a unique identifier of the observations in each dataset. In the test set, it is used to match your predictions with the true values.
Target variable (only in the training data)
subscription: whether the user subscribed through the banner (1:yes, 0:no)
Demographic variables
age: (numeric)
job: type of job (categorical: teacher, industrial_worker, entrepreneur, housekeeper, manager, retired, freelance, salesman, student, technology, unemployed, na)
marital: marital status (categorical: married, divorced, single)
education: (categorical: high_school, university, grad_school, na)
Variables about the current campaign
device: from which device does the user see the banner? (categorical: smartphone, desktop, na)
day: last day of the month when the user saw the banner (numeric)
month: last month of the year when the user saw the banner (numeric)
time_spent: how long the user looked at the banner last time (in seconds) (numeric)
banner_views: number of times the user saw the banner (numeric)
Variables about an old campaign for the same product
banner_views_old: number of times the user saw the banner during an old (and related) online ads campaign (numeric)
days_elapsed_old: number of days since the user saw the banner of an old (and related) online ads campaign (numeric, -1 if the user never saw the banner)
outcome_old: outcome of the old (and related) online ads campaign (categorical: failure, other, success, na)
Variables with no name
X1: (categorical: 1, 0)
X2: (categorical: 1, 0)
X3: (categorical: 1, 0)
X4: (numeric)
