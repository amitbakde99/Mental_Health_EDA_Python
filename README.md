# Mental Health | EDA

This project explores a mental health dataset using Exploratory Data Analysis (EDA) techniques. The goal is to understand the factors that contribute to mental health issues, particularly depression and suicidal thoughts.

## Dataset

The dataset contains the following columns:

*   **id:** Unique identifier for each individual.
*   **Name:** Name of the individual.
*   **Gender:** Gender of the individual (e.g., Male, Female, Other).
*   **Age:** Age of the individual.
*   **City:** City of residence.
*   **Working Professional or Student:** Categorical variable indicating whether the individual is a working professional or a student.
*   **Profession:**  Specific profession of the individual (if applicable).
*   **Academic Pressure:** Level of academic pressure experienced.
*   **Work Pressure:** Level of work pressure experienced.
*   **CGPA:** Cumulative Grade Point Average (if applicable).
*   **Study Satisfaction:** Level of satisfaction with studies.
*   **Job Satisfaction:** Level of satisfaction with job (if applicable).
*   **Sleep Duration:** Average sleep duration.
*   **Dietary Habits:** Description of dietary habits.
*   **Degree:** Highest degree attained.
*   **Have you ever had suicidal thoughts ?:** Binary variable indicating whether the individual has ever had suicidal thoughts (Yes/No).
*   **Work/Study Hours:** Number of work/study hours per day.
*   **Financial Stress:** Level of financial stress experienced.
*   **Family History of Mental Illness:** Binary variable indicating whether there is a family history of mental illness (Yes/No).
*   **Depression:** Level of depression experienced.

## Project Goals

*   Identify key factors associated with depression and suicidal thoughts.
*   Explore the relationships between different variables (e.g., academic pressure, work pressure, sleep duration, financial stress, family history, etc.).
*   Visualize patterns and trends in the data.
*   Gain insights into the prevalence of mental health issues among different demographics.

## Technologies Used

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   Scikit-learn (potentially for further analysis)

## Project Structure
Mental Health | EDA/
├── data/              # Contains the dataset (e.g., mental_health_data.csv)
├── notebooks/         # Jupyter notebooks for EDA and analysis
│   └── mental_health_eda.ipynb
├── images/            # Images and visualizations generated during EDA
├── README.md          # This file
└── requirements.txt   # List of required Python packages

## How to Run

1.  Clone the repository: `git clone https://github.com/YOUR_USERNAME/Mental-Health-EDA.git` (Replace with your repository URL)
2.  Navigate to the project directory: `cd Mental-Health-EDA`
3.  Create a virtual environment (recommended): `python3 -m venv venv`
4.  Activate the virtual environment:
    *   Linux/macOS: `source venv/bin/activate`
    *   Windows: `venv\Scripts\activate`
5.  Install the required packages: `pip install -r requirements.txt`
6.  Open the Jupyter notebook: `jupyter notebook notebooks/mental_health_eda.ipynb`

## Contributing

Contributions are welcome! Please feel free to submit pull requests or open issues.
