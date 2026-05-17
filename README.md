🚢 Titanic Survival Statistical Analysis
📌 Project Overview

This project performs a complete statistical analysis of the famous Titanic Survival dataset using Python. The project applies concepts such as:

🔁 Loops
🧠 Recursion
⚡ Functional Programming
📊 Statistical Analysis
🛠️ Feature Engineering
❗ Exception Handling
📂 File Handling

The main objective of this project is to analyze the factors that influenced passenger survival during the Titanic disaster.

📂 Dataset Information
📄 Dataset Name: Titanic Dataset
👥 Total Rows: 891
📑 Total Columns: 12
🌐 Source: Kaggle Titanic Dataset

The dataset contains passenger details such as:

🧍 Passenger Name
🎟️ Passenger Class
👨 Gender
🎂 Age
💰 Fare
👨‍👩‍👧 Family Information
🚢 Embarked Port
❤️ Survival Status
🛠️ Technologies Used
Technology	Purpose
🐍 Python	Core Programming
🐼 Pandas	Data Analysis
🔢 NumPy	Numerical Operations
🎲 Random Module	Random Sampling
🧠 Functional Programming	Advanced Operations
📄 File Handling	Report Generation
✨ Python Concepts Implemented
1️⃣ Exception Handling

Used try-except blocks for:

📂 File Reading
📝 File Writing
⚠️ Division by Zero Handling
2️⃣ Loops & Conditional Statements

Implemented:

🔁 for loops
✅ if-elif-else
🔗 Logical operators
⚖️ Relational operators

Used for:

Filtering passengers
Counting missing values
Survival analysis
3️⃣ Missing Value Handling

✔️ Missing Age values filled using manually calculated class-wise median.

✔️ Invalid or zero fares replaced using median fare.

4️⃣ Feature Engineering

Created new columns:

Feature	Description
👨‍👩‍👧 FamilySize	Total family members
💵 FarePerPerson	Fare divided by family size
👶 IsChild	Identifies children
🚩 WC_Flag	Women & Children flag
5️⃣ Statistical Analysis

Calculated:

📈 Mean
📉 Median
🔁 Mode
⬆️ Maximum
⬇️ Minimum

Using:

🧠 Manual calculations
🐼 Pandas methods
🔄 Recursive functions
6️⃣ Functional Programming

Implemented:

🧹 filter()
🗺️ map()
➕ reduce()

Used for fare analysis and transformations.

7️⃣ Random Sampling

🎲 Randomly selected:

✅ 50 Survivors
❌ 50 Non-Survivors

Compared:

🎂 Age
💰 Fare
👨‍👩‍👧 Family Size
🔄 Project Workflow
📥 Load Dataset
      ↓
🔍 Explore Data
      ↓
🧹 Handle Missing Values
      ↓
⚙️ Feature Engineering
      ↓
👩‍👧 Women & Children Analysis
      ↓
🎲 Random Sampling
      ↓
📊 Statistical Analysis
      ↓
🧠 Functional Programming
      ↓
📝 Generate Final Report
📄 Output Generated

The program automatically generates:

📝 titanic_analysis_report.txt

This report contains:

📌 Dataset Overview
🧹 Missing Value Analysis
⚙️ Feature Engineering
📊 Survival Analysis
📈 Statistical Summary
🧠 Functional Programming Results
✅ Final Conclusion
🔍 Key Findings

✅ Women and children had higher survival rates.

✅ First-class passengers had better survival chances.

✅ Higher fare passengers showed better survival probability.

✅ Passenger class strongly influenced survival outcomes.

▶️ How to Run the Project
📌 Step 1 — Install Libraries
pip install pandas numpy
📌 Step 2 — Add Dataset

Place titanic.csv inside the project folder.

📌 Step 3 — Run the Program
python titanic_analysis.py
📌 Step 4 — View Generated Report
titanic_analysis_report.txt
📸 Sample Features Generated
Passenger	FamilySize	FarePerPerson	IsChild
John	3	25.50	False
Anna	5	10.20	True
🎯 Learning Outcomes

Through this project, I learned:

📊 Statistical Analysis
🧹 Data Cleaning
⚙️ Feature Engineering
🧠 Functional Programming
🔄 Recursion
📂 File Handling
🐍 Advanced Python Programming
👩‍💻 Author
🌸 Manasa Konala

🎓 B.Tech – Computer Science Engineering
🏫 SRM University AP

✅ Conclusion

This project successfully demonstrates the practical implementation of:

📊 Data Analysis
🐍 Python Programming
📈 Statistical Computation
🧠 Functional Programming
⚙️ Feature Engineering
📂 File Handling

using the Titanic Survival dataset to analyze real-world survival patterns during the Titanic disaster.

⭐ Thank You

🚢 “Data tells the story of survival.”
