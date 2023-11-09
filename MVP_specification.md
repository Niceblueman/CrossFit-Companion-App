
<center> Below is the MVP specification for the CrossFit Companion App </center>


## **Architecture**

The diagram illustrates the end-to-end flow of data through the system. It shows the interaction between the various components of the CrossFit Companion App, including the user interface, server, and database. Each part of the architecture diagram is clearly labeled to showcase the data flow.


## **APIs and Methods**


### **API Routes for Web Client Communication**



* `/api/workouts`
    * GET: Returns a list of CrossFit workouts with detailed instructions and video demonstrations.
    * POST: Allows the creation of new CrossFit workouts in the database.
* `/api/user`
    * GET: Retrieves the user's information based on the session ID.
    * POST: Updates the user's profile information in the database.


### **Public API Endpoints or Methods**



* `class CrossFitAPI.fetchWorkouts(category)`
    * Retrieves CrossFit workouts based on the specified category.
    * Parameters:
        * `category`: The type of CrossFit workout (e.g., cardio, strength, endurance).
* `function calculateCaloriesBurned(workout, duration)`
    * Calculates the estimated calories burned for a specific CrossFit workout.
    * Parameters:
        * `workout`: The type of CrossFit workout performed.
        * `duration`: The duration of the workout in minutes.


### **3rd Party APIs**



* YouTube Data API: Used to fetch video demonstrations for CrossFit workouts.
* OpenWeather API: Integrates weather data for outdoor workout recommendations.
* Firebase Authentication API: Handles user authentication and authorization.


## **Data Model**

The data model is created using SqlDBM to showcase the structure of the database and how data will be stored within the CrossFit Companion App.


## **User Stories**



1. As a beginner, I want to access a variety of structured CrossFit workout programs to improve my fitness level gradually.
2. As an advanced athlete, I want to discover challenging CrossFit workouts that target specific muscle groups to enhance my performance.
3. As a user, I want to save my favorite CrossFit workouts and track my progress over time to stay motivated and monitor my fitness journey.


## **Mockups**


### **Home Screen Mockup**


![alt_text](images/image1.png "image_tooltip")

