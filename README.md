# Visit Manager - Internship Assignment
---
Implement a REST service and a web application to visitors and their visits

## Terminology
---
- **Visitor** - A visit belongs to one and only one visitor
- **Visit** - A visitor can have many visits
## Requirements
---
### Backend
The service should implement the following fonctionalities:
- Create **[Visit, Visitor]**
- Update **[Visit, Visitor]**
- Delete **[Visit, Visitor]**
- Get all/paginated/partially(search, filter) **[visits, visitors]**

### Frontend
The frontend app should implememt the following features:
- Manage **[visits, visitors]** according to provided service(backend)
- Display a paginated data(particularly visits) with filter support
- Add the possbility to print visits.

## Minimum entities Schema
---
### Visit
-  purpose : a string representing the visit purpose
-  date : a date time representing the visit record date
-  departureDate : a date time representing  the visit departure date
### Visitor
-  firstName : a string representing the first name of the visitor 
-  last Name : a string representing the first name of the visitor 
-  email : a string representing the email address of the visitor 
-  phone : a string representing the phone number of the visitor 
-  address : an nullable Address  object representing the address of the visitor

## Notes
- The previous schema ist just an minimal schema, then you'll need to complete it.
- Our tech stack is mostly Java with Spring framework and React for front-end.
- Please create a 'production-ready' service as you see it (documentation / tests / logs / exception handling).
- Please provide an instruction on how to run the app.
- Submit your solution either as a public repository (github, bitbucket, etc.) or as a zip archive.
