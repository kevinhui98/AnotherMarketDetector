# Market Anomaly Detection

## Milestone 1

In this project, I experimented with different models (e.g. Isolation Forest, XGBoost, Linear Regression ...) with different parameters in order to 
to determine the best model that will produce the best results for the given data (data can be viewed in FinancialMarketData.csv). I was able to determine that 
the Random Forest model with max_depth=20 and n_estimators=200 with an accuracy of 94.17%! 

## Milestone 2 (in progress)

During this milestone, a system is being created to propose a data-driven investment strategy based on the model’s predictions, focusing on minimizing losses or maximizing returns.

Plan:
After having the saved model, I will then create a basic web app for users to use and to help them strategize a plan. The data will mostly come from Yahoo Finance and
the user will be able to query from a React.js UI. The reasoning aspect will come from the saved model and the Cerebras Inference model.

Technologies considering:
- React.js
- Cerebras Inference
- Model saved from previous milestone
- Yahoo Finance API


# Market Anomaly Detection 

An intelligent system that combines market crash prediction, automated investment strategies, and AI-driven explanation capabilities to make sophisticated financial strategies accessible to all users.

## 🎯 Project Overview
This project develops through three key phases:
1. Market crash prediction using machine learning
2. Automated investment strategy generation
3. AI-powered strategy explanation and guidance

## 🏆 Milestone 1: Model Development & Selection
Implemented and evaluated multiple machine learning models to identify the most effective approach for market anomaly detection:

### Models Tested:
- Random Forest
- Isolation Forest
- XGBoost
- Neural Networks
- Logistic Regression

### Results:
🥇 **Best Performing Model: Random Forest**
- Accuracy: 94.17%
- Parameters:
  - max_depth: 20
  - n_estimators: 200

The model was trained and validated on historical financial market data (available in `FinancialMarketData.csv`), incorporating various market indicators and metrics.

## 🎯 Milestone 2: Investment Strategy Engine (In Progress)

### Core Features:
- Automated strategy generation based on market conditions
- Risk-adjusted portfolio optimization
- Dynamic rebalancing signals
- Loss minimization algorithms
- Return maximization strategies

### Technical Components:
- Strategy calculation engine
- Portfolio optimization algorithms
- Risk assessment metrics
- Market signal processors
- Performance backtesting framework

## 🤖 Milestone 3: AI Strategy Advisor (Upcoming)

### Planned Features:
- Interactive AI chatbot for strategy explanation
- Natural language processing for user queries
- Personalized strategy recommendations
- Risk tolerance assessment
- Educational content generation
- Step-by-step implementation guidance

### Technology Stack:
Frontend:
- React.js dashboard
- Interactive visualizations

Backend:
- FastAPI server
- Yahoo Finance API integration
- ML model integration
- Strategy computation engine

AI Components:
- Cerebras Inference for strategy explanation
- NLP for user interaction
- Context-aware response generation

## 📈 Future Enhancements
- Multi-language support
- Custom strategy templates
- Advanced scenario analysis
- Real-time market insights

## 🛠️ Installation & Setup
(Coming soon)

## 📚 Documentation
(Coming soon)
