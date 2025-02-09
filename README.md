# Child Growth Analysis

## Overview
This is a Streamlit-based web application for visualizing child growth metrics, including height, weight, and BMI data for boys and girls. The app uses growth standards to compare individual data points against standard deviation (SD) curves, providing insights into child development trends.

The web Application is hosted [here](https://crescere.streamlit.app/)
## Features
- Displays height, weight, and BMI data for boys and girls.
- Compares child growth against standardized growth charts.
- Interactive visualizations using Matplotlib.
- Easy-to-use Streamlit interface for data exploration.

## Repository Structure
```
📂 Project Root
│-- stream.py                # Main Streamlit application
│-- height_df_boy.xlsx       # Height dataset for boys
│-- height_df_girl.xlsx      # Height dataset for girls
│-- weight_df_boy.xlsx       # Weight dataset for boys
│-- weight_df_girl.xlsx      # Weight dataset for girls
│-- bmi_df_boy.xlsx          # BMI dataset for boys
│-- bmi_df_girl.xlsx         # BMI dataset for girls
│-- HFA_Boys.xlsx            # Height-for-age standards for boys
│-- HFA_Girls.xlsx           # Height-for-age standards for girls
│-- WFA_Boys.xlsx            # Weight-for-age standards for boys
│-- WFA_Girls.xlsx           # Weight-for-age standards for girls
│-- BFA_Boys.xlsx            # BMI-for-age standards for boys
│-- BFA_Girls.xlsx           # BMI-for-age standards for girls
|-- Visualisation.ipynb      # Notebook in which code was first drafted
|-- extract.py               # code to extract the code from the ipynb
|-- extracted_code.py        # fetched code from Visualisation.ipynb
```

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone [link](https://github.com/gnanendranaidun/Crescere-data.git)
   cd Crescere-data.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   or 
   pip install streamlit pandas matplotlib openpyxl
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run stream.py
   ```

## How It Works
- The app loads datasets from Excel files using Pandas.
- Growth standard charts for height, weight, and BMI are plotted against age.
- Users can visualize and compare their own data with reference growth curves.

## Technologies Used
- **Python**: Core programming language.
- **Streamlit**: Web application framework.
- **Pandas**: Data processing and manipulation.
- **Matplotlib**: Data visualization.
- **Excel Files**: Data storage format.

## License
This project is licensed under the MIT License.

## Author
Gnanendra Naidu N

## License 
This is a open source project. Feel free to contribute

