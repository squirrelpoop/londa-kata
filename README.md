# Londa Kata
This is a training kata intended for you to work thru each and every situation you would find as a junior developer. Each section will be rated on a scale of:
  * Beginner, Simple, Intermediate, Complex, Complicated

Whilst it is the intention you complete each section on your own, it is encouraged for you to seek help, either from the internet or a team developer on ENR team.

## Overview

You are to create a Classified ad system such that there will be `Person` and `ClassifiedAd` schemas. There will be no need to log in as user since this is just a tutorial exercise, therefore, when you create an ad, you will simply select the `Person` selling. You will have to have UI that allows you to create a `Person` and create an `ClassifiedAd`. You will need to perform the full CRUD operations on each schema. If you decide to use any sugar endpoints to simplify the UI, this is up to you. Of course the default view (dashboard) will be the list of classified ads. Design on how it looks is up to you, but use the material-ui library to find the proper components for your design.

### Steps

Here are the steps to success!


#### Setup

1. Create a personal repository named classified-rails [Beginner]
2. Create a personal repository named classified-react [Beginner]
3. Create a Ruby on Rails project with OpenAPI tools [Beginner]
  - `rails new [name of your app] --api -T`
4. Create a React app [Beginner]
  - `npx create-react-app [name of your app]`
5. Use Stoplight Studio to design your API returning a proper 2xx for each response, 404 for routes that cannot be found, etc [Simple]
6. Stub out the API you just created with the routes/controllers [Simple]
7. Test routes in api-docs [Beginner]


#### React
1. Run `npm i --save react-redux @material-ui/core axios redux-logger redux-promise-middleare`
2. Set up the redux basics (store and provider) [Complex]
3. Follow online tutorial to install `storyboook` for react [Intermediate]
4. Create a classified ad component via storybook that has the `Person` name, `Person` phone, and `ClassifiedAd` ad. [Complex]
5. Create a dashboard that renders all classified ads (GET /classifieds) [Complicated]
6. Add to the dashboard an appbar with a title and a menu that allows you to navigate to `Add Person` and `Create Ad` [Complicated]
7. When clicking `Add Person`, navigate to a empty `Add Person` view [Complex]
8. When clicking `Create Ad`, navigate to an empty `Create Ad` view [Complex]
9. For `Add Person`, create a form that collects `name`, `phone`, and POSTs to `/persons` [Complicated]
10. For `Create Ad`, present a form that allows text up to 250 characters (does not have to be enforced), and allows them to select the person from a list of persons (GET /persons). When they hit save, do a `POST /classifieds`. [Complicated]

#### Team Principle Expectations

1. Maturity - Seek help early and often if needed
2. Maturity - Do not copy paste code examples. This is an exercise for you to learn to code.
3. Maturity - Means no bugs left over bc you couldnt solve them.
4. Maturity - If you estimate a work load to be say 1 hour and you are stuck and havent coded in 45 minutes, ask for help!
5. Quality Baked In - Handle all possible response codes in your UI, etc.
6. No Turd Launching - Commit early and often, get code reviews before you do the next ticket item. Max ticket WIP is 2, but I suggest 1 ticket at a time. So make sure your commits are easy to read. Meaning you commit a single topic at a time, not a whole file of multiple things.
