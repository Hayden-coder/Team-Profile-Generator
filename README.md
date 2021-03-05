# Team-Profile-Generator
## User Story

```md
AS A manager
I WANT to generate a webpage that displays my team's basic info
SO THAT I have quick access to their emails and GitHub profiles
```
## Acceptance Criteria

```md
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
## Video and link 

https://drive.google.com/file/d/1zFAv5suAmRCV85UABZDL-gmczRP1z_4d/view

![Untitled_ Mar 4, 2021 11_41 AM](https://user-images.githubusercontent.com/74078719/110027359-b8390900-7ce6-11eb-8046-47046cb87ff5.gif)

<img width="928" alt="Screenshot 2021-03-04 125300" src="https://user-images.githubusercontent.com/74078719/110028833-9d679400-7ce8-11eb-96d0-479fc6bc948c.png">

## Description
This is a node app that can create an html file of your team members from your input to the prompts.
