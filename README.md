# ExtraaLearn Project

## Predicting Customers 

### Context

This project aims to analyze and predict which leads are more likely to convert into paid customers for ExtraaLearn, an EdTech startup. By leveraging machine learning models, we seek to identify key factors driving the lead conversion process and create profiles of leads most likely to convert.

The EdTech industry has seen significant growth, especially due to the rise in online education during the Covid-19 pandemic. With many new companies emerging and a large volume of leads being generated, it is crucial for ExtraaLearn to effectively allocate resources to maximize lead conversion. This project provides insights and predictive capabilities to help ExtraaLearn prioritize leads, thereby enhancing marketing strategies and improving business efficiency.

### Project Files

1. **Dataset File (`ExtraaLearn.csv`):**
   This file contains the dataset with various attributes of leads and their interactions with ExtraaLearn. It includes demographic information, interaction details, and lead status, which will be used for analysis and model building.

2. **Notebook File (`Predicting_Customers_ExtraaLearn.ipynb`):**
   This Jupyter Notebook contains the complete workflow for the project. It includes data loading, preprocessing, exploratory data analysis, model building, evaluation, and actionable insights. Users will run and edit this notebook to explore the data and build predictive models.

### How Users Can Get Started with the Project

To get started with this project, follow these steps:

1. **Download the Dataset:**
   Ensure the provided dataset (`ExtraaLearn.csv`) is placed in your Google Drive or local directory.

2. **Open the Jupyter Notebook:**
   Launch Jupyter Notebook and open `Predicting_Customers_ExtraaLearn.ipynb` to explore and run the code.

3. **Edit the Data Input Method:**
   Update the data input method to read the dataset from your preferred location:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   df = pd.read_csv('/filepath/ExtraaLearn.csv')
   ```

4. **Run the Notebook:**
   Follow and edit the cells in the notebook to preprocess the data, build and evaluate the machine learning models, and generate insights.

### Project Context

The EdTech industry is experiencing rapid growth, with the online education market projected to be worth $286.62bn by 2023. This growth has been accelerated by the Covid-19 pandemic, leading to an influx of new customers and companies in the sector. ExtraaLearn, an initial stage startup offering programs in cutting-edge technologies, faces the challenge of identifying which leads are more likely to convert to paid customers. This project analyzes leads data to build an ML model for predicting lead conversion and understanding the factors influencing this process.

### Data Description

The dataset contains various attributes of leads and their interactions with ExtraaLearn. Key attributes include:

- **ID:** Lead ID
- **age:** Age of the lead
- **current_occupation:** Occupation of the lead (e.g., Professional, Unemployed, Student)
- **first_interaction:** First interaction channel (e.g., Website, Mobile App)
- **profile_completed:** Percentage of profile completion (e.g., Low, Medium, High)
- **website_visits:** Number of website visits
- **time_spent_on_website:** Total time spent on the website
- **page_views_per_visit:** Average number of pages viewed per visit
- **last_activity:** Last interaction between the lead and ExtraaLearn
- **various flags:** Indicators of ad exposure in different media (e.g., print, digital)
- **status:** Whether the lead converted to a paid customer

### Actionable Insights and Recommendations

1. **Website Interaction:**
   - Maximizing website interaction is crucial for lead conversion. Time spent on the website and profile completion are significant factors. Implement strategies to encourage profile completion, such as offering access to the brochure after a set time if key profile information is provided.

2. **Advertising Mediums:**
   - Evaluate the impact of various advertising mediums on lead conversion. Perform cost analysis to optimize resource allocation towards the most effective channels.

By focusing on these areas, ExtraaLearn can enhance its lead conversion rates and refine its marketing strategies for better outcomes.
