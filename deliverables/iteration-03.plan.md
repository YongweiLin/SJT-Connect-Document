# SJT Connect (St James Town Connect)

## Iteration 3

Start date: 3/11/2019


End date: 3/28/2019

## Iteration process

This iteration involves completing all of the features that were in the MVP and some of the extra features. The iteration also involves polishing the app UI and cleaning up any existing bugs/warnings. After this iteration, the app should be ready to be presented to the partner and uploaded to the app store/google play store.

#### Changes from the previous iteration
In short, our team has decided to fully concentrate on enhancing the user experience. After all, the users will care much more about how user-friendly and useful our App is over how many fancy pages we have.

Our team met with the partner in person after D2 to present the prototype of our app. Based on the feedback from our partner, we have made the following changes:


First of all, Our team decided to polish the app UI, make sure the app is bugs/warnings free and implement add-on features such as :


1. Adding a bar-code scanner in the login page so that people can log-in more easily 

2. Adding date picker and location picker in the event list page so that users can search for events by location or time. Also, the newly updated search bar also allows users to manually input events’ names or location.

in order to improve the user experience.


Secondly,  our partner and our team agreed not to implement the admin page even though we have finished the back end part for the admin page, (for example, the server calls for adding an event to the google calendar). This change is caused by the privacy issue. We still have no direct access to the users’ database and the google calendar. Therefore it would be impossible for our team to implement a functional admin page

Besides these two changes, our partner and our team agreed that there is no need to connect the interactive map with the event list simply because almost all the events for St James Community are held in 200 Wellesley St E. It seems unnecessary to implement this feature since for now, only one of the building on the interactive map can be redirected to the event list page.

#### Roles & responsibilities of members

#### Backend team:

- Nick 


Fetch events data from Google Calendar using Google Calendar API in the backend server. 
Design the database for building information in FileMaker.


Strengths: Java, Javascript, Node.js, familiar with MongoDB and some SQL.


Weaknesses: No experience with mobile app


- Toby


Implement backend’s core functions including server calls, encryption, and authentication. 


Strengths: Large project design/development experience, server development experience. 



Weaknesses: No database experience.



#### Frontend team:
- Andres 


Design the user profile page and multi-language option (will finish in next iteration).


Strengths: Javascript, familiar with React.js, Google Firebase, and Realm Mobile Database


Weaknesses:  No experience with FileMaker


- Chris


Design the main architecture of the mobile app (composition of pages, local data storage). Implement the interactive map and building info.


Strengths: Java, Node.js, Mobile Development


Weakness: No real experience in React, No experience with File Maker, No practical experience with Agile Methodologies


- Xiaoli Liu: 


Implement the front end of the Login and Signup pages.


Strengths: Have knowledge of HTML, CSS, Javascript, Node.js, and React.js. Took CSC309. Have experience of building sign-in and sign-up part. 


Weakness:  No experience of mobile app and FileMaker.

- Yongwei Lin


Design and implement the event list page and event details page.


Strengths:  Familiar with Javascript, Nodejs, NoSql, MySql and agile methodology. Web app development experience.


Weaknesses:  No previous experience with FileMaker. First time doing a mobile app.





#### Team Rules

Our team’s working culture focuses on solving problems as fast as possible and relies on constant communication. Team members are expected to respond to messages frequently and provide assistance when problems arise.

- Communications:


We would be using facebook messenger for our main channel of communication
We expect to communicate on a daily basis within our team
Our main channel of communication with the partner will be via email and Skype meetings (except for the first meeting which would be in person)

 
- Meetings:


Meetings: Team leads in each team (Front End and Back End) would be responsible for holding weekly team meetings and keeping track of the team’s progress throughout the project. The team lead would also be responsible for making sure each team member attends meetings and completes his/her deadline. In the case that a member fails to attend the meeting without a valid reason the team lead should report to the rest of the team and if the situation worsens, report to the TA/professor.
 
- Conflict Resolution:


