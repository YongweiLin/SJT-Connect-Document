# St.James Town Community Corner


#### Q1: What are you planning to build?


  We are planning to build a mobile application for the St.James Town community. The app would provide building-to- building 
  information (head-count, services provided .etc) about the St.James Town community, and the provide its residents with
  information regarding events/programs/services that are available in the area. 
  
The app would provide an interactive map that, when clicked on, will display information about the buildings in the St.James
Town area. A common use case would be for a resident/visitor of the community to use the map to know more about the building 
they are currently in. The user would also be allowed to access different events/programs/services that are available in the 
area. The app would be synced with the Google Calendar for which  the community centre stores its events.
Users of the app would be able to sign up for events by indicating their interest for the event (similar to clicking you are 
‘interested’, ‘going’ or ‘not going’ for Facebook events). User account registration would also be streamlined to make the 
registration process easier.

For interactive map examples the following can be referenced:
https://disneyworld.disney.go.com/en_CA/magic-kingdom/maps/ 


#### Q2: Who are your target users?

Target users are residents of the St.James Town community and the staff operating the community centre and facilitating events 
within the community


#### Q3: Why would your users choose your product? What are they using today to solve their problem/need?


 *  Currently there is no application for the St.James Community that would showcase the community’s information and the 
 events in the area (in terms of mobile applications). 

 * The application would ease the process of residents trying to locate resources/events in the St.James area.

 * The  application would serve as a starting point to connect residents in St.James Town and help build a better sense of 
 community.

#### Q4: How will you build it?

	
  We will build the app using react native. It will be deployed on both Android and iOS thus the app will be released on the 
  Apple App Store and Google Play Store. We would also be building a central server with Node.js to handle all data pull 
  request(for events) from the mobile application. The server would be deployed on web-hosting services like Heroku.
  
	
  In terms of API we would be using the Google Calendar API to perform data GET requests for fetching events from the 
  Community Centre’s Google Calendar.
  
	
  For testing since the app is front-end heavy we would reply on user-testing. As for the web-server we would use API testing 
  apps like Postman to test our server.


### Highlights


Here are 4 key decisions we came up during our meeting with the partner:

1.How to display events
The partners specified an interactive map for displaying building options
We discussed about two options for displaying events:
The first one is to display all the events in a list.
Benefit: Easier to implement.

Second option is building an interactive map that shows the event along with the location. 
Benefit: Better for visualization.
	The partners will give the team a reply by the next meeting

2. The platform for the application 

The partners did not specify the platform for the application in the initial documents, we suggested doing a mobile 
application. The partner agreed and requested a cross-platform (iOS and Android) in order to reach a wider audience. Since 
there are members in the team that have experience with React we suggested using the React Native Framework. In the end we 
agreed on a React Native application.

3.Platform for the admin page and whether it is in the MVP

The partner wanted an interface to access the Google Calendar and fileMaker database at the same time. We suggested we embed 
the admin page into the application, in which the admin can login in via a special login page for admins in the application. 
We suggested this since this would be more convenient for future staff if they were to use the app. It would also reduce the 
development time as we would not need to develop a seperate application. The partners agreed to our suggestion. We also asked 
if this is a must-have feature in the application and the decision was to focus on the front-facing (resident-facing) modules 
first.

4. Requirements for the MVP
	
	As we discussed a lot of different features that could be included in the app, at the end of the meeting we asked the 
  partner to decide of the must-have features that would be in the MVP as it would not be plausible to complete all the 
  features within the 3 month timeframe we were given. The partner then laid out their requirements for the MVP:


  Events page: Displaying what events/programs are available, location of services

  Interactive Map: Display building profiles, click and find info about buildings

  Complete modules: each module presented must be fully tested and usable.




