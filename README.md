# Automated-SOS-RescueApp

The Emergency Response App is a comprehensive solution designed to provide immediate assistance during critical situations such as accidents, medical emergencies, and fires. Developed as part of the IEEE 24-Hour Hackathon organized by NHCE, this software empowers users to register, verify their identity, and quickly report incidents to a central station. It leverages real-time GPS data transmission, sound alerts, and visual cues to ensure a swift and efficient response to emergencies.

## Features
- Instant response system for emergencies, including accidents, medical issues, and fires.
- Sends an SOS message along with live map coordinates to a central station.
- User registration and OTP verification.
- Incident tracking and validation.
- Real-time GPS data transmission.
- Sound and visual alerts for SOS events.

## Dependencies Used
- [x] Flask for the web application.
- [x] Firebase for data storage and authentication.
- [x] Folium for map visualization.
- [x] Pygame for sound and visual alerts.

## Folder Structure
- `app/`: Contains the core application code files.
- `web/`: Includes HTML templates used for user interaction.
- `control_system/`: Contains files related to the control system component.

## Technologies Used
- **Python**: The primary programming language for its versatility and ease of integration with various libraries and frameworks.
- **Flask**: Used to build the web application component, handling user registration, verification, and interaction.
- **Firebase**: Employed for data storage and authentication, ensuring secure user information handling.
- **Folium**: Utilized for map visualization, displaying real-time GPS coordinates to users and emergency responders.
- **Pygame**: Used to create sound and visual alerts for SOS events, enhancing emergency response notifications.

## Setup and Installation 🚀
1. Clone the repository:
   **git clone "repository-url"**
3. Install dependencies:
   **pip install -r requirements.txt**
5. Set up Firebase credentials by replacing "app/...." with your Firebase Admin SDK credentials file path in app.py.
6. Configure other settings and customize the code as needed.
7. Run the Flask application: **python app.py**

## Usage
1. Register as a user by providing your name and phone number.
2. Verify your registration by entering the OTP received.
3. Select an incident category (e.g., medical emergency, fire).
4. If the incident count in the category exceeds a threshold, an SOS message is sent automatically.
5. Real-time GPS data is transmitted to the central station.
6. Visual and sound alerts are triggered for SOS events.

## Future Developments
- Implement a mobile app for users to enhance accessibility and responsiveness during emergencies.
- Enhance security features, including user authentication and data encryption, to ensure data privacy.
- Optimize real-time GPS data transmission for improved accuracy and reduced latency.
- Integrate with local emergency services and responders for a more coordinated and rapid response to incidents.
- Add support for additional incident categories, allowing users to report a wider range of emergencies.


