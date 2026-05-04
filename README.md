## Hi. Welcome to Julia's GitHub.

* I am a grad student at UPenn, studying Computer Science
* Interested in Data-Driven Investing and ML Applications to the Alternative Asset Space.

## Skills:

**Programming:**
Python, SQL, Java, C

**Data Science & Machine Learning:**
pandas, NumPy, scikit-learn, PyTorch, TensorFlow

**Statistical & ML Methods:**
Regression (linear, logistic, Ridge/Lasso), tree-based models (random forest, gradient boosting), PCA, clustering, time-series modeling, NLP, transformer models

**Tools & Platforms:**
Git, Docker, Google Cloud Platform, VS Code, PyCharm

## Projects:

### [Loan Risk & Credit Default Modeling](https://github.com/julia-mt/loan_risk_credit_default_modeling)

**Tech Stack:** Python | Machine Learning | scikit-learn 

Developed machine learning models to estimate borrower default probability and portfolio loss distribution across a ~$1B consumer loan portfolio

Engineered predictive features including borrower behavior, macroeconomic sensitivity, and credit exposure

Applied PCA to transform features and performed K-Means clustering to identify groups of borrowers with similar risk characteristics

Analyzed potential mispricing by loan grade and evaluated implications for risk-adjusted returns

### [Financial Text Alpha Research Using Open-Source LLMs (Ongoing)](https://github.com/julia-mt/financial_text_research.git)

**Tech Stack:** Python | PyTorch | FinBERT | Hugging Face Transformers | statsmodels

Built an end-to-end pipeline ingesting S&P 500 earnings call transcripts from WRDS Capital IQ, parsing speaker-level text into structured executive 
and analyst turns across presentation and Q&A sections

Applied FinBERT to score sentiment at the speaker level and engineered event-level features including analyst Q&A pressure, executive-analyst
sentiment gap, and tone dispersion

Constructed cumulative abnormal returns (CAR) at 1, 3, 5, and 10-day horizons using CRSP daily stock data market-adjusted against the value-weighted index

Found statistically significant negative relationship between analyst Q&A sentiment and future CAR (β=−0.012, p=0.028 at 10-day horizon)

Long-short portfolio sorted on analyst sentiment quintiles generates 77bps mean monthly spread (p=0.048, Newey-West adjusted)

