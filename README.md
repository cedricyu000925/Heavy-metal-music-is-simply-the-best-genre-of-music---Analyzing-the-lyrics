# Heavy metal music is simply the best genre of music - Thematic and Emotional Analysis of Heavy Metal Lyrics

## Introduction

![Iron Maiden](https://github.com/user-attachments/assets/b5078a98-653e-4ac9-b6ba-64ba60ce1233)

This project focuses on analyzing the thematic and emotional content of heavy metal lyrics using a dataset containing song information from various artists. The analysis aims to uncover common themes, sentiment trends, and emotional expressions within heavy metal music, providing insights into the genre's lyrical depth.

## Workflow of the Project

![Opeth](https://github.com/user-attachments/assets/3ff80a48-3888-4d6a-83be-65eab7188178)

1. **Data Loading**: The dataset, `Large Metal Lyrics Archive.csv`, is loaded into a Pandas DataFrame for processing.
2. **Data Cleaning**:
   - Removed leading and trailing spaces from columns.
   - Capitalized entries in relevant columns.
   - Normalized language entries to lowercase.
   - Dropped rows with instrumental songs (marked as "UNKNOWN" in the `DetectedLanguage` column).
   - Converted lyrics to lowercase and removed special characters.
   - Handled missing values by dropping affected rows.
3. **Thematic Analysis**:
   - Defined themes (e.g., love, anger, rebellion) and associated keywords.
   - Tokenized lyrics to categorize songs based on identified themes.
   - Conducted keyword extraction to identify common words associated with each theme.
4. **Emotional Analysis**:
   - Analyzed sentiment using TextBlob and VADER sentiment analysis tools.
   - Created a new column for sentiment scores and categorized sentiments as positive, negative, or neutral.
5. **Temporal Analysis**:
   - Analyzed trends over time by calculating average sentiment scores per year and counting the number of songs released each year.
6. **Artist-Specific Insights**:
   - Calculated average sentiment scores for top artists and visualized theme distributions for specific artists.

## Analysis Results

- The thematic analysis revealed prevalent themes such as love, anger, rebellion, and fantasy within the lyrics.
- Sentiment analysis indicated varying emotional tones across different songs, with some artists displaying consistently positive or negative sentiments.

  ![Average Sentiment](https://github.com/user-attachments/assets/364768c9-5cd8-401e-bfe3-527a093f64af)

- Temporal analysis highlighted trends in sentiment scores over the years, showing how lyrical content has evolved in heavy metal music.

![Sentiment Scores over the Years](https://github.com/user-attachments/assets/35820fb5-1577-45b9-816f-9305c5014565)


## Limitations

![Opeth 2](https://github.com/user-attachments/assets/67418f23-c3c6-4949-91d8-55e9c4b53d2c)

- The analysis relies on a basic keyword-based approach for emotion classification, which may not capture the full complexity of emotions expressed in heavy metal lyrics.
- Access to a widely recognized pre-trained language model would enhance the accuracy of sentiment analysis by providing a more nuanced understanding of lyrical content.

## Visualizations in Power BI

Available later

## Conclusion

![Metallica](https://github.com/user-attachments/assets/fae586e2-aa96-4687-8805-8cad4e2dc53c)

This project provides valuable insights into the thematic and emotional landscape of heavy metal music. The findings can be useful for music analysts, enthusiasts, and researchers interested in exploring the intricate relationship between lyrics and emotions in this genre.

## Files Included
- `Thematic-and-Emotional-Analysis-of-Heavy-Metal-Lyrics.ipynb`: The Python script containing the complete analysis process.
- `compressed_data.csv.gz`: The dataset used for analysis.
