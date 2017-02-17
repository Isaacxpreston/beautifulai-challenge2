# beautiful.ai-engineer-challenge-2

This is the second of two engineer challenges for software developers applying for a position at Beautiful.ai.

This is a harder challenge intended to evaluate candidates for a more senior engineering role. 

## Summary
Beautiful.ai is a serverless single-page application which implements a full-stack mentality within the client. Our ideal candidate will
have detailed knowledge of how to architect and maintain a complicated Model-View architecture.

With this challenge, we are asking you to implement a simple single-page Model-View application that loads and presents data from an external API using vanilla javascript.

## Goal
- Build a simple model-view framework from scratch
- Load data from the Star Wars API and present it in a view.
- Wire up some simple interactivity that loads additional data into a view upon user interaction.

## Your Task
- Create a single-page model-view application
  - Your application should bootstrap itself from index.html into a single main.js function
- Upon startup, load a list of people from the Star Wars API into your model
  - The url for loading people from the Star Wars API is http://swapi.co/api/people/
  - Your model should contain a People collection model that contains a Person model for each entry loaded.
- Render a People view into the document body. Your People view should render a list of Person views that display some properties (like the person's name) from each Person model.
- Add interactivity so that when a user clicks on any Person view, you dynamically load data about that person's homeplanet from the Star Wars API into a new Planet model and then render a Planet view attached to the Person view that displays some properties (like the planet name). The url for loading a person's homeplanet is included in the JSON properties returned for each person.
  
Documentation and more information about the Star Wars API can be found at https://swapi.co

## Project Constraints
- Do not use any 3rd-party MV frameworks like Backbone, React, or Angular.
- Do not use any 3rd-party SWAPI libraries.
- You may use 3rd-party utility libraries like jQuery or underscore if desired.
- Do not include any HTML tags in the body of your index.html page or use a templating engine. All DOM elements should be generated via javascript in your views.
- You may include a style sheet if you want to style your views.
- You are encouraged to but not required to use Javascript ES6.

## Bonus Task
- Add a search box to search across Star Wars people
- Style it to look beautiful.

## Submitting Your Work
Please clone this repo and check it into your own github account. Send an email to jobs@beautiful.ai with a link to the repository and your resume or portfolio links.

Thanks! And Good Luck!
