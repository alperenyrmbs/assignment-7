# Book Library App — Streamlit Coursework

A university notebook assignment for a small book library interface using Python, pandas, and Streamlit.

## Implemented in the notebook

- An initial dataset of five sample books
- A table displaying titles, authors, genres, page counts, and reading status
- A form for adding books
- Required title and author checks
- A positive page-count input
- Session-state storage and a refresh after adding a book

## Repository contents

**assignment7_streamlit_book_app_(2).ipynb** contains the assignment instructions and implementation.

## How to explore

Read the notebook on GitHub or open it in Jupyter/Google Colab. Streamlit needs its own app runtime: to run an interface locally, move the relevant app code into a Python script, install streamlit and pandas, and launch the script with Streamlit. After combining the Python app code from Parts 1–3 into `app.py` (omit the notebook's `!pip` line), the local commands are:

```bash
python -m pip install streamlit pandas
python -m streamlit run app.py
```

`app.py` is not committed in this repository; preparing it is a manual step. The repository currently contains a notebook, not a packaged or hosted application.

## Current limitations

Books are stored in Streamlit session state rather than a database. They are not permanently saved across new sessions. Title and author validation checks for empty strings but does not reject whitespace-only input. Dependencies are not version-pinned, and no automated app tests are included. The notebook retains assignment scaffolding and learning notes. It was reviewed but not executed for this portfolio update.

## Context

University coursework using sample book records. This is a small learning project, not a production library system.

[Alperen Yarimbas — Portfolio](https://alperenyrmbs.github.io/) · [LinkedIn](https://www.linkedin.com/in/alperenyr/)
