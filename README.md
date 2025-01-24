# Best Cars Dealership - Reviews Website 🚗

Welcome to the **Best Cars Dealership Reviews Website**! This project is a comprehensive full-stack web application that allows users to view and post reviews for car dealerships across the United States.

---

## Features 🛠️

### General
- **Homepage**: Links to view dealerships, About Us, and Contact Us.
- **About Us Page**: Learn about the company’s mission, values, and leadership team.
- **Contact Us Page**: Displays company contact information (email, phone, and website).

### User Authentication
- **Register**: Create an account with required details and log in automatically upon registration.
- **Login**: Access your account to post reviews.
- **Guest Access**: Guests can view dealership reviews but cannot post reviews.

### Dealership Listings
- **View All Dealerships**: Access a list of dealerships nationwide.
- **Filter by State**: Narrow down dealership listings by selecting a state.
- **View Reviews**: Check reviews for a specific dealership.

### Review Management
- **Post Reviews**: Logged-in users can write and submit reviews for dealerships, including:
  - Purchase date
  - Car make and year of manufacture
- **Sentiment Analysis**: Display sentiments for posted reviews.

---

## Technologies Used 💻

### Frontend
- **HTML, CSS, Bootstrap**: For static pages (Home, About Us, Contact Us).
- **React**: For creating dynamic pages like Login, Registration, Dealership View, and Review Submission.

### Backend
- **Python, Django, SQLite**: Main backend for user authentication and dealership management.
- **Python, Flask, NLTK**: Sentiment analysis microservice.
- **Node.js, Express, MongoDB**: Dealership and review services.

### Deployment
- **Docker**: Containerized microservices.
- **Kubernetes**: Orchestrating and managing application components.
- **IBM Cloud Code Engine**: Serverless deployment for microservices.

---

## How to Run the Project 🚀

### Backend Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/best-cars-dealership.git
   cd backend
