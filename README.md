# F1 Race Outcome Analysis
Can we use data and machine learning to predict who makes it to the podium in Formula 1?<br/>
This project says **yes** *(and backs it up with predictions for the 2025 Italian Grand Prix at Monza)*.<br/>

# About this project
Using past performance, qualifying stats, lap times, and pit stops, this project predicts the **top 3 finishers** at Monza 2025. It blends F1 domain knowledge with machine learning to simulate what might go down on race day.<br/>

# Features
🏁 Prediction of podium finishers using Random Forest and XGBoost<br/>
🎥 Visualizations of driver and team performance across races in Monza<br/>
🎯 Exploration of track and grid-podium correlations<br/>
⚡ Model pipeline for future predictions<br/> 

# Tech stack 
- Python, pandas, Numpy<br/>
- scikit-learn, XGBoost<br/>
- FastF1 (race data)<br/>

# How it works
1. Gather historical data using FastF1<br/>
2. Engineer features like qualifying position, average lap time, and pit stop count<br/>
3. Train and tune classification models<br/>
4. Predict the top 3 drivers for Monza 2025<br/>
5. Visualize and compare results<br/>

> Full predictions saved to 'italian_gp_2025_predictions.csv'<br/>

# More
This is Part 1 of a 3-part F1 AI/ML series:<br/>
- Race outcome analysis *(you're here)*<br/>
- [Weather impact analysis](https://github.com/swathikalburgi/F1-weather-impact-analysis)<br/>
- [Fan sentiment analysis](http://swathikalburgi/Fan-sentiment-analysis)<br/>
- [Project suite](http://swathikalburgi/F1-AI-ML-project-suite)<br/>


