# reading-notes

# Table of contents

1. [Reading Class - 01a](#code-401---reading-class---01a)
2. [Reading Class - 01b](#code-401---reading-class---01b)

# Code 401 - Reading Class - 01a

How would you describe Node to a non-technical friend?

Node.js is a platform that allows you to run JavaScript code outside of a web browser ,but this language used in browser, so developers giva idea of making JavaScript can work outside the browser.

What does it mean that Node is a JavaScript runtime?

An environment where JavaScript code can be executed without need browser to execute.

What is Node used for?
. can build the server-side of web applications.
. Also used these server-side applications with access to the operating system and file system.

# Code 401 - Reading Class 01b

An introduction to NodeJS and Express

-Explain middleware, answer as though I were a non-technical recruiter ? 
Middleware functions sit between the incoming request and the response from the server. They can perform tasks like logging information, validating user authentication, modifying data, handling errors, or even adding extra functionality to the request or response. After each middleware does its job, it passes the request to the next middleware or the final destination.

Express the most popular _frameworks Node.js web__.

Express is “unopinionated.” What does that mean?
it provides developers with the freedom and flexibility to structure and build their web applications according to their own preferences and requirements. It doesn't enforce strict rules or conventions and allows developers to make their own choices regarding libraries, tools, and coding.

What is a module and why is modularity useful to us as developers?

Module refers to a self-contained unit of code that encapsulates specific functionality. It is a way of organizing code into separate, independent units that can be easily managed and reused. Modules can contain variables, functions, classes, or even larger components of an application.

## What is NPM

What version of npm are you running on your machine? 
npm -v 9.5.0

What command would you type to install a library/package called ‘jshint’ into your node project?
npm install jshint

## What is TDD

Explain why tests are important. Please explain as though I were your non technical elder?
Imagine you're building a new house. Before moving in, you want to make sure everything is in good condition and works properly. You might inspect the plumbing, test the electrical outlets, and check that the doors and windows open and close smoothly. These checks give you confidence that your new house is safe and comfortable.

What are three expected benefits of testing?
1-Software Reliability.
2-Bug Detection.
3-Maintainability and time saving.

Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- Poor maintenance of the test suite.
- writing too many tests at once.
- forgetting to run tests frequently.

## CI/CD

What are three benefits of Continuous Integration?
-Increased Collaboration & Team Efficiency.
-Early Bug Detection & Faster Resolution to catch issues.
-Rapid Feedback.

What is the difference between Continuos Delivery and Continuous Deployment?
Continuous Delivery is a software development approach where the application is always in a release-ready state, allowing it to be deployed at any time with a manual release decision. Continuous Deployment, on the other hand, automatically deploys new features or changes to the production environment as soon as they pass the necessary tests.

Explain how GitHub fits into this process assuming the listener comes from a non-technical background?
GitHub is a platform that collect all users at software development that supports Continuous Integration and Continuous Deployment. It serves as a central repository for code, allowing teams to track changes and collaborate through pull requests and merges, its so helpful.
