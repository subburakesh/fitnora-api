# Fitnora API 🚀

<p align="center">
  <img src="https://github.com/subburakesh/fitnora/blob/main/assets/logo.png" alt="Project Logo" width="300">
</p>

This is the backend server powering the Fitnora ecosystem. Built with Go and Gin, it handles user authentication, cloud backups, and AI-powered food nutrition analysis.

## Features 🌟

* **Secure Authentication:** Handles user signup, login, and password resets using JWT tokens and secure email verification via Gmail SMTP.
* **AI Nutrition Search:** Integrates with the Google Gemini API to analyze food items and calculate accurate macronutrients per serving.
* **Cloud Backup Service:** Supports uploading and restoring encrypted local database archives and media files.
* **High Performance:** Lightweight and lightning-fast concurrency powered by Go routines.

## Tech Stack ⚙️

* **Language:** Go (Golang)
* **Web Framework:** Gin
* **ORM:** GORM
* **Database:** MySQL
* **External Services:** Google Gemini API, Gmail SMTP

## Getting Started & Configuration 🛠️

1. Clone the repository:
   ```bash
   git clone https://github.com/subburakesh/fitnora-api.git
   
   go mod tidy

   # Create a .env file in the root directory with your configurations.
   DB_USERNAME=root
   DB_PASSWORD=
   DB_NAME=fitnora
   DB_HOST=localhost
   DB_PORT=3306
   SMTP_MAIL=your_email@gmail.com
   SMTP_PORT=587
   SMTP_HOST=smtp.gmail.com
   SMTP_PASSWORD=your_email_password
   JWT_KEY=your_jwt_secret
   GEMINI_API_KEY=your_gemini_api_key

   # Run the server
   go run main.go
   ```
   
  
     
