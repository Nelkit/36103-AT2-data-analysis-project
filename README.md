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
