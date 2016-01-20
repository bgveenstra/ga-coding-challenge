# Back End Engineering Challenge - Rubric

GACon is looking for someone to design a RESTful API for data for talks at a conference and attendees. Some sample data is included in data.json.


**Communicate using appropriate technical terms.**   


An ideal candidate:

  - demonstrates knowledge of RESTful conventions

  - creates the specified API routes (knows what "API" and "route" mean)

  - creates RESTful routes of the form:

  	- POST baseurl/talksto add a talk  
  	- POST baseurl/attendees to add an attendee  
  	- POST baseurl/talks/:talk_id/attendees to add an attendee to a talk (or PUT baseurl/talks/:talk_id/attendees/:attendee_id)  




**Demonstrate knowledge of software construction patterns and best practices.**


An ideal candidate:

  - includes helpful comments within code

  - documents the project in a readme, including instructions for installing and running the code.

  - uses version control (preferably git and/or GitHub) with commits that are:  
    - frequent   
    - self-contained units  
    - accompanied by helpful commit messages  

  - bonus: includes a route to remove an attendee from a talk

  	- DELETE baseurl/talks/:talk_id/attendees/:attendee_id or 

  - bonus: includes routes to display the data as well

  	- GET baseurl/talks to see all talks  
  	- GET baseurl/attendees to see all attendees  
  	- GET baseurl/talks/:talk_id/attendees to see list of attendees at that talk  

  - mindfully chooses which REST conventions to follow and which not to (aware of HATEOS)  

**Consider design and implementation alternatives and make decisions based on relevant characteristics of the problem and available tools.**

An ideal candidate:

  - describes the back-end framework or technologies used  

  - lists at least one beneift of the technologies chosen  

  - makes a decision about whether attendees must be added to talks and stays consistent (for instance, if an attendee must be associated with a talk, destroy all attendees when a talk is deleted)  

**Demonstrate awareness of real-world technical development practices and concerns related to the target company, including testing and security.**

An ideal candidate:

  - tests their API before submitting, and describes the testing process

  - 
