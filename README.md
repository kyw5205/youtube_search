# YouTube Search Web Application

This is a web application that allows users to search for YouTube videos using the YouTube Data API v3 and view the results in a card-style UI.

## Features
- Search for videos via keyword
- Display video title, thumbnail, channel name, publish date
- Click on thumbnails to open video in new tab

## Tech Stack
- Backend: FastAPI + Uvicorn
- Frontend: React (CDN) + Babel
- Deployment: Google Colab + pyngrok
- External API: YouTube Data API v3

## Folder Structure
- `app.py`: FastAPI backend server
- `run_server.py`: Starts FastAPI + ngrok in Colab
- `www/templates/index.html`: React mount point
- `www/static/js/app.js`: React code
- `www/static/css/style.css`: Styling

## Deployment (Colab)
1. Clone this repo to Colab
2. Install requirements and start the server
3. Open the ngrok public URL

## Screenshots
![image](https://github.com/user-attachments/assets/69caba57-19c6-4a58-ae27-0df91a206b02)


---
© 2025 by Kim yu wan
