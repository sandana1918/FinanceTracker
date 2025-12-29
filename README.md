# Personal Finance Tracker

A robust desktop application built with Python and Tkinter for managing your personal finances. Track income and expenses, visualize your spending habits, and generate detailed reports.

## Features

*   **Dashboard Overview**: Get a quick snapshot of your total income, expenses, and savings.
*   **Transaction Management**: Easily add, edit, and delete income and expense records.
*   **Data Visualization**: View interactive charts and graphs to understand your financial trends (Monthly Trends, Income vs. Expense, Expense by Category).
*   **Reporting**: Generate monthly and annual reports to analyze your financial health.
*   **Data Export**: Export your summary reports to CSV or Excel for further analysis.
*   **Database**: Uses SQLite for secure and local data storage.

## Prerequisites

Ensure you have Python 3.x installed. You will also need the following Python libraries:

*   `tkinter` (usually included with Python)
*   `tkcalendar`
*   `pandas`
*   `matplotlib`
*   `Pillow`
*   `babel`

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/sandana1918/FinanceTracker.git
    cd FinanceTracker
    ```

2.  **Install dependencies:**
    ```bash
    pip install tkcalendar pandas matplotlib Pillow babel
    ```
    *Note: If you run into issues, try `pip3` instead of `pip`.*

## Usage

1.  **Run the application:**
    ```bash
    python finance_tracker.py
    ```

2.  **Navigate the App:**
    *   Use the sidebar to switch between Dashboard, Add Expense, Add Income, Reports, and Settings.
    *   Enter your transactions and watch the dashboard update in real-time.

## Project Structure

*   `finance_tracker.py`: Main application script.
*   `finance_tracker.db`: SQLite database file (created automatically on first run).
*   `assets/`: Directory for application assets (images, icons).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the [MIT License](LICENSE).
