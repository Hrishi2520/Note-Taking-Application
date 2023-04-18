#Note-Taking-Application

<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 2; ALERTS: 21.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>
<a href="#gdcalert14">alert14</a>
<a href="#gdcalert15">alert15</a>
<a href="#gdcalert16">alert16</a>
<a href="#gdcalert17">alert17</a>
<a href="#gdcalert18">alert18</a>
<a href="#gdcalert19">alert19</a>
<a href="#gdcalert20">alert20</a>
<a href="#gdcalert21">alert21</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



    Project Report on


    **“Note Taking Application”**


    Submitted in partial fulfillment of the requirement for the award of the degree of


    **Master of Science (Computer Science)**


    ACADEMIC YEAR 2022-2023


    By


        **Hrishikesh Rajendra Shedge**


                **Roll No: 228974**


    Under The Guidance Of


    **Dr. Manisha Abhyankar**


    Department Of Computer Science


                        Rayat Shikshan Sanstha's


    Karmaveer Bhaurao Patil College, Vashi (Autonomous)


            Accredited by NAAC with Grade A+(CGPA 3.53) | ISO 9001:2015 certified institute PKC Road,Sec.15-A Juhu Nagar , Vashi Navi Mumbai


                        Maharashtra – 40703


                        

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.jpg "image_tooltip")



    Rayat Shikshan Sanstha's


    Karmaveer Bhaurao Patil College, Vashi (Autonomous)


    Accredited by NAAC with Grade A+(CGPA 3.53) | ISO 9001:2015 certified institute


            PKC Road,Sec.15-A Juhu Nagar , Vashi Navi Mumbai Maharashtra - 400703


    **<span style="text-decoration:underline;">CERTIFICATE</span>**


    This is to certify that the work contained in this project report entitled


# 
    "Note Taking Application "


    submitted by


    **"Hrishikesh R Shedge" Roll No: "228974”**


    In partial fulfillment of the M.Sc(Computer Science) Degree **Semester IV **Examination in the academic year **2022-2023 **to the Karmaveer Bhaurao Patil College, Navi Mumbai and has not been submitted for any other examination and does not form part of any other course undergone by the candidate. It is further certified that he/she has completed all the required phases of the Project.


    External Examiner	Internal Examiner

