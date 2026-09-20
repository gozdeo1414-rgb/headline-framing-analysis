# Can a Headline Change How We Perceive a Story?

## Research Question

How do the linguistic and emotional features of headlines change when the same topic is presented through different framing styles?

## Project Overview

This project explores how different headline framing styles can be distinguished through measurable linguistic and emotional features.

The analysis uses five framing styles:

- Neutral
- Alarmist
- Positive
- Curiosity
- Sensational

Five topics are examined:

- Environment
- Artificial Intelligence
- Economy
- Health
- Technology

The dataset contains 25 controlled headlines, with five framing styles for each topic.

## Dataset

The headlines were created as a controlled dataset for exploratory analysis rather than collected from real news articles.

This design makes it possible to compare framing styles while keeping the topics balanced across categories.

### Dataset structure

- 5 topics
- 5 framing styles
- 25 headlines in total

## Methodology

The project uses Python and explores several measurable features of headline language:

- Word count
- Question mark usage
- Exclamation mark usage
- Positive word count
- Negative word count
- Average word length
- TextBlob sentiment polarity

The analysis compares these features across the five framing categories.

## Key Findings

The exploratory analysis shows several descriptive differences between framing styles.

### Headline length

Sensational headlines had the highest average length, with approximately 12 words per headline.

Neutral headlines had the lowest average length, with approximately 9.2 words per headline.

### Emotional language

Positive headlines contained more positive words on average, while alarmist headlines contained more negative words.

### Question marks

All five curiosity-framed headlines used a question mark, while the other framing categories did not.

### Sentiment

The average TextBlob sentiment scores differed across framing categories. Positive-framed headlines had the highest average score in this dataset.

These findings are descriptive and are based on a small controlled dataset.

## Limitations

This project has several important limitations:

- The dataset contains only 25 headlines.
- The headlines were controlled/generated for exploratory analysis rather than scraped from real news sources.
- The positive and negative word lists are simple and limited.
- TextBlob sentiment scores are model-based measurements and should not be treated as ground truth.
- The study does not include human participants.
- Therefore, the project does not directly measure whether headlines actually change people's perceptions.

## Future Research

Future versions of this project could:

- Analyze a larger corpus of real-world news headlines.
- Use more advanced NLP methods.
- Compare framing across different news organizations.
- Examine topic-specific framing patterns.
- Conduct a human survey or experiment to directly test whether different headline framings influence audience perception.

## Tools

- Python
- pandas
- matplotlib
- TextBlob
- Google Colab
- GitHub

## Project Structure

```text
headline-framing-analysis/
├── headline_framing_analysis.ipynb
├── data/
│   └── headlines_analyzed.csv
├── figures/
│   ├── headline_length_by_framing.png
│   └── sentiment_by_framing.png
└── README.md

Journalism | Data Journalism | AI & Computational Journalism
