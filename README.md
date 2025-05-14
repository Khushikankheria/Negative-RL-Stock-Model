# Negative-RL-Stock-Model

### 🧠 Objective
In the stock market, high rewards often come with high risks. This project shifts the objective from profit maximization to loss prevention, using a customized reward function that penalizes risky trades. By applying Negative RL with PPO, the agent learns to adopt safer trading strategies, ideal for conservative investors or institutional risk management.

### 📚 Features

✅ Reinforcement learning using PPO (Proximal Policy Optimization)
✅ Negative reward shaping to penalize losses and reduce risk exposure
✅ Training environment designed for risk minimization, not profit maximization
✅ Realistic stock market simulation using historical data
✅ Visual insights into agent decisions and trading outcomes

### 🏗️ Model Architecture & Workflow

- Algorithm: PPO (Actor-Critic)
- Environment: Custom OpenAI Gym-compatible stock trading environment
- State Inputs: Stock indicators (OHLC, Volume, Technical Indicators)
- Actions: Buy / Sell / Hold
- Reward Function: Penalizes large drawdowns, risky trades, and erratic behavior
- Training: PPO agent learns policy over multiple episodes with risk-averse feedback

### 📈 Performance Metrics

- Accuracy - 84.5%
- F1 Score - 0.81
- Precision -	0.79
- Recall -	0.84

