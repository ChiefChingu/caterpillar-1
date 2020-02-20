# Testing
Each user story is tested thoroughly. All steps are taken in the main browsers at 3 different viewports: mobile, tablet and desktop. Desktop includes small laptops and larger widescreens (up to 2540px).

Back to the [README](https://github.com/Code-Institute-Solutions/readme-template/blob/master/README.md)

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
..* Try to navigate to all the pages.
..- On smaller screens: try open and close the hamburger menu.
- Contact: see testing user story 4.
- Brand logo: try to click 
- Call to action (on mobile only): fast lane for mobiel users, so they can join directly and set up alerts.
 
### Hero
- Alerts notification: explanation to user that this release only includes a fixed location in Amsterdam.
- Map with infected trees around a fixed location in Amsterdam: allows user to see the infections (if any) around a specific location.

### Call to action
- Call to action button: stimulates the user to take action now and subscribe to alerts.

### Footer
- Social icons: allows the user to check the social channels.
- Secundary navigation: shows privacy policy, cookie policy and about us.

### In addition the detail pages contain:
- Information about what the oak processionary caterpillar is: page 'What is it?'.
- Information about what the symptoms of an infection are: page 'Symptoms'.

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

