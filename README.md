# team-profile-generator
  

  ## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [User&nbsp;Story](#User&nbsp;Story)
  - [Acceptance&nbsp;Criteria](#Acceptance&nbsp;Criteria)
  - [Demo](#Demo)
  - [Test](#test)
  - [License](#license)
  - [Questions](#questions)

  ## Description
  a small app that takes in information about employees and generates an html webpage that displays summaries for each person.<br/>

  ## Installation
  make sure to install jest and inquirer to run app

  ## User Story
    ```
    AS A manager
    I WANT to generate a webpage that displays my team's basic info
    SO THAT I have quick access to their emails and GitHub profiles

    ```


  ## Acceptance Criteria

    ```

    GIVEN a command-line application that accepts user input
    WHEN I am prompted for my team members and their information
    THEN an HTML file is generated that displays a nicely formatted team roster based on user input
    WHEN I click on an email address in the HTML
    THEN my default email program opens and populates the TO field of the email with the address
    WHEN I click on the GitHub username
    THEN that GitHub profile opens in a new tab
    WHEN I start the application
    THEN I am prompted to enter the team manager’s name, employee ID, email address, and office number
    WHEN I enter the team manager’s name, employee ID, email address, and office number
    THEN I am presented with a menu with the option to add an engineer or an intern or to finish building my team
    WHEN I select the engineer option
    THEN I am prompted to enter the engineer’s name, ID, email, and GitHub username, and I am taken back to the menu
    WHEN I select the intern option
    THEN I am prompted to enter the intern’s name, ID, email, and school, and I am taken back to the menu
    WHEN I decide to finish building my team
    THEN I exit the application, and the HTML is generated

    ```
  ## Demo

  [team profile generator demo](https://drive.google.com/file/d/15dufW78ClQh19wgZNg-SuK39MFGyiyai/view)

  ## Test
  npm test

  ## License
  MIT

  ## Questions
  @cruzma</br>