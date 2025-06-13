# Installation Guide for MVTec Anomaly Detection Jupyter Notebook

This is a repository used for storing SCOUT algorithm, its implementation for MVTEC dataset

## Prerequisites

1. Python 3.10.18.
2. GPU with CUDA support.

### 1. Clone the Repository

Ensure the Jupyter Notebook file is available locally. Clone or copy the necessary project files into a working directory on your system.

```bash
git clone https://github.com/your-repo/mvtec-anomaly-detection.git
cd mvtec-anomaly-detection
```

### 2. Set Up a Python Virtual Environment

Create and activate a virtual environment to isolate dependencies:

```bash
python -m venv mvtec_env
source mvtec_env/bin/activate  # On Windows, use mvtec_env\Scripts\activate
```

### 3. Install Required Packages

Install the necessary Python libraries listed below. You can directly use the provided `requirements.txt` file:

#### Using `pip` and `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 4. Install Jupyter Notebook

If Jupyter Notebook is not already installed on your system:

```bash
pip install notebook
```

### 5. Launch Notebook

Launch Jupyter Notebook to ensure all dependencies are correctly installed:

```bash
jupyter notebook
```

Open the `.ipynb` file and ensure it runs without errors.

* **Dataset:**
  Ensure the MVTec dataset is downloaded and organized in the expected format. Place it in the appropriate directory (e.g., `data/mvtec`). Update the paths in the notebook accordingly.

```bash
# Example structure
mvtec-anomaly-detection/
|-- data/
|   |-- mvtec/
|       |-- bottle/
|       |-- cable/
|       |-- ...
```
