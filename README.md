# novel-genre-classification

Interactive dashboard for exploring and classifying literary periods and fiction genres. Built with Python and Streamlit, trained on metadata for 709 novels sourced via the Wikipedia API.

## Streamlit App
See the app [here!](https://final-project-bk104.streamlit.app/)

## Built With
Python (scikit-learn, pandas, Streamlit)

## Features
- Random Forest classifier trained on CountVectorizer features, achieving 75.8% accuracy
- Real-time genre and literary period prediction
- Interactive data exploration and model output visualization
- Error analysis surfacing misclassification patterns across genre categories
- Visual trends in speculative fiction growth over time

## Structure
- `Home_Page.py` — main Streamlit app entry point
- `pages/` — additional app pages
- `data/` — processed novel metadata
- `requirements.txt` — Python dependencies

## Notes
Built as a course project (CS234, Fall 2025).
