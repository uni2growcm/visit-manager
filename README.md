# Visit Manager - Internship Assignment
---
Implement a web application to visitors and their visits

## Terminology
---
- **Visitor** - A visit belongs to one and only one visitor
- **Visit** - A visitor can have many visits
## Requirements
---
### Frontend
The frontend app should implememt the following features:
- Manage **[visits, visitors]**
- Display a paginated data(particularly visits) with filter support
- Add the possbility to print visits.

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
- The previous schema ist just an minimal schema, then you could complete it if necessary.
- Our tech stack is mostly React.
- You could use a local datasource(for example, by storing data in json files)
- Please provide an instruction on how to deploy the app.
- Submit your solution either as a public repository (github, bitbucket, etc.) or as a zip archive.
