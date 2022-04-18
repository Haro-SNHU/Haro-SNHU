# Jonathan Haro ePortfolio

### Table of contents
* [Introduction](#Introduction)
* [Professional Self-Assessment](#Professional-Self-Assessment)
* [Code Review](#Code-Review)
* [Software Design and Engineering Enhancement](#Software-Design-and-Engineering-Enhancementt)
* [Algorithms and Data Structure](#Algorithms-and-Data-Structure)
* [Databases](#Databases)

## Introduction

This ePortfolio is a showcase of projects and enhancements that I completed during my time at Southern New Hampshire University. In the ePortfolio, you will find three artifacts that were enhanced, a code review of these artifacts, and a self-reflection. The enhancements were with three focus areas, Software Design and Engineering, Algorithms and Data Structures, and Databases.

## Professional Self-Assessment

Hello, my name is Jonathan Haro I am a software developer from Chicago. I currently attend SNHU where I am pursuing a degree in computer science. The Southern New Hampshire University computer science program allowed me to gain the necessary skills to pursue a career in software development. The courses I took exposed me to various computers science concepts such as security and best practices, databases, data structures and algorithms, communicating with stakeholders, and collaborating in a team environment. As part of the requirements to complete the degree we were asked to build an ePortfolio that highlights and showcases some of the projects I was able to work on. 

As software developers, we are often part of a team of software developers working together to deliver new software and features. To do so effectively it is important to work on your communication skills and learn important processes such as agile. Important agile concepts are sprints, planning, stand up and requirements gathering. This will not only allow for better communication but also allow for a streamlined process that facilitates a better design, implementation, and deployment of a feature. In addition to agile another important collaborative tool is git. Git is a distributed version control system that allows software developments teams to work on features simultaneously. Important Git features that every developer must know is branch merging, rebasing, squashing, and dealing with conflicts. 

At the core of each successful software implementation, one should find a well-thought-out design. The design should adhere to the given requirements but also follow best practices, contain a security mindset, be maintainable and be performant. In this ePortfolio, I included a Software Design and Engineering Enhancement artifact, for this artifact I chose to implement a feature that allowed the artifact to create an email message and send with an attachment that contained some data collected. To do so I had to take the existing design and modify it to add the new email feature all while improving readability, security, and performance. I also included in this ePortfolio an Algorithms and Data Structure artifact, for this artifact I chose to implement a feature that allowed my artifact to sort and search data more efficiently. Before choosing the binary search tree algorithm I analyzed the different types of sorting algorithms. This allows to me review important concepts such as Big O notation which is a mathematical notation that describes the limiting behavior of a function when the argument tends towards a particular value or infinity. It is what allows software developers to measure the efficiency and performance of the algorithm. Lastly, in this ePortfolio, I included a Database artifact, for this artifact I chose to add a database to an artifact that didn't have one before. This artifact collected data and stored it in a JSON but by doing so the data was not easily accessible to the end-user. By adding a database I was able to use a middleware class that communicated with the database, I also created an interface for the customer to interact with and worked with MongoDB.

Working on this project served as a point of reflection to see how far I have come and served as an opportunity to apply these concepts to artifacts to enhance them and add new features. I hope this ePortoflio showcases my knowledge and proficiency around these core computer science concepts. 


## Code Review

During the course, we were asked to perform an in-depth code review on each project for all enhancements. The code review goes through each of the three artifacts and looks for security flaws and areas for improvements.

<iframe width="560" height="315" src="https://www.youtube.com/embed/TKE2-ZWO3fQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## [Software Design and Engineering Enhancement](https://github.com/Haro-SNHU/WeatherStation)

The name of the artifact is called WeatherStation which was a project I worked on as part of my CS-350 course which covered system architecture. The WeatherStation artifact is an application written in Python that tracks the temperature of a room using RaspberryPi and GrovePi sensors. The application captures the temperature during daytime hours and stores the data which is then displayed on a simple web page.

I choose this artifact because I enjoyed working with embedded systems like the RaspberryPi and GrovePi. Additionally, of all the projects I worked on, I can see this artifact being used in the real world for example it can be used in greenhouses. For my enhancement, I added a way to send the data collected via email. In addition to new email functionality, I refined the code to make sure it follows best practices, such as following proper python variable naming. I also removed unused code and made it more readable, and maintainable. I also made the artifact more secure by adding error handling, closing files, and using constants. This enhancement allowed me to showcase how I can take a working application and redesign it to add new features and improve functionality. Specifically, it showcases my competency with the Python language and familiarity with being able to work with different file types like CSV and JSON. It also showcases how I was able to work with different python libraries and embedded systems.

I enjoyed enhancing this artifact, it had been a while since I worked with a Python application, so it took a while to regain familiarity. I struggled in two areas the first was creating the CSV, the CSVs I was creating were not properly formatted but after a few trials and errors, I was able to create a properly formatted CSV. The second area I struggled with was the email service. I had never worked with an email service before, so I had to learn how to do that. But there were many resources online that helped me figure it out.

## [Algorithms and Data Structure](https://github.com/Haro-SNHU/eBids)

The name of the artifact is eBid_Monthly_Sales which was a project I worked on as part of my CS-260 course which covered algorithms and data structures. The eBid_Monthly_Sales is a C++ application that allows a user to load a CSV and interact with it. They can do simple actions such as the search for bids based on Id, add new bids, display all bids, and delete bids.

I chose this artifact because this application was a perfect vessel to showcase data structures and algorithms. The application calls for sorting and searching through a large amount of data and there are a couple of ways to accomplish this. Therefore, by choosing this application I was able to showcase my understating of data structures and the concept of algorithmic run time by choosing to implement a Binary Search Tree which is O(log n). I improved the artifact by adding new search and sort functionalities based on bid amount using a binary search tree which performs well with a large data set. Additionality, I was able to showcase proficiency in C++.

Working on this artifact was fun and challenging, C++ is the language I have worked with the least, so it took some time to get reacclimated with the syntax. I also had the opportunity to revisit and review different data structures as well as revisit the concept of Big O notation.

## [Databases](https://github.com/Haro-SNHU/WeatherStationDB)

The name of the artifact is called WeatherStation which was a project I worked on as part of my CS-350 course which covered system architecture. The WeatherStation artifact is an application written in Python that tracks the temperature of a room using RaspberryPi and GrovePi sensors. The application captures the temperature during daytime hours and stores the data in a JSON file which is then displayed on a simple web page.

I choose this artifact because as part of this application the data being collected is stored in a JSON file. However, it would be more practical to store the data in a database. This makes the data more accessible by allowing the ability to create an interface with the database, therefore, making the data to be interactive. For my enhancement of this artifact, I added a mongo database to store the data and an interface to show the data via an interactive table. This showcases my ability to create applications with databases as well as my ability to create simple web pages that allow users to interact with the data from the database. Additionally, I also implemented dependency injection to keep passwords and other sensitive data from being stored in plain text.

Working on this artifact allowed me to work on a mongo database which I had not worked on for a while. I also got to work with a new framework “Streamlit” which is a library that allows you to build and ship applications. It was a challenge having to learn this new framework but it was worth it as it not only did the job but I can see myself using this library again in the future.
