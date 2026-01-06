# 🚗 Driving Distance Calculator

A simple, static web app that calculates driving distances between two addresses using Google Maps APIs.  No frameworks, no build tools—just pure HTML, CSS, and vanilla JavaScript hosted on GitHub Pages.

## Features

✨ **Clean, modern UI** with gradient styling  
📍 **Google Places Autocomplete** for both source and destination  
📏 **Accurate driving distance** in miles (via Google Distance Matrix API)  
⏱️ **Estimated driving time** displayed when available  
♿ **Accessible** with ARIA labels and live regions  
📱 **Responsive design** that works on mobile and desktop  
⌨️ **Enter key support** for quick calculations  

## Setup Instructions

### Step 1: Get a Google Maps API Key

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select an existing one
3. Enable these APIs:
   - **Maps JavaScript API**
   - **Places API**
   - **Distance Matrix API**
4. Go to **Credentials** → **Create Credentials** → **API Key**
5. Copy your API key

### Step 2: Configure API Key Restrictions (⚠️ Important for Security)

1. In the Google Cloud Console, select your API key
2. Click **Edit API key**
3. Under **Application restrictions**, select **HTTP referrers (web sites)**
4. Add your GitHub Pages URL: 