# Development Challenge for Node.js

This challenge aims to evaluate basic skills in Node.js development, and a bit of data/entity modeling. The idea is to build an HTTP REST API.

## Functionality

The API has to fulfill the following conditions:
* Endpoints for authentication using JWT.<br/>
  Include an endpoint for refreshing the JWT access token.
* Endpoint for retrieving movies.<br/>
  It should be allowed to filter and sort by some field.
* Endpoint for retrieving the information (director included) of a specific episode of a TV Show
* Endpoint for adding a new object (it could be for any entity you like).

### Model

Entities to consider:
* Movie<br/>
  Has many actors, but one director.
* TV Show<br/>
  Has many actors. It also has seasons and episodes inside each of one.
* Actor<br/>
  Can be on different movies and tv shows.
* Director<br/>
  Can direct many movies and specific episodes of tv shows.

Use your common sense (or imagination 😉) to define the descriptive attributes/properties of each entity. For example, name or genre.

## Tech Requirements

These are the following conditions for the development:
* The code should be using **Node.js 16 or superior**.
* The code could be written in **Javascript or Typescript**.
* All the code and comments should be written in **english**.
* Use a **proper naming conventions** and standards when defining the structure of the project and the name of variables, functions, etc.
* Use a **proper structure** to define the different path for the API endpoints 
* The use of ESLint or other linter is optional.
* The database could be **relational or NoSQL**, it's up to you. The use of ORM is optional too.
* The database doesn't need to be presented. But the model should be represented in some way. It could be in the form of ORM configuration or at least a minimal documentation or example of some of the entities.

## Presentation

The result of this challenge should be presented as a GitHub or GitLab **private** repository, giving access to the person that contacted you.<br/>
Please add some minimal documentation (in the form of a README file) describing how to run the project and if there is any requirement or consideration to do so.

Oh, and please don't link or fork this repo to create your own. That way other people trying to complete this challenge won't be able to see solutions to it 😆.

Let's code 💻!
