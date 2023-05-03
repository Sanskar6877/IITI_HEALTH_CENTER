
**Team Members**

1\.Velpuru Navya ([210001075)](mailto:cse210001063@iiti.ac.in)

2\.Sanskar ([210001063)](mailto:cse210001063@iiti.ac.in)

3\.Vishesh Garg ([210001077)](mailto:cse210001063@iiti.ac.in)

4\.Pranay D Kumar ([210001053)](mailto:cse210001063@iiti.ac.in)

5\.Vikas Maurya ([210001076)](mailto:cse210001063@iiti.ac.in)

**Description**

The <a name="_int_njrdjofi"></a>Health Centre appointment system allows patients to enquire about availability of doctors based on their schedule, book and cancel appointments. The goal of this case study is to design and develop a database that stores information about various doctors and patients. Patients may book their appointment by entering the details. If there are any doctors available, they will be allotted accordingly by the admin. Following that, the admin can cancel any appointment depending upon the situation.




**Templates**

This folder contains all the Express-js file along with their stylings. In total, there are 74 Ejs files with some Html files which comprise of login, register, book appointment, cancel appointments, patient history, feedback, contact us, about us, add doctors and informative pages for awareness.




**Compass Connections**

This is the mongodb connections for the entire project. This is made using mongo dB and node js.Mongo dB is used database and node Js implemented Api. The database consists of 11 collections(tables).




**UML**

This folder also contains activity diagram, class diagram, sequence diagram, use case diagram, state diagram which shows the activities involved in a process of booking appointments, cancelling appointments, adding doctors and reviewing feedback.

**SRS**

This file contains all the requirement specified before starting the project.

**How to use the website**

Create a database with the above mongo dB code, then download all the Express Js(ejs) files from the **views, NodeJs** (Js) files from **routes**  folder and the backend folder. Make sure you have downloaded all the nodemodules and all the modules mentioned in package.json file.Try to create a app.js file and index.js file outside the routes and views folder. Then run the login1.js file of Routes folder on the terminal. When you run the program, you will be directed to the homepage, where you may login as user, admin, doctor. To login, click the Login button, where you will be asked to provide the required details. After successfully signing, you will be directed to the dashboard. Then, user may book his appointment based on his availability by entering the required details. After successfully booking an appointment, an automated message will be sent to the registered email address. user may also give feedback in the reviews tab. In case, the admin wants to add doctor or add user he can do that. The admin can accept or delete the requested appointment and allot timings to the user. Admin sends email to all the user regarding updates on doctors' availability. Doctor can see the allotted patient to him and check the patient history also.
