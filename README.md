# Oefening

**Objective**: Engage in a collaborative data analysis project using Databricks notebooks, integrated with GitHub for version control and team collaboration.

**Project Case:
**Perform a simple data analysis task using a Python notebook in Databricks, such as analyzing a publicly available dataset and creating basic visualizations.

Preparation
Split into teams of 3-4. Assign roles:

**Release Manager**: 
Manages the GitHub repository, reviews, and merges pull requests.
Developer 1, 2, and 3: Each has specific tasks in the development of the notebook.
Ensure all team members have access to Databricks and understand the basics of using notebooks in Databricks.

**Create a GitHub repository**:

The Release Manager creates a new public repository on GitHub, named DataAnalysisProject.
Add a README.md file with a brief project description: "A collaborative data analysis project using Databricks and Python."
**Exercise Steps**

**1. Release Manager:**
Add all team members as collaborators to the GitHub repository.
In Databricks, link the workspace to the DataAnalysisProject repository (via Repos).
**2. All Developers:**

Accept the repository collaboration invitation.
Clone the DataAnalysisProject repository in their Databricks workspace.

**3. Developer 1 (Data Loading and Preparation):**
In Databricks, create a new branch named data-setup.
Create a new notebook in this branch named Data_Setup.
Write Python code to load a dataset (e.g., using Pandas to load a CSV file from a public URL).
Include basic data preparation steps (e.g., handling missing values, basic filtering).
Commit and push the notebook to the data-setup branch using Databricks' Git features.
On GitHub, open a pull request to merge data-setup into the main branch.

**4. Developer 2 (Data Analysis):**
Wait for the data-setup branch to be merged by the Release Manager.
Create a new branch from main, named data-analysis.
Create or continue the notebook, now named Data_Analysis.
Perform basic data analysis, such as computing summary statistics or generating simple plots.
Commit and push these changes to the data-analysis branch.
On GitHub, open a pull request to merge data-analysis into the main branch.
**5. Developer 3 (Documentation and Insights):**

Wait for the data-analysis branch to be merged by the Release Manager.
Create a new branch from main, named documentation.
Update the README.md file with detailed project insights and how to run the analysis.
Optionally, add additional comments or markdown cells in the Data_Analysis notebook to explain the analysis steps.
Commit and push these changes to the documentation branch.
On GitHub, open a pull request to merge documentation into the main branch.

**6. Release Manager:**
Sequentially review and merge pull requests: first data-setup, then data-analysis, and finally documentation.
Ensure the changes are correctly integrated and resolve any merge conflicts if they arise.

**Important Notes:**
Developers should regularly communicate and coordinate, especially if one task depends on the completion of another.
It’s important to wait for the necessary branches to be merged before proceeding with dependent tasks to avoid merge conflicts and ensure data consistency.


