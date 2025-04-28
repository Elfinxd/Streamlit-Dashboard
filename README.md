Streamlit Dashboard
Welcome to the Streamlit Dashboard experiment!
This repository showcases a simple interactive web application built with Streamlit, allowing users to explore, upload, and visualize data — all deployed inside a Docker container.

🚀 Project Overview
This project demonstrates:

Interactive sidebar navigation between multiple pages.

Uploading and previewing CSV datasets.

Basic data summary and shape exploration.

Static and dynamic visualizations using Matplotlib and Streamlit's built-in chart components.

Dockerized deployment for easy reproducibility.

🛠️ Repository Structure

File	Description
Dockerfile	Docker configuration to containerize the Streamlit app.
requirements.txt	List of Python dependencies needed for the app.
main.py	Streamlit application source code.
🐳 Running the App with Docker
Make sure you have Docker installed on your system.

Clone this repository:

bash
コピーする
編集する
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Build the Docker image:

bash
コピーする
編集する
docker build -t streamlit-dashboard .
Run the Docker container:

bash
コピーする
編集する
docker run -p 8501:8501 streamlit-dashboard
Access the app:
Open your browser and go to: http://localhost:8501

🧩 Features
Home Page:
Introduction to the app with a Streamlit logo and navigation instructions.

Data Explorer:
Upload any CSV file and:

Preview the dataset.

View basic dataset statistics.

Check the shape (rows × columns) of the data.

Visualization:

View a sample sine wave plotted using Matplotlib.

Explore dynamically generated random datasets with line charts.

📦 Requirements
The app requires the following Python libraries:

streamlit

pandas

numpy

matplotlib

plotly

These are automatically installed when building the Docker container via requirements.txt.

📝 License
This project is for educational and experimental purposes.
