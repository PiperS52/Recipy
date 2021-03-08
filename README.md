# Recipy

![](images/Recipy-homepage-screenshot.png)

![](images/Recipy-filter-screenshot.png)

## Brief

### Initial Spec

**MVP**:
- A web app
- Access to a large bank of recipes (using WebScraper or API)
- Display the recipes

 **Additional Features**
- Ability to filter the recipes based on single/multiple ingredients
- Spotify playlist
- *Requires signup/login* - Ability to add recipes to favourites
- *Requires signup/login* - Ability to add all ingredients for a recipe into a shopping cart (using whisk API)

---
## User Stories

```
As a user
Because I am obsessed with BBC
I would like to have access to all recipes from BBC Food

As a user
So that I can choose what to eat tonight
I would like to see a list of recipes with titles, images, summary, cook time

As a user
So that the page loads suitably quickly
I would like to be able to scroll infinitely

As a user
So that I can see all the recipe details
I would like to click on a recipe card and see a pop-up of all recipe details (ingredients, instructions etc.)

As a user
So that I can find recipes that use ingredients I have in the cupboard
I want to be able to filter recipes by ingredients

As a user
I can listen to music with my meal
I would like to have a link to a relaxing background music playlist from Spotify
```
## Technologies used

| Technology    | Use                           |
| ------------- | ----------------------------- |
| Node          | Back-end JavaScript Framework |
| Express       | Web application framework     |
| ReactJS       | Frontend JavaScript Framework |
| Redux         | Managing application state    |
| Puppeteer     | Web Scraping                  |
| Cypress       | Front-end testing             |
| Jasmine       | Back-end testing              |
| MongoDB       | Database                      |
| CSS           | Styling                       |
| Travis        | CI/CD                         |
| Heroku        | Production Environment        |
| ESLint        | Linting                       |

---
## Getting started:

Clone this repository
```
git clone https://github.com/PiperS52/Recipy.git
```
Run the package installer with the following command in the root folder, client folder, as well as inside web-api-auth-examples:
```
npm install
```
Run the web app from the root folder:
```
npm run dev
```
## To run tests:

```
npm test
```
---
Runs the app in the development mode.

The browser should open the project url in your browser automatically, but if not visit [http://localhost:3000](http://localhost:3000) to view it in the browser.

## Additional resources:

- Recipe Scraper - https://github.com/PiperS52/scraper
