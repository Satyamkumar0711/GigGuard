# GigGuard – AI-Powered Parametric Insurance for Gig Workers

GigGuard is an AI-driven parametric insurance platform designed to protect India’s gig workers from income loss caused by external disruptions such as extreme weather, pollution spikes, floods, or sudden curfews.
The system automatically detects disruptions, triggers claims, and processes payouts — offering zero-touch, weekly income protection.

🚀 Problem We’re Solving

Gig workers lose a significant part of their income when weather or environmental conditions stop them from working.
Traditional insurance doesn’t cover loss of income, leaving delivery partners vulnerable.
GigGuard provides an automated, affordable, weekly insurance model tailored for their needs.

🎯 Key Features
1. AI-Powered Risk Assessment

Dynamic weekly premium calculation

Hyper-local disruption risk scoring

Personalized pricing for each worker

2. Automatic Parametric Claims

Real-time monitoring of weather, AQI, and disruption triggers

Automatic claim initiation when income loss is detected

Instant payout simulation with no paperwork

3. Intelligent Fraud Detection

Claim anomaly detection

Location spoofing checks

Duplicate & fabricated claims prevention

4. Seamless User Experience

One-step onboarding

Weekly policy activation

Worker dashboard showing payouts, protection, and risk levels

🧩 System Workflow

User signs up and verifies delivery partner details

AI generates a risk score → Weekly premium calculated

Worker activates weekly coverage

GigGuard monitors triggers via APIs

Disruption occurs → Claim auto-initiated

AI validates and prevents fraud

Instant payout (mock) processed

Worker dashboard updates with protection summary

🛠️ Tech Stack

Frontend: React, Tailwind CSS
Backend: Node.js, Express
Database: MongoDB
AI Engine: Python (scikit-learn), anomaly detection models
APIs: Weather (mock), AQI mock, traffic/zone shutdown mocks
Payments: Razorpay/UPI simulator
Automation: Cron jobs + event listeners

📊 Parametric Triggers Used

Heavy rainfall

High AQI levels

Extreme heat

Government-announced curfews

Mocked traffic/zone closures

Each disruption triggers automatic payouts based on predicted income loss hours.

📅 Weekly Pricing Model

Premium = Base Rate + (Risk Score × Weightage)

Risk score factors:

Local weather volatility

Pollution trends

Disruption frequency in worker’s area

Seasonal historical data

👥 Team
Team Name: BugSlayer
Hackathon: Guidewire DEVTrails 2026: Unicorn Chase

Satyam Kumar(Team Leader)
Madhav Sharma
Shresth Kumar Gupta
Mihir Bansal
Vikram Singh

🔮 What's Next

Geofencing-based risk scoring

Real delivery platform API integration

Advanced anti-fraud ML models

Full payout automation with UPI sandbox

Admin dashboard with predictive analytics
