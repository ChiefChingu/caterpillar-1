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
From top to bottom:
#### Header
- Brand logo
- Navigation
- Call to action (on mobile only)

##### Hero
- Alerts notification
- Map with infected trees around a fixed location in Amsterdam

##### Call to action
- Call to action button

##### Footer
- Social icons
- Secundary navigation

#### Feature 3 - Subscribe to alerts (static and hard coded)
User subscribes to future alerts by clicking on the join button at the top of the page (mobile view) or the CTA at the bottom of the page (desktop).

Please note: the interactivity of this feature is out of scope for this project.

#### Feature 4 - Know how to recognize infected trees
User navigates to the section ‘How to recognize infected trees’. Either via the quick links in the content or via the menu at the top of the page.

#### Feature 5 - Know what to do when you have an allergic reaction.
User navigates to the section ‘What are the symptoms’. Either via the quick links in the content or via the menu at the top of the page.

### Features left to implement

#### Feature 1 - Look up infected trees (static and hard coded)
User enters a zipcode/streetname in the location bar. The map will update and shows all infected trees in the vicinity.

Please note: the interactivity of this feature is out of scope for this project.

#### Feature 2 - Add an alert (static and hard coded)
User adds an alert by clicking on the + button. A new window opens and user can specify the alert.

Please note: the interactivity of this feature is out of scope for this project.
1. Enter a zip code of location x, so that I see if that location is safe to go to.
2. Add an alert about location y, so that I warn other people that location y is not safe to go to.

To make Feature 1, 2 and 3 fully functional, the following will be implemented over the next projects.

* Integration with Google Maps.
* Connection with databases.
* Account creation.
* ‘Location based page rendering’: map will automatically show infections in current area of user.

In addition, a connection to local government services is considered. They receive the alerts in their area and can decide to respond. The (lack of) progress of their response is visible in the alerts.

## Technologies Used


## Testing
|# | Objective        | Action         | Result  | Remarks
|------| --------------- |---------------| -------------| --------
|1|Know that location x is safe to go to.|Enter zipcode of location x.|A map with location x showing all alerts in the vicinity.|Out of scope for this project. An image of a map with infections is included.
|2|Let other people know that location Y is not safe to go to.|Add an alert about location Y.|Whenever location Y is queried, the alert is displayed.|Out of scope for this project. An image of a map with infections is included.
|3|Stay informed about future infections on location Z.|Subscribe to alerts around location Z.|Receive a notification whenever there is an update around location Z.|Out of scope for this project. CTAs are included without functionality.
|4|Know how what the processionary is.|Go to the section ‘What is it?’.|The section ‘What is it?’ is displayed.
|5|Know how to recognize an allergic reaction.|Go to the section ‘Symptoms’.|The section ‘Symptoms’ is displayed.

## Deployment

## Credits
### Content
### Media
### Acknowledgements
