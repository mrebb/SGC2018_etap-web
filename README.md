<<<<<<< HEAD
# ETAP mobile responsive Web page

## Part 1- our MVP:

#### Idea: To build a mobile app where volunteer coordinators can keep track of their collection sites, location and data.

#### Target Users: Volunteer Coordinators

#### Problem: Limited given time, building an app from scratch

#### Goal: Our goal is to provide an easy way to volunteer coordinators to report their work

### User Stories:
  1. As a coordinator, I want to enter in information about the site so that I can categorize the location with metadata
  2. As a coordinator, I want to support volunteers with questions via a lookup list (autocomplete dictionary) so that I can keep people moving along
  3. As a coordinator, I want to take a picture of the totaled litter for a category so that I can enhance the data and make it more robust
  4. As a coordinator, I want to enter a total count for given category, as reported by volunteers so that I can quantify the data for a category
  5. As a coordinator, I want to double count minimum 4 categories for a site cleanup, so that I can meet the QAPP (Quality Assurance Project Plan) regulation
  6. As a coordinator, I want to be able to select a threat assessment category, enter a count in that given category, so that I can make the data more robust
  7. As a coordinator, I want to enter a weight (in grams, oz, or lbs - at discretion) of a given category, so that I can make the data more robust
  8. As a coordinator, I want to enter any additional notes (such as brands) for a given category in a free form field, so that I can make the data more robust
  9. As a coordinator, I want to capture the lat/long of a site (i.e. polygon) and have the application calculate the square footage of the cleanup
  10. As a coordinator I should be able to sign up and sign in to the website.

- Nice-To-Haves
  * Customize icons for menu
  * Downloading button for forms
  * Information on how to recycle
  * Photos associated with each event
  
 ## Part 1- ETAP App as a glance/Mockup
  ![Authentication](images/game.png "Sign-in via Google Account")


 
#### Instructions:
  * Log in
  * Left side menu navigate to Sign Up forms
  * Navigate to site by location to view site's collection data
 
  
  
### Material and Tools
  * Javascript
  * [React](https://reactjs.org/)
  * [Redux](https://redux.js.org/)
  * [Material Design Lite](https://github.com/google/material-design-lite)
  * [MySQL Workbench](https://firebase.google.com)
  * [ASP.NET Core](https://spritejs.readthedocs.io/en/latest/)
 
### Copyrights and Acknowledgements
  * [Privacy](https://termsfeed.com/privacy-policy/6cf81f38974eab1bf5dc46b1e06725e6)
  * [Terms & conditions](https://termsfeed.com/terms-conditions/0014ae28a1cef6301fb4b9fb42109b40)
=======
# ETAP Web
A prototype application for the cataloging/categorization and tracking of litter picked up

## Getting Started
- You will need:
    - Dotnet Core SDK
    - NodeJS/NPM
    - Git (of course!)
    - Docker (optional)
- Clone this repository
- Navigate to the root directory
- Run:
    - For Docker: 
        - Run `docker build -t etap.web .`
        - Run `docker run -d -p 8080:80 --name etapweb etap.web`
    - Locally:
        - For unix-based systems, run `./run.sh`
        - For Windows, use `./run.ps1`

## Contribution Guidelines
- NO PASSWORDS OR CREDENTIALS CHECKED IN!
    - The `.gitignore` will ignore a directory named `secrets/`, put them there, or use the [dotnet core secrets manager](https://docs.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-2.1&tabs=macos)
- This work is MIT, see the LICENSE for details
>>>>>>> bcb373c3dd1b10316862a535d4b8427f593f1fa9
