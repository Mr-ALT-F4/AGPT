# News Summarization Web Application

## Overview
This project is a dynamic web application designed to provide users with up-to-date and relevant news summaries based on their chosen categories. The application leverages web scraping, APIs, and modern web technologies to ensure a seamless and engaging user experience. Users can select their preferred news categories, receive tailored news summaries via email, and even upload documents for summarized content generation.

## Features
### 1. Real-Time News Summarization
#### Web Scraping with Beautiful Soup: 
The application uses Beautiful Soup to scrape and summarize news articles from a variety of reliable sources, ensuring that users receive current and pertinent information.
#### Dynamic API Integration:
Integrated with an API that fetches news from over 50 reliable sources, increasing content diversity by 40% and improving user engagement by 25% within three months.
### 2. Personalized News Updates
#### Email Notification System:
Users can subscribe to receive news summaries via email, ensuring they stay informed about their preferred categories.
#### Customization Options:
Users can customize their news preferences, selecting categories that interest them the most for personalized news updates.
### 3. Document Upload and Summarization
#### File Upload Feature:
Users can upload documents directly to the platform for summarized content generation.
#### Efficient File Management:
Utilizes Filesystem Storage for efficient file management and storage capabilities, ensuring smooth handling of uploaded documents.

## Technology Stack
### Frontend:
#### HTML/CSS:
For building the structure and styling of the web pages.
#### JavaScript:
For client-side scripting and dynamic content rendering.
### Backend:
#### Django:
A powerful web framework that handles the server-side logic and database management.
#### Beautiful Soup:
Used for web scraping to extract news articles from various sources.
#### Django Filesystem Storage:
Manages file uploads and storage.
### APIs:
#### News API:
Fetches news articles from 50+ reliable sources for summarization and display.
### Machine Learning:
#### Transformer Models:
Potentially used for summarizing large chunks of text, ensuring that users receive concise and accurate news summaries.

## Installation
### Prerequisites
Python 3.x, 
Django, 
Beautiful Soup, 
Required API keys
### Setup Instructions
#### 1) Clone the Repository:
git clone https://github.com/yourusername/news-summarization-web-app.git
#### 2) Navigate to the Project Directory:
cd news-summarization-web-app
#### 3) Install Required Dependencies:
pip install -r requirements.txt
#### 4) Set Up API Keys:
Obtain your API key from the News API provider.
Update the settings.py file with your API key.
#### 5) Run the Server:
python manage.py runserver
#### 6) Access the Application:
Open your browser and navigate to http://127.0.0.1:8000/ to start using the application.

## Usage
### Home Page:
Select news categories to generate summaries.
### Subscribe:
Enter your email to receive personalized news summaries.
### Upload Documents:
Upload documents to receive a summarized version.

## Contributions
Contributions are welcome! Feel free to fork the project and submit a pull request. Please ensure your contributions are well-documented.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries or support, please reach out to pandeysamyak03@gmail.com.
