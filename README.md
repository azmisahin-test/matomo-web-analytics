# Matomo Web Analytics Project

This project demonstrates how to set up Matomo for web analytics using Docker Compose.

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/matomo-web-analytics.git
   cd matomo-web-analytics
   ```

2. Start the services:
   ```
   docker-compose up -d
   ```
   
3. Access Matomo at http://localhost:8080.

4. Track your web pages by integrating the tracking code in web/index.html

## Project Structure
* docker-compose.yml: Configuration for Matomo and MySQL.
* web/: Directory containing the example web page.
