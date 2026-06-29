<img width="773" height="435" alt="image" src="https://github.com/user-attachments/assets/e4dcd83c-1b88-459f-8ae2-bb86bb0fdf20" />
# Project-Management-Data-Analysis

**Overview:**

The Project Management Data Analysis is an interactive Power BI dashboard designed to monitor project performance, task assignments, project progress, timelines, and resource utilization. It provides project managers and stakeholders with real-time insights into project execution through KPIs, charts, and slicers.

**Objectives:**

Monitor overall project progress.
Track assigned resources.
Analyze project workload.
Monitor project deadlines.
Identify completed and ongoing projects.
Improve project decision-making using interactive visualizations.

**Dataset:**

The dataset contains project administration information with the following columns:

Column	            Description
Project Name	      Name of the project
Task Name	          Individual task under the project
Assigned To	        Employee responsible for the task
Start Date	        Task start date
End Date	          Task completion deadline
Days Required	      Estimated duration
Progress	          Task completion percentage

**Dashboard KPIs:**

**Total Projects**:

Displays the total number of projects.

Total Projects =
DISTINCTCOUNT('Project Management Data Analysis'[Project Name])

**Assigned Projects:**

Displays the number of assigned project resources.

Assigned Projects =
DISTINCTCOUNT('Project Management Data Analysis'[Assigned to])

**Average Progress:**

Shows the average project completion percentage.

Average Progress =
AVERAGE('Project Management Data Analysis'[Progress])

**Total Days Required:**

Displays the total estimated project duration.

Total Days Required =
SUM('Project Management Data Analysis'[Days Required])

**Dashboard Visualizations:**

1️⃣ Count of Task Name by Assigned To

Visualization: Clustered Bar Chart

Purpose:

Shows workload distribution among employees.
Identifies heavily assigned team members.

2️⃣ Average Progress by Project Name

Visualization: Horizontal Bar Chart

Purpose:

Compare project completion percentages.
Identify projects requiring attention.

3️⃣ Count of Task Name by Assigned To

Visualization: Column Chart

Purpose:

Displays task count for each employee.

4️⃣ Count of Task Name by Progress

Visualization: Donut Chart

Purpose:

Shows distribution of project progress percentages.

5️⃣ Count of Task Name by Month

Visualization: Line Chart

Purpose:

Displays monthly task creation trends.

6️⃣ Sum of Days Required by Task Name

Visualization: Bar Chart

Purpose:

Shows which tasks require the highest effort.
7️⃣ Sum of Days Required by Project

Visualization: Bar Chart

Purpose:

Compare project durations.

**Interactive Filters:**

The dashboard includes slicers for:

Project Name
Assigned To
Month (Start Date & End Date)
Task Name

These slicers allow users to filter all visuals simultaneously.

**Features:**

Interactive KPI Cards

Dynamic Slicers

Cross Filtering

Drill Down Analysis

Responsive Dashboard

Clean UI Design

Employee Performance Tracking

Project Progress Monitoring

Timeline Analysis

Resource Allocation Insights

**Tools Used:**

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Microsoft Excel / CSV (Data Source)

**Author:**

Neha 
Aspiring Data Analyst| Power BI | Excel | SQL |
