# Video-Game-Discovery-application

This application 'Video Game Disc' helps you can search for new and interesting games to play. This design is inspired by RAWG website, a popular video game database.
Can be considered as a mini version of that website.

I have used React with TypeScript for this project as I believe TypeScript is better than JavaScript in terms of language features, reference validations, 
collaboration between teams and developer experience in general.

Vite tool was used for bootstrapping as it is more faster and gives smaller bundle sizes when compared to CRA (Create React App).

Some of the features I developed include toggling between dark and light mode, search functionality, filtering the games by genre and platform (PC, Xbox etc.,) 
and sorting functionality.

Below are the steps I would recommend to get started with the application:
1. Clone this repository to your local machine.
2. Run npm install to install the required dependencies.
3. Get a RAWG API key at https://rawg.io/apidocs. You'll have to create an account first.
4. Add the API key to src/services/api-client.ts
5. Run npm run dev to start the web server.
