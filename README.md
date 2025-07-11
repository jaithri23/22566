# URL Shortener Web Application

This project is a lightweight, client-side URL shortener built using React via CDN. It enables users to shorten long URLs, assign optional custom codes, set expiration times, and track usage—all within the browser without any backend server or external database.

## Features

- Shortens long URLs into hash-based short links
- Optional custom codes 
- Set expiry duration in minutes 
- Tracks number of clicks and last clicked timestamp
- Displays link status: active or expired
- Stores data locally using browser's localStorage
- Copy-to-clipboard functionality
- Clean and responsive interface

## Technology Stack

- HTML, CSS for layout and styling
- React  for UI and state management
- Babel  for JSX compilation in-browser
- localStorage for persistent data storage

## How to Use

1. Clone or download this repository.
2. Open the `urlshortner.html` file in any modern web browser.
3. Enter the long URL you wish to shorten.
4. Optionally, enter a custom code and choose an expiration time.
5. Click "Shorten URL" to generate a shortened link.
6. Use the generated short link. When accessed, it redirects to the original URL and updates click statistics.


