# VibeVault

VibeVault is a mobile-first location discovery platform designed to uncover and share hidden spots in Gwalior City, Madhya Pradesh. Built with React Native and Node.js, it combines GPS technology with rich community storytelling, enabling users to find, rate, and share meaningful local spots through an interactive map interface. Whether it’s a serene temple, a romantic garden, or a creative hangout, VibeVault connects users to the heart of Gwalior’s hidden gems with a sassy, vibrant vibe.

## Features

### Frontend (React Native with Expo)

- **Interactive Discovery Map**: GPS-based map displaying nearby hidden spots with custom markers for vibes (Romantic, Serene, Creative).
- **Rich Spot Details**: Immersive profiles featuring photo galleries, personal stories, vibe descriptions, and community tips.
- **Community Rating System**: Intuitive interface for rating spots on uniqueness, vibe, safety, and crowd levels with visual indicators.
- **Spot Submission Flow**: Comprehensive form for users to add new locations, including photo uploads, story writing, and vibe category selection.
- **Experience Sharing**: Comment system allowing anonymous or public sharing of personal experiences at each spot.
- **Smart Discovery Feed**: Personalized recommendations based on user preferences, location, and community ratings.
- **Photo Gallery & Stories**: Rich media displays showcasing multiple photos and personal narratives for each location.
- **Search & Filter System**: Advanced filtering to recommend only local hidden spots, excluding famous landmarks.

### Backend (Node.js with Express.js)

- **Geospatial Database**: MongoDB Atlas with geospatial indexing for efficient location-based queries and radius searches.
- **Multi-Dimensional Rating System**: Algorithm calculating composite scores for uniqueness, vibe, safety, and crowd levels.
- **Story & Experience Storage**: Flexible content management for personal narratives, tips, and community experiences.
- **Image Processing & Optimization**: Automatic image compression, resizing, and gallery management via Cloudinary.
- **Anonymous/Public Comment System**: Dual-mode commenting system allowing users to choose visibility levels.
- **Content Curation**: Community-driven algorithms for quality control and featured spot selection.

### Technical Stack

- **Frontend**: React Native with Expo for cross-platform mobile development.
- **Backend**: Node.js with Express.js for a robust API.
- **Database**: MongoDB Atlas (free tier) with geospatial features.
- **Maps**: Mapbox (free tier) for interactive maps.
- **Image Storage**: Cloudinary (free tier) for efficient image handling.
- **Location Services**: Expo Location for precise geolocation.

### Pre-Loaded Hidden Spots

VibeVault comes pre-loaded with four hidden spots in Gwalior City:

- **Bateshwar Temples** (26.5020° N, 78.2240° E, Serene): A group of 200 ancient Hindu temples, restored by ASI.
- **Teli Ka Mandir** (26.2260° N, 78.1652° E, Historical): A 9th-century temple within Gwalior Fort.
- **Italian Garden** (26.2200° N, 78.1800° E, Romantic): A serene garden with Italian architecture in Phool Bagh.
- **Chhatris of Scindia Dynasty** (26.2300° N, 78.1900° E, Architectural): Memorials with medieval stone carvings, built in 1817 CE.

## Installation

### Prerequisites

- Node.js (v16 or higher)
- MongoDB Atlas account
- Mapbox API key
- Cloudinary account
- Expo CLI (npm install -g expo-cli)

### Backend Setup

1.  git clone https://github.com/your-username/vibevault.gitcd vibevault/backend
2.  npm install
3.  MONGODB_URI=your_mongodb_atlas_connection_stringCLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_nameCLOUDINARY_API_KEY=your_cloudinary_api_keyCLOUDINARY_API_SECRET=your_cloudinary_api_secretMAPBOX_API_KEY=your_mapbox_api_keyPORT=5000
4.  npm start

### Frontend Setup

1.  cd vibevault/frontend
2.  npm install
3.  EXPO_PUBLIC_MAPBOX_KEY=your_mapbox_api_key
4.  npx expo start
5.  Use the Expo Go app on iOS/Android or a simulator to test the app.

## Usage

1.  Launch the app on your mobile device via Expo Go.
2.  Explore the interactive map centered on Gwalior City to discover hidden spots.
3.  View spot details, rate them, or share your experiences via comments.
4.  Submit new hidden spots with photos, stories, and vibe categories.
5.  Use the search and filter system to find spots matching your preferences.

## Future Implementations

To take VibeVault to the next level, we plan to:

- **User Authentication**: Add login/registration with social media integration for personalized profiles.
- **Offline Mode**: Cache map data and spot details for offline access.
- **Real-Time Notifications**: Notify users of new spots or comments in their area.
- **Gamification**: Introduce badges or points for discovering and sharing spots to boost engagement.
- **AI-Powered Recommendations**: Enhance the smart discovery feed with machine learning for better personalization.
- **Augmented Reality (AR)**: Integrate AR to preview hidden spots through the camera.
- **Multi-City Expansion**: Extend the platform beyond Gwalior to other cities in India.
- **Accessibility Features**: Improve UI/UX for visually impaired users with screen reader support.

## Contributing

We welcome contributions to make VibeVault even better! To contribute:

1.  Fork the repository.
2.  Create a new branch (git checkout -b feature/your-feature).
3.  Commit your changes (git commit -m "Add your feature").
4.  Push to the branch (git push origin feature/your-feature).
5.  Open a pull request.

Please ensure your code follows the project’s coding standards and includes tests where applicable.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- Built for an assignment to showcase Gwalior City’s hidden gems.
- Thanks to the open-source communities behind React Native, MongoDB, Mapbox, and Cloudinary.
- Inspired by the vibrant culture and history of Gwalior, Madhya Pradesh.

Happy exploring with **VibeVault**! Let’s uncover the hidden vibes of Gwalior together!
