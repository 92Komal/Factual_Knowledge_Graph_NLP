
# FKG Framework

This repository contains the implementation and resources for the **FKG Framework**, designed to process and analyze datasets effectively. The repository includes preprocessing scripts, code for model training, and datasets for evaluation.

## Repository Structure

- **`FKG`**: Main module for the FKG framework.  
- **`Preprocess_FKG`**: Raw data to prepare it for the FKG pipeline.  
- **`code`**: Python scripts for implementing the core functionalities of the FKG framework, including training and evaluation.  
- **`data`**: Directory containing the proposed test set (Part_1) and supporting data files for evaluation.  
- **`data_1`**: Additional dataset directory containing (Part_2) test data for the framework.  
- **`README.md`**: Documentation file for the repository.



## Setup and Usage

### Prerequisites
- Python 3.7 or higher
- Required Python libraries:
  - `numpy`
  - `pandas`
  - `torch`
  - `tqdm`
  - `scikit-learn`


pip install -r requirements.txt
```

### Dataset
- The proposed test sets are available in the `data` and `data_1` folders.

### Running the Code
1. Preprocess the data using the scripts in `Preprocess_FKG`:
   ```bash
   python Preprocess_FKG/preprocess.py
   ```
2. Train or evaluate models using the scripts in the `code` folder:
   ```bash
   python code/train_model.py
   ```
3. Use the test sets from `data` and `data_1` to validate your results.

## Results and Evaluation

- Outputs include preprocessed data, model predictions, and performance metrics.
- Evaluation results are saved in the specified output directory.




