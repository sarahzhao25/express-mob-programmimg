# express_mob_programming

## Prompt
We are going to be building out a basic server for restaurants, with models and routes. The learning team will be navigating while the fellow drives the entire time.
See below for the requirements, and let's begin.

## Model Requirements

### Model:

Decide what you want for `type` and also if you want any validations. Determine any relationships you may have in the model.

Restaurant
- name
- type of cuisine
- rating (out of 5)
- number of visits
  - defaults to 0

MenuItem
- name
- number of calories
- whether or not it is spicy

### Model Methods:

Decide if it will be an *instance* method, a *class* method, a *getterMethod*, etc. - and why.

- description
  - returns a string such as "Chipotle serves mexican food!"
- rate
  - gives restaurant a new rating
- findBest
  - returns all resturants with a rating greater or equal to 4

HOOKS
- increases the number of visits, then console.logs for ex... "Chipotle has been visited 10 times"

## Routes Requirements
As a user interacting with menu items, I can ...
- GET all menu items
  - include the restaurant model
- GET all menu items from 1 restaurant ID
- GET one menu item by ID
- POST to menu items
  - include the restaurant ID
- UPDATE menu item by ID
- DELETE 1 menu item by ID

As a user interacting with restaurants, I can ...
- GET all restaurants
- GET one restaurant by ID
- POST to restaurants
- UPDATE restaurant information by ID
- DELETE restaurant by ID
