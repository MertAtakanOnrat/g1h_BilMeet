# CS102 ~ Design Project ~ Spring 2019/20
****
## g1H ~~ BilMeet ~~
****
### ~ MeetTheNeeds ~

## Project Description
People can sometimes have problems with socializing. This situation can be very annoying, especially for university students. With this 
application, we aim to get used to people who are shy and cannot make many friends. Moreover, enabling people to easily find places where 
the activities they attend or to organize events easily.

## Project Status
+ **Group/project Selection:** completed (16.02.2020)
+ **Requirements:** completed (23.02.2020)
+ **UI Design:** completed (15.03.2020)
+ **Detailed Design:** completed (21.05.2020)
+ **Implementation:** completed (28.05.2020)
+ **Reflections:** completed (28.05.2020)

## What Has Been Done and What Has Been Remained
When we login to the application, it opens with the login screen. The user can register without any problem and can login to the application 
after confirming it from bilkent mail. As long as we do not log out after logging into the application, the last user in the application 
remains open. After logging into the application, the map screen opens. We can add pins to our map, which we add as pictures. Then we can 
list the events created when the pin is clicked. However, when we make the pins open, we cannot use the zoom feature. In the Create an event 
section, we can select and write the features we want. However, when we press the save button, we return to the main screen. The pins we 
added in the Middle and East map section do not open, but the pictures can be zoomed. When we enter the profile section, user features do 
not appear because we do not add user profiles to the database. All users have the same features. However, these features can be changed in 
Settings. Even if you quit the application and re-enter, the changed and newly entered properties are saved. There are no adding friends or 
sending messages from the user profile. Then, after the changes we made in the code, we started to get an error in the user reporting 
section. However, he had a photograph working on github. In addition, we did not make the chat part that we thought of in addition. Finally, 
we can list the events we wrote on the event page. We can choose when we click the Filter button, but the filtering process does not work. 
In addition, our application size does not work for all devices. We tried the test part only for nexus 5.

#### Group Members
- Mert Atakan Onrat 
- Tuğberk Dikmen 
- Oğulcan Karakollukçu 
- Ahmet Faruk Ulutaş 
- Bartu Teber 

## Details About the Project
We used the current version of Android studio. (3.6.3) We also used firebase for the database part. (17.4.2) We also used github to store and continue our project. (2.20.8) In order to provide various features in our project (zooming, panning and pinning) we used davemorrissey's github library. (https://github.com/davemorrissey/subsampling-scale-image-view) (3.10.0) In order to test, we download the project as github, unzip it and select the file we extracted from android studio by saying open file / project. . Waiting for a while after choosing, android studio automatically compiles and prepares the project. Then we can run the application with Nexus 5 API 25.
