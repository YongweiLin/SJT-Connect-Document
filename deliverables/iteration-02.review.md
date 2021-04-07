# SJT Connect (St James Town Connect)

## Iteration 2

Time: During Tutorial,3/7/2019


Location: BA1170


## Process - Reflection

Overall this iteration turned out well as the team accomplished most of its planned goals. Communication between each sub-team was adequate and the helpful culture within the team was strong throughout the iteration.

#### Decisions that turned out well

- Setting up Firebase Database instead of using FileMaker


During the meeting with the partner, we were given the option to utilize the FileMaker database that the partner is currently using. However for the team to create new fields in the database it would require manually asking the partner to add the fields in, vice versa for adding data. This would create a lot of overhead and slow down the development cycle tremendously. Furthermore, FileMaker is a paid service and none of the team members were familiar with it. As a result, the team elected to go with Firebase Database to store the data for the app and it has eased up the development process tremendously.


- Direct commits to repo were done instead of pull requests.


Given the short development time frame and considering team members would not be available at all times due to other responsibilities (school/work), the development process would need to be sped up. As a result, members were allowed to push directly to the repo instead of waiting for another member to review then merge the pull request, which might take a lot of time since team members were usually busy during February (midterms, work, away from the city during reading week .etc)

#### Decisions that did not turn out as well as we hoped

- Splitting up roles for the front-end too early


Although the team did a good job in terms of job distribution the split was done before a general UI style was finalized. This results in a lot of unnecessary modifications to each individual pages as members have to revamp their page designs to achieve a coherent style in the app.


- Using messenger purely for communication


While using messenger solves the problem of not having to force other members to set up a Slack account/other social media in order to communicate, it means that we could not utilize the extra features Slack offers. For example, in Slack, we could register the team repo with the team Slack channel so that when the repo is updated everyone in the channel would be notified and they can pull the request. Members would also be allowed to post code snippets easily(instead of doing screenshots) during the debugging process

#### Planned changes

We used to have 4 people in the front-end team and 3 people in the back-end team. Since there is one back-end team member dropped the course, some of the front-end team members will also help develop the back end in the next iteration.



## Product - Review

#### Goals and tasks completed:

We have built an event list page that can fetch events from the google calendar and display as a list. There is a search bar on the top of the event list so that specific events can be searched by name. In our prototype App, for now, the event list page renders at most 20 events for demo purpose. In fact, users are able to search for any event held after 2019, March,1. by the event’ name.  


For residents, after they have logged in, they can click on the event they are interested in, navigate to the event details page and register for an event.
For staff, they will be able to see the number of people that will attend the event in the event details page.



We have built an interactive map for the St James Town area so that residents/visitors can click on the buildings on the map and receive information regarding these buildings.



#### Goals and tasks planned but not completed:

For the interactive map, the only thing we haven’t finished is the part of displaying events in a building if users click on this building on the interactive map. Knowing that one of the add-on feature, which is searching for events based on time or location in the event list page, is very similar to getting events in a building on the interactive map. We decided to move this part to D3 so that we can keep all component consistent and reduce as much redundancy as possible.


For the login/ register page. We have finished a functioning login /register page. However, due to the privacy issue, our project partner did not give us access to their residents/staff database. We will wait for further instruction from our project partner if they change their mind about the residents/staff database. Otherwise, the login/register part will be considered done since our team has completed what we are able to implement.

A settings page was planned but since the features at the moment did not require any specific user settings the page was commented out. However a language selector was in development and could be added to the settings page in the future.


## Meeting Highlights

#### What we need to improve:


First of all, pull requests should be reinforced.

Secondly, more communication is needed between Back-End and Front-End teams.

We also need a more direct approach taken towards the partner when discussing the possible features for the app (let the partner know whether a feature is feasible or not).

#### In the next iteration, our top priorities are:


The first goal is to add the admin page let allows the Staff to monitor the app and also modify the FileMaker database and Google Calendar simultaneously.

The other one is to finish the function of searching for events by time and location/building
