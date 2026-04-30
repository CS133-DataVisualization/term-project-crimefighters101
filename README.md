# CSU Crime Statistics Research | CS 133 Data Visualization
## Team: 
CrimeFighters101

## Members: 
Emily Leson, Shannon Lo, Tyler Awender, Ynha Nguyen

## Project Details
This project analyzes reported crime patterns across California State University campuses using consolidated CSU campus safety datasets. The goal is to compare how crime differs across location categories such as on-campus property, public property, non-campus property, and student housing, and how reported crime trends changed from 2015 to 2023.

## Guiding Questions
1. How does the crime profile of public-access campus property (joint use between student and public access) differ from student-only facilities like On-Campus dormitory buildings and classrooms?
2. How have CSU crime patterns shifted over time (2015 between 2023), and is the 2020 to 2021 dip consistent across all campuses or concentrated in certain ones?
3. Are there specific areas on campus where the likelihood of theft relative to security patrol frequency is disproportionately high?
4. Which location category sees the highest share of drug, liquor, and weapons arrests, and does that match where criminal offenses concentrate or do arrests and offenses follow distinct geographic patterns across the four location categories?
5. Does a higher volume of people on campus lead to more reported crimes due to more targets, or fewer crimes due to more potential witnesses?

## Set Up
1. Open the GitHub repository.
2. Click on `CSU_Crime_Consolidated.ipynb` or `CSU_Crime_ML`.
3. At the top of the notebook preview, click **Open in Colab**.
4. If the button does not appear:
   - Go to [Google Colab](https://colab.research.google.com/)
   - Select the **GitHub** tab
   - Paste the notebook URL
   - Open the notebook
5. Upload or place the `Cleaned` folder in Google Drive, and update the CSU_Crime_Consolidated import to reflect where you put the `Cleaned` folder

6. Run the notebook cells from top to bottom.

## Dependencies
The notebook uses the following dependencies:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- geopy
- panel
- jupyter_bokeh
- scikit-learn
- notebook
- ipykernel

They are imported in the `CSU_Crime_Consolidated` file