# Fake-News-Detection
# Fake News Detection

This project focuses on detecting fake news articles using machine learning techniques. The provided dataset includes "Fake" and "True" news articles, and the accompanying Jupyter Notebook (`Fake news detection22.ipynb`) demonstrates the steps taken to build and evaluate the model.

## Project Structure
- **Fake.csv**: Contains fake news articles with metadata (title, text, subject, date).
- **True.csv**: Contains true news articles with metadata (title, text, subject, date).
- **Fake news detection22.ipynb**: Jupyter Notebook detailing data preprocessing, model training, and evaluation.

## Dataset Details
- Both datasets share the same structure:
  - `title`: The headline of the news article.
  - `text`: The body of the article.
  - `subject`: General category of the article (e.g., "News", "politicsNews").
  - `date`: Publication date of the article.

## Limitations
1. **Dataset Bias**: The datasets may include only specific categories or political biases, potentially limiting generalizability.
2. **Time-Specific Data**: Articles are dated, which might not reflect recent trends or writing styles.
3. **Subjectivity**: Labels ("Fake" or "True") may reflect subjective classification, introducing noise in the model.
4. **Model Interpretation**: The notebook lacks explanatory cells (markdown) to describe the logic or assumptions in the code.
5. **Language Variations**: Non-English articles or mixed-language data are not accounted for, restricting broader applicability.

## Usage
1. Load the dataset and notebook.
2. Follow the preprocessing and model training steps outlined in the notebook.
3. Evaluate the model's performance and test it with custom input data.

---

Contributions and suggestions for improvement are welcome!
