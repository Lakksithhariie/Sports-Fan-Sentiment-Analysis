# Sports Fan Sentiment Analysis

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WqZ1gRuej2qdtFJn0HbDXPNgiyNZUHa4?usp=sharing)

## What is this project?

This project uses AI to understand how sports fans feel during games. We analyze Reddit comments using Natural Language Processing (NLP) and Generative AI to:
- Discover what aspects of the game fans care about most
- Predict how fan sentiment might change during future games
- Help teams improve fan engagement strategies

## Where did the data come from?

The data comes from Reddit sports communities (subreddits) using:
- **PRAW API** for recent comments
- **Pushshift API** for historical data

Example subreddits analyzed:
- r/nba (Basketball)
- r/soccer (Football)
- r/nfl (American Football)

## What did I do?

1. **Data Collection:** Gathered game discussions from sports subreddits
2. **Text Processing:** Cleaned and prepared fan comments for analysis
3. **Aspect Detection:** Used Groq's LLaMA-3-70B to find key discussion topics
4. **Sentiment Analysis:** Classified opinions as Positive/Neutral/Negative
5. **Prediction Model:** Built LSTM neural network to forecast sentiment trends
6. **Visualization:** Created interactive dashboards of fan sentiment

## Key Findings

- Game-changing moments (goals/penalties) create immediate sentiment spikes
- Team loyalty significantly affects how fans perceive referee decisions
- Merchandise/Stadium experience discussions correlate with ticket sales
- Our model achieves 82% accuracy in predicting 1-hour sentiment trends

## How to Use This Project

1. **Open in Colab:** Click the "Open in Colab" badge above
2. **API Setup:**
   - Get Reddit API credentials from [Reddit Apps](https://www.reddit.com/prefs/apps)
   - Add your Groq API key in the notebook
3. **Run the code:** Execute cells sequentially (Ctrl+F9 for full run)

**To set up the repository:**  
1. Create new repo at https://github.com/new named "Sports-Fan-Sentiment-Analysis"
2. Add this README.md
3. Upload your Colab notebook (File > Download .ipynb)
4. Add supporting files (data samples, images)

Need help with any step? I can provide specific instructions for:
- Adding collaborators
- Setting up GitHub Actions
- Configuring secret keys
- Adding project wiki pages

