# RFID Access Log Analysis with Pandas

This repository contains a practical assignment for students. The goal is to analyze building access log data with `pandas`, create visualizations with `seaborn` and `plotly`, and build a simple web interface with `Gradio`.

## Files

- `pandas_rfid_task.ipynb` - the main notebook with the assignment, explanations, examples, and starter code
- `data/access_log_1000.csv` - sample dataset with RFID access events

## Dataset

The dataset contains the following columns:

- `Timestamp` - event date and time
- `Employee_ID` - employee identifier
- `Access_Point` - event type: entry or exit
- `Department` - employee department

## Task

Students are expected to:

1. Calculate how many people are inside the building for each hour.
2. Find employees with the longest time spent in the building, or employees whose stay exceeded 10 hours.
3. Detect at least one unusual case, for example an employee who entered the building but did not exit on the same day.
4. Create 2 to 3 charts using `seaborn` and `plotly`.
5. Build a simple `Gradio` app that lets a user upload a file and view at least one table or chart.

## How to Run

1. Install Python 3.10+.
2. Install the required libraries:

```bash
pip install pandas seaborn matplotlib plotly gradio jupyter
```

3. Open the notebook:

```bash
jupyter notebook pandas_rfid_task.ipynb
```

4. Make sure the dataset is available at:

```text
data/access_log_1000.csv
```
