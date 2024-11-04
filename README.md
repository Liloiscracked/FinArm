# FinArm
## Crowdfunding App: Connecting Startups with Investors

## Overview
This project is a cutting-edge crowdfunding solution specifically designed for the Saudi Arabian market. The app facilitates seamless connections between investors and startups through AI-powered matchmaking and intuitive search functionalities. Entrepreneurs can showcase their business ideas via elevator pitches, while investors can discover opportunities that align with their preferences and financial goals.

## Features
- **User Profiles**: Detailed profiles for both investors and entrepreneurs, showcasing history, preferences, and portfolios.
- **Startup Listings**: Startups can create detailed project profiles including videos, descriptions, and funding goals.
- **AI Matchmaking**: Personalized recommendations for investors based on preferences and historical data.
- **Investment Tracking**: Real-time tracking of investments and returns.
- **Portfolio Management**: Investors can view and manage their investment portfolios.
- **Chat System**: Direct communication between investors and entrepreneurs.
- **Notifications**: Users receive updates on investment opportunities and activities.

## Database Design
The database is designed with the following main tables:
- `User`: Stores general user data.
- `Investor`: Contains investor-specific information.
- `Entrepreneur`: Contains entrepreneur-specific information.
- `Startup`: Lists all active and past startups seeking funding.
- `Transaction`: Tracks all investment transactions.
- `Portfolio`: Manages historical investment data.
- `Pitch`: Stores details about startup elevator pitches.
- `Investment Preference`: Captures investor preferences for personalized suggestions.
- `Notification`: Logs notifications sent to users.
- `Chat`: Facilitates communication between users.
- `Feedback and Review`: Allows users to provide feedback and ratings.
- `AI Matchmaking`: Records AI-driven matchmaking results.
- `Admin`: Contains details about platform administrators.

## Tech Stack
- **Backend**: Python (Django), SQLAlchemy for database management.
- **Frontend**: React.js / Vue.js (optional), Bootstrap 4 for styling.
- **Database**: PostgreSQL / MySQL.
- **AI/ML**: Python (scikit-learn, TensorFlow) for implementing recommendation algorithms.
- **Hosting**: AWS, Heroku, or DigitalOcean.