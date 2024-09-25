# RL TRADE WARS


This project explores the application of Reinforcement Learning (RL) algorithms such as Deep Q-Networks(DQN), Double Deep Q-Networks(DDQN), and Advantage Actor Critic(A2C) to algorithmic trading strategies. It simulates a competitive stock trading environment using historical data, where multiple agents trade across short-term and long-term timeframes. The agents are set up in decentralized and competitive manner so as to indicatre a competetion between them, hence the name Trade Wars. The custom-built StockEnvironment is based on the OpenAI Gym standards, enabling agents to learn and make investment decisions using different RL techniques.

The algorithms were trained on historical data of top 25 companies in S&P 100 index. The repository contains 3 folders named: Algorithms, Data and Saved models. It also contains a pdf file named "final_project_report.pdf" which contains the detailed description about the project and the results. The Algorithm folder contains all 4 .ipynb files. The data folder contains trade_wars.ipynb file which contains the code used for downloading the data, using AlphaVantage API. It also contains all the data in .csv format. Saved models folder contains saved models after training the agents.