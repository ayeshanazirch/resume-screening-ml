# AI Resume Screening Tool

## Overview
This project automates resume screening using Natural Language Processing (NLP). It extracts text from PDF resumes and compares them with job descriptions to calculate a relevance score.

## Features
- PDF text extraction
- Text preprocessing
- TF-IDF vectorization
- Cosine similarity scoring
- Resume-job match percentage output

## Technologies Used
- Python
- PyPDF2
- Scikit-learn
- Pandas
- NLP (TF-IDF)

## How It Works
1. Upload a resume in PDF format
2. Extract text from the document
3. Input a job description
4. Convert both texts into numerical vectors using TF-IDF
5. Calculate cosine similarity to generate a match score

## Future Improvements
- Multi-resume ranking system
- Web interface using Flask
- Integration with database
- Advanced NLP models like BERT

## Author
ayesha