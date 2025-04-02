# Assessment Task 2 - Data Analysis Project
# How to open this project with Google Colab

## 1. Open Colab Notebook from GitHub
To open a Jupyter Notebook from GitHub in Google Colab, follow these steps:

1. Navigate to the GitHub repository where the notebook is located.
2. Click on the **"Open in Colab"** button or manually open the notebook in Colab using the URL `https://colab.research.google.com/github/your-repo-path/your-notebook.ipynb`.
3. You can also use the **File** → **Open notebook** option in Colab and select the GitHub tab.

![Open Notebook](https://raw.githubusercontent.com/Nelkit/36103-AT2-data-analysis-project/master/images/open_notebook.gif)

## 2. Copy Dataset to the Notebook Folder in Google Colab
To use a dataset in your notebook, follow these steps:

1. Upload the dataset manually to Google Colab’s file system.
2. Store the dataset in the appropriate folder using the file explorer in Colab.
3. Use the following command in a code cell to ensure the dataset is in the correct location:
   ```python
   import os
   os.listdir("/content/your-dataset-folder")
   ```

![Add Data](https://raw.githubusercontent.com/Nelkit/36103-AT2-data-analysis-project/master/images/add_data_to_notebook.png)

## 3. Commit Changes to the Correct Branch in GitHub
Once you have made modifications, commit them to the appropriate branch that contains the group members’ names.

1. Click on the **Source Control** panel in Google Colab.
2. Select the correct branch where changes should be committed.
3. Add a commit message describing the changes.
4. Click **Commit and Push**.

![Commit Changes](https://raw.githubusercontent.com/Nelkit/36103-AT2-data-analysis-project/master/images/commit_changes.gif)

Now your modifications are successfully saved in the repository!


# To-Do List: Assessment Task 2 - Data Analysis Project

## 📅 Key Dates

- **AT2B - Presentation:** Saturday, May 3 (online)
- **AT2C - Report:** Sunday, May 11 (11:59 pm, PDF submission on Canvas)

## 📌 Tasks

### 📝 AT2B - Project Presentation (15%)

- [X]  **Define the research topic**
- [ ]  **Define research questions**
- [ ]  **Conduct data analysis**
    - [x]  Select appropriate datasets
    - [ ]  Data Loading and Overview
    - [ ]  Conduct a Exploratory Data Analysis
    - [ ]  Data Preprocessing
    - [ ]  Feature Engineering
    - [ ]  Apply statistical and modeling methods
    - [ ]  Generate visualizations that are easy to understand
- [ ]  **Prepare the presentation**
    - [ ]  Create clear and concise slides
    - [ ]  Focus on the audience (non-technical decision-makers)
    - [ ]  Include effective visualizations
    - [ ]  Ensure the message is clear and relevant
- [ ]  **Practice the team presentation**
    - [ ]  Adjust timing and flow
    - [ ]  Review clarity and coherence of the speech
- [ ]  **Upload the PPT file to canvas** 
- [ ]  **Deliver the online presentation**

### 📄 AT2C - Technical Project Report (15%)

- [ ]  **Structure the report**
    - [ ]  Executive summary (brief and clear explanation for non-technical readers)
    - [ ]  Introduction (context and relevance of the problem)
    - [ ]  Methodology (details on datasets and techniques used)
    - [ ]  Results (key findings)
    - [ ]  Conclusion (summary and possible applications)
- [ ]  **Include key elements**
    - [ ]  Use correct terminology and appropriate statistics
    - [ ]  Include at least one regression model
    - [ ]  Visualizations and tables with clear descriptions
    - [ ]  Cite external sources (datasets, literature, etc.)
    - [ ]  Appendix with well-documented code
- [ ]  **Final review before submission**
    - [ ]  Spell and grammar check
    - [ ]  Readable formatting (headings, appropriate fonts, clear structure)
    - [ ]  Convert to PDF and submit on Canvas

✅ **Goal:** Execute a full data science project, communicate findings to different audiences, and improve teamwork skills.
