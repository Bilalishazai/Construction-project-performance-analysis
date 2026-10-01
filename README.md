Construction Project Cost and Schedule Analysis

**About the Project**

This project is about analyzing the cost and schedule of a construction project using Python.
In construction, it is important to know whether a project is staying within its budget and following the planned schedule. In this project, I used basic data analysis methods to compare planned work with actual project performance.
The project helped me explore how Python can be used to understand construction project performance and support project management.

**Project Objectives**

The main objectives of this project are:

To analyze the cost performance of a construction project.

To compare planned work with actual progress.

To calculate Cost Variance (CV) and Schedule Variance (SV).

To create charts to make the results easier to understand.

To explore the use of Python in construction project management.

## Data

The dataset contains monthly values (sample data, not from a real project).
Columns: Month, PV (Planned Value), EV (Earned Value), AC (Actual Cost).

**Tools and Libraries**

I used the following tools and libraries:

Python for calculations and data analysis.

Jupyter Notebook to write and run the code.

Pandas to organize and work with the data.

NumPy for numerical calculations.

Matplotlib to create charts and visualize the results.

**Performance Indicators**

Two main indicators were used to analyze project performance.
1. Cost Variance (CV)
Cost Variance shows the difference between the value of completed work and the actual cost.
Formula:
CV = EV - AC
2. Schedule Variance (SV)
1. Cost Variance (CV) = EV - AC
   - Positive: under budget
   - Negative: over budget

2. Schedule Variance (SV) = EV - PV
   - Positive: ahead of schedule
   - Negative: behind schedule
   - Note: SV is expressed in currency (value of work), not in time.

3. Cost Performance Index (CPI) = EV / AC
   - Greater than 1: cost-efficient. Less than 1: cost-inefficient.

4. Schedule Performance Index (SPI) = EV / PV
   - Greater than 1: ahead of plan. Less than 1: behind plan.

Where EV = Earned Value, AC = Actual Cost, PV = Planned Value.



**How I Worked on the Project**

I started by organizing the project data in Python. Then, I used Pandas and NumPy to perform the calculations and analyze cost and schedule performance.
After that, I created charts with Matplotlib to make the results easier to understand. Finally, I reviewed the calculated values and used them to identify possible cost and schedule problems.

**Results**

After analyzing the construction project data, I obtained the following results:

Total Planned Cost: 88,000

Total Actual Cost: 89,500

Total Cost Variance: -1,500

Total Planned Duration: 45 days

Total Actual Duration: 46 days

Total Schedule Variance: -1 day

Analysis

The results show that the actual project cost was 1,500 higher than the planned cost. This means that the project went over its planned budget.
The project also took 46 days to complete, compared with the planned duration of 45 days. This indicates a delay of one day compared with the original schedule.
Overall, the analysis shows how Python can help identify cost differences and schedule delays in construction projects. These results can help project managers monitor project performance and identify areas that need attention.



**How to Run the Project**

Download or clone this repository.
pip install pandas numpy matplotlib jupyter
Open the project in Jupyter Notebook.

Open the Construction Management.ipynb file.

Run the cells in order.

Make sure Python and the required libraries are installed before running the notebook.

**What I Learned**

Through this project, I practiced using Python for data analysis and visualization. I also explored how cost and schedule indicators can be used to monitor construction projects.
This project helped me connect my background in civil engineering and construction management with my growing interest in programming and data analysis.

**Future Improvements**

In the future, I would like to improve this project by using real construction project data, adding more performance indicators, and developing a simple dashboard to present the results.



Python | Pandas | NumPy | Matplotlib | Jupyter Notebook
Author: Bilalluddin
Field: Civil Engineering and Construction Project Management
