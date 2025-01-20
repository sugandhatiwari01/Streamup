# Jazzify

## Overview
This is a feature-rich **web-based music streaming platform** that allows users to stream and explore music seamlessly. Built using **PHP**, **HTML**, **CSS**, **JavaScript**, and **Tailwind CSS**, the platform offers a modern and intuitive user experience. Key features include Google SSO for streamlined authentication, a mailing system for user engagement, Spotify API integration for music search, and a library of over 50 downloadable songs for playback.

## Key Features
- **Login and Signup System**:
  - Secure login with Google Single Sign-On (SSO).
  - Signup includes email verification through an automated mailing system.
- **Music Search**:
  - Integrated Spotify API for discovering and exploring tracks.
- **Song Library**:
  - Pre-downloaded collection of 50+ songs available for playback.
- **Music Player**:
  - User-friendly interface for playing songs with essential controls.

## Technologies Used
- **PHP**: Backend logic and server-side scripting.
- **HTML, CSS, JavaScript**: Frontend design and dynamic interactivity.
- **Tailwind CSS**: Simplified and responsive styling.
- **Google OAuth**: For secure and convenient SSO.
- **Spotify API**: For music search and metadata.
- **Mailing System**: Sends automated emails during signup.

## Installation
Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd music-streaming-platform
   ```
3. Set up a local server environment (e.g., **XAMPP**, **WAMP**, or **MAMP**).
4. Import the database:
   - Locate the `.sql` file in the repository.
   - Import it using phpMyAdmin or your preferred MySQL client.
5. Install dependencies:
   ```bash
   composer install
   npm install
   ```
6. Configure the environment:
   - Update the `config.php` file with your database credentials, Google API keys, and Spotify API credentials.
7. Start the server:
   - Launch your local server and open the project folder in the browser.

## Usage
1. **Sign Up**:
   - Register for a new account.
   - Verify your email address using the link sent to your email.
2. **Sign In**:
   - Log in using your Google account or registered credentials.
3. **Search for Music**:
   - Use the integrated Spotify API to search for songs.
4. **Play Music**:
   - Browse and play songs from the pre-downloaded library.

## Screenshots
LOGIN PAGE

![image](https://github.com/user-attachments/assets/64b58d2f-6f09-4472-9ed9-5f83e200f4e7)


MAIN PAGE

![Screenshot 2024-12-20 151830](https://github.com/user-attachments/assets/682ec98f-c3e9-4cb6-9cc2-1e3197ab58db)


![image](https://github.com/user-attachments/assets/78121b8d-2571-454a-bdbb-8bd2868a259c)



## Acknowledgments
- **Google**: For the SSO integration.
- **Spotify**: For the music search API.
- **Tailwind CSS**: For responsive and modern design elements.
- **PHP and Mailing Libraries**: For backend functionality and email services.

---

Stream your favorite songs anytime, anywhere with our **Jazzify**!

 


