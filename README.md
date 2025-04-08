# Hospital Power BI Dashboard

## Project Overview
This project involves developing an interactive Power BI dashboard for a hospital. The dashboard focuses on monitoring operational efficiency, patient metrics, doctor performance, and insurance analytics. It enables administrators to track KPIs, patient demographics and financial performance, facilitating data-driven decision-making.

### Model View - 
![Model_View](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Model%20View.png)

## Dashboard Features

### 1. Hospital Overview
- **KPI Cards**  
  Displays key metrics such as Total Revenue, Total Patients, Total Emergency Visits, Average Patient Stay Days, Average Doctor Rating, and Doctor-Patient Ratio.
- **Specialty Slicer**  
  Filters data by doctor specialty (e.g., Cardiology, Neurology).
- **Top 10 Diagnoses**  
  Table ranking diagnoses by the number of cases, including diagnosis name and total cases.
- **Patient Demographics**  
  - Clustered column chart for patients by age and gender.  
  - Line graph visualizing patient and revenue trends over time (Year, Month).
- **Top 10 Doctors**  
  Table ranking doctors by ratings with drill-through capability to the Doctor Details page.
- **Patients & Revenue Trends**  
  Line graph visualizing patient admissions and revenue trends over time (Year, Month).
- **Refresh Button**  
  Clears all filters on the page.

### 2. Doctor Details
- **Selected Doctor from Hospital Overview**  
  Displays detailed information such as Doctor Name, Specialty, Age, Rating, Experience, Total Revenue Generated, Total Emergency Visits handled, Total Patients diagnosed when selected.
- **Prescription Analytics**  
  - Pie chart showing prescription count by medicine type (Injections, Capsules, Tablets).  
  - Line & area charts analyzing medicines prescribed over time.  
  - Table listing top prescribed medicines.

### 3. Insurance Details
- **Financial Metrics**  
  Cards displaying Total Revenue, Insurance Coverage, Out-of-Pocket Payments, Average Insurance Covered and Insurance Coverage Percentage.
- **Insurance Breakdown**  
  - Donut chart showing the share of total revenue by insurance provider.  
  - Pie chart comparing Out-of-Pocket Payment vs. Insurance Coverage.  
  - Bar graph visualizing insurance coverage by provider.  
  - Table listing the Top 10 Hospital Bills with filters by Insurance Provider.

## Technologies Used
- **Power BI:**  
  Utilized for data visualization and interactive dashboard development.
- **Data Cleaning:**  
  Power Query is used to integrate and clean data from patient records, doctor logs and insurance claims.
- **Branding:**  
  Hospital-themed colors and logos are implemented to provide a professional interface.

## How to Use the Dashboard
- Clone the repository :  
  `git clone https://github.com/tejas407/HospitalDashboard.git`
- Open the Power BI file :  
  Use Power BI Desktop to open the file `(Hospital Dashboard.pbix)`
- Explore the Dashboard:  
  Navigate between pages using Menu Bar, filter data with slicers (Specialty, Year/Month), and use drill-through on doctor names for detailed insights.

## Screenshots 
#### Hospital Overview :
`1` KPI Cards, Top 10 Diagnoses
![KPI Cards, Top 10 Diagnoses](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Screenshots/KPI%20Cards%2C%20Top%2010%20Diagnoses.png)
`2` Filtered view with Specialty
![Filtered view with Specialty](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Screenshots/Filtered%20view%20with%20Specialty.png)

#### Doctor Details :
`1` Doctor Profile
![Doctor Profile](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Screenshots/Doctor%20Profile.png)
`2` Doctor Details with an applied filter for a specific medicine type
![Doctor Details with an applied filter for a specific medicine type](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Screenshots/Doctor%20Details%20with%20an%20applied%20filter%20for%20a%20specific%20medicine%20type.png)

#### Insurance Details :
`1` Insurance Coverage Breakdown and Top 10 Bills
![Insurance Coverage Breakdown and Top 10 Bills](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Screenshots/Insurance%20Coverage%20Breakdown%20and%20Top%2010%20Bills.png)
`2` Insurance Details filtered by selected Insurance Provider
![Insurance Details filtered by selected Insurance Provider](https://github.com/tejas407/HospitalDashboard/blob/88b896d17b2a8d596572e259c1b5e5acc2cee5f8/Images/Screenshots/Insurance%20Details%20filtered%20by%20selected%20Insurance%20Provider.png)

## Data Source  
**Note**: The dataset used in this dashboard is synthetically generated using Python's `Faker` library. While the data mimics real-world patterns and relationships, it is not sourced from actual hospital records. All metrics and visualizations are accurate to the generated dataset but may not reflect real-world scenarios.
