# Personal Finance Manager

This is a command-line application for managing your personal finances. It allows you to track income and expenses, view transaction summaries within specific date ranges, and generate visualizations of your financial data.

---

## Features
- **Add Transactions**: Record income and expenses with details like date, amount, category, and description.
- **View Transactions**: Display transactions within a given date range and provide a summary of income, expenses, and net savings.
- **Generate Plots**: Visualize income and expense trends over time using line plots.

---

### Prerequisites
Make sure you have the following installed on your system:
- Python 3.x
- `pandas` library
- `matplotlib` library

### Running the Application
1. **Clone or download this repository**.
2. **Run the application** using the following command:
   ```bash
   python main.py
   ```


## How It Works
- **Data Entry**: You can add transactions which are appended to `finance_data.csv`.
- **Data Visualization**: Using `matplotlib`, you can generate a line plot that visualizes income and expenses over a period.
- **Data Filtering**: Transactions are filtered based on the date range you provide, making it easy to review your financial activity for specific periods.

---

## Notes
- Ensure that the `finance_data.csv` file is in the same directory as your script to avoid any issues with reading or writing data.
- The application uses the `pandas` library for data handling and `matplotlib` for plotting.
