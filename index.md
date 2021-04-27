## TABLE OF CONTENTS

* [OVERVIEW](#overview)
* [LINKS](#links)
* [USER GUIDE](#user-guide)
* [DEVELOPER GUIDE](#developer-guide)
* [DEVELOPMENT HISTORY](#development-history)
* [TEAM MEMBERS](#team-members)

## OVERVIEW

There is not an easy way to see what clubs exist at UH Manoa, so UHM GitClubs is an application for UH Manoa students that provides a centralized directory for Registered Independent Organizations at UH Manoa. Anyone can visit the website to just browse the directory of clubs. The directory includes a description of the club, a link to their website, and contact information. Users are able to login and join a club from the directory.

Features:
- Join a club, and have a list of clubs that you are in
- Admins and club moderators can edit a club
- Admins can create or delete a club

## LINKS

A link to the organization: [UHM GitClubs](https://github.com/uhm-gitclubs)
A link to the deployment: [uhm-gitclubs.club](https://uhm-gitclubs.club/#/)

## USER GUIDE

## DEVELOPER GUIDE

This section provides information to Meteor developers who want to use this code as a basis for their own development projects and tasks.

1. Install [Meteor](https://www.meteor.com/install)
2. Go to the [UHM GitClubs](https://github.com/uhm-gitclubs/uhm-gitclubs) repository, and click the green "Code" dropdown to clone it to GitHub desktop.
3. cd into the ```uhm-gitclubs/app``` directory and install the required libraries with:
```
$ meteor npm install
```
4. Once the libraries are installed, the application can be run with:
```
$ meteor npm run start
```
The application should appear at [http://localhost:3000](http://localhost:3000). You can find the default users and login credentials in ```/config/settings.development.json```. To modify the clubs go to ```app/private/data.json```.

## DEVELOPMENT HISTORY
We are tracking our progress using Milestones:

* [Milestone 1](https://github.com/uhm-gitclubs/uhm-gitclubs/projects/1)
* [Milestone 2](https://github.com/uhm-gitclubs/uhm-gitclubs/projects/3)
* [Milestone 3](https://github.com/uhm-gitclubs/uhm-gitclubs/projects/4)

### Milestone 1: Mockup and Deployment

* Implemented landing page
* Created mockup pages
* Deployed to Digital Ocean

placeholder for M1 screenshot

### Milestone 2

* Implemented funcitonality various pages such as Edit/Create Club, Browse Clubs, Manage Clubs
* Added publications and schemas
* Added database for pages

placeholder for M2 screenshot

### Milestone 3

Issues to be addressed:
* Implement testing for all pages
* Get community feedback

## TEAM MEMBERS
The people collaborating to create this project are:

* [Yong U Cho](https://yongu2000.github.io)
* [Alvin Edrada](https://alvinedrada.github.io)
* [Cris Javier](https://crisjavier.github.io)
* [Mujtaba Quadri](https://mujtaba-a-quadri.github.io)
* [Leeden Raquel](https://leedenkraquel.github.io)
