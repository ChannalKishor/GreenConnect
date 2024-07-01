
GreenConnect
Welcome to GreenConnect! This platform is your one-stop hub for creating and managing events, fundraisers, petitions, and sharing your eco-friendly actions. Join us in reducing our carbon footprint and fostering environmental awareness.

Project Overview
GreenConnect is built to empower individuals and communities to take collective action in protecting our environment. Share your sustainability efforts, engage with like-minded individuals, and contribute to a greener planet.

This project was generated with Angular CLI version 8.3.3.

Motivation
Protecting the environment is not just a trend; it's a necessity. Our mission with GreenConnect is to create a platform where environmental consciousness is celebrated, shared, and amplified. Let's work together to make sustainability a priority in our lives and society.

Technology Stack
Frontend: Angular 8
Backend: Express.js, Node.js
Database: MongoDB
Styling: SASS, CSS, Bootstrap, Angular Material, Google Material Icons
Authentication: Auth0 with JWT tokens (RS256 algorithm, OIDC specifications)
External APIs: Google Maps (Event Location), Flutterwave (Payments via Angular Rave), Air Quality Info, News API (Blogs)
Features
Live Air Quality Index: Stay updated with real-time air quality data on the home page.
Climate Change Blogs: Read and share articles related to climate change and sustainability.
Event Management: Create, manage, and attend eco-friendly events.
Fundraising: Launch and contribute to fundraisers supporting environmental causes.
Carbon Footprint Activities: Share and inspire others with your eco-friendly activities.
Petitions: Start, manage, and sign petitions for environmental advocacy.


API Endpoints
Events

 - GET: /v1/greenconnect/events 
 - POST: /v1/greenconnect/events 
 - GET:/v1/greenconnect/events/:id 
 - PUT: /v1/greenconnect/events/:id 
 - DELETE:/v1/greenconnect/events/:id

Attendees

 - GET: /v1/greenconnect/attendees 
 - POST: /v1/greenconnect/attendees 
 - GET: /v1/greenconnect/attendees/:id 
 - PUT: /v1/greenconnect/attendees/:id
 - DELETE: /v1/greenconnect/attendees/:id

Fundraisers

 - GET: /v1/greenconnect/fundraisers 
 - POST: /v1/greenconnect/fundraisers
 - GET: /v1/greenconnect/fundraisers/:id 
 - PUT: /v1/greenconnect/fundraisers/:id 
 - DELETE: /v1/greenconnect/fundraisers/:id

Donations

 - GET: /v1/greenconnect/donations 
 - POST: /v1/greenconnect/donations

Social Feeds

 - GET: /v1/greenconnect/socialfeeds 
 - POST: /v1/greenconnect/socialfeeds
 - GET: /v1/greenconnect/socialfeeds/:id 
 - PUT: /v1/greenconnect/socialfeeds/:id 
 - DELETE: /v1/greenconnect/socialfeeds/:id

Petitions

 - GET: /petitions 
 - POST: /petitions 
 - PUT: /petitions/:id 
 - DELETE: /petitions/:id 
 - GET: /petitions/:id 
 - GET: /petitions/:emailId

Signatures

 - GET: /signature 
 - POST: /signature 
 - GET: /signature/:petitionId 
 - GET: /signature/:emailId GET: /signature/count/:emailId

Running the App
Prerequisites
MongoDB installed
Node.js and Angular CLI installed

Steps
Install dependencies: Run npm install in both the frontend and backend folders.
Start backend server: In the backend folder, run node server.js.
Start frontend server: In the frontend folder, run ng serve and navigate to http://localhost:4200/. The app will automatically reload if you change any source files.
Build
To build the project, run ng build. The build artifacts will be stored in the dist/ directory. Use the --prod flag for a production build.
