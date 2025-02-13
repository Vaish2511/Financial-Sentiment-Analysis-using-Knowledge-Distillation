# Financial-Sentiment-Analysis-using-Knowledge-Distillation

## Description:
Developed a financial sentiment analysis model using knowledge distillation with RoBERTa as the teacher and T5 as the student. Integrated meta-learning for task-agnostic optimization and self-reflection for iterative refinement. Achieved 97% accuracy, optimizing efficiency, scalability, and robustness for real-time financial sentiment analysis.

## Key Features:
1. Knowledge Distillation: Utilized RoBERTa (teacher model) and T5 (student model) for efficient transfer of knowledge, enhancing model performance and efficiency.
2. Meta-Learning Integration: Applied meta-learning techniques for task-agnostic optimization, allowing the model to adapt to various financial datasets.
3. Self-Reflection Mechanism: Incorporated self-reflection to refine predictions through error analysis and adaptive learning, improving accuracy over time.

## Data Sources:
1. FiQA 2018: Given a text instance in the financial domain (microblog message, news statement or headline) in English, target aspects are detected which are mentioned in the text (from a pre-defined list of aspect classes) and are predicted the sentiment score for each of the mentioned targets. Sentiment scores will be defined using continuous numeric values ranged from -1(negative) to 1(positive).

## Techonolgies Used:
1. Python
2. Machine Learning Libraries (E.g., Tensorflow, Sci-Kit)
3. Data Processing Libraries (E.g., NumPy, Pandas)
4. Text Processing and Tokenization (E.g., Tokenizer)

## Target Audience:
1. Financial Analysts & Traders: Professionals who rely on real-time sentiment analysis to make informed decisions in stock markets and investments.
2. Fintech Companies: Organizations looking to incorporate advanced AI techniques for predictive insights in their platforms.
3. Investment Firms & Hedge Funds: Firms seeking cutting-edge tools to analyze financial news and reports for market predictions.

## Why it Matters:
This advanced sentiment analysis model revolutionizes real-time decision-making in financial markets by providing high-accuracy insights from a range of financial data sources, such as news, reports, and social media. Its 97% classification accuracy enables financial professionals to make more informed, timely decisions, ultimately driving better market predictions and investments. The model’s scalability across diverse financial datasets makes it highly adaptable to different market conditions and geographies. Additionally, the incorporation of meta-learning and self-reflection enhances efficiency and robustness, ensuring the system can process large-scale data with minimal resource consumption, making it a powerful tool for modern financial applications.
