# unit-7-project-week-rollout

## Purpose

The main purpose of this project is to practice building a CRUD Express app (PostgreSQL database, Node.js + Express.js Server, Knex.js) with a front-end for interacting with the app.

## Requirements

**If you are working in a pair**, your app's Minimum Viable Product (MVP) is expected to have:

- At least 3 tables in your app's database
- At least 1 many-to-many relationship in your app. 

**If you working alone**, your app's Minimum Viable Product (MVP) is expected to have

- At least 2 tables in your app's database
- At least 1 one-to-many or many-to-many relationship in your relationship.

**Every group must have:**
- An Entity-Relationship Diagram (ERD) accurately illustrating your final app's data architecture (schema)
First Draft during planning, Final Draft for presentation
- A wireframe (hand-drawn is fine) illustrating the key interactable components in your UI (anything that triggers a fetch) 
- A demo + presentation slides to showcase your project

## Project Ideas
There any many simple app ideas that would fit nicely into these requirements. For example, a Personal To Do List would have a Users table and a ToDos table. A user would be able to create an account, sign in, and keep track of their ToDos. However, so many bootcamp students build a basic To Do List as part of their portfolio.

So, it is perfectly acceptable (and even encouraged) to build a clone of an existing app. Here are some ideas:

#### Group Project Ideas

- AirBnb (Users, Listings, Bookings)
- Instagram (Users, Posts, Comments)
- Twitter (Users, Tweets, Likes)
- Uber (Riders, Rides, Drivers)
- Blogging App (Users, Blogs, Comments)
- Healthcare App (Patients, Appointments, Doctors)
- Social Network (Users, Connections) 

#### Solo Project Ideas

- Personal Blogging Site (Users, Blogs)
- Personal Photo Gallery (Users, Photos)
- Fitness Tracker (Users, Workouts)
- Nutrition Tracker (Users, FoodItems)
- Simple Video Game (Users, Scores)

## Deliverables

1. Project Idea
2. ERD
3. GitHub repo with committed Knex migration and seed files
4. GitHub repo with committed CRUD-capable model
5. GitHub repo with committed Express server that responds 'Hello World' to 'GET /' requests
6. GitHub repo with committed controllers as route handlers to interact with the model for GET, POST, PATCH, and DELETE requests
7. Wireframe (hand drawn is fine) of essential front end components along with descriptions of components that trigger fetch requests (include the url, request method type, and any related body data)
8. GitHub repo with committed HTML/JS including elements that trigger fetch requests
9. GitHub repo with committed CSS styling
10. Project demo with presentation

## Partners

For this project, **you will be able to choose your partner** or **you may choose to do this project alone**. Let your instructor know once you have found a partner to receive your first assignment which you may begin working on immediately. 

Keep in mind, you are still responsible for your individual assignments. If an individual Unit 7 assignment is past-due, project work must be halted until late assignments are turned in. 

Do you accept this challenge?

## Bonus Content

So, you've carefully designed a schema for your database, you've build a CRUD-capable Express API and a simple UI for interacting with it, and now you're looking for more?

Consider these ways of extending your project
* Look into [Socket.io](https://socket.io/) and build out a chat feature for your application.
* Add secure Auth using [bcrypt](https://www.npmjs.com/package/bcrypt) and [jwt](https://jwt.io/)
