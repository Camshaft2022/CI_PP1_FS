![image](https://user-images.githubusercontent.com/100613509/165908486-6aea07b6-07bf-4173-90ec-c1d3505bc589.png)

[Live webpage]https://camshaft2022.github.io/CI_PP1_FS/

##Project Goals 

### User Goals
- Finding a comfortable and motivating enviroment to work on themselves
- find information on memberships and where to sign up
- find information on where the gym is located
- find information on what facilites the gym provides
- find what classes are available

### Site Owner Goals
- Increase number of clients
- Showcase enviroment and whats offered
- Provide clients with contact information
- Provide clients with knowledge of whats for offer when they join the gym

## User Experience

### Target Audience
- people looking to make a change
- people that are looking for a new gym
- people that are professional athletes/or novices
- people looking to work out with a group

### User Requrements and Expectations

- an easy to use navigation bar
- easy to find knowledge
- Links and functions that work as expected
- confortable design with a less is more aproach
- easy to find contact information 
- Accessibility for all

### User Stories

#### First-time User 
1. As a first time user, I want to know where the gym is located
2. As a first time user, i want to know whats to offer if i was to choose this gym
3. As a first time user, I want to know more about the enivorment
4. As a first time user, I want to know about the staff

#### Returning User
5. As a returning user, I want to see facilities options
6. As a returnign user, I want to know the opening times
7. As a returning user, I want to find a phone number to call
9. As a returning user, I want to leave some comment, suggestion or message to the staff
10. As a returning user, I want to find the gym on social media
11. As a returning user, I want to know who is available at the gym
12. As a returning user, I want to get how to get to the location of the gym

#### Site Owner 
13. As the site owner, I want users to find news about up and coming class and have the ability to sign up
14. As the site owner, I want users to get to know the gyms enviroment
15. As the site owner, I want the users to be able to contact us

## Design

### Design Choices
The webpage was designed with a less is more approach so that there not bombarded with alot of information so its a single page scroll so that the information can be easily found via the navigation bar. 

### Colour
For the colour scheme i have choosen a dark teal blue as its a bold color but has a softness thats appealling to a any a customers eye and i have choosen to use both white and black as contrasting colors so that it matchs the color through-out the gyms enviroment and is also easily visible to all
<br>

### Fonts
Bebas Neue 

sans-serif arial

### Structure
the page is a well organised, clean looking and user friendly single scroll page designed to be less is more so that the customer wont be reading massive groups of text but more visual appealling design that can be navigated by the links on the mavigation bar or though a single scroll
<br>
the page consists of 5 seperate sections
- a landing page
- a facilites page that is shown on seperated cards
- a classes page which is a timeline based structure
- a timetable page which shows the weeks classes
- a contact page with a need to know information such as contact number as well as opening hours and a usable map 


### Wireframes

<details><summary>Home</summary>
<img src="docs/wireframes/wireframes-homepage.png">
</details>


## Technologies Used

### Languages
- HTML
- CSS

### Frameworks & Tools
- Git
- GitHub
- Gitpod
- Google Fonts
- Adobe Color
- Font Awsome

## Features
The page consists of five sections and fourteen features

### Logo and Navigation Bar
- Featured on all five pages
- The navbar is fully responsive and is downsized on smaller screens
- It allows users to easily navigate the page
- The link for the page the user is currently on is highlighted

![Logo and navbar](docs/features/feature-logo-and-navbar.jpg)


## Validation

### HTML Validation
The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors no warnings to show.
<details><summary>Home</summary>
<img src="docs/validation/validation-html-index.jpg">
</details>

### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website.

<details><summary>whole page</summary>
<img src="docs/validation/validation-css-whole-page.jpg">
</details>


### Accessibility


### Performance 
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. 

<details><summary>Home</summary>
<img src="docs/validation/lighthouse-performance-index.jpg">
</details>


### Performing tests on various devices 
The website was tested on the following devices:
- Lenovo Yoga 2 Pro (both in pc and tablet mode)
- Honor 20 pro
- Xiaomi Redmi Note 7

In addition, the website was tested using Google Chrome Developer Tools Device Toggeling option for all available device options.

### Browser compatability
The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Egde

### Testing user stories

1. As a first time user, I want to know where the gym is located

2. As a first time user, I want to know the price range of memberships
3. 
4. As a first time user, I want to know more about the gym
5. 
6. As a first time user, I want to get a feel of what to expect at the gym

5. As a returning user, I want to see offers on memberships

6. As a returnign user, I want to know the opening times
7. 
8. As a returning user, I want to find a phone number to call for questions or to sign up

8. As a returning user, I want to see the facilites

9. As a returning user, I want to leave some comment, suggestion or message to the staff

10. As a returning user, I want to find the gym on social media

11. As a returning user, I want to know more about the coaches and staff members

12. As a returning user, I want to get directions to the gym

13. As the site owner, I want users to find news about upcoming events or changes in opening times

15. As the site owner, I want the users to be able to contact us or find us on social media

## Bugs

| **Bug** | **Fix** |
| ----------- | ----------- |
| Home page link stays highlighted when visiting another page | Change active atribute to the correct page |
| The user can submit a contact form input without a message | Add required attribute to message input field |
| Navbar divides into two rows on xs screen size | Add a media query to remove the right margin of the logo in the navbar on xs screen |
| Email overflows on xs screen size | Add a media query that makes the divs spread to 100% width on xs sreens to froce the content onto a seperate line |
| When viewed on tablets, the contact page has whitespace after the footer | Set min-height for body to 100vh |

## Deployment
The website was deployed using GitHub Pages by following these steps:
1. In the GitHub repository navigate to the Settings tab
2. On the left hand menu select Pages
3. For the source select Branch: master
4. After the webpage refreshes automaticaly you will se a ribbon on the top saying: "Your site is published at https://4n4ru.github.io/CI_MS1_BodelschwingherHof/"

You can for fork the repository by following these steps:
1. Go to the GitHub repository
2. Click on Fork button in upper right hand corner

You can clone the repository by following these steps:
1. Go to the GitHub repository 
2. Locate the Code button above the list of files and click it 
3. Select if you prefere to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash
5. Change the current working directory to the one where you want the cloned directory
6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY)
7.Press Enter to create your local clone.

## Credits
Images not referenced below are owned by the developer.

### Media
In order of apearance:

### Code
In order of apearance:


## Acknowledgements
I would like to take the opportunity to thank:
- My mentor Mo Shami for his feedback, advice, guidance and support.
