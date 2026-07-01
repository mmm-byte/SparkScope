# SparkField: Property Repair Estimator

A mobile-first Progressive Web App (PWA) built for the Spark Homes acquisition team to estimate repair costs during onsite property walkthroughs.

## Project Overview
This project was developed for the Spark Homes Developer Contest. The objective was to create a fast, intuitive, and offline-capable tool that allows acquisition agents to perform room-by-room repair estimates in the field, export data to Excel, and streamline the acquisition pipeline.

## Key Features
- **Mobile-First UX**: Designed for field use with large touch targets and real-time calculation.
- **Dynamic Room Management**: Flexible system to add/remove room instances (Kitchen, Bathrooms, Bedrooms, etc.).
- **Offline Capability**: Built as a PWA with service worker caching; fully functional without internet access.
- **Photo Capture & Parsing**: Integrated camera support with basic image handling for serial numbers.
- **Data Persistence**: All projects saved locally via localStorage.
- **Export**: Generates a ZIP file containing an Excel breakdown and walkthrough photos.

## Technical Approach
- **Stack**: Vanilla JavaScript, HTML5, Tailwind CSS (via CDN).
- **Architecture**: Single-page application logic using a modular data structure based on the provided Pricing List.
- **PWA**: Implemented `manifest.json` and service worker for offline installation.
- **State**: Centralized data object managed by a custom state handler.

## How to Run Locally
1. Clone this repository.
2. Serve the files using any local server (e.g., `npx serve .` or Live Server in VS Code).
3. Open in a mobile browser or use Chrome DevTools "Device Mode" to simulate mobile behavior.

## AI Usage
AI tools (Claude/Cursor) were used for [insert your specific use, e.g., "structuring the service worker implementation" or "refining the CSS grid layout"]. The logic and core data implementation are my original work.
