# Data Analytics Environment Setup

This repository contains a Python environment setup for data analytics and PySpark development.

## Prerequisites

- Python 3.8 or higher
- pip (Python package installer)
- Java 8 or higher (required for PySpark)

## Setup Instructions

1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- On macOS/Linux:
```bash
source venv/bin/activate
```
- On Windows:
```bash
venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

## Included Packages

- PySpark: For big data processing
- Pandas: For data manipulation and analysis
- NumPy: For numerical computing
- Matplotlib & Seaborn: For data visualization
- Scikit-learn: For machine learning
- Jupyter: For interactive development
- PyArrow & FastParquet: For efficient data storage
- OpenPyXL & xlrd: For Excel file handling
- Plotly: For interactive visualizations

## Getting Started

After setting up the environment, you can start a Jupyter notebook:
```bash
jupyter notebook
```

Or create a new Python script and import the required packages:
```python
from pyspark.sql import SparkSession
import pandas as pd
import numpy as np
``` 