# Healthcare-from-scratch
A healthcare app/web service that provides a lot of services to healthcare providers on the web..

## Tasks:
### first major iteration:
***in no particular order***
- One at a time 
- Build EMR/EHR data models
- build forms and interface for client to manage EHR in realtime 
- build model and web service for medical image analytics engine (MIAE).
- build forms and interface for client to use MIAE
- Add prognosis models.
- Add prognostics model interface for client to use.
- build survival models
- build api endpoints for all the models 
- launch on a web/store and promote.

Second major iteration.
- Add new functionalities..
- insights from data
- other AI additions 
- build data model for the analytics module.






## Research proven infrastructure plan
- app can run on user device so that managing and saving users data would be efficient when there is no internet but once the app is connected it loads whats in its mini storage to the cloud storage for use by the analytics and for protection of data.
- after the analytics engine updates, it would update on the app client side for exploration by subscribers.
- account can be made for groups or individual, individuals would be associated with one group which would govern the uniqueness of everything(data) available to that group.
- Authorization: users would login to app before having access to minimal data.
- Authorization 2: app would determine if they have group's subscription is good and give access to major functionalities of the app.
- step functions to use lambda/or other alternatives 