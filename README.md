# Objective
X Education aimed to improve conversion for the leads from website and other sources. For the same a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

# Steps Followed
- Reading Data
- Cleaning Data
  - Handling missing/null values
  - Outlier treatment
- EDA
  - Univariate Analysis
  - Bivariate Analysis
  - Multivariate Analysis
- Creating Dummy
- Splitting data into train and test set
- Feature Scaling
- Building Model and Refining
- Making Predictions
- Model Evaluation
- ROC Curve
- Prediction on test set
- Precision- Recall

# Data Dictionary
- Prospect ID: A unique ID with which the customer is identified.
- Lead Number: A lead number assigned to each lead procured.
- Lead Origin: The origin identifier with which the customer was identified to be a lead. Includes API, Landing Page Submission, etc.
- Lead Source: The source of the lead. Includes Google, Organic Search, Olark Chat, etc.
- Do Not Email: An indicator variable selected by the customer wherein they select whether of not they want to be emailed about the course or not.
- Do Not Call: An indicator variable selected by the customer wherein they select whether of not they want to be called about the course or not.
- Converted: The target variable. Indicates whether a lead has been successfully converted or not.
- TotalVisits: The total number of visits made by the customer on the website.
- Total Time Spent on Website: The total time spent by the customer on the website.
- Page Views Per Visit: Average number of pages on the website viewed during the visits.
- Last Activity: Last activity performed by the customer. Includes Email Opened, Olark Chat Conversation, etc.
- Country: The country of the customer.
- Specialization: The industry domain in which the customer worked before. Includes the level 'Select Specialization' which means the customer had not selected this option while filling the form.
- How did you hear about X Education: The source from which the customer heard about X Education.
- What is your current occupation: Indicates whether the customer is a student, umemployed or employed.
- What matters most to you in choosing this course: An option selected by the customer indicating what is their main motto behind doing this course.
- Search: Indicating whether the customer had seen the ad in any of the listed items.
- Magazine: Indicating whether the customer had seen the ad in any of the listed items.
- Newspaper Article: Indicating whether the customer had seen the ad in any of the listed items.
- X Education Forums: Indicating whether the customer had seen the ad in any of the listed items.
- Newspaper: Indicating whether the customer had seen the ad in any of the listed items.
- Digital Advertisement: Indicating whether the customer had seen the ad in any of the listed items.
- Through Recommendations: Indicates whether the customer came in through recommendations.
- Receive More Updates About Our Courses: Indicates whether the customer chose to receive more updates about the courses.
- Tags: Tags assigned to customers indicating the current status of the lead.
- Lead Quality: Indicates the quality of lead based on the data and intuition the the employee who has been assigned to the lead.
- Update me on Supply Chain Content: Indicates whether the customer wants updates on the Supply Chain Content.
- Get updates on DM Content: Indicates whether the customer wants updates on the DM Content.
- Lead Profile: A lead level assigned to each customer based on their profile.
- City: The city of the customer.
- Asymmetrique Activity Index: An index and score assigned to each customer based on their activity and their profile
- Asymmetrique Profile Index: An index and score assigned to each customer based on their activity and their profile
- Asymmetrique Activity Score: An index and score assigned to each customer based on their activity and their profile
- Asymmetrique Profile Score: An index and score assigned to each customer based on their activity and their profile
- I agree to pay the amount through cheque: Indicates whether the customer has agreed to pay the amount through cheque or not.
- a free copy of Mastering The Interview: Indicates whether the customer wants a free copy of 'Mastering the Interview' or not.
- Last Notable Activity: The last notable activity performed by the student.

# Files Summary
- README.md : Provides an overview of the Lead-Score-Case-Study repository
- lead_scoring.ipynb : Jupiter file containing the code for the Lead Scoring Case Study
- Assignment Subjective Questions.pdf : Provides answers to some subjective questions related to the Problem
- Summary.pdf : Provides a summary of the problem and its solution with a Logistic Regression model
- Lead_Scoring_Presentation.pdf: Giving a Presentation of the Problem, solution approach and Recommendations

