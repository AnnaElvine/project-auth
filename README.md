# Project Auth API

For this project, we needed to create a backend and a frontend. For the backend we had to create an API with routes to register and login, as well as an authenticated endpoint, that needed an access token. For the frontend we needed to create a registration form to allow POSTing to the API to create a new user. Passwords in the database needed to be encrypted with bcrypt and the API had to validate the user input when creating a new user. 

## The problem

We began by coding along to the live sessions to get all the routes to work - so that a user could register and log in and see ‘thoughts’ that had been added to the database via Postman. We then decided to add an input field so that a logged-in user could add their own ‘thoughts’, and additionally we added functionality to see what ‘thoughts’ other users had, and who had written them. Finally, we added ‘like’ buttons which any user could click if they liked a ‘thought’. If we had more time we would continue with the google authentication. 

## View it live

Frontend: https://fiona-emilia-anna-auth.netlify.app/
Backend: https://project-authh-oivc6zag6a-lz.a.run.app
