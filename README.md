# House Expenses Tracker

A Python-based expense tracking system for house construction projects, using Jupyter Notebook for interactive expense management and visualization.

## Features

- Track and categorize construction expenses
- Visualize spending patterns
- Automatic data persistence in CSV and Excel formats
- Automatic backups
- Interactive data analysis and reporting

## Setup

1. Create a Python virtual environment:
   ```bash
   python -m venv venv
   ```

2. Activate the virtual environment:
   - Windows:
     ```bash
     .\venv\Scripts\activate
     ```
   - Unix/MacOS:
     ```bash
     source venv/bin/activate
     ```

3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook house_expenses_tracker.ipynb
   ```

2. Follow the instructions in the notebook to:
   - Add new expenses
   - View expense records
   - Analyze spending patterns
   - Generate visualizations

## Data Storage

- Data is automatically saved in both CSV and Excel formats in the `house_expenses_data` folder
- Automatic backups are created with timestamps
- Excel file includes multiple sheets for different views of the data

## Categories

The system includes pre-defined categories for common house construction expenses:
- Foundation
- Structure
- Systems (Electrical, Plumbing, HVAC)
- Interior
- Exterior
- Kitchen
- Bathroom
- Permits
- Labor
- Other

Each category has relevant subcategories for detailed expense tracking.
