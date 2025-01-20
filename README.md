# google-map-28East

This is a simple web application that integrates Google Maps with an address autocomplete feature. Users can search for locations, drop pins on the map, and view details about the selected location.

---

## Features

- Interactive Google Map
- Address autocomplete using Google Places API
- Pin drop functionality with location details
- Responsive design for a clean user interface

---

## Prerequisites

Before running this application, ensure you have the following installed:

1. [Node.js](https://nodejs.org/) (v14 or later)
2. A Google Maps API Key (get it [here](https://console.cloud.google.com/)).

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/IvanKhutso/google-map-28East.git

2. Naviagte this repository:
   ```bash
   cd google-map-28East
3. Install dependencies:
   ```bash
   npm install

3. Create a .env file in the root directory and add your Google API Key:
   ```bash
   GOOGLE_MAPS_API_KEY=YourGoogleAPIKey
## Usage

1. Start the server:
   ```bash
   node server.js
2. Open your browser and navigate to:
   ```bash
   http://localhost:3000


## Folder Structure
```
google-map-28East/
├── public/
│   ├── index.html      # Frontend HTML with Google Maps integration
├── .env                # Environment file for API key
├── server.js           # Node.js backend server
├── package.json        # Project dependencies
└── README.md           # Documentation
