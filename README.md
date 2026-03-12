# Personal Finance Tracker (TrackMySpend)

A Flask-based web application that helps users manage and analyze their personal expenses efficiently.

## Features

- User registration and login system
- Wallet balance management
- Add and track expenses
- Filter transactions by category, date, and payment method
- Interactive expense visualization
- Export transaction history to CSV and PDF
- Overspending alerts when wallet balance is insufficient

## Tech Stack

Backend
- Python
- Flask
- SQLAlchemy
- MySQL

Frontend
- HTML
- CSS
- JavaScript

Libraries
- Flask-Bcrypt
- FPDF

## Project Structure

TrackMySpend  
│  
├── app.py  
├── requirements.txt  
├── README.md  
├── .gitignore  
│  
├── static  
│   └── styles.css  
│  
├── templates  
│   ├── dashboard.html  
│   ├── history.html  
│   ├── homepage.html  
│   ├── index.html  
│   ├── login.html  
│   ├── register.html  
│   └── visual.html  


## Installation

Clone the repository

```bash
git clone https://github.com/Futuristic10/Personal-Finance-Tracker.git
```

Navigate to the project folder

```bash
cd Personal-Finance-Tracker
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

## Running with Docker (MySQL Database)

Start the MySQL container:

```bash
docker-compose up -d
```

This will start a MySQL container with the database `finance_tracker`.

## Future Improvements

- Monthly budgeting system
- Mobile responsive UI
- Multi-user analytics dashboard
- AI-based spending insights 

## Architecture

Flask Backend → MySQL Database → HTML/CSS Frontend → Chart.js Visualization

## Demo

This application allows users to:

- Register and login securely
- Track daily expenses
- Maintain wallet balance
- Visualize spending patterns
- Export reports in CSV and PDF

## Author

Soham Zinjurke
