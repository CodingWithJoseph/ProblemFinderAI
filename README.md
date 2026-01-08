# Problem Finder ML Pipeline

ML system for detecting business opportunities by analyzing Reddit discussions using NLP classification.

## Overview

End-to-end pipeline: Reddit data extraction → cleaning → deduplication → labeling → model training → inference.

**Goal:** Identify and categorize problem statements in text that represent potential business opportunities.

## Tech Stack

- Python 3.9+
- PRAW (Reddit API)
- scikit-learn, XGBoost, LightGBM
- pandas, numpy
- Jupyter notebooks

## Setup
```bash
# Clone repo
git clone https://github.com/CodingWithJoseph/ProblemFinderAI.git
cd problem-finder-ml

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Project Structure
```
problem-finder-ml/
├── src/                    # Source code
│   ├── data/              # Data extraction & processing
│   ├── labeling/          # Annotation tools
│   ├── features/          # Feature engineering
│   ├── models/            # Model training & evaluation
│   └── inference/         # Prediction pipeline
├── notebooks/             # Jupyter notebooks for EDA
├── configs/               # Configuration files
├── scripts/               # CLI scripts
├── data/                  # Data files (gitignored)
└── models/                # Trained models (gitignored)
```

## License

MIT