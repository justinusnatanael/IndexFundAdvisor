# IndexFundAdvisor

### Intelligent Financial Advisory Chatbot: AI-Driven Investment Insights for Index Funds Using CrewAI

## Overview
IndexFundAdvisor is an AI-powered multi-agent financial advisory system designed to provide strategic investment recommendations for stock market indexes using the CrewAI framework.

The chatbot processes a user-specified index and autonomously gathers, analyzes, and synthesizes information from multiple financial sources, including:
- Financial news articles
- Macroeconomic indicators
- Technical chart analysis

Using this multi-source evidence, the system generates actionable investment strategies such as:
- **BUY**
- **KEEP**
- **SELL**

The recommendations are tailored to the selected index and investment time frame.

To evaluate system performance, the project utilizes the RAGAS evaluation framework, including:
- Context Recall
- Context Precision
- Response Relevancy
- Faithfulness
- Noise Sensitivity

Additionally, a FastAPI-based prototype demonstrates the feasibility of deploying the chatbot in real-world financial advisory environments.

To assess practical investment value, AI-generated recommendations are manually reviewed and backtested using Return on Investment (ROI) calculations across multiple trading durations ranging from 3 months to 2 years.

The combined quantitative and qualitative evaluation highlights the system’s ability to deliver contextually relevant and evidence-based investment insights while identifying areas for future improvement in handling noisy or conflicting financial data.

---

# Key Features
- AI-powered multi-agent financial analysis
- CrewAI framework implementation
- Financial news analysis
- Macroeconomic indicator evaluation
- Technical analysis integration
- Automated investment recommendation generation
- RAGAS-based evaluation metrics
- FastAPI deployment prototype
- ROI backtesting and investment evaluation

---

# Project Structure

```bash
IndexFundAdvisor/
│
├── src/
│   └── indexfunds/
│       ├── main.py
│       ├── agents/
│       ├── tasks/
│       ├── tools/
│       └── ...
│
├── knowledge/
├── requirements.txt
└── README.md
```

---

# Technologies Used
- Python
- CrewAI
- FastAPI
- OpenAI API
- RAGAS
- Pandas
- NumPy
- Financial Data APIs

---

# Installation

## Clone the Repository
```bash
git clone <repository-url>
```

---

## Install Dependencies
Install all required packages using:

```bash
pip install -r requirements.txt
```

---

# VSCode Setup

1. Download or clone the repository
2. Open the project folder
3. Open Command Prompt or Terminal inside the project directory
4. Run the following command:

```bash
code .
```

This will open the project directly in Visual Studio Code.

---

# Running the Project

## Run CrewAI Workflow

1. Open the `src` folder
2. Navigate to the project directory
3. Open `main.py`
4. In the terminal, run:

```bash
cd src
```

5. Start the application using:

```bash
python -m indexfunds.main
```

---

# Evaluation Metrics
The system is evaluated using the RAGAS framework:

- **Context Recall**  
Measures how well the retrieved information covers the required context.

- **Context Precision**  
Evaluates the relevance of retrieved information.

- **Response Relevancy**  
Measures how relevant the generated response is to the user query.

- **Faithfulness**  
Assesses whether generated responses remain grounded in the retrieved context.

- **Noise Sensitivity**  
Evaluates the system’s robustness against irrelevant or conflicting information.

---

# Current Limitations
This project is still under development and several improvements can still be made, including:
- Improved financial data retrieval accuracy
- Better handling of noisy financial news
- Enhanced technical analysis capabilities
- More advanced portfolio optimization strategies
- Real-time streaming financial data integration
- Improved multi-agent coordination

---

# Future Improvements
Possible future enhancements include:
- Integration with real-time market APIs
- Advanced Retrieval-Augmented Generation (RAG)
- Portfolio recommendation systems
- Risk profiling and personalized investment strategies
- Deployment using cloud infrastructure
- Interactive web dashboard implementation

---

# Conclusion
IndexFundAdvisor demonstrates the potential of AI-powered multi-agent systems in supporting financial decision-making through automated and evidence-based investment analysis.

By combining financial news, macroeconomic indicators, technical analysis, and RAGAS evaluation, the project showcases how CrewAI-based architectures can provide contextually relevant and strategically valuable investment recommendations for index fund investors.
