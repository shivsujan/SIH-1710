# Smart India Hackathon Workshop

# Date: 02.06.2026
## Register Number: 212223040194
## Name: SHIV SUJAN S R

## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea

RailNav AI – Smart Indoor Navigation System for Railway Stations

RailNav AI is an AI-powered navigation platform that helps passengers easily locate platforms, ticket counters, waiting halls, food courts, restrooms, exits, elevators, and other facilities inside railway stations. The system provides real-time directions through mobile applications, digital kiosks, and voice-guided assistance, ensuring a seamless travel experience for all passengers, including differently-abled individuals.

## Proposed Solution / Architecture Diagram

```
                    +------------------+
                    |   Mobile App     |
                    +------------------+
                             |
                    +------------------+
                    |  Digital Kiosk   |
                    +------------------+
                             |
                             v
        +----------------------------------------+
        |          API Gateway Server            |
        +----------------------------------------+
                     |               |
                     v               v
          +----------------+   +----------------+
          | Navigation AI  |   | Railway Data   |
          | & Route Engine |   | Integration    |
          +----------------+   +----------------+
                     |               |
                     +-------+-------+
                             |
                             v
        +----------------------------------------+
        |      Cloud Database & Map Server       |
        | Facilities | Maps | QR Codes | Users   |
        +----------------------------------------+
                             |
                             v
        +----------------------------------------+
        |    Admin Dashboard & Monitoring        |
        +----------------------------------------+
```

## Use Cases

1. Platform Navigation
Passenger enters train/platform number.
System provides shortest route with live guidance.
2. Facility Finder
User searches for restroom, food court, ATM, or waiting room.
App displays nearest facility and navigation path.
3. Accessibility Support
Voice-guided navigation for visually impaired passengers.
Wheelchair-friendly route suggestions.
4. Emergency Assistance
Displays nearest emergency exits and help centers.
Sends alerts during emergencies.
5. Real-Time Station Updates
Admin updates facility locations or station layout.
Changes are instantly reflected in the application and kiosks.
6. QR-Based Indoor Positioning
Passengers scan QR codes placed throughout the station.
System accurately identifies current location and navigates accordingly.

## Technology Stack

### Frontend
React Native (Mobile App)
React.js (Web Dashboard)
Three.js (3D Maps)
### Backend
Node.js
Express.js
Python
### Database
PostgreSQL
MongoDB
AI & Navigation
TensorFlow
OpenCV
A* Pathfinding Algorithm
Machine Learning Models
### Cloud Services
AWS / Azure / Google Cloud
### Mapping & Tracking
QR Codes
BLE Beacons
GPS Integration
### Accessibility
Text-to-Speech (TTS)
Speech Recognition APIs

## Dependencies

### Software
Node.js
Python 3.x
Android Studio
VS Code
Git & GitHub
### Libraries
React Native
Express.js
Socket.IO
TensorFlow
OpenCV
Three.js
JWT Authentication
Leaflet.js / Mapbox SDK
### Hardware
Digital Touchscreen Kiosks
QR Code Stands
BLE Beacons
Railway Station Display Systems
### External APIs
Railway Information APIs
Google Speech-to-Text API
Text-to-Speech API
Cloud Storage Services (AWS S3 / Azure Blob Storage)

## Output

The developed RailNav AI system provides passengers with real-time indoor navigation inside railway stations through mobile applications and digital kiosks. Users can easily locate platforms, ticket counters, waiting halls, restrooms, food courts, elevators, exits, and other facilities using interactive 3D maps, QR-code-based positioning, and voice-guided assistance. The system also supports accessibility features for visually impaired and differently-abled passengers.

## Result

The proposed RailNav AI – Smart Railway Station Navigation System successfully enhances passenger navigation and accessibility within railway stations. The system reduces confusion, minimizes travel time inside stations, improves passenger convenience, and provides accurate real-time directions to station facilities. By integrating AI-based navigation, 3D maps, QR-based positioning, and accessibility support, the solution contributes to a smarter, more efficient, and passenger-friendly railway infrastructure.
