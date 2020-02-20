# Caterpillar Alarm - Milestone 1
Imagine the following scenarios.

> This Spring you go out for a picknick with your friends. Unfortunately, you are not able to finish your sandwich, because you got a severe rash and sore and weepy eyes. Is it a food allergy? Or hay fever? 

No, it is the oak processionary (link to Wiki). They are a human irritant because of their venomous setae (hairs), which can cause skin irritation and even asthma.

Now imagine that same picnic.

> This Spring you go out for a picknick with your friends. You check the location of the picknick on CaterpillarAlarm.com to see if it is safe to be there this afternoon. You see that there are several alerts of infected trees. You change the plan and pick an area where it is safe to be. You enjoy your sandwich and friends and only have a hangover to worry about (the next day that is).

What is the most likely scenario? Chances are that it will be the first scenario. Why? Because the other one does not exist, **yet**…

This milestone 1 project is **the inception of Caterpillar.com**, a place where you can help each other by adding alerts about infected trees.

## UX
### User stories
As a user I want to:

1. Subscribe to alerts, so that I stay informed about future infections.
2. Read information about the processionary, so that I understand what it is.
3. Read information about the symptoms, so that I know how to recognize allergic reactions.

## Features
### Existing features
For all pages:
#### Header
- Navigation: hamburger menu on mobile, normal horizontal navigation on larger screens.
- Contact: within the navigation, a popup displaying a contact form.
- Brand logo: clickable logo leading to home page.
- Call to action (on mobile only): fast lane for mobiel users, so they can join directly and set up alerts.
 
#### Hero
- Alerts notification: explanation to user that this release only includes a fixed location in Amsterdam.
- Map with infected trees around a fixed location in Amsterdam: allows user to see the infections (if any) around a specific location.

#### Call to action
- Call to action button: stimulates the user to take action now and subscribe to alerts.

#### Footer
- Social icons: allows the user to check the social channels.
- Secundary navigation: shows privacy policy, cookie policy and about us.

#### In addition the detail pages contain:
- Information about what the oak processionary caterpillar is: page 'What is it?'.
- Information about what the symptoms of an infection are: page 'Symptoms'.

### Features left to implement

#### Look up infected trees at a user defined location
User enters a zipcode/streetname in the location bar. The map will update and shows all infected trees in the vicinity.

#### Add an alert
User adds an alert to the map that will be visible for everyone.

#### User profile
User can configure a whole range of settings about alerts. Think about what kind of notifications (infections, healthy trees, local authorities), what areas, etc.

To make these features fully functional, the following will be implemented over the next projects.

* Integration with Google Maps.
* Connection with databases.
* Account creation.
* ‘Location based page rendering’: map will automatically show infections in current area of user.

In addition, a connection to local government services is considered. They receive the alerts in their area and can decide to respond. The (lack of) progress of their response is visible in the alerts.

## Technologies Used
For this project only HTML and CSS were used. Knowing that certain things were easier to do with JS (looking at you, mobile menu!), I still wanted to only use CSS, since this is the first milestone project. I also decided not to use a framework like Bootstrap, because I wanted to really understand CSS grid.

The regular libraries were used for fonts and icons:
- Google Fonts.
- Font Awesome.

To make the whole process of writing code easier, I used npm and webpack with the following packages:
- normalize.css
- postcss-import,
- postcss-mixins,
- postcss-simple-vars,
- postcss-nested,
- postcss-hexrgba,
- autoprefixer.

This is the setup that I learned in this course: [Mastering the Modern Workflow](https://www.udemy.com/course/git-a-web-developer-job-mastering-the-modern-workflow/)

## Testing
Details of the testing can be found in the [testing file](https://github.com/ChiefChingu/caterpillar-1/blob/master/TESTFILE.md). The summary is included here.

Test passed means that the tests passed for the three main browsers Chrome, Firefox and Edge. (??safari??) Each browser was tested on three viewports: mobile, tablet and desktop.

### User stories
|# | Objective| Action| Result  | Test passed|Remarks
|------| ------ |------| -------------| :----:|--------
|1|Stay informed about future infections on location X.|Subscribe to alerts around location X.|Subscribe form is completed and submitted|OK|
|2|Know what the processionary is.|Go to the section ‘What is it?’.|The section ‘What is it?’ is displayed.|OK|
|3|Know how to recognize an allergic reaction.|Go to the section ‘Symptoms’.|The section ‘Symptoms’ is displayed.|OK|
|4|Ask a question.|Go to the contact form.|Contact form is completed and submitted.|OK|

### Features
|Area | Feature | Test passed|Remarks
|------| -------|:---------:|--------
|Header|Navigation|OK|
||Contact form|OK|
||Brand logo|OK|
||Call to action|OK|On mobile and tablet only
|Hero|Alert notification|OK|
||Alert map|OK|
|Call to action|button|OK|
|Footer|social icons|OK|
||secundary navigation|OK|
|Page 'What is it?'|Content|OK|
|Page 'Symptoms?'|Content|OK|


## Deployment


## Credits
### Content
### Media
### Acknowledgements
