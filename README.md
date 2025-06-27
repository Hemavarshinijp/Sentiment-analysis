### Install label-studio
Step 1: Installing and Launching label studio through command prompt
pip install label-studio
label-studio
While running i encountered some errors like missing dependencies
The error indicates that some required files were missing particular c++ build tools
I installed visual studio build tools and install with desktop development with c++ and rerun label studio

### SENTIMENT ANALYSIS 
1. Upload Dataset
- Imported `sentiment_dataset.csv` into **Label Studio**
- Each row in the CSV contains a text statement to be annotated

### 2. Select Template
- Chose the **Text Classification** template under **Natural Language Processing**
- Used predefined labels:  
  - `Positive`  
  - `Negative`  
  - `Neutral`

### 3. Add Label Names
- Added a new custom label `Neutral` using Label Studio's GUI (if not available by default)

### 4. Manually Annotate Data
- Reviewed each text statement and assigned one of the sentiment labels

### 5. Export Labeled Dataset
- Exported the annotated data as a `.json` file (`labeled_data.json`)
- Contains each text with the selected sentiment label



