# Advanced-Project-Study_TUM-GG-Istanbul
From Keywords to Conversations: Traditional vs. LLM-based Consumer Search Behavior

A TUM × Google Istanbul Project Study

🚀 **Overview**

This project compares traditional keyword search (Google) with LLM-based conversational search (Perplexity) to understand how consumer search behavior changes in terms of:

- Search time
- Number & type of queries
- Click behavior
- Query intent pathways
- User satisfaction & trust
- Alignment with global search trends

The study uses logged behavioral data, NLP methods, regression analysis, and Markov models.

**🧪 Experiment
**

Between-subjects: participants randomly assigned to Google or Perplexity

Task: Find and evaluate smartphones under budget constraints

Data collected: queries, clicks, timestamps, session duration, survey responses

Additional layer: Google Trends API for external validation

**📂 Repository Structure
**

data/               # Raw & processed datasets  
notebooks/          # Analysis notebooks (cleaning, regression, NLP, Markov)  
src/                # Preprocessing, classifiers, embeddings, clustering  
presentation/       # Final slides and figures  
requirements.txt  

**📈 Key Findings
**

Perplexity users finished searches 67% faster

They submitted more complex, natural language prompts

Google users performed more refinement loops & clicks

LLM-style search leads to zero-click behavior and higher information overload

Google rated more trustworthy, Perplexity rated faster & more convenient

**🧠 Methods
**

Regex-based multi-label intent classifier

OpenAI embeddings + KMeans clustering

Markov chain models for intent transitions

OLS & Poisson regressions with robust errors

Sentiment analysis using GPT-4o-mini

**🔮 Future Directions
**

Longitudinal studies on conversational search adoption

Real purchase behavior integration

Larger, cross-cultural samples

Trust calibration techniques (citations, confidence cues)

**🤝 Team
**

Yen Vu Thi Ngoc • Rui Liu • Hande Gürsoy
Supervisors: Prof. Dr. Jochen Hartmann & Jan Ole Krugmann
