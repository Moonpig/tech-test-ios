![alt text](img/moonpig-logo.png "Moonpig")

# iOS Technical Challenge

Please complete the task detailed in the brief below. 

We appreciate that your free time is important, and we expect this to take no longer than an evening (2-3 hours) to complete. If you feel your code is unfinished please leave some notes in your README.md explaining what you would do next, given more time. Please take note of the [How We Score](#How-We-Score) section below to ensure that you have demonstrated everything that we are looking for.

We are looking purely at your technical skill in this exercise. Subsequent interview stages will cover the other aspects that we believe are also important.

# How We Score

When reviewing your project, we'll score it on:

- How much of the task has been completed and how accurately it meets the brief. We will continue this project at a later stage of the interview process, so the functionality we've asked for needs to be present and work as intended
- Approach and design patterns used to enable testing. We're looking for code to be written in a way to enable testability and a strong demonstration of how you would test at least one of your created classes/structs in full - the less trivial the better
- Any bugs we find in your code
- SwiftUI usage
- How clean, modular and extensible the code is
- The applied architecture and how the code is structured
- How you handle errors. The customer should be made aware of any critical issues
- Use of modern technologies such as Combine or async/await (where appropriate)
- Any information provided in your README
- Source control management - please commit regularly and include the .git folder in your submission

We will not consider:

- How well the UI matches the wireframe below. It is shown for illustration only
- Extra scope or functionality not requested for the task

## Tools, Libraries and Frameworks

We'll be using Xcode to build and run your application, so please ensure that your project is compatible with the latest major macOS App Store release. Please state the exact version used in the README.md so we can ensure compatibility when reviewing.

We use SwiftUI for all new UI code, so it's ideal if you can use that. If you're not overly familiar with SwiftUI then please make best efforts.

You shouldn't need to use any third-party dependencies to complete the task, but you can use them if you choose to. If you do decide to use any external dependencies, please note them down in the README, along with your justifications.

## The Task

We've been asked to rebuild the Moonpig iOS app using the latest best practices and you are part of a team working on the proof of concept. We'd like you to build a simple screen that uses our API to display a list of our cards for our customers to browse.

It should meet the following use case:

> As a customer I can view a list of available cards

## Wireframes

### Card Listings View
The wireframe is shown for illustration purposes only.

![Card listings page wireframe](img/wireframe1.png "Card listings page wireframe")

## API

### Search Cards

```
curl "https://moonpig.github.io/tech-test-frontend/search.json"
 > Note: static data has been used here to ensure consistency - please treat this as if it were an API call
```
