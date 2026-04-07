# CONTENT-MISUSE-DETECTORR

A Streamlit app for detecting content misuse by comparing image similarity.

## Features
- Upload two images (original and suspected)
- Compute similarity score using image processing
- Display results with threshold-based detection

## Installation
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run: `streamlit run app.py`

## Deployment
### Streamlit Cloud (Recommended)
1. Push your code to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub account
4. Select the repository `Junecoderr/CONTENT-MISUSE-DETECTORR`
5. Click Deploy

### Other Options
- Heroku: Add a `Procfile` with `web: streamlit run app.py --server.port $PORT --server.headless true`
- Docker: Use the provided Dockerfile (if added)