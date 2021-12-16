# The Club for You

### Overview
The Club for You aims to provide a directory for UH Manoa student clubs, both registered and unregistered. This way, it will be easy for students to see what different clubs are out there and how they can join them.

Each club's entry will have (as many as applicable): 
- a description
- meeting times / locations
- a club website URL
- contact information
- a few photos

&nbsp;
<br/>
&nbsp;

## User Guide (Screen Shot of Each Page Section )
-----------------------------------------------------

### Landing page
The landing page will provide a basic idea of the project to the user and have a explanation to the users on how to use it.
<img class = "ui left spaced image" src = "/images/the-club-for-you-landing.PNG">

&nbsp;

### Contact page
<img class = "ui left spaced image" src = "/images/the-club-for-you-contact.PNG">

&nbsp;

### Clubs page
The Clubs page will show all of the clubs who use The Club for You. Each club also has tag(s) that the user can click on to see other, similar clubs.
* Clubs Information (Description, Meeting time, Location etc.)
<img class = "ui left spaced image" src = "/images/the-club-for-you-clubs-1.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-clubs-2.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-clubs-3.PNG">

&nbsp;

### Favorites page
On the Clubs page, you can designate your favorite clubs by clicking on the heart ♡ icon on a Club's card. 
Then, those clubs will show up on the Favorites page.
* Clicking the heart ♡ icon again will remove the favorite designation from the Club (un-favorite it).
<img class = "ui left spaced image" src = "/images/the-club-for-you-favorites-1.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-favorites-2.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-favorites-3.PNG">

&nbsp;

### Edit a Club page (Admins only)
* Identical to the Clubs page except that each Club's informational card has an "Edit" option that links to the Edit Club form
<img class = "ui left spaced image" src = "/images/the-club-for-you-admin-edit-clubs-1.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-admin-edit-clubs-2.PNG">

&nbsp;

### Add a New Club page (Admins only)
<img class = "ui left spaced image" src = "/images/the-club-for-you-admin-add-club.PNG">

&nbsp;

### My Clubs page (Club accounts only).
* Functions: View/Edit Club (Their Own Clubs)
* Note: Can not change the owner of any of the clubs. For that, a club must contact an admin.
<img class = "ui left spaced image" src = "/images/the-club-for-you-clubadmin-myclubs-1.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-clubadmin-myclubs-2.PNG">
<img class = "ui left spaced image" src = "/images/the-club-for-you-clubadmin-myclubs-3.PNG">

&nbsp;

### Browse clubs by interest area(s)
* Each clubs has specific interest tag on, so users can find them if they are interested in that specific area.
<img class = "ui left spaced image" src = "/images/the-club-for-you-interests.PNG">

&nbsp;
<br/>
&nbsp;

## Mockup Page example
-----------------------------------------------------
![](images/Mockup.png)

&nbsp;
<br/>
&nbsp;

## Community Feedback
-----------------------------------------------------
A summary of our community feedback questionnaire responses (as of December 15, 2021). 
&nbsp;
### Score of the website
<img class = "ui left spaced image" src = "/images/community-feedback-score-pie-chart.PNG">

&nbsp;

### Did you find the website helpful? If not, please explain why.
* Yes, we can easily find favorite clubs and interests
* Simple website to help you find the club you want
* Interesting format
* Useful information
&nbsp;

### Anything we can do to help your experiences in our website?
* Filter function is good for selecting what you want, but it sometimes shows nothing, maybe due to low club numbers for the filter tag
* UI design
* After you login, I hope there will be indication that you had logged in, rather than the site jumping back to the start
* Maybe more pictures
* The overall design is great. A little suggestion for the club section: more details about the clubs, maybe more pictures or comments from the club members. 
&nbsp;

### Any suggestions?
* increase more clubs, good job for this awesome website
* more functional features
* format is not scaled for phone users
* change the typography on the mobile phone website
* UI is well designed, really enjoyed using the website
&nbsp;

### Please describe your experiences in a few sentences
* Good experience due to the nice GUI and functions, but needs more clubs. 
* Useful tool for a new student to learn more about clubs at UHM.
* Since you have the sign-in function, there can be more functional features, like commenting on a club.
* Confused at first whether I was logged in or not. There is no sign of being logged in or not.
* It helped me look up some information on the different clubs in UH, and also having the contact information guide me to the next step.
* I had a great experience using this website. There are lots of choices for clubs and all of them are categorized. It really helps me to find the one I want and I could save to my favorites.

&nbsp;
<br/>
&nbsp;

## Developer Guide
-----------------------------------------------------
Installation

First, [install Meteor](https://www.meteor.com/install).

Second, go to [https://github.com/the-club-for-you/the-club-for-you](https://github.com/the-club-for-you/the-club-for-you), and click the "Use this template" button. Complete the dialog box to create a new repository that you own that is initialized with this template's files.

Third, go to your newly created repository, and click the "Clone or download" button to download your new GitHub repo to your local file system.  Using [GitHub Desktop](https://desktop.github.com/) is a great choice if you use MacOS or Windows.

Fourth, cd into the app/ directory of your local copy of the repo, and install third party libraries with:

```
$ meteor npm install
```

### Running the system

Once the libraries are installed, you can run the application by invoking the "start" script in the [package.json file](https://github.com/the-club-for-you/the-club-for-you/blob/master/app/package.json):

```
$ meteor npm run start
```

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

&nbsp;
<br/>
&nbsp;

## TestCafe Result
-----------------------------------------------------
TestCafe tests and ESLint will check that the app runs properly after every changes commit to the master branch. 
A sample screenshot of TestCafe test results:
<img class = "ui left spaced image" src = "/images/testcafe.png">

&nbsp;
Current test result status of the master branch:
![ci-badge](https://github.com/the-club-for-you/the-club-for-you/workflows/ci-the-club-for-you/badge.svg)

&nbsp;
<br/>
&nbsp;

## Application Design
-----------------------------------------------------
The Club For You is build based upon [meteor-application-template-react](https://ics-software-engineering.github.io/meteor-application-template-react/). Please use the videos and documentation at those sites to better acquaint yourself with the basic application design and form processing in The Club For You.

&nbsp;
<br/>
&nbsp;

## Development History 
-----------------------------------------------------
Milestone 1 (done): (<a href = "https://github.com/the-club-for-you/the-club-for-you/projects/1"> link </a>) &nbsp;

Milestone 2 (done): (<a href = "https://github.com/the-club-for-you/the-club-for-you/projects/2"> link </a>) &nbsp;

Milestone 3：(in-progress) (<a href = "https://github.com/the-club-for-you/the-club-for-you/projects/3"> link </a>) &nbsp;

&nbsp;
<br/>
&nbsp;

## Contact Us (Coming Soon)
-----------------------------------------------------

&nbsp;
<br/>
&nbsp;

## Deployment on Digital Ocean
-----------------------------------------------------
Please visit [uhmtheclubforyou.xyz](https://uhmtheclubforyou.xyz).

&nbsp;
<br/>
&nbsp;

## GitHub Organization
-----------------------------------------------------
The repositories for this website as well as the application are available at: (https://github.com/the-club-for-you).

&nbsp;
<br/>
&nbsp;

## Team
-----------------------------------------------------
- Jingzhe Feng
- Joy Okimoto
- Malia Liu
- Trevor Kansaki


