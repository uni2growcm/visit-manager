# Visit Manager - Assignment
---
Implement a web application to manage visitors' visits in a company

## Terminology
---
- **Visitor** - A visitor can have many visits
- **Visit** - A visit belongs to one and only one visitor
## Requirements
---
The web app should implememt the following features:
- Manage **[visits, visitors]**
- Display a paginated data(particularly visits) with filter support
- Add a dashboard to show some statistic about the visits (visits per day, per week, per month, per day period (moring/afternoon), etc)

## Minimum entities Schema
---
### Visit
-  purpose : a string representing the visit purpose
-  date : a date time representing the visit record date
-  departureDate : a date time representing  the visit departure date
-  visitor : a Visitor object representing the visitor
-  user : a User object representing the user.
### Visitor
-  firstName : a string representing the first name of the visitor 
-  last Name : a string representing the first name of the visitor 
-  email : a string representing the email address of the visitor 
-  phone : a string representing the phone number of the visitor 
-  address : an nullable Address  object representing the address of the visitor

## Notes
- The previous schema ist just a minimal schema, then you could complete it if necessary.
- Our tech stack is mostly React/Angular for front-end, Spring Boot for the backend.
- Please provide an instruction on how to deploy the app.
- Submit your solution either as a public repository (recommended) or as a zip archive.
