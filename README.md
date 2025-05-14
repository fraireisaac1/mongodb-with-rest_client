# Setting up a MongoDB connection

## Node dependency list

```bash
npm i express dotenv mongodb
```

## chmod command

```bash
chmod +x find_documents.sh
```

## find ip address command

```bash
curl ifconfig.me
```

```bash
 ipconfig | grep IPv4
   IPv4 Address. . . . . . . . . . . :x.x.x.x

```

## Grocery Database
This was originally a repository that us West-Mec students forked so that we could begin learning about databases in the second year of our program. This was our first instance of learning about data storage and the CRUD operators especially. After some time, the instructor opted to make the repository into an assignment grade, and instead of just being a template, this repository became an individual project for each studetn. We ended up dubbing it the Grocery Database since the data entries we inputted into the database were all themed around different groceries, such as vegetables and canned foods, for instance.

## Purpose
The purpose of this project was for the West-Mec students to first learn about databases for the first time. In specific, we were studying the CRUD operators, and how they interact with the data in the databases. We used the GET, POST, PUT, and DELETE requests in this project to see how we could alter existing sets of data in this project. We worked on it for a few weeks to study and prepare for upcoming quizes based around the CRUD operators, so the code was solid and refined enough by the end for us to use the same template for future database projects that used Express.

## Technologies Used and Why
* JavaScript: Like most other projects we made around this time, we were still working in JavaScript so that we'd have enough know-how of the language and its intricacies to pass the certification exam at the end of the year. In a way, this project, like many others around this time, was almost like study material for that exam. Not only that, but JavaScript suited the purposes of the site perfectly with how the CRUD operators worked within it along with Express and the try catch blocks for error handling.
* Node.js: Yet again just our primary method of executing JavaScript code from outside of a web browser. We used many Node.js command lines to run the project and import necessary dependencies.
* Express.js: This technology enabled the CRUD operators to be completely functional within the project, as well as it was used to retrieve the data we were storing in MongoDB.
* MongoDB: While initially we only stored data in .json files within the project, we'd worked on the project for so long that the instructor thought it apt that we learn how to use MongoDB alongside the development of this project. MongoDB was used to store the databases we created for this project in something other than our small .json files. After learning about MongoDB from this project, we knew enough about it to implement it into further projects.
