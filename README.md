# Emergency Medical Assistance PWA

## Overview

**Organization:** CDK Global (India) Pvt Ltd  
**Category:** Software  
**Difficulty Level:** Simple  

### Problem Description

In medical emergencies, making swift and accurate decisions can be critical. Choosing the right hospital can significantly impact a patient's survival chances. Our Progressive Web App (PWA) addresses this issue by providing users with essential information about nearby hospitals based on their location and specific medical needs, such as available facilities, medicines, blood groups, and specialists.

## Technology Stack

### Platform

- **Progressive Web App (PWA):**
  - **Advantages:** Cross-platform compatibility, responsive design, and no need for separate app stores.

### Geolocation

- **API:** Geolocation API
- **Purpose:** Retrieve the user’s current location to recommend the nearest suitable hospital.

### Mapping and Routing

- **Maps:** OpenStreetMap
- **Routing:** Leaflet Directions API or similar services to find the shortest path to the nearest hospital.

### Backend Services

- **Database:** Firebase Realtime Database or Firestore
- **Authentication:** Firebase Authentication (for secure user access)
- **Hosting:** Firebase Hosting or an alternative cloud-based hosting service

### Push Notifications

- **Service:** Firebase Cloud Messaging (FCM)
- **Purpose:** Send real-time alerts and updates to users.

### Additional Libraries

- **Service Worker:** Implemented for offline capabilities and performance improvements.
- **Responsive Framework:** Bootstrap or Tailwind CSS to ensure the app is responsive and user-friendly.

## Software Requirements

### Development Tools

- **IDE/Editor:** Visual Studio Code, WebStorm, or Sublime Text.
- **Version Control:** Git, with platforms like GitHub or GitLab.

### Frameworks & Libraries

- **Frontend:**
  - **Core Technologies:** HTML/CSS/JavaScript
  - **Framework:** React (for building UI components)
  - **CSS Framework:** Bootstrap (for responsive design)
- **Mapping & Routing:**
  - **Maps:** OpenStreetMap
  - **Routing:** Leaflet Directions API or equivalent
- **Service Worker:** For offline support and caching.
- **Push Notifications:** Firebase Cloud Messaging (FCM)

### Backend Services

- **Database:** Firebase Realtime Database or Firestore
- **Authentication:** Firebase Authentication
- **Hosting:** Firebase Hosting or any other cloud-based hosting service

### APIs

- **Geolocation:** Geolocation API for retrieving user location
- **Maps & Directions:** Leaflet or OpenStreetMap API

### Testing Tools

- **Browser Testing:** Chrome DevTools, Firefox Developer Tools
- **Cross-Browser Testing:** BrowserStack or Sauce Labs

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shashank4617k/Capstone-2024.git
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Run the App:**
   ```bash
   npm start
   ```

4. **Build the App:**
   ```bash
   npm run build
   ```

5. **Deploy the App:**
   Follow the instructions for deploying to Firebase Hosting or your preferred cloud-based hosting service.

## Contributing

Feel free to contribute to this project by submitting pull requests or opening issues for any bugs or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For further information or questions, please contact [Your Contact Information].
