# BT4222 Project Recommendation System

Topic: Job and Course Recommendation System

Group 8

Welcome to our Job and Course Recommendation System project! This system leverages machine learning and NLP to match users with jobs and recommend courses based on their skills and preferences.

## Overview

This project is divided into two main segments: **Job Recommendation** and **Course Recommendation**. Each segment follows a series of steps to preprocess data, generate embeddings, and build machine learning models for personalized recommendations.

### Job Recommendation Pipeline

1. **Preprocessing User and Job Datasets**
   - **Notebook**: `1.1 Preprocessing_UserJob.ipynb`
   - **Aim**: Prepare and merge features for similarity analysis.

2. **Embedding Textual Data**
   - **Notebook**: `1.2 SBERT_EMBEDDINGS.ipynb`
   - **Aim**: Generate embeddings for textual data to enhance similarity measurements.

3. **Encoding IDs**
   - **Notebook**: `1.3 EncodeID.ipynb`
   - **Aim**: Assign unique IDs to users and jobs.

4. **Cosine Similarity Calculation**
   - **Notebook**: `1.4 SBERTcosine_similarity.ipynb`
   - **Aim**: Compute cosine similarity and generate labels.

5. **Feature Selection for Users**
   - **Notebook**: `1.5 feature_selection_user.ipynb`
   - **Aim**: Enhance user data with auxiliary information and generate embeddings.

6. **Feature Selection for Jobs**
   - **Notebook**: `1.6 feature_selection_job.ipynb`
   - **Aim**: Enhance job data with auxiliary information and generate embeddings.

7. **Choosing 1k Jobs for Evaluation**
   - **Notebook**: `1.7 1k-jobs-eval.ipynb`
   - **Aim**: Select 1k jobs for model evaluation.

8. **Building the Model**
   - **Notebook**: `ncf.ipynb`
   - **Aim**: Train the NCF model and predict job suitability.

### Course Recommendation Pipeline

1. **EDA for User’s Online Platform Usage**
   - **Notebook**: `2.1. EDA_User.ipynb`
   - **Aim**: Explore user dataset to understand learning platform preferences.

2. **Course Data Preprocessing**
   - **Notebook**: `2.2. preprocessCourseData.ipynb`
   - **Aim**: Clean course data and translate non-English titles.

3. **Recommending Courses for Users**
   - **Notebook**: `2.3 CourseRecommendation.ipynb`
   - **Aim**: Match users with courses by analyzing skills and requirements.

## Data Sources

- User Data: Located in `survey_results_public.csv`
- Job Data: Available in `job.csv`
- Course Data: Sourced from various platforms and consolidated for analysis.

## Getting Started

To run any part of this pipeline, follow these steps:

1. **Clone the Repository**:
    Clone this repository to your local machine to get started. Use the following command in your terminal:

    ```bash
    git clone https://github.com/yourusername/yourrepositoryname.git
    ```

    Replace `https://github.com/yourusername/yourrepositoryname.git` with the actual URL of your repository.

2. **Install Required Libraries**:
    Make sure you have all the required libraries installed. You can usually find a `requirements.txt` file in the repository or installation instructions in the notebooks.

    If there's a `requirements.txt`, install the dependencies using:

    ```bash
    pip install -r requirements.txt
    ```

3. **Navigate to the Project Directory**:
    Change your directory to the project folder:

    ```bash
    cd yourrepositoryname
    ```

4. **Run the Notebooks**:
    Open the notebooks using Jupyter Notebook or JupyterLab:

    ```bash
    jupyter notebook
    ```

    Navigate to the respective notebook file (`.ipynb`) you wish to run and follow the instructions within.

5. **Data Files**:
    Ensure you have the necessary data files placed in the specified directories as mentioned in the notebooks. The paths to input and output CSV files are crucial for the scripts to run correctly.


