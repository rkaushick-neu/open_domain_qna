# Dense Retrieval Passage for Open Domain Question & Answering

## Overview
This project implements a Dense Passage Retrieval (DPR) model for open-domain question answering. The goal is to retrieve relevant passages from a large corpus in response to user queries.

[ [CODE](./DPR_OpenDomain_QA.ipynb) | REPORT ]

## Prerequisites
Before running the project, ensure you have the following installed:
- Python 3.x
- Jupyter Notebook
- Required libraries (as specified in the notebook)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. Install the required packages. 
    
    If using CPU: 
    ```bash
    pip install -r requirements_cpu.txt
    ```
    If using GPU:
    ```bash
    pip install -r requirements_gpu.txt
    ```

## Running the Project
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook DPR_OpenDomain_QA.ipynb
   ```

2. Follow the instructions in the notebook to:
   - Load the dataset
   - Train the DPR model
   - Evaluate the model's performance

3. To run the model, execute the cells in the notebook sequentially. Make sure to adjust any parameters as needed for your specific use case.

## Usage
- After training, you can input your queries to retrieve relevant passages from the dataset.
- Experiment with different configurations and datasets to improve the model's performance.

## Future Work
This project is a work in progress. Future enhancements may include:
- Fine-tuning the model on larger datasets
- Implementing user feedback mechanisms
- Exploring deployment options for real-world applications

## License
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## Acknowledgments
- [Original DPR Implementation](https://github.com/facebookresearch/DPR)
