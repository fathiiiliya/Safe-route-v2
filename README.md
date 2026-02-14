<p align="center">
  <img src="./img.png" alt="Project Banner" width="100%">
</p>

# SAFE ROUTE🎯

## SafeRoute is a web application designed to help users find the safest route between two locations.Most navigation apps like Google Maps focus on the fastest route, but they do not consider safety factors such as crime-prone areas, poor lighting, isolated roads, or accident zones.This can be risky, especially for women, students, and night travelers. The system evaluates multiple routes using safety parameters such as checkpoints, tolls, and optional user ratings. Each route is assigned a safety score, and routes are ranked accordingly, with the safest route highlighted using intuitive color indicators. The platform is scalable and can be integrated with real map APIs in the future, providing users with a practical and visually clear tool for safe navigation.

### team Name:Byte Force

### Team Members
- Member 1: Fathima Adeeba O P - LBSITW
- Member 2: Liya Fathima C K- LBSITW

### Hosted Project Link
https://regal-tiramisu-7f5448.netlify.app/

### Project Description
SafeRoute is a web app that helps users travel securely by analyzing multiple paths and scoring them based on safety parameters like checkpoints, tolls, and user feedback. The safest route is clearly highlighted, making navigation safer for vulnerable travelers, and the system can be expanded to work with live map services.

### The Problem statement
Current navigation systems fail to consider safety factors, leaving users exposed to unsafe routes and potential hazards during travel.

### The Solution
SafeRoute provides a safer alternative to traditional navigation apps by analyzing multiple routes between two locations. The system evaluates each route using safety parameters such as checkpoints, tolls, road conditions, and optional user ratings. Each route is assigned a safety score based on these factors, and routes are ranked accordingly. The safest route is highlighted with intuitive color indicators, making it easy for users to identify at a glance. This approach empowers travelers—especially women, students, and night commuters—to make informed decisions about their journeys. The platform is scalable and can be integrated with real-time map APIs in the future, providing a practical and reliable solution for safe navigation.

---

## Technical Details

### Technologies/Components Used

- Languages used: HTML
- Frameworks used: React.js
- Libraries used: Netlify Deployment tools-for hosting and deployment
- Tools used: VS Code

## Features
Main features of the project:
1)Safety-Based Route Ranking: Evaluates multiple routes using safety parameters like checkpoints, tolls, road conditions, and user ratings, and ranks them accordingly.

2)Visual Safety Indicators: Highlights the safest route with intuitive color codes for easy identification at a glance.

3)User Feedback Integration: Allows users to contribute ratings or feedback on route safety, improving the system’s recommendations over time.

4)Scalable Design: Built to support future integration with real-time map APIs and additional safety data sources.

5)Secure and Accessible Navigation: Provides a practical tool for travelers, especially women, students, and night commuters, to make informed decisions about their journeys.

## Implementation
User enters source and destination locations.
Google Maps API generates multiple possible routes.
Each route is divided into smaller segments for analysis.
Safety data (crime zones, time-based risk, user reports) is mapped to route segments.
A safety score is calculated using weighted risk factors.
The route with the highest safety score is recommended.
The safest route and risk zones are visually highlighted on the map.
Application is deployed using Netlify for public access.

#### Installation
Install Required Software:

1)Install Python (for backend processing).

Install Node.js and npm (for frontend development with React).

Install Git (for version control).

2)Clone the Repository:

git clone <your-repo-link>
cd SafeRoute

3)Backend Setup:

Navigate to the backend folder.

Install dependencies:

pip install -r requirements.txt


Run the backend server:

python manage.py runserver   # Django
or
flask run                    # Flask


4)Frontend Setup:

Navigate to the frontend folder.

Install dependencies:

npm install


Start the frontend server:

npm start


5)Access the Application:

Open a web browser and go to http://localhost:3000 (or the specified port) to use SafeRoute.

6)Optional Tools:

Use Postman to test APIs.

Use Docker for containerized deployment if needed.

#### Run
1.Start the Backend Server:

Navigate to the backend folder.

Run the server:

python manage.py runserver   # Django
or
flask run                    # Flask


2.Start the Frontend Server:

Navigate to the frontend folder.

Install dependencies (if not already done):

npm install


Run the frontend:

npm start


3.Open in Browser:

Open a web browser and go to http://localhost:3000 (or the port specified).

Enter the starting point and destination to see the safest routes.

4.Optional Testing:

Use Postman to test API endpoints.

Check safety scoring and route ranking functionality.




#### Screenshots 
opening page<img width="1914" height="957" alt="Screenshot 2026-02-14 080421" src="https://github.com/user-attachments/assets/1bfee02f-5256-4acc-82c1-63ad10db0751" />
this is the page which the user first sees and can input origin and destnation



final page<img width="1885" height="919" alt="Screenshot 2026-02-14 080517" src="https://github.com/user-attachments/assets/d90d3dee-c952-4ed3-b7d9-f735a3687935" />
this page shows the output to the user


**Example 1: Basic Processing**

**Input:**
Enter Origin and Destination to analyze multiple routes: origin-kochi , destination-trivandrum
**Output:**
Routes from kochi → trivandrum
Total routes found: 5

Route 4
Checkpoints: 6 | Tolls: 3 | User Rating: 2/5
Safety Score = 70 ⭐ BEST & SAFEST ROUTE
Route 5
Checkpoints: 3 | Tolls: 3 | User Rating: 5/5
Safety Score = 58
Route 3
Checkpoints: 2 | Tolls: 1 | User Rating: 1/5
Safety Score = 26
Route 1
Checkpoints: 1 | Tolls: 0 | User Rating: 1/5
Safety Score = 20
Route 2
Checkpoints: 2 | Tolls: 3 | User Rating: 1/5
Safety Score = 14


## Project Demo

### Video
[Add your demo video link here - YouTube, Google Drive, etc.]

*Explain what the video demonstrates - key features, user flow, technical highlights*



## AI Tools Used (Optional - For Transparency Bonus)


**Tool Used:**  GitHub, Copilot,perplexity ChatGPT


**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
  
## Team Contributions

- fathima adeeba: Frontend development,documentation, API integration
- liya fathima: Backend development,testing, Database design


**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
