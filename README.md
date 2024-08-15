# Programming Languages Analysis & Visualization

This project analyzes programming languages' popularity over time using data from Stack Overflow posts. The data is visualized using Matplotlib to show trends in the number of posts tagged with specific programming languages.

## Project Overview

This repository contains scripts and notebooks that perform data analysis and visualization of programming languages' popularity. The project uses Python and several key libraries such as Pandas and Matplotlib.

## Setup and Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/repositoryname.git
    cd repositoryname
    ```

2. **Set up a virtual environment (optional but recommended):**
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Ensure the directory structure is correct:**
    The script in `Practice8.py` expects a specific working directory. Make sure the directory path is correct or modify it in the script:
    ```python
    os.chdir('C:\\Users\\Siris\\Desktop\\GitHub Projects 100 Days NewB\\_24_0077__Day73_Data_Visualization_with_Matplotlib__240812\\NewProject\\r00-r09 START\\r00_env_START')
    ```

## File Descriptions

- **Practice8.py:** 
  - A Python script that processes data from `QueryResults.csv`, performs data transformations, and visualizes the rolling mean of programming languages' popularity over time.
  
- **Programming_Languages_(start).ipynb:** 
  - A Jupyter Notebook that likely contains exploratory data analysis (EDA) and visualization. Further details about the notebook contents would be needed to expand this description.
  
- **Data_Visualization_with_Matplotlib.ipynb:**
  - Another Jupyter Notebook focused on data visualization using Matplotlib. It likely builds on the data processed in the Python script or other notebooks.
  
- **QueryResults.csv:** 
  - A CSV file containing the dataset used for analysis. It includes columns for the date, programming language tags, and the number of posts.

## Usage

### Running the Script
To run the analysis and visualization provided in `Practice8.py`, ensure you have the necessary dependencies installed and the correct file paths configured. Then, execute the script:

```bash
python Practice8.py
Running the Notebooks
To explore or run the Jupyter Notebooks, start Jupyter Notebook or JupyterLab in your terminal:

bash
Copy code
jupyter notebook
Navigate to the Programming_Languages_(start).ipynb or Data_Visualization_with_Matplotlib.ipynb files and run the cells interactively.

Examples
Here is an example output from Practice8.py, showing the rolling mean of the number of Stack Overflow posts tagged with various programming languages over time:


License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
The data used in this project is sourced from Stack Overflow.
Special thanks to Dr. Angela Yu's 100 Days of Code course for providing inspiration and foundational knowledge.
Feel free to customize this README.md as necessary to fit your project.

vbnet
Copy code

### Next Steps:
- Make sure to replace `"path/to/your/saved/plot.png"` with the actual path where your plot image will be saved or provide additional instructions on how to generate it.
- Add any additional files or references you need for the project.

This `README.md` is ready to be pasted directly into your GitHub repository. If you need any adjustments or additions, just let me know!