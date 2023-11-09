<!-- Output copied to clipboard! -->

<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 1

Conversion time: 2.164 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Thu Nov 09 2023 14:47:16 GMT-0800 (PST)
* Source doc: CrossFit Companion  App  MVP specification
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 0; ALERTS: 1.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>


Below is the MVP specification for the CrossFit Companion App


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



<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")

