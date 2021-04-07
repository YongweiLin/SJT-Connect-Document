# SJT Connect

## Iteration 3

 Time: During Tutorial, 3/28/2019
 
 
 Location: BA1170


#### Process - Reflection

Overall this iteration turned out well as the team accomplished most of its planned goals. Communication between each sub-team was adequate and the helpful culture within the team was strong throughout the iteration.


#### Decisions that turned out well


- Continued using direct commits rather than pull requests


As noted in the previous iteration documents, we elected to perform direct commits to the repository rather than doing pull requests. Although the team considered reverting to the original plan on reinforcing pull requests. This proved to have improved team efficiency as it allowed team members to update the code base quickly, without having to worry about the pull request not being reviewed and tested in time. 



This can be supported by the data (for the last month) provided by Github:
	
	
	

	“Excluding merges, 8 authors have pushed 242 commits to master 
	and 245 commits to all branches. On the master, 104 files have 
	changed and there have been 4,459 additions and 15,597 deletions.”





Considering the tight development timeframe and teams members’ other responsibilities (work, other school projects, etc.), it can be seen that our team’s efficiency would have been slowed down tremendously (fewer changes would have been made) if pull requests were made. Although it is not good practice such improvision made the development process much simpler and efficient.


- Not implementing the admin page


(Note: Admin page is not part of the MVP requirements)
	As mentioned above, as we were not given direct access to the Filemaker database and Google Calendar, it is difficult for us to implement an admin page, for which the partner wanted in order to manage their events. Considering the short iteration duration and the project nearing the end of its development the partner and our team agreed not to implement this feature and focused on polishing existing features. This decision turns out working well for the team as we made sure that all of our features were bug-free and fully completed and the partner was satisfied with the current state of the app.
 
#### Decisions that did not turn out as well as we hoped

- Splitting up roles for the front-end too early


Although the team did a good job in terms of job distribution the split was done before a general UI style was finalized. This results in a lot of unnecessary modifications to each individual pages as members have to revamp their page designs to achieve a coherent style in the app.

- Using messenger purely for communication


While using messenger solves the problem of not having to force other members to set up a Slack account/other social media in order to communicate, it means that we could not utilize the extra features Slack offers. For example, in Slack, we could register the team repo with the team Slack channel so that when the repo is updated everyone in the channel would be notified and they can pull the request. Members would also be allowed to post code snippets easily(instead of doing screenshots) during the debugging process 

#### Planned changes


Other then what we have decided to change from the previous iteration, which we have clearly stated in iteration-03.plan.md, there are no planned changed within this iteration.


## Product - Review

#### Goals and tasks completed:


We have completed and tested all the main features that the partner requested to be in the MVP of the app. All completed parts are fully functional and bug-free. In addition to the MVP features, as requested by the partner, we also implemented a barcode scanner for the login section, allowing the user to scan their library card (which is used as the username for login) to login into the SJT Connect app. The password reset system has also been implemented, in which users can choose the reset password option with their library card and a password reset email will be sent to the email associated with the account. The user can then receive an auto-generated new password to login to their account again and set a new password.



#### Goals and tasks planned but not completed:

The partner wanted an admin page to be added to the app. The admin page would be used to monitor users and to add events to the google calendar and the Filemaker database (which the partner stores its events). However, as we are not given access to the Filemaker database (due to privacy issues) the function was not implemented. Despite this to accommodate future development we have implemented a function on the server to support adding events to the partner’s google calendar.


Initially, a plan was made to migrate all building info to the partner’s Filemaker database to avoid hard-coding all data into the app’s interactive map. However, as the partner do not have time to enter the building info into the database the building info will still be stored in the app instead of being pulled from the server dynamically. Moreover, all buildings are being displayed with a default image as the partner was not able to provide the team with actual images of the buildings


## Meeting Highlights

#### Things we need to improve:
-  More communication needed between Back-End and Front-End teams
-  More direct approaches should be taken towards the partner when discussing possible features for the app




   We should let the partner know whether a feature is feasible or not as soon as possible so that requirements can be finalized earlier.

#### In the next iteration, our top priorities are:

- Provide support to the partner in terms of maintenance of the app

- Further documentation to help the future team which will take over the codebase of the app







