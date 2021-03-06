# Frontend Internship Test: Github User Search

## Assigment Description

For this assigment, you should consume the public [Github REST API](https://docs.github.com/en/free-pro-team@latest/rest/overview/endpoints-available-for-github-apps#users) in order to present the github data of a given user. 

The web app must have two pages/routes:

- <b>Search page</b>: the user types a Github username in a form. Once the form is submitted, the data is fetched and presented in the UI. The following data is required: Avatar picture, name, email, bio and their repositories' metadata info: name, description, URL.

- <b>Followers page</b>: the page must show all followers of the user, sorted by username. The application user must be able to click on a username in this page to go to that github user's followers page.

Take into consideration that this web application must be scalable: more requirements will be added on top, and other teams/developers will work on it in the future.

## Submission

1. Don't fork this repo, create a new private repository
2. Share your solution via URL to your private git repository (add admin-learnseeker as a contributor with atleast view access)
3. Create a 30s-2min video (hosted on youtube as unlisted) showcasing the application's use.

Submit your repo URL and video 48 hours after you receive these instructions.

## Bonus

- <b>Write the api queries for GraphQL (comment out the REST API query)</b>: https://docs.github.com/en/graphql/guides/migrating-from-rest-to-graphql
- Use Typescript

## Stack

In your assigment, you are required to use:
- React & Hooks
- Redux
- CSS (styled-components, CSS modules, or plain CSS/SASS/LESS)
- Typescript <b>(for bonus points)</b>

## Review

During the assessment, we will look into the following points:

* Whether you use React/Hooks, Redux, HTML and CSS properly
* Code performance
* Writing testable code
* Code organization (modularity, dependencies between modules, naming, etc)
* SOLID principles
* Error handling
* Mobile friendly
* Assignment interpretation/completion
* Git Best Practices:
  1. Git Commits: https://chris.beams.io/posts/git-commit/#why-not-how (there are 7 rules but this is the most important)
  2. Choose a good Branch Workflow: https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows

## Hints

* You don't need to spend time creating a dev/build environment. You can use [create-react-app](https://github.com/facebookincubator/create-react-app) (and other alike tools) for that
* Third-party libraries are allowed, although is highly recommended to provide a vanilla solution since our main focus is to assess your skills with HTML, Javascript and CSS. Try to rely as much as possible in the Browser/Node native API. 
* If something is not clear to you, or if you have doubts, please let us know!

## End of instructions

Good Luck and have fun!
