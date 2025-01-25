# Aspect-Based Sentiment Analysis of Student Feedback on the Indian Education System

## Project Overview

In this project, we developed a comprehensive sentiment analysis system for student feedback on various aspects of the Indian education system. The process involved creating a custom questionnaire, collecting responses, and performing data preprocessing followed by sentiment analysis to gain insights into students' experiences. Based on these insights, we proposed actionable improvements for each aspect of the system.

## Key Steps

1. **Questionnaire Creation and Data Collection**: 
   - We designed and distributed a detailed questionnaire to collect feedback from students on various aspects of the education system, including course/program satisfaction, stress levels, examination experiences, learning methods, and future plans.

2. **Data Preprocessing**:
   - The collected data underwent extensive preprocessing, including:
     - **Tokenization**: Splitting text into smaller units (tokens) such as words or phrases.
     - **Filtering**: Removing irrelevant or non-informative words.
     - **Stop Word Removal**: Eliminating common words (e.g., "the," "and") that do not contribute to sentiment analysis.
     - **Stemming**: Reducing words to their root form (e.g., "running" to "run").

3. **Data Processing**:
   - We used various techniques to process the data:
     - **Cosine Similarity**: To measure the similarity between different student responses.
     - **Vectorization**: Converting text data into numerical vectors for machine learning models.
     - **Clustering**: Grouping similar responses to identify common themes.
     - **Word Cloud**: Generating visual representations of frequent words to identify major concerns among students.

4. **Sentiment Classification**:
   - We performed sentiment classification to categorize student feedback as positive, negative, or neutral.
   - We also analyzed the **subjectivity** and **polarity** of the feedback to understand how students felt about different aspects.

5. **Proposed Improvements**:
   - Based on the sentiment analysis, we came up with suggestive measures for each aspect of the education system to enhance student satisfaction and address common issues. These suggestions are detailed in our research paper.

6. **Research Paper**:
   - We documented the entire process, analysis, and findings in a comprehensive research paper that presents our results and proposed solutions for improving the Indian education system.

## Technologies Used

- **Python**: Core programming language for data processing and analysis.
- **pandas**: For data manipulation and cleaning.
- **nltk & text blob**: For natural language processing tasks like sentiment analysis, tokenization, and stemming.
- **sklearn**: For cosine similarity, vectorization, and clustering.
- **matplotlib**: For visualizations such as word clouds and charts.
- **Word Cloud**: To generate word cloud visualizations highlighting major student concerns.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

