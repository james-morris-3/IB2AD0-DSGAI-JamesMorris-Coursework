# IB2AD0 Data Science & Generative AI

This repository contains my coursework for the IB2AD0 Data Science & Generative AI module at Warwick Business School. The notebooks cover Python fundamentals, data engineering with Pandas, statistical analysis, classical machine learning models (decision trees, linear/logistic regression), advanced ML techniques (random forests, GBDT), deep learning with PyTorch, CNNs, attention mechanisms, and transformer models for NLP.

The work progresses from basic Python programming through to implementing and fine-tuning BERT for sentiment analysis. Key sections include exploratory data analysis, feature engineering, model evaluation, and practical considerations for deploying ML in business contexts. The modeling hackathon (5_02) demonstrates end-to-end project execution under time constraints.

## Key Takeaways

The most valuable insight from this module was understanding the tradeoff between model complexity and interpretability. In business contexts, being able to explain why a model made a decision often matters more than squeezing out another percentage point of accuracy. This came through clearly in the decision trees work where simpler models with constraints performed nearly as well as complex ones but were actually usable in practice.

The transformer section showed how pre-trained models fundamentally change the economics of AI implementation. Rather than needing massive datasets and compute, fine-tuning existing models makes powerful NLP accessible. This has real implications for how businesses should approach AI strategy - buy vs build calculations look very different now.

Coming from a management background, the most challenging part was getting comfortable with the math behind backpropagation and gradient descent. The PyTorch notebooks forced me to actually understand what's happening rather than just calling sklearn functions, which was frustrating but ultimately more valuable.