# Geni Fellah: Smart Agricultural Assistant

![Geni Fellah Logo](generated-icon.png)

## Overview

Geni Fellah is an intelligent agricultural assistant platform that helps farmers make informed decisions about their land, crops, and farming practices. Combining interactive mapping, crop recommendations, and personalized agricultural advice, Geni Fellah serves as a digital companion for farmers in Morocco.

## Features

### 1. Interactive Land Mapping
- Draw and select your land parcels directly on the map
- Automatic detection of region and estimation of surface area
- Soil type identification for accurate recommendations

### 2. Dual Chatbot System
- **General Agricultural Assistant**: Provides broad agricultural knowledge about crops, farming techniques, and best practices in Morocco
- **Land-Specific Expert**: Offers tailored advice based on your specific land parameters, including:
  - Crop recommendations
  - Irrigation planning
  - Disease prevention
  - Harvesting guidelines
  - Market information

### 3. Cultural Adaptation
- Full support for Darija (Moroccan Arabic dialect) with Arabic script
- Natural typing animation that simulates real conversation
- Contextual responses based on Moroccan agricultural conditions

### 4. Agricultural Knowledge
- Crop database with growth requirements and market potential
- Regional agricultural insights for different parts of Morocco
- Sustainable farming recommendations

## Technology Stack

- **Frontend**: React with TypeScript, Tailwind CSS, shadcn/ui components
- **Backend**: Express.js server
- **Map Integration**: Leaflet.js for interactive mapping
- **State Management**: React Query
- **Styling**: Custom agricultural theme with grain textures and earthy color palette

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the development server:
   ```
   npm run dev
   ```
4. Open your browser to view the application

## Usage Guide

### Land Selection

1. From the dashboard, click "Draw Your Land" to access the mapping tool
2. Use the drawing tools to outline your land parcel
3. The system will automatically detect the region and estimate the surface area
4. Select your soil type from the dropdown menu
5. Click "Consult Your Expert" to get land-specific advice

### Chatting with Geni Fellah

#### General Assistant (Dashboard)
- Ask general questions about agriculture in Morocco
- Learn about crop varieties, farming techniques, or market trends
- Get suggestions for sustainable farming practices

#### Land-Specific Expert (After land selection)
- Receive personalized recommendations based on your specific land parameters
- Ask detailed questions about:
  - Irrigation needs and scheduling
  - Fertilizer requirements
  - Pest and disease prevention
  - Optimal planting and harvesting times
  - Expected yields and market opportunities

## Project Structure

```
/
├── client/               # Frontend React application
│   ├── src/
│   │   ├── components/   # Reusable UI components
│   │   ├── hooks/        # Custom React hooks
│   │   ├── lib/          # Utility functions and types
│   │   ├── pages/        # Main application pages
│   │   └── ...
├── server/               # Backend Express server
│   ├── index.ts          # Server entry point
│   ├── routes.ts         # API routes
│   ├── storage.ts        # Data storage and retrieval
│   └── ...
└── shared/               # Shared types and schemas
```

## Supported Languages

- Darija (Moroccan Arabic dialect) with Arabic script
- English (for UI elements and navigation)

## Future Enhancements

- Weather forecast integration
- Crop market price tracking
- Integration with irrigation systems
- Mobile application with offline capabilities
- Community features for farmer collaboration

## About

Geni Fellah (الجني الفلاح) - meaning "The Agricultural Genius" in Moroccan Arabic - is designed to bridge the gap between traditional farming knowledge and modern agricultural technology, making expertise accessible to farmers across Morocco.