<p style="text-align: right">
Project Guide</p>



                                        

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline drawings not supported directly from Docs. You may want to copy the inline drawing to a standalone drawing and export by reference. See <a href="https://github.com/evbacher/gd2md-html/wiki/Google-Drawings-by-reference">Google Drawings by reference</a> for details. The img URL below is a placeholder. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![drawing](https://docs.google.com/drawings/d/12345/export/png)


    Head of Department	Principal


# Acknowledgement


    I have taken efforts in this project research. It would not have been possible without the kind support and help of many individuals and organizations. I would like to express my sincere gratitude to the people who helped me in completing the project. I heartily thank my project guide, Dr. Manisha Abhyankar, for her valuable guidance, co-operation, encouragement and time spent for this project work. I also thank her for showing faith in me throughout the course of the project. I extend my sincere thanks to the principal of our college and all faculty members of MSc Computer Science department who tuned my knowledge in the field of Computer Science. I am also grateful to my family members for constantly supporting me and all those who guided me directly or indirectly during my project, encouraging me to put my best efforts for continual improvement of the project


# 
    Abstract

This project involves the development of a note-taking application using Java, SpringBoot, MySQL database, ThymeLeaf and Docker. The application will allow users to signup a new user and login the user. User can create, add, update, and delete notes.The main objective of the project is to provide a scalable, secure, and reliable platform for organizing and managing notes.The application will leverage various Java libraries, SpringBoot features, and MySQL database capabilities to ensure efficient data storage, retrieval, and management. Additionally, the application will be deployed using Docker, which will enable seamless containerization and deployment across multiple environments.

The development process will involve several stages, including requirement gathering, design, implementation, testing, and deployment. During the implementation stage, the team will utilize the Model-View-Controller (MVC) architecture pattern, which will allow for the separation of concerns and ease of maintenance.


# The final product will be a high-quality, user-friendly, and efficient note-taking application that is easy to deploy and use across various platforms.


# 
    


# 
    Index



1. **Acknowledgement**
2. **Abstract**
3. **Introduction	**
1. About Note taking Application
2. Functions
4. **Requirement Analysis**
1. Functional Requirements
2. Operational Requirements
3. Technical Requirements
5. **Project Implementation**
6. **Technology used**
7. **Source Code**
8. **Future Scope**
9. **Conclusion**
10. **Reference**

# 
    Introduction



## About Note taking Application

Note-taking is an important activity for many individuals and organizations, and digital technologies have made it more accessible and efficient than ever before. In this project, we developed a note-taking application using Java, SpringBoot, MySQL database, Docker, Spring Security, and Thymeleaf.

The application allows users to create, update, and delete notes. We leveraged the power of SpringBoot, a popular Java-based framework for building web applications, to develop a scalable and efficient application. To ensure efficient data storage and retrieval, we utilized MySQL, a robust open-source relational database management system.

We also deployed the application using Docker, which enabled us to containerize and deploy the application across various platforms seamlessly. This ensured that the application was easy to deploy and maintain, reducing operational costs.

To provide a secure experience for users, we integrated Spring Security, a powerful framework for authentication and authorization in Java applications. This allowed us to provide a secure login and signup process for users, ensuring the confidentiality and integrity of their data.

To develop the frontend of the application, we utilized Thymeleaf, a modern server-side Java template engine. This enabled us to build dynamic and interactive user interfaces that were easy to maintain.

Throughout the development process, we followed the Model-View-Controller (MVC) architecture pattern, which allowed for the separation of concerns and ease of maintenance. The resulting application is scalable, efficient, and user-friendly, providing a valuable tool for individuals and organizations that need to manage large volumes of notes efficiently.** **yes, head, and face.


## Functions

	Users should be able to register and create an account to access the application. They should be able to log in to the application using their credentials.** \
**Users Should Edit the Profile Information.Users should be able to create new notes, with the ability to add a title and description for each note. \
Users should be able to view a list of all their notes, along with the date and time they were created. \
Users should be able to edit the title and description of their existing notes.Users should be able to delete notes that they no longer need.

Users Should be Able to logout.


# 
                Requirement Analysis


## 1.Functional Requirements

**User Registration and Login:** 

	Users should be able to register and create an account to access the application. They should be able to log in to the application using their credentials.

**Edit Profile: **

**	**Users Should Edit the Profile Information.

**Note Creation:** 

	Users should be able to create new notes, with the ability to add a title and description for each note.

**Note Listing:** 

	Users should be able to view a list of all their notes, along with the date and time they were created.

**Note Editing:** 

	Users should be able to edit the title and description of their existing notes.

**Note Deletion:** 

	Users should be able to delete notes that they no longer need.

**User Logout:**

	Users Should be Able to logout.


## 2. Operational Requirements

**Availability:** The application should be available for use 24/7 without any downtime or service interruptions.

**Scalability:** The application should be able to handle a large number of users and notes without any performance degradation.

**Performance:** The application should respond quickly to user requests and should be able to handle a large number of concurrent requests.

**Reliability:** The application should be reliable and should not lose any user data due to system failure or other issues.

**Security:** The application should be secure and should protect user data from unauthorized access or malicious attacks.

**Compatibility:** The application should be compatible with different web browsers, operating systems, and devices.

**Upgrades and Updates:** The application should be upgradable and should support new features and functionality as they become available.

**Performance Testing:** The application should be tested for performance to ensure that it can handle a large number of users and notes.


## 


## 3.Technical Requirements

Here are some technical requirements for a note taking application built using Spring Boot and Thymeleaf:

**Programming Language:** The application should be written in Java.

**Framework:** The application should be built using the Spring Boot framework, which provides a comprehensive set of tools and features for building robust web applications.

**User Interface:** The application should use Thymeleaf, which is a popular templating engine for building dynamic web pages.

**Database:** The application should use a relational database such as MySQL or PostgreSQL to store user data.

**Object-Relational Mapping (ORM):** The application should use an ORM framework such as Hibernate to interact with the database.

**Authentication and Authorization:** The application should use Spring Security for user authentication and authorization.

**RESTful API:** The application should expose a RESTful API for accessing and manipulating user data.

**Testing:** The application should be thoroughly tested using automated testing tools such as JUnit and Mockito.

**Version Control:** The application should use a version control system such as Git to manage source code changes.

**Deployment: **The application should be deployed on a web server such as Tomcat or Jetty.

**Code Quality:** The application code should adhere to best practices and coding standards to ensure maintainability and scalability.

**Security:** The application should be designed with security in mind and should follow best practices for securing web applications


# Project Implementation


## 1.Project Structure



<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



## 2.Edit Configuration



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



## 3.Docker Compose File



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



## 4.Go to Above file Path

** \
**

<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")





## 5.run docker compose up -d

**It will run the mysql database image in container**



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")



## 6. Running Project



<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")



## 7. UI

**open the browser and  type “localhost:8080” and click.**


## 


## 8.HomePage



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.png "image_tooltip")



## 9.Sign up



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.png "image_tooltip")



## 


## 10.login



<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.png "image_tooltip")



## 11.create account if user not sign up



<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")



## 


## 12.add note



<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")
** **


## 12.Search Note



<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")





## 13. Edit Note



<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")



## 14.Delete Note



<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")



## 15. User Profile



<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image16.png "image_tooltip")



## 16.Docker compose Down



<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image17.png "image_tooltip")



## 


## 17. Checking Container Status



<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image18.png "image_tooltip")



## 18. Stop the Application



<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image19.png "image_tooltip")



## 16. Logout



<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image20.png "image_tooltip")



# 
                Technologies Used

**PROGRAMMING LANGUAGE: JAVA**



* **JDK:**	JDK 1.8
* **IDE:** Intellij
* **FrameWork:** Spring Boot
* **Server:** TomCat Server
* **OPERATING SYSTEM:** Windows or LINUX both are supported
* **DataBase:** Mysql
* **FrontEnd:** ThymeLeaf
* **Other:** Doker


