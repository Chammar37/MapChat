# MapChat
Hyper-local social network

## Explanation of project

A lightweight social media network focused on map-groups and uploading pictures and short videos as flags to those groups. 

## What is a map-group?

A map-group is defined by a set of users and a map: users can document their activities and share moments at locations. 

## Social benefits

1. Getting outside to build a collection of images / videos / stories with friends

2. Similar to Pokemon GO in some sense, gives certain people a reason / reward to exercise or just go outside

3. Exploring locations in your home city / place you may not have been before

## Economic benefits

1. A town or city can have their own official map-group

2. Popular restaurants (or unpopular) could pay to have their restaurant as a flag

3. Tourist sites are marked by flags (monuments, points of interest)

4. Important city locations are flagged (public libraries, city hall, firehouse, post office . . )

5. Different layers for city

6. Restricted privileges for users

## Environment

Mobile-app, desktop. (Prototype can run in a web browser)

## High-level Requirements


1. Users can sign up for an account through an account creation process.\
Priority: 1

2. Users can login through a login process.

3. Users can create a map-group by selecting a location.\
Priority: 1

4. Users can invite other users to join their own map-group.\
Priority: 1

5. Users with sufficient privileges can remove other users from a map group.\
Priority: 2

6. A map-group interface will have a chat box.\
Priority: 2

7. Users can upload a photo or video to a map-group (through mobile app), where it will appear as a flag for other users to interact with. Photo has the coordinate meta data.\
Priority: 1

8. A user can choose to make the content of a flag hidden, requiring another user to visit the location in order to access the content. 
Priority: 2

9. Users can select a flag in a map-group (mouse-click, touchscreen press), that will launch the picture or video for viewing.\
Priority: 1

10. Users can jump between different map-groups through a GUI.\
Priority : 1

11. Administrator users (those who created a map-group) can delegate group-member privileges: invitation, removal, chat-enabled, chat-muted\
Priority: 2

12. User can choose to display only certain layers of flags. e.g: choose to only see one other user’s flags)\
Priority: 2

## Challenges 

Differentiating from other services: This is very similar to Google My Maps

Map generation: This can be a blackbox in the prototype, but could be necessary to design.

1. Handcraft maps for major cities (New York, Tokyo, Delhi . .), or start with Ontario and do the major cities. probably not feasible

2. Basic Custom map generation: scrape google maps or another service, take a static snapshot from the map

3. Third party software or service: connect it to the system as a component

4. Develop more advanced map generation

High volume of users

## Functional requirements or use cases

Probably not necessary for assignment 1

## Nonfunctional requirements

These could be worth mentioning in our presentation

## Priorities

1 = Essential\
2 = Important\
3 = Desirable, not completely necessary

Priority 1 items must be implemented for the system to operate.

Priority 2 items should be implemented, but can be leveraged if needed, and the system will still function.

Priority 3 items can be absent, but would be nice to have and would improve the product.

## Architecture styles

Model-view-controller





