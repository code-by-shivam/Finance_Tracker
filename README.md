# Finance Tracker 💸

Finance Tracker is a full-stack web application built with the Python and Django framework. This application helps users monitor their personal finances, providing a clean interface to log and review their daily income and expenses.

## 🚀 Live Demo

You can access the live application here:

**[https://your-deployment-link.com](https://your-deployment-link.com)**

*(Replace the link above with your actual deployment link.)*



## ✨ Key Features

* **User Authentication:** Secure user registration, login, and logout system.
* **Transaction Management:** Easily **Add**, **Edit**, and **Delete** new income and expense records.
* **Dashboard:** A visual overview displaying your total balance, total income, and total expenses.
* **Categorization:** Organize your transactions into different categories (e.g., 'Food', 'Travel', 'Bills', 'Salary').
* **Filtering & Reports:** Filter transactions by date range, category, or type (income/expense).

## 🛠️ Tech Stack

* **Backend:** Python, Django
* **Database:** SQLite 3 (Default) / PostgreSQL (in Production)
* **Frontend:** HTML, CSS, Bootstrap (If used)
* **Authentication:** Django's built-in Authentication System

## 🚀 Local Setup and Installation

You can follow these steps to run the project on your local system:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/code-by-shivam/Finance_Tracker.git](https://github.com/code-by-shivam/Finance_Tracker.git)
    cd Finance_Tracker
    ```

2.  **Create and Activate a Virtual Environment:**
    ```bash
    # Windows
    python -m venv venv
    .\venv\Scripts\activate
    
    # macOS / Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install Required Packages:**
    (This command will install all necessary packages from `requirements.txt`.)
    ```bash
    pip install -r requirements.txt
    ```

4.  **Apply Database Migrations:**
    (This command will create the necessary tables in the database.)
    ```bash
    python manage.py migrate
    ```

5.  **Create a Superuser (Admin):**
    (Create an admin account to access the admin panel.)
    ```bash
    python manage.py createsuperuser
    ```

6.  **Run the Server:**
    ```bash
    python manage.py runserver
    ```

7.  **Access the Application:**
    Open your web browser and go to `http://127.0.0.1:8000/`.

## Usage

1.  **Register** a new account or **Login** with an existing one.
2.  On the dashboard, click 'Add Income' or 'Add Expense' to add new transactions.
3.  Go to the 'View Transactions' page to see all your records, filter them, or edit/delete them.
4.  Access the admin panel at `http://127.0.0.1:8000/admin/`.

## 📄 License

This project is licensed under the MIT License.