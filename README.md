# SkillCraft Technology — Task 01

## Population Data Visualization

### 📌 Project Overview

This project was completed as **Task 01 of my Data Science Internship at SkillCraft Technology**.

The objective of this task was to create a **bar chart or histogram to visualize the distribution of a variable** using a real-world dataset.

For this task, I used the **World Bank Population, total** dataset to analyze population distribution across countries and created a bar chart showing the **10 most populated countries in 2025**.

### 📊 Dataset

**Source:** World Bank — Population, total

**Indicator:** `SP.POP.TOTL`

The dataset contains population information for countries and regions across multiple years.

The analysis uses the **2025 population data**.

### 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* PyCountry
* VS Code
* Git & GitHub

### 🔍 Data Processing

The following steps were performed:

1. Loaded the World Bank CSV dataset using Pandas.
2. Inspected the dataset structure and available years.
3. Selected the population data for 2025.
4. Removed missing population values.
5. Filtered the dataset to include actual countries rather than World Bank regional or income-group aggregates.
6. Sorted countries by population in descending order.
7. Selected the top 10 most populated countries.
8. Converted population values into millions for better visualization.
9. Created a bar chart using Matplotlib.
10. Added population values above each bar.
11. Saved the final visualization as a high-resolution PNG image.

### 📈 Visualization

The final visualization presents the top 10 most populated countries in 2025.

The countries included are:

1. India
2. China
3. United States
4. Indonesia
5. Pakistan
6. Nigeria
7. Brazil
8. Bangladesh
9. Russian Federation
10. Ethiopia

### 💡 Key Observations

* India has the highest population among the countries analyzed.
* China has the second-highest population and is relatively close to India.
* The United States ranks third but has a substantially smaller population than India and China.
* Indonesia, Pakistan, Nigeria, Brazil, Bangladesh, Russia, and Ethiopia make up the remaining countries in the top 10.
* The visualization clearly shows the significant population difference between the two most populated countries and the rest of the top 10.

### 📁 Project Structure

```text
SCT_DS_Task01/
│
├── Task_1_dataset/
│   ├── API_SP.POP.TOTL_DS2_en_csv_v2_33112.csv
│   ├── Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_33112.csv
│   └── Metadata_Indicator_API_SP.POP.TOTL_DS2_en_csv_v2_33112.csv
│
├── task1_population.py
├── top_10_population_2025.png
├── README.md
└── .gitignore
```

### ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/Likhi-tha1505/SCT_DS_Task01.git
```

Navigate to the project directory:

```bash
cd SCT_DS_Task01
```

Install the required libraries:

```bash
python -m pip install pandas matplotlib pycountry
```

Run the Python program:

```bash
python task1_population.py
```

The program generates:

```text
top_10_population_2025.png
```

### 📷 Output

The generated bar chart visualizes the population of the top 10 most populated countries in 2025, with population values represented in millions.

### 🎓 Learning Outcomes

Through this task, I gained practical experience in:

* Working with real-world datasets
* Data loading and exploration using Pandas
* Data cleaning and filtering
* Handling country and regional data
* Sorting and selecting relevant records
* Data visualization using Matplotlib
* Creating meaningful insights from data
* Using Git and GitHub for project version control

### 👩‍💻 Internship

**Internship:** Data Science Internship
**Organization:** SkillCraft Technology
**Task:** Task 01 - Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable, such as the distribution of ages or genders in a population.

---

### 📚 Data Source

World Bank - Population, total (`SP.POP.TOTL`)

https://data.worldbank.org/indicator/SP.POP.TOTL