Possible Situation 1: A team member is not meeting the deadline. 

We will talk with the member and offer help. If the workload assigned to the member is too much, other teammates will help finish only part of the work. We will not directly take over a large proportion without communication.


Possible Situation 2: A team member is not answering the emails/texts. 

We will send out more messages in a polite and constructive way. If necessary, we will try to find the team member in person. We are going to talk with the professors after we try both ways above.


Possible Situation 3: A team member finished a large portion of the project without consulting with anyone else. 
This situation may happen when the design of our project is too simple. In this case, we will implement more features to add complexity to the project. Each of the team members will participate in the code review to check if there are problems/bugs with the code this member has finished.



#### Events

- Every Thursday in-person meeting during tutorials


- Weekly reports on team progress


- Coding sessions


According to the needs of the product, we would split into sub-teams and each sub-team will have its own weekly meetings/coding sessions


Coding sessions are held at least once during each iteration and coding reviews are conducted during the session, the coding session also involves reviewing the progress of different features in which team members are responsible for.


#### Artifacts

- Trello


We are using Trello to keep track of different tasks and it’s deadlines
During each team meeting, each sub-team would determine the priority of its tasks according to the project requirements.
Tasks would be assigned to team members during each sub-team meeting

- Iteration Plan


The iteration plan is reviewed in order to reflect on the team’s current progress (whether the team is behind or ahead of schedule).
Depending on the progress of completing the goals in the plan, if the team is ahead of schedule extra features could be considered.



#### Deployment and Github Workflow

The team’s deployment process is streamlined into two phases: local testing and reviews in pull requests.
To be exact the deployment workflow would be as follows:


1. Local testing of a mobile app using emulator/Postman(for the server)


2. Local commits


3. Push to Github fork branch


4. Pull request


5. Other team members review the changes and test the changes (front-end tests front-end changes, back-end tests back-end changes)


6. If problems arise, either push an immediate fix or reject the request


7. If no problems arise merge the pull request.


Since the application consists of a Server and a mobile app they would be tested separately. For Server code changes first, it would be tested locally then pushed to Heroku where the server is hosted. For the mobile app, it would be tested on mobile emulators/installed on Android devices using a debug APK.


## Product

#### Goals and tasks

The Goals are:


1. Finish all of the MVP requirements

2. Finish the add-on features listed below

To specify tasks, we created some user stories:


- User stories for Core features of MVP:

As a resident, I would like to be able to search for events/programs in the St.James Town area (according to events’ names) so that I can get to know what events are happening in my area.

As a resident, I would like to easily reset my password via email so that I can still login in the case that I forgot my password.

As a resident, I would like to be able to scan my library card during login so I can easily login to the app.

 As a resident, I would like to register / login with my library card so that I can indicate my interest in different events.

 As a staff, I would like to see residents’ interest in events so that I can plan ahead based on the headcount of respective events. 


 As a resident/visitor, I would like to use the interactive map to check out the information regarding the buildings on the map,  such as events that will be held in the building. 

-User stories for add on features

 As a resident, I would like to search for events not only by the event’s name but also by time or the location so that I can find an event precisely.
 
 
 As a resident, I would like to log in by scanning the bar code on my library card so that I can log in easily and save the time of typing the long library card number.

 As a staff, I would like to add events via the admin page embedded in the application so I can modify the FileMaker database and Google Calendar simultaneously. 
 (our partner and our team agreed not to implement the admin page even though we have finished the back end part for the admin page)


####  Artifacts


- User Stories: 

allows us to get a precise understanding of the purpose and goals the product is trying to achieve


- Link to similar applications(for interface design): 

allows the partners and the team to get an idea of what the application would look like.


- UML: 

Allows the team to get an overview of the structure of the main application


- Testable modules: 

Allows the team to be able to give constant updates to partners as each module would be fully tested and usable when it is completed. For example, app or apk. In this iteration, we have provided an apk package to present the prototype app.




