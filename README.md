# LEAF Framework: A Less Expert Annotation Framework

This repository contains the code and data used to train, test, and validate the models presented in our paper "A Less Expert Annotation Framework for Active Learning."

## Overview

Our project introduces a new annotation framework called LEAF (Less Expert Annotation Framework), designed to minimize reliance on highly-skilled annotators. Using a combination of soft labeling, large language models, and automatic hyperparameters optimization, LEAF aims to improve efficiency in an active learning environment.

## Repository Structure

Here is a brief explanation of the main contents of this repository:

- `data/`: Folder that contains all the datasets used in our experiments. Datasets are divided into subdirectories according to the tasks.
- `code/`: Folder containing the source code.
- `utils/`: Folder containing utility scripts and modules used in data processing, model evaluation, etc.
- `requirements.txt`: File listing all Python dependencies required to run the project.

## How to Run the Code

1. **Set up the Environment**
    - We recommend creating a new Python virtual environment, using tools like virtualenv or conda.
    - Activate the Python environment.
    - Install the Python dependencies using the command: `pip install -r requirements.txt`.

2. **Running Scripts**
    - From the root directory, navigate to the `src` directory: `cd src/`.
    - Execute the main script: `python main.py`.

## Datasets

The datasets for this project are stored under the `data/` directory. Each dataset is stored in a separate subdirectory, named according to the task. These datasets were used for training and testing purposes in our experiment.

Note: Be mindful that some of these datasets are large and may require significant memory when loaded into Python.

## Models

The trained models can be found in the `models/` directory. These models are saved in .h5 format and can be loaded using various machine learning libraries such as TensorFlow and Keras.

## Contributing

We welcome contributions! Please submit a Pull Request or open an Issue on GitHub if you have improvements or bug fixes. Please follow the existing coding convention, functionally modularize your code, and provide test units.

## Licensing

The LEAF Framework and the associated datasets are released under an MIT license. For more detailed information, please see the `LICENSE` file in the repository.

## Contact

For any further inquiries or questions about our project, please contact us at hasanjan@outlook.com.

## Citation

If you use our framework, datasets or implementations in your work, we encourage you to cite our paper:

```
[Publication Details]
```

---

**Thank you for visiting our repository! Enjoy exploring and utilizing the LEAF Framework for your research or projects!**
