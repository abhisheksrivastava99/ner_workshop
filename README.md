# Interactive Named Entity Recognition (NER) for Financial Document Analysis

An interactive Jupyter Notebook workshop on Named Entity Recognition with a specific focus on financial document analysis and text processing.

## Overview

This workshop provides a comprehensive, hands-on approach to understanding and implementing Named Entity Recognition (NER) for financial text. Through interactive notebooks, you'll explore fundamental concepts, build custom solutions, and learn how to apply modern NLP techniques to extract structured information from unstructured financial documents.

## Workshop Structure

The workshop is divided into three Jupyter notebooks:

1. **ner_workshop.ipynb**: Introduction, basic implementation, and interactive concept explanation
2. **ner_workshop_continued.ipynb**: Advanced implementations and data flow visualization
3. **ner_challenges.ipynb**: Handling challenges, edge cases, and conclusion

## Prerequisites

- Python 3.7+
- Jupyter Notebook or JupyterLab
- Basic understanding of Python programming
- Familiarity with basic NLP concepts (helpful but not required)

## Installation and Setup

1. Clone this repository or download the notebook files
2. Install the required dependencies:

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

The workshop uses the following libraries:
- NLTK and spaCy for NLP and entity extraction
- pandas and NumPy for data manipulation
- matplotlib, seaborn, and plotly for visualizations
- ipywidgets for interactive elements

## Workshop Content

### Notebook 1: Introduction and Basic Implementation (ner_workshop.ipynb)

- **Introduction to NER**: Core concepts, entity types, and importance in financial analysis
- **Basic Implementation from Scratch**: Building a rule-based NER system using regex
- **Interactive Concept Explanation**: Exploring NER patterns through interactive tools

### Notebook 2: Advanced Implementation (ner_workshop_continued.ipynb)

- **Advanced Implementation with Libraries**: Using spaCy, NLTK, and comparing approaches
- **Data Flow Visualization**: Understanding the NER pipeline and data transformations

### Notebook 3: Challenges and Conclusion (ner_challenges.ipynb)

- **Challenges & Edge Cases**: Handling ambiguity, nested entities, and domain-specific terms
- **Interactive Edge Case Explorer**: Testing and debugging challenging financial texts
- **Conclusion & Further Reading**: Next steps and resources for continued learning

## Key Features

- **Interactive Demonstrations**: Real-time entity extraction and visualization
- **Financial Domain Focus**: Specialized for financial documents like SEC filings, earnings reports, and news
- **Custom Entity Types**: Financial-specific entities like stock tickers, monetary values, and percentages
- **Comparative Analysis**: Evaluation of different NER approaches for financial text
- **Practical Exercises**: Hands-on tasks and edge case exploration

## Learning Outcomes

After completing this workshop, you will be able to:

1. Understand the fundamentals of Named Entity Recognition and its applications
2. Build a custom NER system for financial text from scratch
3. Implement and compare rule-based, statistical, and deep learning NER approaches
4. Handle common challenges in financial NER like ambiguity and domain-specific terminology
5. Apply NER techniques to extract structured data from financial documents
6. Create interactive visualizations to explore entity relationships

## Usage

To get the most out of this workshop:

1. Start with the first notebook (`ner_workshop.ipynb`) and proceed sequentially
2. Execute each cell to see the interactive demos and visualizations
3. Modify the code and experiment with your own financial texts
4. Complete the practice exercises at the end of each section
5. Use the Edge Case Explorer in the third notebook to test challenging scenarios

## Sample Data

The notebooks include pre-configured examples of financial text for experimentation:
- Earnings reports
- Financial news
- SEC filings
- Market analyses

You can also input your own financial text to test the models.

## Contributing

Contributions to improve the workshop are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- spaCy and NLTK communities for their excellent NLP tools
