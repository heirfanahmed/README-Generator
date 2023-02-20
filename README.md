# README-Generator

## Task

Create a command-line applciation that dynamically generates a professional README.md file from a users input using  the [Inquirer package](https://www.npmjs.com/package/inquirer).

The application will be invoked by using the following command:

```bash
node index.js
```


## User Story

* As a developer, I want a README generator through the command line so that, I can quickly create a professional README for a new project.


## Acceptance Criteria

* Create a command-line application that accepts user input.

* When a user is prompted for information about the application repository then a high-quality, professional README.md is generated with:
    * The title of my project 
    * Sections entitled:
      * Description 
      * Table of Contents 
      * Installation 
      * Usage 
      * License 
      * Contributing 
      * Tests 
      * Questions

* When a user enters the project title then it is displayed as the title of the README.

* When a user enters a description, installation instructions, usage information, contribution guidelines, and test instructions then this information is added to the sections of the README entitled Description, Installation, Usage, Contributing, and Tests.

* When a user chooses a license for their application from a list of options then a badge for that license is added near the top of the README and a notice is added to the section of the README entitled **License** that explains which license the application is covered under.

* When a user enters their GitHub username then this is added to the section of the README entitled Questions, with a link to their GitHub profile.

* When a user enters their email address then this is added to the section of the README entitled Questions, with instructions on how to reach them with additional questions.

* When a user clicks on the links in the **Table of Contents** then they are taken to the corresponding section of the README.

* Create a README-Generator where we enter details of the README file in the command line and it creates a README file with all details as entered in the command line.


## Description of the Project

* Create a `.gitignore` file and include `node_modules/` and `.DS_Store/` so that `node_modules` directory isn't tracked or uploaded to GitHub.

* Create `.gitignore` file before installing any npm dependencies.

* Make sure that repo includes a `package.json` with the required dependencies. I can create one by running `npm init` when I first set up the project, before installing any dependencies.


## Technologies Used
1. ES6.
2. Node.js.


## Action

1. Created a simple application that allows a user to see weather condition ans based on that the web app recomments movies.

2. This app runs in the browser and feature dynamically updated HTML and CSS powered by Javascript using jQuery.

3. It is linked to Moment.js library along with the jQuery library and UI library.
     
4. It adapts to multiple screen sizes.

5. The following points show how the app should works:

    * Displays the current weather condition based on selected city.
 
    * Recommends 12 movies to watch.


## Screen Shot of the README file generated:

![README-Generator](https://.png)


## Links to the deployed website and repository URL:

*** Repository URL: https://github.com/heirfanahmed/README-Generator

*** Deployed website: https://heirfanahmed.github.io/README-Generator/