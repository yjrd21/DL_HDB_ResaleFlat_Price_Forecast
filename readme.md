# DL_HDB_ResaleFlat_Price_Forecast

This repository contains our 50.039 Theory and Practice of Deep Learning project for forecasting HDB resale flat prices using deep learning techniques.

## Dataset
The dataset used for this project is retrieved from [data.gov.sg](https://data.gov.sg/datasets/d_8b84c4ee58e3cfc0ece0d773c8ca6abc/view).

`resale_flat_prices_original.xlsx` is the original dataset exported from the source.

The files below are intermediary files generated during the data preparation step:
- `resale_flat_prices_classified.xlsx`
- `resale_flat_prices_aggregated.xlsx`
- `resale_flat_prices_final.xlsx`

`resale_flat_prices_one_hot_vector_and_embed.xlsx` is the pre-processed dataset that will be used to train the forecasting models.

All dataset files can be found at [this Google Drive link](https://drive.google.com/drive/folders/16yzyB7VBLktP9UFbtng2bhYS_2SJL5_g). It is advised to only download `resale_flat_prices_one_hot_vector_and_embed.xlsx` into the folder 'DL_HDB_ResaleFlat_Price_Forecast', but feel free to explore the other data files.

## Prerequisites

Before running the notebook, ensure you have the following installed:
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab or VS Code with Jupyter extension
- Required Python libraries (see below)
    - Pandas
    - NumPy
    - PyTorch
    - Matplotlib
    - Scikit-learn

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yjrd21/DL_HDB_ResaleFlat_Price_Forecast.git
    cd DL_HDB_ResaleFlat_Price_Forecast
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
    
## Running the Notebooks

There are 2 notebooks to be run:
1. `data_preparation.ipynb`: contains data preparation and cleaning steps
2. `main.ipynb`: contains forecasting models and training process

**How to Run the Notebooks:**
1. Open this repository in Jupyter Notebook or JupyterLab or VS Code with Jupyter extension.

2. In the preferred interface, open the `data_preparation.ipynb` file.

3. Follow the instructions in the notebook to execute each cell. Ensure that you run the cells sequentially for proper execution.

4. Repeat Steps 2-3 with the `main.ipynb` file.

## Notes
- If you encounter any issues, verify that all dependencies are installed and compatible with your Python version.

## Acknowledgments

Special thanks to Professor Matthieu de Mari for providing us with guidance on this project.

## Deep Learning Group 10
- Daniel Yuen Jun Rong (1006380)
- Lim Jie Han (1006246)
- Ng Xue Min (1006127)