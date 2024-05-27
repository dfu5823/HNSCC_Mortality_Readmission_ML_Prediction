## Machine Learning Prediction of 30-day Readmission and 30-day Mortality Following Surgical Resection of Head and Neck Squamous Cell Carcinoma

### Primary Author
**Daniel Fu, MS**  
Rutgers New Jersey Medical School, Newark, New Jersey, USA  
Email: danfu42@gmail.com

### Overview
This repository contains Jupyter notebooks for predicting 30-day readmission and 30-day mortality following surgical resection of head and neck squamous cell carcinoma. The analysis is implemented in Python 3.12.2 using Jupyter Notebooks.

### Data
The data used in this project is obtained from the National Cancer Database (NCDB). Due to privacy restrictions, the dataset is available by request only. For access to the data, please visit: [NCDB Patient User File](https://www.facs.org/quality-programs/cancer-programs/national-cancer-database/puf/).

### Installation

#### Prerequisites
- Python 3.12.2
- Conda environment manager

#### Setting Up the Environment
1. Clone this repository to your local machine.
2. Navigate to the cloned directory.
3. To create and activate the Conda environment with all the required dependencies, run the following commands:

    ```bash
    conda env create -f environment.yaml
    conda activate myenv
    ```

### Usage

#### Starting Jupyter Notebook
Once the environment is set up, you can start the Jupyter Notebook server using:
```bash
jupyter notebook
```
This command will start the server and open the notebook interface in your default web browser.

#### Running the Notebooks
The main notebooks for analysis are:
- `ent_outcomes_readmission.ipynb` for readmission prediction.
- `ent_outcomes_mortality.ipynb` for mortality prediction.

To run a notebook:
1. Open the notebook in Jupyter Notebook interface.
2. Navigate to `Kernel` > `Restart & Run All` to execute all cells in the notebook.

**Note:** Running the main notebooks may take up to 12 hours depending on your hardware configuration.

### Hardware Specifications
Tested on MacOS Ventura with the following specs:
- Processor: 1.4 GHz Quad-Core Intel Core i5
- Memory: 8 GB 2133 MHz LPDDR3

### Additional Information
This repository also includes several utility notebooks and Python pickle files containing intermediate data states to facilitate different stages of analysis. Please refer to `ent_utils.ipynb` for utility functions used across the project. For any questions please reach out to Daniel Fu.

### License
MIT License

Copyright (c) 2024 Daniel Fu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### Citation
