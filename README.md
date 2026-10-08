# 🐼 Pandas

**Pandas** is an open-source Python library used for **data manipulation, data analysis, and data preprocessing**. It provides easy-to-use data structures such as **Series and DataFrame** for working with structured data.

## 📌 Key Features

* Series and DataFrame
* Data cleaning
* Data filtering and sorting
* Handling missing values
* Grouping and aggregation
* Reading and writing CSV/Excel files
* Data analysis and preprocessing

## ⚙️ Installation & Setup

### 1. Check Python Installation

Make sure Python is installed on your system:

```bash
python --version
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows:**

```bash
venv\Scripts\activate
```

**macOS/Linux:**

```bash
source venv/bin/activate
```

### 3. Install Pandas

```bash
pip install pandas
```

### 4. Verify Installation

```bash
python -c "import pandas as pd; print(pd.__version__)"
```

If the version number is displayed, Pandas has been installed successfully.

## 🚀 Import Pandas

```python
import pandas as pd
```

## 📝 Simple Example

```python
import pandas as pd

data = {
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [20, 25, 22]
}

df = pd.DataFrame(data)

print(df)
```

## 🎯 Uses

Pandas is commonly used in:

* Data Analysis
* Data Science
* Machine Learning
* AI Projects
* Exploratory Data Analysis (EDA)
