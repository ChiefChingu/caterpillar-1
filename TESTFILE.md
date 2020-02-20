# Testing
Each user story is tested thoroughly. All steps are taken in the main browsers at 3 different viewports: mobile, tablet and desktop. Desktop includes small laptops and larger widescreens (up to 2540px).

Back to the [README](https://github.com/ChiefChingu/caterpillar-1/blob/master/README.md).

## User stories
### User story 1
As a user I want to subscribe to alerts, so that I stay informed about future infections.

1. Try to locate the call to action 'keep me save' or 'join'.
2. Try to click the button.
3. Try to submit the empty form and verify that an error message about the required fields appears.
4. Try to submit the form with an invalid email address and verify that a relevant error message appears.
5. Try to submit the form with all inputs valid and verify that a confirmation message appears.

### User story 2
As a user I want to read information about the processionary, so that I understand what it is.

1. Try to navigate to the page 'What is it?'.
2. Try to scroll down and read the information.
3. Try to view the pictures.
4. Try to hover your mouse over the pictures to see the img tag.

### User story 3
As a user I want to read information about the symptoms, so that I know how to recognize allergic reactions.

1. Try to navigate to the page 'Symptoms'.
2. Try to scroll down and read the information.
3. Try to view the pictures.
4. Try to hover your mouse over the pictures to see the img tag.

### User story 4
As a user I want to ask a question, so that my particular issue or concern can be addressed.

1. Try to find the contact form.
2. Try to submit the empty form and verify that an error message about the required fields appears.
3. Try to submit the form with an invalid email address and verify that a relevant error message appears.
4. Try to submit the form with all inputs valid and verify that a confirmation message appears.

## Features
### Header
- Navigation:
  - Try to navigate to all the pages.
  - On smaller screens: try to open and close the hamburger menu.
- Contact: see testing user story 4.
- Brand logo: 
  - Try to click on the logo on every page.
  - Verify that you go to the home page very time you click on the logo.
- Call to action (on mobile only): see testing user story 1.
 
### Hero
- Alerts notification: 
  - Try to click on the alerts notification.
  - Verify that the notification popup renders correctly.
- Map: verify that the map renders correctly.

### Call to action
- Call to action button: see testing user story 1.

### Footer
- Social icons: 
  - Try to click the social icons.
  - Verify that a new tab/window opens.
  - Verify that the right soccial page loads.
- Secundary navigation:
  - Try to navigate to the cookie policy, privacy policy and the about section.
  - Verify that each page loads correctly.

### In addition the detail pages contain:
- Information about what the oak processionary caterpillar is: page 'What is it?'. See testing user story 3.
- Information about what the symptoms of an infection are: page 'Symptoms'. See testing user story 4.

## Issues
### No javascript, only CSS
As explained in the README I wanted to use CSS and HTML only for this project. This lead to some challenges with the mobile hamburger menu. I found a pure css mobile menu on CodePen. However, this caused all content to be pushed down when that mobile menu was toggled. This is of course not acceptable, so I discarded this solution. I found a better way in the form of a [pure CSS popup window] (https://codepen.io/imprakash/pen/GgNMXO). I modified this to be a full width nav bar on mobile. Also, I used this as a contact and subscription box.

This lead to another issue: on mobile the on-screen keyboard overlaps the input field for the message of the contact form. I tried adding a scroll functionality, but did not manage to get the bar scrolling. In the end I split the contact form in steps, which makes it possible to have lower height boxes that do not overlap with on-screen keyboards.

Lastly, I'd like to have the menu showing the active page in a different color. I only found solutions with javascript. I made a less elegant, hard coded solution. I added an ID called 'active-page' to give the navigation item of the current page an orange color.

### Forms lacks a POST method
For the forms: first I used the Code Inistitute post URL, but I wanted to add a confirmation/thank you message. That is not possible since the Code Institute page is out of my control.

Therefore I changed the action attribute to go to a new popup message and left out the method="post" on purpose.

### Image sizing
I made all images responsive: both in file size and when relevant in dimensions. This was a pretty large task, because I have no experience with resizing and editing images. Finally made it work with the picture element.

### Edge shows all popups at once for 1 milisecond
Due to the fact that I want to use CSS only, I had to code a pretty 'verbose' part for the popup window. This code is hidden until the user activates the popup. In Edge there is a slight issue here: when the page loads it displays all the popup windows stacked on top of each other for just a milisecond.

Solution: disabled the transition effect of the popups.

## Table summary
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

