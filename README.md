# Employee_Evaluation:
Employee perfomance evaluation using Power BI
PROJECT TITLE: EMPLOYEE PERFORMANCE DECISION SUPPORT SYSTEM
Project Statement : Employees are unaware of the decision-making process, leading to dissatisfaction and detachment.
The introduction of our Decision Support System (DSS) addresses the above issues and provides a standardized and objective performance evaluation process and relevant recommendations.
System Architecture : [ Data Sources ]
(Employee Data: Attendance, Tasks, Ratings, Productivity)
            ↓
[ Data Processing ]
(Cleaning, Transformation, Preparation)
            ↓
[ Decision Logic Layer ]
(Score Calculation + Decision Rules)
            ↓
[ DSS Application ]
(Power BI Dashboard)
            ↓
[ Decision Output ]
(Category + Recommendation)
Decision Logic
The decision model incorporates a score-based approach where various components have their assigned weight to determine the performance score.
Formula
Performance Score = (Attendance x 0.2) + (Task Completion x 0.3) + (Productivity x 0.3) + (Adjusted Supervisor Rating x 0.2)
Supervisor rating (1-10) is adjusted to 0-100, as with other measurements.
Decision Criteria
- Above 80: High Performer – Promote. Acknowledging the top talent and ensuring their retention.
- 60 to 80 (inclusive): Average Performer – Maintain. Employee meets the requirements; nothing more is required.
- Below 60: Needs Improvement – Requires Training. Demonstrates that the employee lacks certain skills.
All the above constitutes decision making and the transformation of unstructured data into structured information used for decision making, the primary objective of a Decision Support System.
Technologies used :
- Power BI
- Microsoft Excel
- CSV Dataset
- Data Visualization Techniques
Screenshot of Dashboard : <img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/094b91cf-b5f4-4f2d-b92a-1ae62f1c0f15" />
Team Members and Contributions:
Sylvia Mula IdNo 668830 - Searched for evaluation Dataset
- Data cleaning and preprocessing
- Created calculated columns (Productivity, Score)
- Built initial dashboard visuals
- Did the Github Repositories Deliverables
Immaculate Mutembei IdNo 669802 - Dashboard design and layout
- Styling and formatting
- Final report Documentation
- Power point presentation slides creation
