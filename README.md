# Calendar

1. Introduction

For our project this semester for "Computer Interfaces programming", we chose the calendar application. This application allows the user to create events, update and delete them.
The group is consisted of two members: Angela Kostadinova (5263) and Milana Sokolova (5332). In order to complete this project we used the following:
  
  -Java Spring Boot
  
  -Spring Data JPA
  
  -PostgreSQL
  
 
 2. CRUD

As mentioned before our application allows the user to create events, update and delete them.

 -Create an event

   Endpoint: POST /event

   Description: Create a new calendar event.

 -Get event Details

   Endpoint: GET /event/{Id}

   Description: Retrieve details of a specific event.

   Response: Returns the event object corresponding to the provided event ID.

 -Update an event

   Endpoint: PUT /event/{Id}

   Description: Update an existing event with new information.

 -Delete an event

   Endpoint: DELETE /event/{Id}

   Description: Delete a specific event.

 -List Events

   Endpoint: GET /events

   Description: Retrieve a list of all calendar events.

   Response: Returns an array of event objects.

   Response: Returns a success message upon successful deletion.
   
 3. Error handling
 
 We faced a lot of complicated bugs during the making of the application. The most repetitive bug was the Spring Boot application not starting. 
 The solution we came up for it:
 
   -Start the docker engine first and then start the IDE and run the calendar API.
   
 4. Testing

Our calendar API was tested on Postman platform, where it gave correct outputs.

 5. Docker Engine

URL:jdbc:postgresql://localhost:32769/postgres

Username: postgres

Password: passpass
    
 6. Link to Github Project upload

https://github.com/Kosangela/Calendar

  7. Conclusion
 
 The Calendar API provides a convenient way to manage calendar events through a set of RESTful endpoints. 
 This API offers a robust and user-friendly solution for managing calendar events in your application.
 By leveraging this powerful API, users can effortlessly create, retrieve, update, and delete events, providing a seamless and efficient scheduling experience.
 With the Calendar API, the user has the flexibility to create new events with customized titles, start and end times, descriptions, and locations.
 This allows the calendar's functionality to be tailored to meet the unique needs of the users, whether it's a personal planner, team collaboration tool, or enterprise-level calendar system.
 
