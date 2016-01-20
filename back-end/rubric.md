# Back End Engineering Challenge - Rubric

GACon is looking for someone to design a RESTful API for data for talks at a conference and attendees. Some sample data is included in data.json.


## Some of our most successful candidates...


**Communicate using appropriate technical terms.**   

  - Demonstrate knowledge of *RESTful* conventions

  - Create the specified API routes/endpoints (knows what *API* and *route* mean) **and** list the endpoints in documentation.





**Demonstrate knowledge of software construction patterns and best practices.**
  
  - Use object oriented programming to create data structures mirroring talks and attendees. 

  - Create RESTful routes of the form:

  	- POST baseurl/talksto add a talk  
  	- POST baseurl/attendees to add an attendee  
  	- POST baseurl/talks/:talk_id/attendees to add an attendee to a talk (or PUT baseurl/talks/:talk_id/attendees/:attendee_id)  

  - Bonus: include a route to remove an attendee from a talk, probably:

  	- DELETE baseurl/talks/:talk_id/attendees/:attendee_id  

  - Bonus: include routes to display the data as well, for testing purposes

  	- GET baseurl/talks to see all talks  
  	- GET baseurl/attendees to see all attendees  
  	- GET baseurl/talks/:talk_id/attendees to see list of attendees at that talk  

  - Bonus: Describe the REST conventions he or she is following, possibly demonstrating awareness of pure REST (HATEOS, HTTP status codes).

**Consider design and implementation alternatives and make decisions based on relevant characteristics of the problem and available tools.**

  - Describe the back-end framework or technologies used and lists a benefit or benefits of the technology chosen. 
  
  - Decide how to host and display the API  and document this decision.

  - Decide whether attendees must be added to talks and stay consistent (for instance, if an attendee must be associated with a talk, destroy all attendees when a talk is deleted). Bonus: document this decision.
  
  - Either create a database or document that a database would be used in a real-world scenario.

**Demonstrate awareness of real-world technical development practices and of concerns related to the target company, including testing and security.**


  - Follow the format of data provided in data.json. (Bonus: read or load data from data.json programmatically).
  
  - Test the API before submitting, and describe the testing process.

  - Connect the coding challenge to GACon by mentioning attendee privacy, accuracy of timestamps for users from various timezones, or some other thoughtful feature.
  
