#  Reddit Comment Sentiment Analyzer

This project is a simple yet powerful tool that performs **sentiment analysis** on Reddit post comments using **VADER** (Valence Aware Dictionary and sEntiment Reasoner) from the `nltk` library, and **PRAW** (Python Reddit API Wrapper) for accessing Reddit data.

It's useful for analyzing community sentiment around hot topics in any subreddit — whether it's news, tech, gaming, finance, or general discussions.

---

##  Features

- Fetches comments from a specific subreddit or Reddit post
- Analyzes sentiment of comments using **VADER**
- Categorizes comments as **positive**, **neutral**, or **negative**
- Falls back across `hot`, `new`, and `top` posts if needed
- Adjustable comment limit

---

##  File Structure

| File                        | Description                                      |
|-----------------------------|--------------------------------------------------|
| `reddit_sentiment.py`       | Main Python script (you may rename as needed)   |
| `README.md`                 | Project documentation                           |
| `.env`                      | Environment variables file *(not uploaded)*     |

---

##  Dependencies

Install required libraries:

```bash
pip install praw nltk python-dotenv
