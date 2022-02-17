![alt text](img/moonpig-logo.png "Moonpig")

# iOS Technical Challenge

Please complete the task detailed in the brief below. 

We are more interested in your approach to solving this problem than if you fully solve it. We also appreciate that your free time is important. Therefore if you feel your code is unfinished please leave some notes in your README.md explaining what you would do next, given more time. We are more than happy to review this.

When reviewing your project, we'll consider:

- How clean, modular and extensible the code is
- Approach to testing
- Techniques used to present and lay out content in the app
- Any other information provided in your README
- Source control management - please commit regularly and include the .git folder in your submission

## Tools, libraries and frameworks

We'll be using Xcode to build and run your application, so please ensure that your project is compatible with the latest macOS App Store release.

If you do decide to use any external dependencies, please note them down in the README, along with your justifications.

## The Task

We've been asked to rebuild the Moonpig iOS app using the latest best practices and you are part of a team working on the proof of concept. We'd like you to build a simple app that uses our API to display a list of our cards for our customer to browse.

It should meet the following use case:

> As a customer I can view a list of available cards so that I can celebrate my new job

## Wireframes

### Card Listings View

![Card listings page wireframe](img/wireframe1.png "Card listings page wireframe")

## API

### Search Cards

```
curl "https://search.moonpig.com/api/products?size=12&fq=card_shop_id:1&searchFacets=occasion_level_3:occasion%3Ewell%20done%3Enew%20job"
```

