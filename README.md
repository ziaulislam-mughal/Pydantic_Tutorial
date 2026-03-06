# Pydantic Crash Course

<div align="center">
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
</div>

Welcome to the **End-to-End Pydantic Crash Course**!...

 This repository contains a series of Jupyter Notebooks designed to take you from the basic problems Pydantic solves to advanced features like computed fields and nested models. 

## 📚 Course Content

The course is structured logically to build your understanding step-by-step. You can follow along by running the notebooks in order:

* **[0. Problems in Python](0-problems-in-python.ipynb)** An introduction to the common typing and data validation issues in standard Python that Pydantic helps resolve.
* **[1. Type Validation](1-type_validation.ipynb)**
  Learn the basics of how Pydantic enforces strict type hints and type coercion.
* **[2. Data Validation](2-data_validation.ipynb)**
  Explore built-in data validation features to ensure your data meets specific constraints.
* **[3. Field Validators](3-field_validator.ipynb)**
  Customizing validation logic at the field level using the `@field_validator` decorator.
* **[4. Model Validation](4-modal_validaor.ipynb)** *(Note: Filename is `4-modal_validaor.ipynb`)*
  Implementing complex validation logic that depends on multiple fields across an entire model.
* **[5. Computed Fields](5-computed_field.ipynb)**
  How to dynamically generate fields based on the values of other fields using `@computed_field`.
* **[6. Nested Models](6-nested-modal.ipynb)** *(Note: Filename is `6-nested-modal.ipynb`)*
  Structuring complex data by nesting Pydantic models within one another.

## 🚀 Getting Started

### Prerequisites

To run these notebooks, you will need Python installed on your machine along with Jupyter and Pydantic. 

### Installation

1. Clone this repository:
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>

2. (Optional but recommended) Create a virtual environment:
    ```bash 
    python -m venv venv
    source venv/bin/activate  # On Windows use 

3. Install the required packages:
    ```bash
    pip install pydantic jupyterlab

### 💻 Usage
--- 
Start the Jupyter Lab or Jupyter Notebook server to interact with the files:
```bash 
jupyter lab
# OR
jupyter notebook
```

#### Click on `0-problems-in-python.ipynb` to begin the crash course!

### 📄 License
This project is open source and available under the terms of the included *LICENSE* file.

---

**Tip:** Make sure to replace `<your-repo-url>` and `<your-repo-directory>` in the installation section with your actual GitHub repository URL and folder name! 

Would you like me to add a "Contributing" section or adjust any of the descriptions to better match the exact code inside your notebooks?

## 📬 Contact

If you have any questions, feedback, or just want to connect, feel free to reach out!

* **GitHub :** [Zia ul islam Mughal](https://github.com/ziaulislam-mughal)
* **LinkedIn :** [Zia ul Islam Mughal](https://www.linkedin.com/in/ziaulislammughal/)
* **Email :** [ziaulislammughal0@gmail@.com](ziaulislammughal0@gmail.com)
