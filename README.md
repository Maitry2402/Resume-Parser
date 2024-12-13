# ResumeRevealer

ResumeRevealer is an advanced resume analysis tool that supports various document formats, including DOCX, PDF, and HTML. It leverages Natural Language Processing (NLP) techniques and machine learning algorithms to intelligently extract and analyze relevant information from resumes, making it an invaluable tool for recruitment, career counseling, and more.


## Features

### 1. Document Format Support
- DOC and DOCX: Extracts details from Microsoft Word documents, both legacy (DOC) and modern (DOCX) formats.
- PDF: Utilizes the `pdfminer` library for accurate text extraction.
- HTML: Processes resumes in web formats with seamless parsing.

### 2. Information Extraction
- Extracts key details such as:
  - Education
  - Contact Information (phone numbers, emails)
  - Skills
- Employs predefined lists and regular expressions for precise pattern matching.

### 3. Job Prediction
- Classifies and visualizes job title distributions within resumes using predictive algorithms.

### 4. Sentiment Analysis
- Reviews and evaluates the tone expressed in resumes.

### 5. Unethical Practice Detection
- Detects concealed content, such as white text on a white background, using advanced techniques. 
- Highlights and flags fraudulent practices to ensure ethical recruitment processes.

---

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.X
- Libraries:
  - `docx2txt`: Extract text from DOCX files.
  - `os`: Standard Python library for system operations.
  - `re`: Regular expression matching operations.
  - `nltk`: Natural Language Toolkit for NLP tasks.
  - `pandas`: Data manipulation and analysis.
  - `scikit-learn`: For vectorization, model training, and analysis.
  - `matplotlib.pyplot`: Plotting and visualizations.
  - `seaborn`: Advanced statistical data visualization.
  - `pdfminer.high_level`: High-level text extraction from PDFs.

Install the dependencies using `pip`:

```bash
pip install docx2txt nltk pandas scikit-learn matplotlib seaborn pdfminer.six
```

---

## Usage

1. Process Resumes: Parse resumes in various formats.
2. Extract Key Information: Automatically extract education, contact details, and skills.
3. Predict Job Titles: Classify job roles based on resume content.
4. Analyze Sentiment: Evaluate the tone of resumes.
5. Prevent Fraudulent Practices: Identify and flag unethical manipulations.

---

## Unique Selling Point (USP)

ResumeRevealer ensures ethical resume analysis by detecting and flagging practices like:
- White text manipulation (e.g., white text on a white background).
  
It enhances transparency and reliability, empowering recruiters with accurate and insightful resume evaluations.

---

## Project Overview

Although some functions are yet to be fully integrated, the existing features operate independently and effectively. The project aims to deliver a comprehensive solution with future updates.

Explore individual scripts and code in our [GitHub repository](https://github.com/Maitry2402/Resume-Parser).

---

## Future Enhancements

- Complete integration of all functionalities.
- Expand support for additional document formats.
- Add more advanced NLP and machine learning features.

---

## License

This project is licensed under the [MIT License](#) (or your chosen license). See the LICENSE file for details.

---
