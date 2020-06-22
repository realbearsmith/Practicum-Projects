### Step 1. Open the data file /datasets/credit_scoring_eng.csv and have a look at the general information. Download dataset.


### Step 2. Preprocess the data:

—Identify and fill in missing values.

—Replace the real number data type with the integer type.

—Delete duplicate data.

—Categorize the data.

**Explain:**

—which missing values you identified;

—possible reasons these missing values were present;

—which method you used to fill in missing values;

—which method you used to find and delete duplicate data and why;

—possible reasons why duplicate data was present;

—which method you used to change the data type and why;

—which dictionaries you've selected for this data set and why.

*The data may contain artifacts, or values that don't correspond to reality—for instance, a negative number of days employed. This kind of thing happens when you're working with real data. You need to describe the possible reasons such data may have turned up and process it.*


### Step 3. Answer these questions:

—Is there a connection between having kids and repaying a loan on time?

—Is there a connection between marital status and repaying a loan on time?

—Is there a connection between income level and repaying a loan on time?

—How do different loan purposes affect timely loan repayment?

*Interpret your answers. Explain what the results you obtained mean.


### Step 4. Write an overall conclusion.

*Format: Complete the project in the Jupyter Notebook (it opens when you click Next). Write code in the code cells and notes with explanations and interpretations in the markdown cells. Use formatting and headings.*

**Data description**

—children : the number of children in the family

—days_employed: how long the customer has worked

—dob_years: the customer’s age

—education: the customer’s education level

—education_id: identifier for the customer’s education

—family_status: the customer’s marital status

—family_status_id: identifier for the customer’s marital status

—gender: the customer’s gender

—income_type: the customer’s income type

—debt: whether the client has ever defaulted on a loan

—total_income: annual income

—purpose: reason for taking out a loan