# Source Code

##enotes

### [config](https://github.com/Hrishi2520/Note-Taking-Application/tree/main/src/main/java/com/enotes/config)

### [controller](https://github.com/Hrishi2520/Note-Taking-Application/tree/main/src/main/java/com/enotes/controller)

### [entity](https://github.com/Hrishi2520/Note-Taking-Application/tree/main/src/main/java/com/enotes/entity)

### [repository](https://github.com/Hrishi2520/Note-Taking-Application/tree/main/src/main/java/com/enotes/repository)

##resources

### [static](https://github.com/Hrishi2520/Note-Taking-Application/tree/main/src/main/resources/static)

### [templates](https://github.com/Hrishi2520/Note-Taking-Application/tree/main/src/main/resources/templates)

### [docker-compose.yml](https://github.com/Hrishi2520/Note-Taking-Application/blob/main/src/main/resources/docker-compose.yml)

### [application.properties](https://github.com/Hrishi2520/Note-Taking-Application/blob/main/src/main/resources/application.properties)

# Future Scope

The future scope of a note taking application built using Spring Boot and Thymeleaf can be vast and diverse. Here are some potential areas where the application could be improved and expanded:

**Mobile App:** A mobile application can be developed to provide users with easy access to their notes on their mobile devices. This can be done by creating a mobile app that integrates with the web application.

**Collaboration: **Adding collaboration features such as the ability to share notes and work together on notes can be a valuable addition to the application.

**Integration with other Applications:** The application can be integrated with other applications such as Google Drive, Dropbox, and other cloud storage providers. This can help users easily store and access their notes from different devices.

**Artificial Intelligence:** The application can be enhanced with artificial intelligence to provide users with intelligent note-taking capabilities such as automatic summarization, categorization, and tagging of notes.

**Voice Recognition:** Incorporating voice recognition technology can provide users with the ability to create notes hands-free.

**Multi-language Support:** Adding support for different languages can help users from different regions access the application with ease.

**Machine Learning:** Machine learning can be used to provide users with personalized recommendations based on their note-taking history.

**Analytics: **Adding analytics capabilities to the application can provide insights into user behavior, such as the most commonly used features and the most popular notes.

**Offline Access:** Providing offline access to the application can help users access their notes even when they don't have an internet connection.

**Conclusion**

In conclusion, building a note taking application using Spring Boot and Thymeleaf with Spring Security and Docker can be a great choice for developers who are looking for a robust, efficient, and scalable way to create a secure web application. By using these technologies together, developers can create a powerful application that provides a seamless user experience and can be easily deployed on any platform.

Spring Boot provides an efficient way to build web applications, while Thymeleaf allows developers to create dynamic web pages with ease. Spring Security provides a robust and flexible security model that can be easily integrated with Spring Boot applications, and Docker makes it easy to package and deploy applications on any platform.

By combining these technologies, developers can create a highly functional note taking application that is secure, scalable, and easy to deploy. With the help of the right resources and references, developers can get started with building a note taking application using Spring Boot and Thymeleaf with Spring Security and Docker.


# 
                        Reference



1. Building a Note Taking App with React and Firebase: [https://scotch.io/tutorials/build-a-note-taking-app-with-react-and-firebase](https://scotch.io/tutorials/build-a-note-taking-app-with-react-and-firebase)
2. Building a Note Taking App with Vue.js and Firebase: [https://scotch.io/tutorials/build-a-note-taking-app-with-vue-js-and-firebase](https://scotch.io/tutorials/build-a-note-taking-app-with-vue-js-and-firebase)
3. Building a Note Taking App with Angular and Firebase: [https://fireship.io/lessons/building-a-note-taking-app-with-angular-and-firebase/](https://fireship.io/lessons/building-a-note-taking-app-with-angular-and-firebase/)
4. Building a Note Taking App with Node.js and Express: [https://codeburst.io/build-a-note-taking-app-with-node-js-express-mongodb-and-vue-js-6674fefe8ce](https://codeburst.io/build-a-note-taking-app-with-node-js-express-mongodb-and-vue-js-6674fefe8cea)
5. Building a Note Taking App with Django: [https://realpython.com/build-a-note-taking-app-with-django/](https://realpython.com/build-a-note-taking-app-with-django/)
6. Building a Note Taking App with Flutter: [https://medium.com/flutter-community/building-a-note-taking-app-in-flutter-part-1-4dcdd4e6cddb](https://medium.com/flutter-community/building-a-note-taking-app-in-flutter-part-1-4dcdd4e6cddb)
7. Building a Note Taking App with Kotlin and Android Studio: [https://www.raywenderlich.com/5113993-building-a-note-taking-app-for-android-with-kotlin](https://www.raywenderlich.com/5113993-building-a-note-taking-app-for-android-with-kotlin)
8. Building a Note Taking App with React Native: [https://reactnative.dev/docs/tutorial](https://reactnative.dev/docs/tutorial)